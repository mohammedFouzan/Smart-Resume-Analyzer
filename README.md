# Smart Resume Analyzer Application

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.8]   


## Source
- Extracting user's information from the Resume, I used [PyResparser](https://omkarpathak.in/pyresparser/)
- Extracting Resume PDF into Text, I used [PDFMiner](https://pypi.org/project/pdfminer/).

## Features
- User & Admin Section
- Resume Score
- Career Recommendations
- Resume writing Tips suggestions
- Courses Recommendations
- Skills Recommendations
- Youtube video recommendations

## Usage
- Open CMD in working directory.

- Run following command
  ```
  pip install -r requirements.txt
  ```
- Downloads necessary libraries

- `App.py` is the main Python file of Streamlit Web-Application. 

- `Courses.py` is the Python file that contains courses and youtube video links.

- Download XAMPP or any other control panel, and turn on the Apache & SQL service.

- To run app, write following command in CMD. or use any IDE.
  ```
  streamlit run App.py
  ```

- `Uploaded_Resumes` folder contains the user uploaded resumes.
