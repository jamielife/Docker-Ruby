# Ruby on Rails Docker Container

## Build
1. ```docker-compose build```

2. ```docker-compose run --rm --service-ports ruby_dev```


## Create App
1. ```rails new myapp && cd myapp```

2. ```bundle update && bundle install```

3. ```rails server -p $PORT -b 0.0.0.0```