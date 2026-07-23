[README.md](https://github.com/user-attachments/files/30323106/README.md)
# Tradutor Tupife

Ferramenta web para a **notação numérica Tupife** — a tablatura de furos usada
nos pífanos. Traduz, transpõe e guarda o repertório.

O sistema Tupife funciona assim: números de 0 a 6 indicam quantos furos estão
tapados, `)` indica forquilha (meio furo), `'` a 2ª oitava, `''` a 3ª oitava e
`~` a sustentação da nota.

Feito para a **Pifarada** — orquestra de pífanos do Rio de Janeiro.

---

## O que ela faz

### 🎵 Música completa
Cole a cifra inteira — com títulos, "Parte A", "Refrão", barras `|` e casas de
repetição. A ferramenta preserva todo o texto e troca **apenas as digitações**:

- escolha o **pife de origem** (de onde veio a cifra) e o **pife de destino**;
- ajuste o **tom** em meios-tons, para cima ou para baixo;
- copie o resultado inteiro com um clique.

Notas que ficarem fora do alcance do pife aparecem como `?` — basta ajustar o
tom até desaparecerem.

### Digitações → Notas
Digite uma sequência e veja as notas que soam, o tom provável da melodia e a
transposição para os outros dois pífanos, nota a nota.

### Notas → Digitações
Digite as notas (`dó ré mi…` ou `c d e f g a b`) e veja a digitação nos três
pífanos. Maiúscula indica oitava acima (`DO` = dó agudo).

### Repertório
Salve as músicas direto no aparelho:

- dê um nome e clique em **Salvar** — a música entra no repertório;
- toque no nome para carregar de volta a qualquer momento;
- **⬇ Backup** baixa um arquivo `.json` com tudo;
- **⬆ Restaurar** traz o backup de volta (mescla com o que já existe, não
  sobrescreve).

> As músicas ficam guardadas no navegador daquele aparelho. Se os dados do
> navegador forem limpos, elas somem — por isso vale fazer backup de vez em
> quando.

---

## Como publicar

É um site de **arquivo único**. Não precisa instalar nada, não tem build, não
depende de internet depois de carregado.

- **Testar no computador:** dê dois cliques em `index.html`.
- **Publicar no GitHub Pages:**
  1. Suba o `index.html` para o repositório.
  2. Vá em **Settings → Pages**.
  3. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
  4. Salve. Em um minuto o site fica no ar.

Para atualizar, basta subir a nova versão do `index.html` por cima da antiga.

Também funciona em Vercel, Netlify, Cloudflare Pages ou qualquer hospedagem
estática.

---

## Créditos

Sistema de digitação numérica criado pelo **Bloco Tupife**:
David Gonçalves, Pedro Autran (Pepe), Victor Lourenço e Surian dos Santos.

Aplicado nos arranjos da **Pifarada**.
