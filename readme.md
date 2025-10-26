# Django Video Chat App

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Django](https://img.shields.io/badge/Django-5.0-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
[![Agora Integrated](https://img.shields.io/badge/Agora-Integrated-blue?logo=agora&logoColor=white)](https://www.agora.io/en/)

## Overview

> A **real-time** video chat application built with **Django** and the **Agora API**, enabling users to create or join video rooms for seamless, low-latency communication.

## Features

- User Authentication
- Video & Audio Calls
- Multi-User Rooms
- Responsive UI
- Dynamic Channel Creation

## Quick Start

#### 1 - Clone repo

```bash
git clone <repo_url>
```

#### 2 - Install requirements

```bash
pip install -r requirements.txt
```

#### 3 - Update Agora credentials

###### views.py

```bash
def getToken(request):
    appId = "YOUR APP ID"
    appCertificate = "YOUR APPS CERTIFICATE"
```

###### streams.js

```bash
const APP_ID = 'YOUR APP ID'
```

#### 4 - Run server

```bash
python manage.py runserver
```

## Contributing

1. Fork the repository
2. Create feature branch: `git checkout -b feature/new-feature`
3. Commit changes: `git commit -m 'Add new feature'`
4. Push: `git push origin feature/new-feature`
5. Open Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

**⭐ Star this repo if it helped you!**
