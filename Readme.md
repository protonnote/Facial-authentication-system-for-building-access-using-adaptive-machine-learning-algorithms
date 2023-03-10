
# Facial authentication system for building access using adaptive machine learning algorithms #

- For Back-end repository : [Back End repository](https://github.com/protonnote/backend-graduate-project.git).

## Installation 
- **OpenCV on Raspberry Pi**
    1. Open Terminal.
    2. Use command :``sudo git clone https://github.com/freedomwebtech/raspbianlegacy.git 
   ``.
    3. Use command : ``cd raspbianlegacy``.
    4. Use command : `` sudo chmod 775 install.sh ``.
    5. Use command `` sudo ./install.sh `` and wait untill success (~ 2 hours).
    6. After install complete use `` python3 `` command in Terminal and type
    >  \>>import cv2 \
    > \>>cv2.__version __
    7. If install success it will show version of OpenCV eg. ``4.5.2``.

- **TensorFlow lite on Raspberry Pi**
    1. Open Terminal.
    2. Use command : ``sudo git clone https://github.com/freedomwebtech/raspbianlegacy.git ``.
    3. Use command : `` cd raspbianlegacy ``.
    4. Use command : `` sudo chmod 775 tensorflow-lite.sh ``.
    5. Use command : `` sudo ./tensorflow-lite.sh `` and wait untill success.
    6. After install use command : `` pip show tensorflow ``.
    7. If install success it will show version of TensorFlow.

- **Mediapipe library on Raspberry Pi**
    1. Open Terminal.
    2. Use command : `` sudo apt update ``.
    3. Use command : `` sudo pip3 install mediapipe-rpi4 `` and wait untill success.
- **TKinter on Raspberry Pi**
    1. Open Termenal.
    2. Use command : `` sudo apt update ``.
    3. Use command : `` sudo pip3 install tk `` and wait untill success.
# Usage
After use `` git clone `` command for download this repository.
1. Open Terminal.
2. Use command : `` cd Front-end ``.
3. Edit ``url`` Back-end-ip.
```python
import json
from os import path
import requests

url = "http://Back-end-ip:5000/file-upload" <------- edit url
filename = 'response.json'

```
4. Use command : `` python main_ui.py `` for start program.