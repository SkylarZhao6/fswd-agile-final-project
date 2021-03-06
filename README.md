# Health Bro

## Heroku app: [go now](https://healthbro.herokuapp.com)

* Basic account users can search for meal suggestions by searching the main ingredient, calorie amount, or dietary restrictions.
* Premium account user can search for any type of ingredient, calorie amount, dietary restrictions, cuisine type, and meal type. A bonus option of searching a for meal plan with target total calorie amount per day.
* Filters to results can be applied through calorie per serving and specific diet restrictions.

## prepare
1. go to [rapidapi](https://rapidapi.com)
2. go to [Spoonacular](https://rapidapi.com/spoonacular/api/Recipe%20-%20Food%20-%20Nutrition)
   1. get your X-RapidAPI-Key and X-RapidAPI-Host
3. go to [Edamam](https://rapidapi.com/edamam/api/Recipe%20Search%20and%20Diet)
   1. get your X-RapidAPI-Key and X-RapidAPI-Host
4. Go to ".env" file and change the value as describe
**Note:** If you have a **MongoDB** we suggest you use your **Own MongoDB URI**. In case you want to use your own **Mongo** [click here](https://www.mongodb.com)


## Installation 
To run locally:

1. install dependencies

```bash
npm install
```

2. run server

```bash
npm start
```

_or_

```bash
node server.js
```

_or_

```bash
npm run dev
```

## Built Using:
* Node.js
* Express
* MongoDB

## API keys
Please use your own API keys. The APIs used for this project includes:

* [Edamam](https://www.edamam.com/)
* [Spoonacular](https://spoonacular.com/)

## Current active endpoints for users:

```
* home
http://localhost:8888/

* login/sign-up
http://localhost:8888/login_and_signup

--- note you will be automatically redirected to the appropriate endpoints depending on the type of user ---

* dashboard
http://localhost:8888/secure

* admin panel
http://localhost:8888/admin/a

* normal user for admin
http://localhost:8888/admin/normal

* premium user for admin
http://localhost:8888/admin/premium

* logout
http://localhost:8888/user/logout

```

---

## Internal endpoints

```

* depreciated sign-up POST
http://localhost:8888/signup

* depreciated sheets.best POST
http://localhost:8888/admin/a

---

* user login POST
http://localhost:8888/user/gNQu5jGgxPL42r8g5zm6

* create user POST
http://localhost:8888/user/JKp7DeJXgaFtxaJ7FTXb

* premium user api route POST
http://localhost:8888/api/getinfo

* normal user api route POST
http://localhost:8888/api/getinfo_normal

* admin get user info GET
http://localhost:8888/admin/a

* admin update user UPDATE
http://localhost:8888/admin/update

* admin delete user DELETE
http://localhost:8888/admin/delete

* normal and premium dashboard access for admin
http://localhost:8888/admin/normal
http://localhost:8888/admin/premium

```
## Not Yet Implemented
* Calorie Tracker

## Contributors
* Homer Li / emo8355 
* Don Li / dl90
* Skylar Zhao / SkylarZhao 6
* Cindy Le / cee-elle
* Jaime Deng / jaime-deng

## Licensing
MIT License

Copyright (c) 2020 emo8355, dl90, SkylarZhao6, cee-elle, jaime-deng

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
