# Esconde-Esconde Prompt

Aplicação web Node.js para reformular prompts usando a API da OpenAI.

## Render
- Runtime: Node
- Build command: npm install
- Start command: npm start
- Environment variables: OPENAI_API_KEY (obrigatória), OPENAI_MODEL (opcional; padrão gpt-4.1-mini)

Nunca publique a chave da API no GitHub nem no navegador. Configure-a somente nas variáveis de ambiente do Render. Chamadas à API podem gerar custos.

O app não possui banco de dados nem histórico próprio. Os textos são enviados ao provedor de IA para processamento. Antes de abrir ao público, recomenda-se autenticação, rate limiting e limites de uso. Não use para disfarçar malware, fraude, roubo de credenciais, invasão não autorizada ou evasão de controles.
