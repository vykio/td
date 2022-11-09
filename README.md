# td
> Todo CLI application created in Go

# Usage

```shell
make build
```

To generate the binary file and 

### Create a task
```shell
./td -add My first task
```

### List all tasks
```shell
./td -list
```

### Complete the `<nth>` task
```shell
./td -complete <nth>
```

### Delete the `<nth>` task
```shell
./td -del <nth>
```

# Todo

- [ ] Refactor the code
- [ ] Add compact flags
- [ ] Create tests
- [ ] Add filters
- [ ] Dockerize the app for development
- [ ] Add history
- [ ] Create a web interface