README — Templates de Peças Jurídicas

Descrição
Esta pasta contém modelos editáveis de peças jurídicas (petição inicial, contestação e recurso de apelação). Os arquivos são modelos base para serem adaptados ao caso concreto.

Arquivos
- peticao_inicial.docx — modelo de petição inicial com campos entre colchetes.
- contestacao.docx — modelo de contestação com estrutura de preliminares, mérito e pedidos.
- recurso_apelacao.docx — modelo de razões de apelação.

Como usar
1. Abra o arquivo no Word, LibreOffice ou Google Docs.
2. Substitua todos os campos entre colchetes [EXEMPLO] pelos dados do caso.
3. Mantenha roteiro lógico (fatos → direito → pedidos) e verifique prazos aplicáveis.
4. Revise e valide todas as citações legais, valores e prazos antes de protocolar.

Campos padrão a preencher
- [COMARCA/UF], [PROCESSO1], [NOME DO AUTOR], [NOME DO RÉU], [CPF1], [ENDERECO1], [VALOR], [NOME DO ADVOGADO], [OAB/UF] etc.

Dicas para preenchimento automático com IA
- Use prompts padronizados (ex.: prompts/prompts.csv p01/p03) para gerar rascunhos com base em fatos informados.
- Fluxos sugeridos:
  1. Forneça ao modelo apenas o bloco “Fatos” e peça resumo em tópicos.
  2. Peça ao modelo para preencher os campos do template com linguagem formal.
  3. Execute o prompt de revisão (p04) para checar omissões e erros.
  4. Revise manualmente e ajuste citações legais e jurisprudência.

Boas práticas
- Anonimize dados sensíveis antes de enviar ao modelo ou indexar em base RAG.
- Sempre realize revisão humana final por advogado responsável.
- Mantenha versão controlada: salve o documento final com nome contendo versão e data (ex.: peticao_inicial_v1_2025-09-25.docx).

Avisos
- Estes modelos são exemplos e não substituem análise jurídica detalhada nem adaptação conforme legislação local.
- Não publicar documentos com dados de clientes neste repositório público.
