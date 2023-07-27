# logica-imperativa1
Elabore um algoritmo para que o usuário, através da entrada de dados, informe os seus dados pessoais.


```markdown
# Coleta de Dados Pessoais em Portugol

Aqui está um algoritmo simples em Portugol para coletar os dados pessoais do usuário e apresentá-los na tela:

```portugol
algoritmo DadosPessoais

var
    nome, endereco, cidade, cpf, rg: caractere

inicio
    escreva("Digite o seu nome: ")
    leia(nome)

    escreva("Digite o seu endereço: ")
    leia(endereco)

    escreva("Digite a sua cidade: ")
    leia(cidade)

    escreva("Digite o seu CPF: ")
    leia(cpf)

    escreva("Digite o seu RG: ")
    leia(rg)

    escreva("-----------------------------")
    escreva("Dados Pessoais:")
    escreva("-----------------------------")
    escreva("Nome: ", nome)
    escreva("Endereço: ", endereco)
    escreva("Cidade: ", cidade)
    escreva("CPF: ", cpf)
    escreva("RG: ", rg)
fim
```

Neste algoritmo, declaramos as variáveis `nome`, `endereco`, `cidade`, `cpf` e `rg` como caracteres para armazenar os dados fornecidos pelo usuário. Em seguida, usamos a função `leia()` para capturar esses dados do usuário. Após a entrada dos dados, usamos a função `escreva()` para apresentar os dados informados na tela.

Ao executar o algoritmo, ele solicitará ao usuário que insira os dados pessoais e, após a entrada dos dados, exibirá os mesmos na tela. Note que esse é apenas um exemplo básico e pode ser estendido ou melhorado para atender a necessidades específicas em um programa real.
```
