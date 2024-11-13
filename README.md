<<<<<<< HEAD
# Backend Boilerplate Django

A backbone for your coding challenge.

## Contents

- [Backend service](app) - a Django service with a `/ping` endpoint.
- [E2E test suites](cypress/integration) - a backend and a frontend Cypress test suites. Extend with your tests.
- [Pipeline](.github/workflows/tests.yml) - a test Runner that executes the Cypress tests on push to a branch other than `master`/`main`.

## Tech Stack

### Backend

- Django 4.1.4

#### Additional libs

- sqlite3 (SQLite connection)
- django-cors-headers (CORS support)

### Misc

- Cypress
- GitHub Actions

## Getting started

1. Make sure [`python3`](https://www.python.org/downloads/) and [`pip3`](https://pip.pypa.io/en/stable/installing/) are installed on your local env.

2. Make sure npm & node are configured on your local env. You can download those distributions for your platform [here](https://nodejs.org/en/download/)

3. Build your app.

```bash
npm install
npm run build # both Django backend
```

4. Start your app.

```bash
npm install
npm run start # both Django backend
```

5. Run the Cypress tests.

```bash
npm run test # run project tests under `cypress/integration`
```

---

Made by [DevSkills](https://devskills.co).

Did you find this repo useful? **Give us a shout on [Twitter](https://twitter.com/DevSkillsHQ) / [LinkedIn](https://www.linkedin.com/company/devskills)**.
=======
# cheki
A web service to view transaction history 
<<<<<<< HEAD
>>>>>>> 09864d8a64e97157e21b4f8b97766ac8fe13b7c7
=======

## Getting started

1. Make sure [`python3`](https://www.python.org/downloads/) and [`pip3`](https://pip.pypa.io/en/stable/installing/) are installed on your local env.

2. Build your app.

```bash
pip3 install -r requirements.txt && python3 manage.py migrate
```

3. Start your app.

```bash
python3 manage.py runserver
```

>>>>>>> b6fddeee2a82ec4d570f199fcb403b7755200c08
