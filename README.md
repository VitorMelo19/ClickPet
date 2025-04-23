# 🐾 ClickPet - Sistema Web de Petshop!
---
<p align="center">
  <img src="https://github.com/user-attachments/assets/9b389af7-4467-4ee7-8ff5-3ba260b5a59a" alt="Site_ClickPet" width="800"/>
</p>

## Desenvolvedor:
- [Vitor Melo](https://github.com/VitorMelo19)
---

## Professor Orientador:
- [Me. Franscisco de Souza Escobar](https://www.linkedin.com/in/francisco-escobar/)

---

## 📑 Funcionalidades Principais
- Página inicial com informações sobre a ClickPet.
- Seções: Home, Sobre Nós, Nossa História, Visão e Missão, Nossos Serviços e Contato.
- Design moderno, responsivo e com animações.

---

## 🔐 Autenticação e Cadastro

### Login
- Tela de login com campos de e-mail e senha.
- Redirecionamento para área do cliente ou administrador após autenticação.

### Escolha de Cadastro
- Tela onde o usuário escolhe se deseja se cadastrar por:
  - Conta Google (OAuth)
  - Conta Apple (em desenvolvimento)
  - Formulário padrão (nome, sobrenome, CPF/CNPJ, endereço, celular, e-mail e senha)

### Cadastro (formulário)
- Tela com inputs organizados em duas colunas.
- Coleta completa dos dados do cliente.

---

## 👤 Dashboard do Cliente

Acessado apenas após login, permite ao usuário:

### Página Inicial
- **Serviços usados recentemente**
- **Próximos agendamentos**
- **Pets cadastrados**
- Carrossel com imagens promocionais
- Chat lateral e menu fixo com atalhos

### Página de Agendamento
- Escolha de pet já cadastrado
- Seleção de data, horário e serviço
- Envio de observações adicionais

### Configurações
- Edição dos dados pessoais do cliente
- Edição e cadastro de pets (nome, idade, raça, nascimento, gênero)

---

## 🛠️ Dashboard do Administrador

Acesso restrito com base na role do usuário. Funcionalidades:

### Gerenciamento Completo
- **Agendamento de serviços para clientes**
- **Cadastro e edição de serviços**
- **Cadastro e edição de clientes**
- **Cadastro e edição de pets por cliente**

### Agendamento em 3 Etapas
1. Buscar cliente
2. Selecionar pet(s)
3. Definir data, horário, serviço e observações

### Telas em sobreposição
- Fluxo guiado com sobreposições modais
- Navegação dinâmica sem redirecionamentos

---

## 🎨 Layout e Design

- Design clean, acessível e atrativo
- Utilização de AOS (Animate on Scroll) para transições
- Imagens personalizadas e responsividade mobile
- Ícones representativos e navegação intuitiva
- Cores principais: **laranja e azul**, em harmonia com a identidade visual

---

## 🧠 Tecnologias Utilizadas

- **HTML5**, **CSS3**, **JavaScript**
- Animações com **AOS.js**
- Integração com **Google OAuth**
- Lógica de agendamento e autenticação com **JavaScript**
- Backend (não incluso neste repositório) esperado para: autenticação, banco de dados, validação e persistência

---

## 🚀 Como usar

1. Clone o repositório
2. Abra o `index.html` para visualizar o site principal
3. Acesse `login.html` para simular login
4. Teste os dashboards de acordo com o tipo de usuário

---

## 📸 Imagens de Demonstração (Sugestão)

> Você pode adicionar capturas de tela das principais páginas aqui.

---

## 📌 Observações

- O fluxo com Apple ainda será implementado.
- O sistema depende de backend (Node.js ou outro) para persistência real de dados.
