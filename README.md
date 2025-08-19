# python-requirements-generator
=============================

Scans all Python files recursively in a directory and prints all imports that are needed, that are not installed

Download the file<br />
RUN: python python_requirements_generator.py \<FULL FOLDER PATH\><br />
Note: Absolute path wont work<br />
EXAMPLE: python python_requirements_generator.py /home/johndoe/myapplicationcode<br />
Works with python 2.6, 2.7, 3.0

Sample Output
```bash
2014-12-02::16:06:08 GENERATING REQUIREMENTAS
2014-12-02::16:06:08 REQUIREMENTS :
					ast
					datetime
					flask
					glob
					importlib
					json
					logging
					mandrill
					os
					passlib
					prettytable
					pudb
					pymongo
					pytz
					random
					requests
					string
					sys
					time
					validate_email
					xml
2014-12-02::16:07:02 CHECKING WHETHER REQUIREMENTS ARE ALREADY INSTALLED
2014-12-02::16:07:02 REQUIREMENTS TO BE INSTALLED :
							prettytable
```

## TODO:
- [ ] support python 3.13.x
- [ ] support from x.a.b import y as z
- [ ] debug
