\# Arrays, Slices e Maps



\## Arrays



Arrays possuem tamanho fixo.



```go

var numeros \[3]int

```



\## Inicialização de Arrays



```go

numeros := \[3]int{1,2,3}

```



\## Slices



Slices possuem tamanho dinâmico.



```go

lista := \[]int{1,2,3}

```



\## Append



```go

lista = append(lista, 4)

```



\## Maps



Maps armazenam chave e valor.



```go

idades := map\[string]int{

&#x20;   "Ana": 20,

}

```



\## Acessando valores



```go

fmt.Println(idades\["Ana"])

```



!!! note "Observação"

&#x20;   Slices são muito utilizados em Go devido à flexibilidade.

