ORBIS FOUNDATION — EXPORTACAO ESTATICA DO SITE

Este pacote inclui a pagina inicial, contato e as sete paginas de causas, com os arquivos compilados e imagens usadas pelo site.

Como abrir localmente:
1. Extraia o ZIP para uma pasta.
2. Abra um terminal nessa pasta.
3. Execute: python3 -m http.server 8000
4. Acesse: http://localhost:8000/

Paginas incluídas:
- Pagina inicial: /
- Contato: /help/contact/
- Ross: /help/ross/
- Maria Alice: /help/maria-alice/
- Fundo para a casa da familia: /help/family-home/
- Cavalo resgatado: /help/rescued-horse-surgery/
- Gael: /help/gael-surgery/
- Bernid: /help/bernid-gaza/
- Chico: /help/chico-tumor/

O servidor estatico deve servir index.html dentro das pastas das rotas. Os arquivos de imagem, CSS e JavaScript ficam nas pastas /images e /assets.
