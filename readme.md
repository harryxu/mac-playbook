# MacOS provision


## Prerequirements.

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install pipx
pipx install --include-deps ansible

```

## Installing
```
ansible-galaxy install -r requirements.yml
ansible-playbook main.yml --ask-become-pass
```