# 💕 Site do Dia dos Namorados

## Como personalizar

Abra o arquivo `index.html` e edite:

### 1. Nome do casal
Troque **Ana & Bruno** pelo nome de vocês:
- Linha `<title>Ana & Bruno...`
- Linha `<div class="nav-logo">Ana & Bruno</div>`
- Linha `<h1 class="hero-title">Ana<br>...`
- Rodapé: `feito com ♥ para o amor da minha vida`

### 2. Data do início do relacionamento
Linha: `const START = new Date('2021-02-14T00:00:00');`
Troque pela data real de vocês.

### 3. Linha do tempo (seção #historia)
Edite os blocos `.tl-item` com suas datas e memórias reais.

### 4. Fotos (polaroids)
Para adicionar fotos reais, substitua o emoji dentro de `.polaroid-img` por:
```html
<img src="foto.jpg" alt="descrição" />
```
E coloque as fotos na mesma pasta do index.html.

### 5. Quiz
Edite o array `questions` no JavaScript com perguntas sobre vocês.

### 6. Playlist
Edite o array `tracks` com as músicas de vocês e os links do Spotify.

### 7. Lugares especiais
Edite os blocos `.lugar-card` com os lugares da história de vocês.

### 8. Carta
Edite o conteúdo dentro de `.letter-body` e `.letter-sign`.

---

## Como subir na Vercel (grátis, sem precisar de servidor)

### Opção A — Arraste e solte (mais fácil, 1 minuto)
1. Acesse **vercel.com** e crie uma conta gratuita
2. No dashboard, clique em **"Add New Project"**
3. Escolha **"Deploy without Git"** (ou "Drag & Drop")
4. Arraste a **pasta `namorados/`** inteira para a área indicada
5. Clique em **Deploy**
6. Pronto! Você receberá um link como `namorados-abc123.vercel.app`

### Opção B — Via GitHub (recomendado para atualizar fácil)
1. Crie um repositório no **github.com** (pode ser privado)
2. Faça upload da pasta `namorados/`
3. No **vercel.com**, clique em **"Add New Project"**
4. Conecte sua conta do GitHub e selecione o repositório
5. Clique em **Deploy**
6. A cada atualização no GitHub, o site atualiza automaticamente

### Opção C — Via terminal (para quem já tem Node.js)
```bash
npm i -g vercel
cd namorados/
vercel
```
Siga as instruções na tela. Na primeira vez, fará login pelo browser.

---

## Domínio personalizado (opcional)
- Na Vercel, vá em **Settings → Domains**
- Adicione um domínio como `anaebr.uno` ou `anaebruno.com`
- Domínios custam em torno de R$ 20–50/ano no Registro.br ou GoDaddy

---

## Estrutura de arquivos
```
namorados/
├── index.html    ← site completo (tudo em um arquivo)
├── vercel.json   ← configuração de deploy
└── README.md     ← este guia
```

Se quiser adicionar fotos, coloque-as aqui na mesma pasta.
