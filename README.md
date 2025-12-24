# Sistema de Multas (DETRAN)

> Projeto desenvolvido para praticar **Estruturas Condicionais** e manipulação do DOM.

Este simulador simples verifica a velocidade de um veículo inserida pelo usuário. Baseado em um limite predefinido (100km/h), o sistema toma uma decisão lógica para informar se o condutor foi multado ou se está dentro das leis de trânsito.

## Tecnologias Utilizadas

- **HTML5** (Estrutura e Inputs)
- **JavaScript** (Lógica de decisão e interação com a página)

## Funcionalidades

- [x] **Entrada de Dados:** Captura a velocidade informada no campo numérico.
- [x] **Conversão de Tipos:** Garante que o valor seja tratado como número (`Number()`) para comparações matemáticas corretas.
- [x] **Verificação de Limite:** Utiliza a estrutura condicional `if` para verificar se a velocidade ultrapassa 100km/h.
- [x] **Feedback Visual:**
    - Se ultrapassar o limite: Exibe mensagem de **Multa** com destaque em negrito.
    - Se estiver dentro do limite: Exibe mensagem de aprovação.
- [x] **Injeção de HTML:** Uso de `innerHTML` para inserir tags HTML (como `<strong>`) dinamicamente na resposta.

## Aprendizados e Destaques do Código

1. **Estrutura Condicional Composta:** Diferente de um `if` simples, aqui utilizei o bloco `if/else` para garantir que o usuário sempre receba uma resposta, seja ela positiva ou negativa.
2. **Template Strings:** Uso de crases (`` ` ``) para misturar texto com variáveis (`${vel}`) de forma limpa.
3. **Manipulação de Tags via JS:** Aprendi que posso escrever tags HTML (como `<strong>`) dentro da string do JavaScript e o navegador renderiza isso visualmente, permitindo destacar palavras importantes na mensagem de erro.

## Como rodar o projeto

1. Clone este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Digite uma velocidade (ex: 120) e clique em "Identificar" para ver a lógica da multa funcionar.

---
Desenvolvido por **Fabio** durante estudos de Lógica de Programação.
