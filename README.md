celery
======
- creates a `celery` user
- creates a working dir
- installs init scripts
- installs config files

Role Variables
--------------
| Variable | Description | Default value |
|----------|-------------|---------------|
|`celery_app`| Import path of the Celery app | `none` |
|`celery_virtualenv`| Virtualenv where Celery is installed | `{{ python_virtualenvs_dir }}/celery` |
|`celery_work_dir`| Celery's working dir | `/opt/celery` |

Dependencies
------------
- [python](https://github.com/LucianU/ansible-python)

License
-------
BSD
