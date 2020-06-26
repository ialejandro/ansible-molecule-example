# Molecule: Apache2

## Requirements

* [docker](https://docs.docker.com/engine/install/)
* [vagrant](https://www.vagrantup.com/intro/getting-started/install)
* [pipenv](https://github.com/pypa/pipenv#installation)

## Quick start!

```
git clone git@github.com:ialejandro/ansible-molecule-example.git

# requirements
cd ansible-molecule-example/pipenv
pipenv sync && pipenv shell

# testing
cd ../roles/apache2

# list scenarios
molecule list

# execute scenario
molecule test -s <scenario>
```
