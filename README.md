# XBRL Taxonomy License File Creator

## :newspaper: About the project

A small commandline tool that allows the user to create a license file template like in `lics/filebasename 3.3 XBRL Taxonomy - Third party Software License Approval Form YYYYMMDD.docx`.

### Content overview

    .
    ├── img/ - folder where all the images can be found for the application
    ├── lics/ - folder where the license files are generated into
    ├── Constants.py - contains all constants for the program
    ├── gen_lic_approval.py main program and code designing and generating the file
    ├── README.md - relevant information about the project
    ├── LICENSE - license text
    └── requirements.txt - requirements to run the project

## :runner: Getting started

### Prerequisites and example usage

1. Install relevant requirements

```sh
pip3 install -r requirements.txt
```

2. Run the script with parameter of you choice. E.g.:

```sh
python3 gen_lic_approval.py -family='eba' -version="3.2"
```

## :books: Resources used to create this project

* Python
  * [Python 3.11 documentation](https://docs.python.org/3.11/)
  * [Built-in Functions](https://docs.python.org/3.11/library/functions.html)
  * [Python Module Index](https://docs.python.org/3.11/py-modindex.html)
* Markdwon
  * [Basic syntax](https://www.markdownguide.org/basic-syntax/)
  * [Complete list of github markdown emofis](https://dev.to/nikolab/complete-list-of-github-markdown-emoji-markup-5aia)
  * [Awesome template](http://github.com/Human-Activity-Recognition/blob/main/README.md)
  * [.gitignore file](https://git-scm.com/docs/gitignore)
* Editor
  * [PyCharm Community Edition](https://www.jetbrains.com/pycharm/)

## :bookmark: License

This project is licensed under the terms of the [GPL v3](LICENSE).
