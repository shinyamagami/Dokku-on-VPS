# AWS LightSail to DigitalOcean

The reason I decided to move from LightSail to DigitalOcean is Dokku tells me to use root, which LightSail does not allow me to.
While DigitalOcean does, the cheapest VPS from it is $4 for 1 CPU, 512MB, and meager 10GB SSD. The cheapest one from LightSail offers
a $5 plan for 2! CPU, 512MB, and 20GB SSD, whose half is already used from the beginning.

# AWS LightSail to Akamai Linode

I happened to learn that 10GB was too small for Dokku so that I would have to use, at least, $6 plan on DigitalOcean.
It changed my mind, and I decided to use Linode, which offers $5 plan with 25GB SSD. Linode is now owned by Akamai.

It seems that we have to install dokku under root. I installed it under an user I created and I couldn't not deploy
an application. 


When you want to seed with the seed file,
dokku run rails7-sample bundle exec rake db:migrate db:seed


# Useful Commands for Dokku

`docker image ls`
