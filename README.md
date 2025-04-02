[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18932794)

# CSSE6400 Week 2 Practical

Integration of a local relational database into our application.

Please see the [instructions](https://csse6400.uqcloud.net/practicals/week02.pdf) for more details.

Update this README file with appropriate information about your project,
including how to run it.

There are [resources](https://www.makeareadme.com) available to help you write a good README file.

## Name

Practical Object Relational Mapoping, SQLAlchemy, Migrations and testing HTTP APIs

## Description

A simple RESTful API for managing todo items, built using Flask and SQLAlchemy. We can use the API to create, read, update, and delete todo items. We can also
use the API to:

-   mark todo items as completed;
-   filter todo items by whether they are completed or not (a query parameter of completed in the list
    get query); and
-   filter todo items by whether they are within the next N days. In the tests this is exposed by a query
    parameter window.

## Installation

1. Clone the repository

```bash
git clone https://github.com/CSSE6400/2025-p2-JustBroch
```

2. Install dependencies using poetry

```bash
poetry install
```

3. Run the app locally

```bash
poetry run flask run
```

4. Run tests

```bash
poetry run python3 -m unittest discover -s tests
```

## Project Status

The project is finished.
