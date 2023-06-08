# udemy-building-modern-web-applications-with-go

## Session 2: Overview of the Go language

### Variables & Functions

- in Go, we use `var` keyword to declare a variable with Camel case name convention. the syntax is:

  ```go
  var variableName variableType
  ```

- we can assign value to a variable by using `=` operator. the syntax is:

  ```go
  variableName = value
  ```

- we must use the variable after we declare it, otherwise we will get an error.
- here we make use of variable by print it out with `fmt.Println()` function. the syntax is:

  ```go
  fmt.Println(variableName)
  ```

- we can also declare package level variable by using `var` keyword outside any function.
- now we create a function `saySomething` that return a string in the `main.go` file.
- we can use short declaration operator `:=` to declare and assign value to a variable. the syntax is:

  ```go
  variableName := value // the data type will be inferred from the type of value
  ```

- function in Go can return more than 1 value, checkout function `saySomethingElse` that return `string` and `int`.
- checkout the code in [main.go](main.go) file.
