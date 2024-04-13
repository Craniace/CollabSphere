<p align="center">
  <img src="https://img.icons8.com/external-tal-revivo-filled-tal-revivo/96/external-markdown-a-lightweight-markup-language-with-plain-text-formatting-syntax-logo-filled-tal-revivo.png" width="100" />
</p>
<p align="center">
    <h1 align="center">COLLABSPHERE</h1>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/Craniace/CollabSphere?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/Craniace/CollabSphere?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Craniace/CollabSphere?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Craniace/CollabSphere?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat&logo=HTML5&logoColor=white" alt="HTML5">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
</p>
<hr>

## 🔗 Quick Links

> - [📍 Overview](#-overview)
> - [📦 Features](#-features)
> - [📂 Repository Structure](#-repository-structure)
> - [🧩 Modules](#-modules)
> - [🚀 Getting Started](#-getting-started)
>   - [⚙️ Installation](#️-installation)
>   - [🤖 Running CollabSphere](#-running-CollabSphere)
>   - [🧪 Tests](#-tests)
> - [🤝 Contributing](#-contributing)

---

## 📍 Overview

Real-Time Chat Application using Django

---

## 📦 Features

1. **Rooms or Group Chat:** Join various chat rooms for diverse conversations.
2. **User Authentication:** Securely log in to access personalized features.
3. **Security:** Prioritize the safety of your interactions and data.
4. **ChatBot:** Quick assistance with an integrated chatbot.
5. **Dark/Light Mode:** Toggle between modes for a personalized experience.
6. **Responsiveness:** Seamlessly access the chat across different devices.
7. **Interactive GUI:** Engaging graphical user interface.
8. **Contact Us:** Easily reach out for queries or assistance.
9. **Description of Room:** Insights into each chat room's theme and purpose.

---

## 📂 Repository Structure

```sh
└── CollabSphere/
    ├── CollabSphere
    │   ├── README.md
    │   ├── core
    │   │   ├── __init__.py
    │   │   ├── __pycache__
    │   │   │   ├── __init__.cpython-311.pyc
    │   │   │   ├── __init__.cpython-39.pyc
    │   │   │   ├── admin.cpython-311.pyc
    │   │   │   ├── admin.cpython-39.pyc
    │   │   │   ├── apps.cpython-311.pyc
    │   │   │   ├── apps.cpython-39.pyc
    │   │   │   ├── forms.cpython-311.pyc
    │   │   │   ├── forms.cpython-39.pyc
    │   │   │   ├── models.cpython-311.pyc
    │   │   │   ├── models.cpython-39.pyc
    │   │   │   ├── urls.cpython-311.pyc
    │   │   │   ├── urls.cpython-39.pyc
    │   │   │   ├── views.cpython-311.pyc
    │   │   │   └── views.cpython-39.pyc
    │   │   ├── admin.py
    │   │   ├── apps.py
    │   │   ├── forms.py
    │   │   ├── migrations
    │   │   │   ├── __init__.py
    │   │   │   └── __pycache__
    │   │   │       ├── __init__.cpython-311.pyc
    │   │   │       └── __init__.cpython-39.pyc
    │   │   ├── models.py
    │   │   ├── templates
    │   │   │   └── core
    │   │   │       ├── base.html
    │   │   │       ├── frontpage.html
    │   │   │       ├── login.html
    │   │   │       └── signup.html
    │   │   ├── tests.py
    │   │   ├── urls.py
    │   │   └── views.py
    │   ├── db.sqlite3
    │   ├── djangochat
    │   │   ├── __init__.py
    │   │   ├── __pycache__
    │   │   │   ├── __init__.cpython-311.pyc
    │   │   │   ├── __init__.cpython-39.pyc
    │   │   │   ├── asgi.cpython-311.pyc
    │   │   │   ├── asgi.cpython-39.pyc
    │   │   │   ├── settings.cpython-311.pyc
    │   │   │   ├── settings.cpython-39.pyc
    │   │   │   ├── urls.cpython-311.pyc
    │   │   │   └── urls.cpython-39.pyc
    │   │   ├── asgi.py
    │   │   ├── settings.py
    │   │   ├── urls.py
    │   │   └── wsgi.py
    │   ├── manage.py
    │   └── room
    │       ├── __init__.py
    │       ├── __pycache__
    │       │   ├── __init__.cpython-311.pyc
    │       │   ├── __init__.cpython-39.pyc
    │       │   ├── admin.cpython-311.pyc
    │       │   ├── admin.cpython-39.pyc
    │       │   ├── apps.cpython-311.pyc
    │       │   ├── apps.cpython-39.pyc
    │       │   ├── consumers.cpython-311.pyc
    │       │   ├── consumers.cpython-39.pyc
    │       │   ├── models.cpython-311.pyc
    │       │   ├── models.cpython-39.pyc
    │       │   ├── routing.cpython-311.pyc
    │       │   ├── routing.cpython-39.pyc
    │       │   ├── urls.cpython-311.pyc
    │       │   ├── urls.cpython-39.pyc
    │       │   ├── views.cpython-311.pyc
    │       │   └── views.cpython-39.pyc
    │       ├── admin.py
    │       ├── apps.py
    │       ├── consumers.py
    │       ├── migrations
    │       │   ├── 0001_initial.py
    │       │   ├── 0002_message.py
    │       │   ├── 0003_room_description_room_participants.py
    │       │   ├── 0004_alter_room_description.py
    │       │   ├── 0005_remove_room_description_remove_room_participants.py
    │       │   ├── __init__.py
    │       │   └── __pycache__
    │       │       ├── 0001_initial.cpython-311.pyc
    │       │       ├── 0001_initial.cpython-39.pyc
    │       │       ├── 0002_message.cpython-311.pyc
    │       │       ├── 0002_message.cpython-39.pyc
    │       │       ├── 0003_room_description_room_participants.cpython-311.pyc
    │       │       ├── 0004_alter_room_description.cpython-311.pyc
    │       │       ├── 0005_remove_room_description_remove_room_participants.cpython-311.pyc
    │       │       ├── __init__.cpython-311.pyc
    │       │       └── __init__.cpython-39.pyc
    │       ├── models.py
    │       ├── routing.py
    │       ├── templates
    │       │   └── room
    │       │       ├── room.html
    │       │       └── rooms.html
    │       ├── tests.py
    │       ├── urls.py
    │       └── views.py
    └── README.md
```

---

## 🧩 Modules

<details closed><summary>CollabSphere</summary>

| File                                                                                     | Summary                                            |
| ---                                                                                      | ---                                                |
| [manage.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/manage.py) | HTTP error 401 for prompt `CollabSphere/manage.py` |

</details>

<details closed><summary>CollabSphere.room</summary>

| File                                                                                                | Summary                                                    |
| ---                                                                                                 | ---                                                        |
| [admin.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/admin.py)         | HTTP error 401 for prompt `CollabSphere/room/admin.py`     |
| [apps.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/apps.py)           | HTTP error 401 for prompt `CollabSphere/room/apps.py`      |
| [tests.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/tests.py)         | HTTP error 401 for prompt `CollabSphere/room/tests.py`     |
| [views.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/views.py)         | HTTP error 401 for prompt `CollabSphere/room/views.py`     |
| [consumers.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/consumers.py) | HTTP error 401 for prompt `CollabSphere/room/consumers.py` |
| [routing.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/routing.py)     | HTTP error 401 for prompt `CollabSphere/room/routing.py`   |
| [urls.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/urls.py)           | HTTP error 401 for prompt `CollabSphere/room/urls.py`      |
| [models.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/models.py)       | HTTP error 401 for prompt `CollabSphere/room/models.py`    |

</details>

<details closed><summary>CollabSphere.room.templates.room</summary>

| File                                                                                                           | Summary                                                                 |
| ---                                                                                                            | ---                                                                     |
| [room.html](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/templates/room/room.html)   | HTTP error 401 for prompt `CollabSphere/room/templates/room/room.html`  |
| [rooms.html](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/templates/room/rooms.html) | HTTP error 401 for prompt `CollabSphere/room/templates/room/rooms.html` |

</details>

<details closed><summary>CollabSphere.room.migrations</summary>

| File                                                                                                                                                                                                   | Summary                                                                                                           |
| ---                                                                                                                                                                                                    | ---                                                                                                               |
| [0003_room_description_room_participants.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/migrations/0003_room_description_room_participants.py)                             | HTTP error 401 for prompt `CollabSphere/room/migrations/0003_room_description_room_participants.py`               |
| [0001_initial.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/migrations/0001_initial.py)                                                                                   | HTTP error 401 for prompt `CollabSphere/room/migrations/0001_initial.py`                                          |
| [0002_message.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/migrations/0002_message.py)                                                                                   | HTTP error 401 for prompt `CollabSphere/room/migrations/0002_message.py`                                          |
| [0004_alter_room_description.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/migrations/0004_alter_room_description.py)                                                     | HTTP error 401 for prompt `CollabSphere/room/migrations/0004_alter_room_description.py`                           |
| [0005_remove_room_description_remove_room_participants.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/room/migrations/0005_remove_room_description_remove_room_participants.py) | HTTP error 401 for prompt `CollabSphere/room/migrations/0005_remove_room_description_remove_room_participants.py` |

</details>

<details closed><summary>CollabSphere.core</summary>

| File                                                                                          | Summary                                                 |
| ---                                                                                           | ---                                                     |
| [admin.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/admin.py)   | HTTP error 401 for prompt `CollabSphere/core/admin.py`  |
| [apps.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/apps.py)     | HTTP error 401 for prompt `CollabSphere/core/apps.py`   |
| [tests.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/tests.py)   | HTTP error 401 for prompt `CollabSphere/core/tests.py`  |
| [views.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/views.py)   | HTTP error 401 for prompt `CollabSphere/core/views.py`  |
| [urls.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/urls.py)     | HTTP error 401 for prompt `CollabSphere/core/urls.py`   |
| [forms.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/forms.py)   | HTTP error 401 for prompt `CollabSphere/core/forms.py`  |
| [models.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/models.py) | HTTP error 401 for prompt `CollabSphere/core/models.py` |

</details>

<details closed><summary>CollabSphere.core.templates.core</summary>

| File                                                                                                                   | Summary                                                                     |
| ---                                                                                                                    | ---                                                                         |
| [login.html](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/templates/core/login.html)         | HTTP error 401 for prompt `CollabSphere/core/templates/core/login.html`     |
| [frontpage.html](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/templates/core/frontpage.html) | HTTP error 401 for prompt `CollabSphere/core/templates/core/frontpage.html` |
| [base.html](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/templates/core/base.html)           | HTTP error 401 for prompt `CollabSphere/core/templates/core/base.html`      |
| [signup.html](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/core/templates/core/signup.html)       | HTTP error 401 for prompt `CollabSphere/core/templates/core/signup.html`    |

</details>

<details closed><summary>CollabSphere.djangochat</summary>

| File                                                                                                    | Summary                                                         |
| ---                                                                                                     | ---                                                             |
| [asgi.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/djangochat/asgi.py)         | HTTP error 401 for prompt `CollabSphere/djangochat/asgi.py`     |
| [wsgi.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/djangochat/wsgi.py)         | HTTP error 401 for prompt `CollabSphere/djangochat/wsgi.py`     |
| [urls.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/djangochat/urls.py)         | HTTP error 401 for prompt `CollabSphere/djangochat/urls.py`     |
| [settings.py](https://github.com/Craniace/CollabSphere/blob/master/CollabSphere/djangochat/settings.py) | HTTP error 401 for prompt `CollabSphere/djangochat/settings.py` |

</details>

---

## 🚀 Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **Python**: `version x.y.z`

### ⚙️ Installation

1. Clone the CollabSphere repository:

```sh
git clone https://github.com/Craniace/CollabSphere
```

2. Change to the project directory:

```sh
cd CollabSphere
```

3. Install the dependencies:

```sh
pip install -r requirements.txt
```

### 🤖 Running CollabSphere

Use the following command to run CollabSphere:

```sh
python main.py
```

### 🧪 Tests

To execute tests, run:

```sh
pytest
```

---
## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/Craniace/CollabSphere/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Craniace/CollabSphere/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/Craniace/CollabSphere/issues)**: Submit bugs found or log feature requests for Collabsphere.

<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/Craniace/CollabSphere
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

[**Return**](#-quick-links)

---

