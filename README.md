**This is the instruction for Filtering/Fourier not the object detection!**
1) Install Python Dependencies: https://www.python.org/downloads/
2) You can either clone repo or go to "Code" and download the zip file
3) In the HPF+FOURIER file, make sure to change the filename or directory to filter/show the frequency representation
4) Have fun!

   
**Follow these instruction for object detection!**
1) Install Anaconda: https://docs.anaconda.com/free/anaconda/install/index.html
2) Install Python Dependencies: https://www.python.org/downloads/
3) Clone this repository
```
git clone https://github.com/letreetop/CVCapstone.git # clone
```
4) CD into your repo and create a conda environment and type "y" to install dependencies
```
conda create --name "whatever" python="version ex 3.8 etc...."
```
5) Then you want to activate the conda environment
```
conda activate "whatever"
```
6) Install pip requirements
```
pip install -r requirements.txt
```
7) You can detect! In your terminal you can use this command to detect anything
```
!python detect.py --source "image or video datapath" --weights "weights you want to choose, ex: yolov5l.pt, 300epoch.pt, double.pt etc" --classes "you can choose what class you want to see
   
