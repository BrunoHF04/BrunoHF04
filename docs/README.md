# GitHub Pages (`/docs`)

URL do site: **`https://brunohf04.github.io/BrunoHF04/`**  
Tetris: **`https://brunohf04.github.io/BrunoHF04/tetris.html`**

## Se aparece **404** — ativa o Pages (uma vez)

### Opção A — GitHub Actions (recomendado)

Este repo inclui [`.github/workflows/deploy-pages.yml`](../.github/workflows/deploy-pages.yml), que envia a pasta `docs/` para o Pages.

1. Abre **https://github.com/BrunoHF04/BrunoHF04/settings/pages**
2. Em **Build and deployment** → **Source**, escolhe **GitHub Actions** (não “Deploy from a branch”).
3. Vai a **Actions** → workflow **Deploy GitHub Pages** → **Run workflow** (ou faz um push em `main`).
4. Espera o job ficar verde; recarrega o Tetris após ~1 min.

### Opção B — Branch + pasta `/docs` (clássico)

1. **Settings** → **Pages**
2. **Source**: **Deploy from a branch**
3. Branch **main**, pasta **`/docs`** → **Save**

---

**Nota:** Sem um destes passos, o GitHub **não publica** o site — daí a mensagem *“There isn't a GitHub Pages site here”*.
