# Virtualenv

Virtualenv python on linux.

### Use

Create a virtualenv:
```
virtualenv $new_project
```

Set different python version for create virtualenv:
```
virtualenv -p `which python3` $new_project

virtualenv --p=/usr/local/bin/python3 $new_project

python3 -m virtualenv $new_project
```

Activate venv:
```
source $new_project/bin/activate
```

Deactivate venv:
```
deactivate
```

Upgrade pip in virtualenv
```
./bin/python -m pip install --upgrade pip
```
