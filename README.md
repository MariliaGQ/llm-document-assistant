# LLM Document Assistant

Assistente de consulta a documentos utilizando **Large Language Models (LLMs)**, desenvolvido como **projeto de estudo aplicado** para compreensão de fluxos de interação entre documentos e modelos de linguagem.

O projeto explora como arquivos podem ser carregados, interpretados e utilizados como contexto em conversas com LLMs, de forma simples e controlada.

---

## 🎯 Objetivo

Compreender e experimentar:

- Consumo de documentos por LLMs  
- Injeção de contexto textual em prompts  
- Arquitetura básica de um chat orientado a documentos  
- Separação de responsabilidades entre interface, carga de dados e IA  

---

## 🧠 O que este projeto é

- Um **assistente de documentos baseado em LLM**
- Um **projeto educacional com foco em arquitetura e entendimento técnico**
- Um laboratório para experimentação consciente de IA aplicada

---

## 🚫 O que este projeto NÃO é

- Uma solução enterprise  
- Um sistema escalável de RAG  
- Um mecanismo de busca vetorial  
- Um produto pronto para produção  

---

## 🧱 Arquitetura (visão geral)

- **Interface:** Streamlit  
- **Camada de IA:** LangChain + LLM  
- **Carga de documentos:** HTML, PDF e TXT  
- **Estratégia:** Contexto textual direto (sem embeddings ou banco vetorial)

---

## 📂 Estrutura do projeto

    src/
    ├─ chat.py        # Interface e lógica de interação com o LLM
    ├─ loaders.py     # Carregamento de documentos (HTML, PDF, TXT)

---

## 🚀 Como executar

### 1️⃣ Instalar dependências

```bash
pip install -r requirements.txt
```

### 2️⃣ Configurar variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto:

```text
OPENAI_API_KEY=your_api_key
```

### 3️⃣ Executar a aplicação

```bash
streamlit run src/chat.py
```

---

## 📘 Principais aprendizados

- Diferença entre contexto direto e RAG  
- Limitações de escala sem uso de embeddings  
- Importância de controle do tamanho do contexto  
- Organização de código para facilitar evolução futura  

---

## 🔭 Possíveis evoluções

- Implementação de chunking de documentos  
- Uso de embeddings para recuperação semântica  
- Integração com banco vetorial  
- Evolução para um padrão RAG completo  

---

## 🧪 Contexto do projeto

Este projeto faz parte de um processo contínuo de aprendizado em **Engenharia de IA**, com foco em compreensão arquitetural, experimentação prática e tomada consciente de decisões técnicas.
