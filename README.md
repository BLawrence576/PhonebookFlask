"Ran through code along until Flask Phonebook 4.3 – Virtual Environments"

###

Error: While importing 'app', an ImportError was raised:

Traceback (most recent call last):
  File "C:\Users\Genos\Documents\Coding Temple\flask\Phonebook\.venv\Lib\site-packages\flask\cli.py", line 218, in locate_app
    __import__(module_name)
  File "C:\Users\Genos\Documents\Coding Temple\flask\Phonebook\app\__init__.py", line 4, in <module>
    from .authentication.routes import auth
  File "C:\Users\Genos\Documents\Coding Temple\flask\Phonebook\app\authentication\routes.py", line 2, in <module>
    from models import User, db, check_password_hash
  File "C:\Users\Genos\Documents\Coding Temple\flask\Phonebook\models.py", line 6, in <module>
    from flask_login import UserMixin
  File "C:\Users\Genos\Documents\Coding Temple\flask\Phonebook\.venv\Lib\site-packages\flask_login\__init__.py", line 16, in <module>
    from .login_manager import LoginManager
  File "C:\Users\Genos\Documents\Coding Temple\flask\Phonebook\.venv\Lib\site-packages\flask_login\login_manager.py", line 24, in <module>
    from .utils import (login_url as make_login_url, _create_identifier,
  File "C:\Users\Genos\Documents\Coding Temple\flask\Phonebook\.venv\Lib\site-packages\flask_login\utils.py", line 13, in <module>
    from werkzeug.security import safe_str_cmp
ImportError: cannot import name 'safe_str_cmp' from 'werkzeug.security' (C:\Users\Genos\Documents\Coding Temple\flask\Phonebook\.venv\Lib\site-packages\werkzeug\security.py)

PS C:\Users\Genos\Documents\Coding Temple\flask\Phonebook>

###
