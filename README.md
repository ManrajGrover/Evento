# Evento

<p align="center">
  <img src="https://raw.githubusercontent.com/ManrajGrover/Evento/master/assets/logo.png" width="400px" />
</p>

> View your Github events in a better way

## Installation

1. Download and extract zip file
2. Change directory to the folder created and go to `api` folder
3. Run `pip install -r requirements.txt`
4. Go to root folder of app and change directory to `webapp`
5. Run `npm install` to install all dependencies
6. Visit `https://github.com/settings/applications/new` and create your own Github Application
7. Get your client id and secret key and fill it in `api/application.yml`
8. Go to `webapp/src/js/angular-scripts.js` and change [this](https://github.com/ManrajGrover/Evento/blob/master/webapp/src/js/angular-scripts.js#L68) line with client id
9. Build the client side by going to `webapp` and running gulp
10. Finally, go back to `api` folder and run `python app.py`
11. App will run on `http://localhost:5000`

## Technologies used

* Flask v0.11.1
* Node v4.5.0
* Angular v1.5.8
* Angular Route v1.5.8
* Bootstrap v3.3.7
* jQuery v3.1.1
* ngInfiniteScroll v1.3.0
* Gulp v3.9.1

## License
[MIT](https://github.com/ManrajGrover/Evento/blob/master/LICENSE) © Manraj Singh
