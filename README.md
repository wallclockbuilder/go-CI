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

## Refactoring Standards
- 5 lines of code max per function. Write your code to pass then refactor to meet this rule.
- Functions with more than 5 lines of code MUST have godoc comments.
- Comments have to
  - explain intent of the code.
  - be comprehensive(more than one sentence).


If you like these rules. More goodies for you:
- [Rules](https://www.youtube.com/watch?v=npOGOmkxuio) by Sandi Metz
- [Simple made easy](http://www.infoq.com/presentations/Simple-Made-Easy) by Rich Hickey

If you hate the rules, check out the talks above.

## Contributing
1. Fork it ( https://github.com/wallclockbuilder/go-CI )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
