# 🚀 Azure OpenAI e Semantic Kernel

Este repositório contém um resumo do aprendizado sobre a utilização do **Azure OpenAI** e **Semantic Kernel**, incluindo chamadas de API e a configuração do serviço na nuvem.

## 📌 Objetivo
O objetivo deste estudo é explorar a integração de **modelos de IA** no Azure OpenAI, realizar chamadas de API e entender o uso do **Semantic Kernel** para agentes inteligentes.

---

## 📖 Conteúdo
### 🔹 **1. Configurando o Azure OpenAI**
- Criando e configurando uma conta no Azure.
- Gerenciamento de **modelos e endpoints**.
- Configuração de **cotas e limitações**.
- Implementação de **filtros de conteúdo**.
- Boas práticas de **segurança e armazenamento de dados**.

### 🔹 **2. API do Azure OpenAI**
- Chamadas de API suportadas:
  - `Chat`
  - `Completion`
  - `Imagens`
  - `Áudio`
- Estrutura de uma requisição `POST`.
- Parâmetros importantes: `model_id`, `temperature`, `max_tokens`, etc.
- Exemplos de código para chamadas via **Python**.

### 🔹 **3. Introdução ao Semantic Kernel**
- O que é o **Semantic Kernel**?
- Principais componentes:
  - **Kernel** → Middleware de IA.
  - **Functions** → Funções programáveis.
  - **Memory** → Armazenamento e recuperação de informações.
  - **Vector Stores** → Busca otimizada de dados.
- Criando um **Agente de IA**.
- Exemplo prático de uso.

---

## 🛠 Tecnologias Utilizadas
- **Azure OpenAI**
- **Python** (para chamadas de API)
- **Semantic Kernel**
- **Azure Monitor** (para logs e segurança)

---

## 📂 Estrutura do Projeto
```
📦 azure-openai-semantic-kernel
 ┣ 📜 README.md  # Documentação do projeto
 ┣ 📂 src        # Códigos-fonte
 ┃ ┣ 📜 api_example.py  # Exemplo de chamada API
 ┃ ┣ 📜 semantic_kernel_example.py  # Exemplo de uso do Semantic Kernel
 ┣ 📂 docs       # Documentação extra
 ┗ 📂 assets     # Imagens e materiais de apoio
```

---

## 🚀 Como Executar os Exemplos
### 🔹 **1. Configurar ambiente**
Certifique-se de ter **Python 3.8+** e as bibliotecas necessárias:
```sh
pip install openai semantic-kernel azure-ai-monitor
```

### 🔹 **2. Definir variáveis de ambiente**
```sh
export AZURE_OPENAI_ENDPOINT="SEU_ENDPOINT"
export AZURE_OPENAI_API_KEY="SUA_CHAVE"
export AZURE_OPENAI_DEPLOYMENT_NAME="SEU_MODELO"
```

### 🔹 **3. Executar exemplos**
```sh
python src/api_example.py
python src/semantic_kernel_example.py
```

---

## 📌 Links Úteis
- 📄 [Documentação Oficial do Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
- 📄 [Documentação do Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/overview/)
- 📄 [Modelos do Azure OpenAI](https://azure.microsoft.com/en-us/products/ai-model-catalog)

---

## 📢 Contribuição
Sinta-se à vontade para abrir **issues** ou enviar **pull requests** com melhorias!

📧 Contato: *[Seu Email ou LinkedIn]*
