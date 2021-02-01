# HealthCare

Aim of this project is to detect diabetic retinopathy using CNN. This was one of the competitions held on Kaggle. This uses Werkzeug, Flask, numpy, Keras, gevent, pillow, h5py and tensorflow and few other packages.

Download the source data from https://www.kaggle.com/c/diabetic-retinopathy-detection/data


To use Google Colab with Kaggale API, follow below steps. 

! pip install -q kaggle<br>
from google.colab import files<br>
files.upload() # download the JSON activation file from you kaggle account and upoload it here <br>
! mkdir ~/.kaggle<br>
! rm ~/kaggle/kaggle.json<br>
! cp kaggle_1.json kaggle/ <br>
! chmod 600 kaggle/kaggle.json<br>
! kaggle datasets list<br>
!kaggle competitions download -c diabetic-retinopathy-detection<br>
 
