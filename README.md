# OCR-Image Text Extracting

[![Total Downloads](http://poser.pugx.org/shababsoftwares/ocr-text-recognition/downloads)](https://packagist.org/packages/shababsoftwares/ocr-text-recognition)
[![Downloads](https://poser.pugx.org/ShababSoftwares/OCR-Text-Recognition/d/total.svg)](https://github.com/ShababSoftwares/OCR-Text-Recognition)
[![License](https://poser.pugx.org/ShababSoftwares/OCR-Text-Recognition/license.svg)](LICENSE.md)

This is simple PHP Code using Tesseract-OCR to read and extract Text in any Image.

## How to Install Tesseract-OCR

You need to have Tesseract-OCR installed and set Environment.
    
### On Window 10,11

Installation guide on this link <a href="https://ironsoftware.com/csharp/ocr/blog/ocr-tools/tesseract-ocr-windows/" target="_blank">How to install tesseract ocr on window</a>

Install Tesseract-OCR 
Edit Path under Environment System variables 
add new path
    `%InstalationPath%/Tesseract-OCR`
like
    `C:\Program Files (x86)\Tesseract-OCR`
    
Add New Variable under System variables
Variable Name: `TESSDATA_PREFIX`
Variable Value: `%InstalledPath%/Tesseract-OCR` // C:\Program Files (x86)\Tesseract-OCR\

### On Linux / ubuntu

Step 1 : Update your system
Begin the installation process by updating the APT Index.
```bash
    sudo apt update
```

Step 2 : Add Tesseract OCR 5 PPA to your system.
To add the Tesseract OCR 5 PPA to your system, run the command below
```bash
    sudo add-apt-repository ppa:alex-p/tesseract-ocr-devel
```
Step 3 : Install Tesseract on Ubuntu
Run the command :
```bash
    sudo apt install -y tesseract-ocr
```
Once installation is complete update your system
```bash
    sudo apt update 
```
Confirm the Tesseract version installed.
```bash
    $ tesseract --version
```

## Set Path of Image and Output text file.

    shell_exec('"C:\\Program Files (x86)\\Tesseract-OCR\\tesseract" "C:\\xampp\\htdocs\\OCR-Text-Recognition\\images\\'.$file_name.'" out');
    
## License

The MIT License (MIT). Please see [LICENSE](LICENSE.md) for more information.

## Shabab Softwares

<p align="center"><a href="https://www.shababsoftwares.com" target="_blank">www.shababsoftwares.com</a></p>

Shabab Softwares (c) 2024