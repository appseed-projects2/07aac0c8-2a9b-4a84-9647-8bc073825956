# [Soft UI Design Flask](https://appseed.us/product/soft-ui-design/flask/) 

Open-source **Flask Web App** generated by `AppSeed` op top of a modern design. Designed for those who like bold elements and beautiful websites, **[Soft UI Design](https://appseed.us/product/soft-ui-design/flask/)** is ready to help you create stunning websites and webapps. **Soft UI Design** is built with over 70 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining.

- 👉 Free [support](https://appseed.us/support/) via Email & `Discord` 
- 🚀 [Custom Development Services](https://appseed.us/custom-development/) for `accelerated growth`
- ✅ [Deploy on AWS, DO, and Azure](https://deploypro.dev/) via `DeployPRO` service (read the [DOCS](https://www.docs.deploypro.dev/))

<br />

### `PROMO` [Discounts for Developers](https://appseed.us/discounts/) Up to `30%OFF`

> The **discount is applicable to all products and licenses** (no stock limits) 

[![Discounts for Developers and Designers - AppSeed](https://user-images.githubusercontent.com/51070104/229268648-6ded378f-33aa-4909-a090-31fca49caa49.png)](https://appseed.us/discounts/)

<br />

> Built with [App Generator](https://appseed.us/generator/), timestamp `2023-11-24 20:13`

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Soft UI Design - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168812602-e35bad42-823f-4d3e-9d13-87a6c06c5a63.png)

<br />


## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/<YOUR_BUILD_ID>.git
$ cd <YOUR_BUILD_ID>
```

<br />

> **Step 2** - Edit `.env` and set `DEBUG=True`. This will activate the `SQLite` persistance. 

```txt
DEBUG=True
```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />


## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/07aac0c8-2a9b-4a84-9647-8bc073825956.git
$ cd 07aac0c8-2a9b-4a84-9647-8bc073825956
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />



## [Soft UI Design PRO Flask](https://appseed.us/product/soft-ui-design-pro/flask/)

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Soft UI Design is a premium Bootstrap 5 Design now available for download in Flask. Made of hundred of elements, designed blocks, and fully coded pages, Soft UI Design PRO is ready to help you create stunning websites and web apps.

- 👉 [Soft UI Design PRO Flask](https://appseed.us/product/soft-ui-design-pro/flask/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Soft UI Design (PRO Version) - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168812715-52e036b7-582d-4851-9657-6b1f99727619.png)

<br />

---
[Soft UI Design Flask](https://appseed.us/product/soft-ui-design/flask/) - Open-source starter generated by **[App Generator](https://appseed.us/generator/)**.
