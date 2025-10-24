# 🐾 PetCare – Tecnologia e Inovação no Cuidado com seu Pet

## 🌐 Sobre o Projeto

**PetCare** é um site voltado para a **prestação de serviços para pets**, como **vacinação, banho e tosa, planos de saúde animal, checkups e consultas veterinárias**.  
O projeto foi desenvolvido com o objetivo de **promover e integrar tecnologias em alta no mercado**, como **Lovable**, **N8N** e **Supabase**, além de **sistemas de pagamento modernos**, como **AbacatePay** e **Stripe**.

A ideia principal é demonstrar como é possível construir um **projeto real e funcional** do mercado pet com **baixo investimento**, **alta automação** e **tempo de desenvolvimento reduzido**, utilizando ferramentas no-code e low-code em conjunto com tecnologias web modernas.

---

## 🚀 Tecnologias Utilizadas

O site foi desenvolvido utilizando:

- **Lovable.dev** – Plataforma de desenvolvimento rápido com integração contínua e deploy automático.
- **N8N** – Ferramenta de automação para fluxos de trabalho e integrações.
- **Supabase** – Banco de dados e autenticação em tempo real.
- **Stripe** e **AbacatePay** – Sistemas de pagamento online integrados.
- **React + TypeScript + Vite** – Base do front-end.
- **Tailwind CSS + shadcn-ui** – Design moderno, limpo e responsivo.

---

## 🧩 Funcionalidades

### 👤 Sistema de Login e Registro
- Autenticação segura via **Supabase**.
- Criação e gerenciamento de contas de usuários (tutores de pets e prestadores de serviço).

### 📅 Agendamento de Consultas
- O usuário pode agendar serviços como consultas, banho e tosa, checkups e vacinas.
- Após o agendamento, uma **IA integrada** envia uma **mensagem automática de confirmação**.
- A IA também pode **tirar dúvidas do cliente**, simulando um **atendimento humano inteligente**.

### 💬 Integrações com Webhooks
- Captura de dados e eventos via **webhooks**, conectando o site com **N8N** para automações.
- Exemplo: criação automática de registros no CRM, envio de e-mails ou notificações após uma reserva.

### 💳 Pagamentos Online
- Integração com **AbacatePay** e **Stripe**, permitindo pagamentos rápidos e seguros.
- Possibilidade de adicionar planos mensais de serviços e pacotes personalizados.

### 🧠 CRM e Automação Inteligente
- Integração opcional com **sistemas de CRM** via **N8N**, facilitando a gestão de clientes, agendamentos e histórico de serviços.
- Possibilidade de acompanhamento do cliente após o atendimento por meio de mensagens automatizadas.

---

## 💡 Objetivo do Projeto

O projeto **PetCare** tem como foco **explorar e demonstrar o potencial das tecnologias modernas** para negócios reais, com ênfase em:

- Redução de custos de desenvolvimento.
- Ganho de agilidade e eficiência operacional.
- Criação de **automação inteligente** e **experiência personalizada**.
- Demonstração prática de como **Lovable**, **N8N**, **Supabase** e **sistemas de pagamento integrados** podem trabalhar juntos.

---

## 🛠️ Como Executar o Projeto Localmente

### Pré-requisitos
- [Node.js](https://nodejs.org) (recomendado usar com [nvm](https://github.com/nvm-sh/nvm#installing-and-updating))
- npm ou yarn instalado

### Passos
```bash
# 1️⃣ Clone o repositório
git clone https://github.com/Meizolas/Pet-Care.git

# 2️⃣ Acesse a pasta do projeto
cd petcare

# 3️⃣ Instale as dependências
npm install

# 4️⃣ Inicie o servidor de desenvolvimento
npm run dev
