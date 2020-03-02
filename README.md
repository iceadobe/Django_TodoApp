# Running the application


```shell
#clone the repository
git clone https://github.com/iceadobe/Django_TodoApp.git
#create a virtual environment
virtualenv env --no-site-packages
#activate the virtual environement
source ./env/scripts/activate
#install the dependencies
pip install -r requirements.txt
#migrate the project to this system
python manage.py migrate
#run the server
python manage.py runserver

```
