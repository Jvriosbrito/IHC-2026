# UA4 – Programação Orientada a Objetos com TypeScript

## Objetivo
Implementar um sistema de vendas utilizando Programação Orientada a Objetos (POO) em TypeScript, demonstrando domínio de tipagem forte, encapsulamento e manipulação de coleções de objetos.

## Funcionalidades Implementadas

A solução prática consistiu na codificação completa de duas classes principais que abstraem entidades do mundo real para o ambiente digital:

### 1. Classe `Produto`
Modelagem da entidade de produto contendo 5 atributos obrigatoriamente tipados:
- `nome` (string)
- `descricao` (string)
- `valorComercial` (number)
- `fabricante` (string)
- `emEstoque` (boolean)

A classe utiliza um método construtor para garantir que todo objeto instanciado receba dados válidos e tipados logo na sua criação.

### 2. Classe `Venda`
Responsável por encapsular uma coleção de produtos.
- Recebe um array de objetos `Produto` (`Produto[]`) através do seu construtor.
- Implementa o método rigorosamente tipado `calcularTotal()`, que itera sobre o array de produtos (utilizando laço de repetição ou o método `reduce`) para computar e retornar o montante financeiro total da transação.

## Código Desenvolvido

```typescript
// a) Classe Produto com 5 atributos tipados
class Produto {
    nome: string;
    descricao: string;
    valorComercial: number;
    fabricante: string;
    emEstoque: boolean;

    constructor(
        nome: string,
        descricao: string,
        valorComercial: number,
        fabricante: string,
        emEstoque: boolean
    ) {
        this.nome = nome;
        this.descricao = descricao;
        this.valorComercial = valorComercial;
        this.fabricante = fabricante;
        this.emEstoque = emEstoque;
    }
}

// b) Classe Venda com array de produtos no construtor e método de soma
class Venda {
    produtos: Produto[];

    constructor(produtos: Produto[]) {
        this.produtos = produtos;
    }

    calcularTotal(): number {
        let total = 0;
        for (let i = 0; i < this.produtos.length; i++) {
            total += this.produtos[i].valorComercial;
        }
        return total;
        
    }
}

// c) Criação de instâncias, inserção na Venda e execução da soma
const produto1 = new Produto(
    "Monitor Gamer Samsung Odyssey G40",
    "Monitor 27 polegadas, 240Hz, painel IPS",
    1850.00,
    "Samsung",
    true
);

const produto2 = new Produto(
    "Camisa Oficial Cruzeiro",
    "Camisa titular azul, modelo torcedor",
    350.00,
    "Adidas",
    true
);

// Criando o objeto Venda passando o array de produtos
const minhaVenda = new Venda([produto1, produto2]);

// Realizando a soma
const valorTotal = minhaVenda.calcularTotal();
console.log(`O valor total da venda é: R$ ${valorTotal.toFixed(2)}`);
```

## Como Executar o Projeto

### Pré-requisitos
- Node.js instalado
- Gerenciador de pacotes (npm ou yarn)

### Passo a Passo

1. **Instale o compilador TypeScript globalmente** (caso não possua):
   ```bash
   npm install -g typescript
   ```

2. **Compile o arquivo TypeScript** para JavaScript:
   ```bash
   tsc index.ts
   ```

3. **Execute o código** utilizando o Node.js:
   ```bash
   node index.js
   ```

*(Alternativa: O código também pode ser executado diretamente no TypeScript Playground no navegador).*

## Arquivos Entregues
- `UA4_VendasTS/index.ts` (Código fonte)
- `UA4_VendasTS/index.js` (Código compilado)

