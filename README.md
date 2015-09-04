[NOTE: This package is currently under development.]

# gotest
Colorful TDD for Golang

gotest displays your golang test results in the browser.
Its inspired by the webui from smartystreet's [goconvey](https://github.com/smartystreets/goconvey) suite.

gotest uses the webui and the cli param format of [watch](github.com/eaburns/watch).

##Quick start
###Install
```bash
go get github.com/wallclockbuilder/gotest
```

###Run
You can just simply cd into your working directory and run gotest
```bash
gotest
```
gotest will default to the current directory, and go test.

You can specify a test command to run after any *.go file changes in the working directory
```bash
gotest pkg=github.com/wallclockbuilder/gotest cmd="go test -v wif_test.go"
```

See your tests running at: [http://localhost:4628](http://localhost:4628)


![](https://cdn-images-2.medium.com/max/600/1*_SxyPZYd5i_ss1KomYmJMg.png)

## Contributing
1. Fork it ( https://github.com/wallclockbuilder/gotest )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
