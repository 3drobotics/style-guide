# 3DR Style Guide
### A guide to all 3DR styles on the web.

### Features:
* colors
* buttons
* web page partial options
* typography
* alerts
* navigations
* tbd

### Prerequisites
This app is built on ruby V2.2.3, rails V4.2.5, and requires a postgresql database.
See instructions [here](https://gorails.com/setup) on how to setup your environment.

### Set up
```
bundle install
rake db:create
rake db:migrate
```

### Local Usage
```
rails s
```

###Environments

[Staging]
(https://styleguide-3dr-staging.herokuapp.com/)

```
git remote add staging  https://git.heroku.com/styleguide-3dr-staging.git
```

[Production]
(https://styleguide-3dr.herokuapp.com/)
```
git remote add production https://git.heroku.com/styleguide-3dr.git
```