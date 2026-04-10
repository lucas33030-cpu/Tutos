# 📚 Tutoriais do Escritório — Repositório

Base de conhecimento interna da equipe, construída com [Docsify](https://docsify.js.org/) e hospedada gratuitamente no GitHub Pages.

---

## 🚀 Como publicar no GitHub Pages

1. Suba esta pasta como um **repositório no GitHub**
2. Vá em **Settings → Pages**
3. Em "Source", selecione o branch `main` e a pasta `/root`
4. Clique em **Save**
5. Em alguns minutos o site estará disponível em:
   `https://<seu-usuario-ou-org>.github.io/<nome-do-repositorio>`

---

## 📁 Estrutura do projeto

```
📁 /
├── index.html          ← Configuração do Docsify
├── README.md           ← Página inicial do site
├── _sidebar.md         ← Menu lateral de navegação
├── _navbar.md          ← Barra de navegação superior
├── como-contribuir.md  ← Guia para editar tutoriais
├── contato.md          ← Página de contato
└── 📁 tutoriais/
    ├── onboarding.md
    ├── ferramentas.md
    ├── comunicacao.md
    ├── sistemas.md
    ├── email.md
    ├── chamados.md
    ├── procedimentos.md
    └── faq.md
```

---

## ✏️ Como adicionar novos tutoriais

1. Crie um arquivo `.md` na pasta `tutoriais/`
2. Adicione o link no `_sidebar.md`
3. Faça o commit — o site atualiza automaticamente!

Veja o guia completo em `como-contribuir.md`.
