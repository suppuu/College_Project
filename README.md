"#Online-Discussion-Forum" 


1. Install VirtualEnv Wrapper
	* For Windows:
		`pip install virtualenvwrapper-win`
	* For Unix:
		`pip install virtualenvwrapper`

2. Virtual environment
	
	> This creates a new virtual environment and automatically activates it
	`mkvirtualenv college_project_2021`

	> To deactivate
	`deactivate college_project_2021`

	> To again enter the environment
	`workon college_project_2021`

3. Download the application provided and install all the requirements

	> Activate virtual enviroment
	`workon college_project_2021`

	> Install all the required libraries
	`pip install -r requirements.txt`

4. Now navigate to 'Online Discussion Forum' folder

	`cd Online Discussion Forum`

5. Prepare application database

	> Setup database
	`python manage.py migrate`

	

6. Run Application

	`python manage.py runserver`

7. Create superuser to run admin panel
	'python manage.py createsuperuser

8. You can register yourself and login

9.To view account

	url: localhost/account/user_id---eg: localhost/account/1----if it doesnt work, add slash at last
10. Features:
	you can send friend request
	you can cancel friend request
	you can add friend request
	you can decline friend request
	you can accept friend request
	you can update your profile
	you can crop image while updating profile picture.