# AI-Robotics-summer-school-2018-Yonsei-University
This is source code for AI Robotics summer class. Inside here are all the source code of knowledge about AI with the state of art algorithms: MLP, SVM, DNN, Faster R-CNN, SSD, YOLO, Time Series seq-to-seq modeling: RNN, LSTM, GRU and Reinforcement Learning
## The 3rd Artificial Intellligent and Robotics Summer School (August 22nd, Wednesday)

### Codes
- [Lab-01: MLP](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-01-MLP)
- [Lab-02: SVM](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-02-SVM)
- [Lab-03: MLP-tf](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-03-MLP-tf)
- [Lab-04: CNN](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-04-CNN)
- [Lab-05: CNN-tf](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-05-CNN-tf.nn)
- [Lab-06: CNN-tf.layers](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-05-CNN-tf.nn)
- [Lab-07: CNN-tf-slim](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-07-CNN-slim)
- [Lab-08: Object Detection: YOLO](https://github.com/yonsei-cilab/yolo-tensorflow)

### Requirements
- tensorflow
- numpy
- matplotlib
- cvxopt
- scipy
- sklearn 
- opencv-python

#### Package download for Windows + python 3.6
1. [here](https://drive.google.com/open?id=1k707gyg--Lb_0uTTmBp7_BsllWR8gofH) download .whl file
2. win+R -> cmd for open a command prompt window.
3. ``` pip install ".whl file download path"  ```   
ex) ```pip install "C:\tensorflow-1.10.0-cp36-cp36m-win_amd64.whl"  ```  
Use the above command to install tensorflow first.
4. After that install files .whl
5. Install three packages as follow
```pip install scipy  ```
6. ``` pip install sklearn  ```
7. ``` pip install matplotlib  ```

> If you downloaded from here, ".whl" files have been modified, so please download again and deleted all existing packages with the following command.  
```pip uninstall numpy tensorflow cvxopt mkl opencv-python```  
And you can install again from step 1 in above.

#### Package download for Windows + python 3.XX
1. ``` pip install tensorflow  ```
2. ``` pip uninstall numpy  ```   
Install tensorflow and delete the existing numpy installed
3. https://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy  
Install numpy+mkl as the python version
``` pip install ".whl file download path"  ```
4. https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv  
Install opencv with the correct version of python
``` pip install ".whl file download path"  ```
5. ``` pip install scipy  ```
6. ``` pip install sklearn  ```
7. ``` pip install cvxopt  ```
8. ``` pip install matplotlib  ```  
> You need to install tensorflow first. Please install tensorflow first.

#### Package download for Ubuntu 16.04
```
$ sudo apt-get install python3-pip python3-dev python-virtualenv python3-numpy python3-tk  
$ sudo pip3 install matplotlib cvxopt scipy sklearn  
$ sudo pip3 install opencv-python tensorflow  
```

### Note
YOLO implementation are simple refactoring of [Peng Zhang's implementation](https://github.com/hizhangp/yolo_tensorflow) for lab.
