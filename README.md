# MasterIA Studio 3.0 — Android PWA

## Instalar / publicar
1. Extraia o ZIP e envie **os arquivos extraídos** para um repositório GitHub seu. Não envie `.env` nem chaves de API.
2. No Render, crie **Web Service** conectado ao repositório (Node).
3. Build command: `npm install`; Start command: `npm start`.
4. Em Environment, crie `MINIMAX_API_KEY` com a chave da sua conta. Nunca coloque a chave no HTML ou GitHub.
5. Abra o endereço HTTPS fornecido pelo Render no Chrome Android. Menu ⋮ → **Adicionar à tela inicial** → **Instalar** (se disponível).

## Limitações importantes
- A geração real de vídeo requer API MiniMax ativa, modelo suportado, créditos e parâmetros aceitos pela conta. A API pode rejeitar certas combinações de duração/resolução. Se isso ocorrer, ajuste o seletor.
- Os filmes são **roteiros de cenas**; a montagem automática dos clipes em um único MP4 não está implementada.
- Os roteiros, anúncios e prompts funcionam localmente por modelos de texto, não por LLM.
- A aba Premium é informativa: não há cobrança nem autenticação implementada.
- O MP4 é disponibilizado por link de download retornado pela MiniMax. Não há promessa de resolução 4K.
- Não testado com uma chave MiniMax real. Verifique as condições e a documentação atual da API antes de consumir créditos.
- Não há garantia de zero bugs; monitore os logs do Render.
