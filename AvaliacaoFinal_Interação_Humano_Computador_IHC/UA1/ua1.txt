# UA1 – Introdução à IHC e seus benefícios

## Objetivo
Aplicar os princípios fundamentais de Interação Humano-Computador para diagnosticar problemas de usabilidade em um sistema existente e propor soluções que melhorem a experiência do usuário, com ênfase em clareza de ações, feedback visual e prevenção de erros críticos.

## Análise do Problema
Realizou-se a análise de um painel de controle de gerenciamento de estoque que apresentava deficiências significativas na comunicação visual. Os principais problemas identificados incluíram:
- Ícones genéricos sem contexto adequado
- Sequência de passos não intuitiva
- Ausência de confirmação antes de ações irreversíveis
- Falta de contraste entre elementos interativos

## Solução Desenvolvida
A solução implementada envolveu a reorganização hierárquica dos elementos, introdução de microcópias explicativas, implementação de diálogos de confirmação com linguagem clara e aumento do contraste visual para melhor legibilidade. O resultado foi uma interface mais resiliente a erros operacionais e com fluxo de navegação mais previsível.

Para a implementação prática (como visto no exemplo do Sistema de Folha de Pagamento), a estrutura HTML5 e CSS3 focou em:
1. **Semântica:** Uso da tag `<dialog>` nativa do HTML5 para pop-ups de confirmação.
2. **Acessibilidade:** Foco automático no teclado para leitores de tela.
3. **Clareza:** Substituição de rótulos ambíguos ("Avançar") por comandos diretos ("Confirmar Exclusão" e "Cancelar").
4. **Prevenção de Erros:** Inversão do padrão de cores, destacando o botão de confirmação de exclusão com cor de alerta (vermelho).


