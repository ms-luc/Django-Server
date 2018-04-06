to start:
	python manage.py runserver

to enter the polls index:
	http://127.0.0.1:8000/polls/

to enter admin:
	http://127.0.0.1:8000/admin/

	-login i sent via fb

to edit the sql db:
	python manage.py shell
	commands: https://github.com/miranska/cps847-w18/commit/b88a79e7706088901fc5147994ef9688ff8eddd9

to update/commit sql:
	python manage.py sqlmigrate polls 0001_initial

	- commits, but commits something that doesn't look right

	- 001(initial) and 002 are the sql commands by the commands ran in "python manage.py shell"