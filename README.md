# set up on heroku 
heroku login
git clone https://github.com/Igor-Kwin/shophipster.git
cd shophipster
heroku create
git push heroku master
heroku ps:scale web=1
heroku open
