# This is example social network
[*only ruby on rails without any backend ro frontend framefork*]
***
# Details

#### *Preparation*
> App uses PostgreSQL. You need change config in database.yml or create new pg_user:
#
```sh
$ sudo -u postgres createuser -s rails_user
$ sudo -u postgres psql
in postgres=#
$ \password rails_user
$ password
$ password
$ \q
```

#### *Run as all rails applicattion*
```sh
1)bundle install
2)rake db:setup
3)rails s
```

And just visit http://localhost:3000


***
#
# Tests

***

### *Rails test*

[*unit and integration tests*]

* Open terminal window in current folder and run: `rails test test`
