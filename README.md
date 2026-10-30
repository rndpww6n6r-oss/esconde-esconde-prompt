# Esconde-Esconde Prompt

Aplicação web Node.js para reformular prompts usando a API Gemini do Google AI Studio.

## Render
- Runtime: Node
- Build command: npm install
- Start command: npm start
- Environment variables: `GEMINI_API_KEY` (obrigatória), `GEMINI_MODEL` (opcional; padrão `gemini-2.5-flash`)

O Gemini oferece uma modalidade gratuita com limites de requisições e modelos. A disponibilidade e a cota variam por projeto e podem mudar. Confira os limites ativos no Google AI Studio. Não habilite faturamento pago se a intenção for manter custo zero.

Nunca publique a chave da API no GitHub nem no navegador. Configure-a somente nas variáveis de ambiente do Render. O app não possui banco de dados nem histórico próprio. Os textos são enviados ao Google para processamento; no nível gratuito, o Google informa que pode usar os dados para melhorar seus produtos. Antes de abrir ao público, recomenda-se autenticação, rate limiting e limites de uso. Não use para disfarçar malware, fraude, roubo de credenciais, invasão não autorizada ou evasão de controles.
