\# Structs e Métodos



Structs são utilizadas para agrupar dados relacionados.



\## Criando Struct



```go

type Pessoa struct {

&#x20;   Nome string

&#x20;   Idade int

}

```



\## Instanciando Struct



```go

pessoa := Pessoa{

&#x20;   Nome: "Carlos",

&#x20;   Idade: 25,

}

```



\## Métodos



```go

func (p Pessoa) Apresentar() {

&#x20;   fmt.Println(p.Nome)

}

```



\## Chamando método



```go

pessoa.Apresentar()

```



!!! warning "Importante"

&#x20;   Métodos ajudam na organização e reutilização do código.

