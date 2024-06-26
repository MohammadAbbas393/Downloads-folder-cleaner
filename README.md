
### Downloads folder cleaner

Create this file to provide an overview of your project, including installation, usage, configuration, and license information.

```
# Downloads Folder Cleaner

A Python-based application to organize your Downloads folder by automatically moving files based on their extensions.

## Features
- Automatically organizes files in the Downloads folder.
- Customizable file extensions and destination folders.
- Logs all actions for transparency.
- System tray icon for easy access and notifications.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MohammadAbbas393/Downloads-folder-cleaner.git

2. cd Downloads-folder-cleaner

3. python3 -m venv venv
source venv/bin/activate  # On macOS and Linux

4. pip install -r requirements.txt

5. run the script
 venv/bin/python cleaner.py

```

###  requirements.txt

Ensure this file lists all dependencies required for the project.

```
plaintext
Pillow==9.3.0
pystray==0.19.3

```

### Project

This project is an interactive tool designed to help people organize their downloads folder and preview the results in a cleaner log to see exactly what has been moved. The code allows users to adjust multiple folders such as downloads, desktop, and documents. The trick here is that you need to change the input in the code to specify the category you want to fix. This project is different from others because it not only cleans your folders but also organizes them in the output. In the downloads folder, files are grouped into folders, and within these folders, there are subfolders.

### authors

[@Mohammad Abbas](https://github.com/MohammadAbbas393/)

### Introduction 

As a passionate coder and intern at multiple ITS departments at Middlebury College, including Helpdesk, Digital Learning and Inquiry, and Endpoint Collaboration Services, I develop projects aimed at assisting people. One common issue I observed among clients is disorganized desktop and downloads files. Despite the negative impact it has on computer aesthetics and the time wasted searching for documents, this problem can be easily solved, benefiting users by organizing their folders.

To tackle this issue, I devised an algorithm to effectively organize folders while retaining crucial organizational details. Unlike conventional apps that simply dump files into one folder, my algorithm categorizes files into different folders, each containing specific subfolders for various types of unorganized content identified in the input of the code. The algorithm maintains the same folder structure but optimizes it for better visibility, detail, and time-saving purposes.

### How To Use

1. Clone this repository in your terminal.
2. Make sure to read the README file to understand how to run it.
3. After running it, ensure to close the app from the toolbar to stop the code.
4. [Optional] Check the cleaner log to address all the files you moved.
5. Check your Downloads (output) category, and you will see all the organized folders.

### Demo
https://github.com/MohammadAbbas393/Downloads-folder-cleaner/assets/171047105/5544a6e0-222d-4f43-bc54-b9c8595953cf

## Methods

This project utilizes Python's os and shutil libraries to automate the process of sorting files in the Downloads folder based on their file extensions. The key method involves scanning the directory, identifying file types, and then moving them into pre-defined category folders, ensuring each file type has a corresponding subfolder.

## Results

The script successfully categorized and moved over 200 files during testing, reducing clutter and improving file retrieval times. See the attached results screenshot for a before and after comparison of the Downloads folder.

![result](https://github.com/MohammadAbbas393/Downloads-folder-cleaner/blob/50c008830e575e3f0bcf81142c7923c90625cbe4/results.png)

## Issues

1. Limited to certain file extensions; new types require manual updating of the script.
2. Does not handle duplicate file names in the destination directory, leading to overwrites.


## Improvements

1. Automatic detection of new file types and dynamic folder creation.
2. Implementing a user interface to allow non-technical users to customize settings without editing code.
3. Adding support for duplicate file handling by renaming instead of overwriting.



Support
-------
If you like my work and wish to support it, feel free to buy me a coffee!

<p align="center">
  <a href="https://www.buymeacoffee.com/mohamadabb3">
    <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy me a coffee"/>
  </a>
</p>






