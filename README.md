
# Face and Eye Detection System


This Face and Eye Recognition System utilizes OpenCV to detect faces and eyes in real-time from a webcam feed. The system employs Haar cascades for efficient object detection, drawing rectangles around identified faces in blue and eyes in green. It continuously captures frames, converting them to grayscale for analysis, and displays the results in a window.
## Run Locally

Install Python 3.10.0

https://www.python.org/downloads/release/python-3100/


Clone the project

```bash
  git clone https://github.com/chamoddissanayake/Face-and-Eye-Detection-System.git
```

Install dependencies

```bash
  pip install -r requirements.txt
```

If your device has multiple cameras, change camera id in here

```bash
  cap = cv2.VideoCapture(0)
```

Run the Application

```bash
  python face_detection_realtime.py
```
## Tech Stack

**Programming Language:**
* Python

**Libraries/Frameworks:**

* OpenCV: For computer vision tasks and image processing.
* NumPy: For numerical operations and array manipulations.

**Development Environment:**

* IDEs: PyCharm, Visual Studio Code, or Jupyter Notebook.

**Hardware:**

* Webcam: For capturing video input.


**Operating System:**

* Windows, macOS, or Linux (any OS that supports Python and OpenCV).