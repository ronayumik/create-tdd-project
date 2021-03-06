# 2. Hello, World!

Here are your very first start of starting Golang (and TDD) Journey. In this first example, I'm creating a simple "Hello World" version.

## Getting Started

### Testing

You can run
```sh
$ go test main.go main_test.go
ok      command-line-arguments  (cached)
```

Try to fail the test. Change some string in `Hello()` function. Run the test and you will see this output
```sh
$ go test main.go main_test.go
--- FAIL: TestHello (0.00s)
        main_test.go:10: got 'Hello, wooorld' want 'Hello, world'
FAIL
FAIL    command-line-arguments  0.011s
```


### Running

You can run
```sh
$ go run main.go
```

And you will see
```sh
Hello, World!
```

End with an example of getting some data out of the system or using it for a little demo

### Creating executable

To create executable, you can run
```sh
$ go build main.go
```

And you will see an executable added in your project directory.
```sh
$ ls
README.md    main         main.go      main_test.go
```



### Cleaning executable
You can run this command to clean your executable from your project directory.
```sh
$ go clean
```

## Next Step
