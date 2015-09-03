[NOTE: This package is currently under development.]

# goat
Colorful TDD for Golang

Goat displays your golang test results in the browser.
Its inspired by the webui from smartystreet's [goconvey](https://github.com/smartystreets/goconvey) suite.

goat uses the webui and the cli param format of [watch](github.com/eaburns/watch).

##Quick start
###Install
```bash 
go get github.com/wallclockbuilder/goat
```

###Run
You can just simply cd into your working directory and run goat
```bash 
goat
```
Goat will default to the current directory, and go test.

You can specify a test command to run after any *.go file changes in the working directory
```bash
goat pkg=github.com/wallclockbuilder/goat cmd="go test -v wif_test.go"
```

See your tests running at: [http://localhost:4628](http://localhost:4628)


![](https://cdn-images-2.medium.com/max/600/1*_SxyPZYd5i_ss1KomYmJMg.png)

## Contributing
1. Fork it ( https://github.com/wallclockbuilder/goat )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
