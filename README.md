# anti-captcha

Go library for accessing the anti-captcha.com API

# Install

```go
go get github.com/zplzpl/anti-captcha
```

# Usage

```go
import "github.com/zplzpl/anti-captcha"

func main() {
    client := anti-captcha.NewClient("your-key-here")
    
    balance, _ := client.GetBalance(context.Background())
    
    fmt.Println(balance) // 4.77
}
```
