# README

The site can be accessed at https://zenhomework.herokuapp.com/

The presentation can be viewed here:

### Screen during work

### Screen during short break


### Screen during long break


### Installation instructions

- Install postgres `brew install postgres`
- Create postgres user called `dev_user` with password `password`

```
createuser -s dev_user
```

Launch `psql`

```
password dev_user
```

- install rvm
```
\curl -sSL https://get.rvm.io | bash -s stable --ruby
```

- install rails

```
gem install rails
```

- create databases for the project

```
rake db:create
```

- create database tables

```
rake db:migrate
```

- run rails server

```
bin/rails server
```
