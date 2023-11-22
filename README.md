E-Learning platform
--------------------

The E-learning platform allows instructors to create courses containing text, images, videos, and files. Students can enroll in courses after creating an account on the platform. Each course contains a chat room  for discussions or comments.

To run the project locally: clone this repository on your computer

```
    cd  #to your preferred directory
    git clone https://github.com/isaacmain254/E-learning.git
    cd E-learning
```

create a virtual environment and install all packages from **requirements.txt**.

 Make sure you are in the `$ ... E-learning ` directory

```python
    #create a virtual environment
    python -m venv venv

    #Activate the virtual environment, for Linux users
    # For Windows users search on how to activate a virtual environment
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
