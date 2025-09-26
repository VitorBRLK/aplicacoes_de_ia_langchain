# LangChain Tutorials - Conceitos Fundamentais

Este repositório contém uma série de tutoriais sobre os conceitos fundamentais do LangChain, uma estrutura poderosa para construção de aplicações com modelos de linguagem grande (LLMs).

## Estrutura do Repositório

### 1. 02_models.ipynb
Introdução aos modelos de linguagem no LangChain, cobrindo:
- **LLMs (Large Language Models)**: Interface padrão para interagir com diferentes provedores (OpenAI, Cohere, Hugging Face)
- **ChatModels**: Modelos que utilizam mensagens de chat como entrada e saída
- Métodos de chamada: `invoke()`, `stream()`, `batch()`
- Tipos de mensagens: `HumanMessage`, `AIMessage`, `SystemMessage`, `FunctionMessage`, `ToolMessage`

### 2. 03_models_avancado.ipynb
Conceitos avançados sobre modelos:
- **Prompt Few-shot**: Técnica de aprendizado com exemplos
- **Integração com outros modelos**: Utilização do Hugging Face e Mistral
- **Caching**: Otimização de performance com cache em memória e SQLite
- **Debugging**: Como ativar e utilizar o modo de depuração

### 3. 04_prompt_templates.ipynb
Trabalhando com templates de prompt:
- **PromptTemplate**: Criação de templates básicos com variáveis
- **Composição de prompts**: União de múltiplos templates
- **ChatPromptTemplate**: Templates específicos para modelos de chat
- **Few-shot prompting**: Exemplos avançados para LLMs e ChatModels

### 4. 05_output_parsers.ipynb
Formatação e estruturação de saídas:
- **StrOutputParser**: Conversão de saídas de chat para texto
- **Estruturação com Pydantic**: Saídas estruturadas usando `with_structured_output()`
- **Exemplo prático**: Processamento de reviews de clientes com schema definido

## Tecnologias e Dependências

O projeto utiliza as seguintes tecnologias principais:

- **LangChain** (0.3.13) - Framework principal
- **OpenAI** (1.55.3) - Integração com modelos da OpenAI
- **Hugging Face** - Integração com modelos open-source
- **Pydantic** (2.7.4) - Modelagem de dados e validação
- **SQLite** - Cache persistente para otimização

## Pré-requisitos

- Python 3.11+
- Conta na OpenAI (para usar modelos GPT)
- Conta no Hugging Face (opcional, para modelos alternativos)
