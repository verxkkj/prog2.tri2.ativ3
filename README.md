## Instruções Gerais

Todas as atividades devem ser desenvolvidas utilizando o TypeScript Playground.

Para cada atividade:

1. Copie o enunciado da atividade para o README.md do repositório.
2. Resolva a atividade no TypeScript Playground.
3. No topo do arquivo, adicione um comentário explicando:
   * qual problema está sendo resolvido;
   * qual conceito de orientação a objetos está sendo demonstrado;
   * por que esse conceito é útil;
   * quais dificuldades surgiriam sem sua utilização;
   * se aplicável, compare a solução com uma abordagem procedural ou funcional.
4. Gere o link compartilhável do Playground.
5. Cole o link da resposta imediatamente abaixo do enunciado correspondente no README.md.

O repositório deve possuir o nome:

**PROG2.TRI2.ATIV3**

## Enunciado

Escreva trechos de códigos que justiquem a necessidade da existencia dos temas abaixo em a objetos, se necessário compare com programçaõ funcional para justificativa, adicione ao topo de seus arquivos comentários que justifiquem a abordagem tomada na solução (para cada tópico faça duas soluções diferentes):

1. Classes e objetos
https://www.typescriptlang.org/play/?#code/PQKgUABCEKIM4BcCmEDGBngJgSwOYHsJMkBbfAO0QCcBDCQgVzkOLQBsa44k4IV8ARgCskCfLwAONWhCpIJc7uQTSIEns058INcthI1scAHSRo8bmgqok2MRG5UAbigV18VXLuwAvVeKIaTACUVHwSCQ8VEiRlEJIIBgMIAC+9VDoeBCoGBAZaABozCAAzGlRsNjtdYJ1ZJFzK3xoAc4BjwhQ6A3Jc2PaWQgwcAmMIAGVSdk5uOAKHJCpsOnIkGy4AQ6X8YtQl1Sct5d4naWwNlyNtEoZyFoBXngWpWkxOMZgEsIjpVo6rBJJOg0AQeN64KYKfA2TD5GhseY0YoebCxFQDOqCERiXg0XA5KT0XhvYK8Lq4h5POQcCoUIJaKZJCAxOBkPhsUho-CmKDAMBgYDAaZcHj81AcLgQAAKGnwdAA3pAIMryOEkABCABcDmy2HIuH5yuVNAUPDR0gAFABKCCKo32qyUfAc4xsfC4C0AAwA8mwNvMYgwIKqYhAAJcQAAk8oQAAsjMYQ0gAL6eq1K5XJsBZsDimYQACCegMbFtGb4cHUFQ12uoeoN5dIdmwVHG4WtZYdRrCTpdbo9nujcYTPCrqOTpSQPkSCWYJDT5azOcFED1iF0FS0YooiDUspoAEYIABeYNIADu0v31rA6i4coPibVJ4gACIZZgqPhX9vKAg9-eNAAEwvqsl4yoBN53poQFPqGp6vkWNA-rmO7-t4JZHqeYGFsW8I3hh8KPqOayoi+r5eGIKE9ruhFsCB2EXrh+j4emdGwSR1bkRkqCxh4X4oSuyCIEgv7MC64pIJa6a3vuj4moo5pUFB+6wQpZrKNJ-J0cRJDNq27ZsXh9HGE2CAtm2JAqYB8mmkoKjKem0FympdlKTeQA

0. Atributos e métodos


0. Construtores (constructor)


0. Instanciação de objetos
0. Modificadores de acesso (public, private, protected)
0. Propriedades somente leitura (readonly)
0. Métodos estáticos (static)
0. Propriedades estáticas (static)
0. Encapsulamento
0. Herança
0. Polimorfismo
0. Abstração
0. Getters e setters
0. Classes abstratas (abstract)
0. Métodos abstratos
0. Sobrescrita de métodos (override)
0. Sobrecarga de métodos (method overloading)
0. Parâmetros opcionais em métodos
0. Parâmetros padrão
0. Herança simples
0. Cadeia de herança
----------------------

// JUSTIFICATIVA:
// este código demonstra o uso de atributos e métodos.
//  atributos armazenam informações dos objetos, enquanto os
// métodos executam ações utilizando esses dados.
// neste exemplo utilizamos as classes ContaBancaria e Lampada.

// classes

class ContaBancaria {
    saldo: number = 0

    depositar(valor: number) {
        this.saldo += valor
        console.log(`Saldo: RS ${this.saldo}`)
    }
}

class Lampada {
    ligada: boolean = false

    ligar() {
        this.ligada = true
        console.log("Lâmpada ligada")
    }
}

// instanciação de objetos

const conta = new ContaBancaria()
const lampada = new Lampada()


console.clear()

conta.depositar(100)
conta.depositar(50)

lampada.ligar()

-----------------

// JUSTIFICATIVA:
// este código demonstra o uso do constructor.
// construtor é executado automaticamente quando um objeto é criado,
// permitindo inicializar os atributos obrigatórios.
// neste exemplo utilizamos as classes Produto e Aluno.

// definição de classes

class Produto {
    constructor(
        public nome: string,
        public preco: number
    ) {}

    mostrar() {
        console.log(`${this.nome} custa RS ${this.preco}`)
    }
}

class Aluno {
    constructor(
        public nome: string,
        public curso: string
    ) {}

    apresentar() {
        console.log(`${this.nome} estuda ${this.curso}`)
    }
}

// instanciação de objetos

const produto1 = new Produto("Notebook", 1000)
const produto2 = new Produto("Mouse", 100)

const aluno1 = new Aluno("Bernardo", "Arquitetura")
const aluno2 = new Aluno("Filipe", "Engenharia Civil")

console.clear()

produto1.mostrar()
produto2.mostrar()

aluno1.apresentar()
aluno2.apresentar()
0. Tratamento de exceções (throw, try, catch)
0. Classes e herança de classes de erro
