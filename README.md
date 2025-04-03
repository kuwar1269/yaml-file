# yaml-file
YAML Student App
================

A simple Python application that reads student information from a YAML file and allows users to view and filter students based on their GPA.

Features
--------

-   Read student data from a YAML file.

-   Display all students.

-   Filter students based on a minimum GPA value entered by the user.

Prerequisites
-------------

Ensure you have the following installed:

-   Python 3.x

-   pip (Python package manager)

Installation
------------

### 1\. Clone the Repository

```
git clone https://github.com/kuwar1269/yaml-file.git
cd yaml-file

```

### 2\. Create a Virtual Environment (Optional but Recommended)

```
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate    # On Windows

```

### 3\. Install Dependencies

```
pip install -r requirements.txt

```

Usage
-----

### 1\. Run the Application

```
python app.py

```

### 2\. Expected Output

```
All Students:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Bob, Age: 22, Major: Mathematics, GPA: 3.5
...

Enter minimum GPA to filter students: 3.6

Students with GPA >= 3.6:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
...

```

File Structure
--------------

```
├── yaml-file/
│   ├── students.yaml  # YAML file with student data
│   ├── app.py         # Python script
│   ├── requirements.txt  # Dependencies
│   ├── README.md      # Documentation

```

Contributing
------------

Feel free to fork the repository and submit pull requests.

License
-------

This project is open-source and available under the [MIT License](https://chatgpt.com/c/LICENSE).
