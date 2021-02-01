# HealthCare

This project is trying to detect diabetic retinopathy using CNN. This was one of the competition held on Kaggle. This uses Werkzeug, Flask, numpy, Keras, gevent, pillow, h5py and tensorflow and few other packages. 

To use Google Colab with Kaggale API, follow below steps. 

! pip install -q kaggle
from google.colab import files
files.upload() # download the JSON activation file from you kaggle account and upoload it here 
! mkdir ~/.kaggle
! rm ~/kaggle/kaggle.json
! cp kaggle_1.json kaggle/
! chmod 600 kaggle/kaggle.json
! kaggle datasets list
!kaggle competitions download -c diabetic-retinopathy-detection
 
