# Levantamento de Obra

App para desenhar o levantamento de uma obra: paredes existentes, a construir e a demolir, portas, janelas, ambientes (piso, forro, pé-direito), pontos elétricos, água, esgoto, gás, louças e bancadas. Também tem vista 3D, cortes e prancha em PDF com carimbo.

**Abrir o app:** https://edisonheliolopes2026.github.io/levantamento-obra/

## Usar no celular sem internet
1. Com internet, abra o link acima uma vez.
2. Adicione à tela inicial:
   - **Android (Chrome):** menu ⋮ → *Instalar app* / *Adicionar à tela inicial*
   - **iPhone (Safari):** Compartilhar → *Adicionar à Tela de Início*
3. Abra pelo ícone. Daí em diante funciona sem internet.

## Onde ficam os projetos
Os projetos ficam salvos **no aparelho** (no navegador), não neste repositório. Faça cópias de segurança de vez em quando em **Exportar → Arquivo do projeto (.json)**. Para levar um projeto para outro aparelho, use **Projetos → Importar**.

## Arquivos
- `index.html`: o app completo, com as bibliotecas (three.js, jsPDF e pdf.js) embutidas para funcionar offline
- `sw.js` e `manifest.webmanifest`: permitem instalar o app e usá-lo sem internet
