# printfirsthalf

### Instructions

Write a function called `Printfirsthalf()` that takes a string as an argument and prints the first half, 
If the length of the string is odd round it down.

- Prints the first half followed by newline `\n`.
- If the string is empty, return `Invalid Output`, followed by newline `\n`.
- If the string's length equals one, return it, followed by newline`\n`.

### Expected function

```go
func PrintFirstHalf(str string) string {
}
```

### Usage

Here is a possible program to test your function:

```go
package main

func main() {
    fmt.Print(FirstHalf("This is the 1st halfThis is the 2nd half"))
    fmt.Print(FirstHalf(""))
    fmt.Print(FirstHalf("Hello World"))
}
```

And its output :

```go
$ go run . | cat -e
This is the 1st half$
Invalid Output$
Hello$
```