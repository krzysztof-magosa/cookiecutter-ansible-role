# {{ cookiecutter.name }}

[![Build Status](https://travis-ci.org/{{ cookiecutter.github_user }}/{{ cookiecutter.github_repo }}.svg?branch=master)](https://travis-ci.org/{{ cookiecutter.github_user }}/{{ cookiecutter.github_repo }})

## Description
{{ cookiecutter.description }}

## Supported Ansible versions
{% for version in cookiecutter.ansible_versions %}
* {{ version }}
{% endfor %}

## Supported systems
* CentOS (tested on 8, 7)
* Debian (tested on 11 Bullseye, 10 Buster)
* Ubuntu (tested on 19.04 Disco Dingo, 18.04 Bionic Beaver)

## Variables
See [defaults](defaults/main.yml).

## License
Licensed under [{{ cookiecutter.license }}](LICENSE.txt).
