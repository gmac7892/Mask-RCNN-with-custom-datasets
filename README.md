# Mask-RCNN-with-custom-datasets
A-Z for using Mask RCNN with your custom dataset

***
## 1. Anaconda Setting
We control our packages by using Anaconda\
You can set your anaconda setting [[here]](https://github.com/gmac7892/Ubuntu-Anaconda-Setting)

    $ conda create -n MRCNN python=3.6 pip
    Proceed ([y]/n)? Select "y"
    $ conda activate MRCNN
    $ conda install –c anaconda git
    $ pip install tensorflow-gpu==1.13.1
    $ pip install keras
    $ pip install numpy scipy cython Matplotlib h5py Pillow scikit-image jupyter pandas
    $ pip install opencv-python ipython
    $ pip install imgaug
***
## 2. Requirment Packages

* labelme [[link]](https://github.com/wkentaro/labelme)
* clodsa [[link]](https://github.com/joheras/CLoDSA)

## 3. Install our Package

    $ git clone https://github.com/gmac7892/Mask-RCNN-with-custom-datasets.git
    
## 4. Usage
make your annotation file(.json) by using labelme
