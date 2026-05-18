\# Tratamento de Erros



Go utiliza retornos de erro ao invés de exceções tradicionais.



\## Exemplo de erro



```go

arquivo, err := os.Open("dados.txt")



if err != nil {

&#x20;   fmt.Println("Erro ao abrir arquivo")

}

```



\## Criando erro



```go

errors.New("erro personalizado")

```



\## Tratamento correto



```go

if err != nil {

&#x20;   return err

}

```



!!! danger "Cuidado"

&#x20;   Ignorar erros pode causar falhas inesperadas no sistema.

