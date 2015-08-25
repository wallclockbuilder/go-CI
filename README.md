# goat
Colorful TDD for Golang

goat uses the webui from goconvey(https://github.com/smartystreets/goconvey) and the cli param format of watch(github.com/eaburns/watch).

Quick start
-----------
Install
```bash 
go get github.com/wallclockbuilder/goat
```

Usage
You can just simply cd into your working directory and run goat
```bash 
goat //tests the package in the current working directory
```

You can specify a package to test
```bash
goat github.com/wallclockbuilder/goat
```

See all your tests running http://localhost:4628


## Contributing
1. Fork it ( https://github.com/wallclockbuilder/stringutil )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
