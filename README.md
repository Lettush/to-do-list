# Installation #
Steps to try this:
<br>

    git clone https://github.com/Lettush/to-do-list.git
    cd to-do-list
    virtualenv -p python3.8 venv
    source venv/bin/activate
    pip install -r requirements.txt
    python manage.py migrate
    python manage.py runserver # starts the server
    
# Requirements #
- Python 3.8+
- Django 3.1.6

See [requirements.txt](https://github.com/Lettush/to-do-list/blob/master/requirements.txt) for more information.
