CCTV Camera Object tracking and Detection


In this project, we detect moving objects in a video from a CCTV camera. The camera will be in a fixed position and does not move. We will do the following: Estimate the background with median filering remove the background from a picture Blurring and thresholding techniques Detection of countours and  implement object_tracking.
## Screenshots

## 🛠 Skills
Python,OpenCv


## Installation

Install my-project with npm

```bash
  npm install OBJECT-DECTECTION-AND-TRACKING
  cd OBJECT-DECTECTION-AND-TRACKING

SETTING UP A VIRTUAL ENVIRONMENT
  python3 -m venv 
  envsource env/bin/activate

pip install opencv-python
``` 

 
## Methods implemented
Thresholding

method was used to determine the point of transition in the images. A transition is a change of pixel value which is necessary to eventually determine edges.
We use it  to focus on objects areas of interest in an image.




Blurring 

is usually a precursor to more advance techniques like edge detection 

Edge Detection

was needed to detect objects in a picture. 

Contour identification and
Bounding box creation

## Acknowledgements
CloudxLab
pysource