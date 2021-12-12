# YSLC2021 C08 JORDAN
## Screenshort
<img src="https://github.com/5hyfilm/yslc2021-c08-jordan/blob/main/images/img1.png">

## How to use
1. Visit to our web app https://yslc2021-c08-jordan.azurewebsites.net/.
2. Type texts from news in the box
3. Click the button.
4. Wait for the result.
---
## How to install
1. Clone or download this [repository](https://github.com/5hyfilm/yslc2021-c08-jordan).
2. Change directory by type ```cd yslc2021-c08-jordan``` in terminal.
3. Create virtualenv by type ```python3 -m venv venv``` in terminal.
4. Activate virtualenv by type ```source venv/bin/activate``` in terminal.
5. Install all requirements by type ```pip3 install -r requirements.txt``` in terminal.
6. Run ```python3 app.py``` in terminal.
7. Open localhost http://127.0.0.1:5000 in your browser.
---
## Requirements.txt
Please edit before install on device.

For Deploy on Linux server
```
torch==1.9.0+cpu
torchvision==0.10.0+cpu
torchaudio==0.9.0
-f https://download.pytorch.org/whl/torch_stable.html
```
For use on macOS and Windows
```
torch==1.9.0
torchvision==0.10.0
torchaudio==0.9.0
```