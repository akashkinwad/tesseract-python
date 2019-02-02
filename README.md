# tesseract_with_python
Jupyter notebook code for Tesseract ocr to extract the images to text, box files and hocr files using pytesseract + python

# link to install tesseract on ubantu 16.04
https://www.linuxhelp.com/how-to-install-tesseract-ocr-on-ubuntu-16-04

# install pytesseract using pip
https://pypi.org/project/pytesseract/
    
pip install pytesseract    

# execute from cammand line to get tesseract_cmd location
sudo find / -name "tesseract"

# execute from cammand line to get tessdata_dir_config location
sudo find / -name "tessdata" 

1. Keep all the png files in one folder and replace path with its location
2. Use "" to enhance the dpi of the images
3. It will create the text file, box file and hocr file for the input image and will save in the same directory
