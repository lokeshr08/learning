# Day 01

- Goroutines: `go` keyword
- `go build` & `go run` commands
- Syntax
  - Variables, packages and functions
    - Functions
      - Multiple returns
        `func hello() (int, string) {}`
      - named returns, zero values, type conversion & inference
    - constants:
      - `const` keyword
      - `iota` built-in
    - Flags
    - `log` package
    - cgo
    - Flow control
      - for `for {`
        - normal `for <init>; <expression>; <condition> {`
        - while `for <condition> {`
        - forever `for {`
          - can control execution using `break`
        - `for` along with `range`
      - if / else if / else `if <statement>; <condition> {`
      - switch `switch {`
        - normal `switch <value> {`
        - conditional `switch <value> { case <statement>: `
        - no condition switch `if-else-if`
      - defers `defer <funcCall>`
