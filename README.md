[NOTE: This package is currently under development.]

# go-CI [![Circle CI](https://circleci.com/gh/wallclockbuilder/go-CI.svg?style=svg)](https://circleci.com/gh/wallclockbuilder/go-CI)
`go test` in Color.

go-CI displays golang test results in the browser.
Its inspired by the webui from smartystreet's [goconvey](https://github.com/smartystreets/goconvey) suite.

go-CI is a gui to the idiomatic `go test` tool.
It watches the current directory and re-runs `go test` with your args when `*.go` files change. It takes the same arguments as the go test tool.


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
go-CI will default to running `go test` in the current directory.

See your tests running at: [http://localhost:4624](http://localhost:4624)


![](https://cdn-images-2.medium.com/max/600/1*_SxyPZYd5i_ss1KomYmJMg.png)
