\# Testes Automatizados em Go



Go possui suporte nativo para testes automatizados.



\## Arquivo de teste



Arquivos de teste utilizam o padrão:



```go

arquivo\_test.go

```



\## Exemplo de função



```go

func Soma(a int, b int) int {

&#x20;   return a + b

}

```



\## Exemplo de teste



```go

func TestSoma(t \*testing.T) {

&#x20;   resultado := Soma(2,2)



&#x20;   if resultado != 4 {

&#x20;       t.Errorf("Erro no teste")

&#x20;   }

}

```



\## Executando testes



```go

go test

```



!!! tip "Boa prática"

&#x20;   Testes automatizados ajudam na manutenção e qualidade do software.

