# Custom-Object-Detection-Using-Darkflow-Simplified
This is a very simplified repository for custom object detection .If you want to just apply custom object detection using YOLO this is the best that you can get .It requires no prior Knowledge. So gear up and enjoy.

# Steps 
  - Setting up for installing tensorflow-gpu (if your GPU supports CUDA)
  - Image gathering 
  - Image annotation
  - Setting up environment
  - Setting up darkflow
  - File editing in Darkflow folder
  - Training
  - Predicting 
# Setting up for installing tensorflow-gpu (skip if you already have)
    
   
   This step is the most time taking step as during this step anyone can face lot of errors.So I will try my best to give you steps so that    you will not encounter any error.
   Note -- Install all the package and dependencies version same as give below to avoid any error.
   
   - First of all check your GPU is compatible with CUDA or not ?
   
     [CUDA comapatible GPUs](https://developer.nvidia.com/cuda-gpus)
   - Then install anaconda cloud.  [from here](https://www.anaconda.com/distribution/) 
     Note - while installing anaconda check"the anaconda add on my PATH variable"
     ![alt text](https://github.com/Boltuzamaki/Custom-Object-Detection-Using-Darkflow-Simplified-/blob/master/images%20support%20file/anaconda.PNG)
   - Then install Cuda Toolkit 9 [from here](https://developer.nvidia.com/cuda-90-download-archive).
     Download Base installer
   - After then download Visual studio 19 [from here](https://visualstudio.microsoft.com/downloads/).Download community version.
    After installing it go to modify option and select "Desktop development with c++" and modify.You only need to download this 
    because it supports CUDA.
    ![alt text](https://github.com/Boltuzamaki/Custom-Object-Detection-Using-Darkflow-Simplified-/blob/master/images%20support%20file/2.PNG)
    
   - Download cuDNN version which is latest and supported by CUDA 9. [from here](https://developer.nvidia.com/rdp/cudnn-archive).
     and then extract it.
     It has three folders bin,include,lib we have to add this location to path variable.
     For this,
     go to This PC->Properties ->Advance system setting -> Environment Variables ->Path 
     Then add location of all the three folders of cuDNN.
     
     This will look something like this
     ![alt text](https://github.com/Boltuzamaki/Custom-Object-Detection-Using-Darkflow-Simplified-/blob/master/images%20support%20file/3a.png?raw=true)
     
     - At last install tensorflow-gpu.
        **pip install --ignore-installed --upgrade tensorflow-gpu**
     
     
     
    
    
    
    
      
     
   -  
 
     
     
   
   


  
