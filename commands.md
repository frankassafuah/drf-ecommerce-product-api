# Commands

python manage.py shell
from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())

<!-- environment variable -->
from dotenv import load_dotenv
import os

load_dotenv()


<!-- copy installed packages to requirements.txt -->

pip freeze > requirements.txt

<!-- install required packages from requirements.txt -->

pip install -r requirements.txt