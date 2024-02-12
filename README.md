# Barcode Tags

![Badge](https://img.shields.io/static/v1?label=author&message=DanielHessel&color=0070f3&style=flat&logo=<LOGO>)
![Badge](https://img.shields.io/static/v1?label=status&message=Done&color=success&style=flat&logo=<LOGO>)
![Badge](https://img.shields.io/static/v1?label=license&message=MIT&color=0070f3&style=flat&logo=<LOGO>)

A simples API using Python and Flask to generate barcode tags.

## :pushpin: Table of contents

<!--ts-->

- [Technologies](#zap-technologies)
  - [Code standards](#balloon-code-standards)
- [Getting started](#computer-getting-started)
- [How to run](#information_source-how-to-run)
  - [How to run test](#heavy_check_mark-how-to-run-tests)
- [How to contribute to the project](#tada-how-to-contribute-to-the-project)
- [License](#page_facing_up-license)

<!--te-->

## :zap: Technologies

This project was developed with the following technologies:

- [Python](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/en/3.0.x/)
- [Python Barcode](https://python-barcode.readthedocs.io/en/stable/)
- [Pytest](https://docs.pytest.org/en/8.0.x/)
- [Cerberus](https://docs.python-cerberus.org/)

### :balloon: Code standards

- [Pylint](https://pylint.readthedocs.io/en/stable/)

## :computer: Getting started

Before you begin, you will need to have the following tools installed on your
machine:

- [Git](https://git-scm.com)

- [Python 3.10.12](https://www.python.org/) or heigher.

Also, it’s good to have an editor to work with the code like
[VSCode](https://code.visualstudio.com/).

## :information_source: How to run

Follow the instructions below to download and use the project from this
repository:

> You can use yarn or npm as package manager to run this project, but preferably
> I use npm.

Clone this repository using SSH:

```bash
git clone git@github.com:danielhessell/barcode-tags.git
```

Go to project folder in terminal/cmd:

```bash
cd barcode-tags
```

Create virtual environment:

```bash
python3 -m venv .venv
```

Initialize virtual environment(on linux):

```bash
. .venv/bin/activate
```

Install dependencies(from requirements.txt):

```bash
pip3 install -r requirements.txt
```

Run project:

```bash
python3 run.py
```

The server will start on port 8080. Go to http://localhost:8080.

<details>
<summary>More commands</summary>

To save new installed dependencies `.venv/bin/pip3 freeze > requirements.txt` or
`pip3 freeze > requirements.txt`.

</details>

### :heavy_check_mark: How to run tests

This project has unit and integration testing. Run `pytest` or `pytest -s -v`(to
show coverage and details).

## :tada: How to contribute to the project

1. Fork the project
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save the changes and create a commit message telling what you've done:
   `git commit -m "feature: My new feature"`
4. Submit your changes: `git push origin my-feature`

Caso tenha alguma dúvida confira este
[guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions).

## :page_facing_up: License

This project is under the MIT license. See the
[LICENSE](https://github.com/danielhessell/barcode-tags/blob/master/LICENSE)
file for more details.

---

Made by Daniel Hessel.
