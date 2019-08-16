<img width="1264" alt="home_top" src="https://user-images.githubusercontent.com/13613724/63157458-dd164000-bfcb-11e9-9947-17034e742cb0.png">
<img width="1220" alt="home_bottom" src="https://user-images.githubusercontent.com/13613724/63157472-e2738a80-bfcb-11e9-9d36-f92749bfcd8d.png">
<img width="1300" alt="following" src="https://user-images.githubusercontent.com/13613724/63157478-e4d5e480-bfcb-11e9-92b4-a5f20922dc9a.png">

# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).
