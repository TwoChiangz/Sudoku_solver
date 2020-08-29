# Sudoku_solver
Using image processing to solve sudoku boards pull original from https://github.com/CVxTz/sudoku_solver. 

## First Run
```
pipenv shell
pip install streamlit
pip install matplotlib
pip install opencv-python
pip install scikit-image
pip install imgaug
pip install tensorflow
bash run_app.sh
```

## After dependencies
```
streamlit run app.py
```

## Errors
libgcc_s.so.1 must be installed for pthread_cancel to work
Aborted (core dumped)
Fixed - moved import cv2 into functions that use cv2
moved import imgaug.augmenters as iaa into functions that use iaa

W tensorflow/stream_executor/platform/default/dso_loader.cc:59] Could not load dynamic library 'libcudart.so.10.1'; dlerror: libcudart.so.10.1: cannot open shared object file: No such file or directory
2020-08-03 16:58:13.376368: I tensorflow/stream_executor/cuda/cudart_stub.cc:29] Ignore above cudart dlerror if you do not have a GPU set up on your machine.
Install bazel https://docs.bazel.build/versions/master/install-ubuntu.html
```
pip install -U pip six 'numpy<1.19.0' wheel setuptools mock 'future>=0.17.1'
pip install -U keras_applications --no-deps
pip install -U keras_preprocessing --no-deps

```
