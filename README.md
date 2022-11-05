# Install the docker with ansible

```console
$ pipenv install
$ pipenv shell

$ ansible-galaxy install -r ./requirements.yml
$ ansible-playbook ./deployment/playbook.yml --ask-become-pass
```
