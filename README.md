# 💾 Dominando Contas de Armazenamento no Azure

Resumo da aula do bootcamp sobre a criação e configuração de **contas de armazenamento** no Microsoft Azure.

## 🛠️ Criação da Conta de Armazenamento

- **Assinatura e Grupo de Recursos**: escolha a assinatura em uso e defina o grupo de recurso onde a conta ficará.
- **Nome da Conta**: deve ser **exclusivo**, com **3 a 24 caracteres**, contendo apenas **letras minúsculas** e **números**.
- **Região**: selecione a localização do datacenter para hospedar a conta.

## ⚡ Desempenho

- **Standard**: recomendado para cenários gerais.  
- **Premium**: ideal para aplicações que exigem **baixa latência**.

## 🛡️ Redundância

- Configuração demonstrada: **LRS (Locally Redundant Storage)** – garante cópias dos dados dentro de um único datacenter.

## 📂 Serviços Disponíveis

A conta de armazenamento criada oferece:
- **Contêineres (Blob Storage)**  
- **Compartilhamento de Arquivos (File Shares)**  
- **Filas (Queues)**  
- **Tabelas (Tables)**

### 🗃️ Teste de Compartilhamento de Arquivo
- Criado um compartilhamento de arquivo simulando um departamento de TI (sem backup por ser apenas um teste).  
- Em **Propriedades → Conectar**, foi atribuída a letra **M** da unidade.  
- **Autenticação**: chave da conta de armazenamento, gerando um **script** para acesso à máquina.

### 📑 Tabelas de Teste
- Adicionada uma **tabela de teste** com definição de **políticas de acesso**.

## 🚀 Migração para Azure

- Demonstração do **Serviço de Migração** do Azure para transferência de dados e aplicações.

## 🎯 Conclusão

- Aprender a criar e gerenciar contas de armazenamento é essencial para organizar e proteger dados.  
- Escolher corretamente desempenho e redundância garante **custo-benefício** e **resiliência** de acordo com a necessidade do projeto.
