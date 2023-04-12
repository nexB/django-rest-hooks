Forked from zapier/django-rest-hooks

CHANGES
-------

- Add missing migration file: 0003_alter_hook_user.py
- Fix the TypeError: Signal.__init__() got an unexpected keyword argument 'providing_args'
- Upgrade version to 1.6.1

BUILD
-----

    $ python3 -m venv .
    $ source bin/activate
    $ pip install wheel Django requests
    $ rm -rf dist/ build/
    $ python setup.py bdist_wheel
