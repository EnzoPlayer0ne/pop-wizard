# Pop-wizard

This repository is used to manage my Pop!\_OS machine.
The idea was taken from [geerlingguy's mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook).

## Quickstart

    git clone git@github.com:Nequo/pop-wizard.git
    cd pop-wizard
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ansible-playbook main.yml --ask-become-pass
