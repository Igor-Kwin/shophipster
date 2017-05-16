# set up on heroku 
heroku login <br>
git clone https://github.com/Igor-Kwin/shophipster.git <br>
cd shophipster  <br>
heroku create <br> 
git push heroku master <br>
heroku ps:scale web=1  <br>
heroku open  <br>
