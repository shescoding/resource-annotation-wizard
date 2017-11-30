Tool to annotate resources meant to be published on http://shescoding.org/resources

Resource Annotation Wizard installation notes

1. create virtualenv
	(a) install virtualenv
		https://virtualenv.pypa.io/en/stable/installation/
	(b) install virtualenvwrapper
		https://virtualenvwrapper.readthedocs.io/en/latest/install.html
	(c) create a new environment
		mkvirtualenv resource-wizard
		workon
		https://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html#managing-environments

2. install brew
	/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

	https://brew.sh/
	

3. install Python 3.6.3
	brew install python3
	http://docs.python-guide.org/en/latest/starting/install3/osx/

4. install Django 1.11.7
	pip3 install Django
	https://docs.djangoproject.com/en/1.11/topics/install/#installing-official-release

5. install PostgresQL
	TBD

6. setup the database
	TBD

7. clone the resource-annotation-wizard project

8. start the server
	python3 manage.py runserver 

