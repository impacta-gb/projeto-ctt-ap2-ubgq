\# Channels



Channels permitem comunicação entre goroutines.



Eles são usados para enviar e receber dados.



\## Exemplo



```go

package main



import "fmt"



func main() {

&#x20;   canal := make(chan string)



&#x20;   go func() {

&#x20;       canal <- "Olá"

&#x20;   }()



&#x20;   mensagem := <-canal



&#x20;   fmt.Println(mensagem)

}

```

