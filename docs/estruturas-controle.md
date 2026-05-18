\# Estruturas de Controle



As estruturas de controle são utilizadas para tomada de decisão e repetição.



\## If



```go

idade := 18



if idade >= 18 {

&#x20;   fmt.Println("Maior de idade")

}

```



\## If e Else



```go

if nota >= 7 {

&#x20;   fmt.Println("Aprovado")

} else {

&#x20;   fmt.Println("Reprovado")

}

```



\## For



Go possui apenas a estrutura `for`.



```go

for i := 0; i < 5; i++ {

&#x20;   fmt.Println(i)

}

```



\## Switch



```go

dia := 2



switch dia {

case 1:

&#x20;   fmt.Println("Domingo")

case 2:

&#x20;   fmt.Println("Segunda")

}

```



!!! tip "Boa prática"

&#x20;   Utilize switch para evitar múltiplos if encadeados.



