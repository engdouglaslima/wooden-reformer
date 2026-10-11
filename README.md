# Wooden Reformer — visualizador 3D

Site estático com rotação, zoom e vistas predefinidas, projetado para GitHub Pages.

## Publicação no GitHub Pages

1. Crie um repositório público no GitHub, por exemplo `wooden-reformer-3d`.
2. Envie **todos** os arquivos desta pasta para a raiz do repositório (`index.html`, `reformer.glb`, `.nojekyll`).
3. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch**.
4. Escolha **main** e **/(root)**, depois clique em **Save**.
5. Após a publicação, abra `https://SEU-USUARIO.github.io/wooden-reformer-3d/`.

Se você tiver um nome de repositório diferente, ajuste a URL de acordo. No computador, para testar localmente, execute `python -m http.server 8000` na pasta e abra `http://localhost:8000`.

## Sobre a visualização

- Geometria convertida do arquivo CAD STEP original.
- Cores e acabamentos são **preliminares**, atribuídos por heurísticas geométricas; não equivalem a especificações finais de fabricação.
- O código usa Three.js, carregado por CDN. O navegador precisa de conexão à internet.
- **Atenção à propriedade intelectual:** em um repositório público, o modelo 3D pode ser baixado pelos visitantes. Não publique uma geometria proprietária integral sem avaliar essa exposição. Para investidores, considere uma versão simplificada do modelo.
- GitHub Pages não substitui controle de acesso a informações confidenciais.
