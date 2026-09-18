# Desafio Vibecoding Inovatech IA - Agenda de Consultas (React/Vite)

## 📌 O Problema
O desafio consistia em criar uma interface clara e funcional para facilitar o encontro de profissionais de saúde, a consulta de horários e a solicitação de atendimento, resolvendo a complexidade e desorganização dos agendamentos manuais.

## 💡 A Solução Proposta e Escopo Entregue
Foi desenvolvido um Produto Mínimo Viável (MVP) de uma aplicação web responsiva (Mobile e Desktop). A solução engloba uma jornada principal completa:
1. **Catálogo de Especialistas:** Visualização de profissionais com foto, especialidade e breve descrição.
2. **Seleção de Horários:** Interação para visualizar e escolher os horários disponíveis de cada médico.
3. **Solicitação de Atendimento:** Formulário de agendamento com validação básica (campos obrigatórios e validação de formato de e-mail).
4. **Feedback Visual:** Implementação de estados de carregamento (simulação de rede), mensagens de erro e feedback visual de sucesso após o agendamento.

## 🛠️ Tecnologias Utilizadas
A arquitetura do projeto foi gerada utilizando uma *stack* moderna de Front-end:
* **React:** Criação de interfaces de utilizador baseadas em componentes.
* **TypeScript:** Adição de tipagem estática para maior segurança e prevenção de erros no código.
* **Tailwind CSS:** Estilização rápida e responsiva utilizando classes utilitárias.
* **Vite:** Ferramenta de *build* super rápida para inicialização do projeto e ambiente de desenvolvimento.

## 🤖 Uso de Inteligência Artificial e Decisões
* **Ferramenta de IA Utilizada:** Gemini 1.5 Pro (através da interface do Google AI Studio).
* **Decisões Relevantes:** O modelo de IA decidiu autonomamente estruturar o projeto utilizando o ecossistema React/Vite para garantir maior escalabilidade dos componentes, em vez de um simples ficheiro HTML. Aceitei a sugestão da IA para demonstrar a viabilidade de construir um ambiente moderno utilizando *Vibecoding*.
* **Processo:** Forneci os requisitos do edital (dados mockados, validações, responsividade e estados de interface) e a IA estruturou os componentes (`App.tsx`, `index.css`, etc.) com a lógica e estilos necessários.

## 🚀 Como Executar o Projeto Localmente
Para correr este projeto no seu computador, certifique-se de que tem o **Node.js** instalado.
1. Clone este repositório para o seu computador.
2. Abra o terminal na pasta raiz do projeto.
3. Execute o comando `npm install` para instalar as dependências.
4. Execute o comando `npm run dev` para iniciar o servidor de desenvolvimento.
5. Abra o link fornecido no terminal (geralmente `http://localhost:5173`) no seu navegador.

## 🚧 Limitações Atuais
* Os dados dos profissionais, horários e agendamentos são simulados e não persistem numa base de dados real.

## 🔮 Evolução Futura
* Substituir os dados estáticos por chamadas a uma API REST.
* Adicionar um sistema de autenticação e uma base de dados para guardar as marcações de forma definitiva.
