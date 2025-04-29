# DIO-BRADESCO-Desafio-AI-Search
Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

# Laboratório de Organização e Pesquisa de Documentos com IA

## Descrição do Desafio
Este projeto prático explora técnicas avançadas de processamento de documentos utilizando inteligência artificial, com foco em:
- **Ingestão de conteúdo** para IA
- **Criação de índices inteligentes**
- **Exploração de dados organizados**

O objetivo é demonstrar como ferramentas de IA podem transformar grandes volumes de dados não estruturados em informação acionável.

## Tecnologias Utilizadas
- **Azure AI Document Intelligence** (extração de conteúdo)
- **Azure AI Search** (indexação semântica)
- **Azure Blob Storage** (armazenamento de documentos)
- **Python SDK** (automação dos processos)

## Etapas Implementadas

### 1. Ingestão de Conteúdo
- Configuração de pipeline para processar:
  - Documentos em PDF, imagens e formatos textuais
  - Extração estruturada com modelos pré-treinados
- Exemplo de código:
  ```python
  from azure.ai.formrecognizer import DocumentAnalysisClient
  # Configuração do cliente para extração

2. Criação de Índices Inteligentes

Definição de campos indexados:
Metadados (autor, data)
Conteúdo semântico (entidades, relações)
Configuração de skillsets para:
Reconhecimento de entidades
Tradução automática
3. Exploração dos Dados

Consultas semânticas:
Busca por intenção (não apenas keywords)
Filtros por relevância
Visualização de insights:
>>"resultados": {
>>  "termos_chave": ["contrato", "cláusula"],
>>  "relacionamentos": ["assinatura <> validade"]
>>}

Entregáveis

Pipeline de ingestão documental
Índice configurado no Azure AI Search
Notebook Jupyter com análise exploratória
Relatório de insights (PDF ou Markdown)
Como Executar

1.Clone o repositório:
>>git clone [url-do-repositorio]


2.Configure as credenciais no arquivo config.py
3.Execute o pipeline principal:
>>python main.py --input documentos/ --output resultados/

Insights Obtidos

A IA identificou padrões não óbvios em 78% dos contratos analisados
O tempo de busca reduziu em 62% com indexação semântica
Desafios encontrados: [listar brevemente]
Próximos Passos

Integração com Power BI para dashboards
Expansão para documentos em espanhol
Modelo customizado para documentos jurídicos
Nota: Este projeto foi desenvolvido como parte do curso [Nome do Curso] em [Data/Mês/Ano].

### Dicas para personalização:
1. Adicione screenshots do processo (`/assets/imgs/`)
2. Inclua um diagrama de arquitetura (usando [Mermaid.js](https://mermaid.js.org/))
3. Atualize as seções de "Insights" e "Próximos Passos" conforme seus resultados reais
😊
