                               *   Front-end Engineering Assignment   *
******************************************************************************************************************************			       
				  
INSTALLTION OF SOFTWARE:-
1.Install python
2.pip install Django
******************************************************************************************************************************
******************************************************************************************************************************
open terminal from expenses folder 
   1."python manage.py migrate".
     or if this is not working then 
       TO run this software first check the location of Django folder which is installed by pip in python folder then run that version of python like 
       if you have python3.5
       "python3.5 manage.py migrate"
  2."python manage.py makemigrations record"
  3."python manage.py sqlmigrate record 0001"
  4 "python manage.py migrate"       
*****************************************************************************************************************************

*****************************************************************************************************************************
now to access database first you have to create superuser for this followed below command in your terminal
             1." python manage.py createsuperuser"
	           Username: admin
	           Email address: admin@example.com(enter your email id)
	                           then it will ask to set password
	           like:-
	           Password: **********
                   Password (again): *********
                   finally it will show 		  
                   Superuser created successfully.
	           from now you can access my website 
		   
*****************************************************************************************************************************

*******************************************************************************************************************************
 to run website run command
        python manage.py runserver
	      then copy this url and run on chrome or mozilla http://127.0.0.1/main
  
