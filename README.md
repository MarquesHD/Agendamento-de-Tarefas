# Sistema de Agendamento de Tarefas

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue)

Um sistema web simples e eficiente para agendamento de tarefas, desenvolvido com HTML, CSS e JavaScript puro. O projeto permite cadastrar, visualizar, filtrar e excluir tarefas, com persistência de dados local no navegador (LocalStorage), sem necessidade de backend.

---

## Preview

Interface com barra lateral de cadastro e área principal de listagem, com filtros dinâmicos e faixas coloridas indicando a prioridade de cada tarefa.

<img width="1026" height="779" alt="Capturar" src="https://github.com/user-attachments/assets/51f1c2bd-5d64-46c7-a996-4749affaae23" />


---

## Funcionalidades

- Cadastro de Tarefas: Nome, Data, Horário, Nível de Prioridade (Alta, Média, Baixa) e Descrição opcional.
- Persistência Local: Todas as tarefas são salvas automaticamente no localStorage do navegador. Você pode fechar a página e voltar depois que os dados estarão lá.
- Filtros Avançados:
  - Filtrar por Nível de Prioridade (Alta, Média, Baixa).
  - Filtrar por Data específica (através de um calendário nativo).
  - Filtrar por Período do dia (Manhã, Tarde, Noite).
- Ordenação Automática: As tarefas são exibidas em ordem cronológica (da mais próxima para a mais distante).
- Indicador Visual de Prioridade: Cada tarefa possui uma faixa colorida lateral:
  - Vermelho: Prioridade Alta
  - Laranja: Prioridade Média
  - Verde: Prioridade Baixa
- Exclusão de Tarefas: Remoção com confirmação para evitar acidentes.
- Design Responsivo e Limpo: Inspirado em painéis administrativos modernos, com foco em usabilidade.

---

## Tecnologias Utilizadas

- HTML5: Estrutura semântica da aplicação.
- CSS3: Estilização com Flexbox, variáveis de cores e design responsivo.
- JavaScript (Vanilla): Lógica de negócio, manipulação do DOM, filtros e integração com o localStorage.
- LocalStorage API: Para persistência de dados no lado do cliente.

---

## Como Executar o Projeto

Como o projeto é composto por um único arquivo HTML (com CSS e JS embutidos), a execução é extremamente simples:

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
