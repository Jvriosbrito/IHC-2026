# Avaliação Final – Interação Humano-Computador (IHC)

## Identificação do Estudante

- Nome: João Victor Rios Brito e Nascimento
- Matrícula: 22400050
- Curso: Ciêcias da Computação
- Polo: Asa Norte
- Data de Entrega: 17/06/2026

## Descrição Geral

Este repositório reúne as atividades desenvolvidas durante a disciplina de Interação Humano-Computador (IHC), contemplando os desafios das Unidades de Aprendizagem UA1, UA2, UA3 e UA4. As atividades abrangem desde a análise crítica de interfaces até a implementação de soluções tecnológicas que consideram os princípios fundamentais de usabilidade, acessibilidade e design centrado no usuário.

---

## UA1 – Introdução à IHC e seus benefícios

### Objetivo

Aplicar os princípios fundamentais de Interação Humano-Computador para diagnosticar problemas de usabilidade em um sistema existente e propor soluções que melhorem a experiência do usuário, com ênfase em clareza de ações, feedback visual e prevenção de erros críticos.

### Solução Desenvolvida

Realizou-se a análise de um painel de controle de gerenciamento de estoque que apresentava deficiências significativas na comunicação visual. Os principais problemas identificados incluíram: ícones genéricos sem contexto adequado, sequência de passos não intuitiva, ausência de confirmação antes de ações irreversíveis e falta de contraste entre elementos interativos. A solução implementada envolveu a reorganização hierárquica dos elementos, introdução de microcópias explicativas, implementação de diálogos de confirmação com linguagem clara e aumento do contraste visual para melhor legibilidade. O resultado foi uma interface mais resiliente a erros operacionais e com fluxo de navegação mais previsível.

### Arquivos Entregues

- UA1_interface.html
- UA1_ua1.md

---

## UA2 – Interface, interação e Affordance

### Objetivo

Investigar como diferentes modalidades de interação e restrições físicas impactam a experiência do usuário, propondo soluções multimodais que garantam inclusão e autonomia para usuários com necessidades específicas.

### Solução Desenvolvida

Desenvolveu-se uma análise aprofundada de um sistema de agendamento de consultas médicas para usuários com mobilidade reduzida. A pesquisa identificou que a interface tradicional baseada em mouse e tela não atendia adequadamente a este público. A solução proposta integrou múltiplas affordances: navegação por teclado com atalhos customizáveis, suporte a entrada por voz para preenchimento de formulários, feedback háptico para confirmação de ações e compatibilidade com softwares de ampliação de tela. Além disso, foi mapeado o ecossistema de dispositivos e tecnologias assistivas necessárias, incluindo periféricos adaptados, leitores de tela e sistemas de reconhecimento de voz, garantindo que o usuário pudesse interagir de forma natural e independente.

### Arquivos Entregues

- UA2_Analise_Multimodal.txt

---

## UA3 – Storyboarding e prototipação de interfaces

### Objetivo

Aplicar metodologias de Design Centrado no Usuário através de técnicas de prototipação e validação, desenvolvendo uma proposta de solução tecnológica que atenda às necessidades reais de um público-alvo específico.

### Solução Desenvolvida

Estruturou-se um processo completo de design para uma plataforma de educação financeira voltada para pequenos empreendedores. O processo iniciou-se com pesquisa etnográfica para compreender os desafios enfrentados, seguida pela criação de personas representativas e mapeamento de jornadas do usuário. Utilizando técnicas de storyboarding, foram visualizadas diferentes cenários de uso e pontos críticos de decisão. Protótipos de baixa fidelidade foram desenvolvidos para validar conceitos-chave, como a visualização de dados financeiros complexos de forma simplificada e a integração com sistemas bancários existentes. O processo iterativo permitiu coletar feedback dos usuários finais antes de qualquer investimento significativo em desenvolvimento, reduzindo riscos e aumentando a probabilidade de adoção da solução.

### Ferramentas Utilizadas

- Storyboarding
- Jornada do Usuário
- Ferramentas de prototipação de baixa fidelidade

### Arquivos Entregues

- UA3_Storyboards.pdf
-UA3_Prototipos_Baixa_Fidelidade.fig

---

## UA4 – TypeScript

### Objetivo

Implementar um sistema de gerenciamento de biblioteca utilizando Programação Orientada a Objetos em TypeScript, demonstrando domínio de tipagem forte, encapsulamento e reutilização de código.

### Funcionalidades Implementadas

- Classe Livro: Modelagem de entidades de livro com atributos como isbn (identificador único), titulo, autor, anoPublicacao e disponivel (booleano), com validação de tipos em tempo de compilação
Classe Usuario: Representação de usuários da biblioteca com propriedades id, nome, email e livrosEmprestados (array tipado de Livro).
- Classe Biblioteca: Gerenciadora central que mantém coleções de livros e usuários, implementando métodos como adicionarLivro(), emprestarLivro(), devolverLivro() e listarDisponibilidade().
- Método calcularMulta(): Função que calcula multas por atraso na devolução baseada em dias em atraso e valor diário configurável.
- Relatórios Tipados: Geração de relatórios estruturados sobre empréstimos ativos, histórico de transações e estatísticas de uso.

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

- UA4_Biblioteca/src/index.ts
- UA4_Biblioteca/src/models/Livro.ts
- UA4_Biblioteca/src/models/Usuario.ts
- UA4_Biblioteca/src/models/Biblioteca.ts
- UA4_Biblioteca/package.json
- UA4_Biblioteca/tsconfig.json

---

Uso de Inteligência Artificial (IA)

Para o desenvolvimento e documentação destas atividades, foi utilizada a Inteligência Artificial Manus. O uso da tecnologia limitou-se estritamente a:

- Revisão estrutural e gramatical da documentação, assegurando clareza e profissionalismo no texto.
- Validação de sintaxe e boas práticas em código TypeScript, garantindo conformidade com padrões da indústria.
- Pesquisa sobre padrões de design orientado a objetos aplicáveis aos contextos específicos de cada atividade.

A concepção de soluções, análises de usabilidade, decisões de design, modelagem de dados e resolução de problemas foram desenvolvidas através de pensamento crítico e análise independente, respeitando integralmente os princípios acadêmicos de autoria intelectual.



## Considerações Finais

O percurso através das quatro unidades de aprendizagem revelou a profunda interconexão entre teoria e prática em IHC. As primeiras unidades demonstraram que decisões de design aparentemente simples, como escolha de palavras, posicionamento de elementos e feedback visual, possuem impacto exponencial na experiência do usuário e na prevenção de erros. A exploração de múltiplas modalidades de interação ampliou a perspectiva sobre inclusão digital, evidenciando que acessibilidade não é um recurso adicional, mas uma necessidade fundamental.

A prototipação e validação com usuários reais confirmaram a importância de envolver o público-alvo desde as fases iniciais do design, evitando desenvolvimentos custosos baseados em suposições incorretas. Por fim, a implementação técnica em TypeScript conectou os conceitos abstratos de IHC com a realidade da engenharia de software, demonstrando como uma arquitetura bem pensada reflete diretamente na qualidade da interação humano-computador.





---

## Declaração de Autoria

Declaro que este trabalho foi desenvolvido por mim, 
respeitando as normas acadêmicas e de integridade estabelecidas pela instituição.

**Nome do Estudante:** João Victor Rios Brito e Nascimento

**Data:** 17/06/2026
