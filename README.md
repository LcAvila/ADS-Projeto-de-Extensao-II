# 🛠️ Sistema de Controle de Equipamentos Calibrados

Sistema web desenvolvido para controle e gerenciamento de equipamentos calibrados na área de metrologia. A aplicação permite o cadastro, edição e visualização de instrumentos, especificações técnicas, datas de calibração e prazos de vencimento.

Este projeto foi criado como parte da disciplina **Projeto de Extensão II – Análise e Desenvolvimento de Sistemas** do curso de **ADS – UNOPAR / Anhanguera**, com aplicação prática na empresa **Compactor**, em colaboração com o metrologista **Sérgio Luis Zago**.

---

## ✨ Funcionalidades

- 📋 Cadastro de equipamentos
- 🛠️ Registro de especificações técnicas
- 🕑 Controle de datas de calibração e vencimento
- 📢 Alertas de equipamentos prestes a vencer
- 📊 Painel de visualização de status
- 🔒 Autenticação de usuário (em desenvolvimento)
- 🌐 Deploy online com acesso público

---

## 🚀 Tecnologias Utilizadas

| Tecnologia        | Descrição                                      |
|-------------------|-----------------------------------------------|
| **React.js**      | Biblioteca para construção de interfaces      |
| **Next.js**       | Framework para aplicações React com SSR       |
| **Tailwind CSS**  | Framework CSS utilitário para estilização     |
| **JavaScript**    | Linguagem principal do front-end              |
| **Prisma ORM**    | Mapeamento de banco de dados relacional       |
| **SQLite** / PostgreSQL | Banco de dados leve e simples para produção    |
| **Vercel**        | Plataforma de deploy automático para Next.js  |

---

## 📦 Instalação Local

```bash
# Clone o repositório
git clone https://github.com/seuusuario/controle-calibracao.git

# Acesse a pasta do projeto
cd controle-calibracao

# Instale as dependências
npm install

# Configure o banco de dados
npx prisma generate
npx prisma migrate dev

# Inicie o servidor de desenvolvimento
npm run dev
```

---

## 📷 Capturas de Tela (exemplo)

> Adicione aqui prints das telas do sistema, como dashboard, cadastro, alertas etc.

---

## 📌 Sobre o Projeto

Este sistema foi idealizado para resolver um problema real enfrentado por profissionais de metrologia: a **dificuldade de controlar e acompanhar equipamentos com prazos de calibração** utilizando apenas planilhas manuais. Com o sistema, é possível **automatizar o acompanhamento**, ter **mais clareza nas especificações dos instrumentos** e manter a **qualidade e confiabilidade dos processos da empresa**.

---

## 🎓 Projeto de Extensão Acadêmica

Projeto desenvolvido para a disciplina **Projeto de Extensão II**, com vínculo ao **Programa de Ação e Difusão Cultural**. Mesmo não estando diretamente ligado a uma atividade cultural artística, este projeto contribui para a **cultura organizacional da qualidade** e o apoio a setores que garantem a excelência em produtos usados em ambientes escolares, artísticos e técnicos.

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** – veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🙋 Autor

Desenvolvido por **Lucas de Souza Ávila**  
📧 avila.estudohtml@gmail.com 
🔗 [linkedin.com/in/seu-perfil](https://linkedin.com/in/seu-perfil](https://www.linkedin.com/in/devlucasavila/)

---

## 🌐 Acesso ao Projeto Online

🔗 [https://metrologia-cq.vercel.app](https://metrologia-cq.vercel.app)
