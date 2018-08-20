# Setup for Xenial 16.04

- [Pytesseract](https://pypi.org/project/pytesseract/)
- [Adding PPA](https://launchpad.net/~alex-p/+archive/ubuntu/tesseract-ocr?field.series_filter=xenial)

```shell
# adding ppa and update
sudo add-apt-repository ppa:alex-p/tesseract-ocr
sudo apt-get update

# install tesseract
sudo apt install tesseract-ocr

# install python wrapper
pip install pytesseract
```