1. #### Train Data

- Smaller CCT images:

  Download train.csv and train_images.zip from [here](https://www.kaggle.com/c/iwildcam-2019-fgvc6/data), and unzip train_images to folder "iWildCam_2019_CCT_images_small/"  (or download Smaller CCT images from [here](https://lilablobssc.blob.core.windows.net/iwildcam2019/iWildCam_2019_CCT_images_small.tar.gz) and unzip it)

- iNat Idaho images (optional):

  Download iNat Idaho images from [here](https://lilablobssc.blob.core.windows.net/iwildcam2019/iWildCam_2019_iNat_Idaho.tar.gz) and unzip it to folder "iWildCam_2019_iNat_Idaho/"

2. #### Test Data

   Download test.csv and test_images.zip from [here](https://www.kaggle.com/c/iwildcam-2019-fgvc6/data), and unzip test_images to folder "test_images/"  (or download Smaller IDFG images from [here](https://lilablobssc.blob.core.windows.net/iwildcam2019/iWildCam_IDFG_images_small.tar.gz) and unzip it)

3. #### Annontation 
   Download Annotation for train and test set from [here](https://lilablobssc.blob.core.windows.net/iwildcam2019/iWildCam_2019_Annotations.tar.gz) and unzip it to folder "iWildCam_2019_Annotations"

4. #### Camera Trap Animals Detection Result
   Download detection bbox results from [here](https://lilablobssc.blob.core.windows.net/iwildcam2019/Detection_Results.tar.gz) and unzip it to folder "bbox/Detection_Results/"
   
   In my method, I first run object detection and crop the bounding box for classification. If you want to classify objects directly, you don't need to download this file.  


