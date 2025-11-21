# Shirobase

A production-ready Django skeleton project that serves as a solid starting point for building modern web applications.

## 🎯 Overview

Shirobase is a pre-configured Django base project designed to jumpstart your development process. Instead of setting up the same boilerplate configurations for every new project, use Shirobase as your foundation. It comes with essential packages and best practices already integrated, allowing you to focus on building your application's unique features from day one.

## 🚀 Tech Stack

-   **Python 3.14** - Latest Python version
-   **Django 5.2** - Modern Django framework
-   **uv** - Fast Python package manager
-   **pytest** - Testing framework
-   **django-allauth** - Authentication and registration
-   **dj-rest-auth** - REST API authentication endpoints

## ✨ Features

This skeleton project includes:

-   ✅ Pre-configured Django 5.2 setup
-   ✅ Modern Python 3.14 support
-   ✅ UV package management for lightning-fast dependency resolution
-   ✅ Pytest configuration for robust testing
-   ✅ Django Allauth integration for complete authentication flows
-   ✅ DJ-REST-Auth for RESTful API authentication
-   ✅ Clean project structure
-   ✅ Ready for production deployment

## 📋 Prerequisites

-   Python 3.14 or higher
-   [uv](https://github.com/astral-sh/uv) package manager

## 🔧 Getting Started

### 1. Clone or Use as Template

```bash
# Clone the repository
git clone <repository-url> your-project-name
cd your-project-name
```

### 2. Install Dependencies

```bash
# Using uv (recommended)
uv sync
```

### 3. Set Up Environment Variables

Create a `.env` file in the project root with your configuration:

```env
SECRET_KEY=your-secret-key-here
DEBUG=True
DATABASE_URL=sqlite:///db.sqlite3
```

### 4. Run Migrations

```bash
uv run python manage.py migrate
```

### 5. Create Superuser

```bash
uv run python manage.py createsuperuser
```

### 6. Start Development Server

```bash
uv run python manage.py runserver
```

Visit `http://localhost:8000` to see your application running.

## 🧪 Running Tests

```bash
# Run all tests
uv run pytest

# Run with coverage
uv run pytest --cov

# Run specific test file
uv run pytest path/to/test_file.py

# Run specific test Test Class
uv run pytest path/to/test_file.py::DummyTestClass

# Run specific test function
uv run pytest path/to/test_file.py::DummyTestClass::dummy_test_successful
```

## 📦 Included Packages

This project comes pre-configured with:

-   **Django Allauth** - Handles user registration, login, logout, password reset, and social authentication
-   **DJ-REST-Auth** - Provides REST API endpoints for authentication operations
-   **Pytest** - Modern testing framework with Django integration

_Additional packages will be added and documented as the project evolves._

## 🏗️ Project Structure

```
shirobase/
├── apps              # Django apps
├── pyproject.toml       # Project dependencies and configuration
├── README.md            # This file
├── .gitignore
├── .python-version
├── manage.py           # main entry point
├── uv.lock             # Locked dependencies
└── Dockerfile
```

## 🎨 Customization

This is a skeleton project meant to be customized for your specific needs:

1. Rename the project to match your application
2. Add your Django apps
3. Configure your database settings
4. Customize authentication flows
5. Add your business logic

## 🤝 Contributing

This is a base template project. Feel free to fork and customize it for your needs.

## 📝 License

-   MIT

## 🔮 Roadmap

-   [ ] Add more pre-configured Django apps
-   [ ] Include Docker configuration
-   [ ] Add CI/CD pipeline examples
-   [ ] Include additional commonly used packages
-   [ ] API documentation setup
-   [ ] Frontend integration examples

## 📞 Support

For issues, questions, or contributions, please refer to the project's issue tracker.

---

**Built with ❤️ to accelerate Django development**
