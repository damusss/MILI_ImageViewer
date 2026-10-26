![Unmaintained](https://img.shields.io/badge/Status-Unmaintained-orange)

> [!WARNING]
> `MILI_ImageViewer` was created as a small demo application to showcase `mili-ui` but is not up to date to the most recent version and there's no plan to update it.

# Image Viewer

Run from source the image viewer:
```shell
pip install -r requirements.txt
python ImageViewer.py
```
Build the image viewer:
```shell
pip install pyinstaller
pip install -r requirements.txt
pyinstaller --onefile ImageViewer.py
start dist/ImageViewer.exe
```
