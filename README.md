[NOTE: This package is currently under development.]

# go-CI
Colorful TDD for Golang

go-CI displays your golang test results in the browser.
Its inspired by the webui from smartystreet's [goconvey](https://github.com/smartystreets/goconvey) suite.

go-CI is a gui to the idiomatic `go test` tool.
It watches the current directory and re-runs `go test` when `*.go` files change.


##Quick start
###Install
```bash
go get github.com/wallclockbuilder/go-CI
```

###Run
At the terminal, cd into your working directory and run go-CI
```bash
go-CI
```
go-CI will default to the current directory, then just like `go test`.

See your tests running at: [http://localhost:4624](http://localhost:4624)


![](https://cdn-images-2.medium.com/max/600/1*_SxyPZYd5i_ss1KomYmJMg.png)
