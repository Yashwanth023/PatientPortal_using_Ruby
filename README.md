# Health soft

---

## Project Description

Health soft is a hospital management system module meant to manage patient admission, patient appointments and patients treatment.

---

## Table of content

- [Technologies](#description)
- [Description](#description)
- [Features](#features)
- [Setup-process](#setup_process)
- [Project-usage](#project-usage)

---

## Technologies

languages used are:

- Front-end

1. React(Typescript)
2. Sass

---

- Back-end

1. Ruby on Rails

---

### Features

- As a Nurse you can be able to:

1. Login with his/her account.
2. Register a new patient
3. Manage registered patients( update info, delete records)
4. take patients vitals signs
5. Book appointment(s) for a patient

- As a Doctor you can be able to:

1. View all the appointments.
2. Check up patients records
3. Do a checkup on a patient and record your findings and diagnosis

- AS an admin you can be able to:

4. Add new nurse, doctor or admin
5. Update system users details.
6. Delete an system users account

---

### description

- When a patient walks in the hospital he is admited if it is the first time he/she visits
- His or her vitals signs will be recorded, including, temperature blood presure...
- The nurse at reception will book an appointment for the patient with available doctor
- The doctor will recieve the patient, and check on recorded vitals signs
- the doctor will diagonise the patient and record the finding

---


### Dependencies

- npm
- ruby
- rails
- node

---

### setup

#### Client (React)

clone the repository

change directory using command

```shell
cd health-soft
```

open project in vscode editor

```shell
code .
```

install dependancies

```shell
npm install
```

run front end

```shell
npm run dev
```

---

#### API (Ruby on Rails)

clone the repository

change directory using command

```shell
cd health-soft
```

open project in vscode editor

```shell
code .
```

Check your Ruby version

```shell
ruby -v
```

The ouput should start with something like `ruby 2.5.1`

If not, install the right ruby version using [rbenv](https://github.com/rbenv/rbenv) (it could take a while):

```shell
rbenv install 2.7.0
```

install dependancies packages

```shell
bundle install
```

Initialize the database

```shell
rails db:create db:migrate db:seed
```

run api server

```shell
rails s
```

---

- run the following live link in your browser
  `https://localhost:3000`

#### login Credentials..

Admin:

```shell
email: admin@admin.com
password: admin@admin.com
```

Nurse:

```shell
email: nurse@nurse.com
password: nurse@nurse.com
```

Doctor

```shell
email: doctor@doctor.com
password: doctor@doctor.com
```

## How to use the project

---

### Contributing to project

- Fork the repo

* Create a new branch in your terminal (git checkout -b improve-feature)
* Install the prerequisites
* Make appropriate changes in file(s)
* Run the server to see the changes
* Add the changes and commit them (git commit -am "Improve App")
* Push to the branch (git push origin improve-app)
* Create a Pull request

---
