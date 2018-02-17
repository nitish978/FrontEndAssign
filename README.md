                       Front-end Engineering Assignmen
		   
TO run this software first check the location of Django folder which is installed by pip then run that version of python like 
if you have python3.5

  then the command for terminal is "python3.5 manage.py migrate".
  
otherwise you can directly run python.manage.py migrate
 then run in terminal :-python manage.py makemigrations record
 after that run
            python manage.py sqlmigrate record 0001
	    python manage.py migrate
	    
	    
now to access database first you have to create superuser for this followed below command in your terminal
              python manage.py createsuperuser
	      Username: admin
	      Email address: admin@example.com(enter your email id)
	      then it will ask to set password
	      like:-
	           Password: **********
                  Password (again): *********
     finally it will show 		  
Superuser created successfully.
	           from now you can access my website 
 
  
