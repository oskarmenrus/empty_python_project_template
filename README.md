# It's just template-folder with start files for your project.

## This empty project include next files:

* dist - folder with packaged project files;
  * remove_this_empty_project_archive.tar.gz - the name speaks for itself;
* project_name  - main folder for your project;
  * __ init __.py - file with project version and some imports etc.;
  * project_name.py - main python file;
* .gitignore - this file needed to ignore some files, when git using;
* .pypirc - configuration file to upload your project in pypi.org;
* LICENSE - file with most popular MIT license;
* MANIFEST.in - configuration file for including different files in your project;
* README.md - file with some documentation or description, like this etc.;
* requirements.txt - file with some requirements, generated by 'pip freeze > requirements.txt';
* setup.py - start 'python setup.py sdist' to pack your project in *.tar.gz.
