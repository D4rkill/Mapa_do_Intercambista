# Mapa_do_Intercambista

# 🌍 Mapa do Intercambista

O **Mapa do Intercambista** é uma aplicação desenvolvida em **Angular** para auxiliar estudantes e interessados em intercâmbio a explorarem destinos, pacotes e agências de maneira intuitiva, rápida e organizada.  
O projeto integra conceitos de **UX/UI**, **Testes A/B**, **usabilidade**, **arquitetura de software** e **engenharia de software**, desenvolvido como parte das atividades acadêmicas da FACENS.

---

## 🚀 Tecnologias Utilizadas

### **Frontend**
- Angular  
- TypeScript  
- HTML5  
- CSS3  
- Bootstrap  

### **Backend & Banco de Dados**
- Supabase  
  - API REST  
  - Autenticação  
  - PostgreSQL integrado  

### **Ferramentas de Design e Gestão**
- Figma (wireframes e protótipos)  
- Git & GitHub (versionamento)  
- Trello (gestão do projeto)  

---

## 📌 Objetivo do Projeto

Fornecer ao usuário uma plataforma acessível para consultar informações sobre intercâmbio, visualizar **destinos**, **pacotes completos**, **agências parceiras** e navegar por um ambiente otimizado para usabilidade e clareza.

---

## 🧭 Funcionalidades Principais

- Catálogo de pacotes de intercâmbio  
- Visualização de destinos específicos  
- Acesso rápido às agências parceiras  
- Interface responsiva (Bootstrap)  
- Busca dinâmica utilizando Angular  
- Integração com banco de dados via Supabase  
- Navegação fluida com rotas internas  

---

## 🧪 Testes A/B e Usabilidade

Durante o desenvolvimento, foram realizados **Testes A/B** para comparar duas versões da interface:

- **Tela A** – Versão inicial  
- **Tela B** – Versão revisada com melhorias  

Os testes avaliaram:
- Clareza dos elementos na tela  
- Facilidade de navegação  
- Compreensão dos cards  
- Eficiência para completar tarefas  

### **Roteiro aplicado ao usuário**
1. Acessar a seção de **Agências**  
2. Acessar o pacote de **Nova Zelândia**  
3. Acessar o pacote de **Austrália**

### **Exemplos de comentários coletados**
- “O sistema é intuitivo e consegui acessar todas as seções sem dificuldades.”  
- “A navegação foi clara e os pacotes estavam bem organizados.”  
- “Achei rápido encontrar os destinos e acessar cada página.”

Essas informações ajudaram a validar decisões de design e melhorar a experiência final do usuário.

---

## 🧱 Arquitetura do Sistema

A arquitetura foi organizada em três camadas principais:

### **1. Interface (Front-End – Angular)**  
O Angular foi utilizado para estruturar os componentes, gerenciar rotas, controlar estados, consumir APIs e renderizar a interface. A modularização facilita a manutenção e o reuso de elementos, garantindo uma navegação fluida e responsiva.

### **2. API / Lógica de Negócio (Supabase)**  
O Supabase fornece autenticação integrada, endpoints REST e comunicação segura com o banco de dados. As requisições são tratadas pelos serviços do Angular, utilizando `HttpClient` para realizar operações CRUD.

### **3. Banco de Dados (PostgreSQL – Supabase)**  
O banco armazena informações como:
- Destinos  
- Pacotes  
- Agências  
- Usuários cadastrados  

A integração permite consultas rápidas e estruturadas, mantendo a consistência dos dados.

---

## 🖥️ Sistema Operacional

O desenvolvimento foi realizado no:

- **Windows 11 Education – Versão 25H2**

Essa versão oferece compatibilidade com ferramentas de desenvolvimento, estabilidade e suporte ideal para Angular, Node.js, Supabase CLI e demais softwares utilizados.

---

## 📦 Como Rodar o Projeto

### **1. Clonar o Repositório**
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
