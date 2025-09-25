Meu Assistente Jurídico

Descrição
Este repositório contém um conjunto de recursos (prompts, templates de peças jurídicas, notebooks e scripts) para construir um assistente jurídico MVP com técnicas como RAG (Retrieval-Augmented Generation), OCR e automação. É um material de apoio e prova de conceito para escritórios de advocacia que desejam explorar IA aplicada ao trabalho jurídico.

Avisos importantes
- Não suba ou compartilhe dados de clientes ou documentos sensíveis neste repositório público.
- Sempre revise manualmente qualquer conteúdo gerado por IA antes de utilizá-lo em processos ou comunicações oficiais.
- Adapte os templates e scripts conforme a política do seu escritório e legislação aplicável (LGPD).

Estrutura sugerida do repositório
- README.md — este arquivo.
- LICENSE — licença do projeto (ex.: MIT).
- .gitignore — arquivos a serem ignorados pelo Git.
- prompts/ — CSV com prompts prontos.
  - prompts/prompts.csv
- templates/ — templates de peças jurídicas (texto prontos para salvar em .docx)
  - templates/peticao_inicial.docx
  - templates/contestacao.docx
  - templates/recurso_apelacao.docx
- scripts/ — scripts auxiliares em Python
  - scripts/ocr_preprocess.py
  - scripts/indexacao_rag.py
- notebooks/ — Jupyter notebook de exemplo
  - notebooks/mvp_rag.ipynb
- requirements.txt — dependências Python sugeridas

Como usar (rápido)
1. Clone o repositório no seu notebook:
   git clone https://github.com/ig1965or/meu-assistente-juridico.git

2. Crie e ative um ambiente virtual:
   python -m venv venv
   # No Linux/Mac
   source venv/bin/activate
   # No Windows (PowerShell)
   .\venv\Scripts\Activate.ps1

3. Instale dependências:
   pip install -r requirements.txt

4. Configure variáveis de ambiente (ex.: OpenAI API key):
   export OPENAI_API_KEY="sua-chave-aqui"   # Linux/Mac
   setx OPENAI_API_KEY "sua-chave-aqui"     # Windows (definir via PowerShell)

5. Teste o notebook:
   jupyter notebook notebooks/mvp_rag.ipynb
   (ou abra via Jupyter Lab)

Conteúdo principal
- Prompts: coleção de prompts para tarefas jurídicas (resumo de peças, extração de cláusulas, geração de teses, revisão e anonimização).
- Templates de peças: petição inicial, contestação e recurso de apelação em formato editável.
- Scripts: OCR e pré-processamento de PDFs, indexação de textos com embeddings e criação de base RAG.
- Notebook: fluxo mínimo para indexar textos, recuperar trechos e responder perguntas com referências.

Boas práticas recomendadas
- Anonimize documentos antes de indexar ou compartilhar.
- Registre logs de consultas e decisões automatizadas.
- Defina processos de revisão humana para cada tipo de saída (rascunho de peça, estratégia, orientação ao cliente).
- Escolha licença apropriada e adicione aviso de responsabilidade jurídica nos templates.

Contribuições
Pull requests são bem-vindos. Para alterações relevantes, abra uma issue descrevendo a proposta antes de submeter o PR.
