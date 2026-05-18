\# Goroutines



Goroutines são funções executadas concorrentemente em Go.



Elas permitem executar várias tarefas ao mesmo tempo.



\## Exemplo



```go

package main



import "fmt"



func mensagem() {

&#x20;   fmt.Println("Executando goroutine")

}



func main() {

&#x20;   go mensagem()

}

```

