# MeetingTimer · Cronômetro de Pautas

> **Uma pauta de cada vez. Um tempo para cada conversa.**  
> One agenda item at a time. Time for every conversation.

O **MeetingTimer** é um cronômetro de pautas gratuito, bilíngue (PT-BR / EN), desenvolvido com **HTML, CSS e JavaScript**, em um contexto de mentoria da [DiversificaDev](https://diversifica.dev/). Projeto de **Thalles Bastos**.

🔗 **Aplicação:** https://thallesbastos.github.io/meeting-items-timer/  
📖 **Como usar:** https://thallesbastos.github.io/meeting-items-timer/como-usar.html  
✨ **Sobre:** https://thallesbastos.github.io/meeting-items-timer/sobre.html

## Recursos

- Criação de pautas com duração individual e acompanhamento visual.
- Contagem regressiva, pausa, avanço de pauta e encerramento com confirmação.
- Acréscimos de tempo (+5 e +1 minuto), exibidos durante a reunião.
- Alertas sonoros com opção para silenciar.
- **Modo apresentação**, exibindo apenas a área do cronômetro dentro da aba.
- Modo claro/escuro e interface em português/inglês.
- Responsivo para desktop e celular.
- Aplicativo estático, **sem backend, cadastro ou banco de dados**.

## Como funciona

1. Quem facilita a reunião acessa o site e adiciona os assuntos com seus tempos.
2. Abre o cronômetro, inicia a contagem e compartilha a aba/janela pelo Meet, Teams ou outra plataforma.
3. Participantes acompanham a tela compartilhada; **não há sincronização entre navegadores**.
4. A pessoa que iniciou controla pausa, avanço e acréscimos.

**Atenção:** os dados são mantidos somente na memória da página. **Atualizar ou fechar a aba faz perder as pautas e o progresso.** Ao encerrar pelo botão do próprio aplicativo, a lista permanece enquanto a página estiver aberta.

Os sons compartilhados dependem das opções de áudio da plataforma de videoconferência e do navegador.

## Executar localmente

Baixe este repositório e abra `index.html` no navegador. Não há instalação nem dependências de compilação. A fonte Poppins vem do Google Fonts; sem internet, o navegador usa uma fonte alternativa.

## Estrutura

```text
meeting-items-timer/
├── index.html          # Aplicativo principal
├── como-usar.html      # Guia bilíngue
├── sobre.html          # Projeto, autor e DiversificaDev
├── assets/
│   ├── thalles-bastos.webp
│   ├── diversificadev-neon.webp
│   └── reportagem-correio-braziliense.webp
├── README.md
└── GUIA-PUBLICACAO.md
```

## Publicar no GitHub Pages

O repositório já usa **Settings → Pages → Deploy from a branch → main → /(root)**. Substitua os arquivos na raiz da branch `main` e mantenha a pasta `assets/`. A publicação ocorre automaticamente após o commit. Consulte `GUIA-PUBLICACAO.md` para instruções detalhadas.

## Personalização

- Editar textos institucionais: `sobre.html` (versões PT e EN).
- Editar guia: `como-usar.html` (versões PT e EN).
- Alterar cores: bloco `<style>` em cada página.
- Ajustar links de perfil, cursos e redes sociais: procure por `href=` em `sobre.html`.
- Editar o cronômetro: `index.html`.

As preferências de idioma e tema usam `localStorage`. **Não são dados das pautas.**

## Créditos

**Desenvolvimento:** [Thalles Bastos](https://thbastos.com) · [LinkedIn](https://www.linkedin.com/in/thallesbastos/)  
**Mentoria e comunidade:** [DiversificaDev](https://diversifica.dev/) · [LinkedIn](https://www.linkedin.com/company/diversifica-dev/)

A página Sobre inclui recorte jornalístico de **Correio Braziliense** (09/02/2025), atribuído a **Marina Rodrigues**, fornecido pelo autor do projeto. Direitos do material editorial permanecem com seus respectivos titulares. Confirme permissões de reprodução antes de uma divulgação mais ampla.
