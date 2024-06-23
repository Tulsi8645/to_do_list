To start the project, you can clone or download as zip
To start the frontend ,open the terminal, enter the client_side directory , run npm install ; which will insatll node modules along with all packages required.
It is created with create-react-app , npm start; will run the frontend side.




To start the backend , You might need to install a virtual environment . 
pip install virtualenv ;
To create a virtual environment .
vrtualenv myenv;( name your virtual env)
To activate it.
myenv\Scripts\activate
You will enter your virtual environment .

The next step is to install all the requirements 
pip install -r requirements.txt

You need to be in the django_side directory to run the backend
python manage.py runserver;

After running both frontend and backend
To be able to use the App you  need to Register ( make sure to enter a strong password; you will get internal server error if its a common one.)
To log in ,you need to enter your email and passsword .
You will land in a home page after logging in, you have the options to navigate to the dashboard, Todo App or simply Log out .

Inside the Dashboard you will find the details of a registered user. additionally, You can also upload image .

Navigating to the Todo App , you will be Able to create your task, Edit them , delete them and additionaaly view the completed and incomplete ones.


Improvement areas:
The project is created with create-react-app and most of the packages are depricated. You can install a react app with Vite Package manager.
You should not expose the URl endpoints raw, on both the frontend and backend sides it could be placed as environment variable.








