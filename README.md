# Django + React
## By Chau The Khanh

## Integrating Frontend And Backend For Efficient Web Development
<img src="img/ReactDjango.png" height="500" width="800">

## Technologies Used:
<ul>
    <li>Python 3.8</li>
    <li>Django 4.2</li>
    <li>Node.js (npx 9.5.1)</li>
</ul>

## 1. Setting Up The Development Environment
### 1.1 Install Django
- Open your terminal and run the following command: 
```bash 
pip install django
pip install django djangorestframework
```
- After installing Django, create a new Django project using the command below:
```bash
django-admin startproject ProjectWebApp
```

### 1.2 Install Node.js And NPM
Download and install them from the [official Node.js website](https://nodejs.org/en).

### 1.3 Create A React App
Create a new React app inside your Django project directory:
```bash npx create-react-app myapp```

``` bash
We suggest that you begin by typing:

  cd myapp
  npm start

Happy hacking!
```
### 1.4 Configure Django Settings
### 1.5 Set Up Static Files
### 1.6 Run Development Servers
In one terminal, navigate to your Django project directory and run:
```bash
python manage.py runserver
```

In another terminal, navigate to your React app directory and run:
```bash
npm start
```