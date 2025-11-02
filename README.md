# ai-face-detection — minimal demo

This repository is a minimal local demo for a webcam-based facial emotion detection app.

Run locally (tested on macOS/Linux):

1. Create a venv and activate it:

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start the app:

```bash
python app.py
```

4. Open http://127.0.0.1:5000 in your browser and click "Start Emotion Detection".

Notes:
- The server-side video capture uses the local machine's webcam. This will not work on cloud hosts.
- If `face_emotions_model.h5` is large and excluded, see the project writeup for how to provide the model or run a diagnostic.
## EMOTION DETECTOR PROGRAM

This is a Python ML program made with Flask and the Keras Model, used for detecting the emotion displayed in an image, using the OpenCV capture

*this is probably bullshit*

_Written by Adefela_