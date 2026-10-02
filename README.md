# Duda AnkiCards AI — PWA

## Publicar no Render
1. Coloque esta pasta em um repositório GitHub.
2. No Render, crie um Blueprint/Web Service a partir do repositório. O `render.yaml` já configura build e start.
3. Quando solicitado, informe `OPENAI_API_KEY` no painel do Render. Nunca coloque a chave no código ou no GitHub.
4. Aguarde o deploy e abra a URL `https://...onrender.com`.
5. iPhone/iPad: Safari > Compartilhar > Adicionar à Tela de Início.
6. Mac: abra a URL no Safari/Chrome; a PWA pode ser instalada quando o navegador oferecer a opção.

## Fluxo
Importar PDF/TXT/MD > detectar disciplina (opcional) > Gerar flashcards > revisar > exportar CSV para Anki.

## IA
Modelo padrão: `gpt-5.6-luna`, configurável pela variável `OPENAI_MODEL`.
A chave fica somente no backend (`OPENAI_API_KEY`).
