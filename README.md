# Configurando-uma-instancia-de-Banco-de-Dados-na-Azure
The following repository was created by me as part of a Bootcamp project for evaluation and approval purposes. Although the task involves basic steps and configurations, the implementation was carried out according to the requirements described in the Challenge Description.
Este repositório foi criado por mim como parte de um projeto de Bootcamp para fins de avaliação e aprovação. Embora a tarefa envolva etapas e configurações básicas, a implementação foi realizada conforme os requisitos descritos na Descrição do Desafio.

# 📘 Projeto de Desafio - Bootcamp DIO

> ⚠️ O seguinte README refere-se a um projeto para a obtenção de nota ou aprovação em um Bootcamp da DIO e está de acordo com a respectiva **"Descrição do Desafio"** que possuir.  
> Em determinados casos, o projeto possui entregas **simplesmente visuais que sejam apresentadas neste README do GitHub**. Neste caso, a entrega do projeto será realizada por **meio deste arquivo**.

---

## 🎯 Objetivos do Projeto

- ✅ Aplicar os conceitos apresentados durante as aulas em um ambiente prático;
- ✅ Documentar o processo técnico de forma clara e estruturada;
- ✅ Utilizar o GitHub como ferramenta de versionamento e compartilhamento da documentação do projeto.

---

## 🖥️ Passos Realizados

A seguir, os passos executados para a criação de uma instância de **Banco de Dados SQL** na plataforma Microsoft Azure, utilizando uma conta **Trial**:

### 🔹 Criando o Recurso
- Acesse o Portal do Azure.
- Clique em **Criar um novo recurso** e busque por **SQL Database**.

![marketplace](https://github.com/user-attachments/assets/dd46c001-3fdd-46a1-896e-2c2951dc5151)


---

### 🔹 Tela *Basics*
- Subscription: selecionada a assinatura Trial.
- Resource Group: definido manualmente.
- Nome do banco de dados: `dblabvbtst-ph`.
- Servidor SQL: reutilizado de labs anteriores.
- Elastic Pool: **não utilizado**.
- Ambiente: **Dev**.
- Redundância de backup: **LRS (Locally-Redundant Storage)**, já que o ambiente é temporário e de laboratório.

![Basics-tela](https://github.com/user-attachments/assets/4875962b-3e31-4cad-b60a-32163881c8ac)

---

### 🔹 Tela *Networking*
- Todas as configurações foram mantidas como padrão.

---

### 🔹 Tela *Security*
- Todas as configurações foram mantidas como padrão.

---

### 🔹 Tela *Additional Settings*
- Todas as configurações foram mantidas como padrão.

---

### 🔹 Tela *Tags*
- Adicionadas **tags de billing**, incluindo:
  - Tag: `Ambiente`
  - Valor: `prj-lab-java-ai-europe`
- Isso possibilita controle de gastos futuros relacionados ao Bootcamp.

![tags-tela](https://github.com/user-attachments/assets/ab73bd27-2065-43b4-b791-f9886ae96e9f)

---

### 🔹 Tela *Review + Create*
- Todas as validações foram concluídas com sucesso.
- Cliquei em **Create** para iniciar a criação da instância do banco de dados.

![review+create tela](https://github.com/user-attachments/assets/6f997eda-d5d4-41a6-bb58-b7c132f7eaba)

Custo previsto:
![Basics-tela-custo](https://github.com/user-attachments/assets/f20a7c7e-dff3-41e2-826c-9dc04148e149)


---

### 🔹 Tela *Deployment*
- O processo de deploy foi realizado com sucesso.
- O banco está pronto para uso e testes.

![Deploy-tela](https://github.com/user-attachments/assets/4d031764-de4f-4fa1-b507-185e916c94ce)

---

## 🧾 Notas Finais

Este README documenta o processo completo de criação de um banco de dados SQL no Azure, conforme orientado no desafio proposto no Bootcamp DIO.  
As imagens estão organizadas na pasta `/images` e o repositório segue a estrutura definida para entregas visuais.

---
# 📘 Projeto de Desafio - Bootcamp DIO

> ⚠️ O seguinte README refere-se a um projeto para a obtenção de nota ou aprovação em um Bootcamp da DIO e está de acordo com a respectiva **"Descrição do Desafio"** que possuir.  
> Em determinados casos, o projeto possui entregas **simplesmente visuais que sejam apresentadas neste README do GitHub**. Neste caso, a entrega do projeto será realizada por **meio deste arquivo**.

---

## 🎯 Objetivos do Projeto

- ✅ Aplicar os conceitos apresentados durante as aulas em um ambiente prático;
- ✅ Documentar o processo técnico de forma clara e estruturada;
- ✅ Utilizar o GitHub como ferramenta de versionamento e compartilhamento da documentação do projeto.

---

## 🖥️ Passos Realizados

A seguir, os passos executados para a criação de uma instância de **Banco de Dados SQL** na plataforma Microsoft Azure, utilizando uma conta **Trial**:

### 🔹 Criando o Recurso
- Acesse o Portal do Azure.
- Clique em **Criar um novo recurso** e busque por **SQL Database**.

> ![Imagem - SQL Database Marketplace](./images/sql-database-marketplace.png)

---

### 🔹 Tela *Basics*
- Subscription: selecionada a assinatura Trial.
- Resource Group: definido manualmente.
- Nome do banco de dados: `dblabvbtst-ph`.
- Servidor SQL: reutilizado de labs anteriores.
- Elastic Pool: **não utilizado**.
- Ambiente: **Dev**.
- Redundância de backup: **LRS (Locally-Redundant Storage)**, já que o ambiente é temporário e de laboratório.

> ![Imagem - Tela Basics](./images/sql-database-basics.png)

---

### 🔹 Tela *Networking*
- Todas as configurações foram mantidas como padrão.

> ![Imagem - Tela Networking](./images/sql-database-networking.png)

---

### 🔹 Tela *Security*
- Todas as configurações foram mantidas como padrão.

> ![Imagem - Tela Security](./images/sql-database-security.png)

---

### 🔹 Tela *Additional Settings*
- Todas as configurações foram mantidas como padrão.

> ![Imagem - Tela Additional Settings](./images/sql-database-additional-settings.png)

---

### 🔹 Tela *Tags*
- Adicionadas **tags de billing**, incluindo:
  - Tag: `Ambiente`
  - Valor: `prj-lab-java-ai-europe`
- Isso possibilita controle de gastos futuros relacionados ao Bootcamp.

> ![Imagem - Tela Tags](./images/sql-database-tags.png)

---

### 🔹 Tela *Review + Create*
- Todas as validações foram concluídas com sucesso.
- Cliquei em **Create** para iniciar a criação da instância do banco de dados.

> ![Imagem - Tela Review](./images/sql-database-review.png)

---

### 🔹 Tela *Deployment*
- O processo de deploy foi realizado com sucesso.
- O banco está pronto para uso e testes.

> ![Imagem - Tela Deployment](./images/sql-database-deployment.png)

---

## 🧾 Notas Finais

Este README documenta o processo completo de criação de um banco de dados SQL no Azure, conforme orientado no desafio proposto no Bootcamp DIO.  

---
