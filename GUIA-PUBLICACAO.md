# GUIA DE PUBLICAÇÃO · MEETINGTIMER

## Atualização do repositório existente

Repositório: https://github.com/thallesbastos/meeting-items-timer

1. **Faça um backup**: no GitHub, clique em **Code → Download ZIP** antes da alteração, ou faça uma cópia de `index.html`.
2. Extraia o ZIP entregue por Nico Neon. Entre na pasta `meetingtimer-site/` e selecione **o conteúdo dela**, não a pasta inteira.
3. Abra o repositório no GitHub, na branch **main**, aba **Code**.
4. Escolha **Add file → Upload files** (se o menu estiver disponível) e arraste **index.html, como-usar.html, sobre.html e a pasta assets/**. Caso a interface não aceite pasta arrastada, envie os arquivos da pasta `assets/` individualmente entrando em `assets/` (ou use Git no computador, abaixo).
5. No fim da página, escreva uma mensagem de commit, por exemplo: `feat: páginas como usar e sobre bilíngues` e clique em **Commit changes**.
6. Confirme em **Settings → Pages** que a origem continua **Deploy from a branch**, branch **main**, pasta **/(root)**. **Não altere essa configuração.**
7. Aguarde a publicação e abra: https://thallesbastos.github.io/meeting-items-timer/
8. Confira as páginas `/como-usar.html` e `/sobre.html`, os botões de idioma, tema, fotos e links. Para forçar atualização no Firefox, pressione **Ctrl+Shift+R** (Windows/Linux) ou **Cmd+Shift+R** (Mac).

### Alternativa segura via Git no computador

Se você tem Git instalado, dentro de uma pasta de trabalho:

```bash
git clone https://github.com/thallesbastos/meeting-items-timer.git
cd meeting-items-timer
# Copie aqui o conteúdo da pasta meetingtimer-site/ extraída do ZIP
git add index.html como-usar.html sobre.html assets README.md GUIA-PUBLICACAO.md
git commit -m "feat: guia e sobre bilíngues"
git push origin main
```

**Não use `git push --force`** e não apague o repositório antigo. A URL do Pages permanece a mesma.

## Links para conferir ou ajustar

- Site pessoal: https://thbastos.com
- LinkedIn pessoal: https://www.linkedin.com/in/thallesbastos/
- Site da DiversificaDev: https://diversifica.dev/
- LinkedIn DiversificaDev: https://www.linkedin.com/company/diversifica-dev/
- Cursos: https://diversifica.dev/cursos-gratuitos/
- Quem somos: https://diversifica.dev/quem-somos/

O link para cursos leva para a seção geral, não para matrículas individuais. Confirme a oferta atual antes de divulgar inscrições.

## Atenção aos arquivos

- **Não renomeie `index.html`**: o GitHub Pages precisa dele na raiz para abrir o app.
- Preserve `assets/` e seus três `.webp`: as imagens da página Sobre dependem deles.
- Os textos em **português e inglês** estão nas duas páginas e podem ser editados separadamente.
- O idioma e o tema são lembrados pelo navegador, mas **as pautas não são salvas**. Atualizar a página apaga os dados.
- O recorte de jornal é uma imagem fornecida para o projeto: confirme direitos de republicação antes de uso público se necessário.

## Checklist rápido

- [ ] Cronômetro inicia, pausa, avança e finaliza
- [ ] Sons e acréscimos funcionam
- [ ] Modo apresentação oculta o restante da interface
- [ ] Menu abre as 3 páginas
- [ ] PT/EN e claro/escuro funcionam nas 3 páginas
- [ ] Fotos aparecem na página Sobre
- [ ] Links externos abrem corretamente
- [ ] Layout está confortável no celular
