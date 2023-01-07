# Django api server + single page app template

- Api server using [Django Ninja](https://github.com/vitalik/django-ninja)
- Vitejs frontend using [Vuejs](https://vuejs.org/)

## Features

- Login and logout forms
- User registration with email confimation
- Auth and csrf protected api by default
- Auto generated api docs
- Django forms support
- Responsive frontend with dark mode support

## Install

Clone or [degit](https://github.com/Rich-Harris/degit) and:

```bash
make install
```

This will create a virtual env, install the backend, run the migrations and then install the frontend

## Run

Run the backend dev server:

```bash
make run
```

Run the frontend dev server:

```bash
make front
```

Go to localhost:3000 for the dev frontend, go to localhost:8000/admin for the Django admin

## Build

Build the frontend for production:

```bash
make build-front
```

This compiles the frontend to an index.html template. Go to localhost:8000 to check
out the build in production mode