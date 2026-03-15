# ClipMaker

ClipMaker é um protótipo de interface para extrair momentos virais de vídeos usando IA, Cloudinary e geração de transcrições.

Veja funcionando [aqui](https://lazaro277.github.io/clip-maker/)

## Estrutura do Projeto

- `index.html` — página principal com UI para inserir API Key, enviar vídeo e exibir o preview.
- `draw.excalidraw` — diagrama de design/fluxo (formato Excalidraw).

## Como usar

1. Abra `index.html` no navegador.
2. Insira sua API Key do Gemini (ou o provedor configurado pelo projeto).
3. Clique em **Enviar vídeo** e aguarde o processamento.

## Tecnologias usadas

- Tailwind CSS (CDN)
- Lucide Icons
- GSAP (animações)
- Cloudinary Upload Widget

## Notas

- O projeto é uma interface de demonstração; a lógica de backend (processamento de vídeo/transcrição) depende de serviços externos.
