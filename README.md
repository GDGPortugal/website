# GDG Portugal Website

The directory of all GDGs active in Portugal.

## How to run

Requires [Jekyll](https://jekyllrb.com/) to build the website and a host, in this case [Firebase](https://firebase.google.com/) to deploy.


### with RVM

using https://rvm.io

```
gpg2 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

curl -sSL https://get.rvm.io | bash -s stable
```

Follow RVM instructions to add RVM to PATH and reload of close/open another console/ssh session.

To install ruby on global rvm:

```
rvmsudo rvm install ruby-2.7.1

````

or just to local user:

```

rvm install ruby-2.7.1

```

then

```

cd /.../gdg-portugal-website

bundle install

jekyll serve -w

```

### with Docker compose

[Install Docker compose](https://docs.docker.com/compose/install/)

then run:

```
docker-compose up
```

Open http://127.0.0.1:4000


## How to build

### with Ruby

Run

```
jekyll build
```

### with Docker compose

Run
```
docker-compose run jekyll jekyll build
```

## Contact

Reach out to your nearest GDG to give an helping and or participate in our meetups!