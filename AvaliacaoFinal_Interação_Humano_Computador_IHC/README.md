# Avaliação Final – Interação Humano-Computador (IHC)

## Identificação do Estudante

- Nome: João Victor Rios Brito e Nascimento
- Matrícula: 22400050
- Curso: Ciêcias da Computação
- Polo: Asa Norte
- Data de Entrega: 17/06/2026

## Descrição Geral

Este repositório reúne as atividades desenvolvidas durante a disciplina de Interação Humano-Computador (IHC), 
contemplando os desafios das Unidades de Aprendizagem UA1, UA2, UA3 e UA4.

---

## UA1 – Introdução à IHC e seus benefícios

### Objetivo

Compreender os fundamentos de Interação Humano-Computador (IHC), com foco em navegabilidade, experiência do usuário (UX), prevenção de erros e conformidade visual para sistemas corporativos, analisando uma interface com problemas de usabilidade e propondo melhorias práticas.

### Solução Desenvolvida

Foi realizada uma análise crítica do pop-up de um Sistema de Folha de Pagamento que apresentava problemas de usabilidade, como falhas de rotulagem (uso de termos ambíguos como "Avançar"), falta de clareza nas consequências da ação e problemas de acessibilidade. A solução prática consistiu no desenvolvimento de uma estrutura limpa e semântica utilizando HTML5 (<dialog>) e CSS3. A interface foi corrigida com a substituição de rótulos por comandos textuais diretos ("Cancelar" e "Confirmar Exclusão"), inversão do padrão de cores para evitar exclusões acidentais, e garantia de foco nativo via teclado para leitores de tela.

### Arquivos Entregues

- UA1_Popup/index.html
- UA1_Popup/style.css 

---

## UA2 – Interface, interação e Affordance

### Objetivo

Analisar o comportamento do usuário diante de diferentes tipos de interfaces e restrições físicas, mapeando o uso correto de tecnologias assistivas e canais de interação (Voz, Áudio e Tato) para garantir a autonomia de usuários com deficiência visual.

### Solução Desenvolvida

Foi elaborada uma proposta de Interface Assistiva para um gerenciador de cursos voltado para funcionários com deficiência visual. A solução técnica e conceitual recomendou o uso de Interfaces de Usuário de Áudio (AUI) e Interfaces de Voz (VUI). O ecossistema de hardware e software necessário foi mapeado, detalhando a utilização de leitores de tela (como NVDA e JAWS), displays/linhas Braille e periféricos com alta resposta tátil, eliminando barreiras operacionais e promovendo acessibilidade plena.

### Arquivos Entregues

- UA2_Resposta_Discursiva.txt

---

## UA3 – Storyboarding e prototipação de interfaces

### Objetivo

Dominar o processo de Design Centrado no Usuário (DCU) na fase de descoberta de escopo, utilizando técnicas de imersão, cocriação e validação rápida para projetar uma solução tecnológica de mobilidade urbana assistiva.

### Solução Desenvolvida

Foi estruturado um plano de processo de design passo a passo para criar uma solução de mobilidade para o usuário "Ricardo", que possui perda gradativa da visão. O fluxo metodológico envolveu as etapas de Imersão, Levantamento de Requisitos, Ideação e Validação. Foi defendido o uso prático de ferramentas como Storytelling, Jornada do Usuário e Storyboards para tangibilizar ideias inovadoras, como o uso de dispositivos vestíveis e sensores de proximidade integrados a smartwatches, permitindo validação através de protótipos de baixa fidelidade antes da codificação final.

### Ferramentas Utilizadas

- Storyboarding
- Jornada do Usuário
- Ferramentas de prototipação de baixa fidelidade

### Arquivos Entregues

- UA3_Processo_Design.txt

---

## UA4 – TypeScript

### Objetivo

Aplicar conceitos fundamentais de Programação Orientada a Objetos (POO) utilizando a sintaxe do TypeScript, garantindo tipagem forte, reutilização de código e segurança no fluxo de dados através da modelagem de um sistema de vendas.

### Funcionalidades Implementadas

- Classe Produto: Implementada com 5 atributos obrigatórios (id, nome, descricao, valor, fabricante), inicializados via método construtor para garantir dados válidos na criação.
- Classe Venda: Criada para gerenciar o agrupamento de produtos, recebendo um array de objetos Produto em seu construtor.
- Método valorVenda(): Implementado na classe Venda para iterar sobre a lista de produtos e calcular o montante total da transação de forma rigorosamente tipada.
- Instanciação e Execução: Criação de objetos da classe Produto (ex: Cadeira Gamer, Mesa de Escritório), injeção na classe Venda e exibição do resultado do cálculo no console.

### Tecnologias Utilizadas

- TypeScript
- Node.js
- Outras bibliotecas

### Como Executar o Projeto

#### Pré-requisitos

- Node.js instalado
- npm ou yarn

#### Instalação

\```bash
npm install
\```

#### Execução

\```bash
npm start
\```

#### Compilação

\```bash
tsc
\```

### Arquivos Entregues

- UA4_VendasTS/index.ts
- arquivo2.ext

---

Uso de Inteligência Artificial (IA)

Para o desenvolvimento e documentação destas atividades, foi utilizada a Inteligência Artificial Manus. O uso da tecnologia limitou-se estritamente a:

-Correções e validações estruturais dos códigos.
-Pesquisas pontuais sobre a sintaxe do TypeScript, assegurando o uso correto de construtores e tipagem estrita de arrays.
-Formatação e organização deste arquivo de documentação, gerando um relatório padronizado, limpo e profissional.
-A lógica de negócios, a engenharia de acessibilidade, o design de IHC e a resolução analítica das questões discursivas foram de autoria inteiramente própria.



## Considerações Finais

A realização deste conjunto de desafios proporcionou um entendimento profundo sobre a indissociabilidade entre a engenharia de software e os fatores humanos. O desenvolvimento da UA1 e UA2 consolidou o entendimento prático de que interfaces acessíveis e semânticas não são apenas recursos adicionais, mas sim pilares de usabilidade e responsabilidade técnica que evitam erros operacionais graves.

Na UA3, ficou clara a importância do amadurecimento conceitual e do design centrado na dor do usuário antes de iniciar qualquer linha de desenvolvimento. Por fim, a UA4 permitiu transpor regras de negócios para arquiteturas de código robustas e seguras utilizando os pilares da orientação a objetos e da tipagem estrita do TypeScript.



---

## Declaração de Autoria

Declaro que este trabalho foi desenvolvido por mim, 
respeitando as normas acadêmicas e de integridade estabelecidas pela instituição.

**Nome do Estudante:** João Victor Rios Brito e Nascimento

**Data:** 17/06/2026
