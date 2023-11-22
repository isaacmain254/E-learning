E-Learning platform
--------------------

The E-learning platform allow instructors to create courses containing text, images, vidoes and files. Students can enroll to courses after creating an account on the platform. Each course contains a chat room  where for discussions or comments .

To run the project locally: clone this repository on your computer

```
    cd  #to your preferred directory
    git clone https://github.com/isaacmain254/E-learning.git
    cd E-learning
```

create a virtual environment and install all packages from **requirements.txt**.

 Make sure your are in `$ ... E-learning ` directory

```python
    #create virtual enviroment
    python -m venv venv

    #Activate the virtual environment, for linux users
    #for windows users search on how to activate virtual enviroment
    source venv/bin/activate

    pip install -r requirements.txt
```

Next makemigrations

```python
    #makemigrations
    python manage.py makemigrations

    #migrate
    python manage.py migrate

    #create a super user
    python manage.py createsuperuser
    
    #start the development server
    python manage.py runserver
```
