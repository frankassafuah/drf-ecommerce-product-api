# Commands

python manage.py shell
from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())

<!-- environment variable -->
from dotenv import load_dotenv
import os

load_dotenv()