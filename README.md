# 📸 Programgram — Clone das Páginas do Instagram

Projeto frontend desenvolvido para simular as páginas de **login** e **cadastro** do Instagram, com layout fiel ao original, responsividade e navegação entre as telas.

---

## 🖥️ Demonstração

| Página | Descrição |
|--------|-----------|
| `index.html` | Página de login |
| `cadastro.html` | Página de cadastro |

---

## 📁 Estrutura do Projeto

```
programgram/
│
├── index.html        # Página de login
├── style.css         # Estilos da página de login
│
├── cadastro.html     # Página de cadastro
├── cadastro.css      # Estilos da página de cadastro
│
└── imgs/
    ├── Programgram.png       # Logo do projeto
    ├── FotoPerfilInsta.png   # Imagem decorativa (coluna esquerda)
    ├── appstore.png          # Badge App Store
    └── googleplay.png        # Badge Google Play
```

---

## ✨ Funcionalidades

- ✅ Página de **login** com campos de usuário e senha
- ✅ Página de **cadastro** com campos de celular/email, nome, usuário e senha
- ✅ Botão de login com Facebook
- ✅ Links de navegação entre as páginas (login ↔ cadastro)
- ✅ Links para download do app (App Store e Google Play)
- ✅ Layout **responsivo** para dispositivos móveis
- ✅ Footer com links institucionais

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura das páginas
- **CSS3** — Estilização e responsividade
  - Flexbox para alinhamento de layouts
  - Media Queries para responsividade
  - Pseudo-classes (`:focus`, `::placeholder`) para melhor UX

---

## 🚀 Como Executar

1. Clone ou baixe o repositório:
   ```bash
   git clone https://github.com/seu-usuario/programgram.git
   ```

2. Abra o arquivo `index.html` diretamente no navegador **ou** use uma extensão como o **Live Server** no VS Code para melhor experiência.

> ⚠️ Não é necessário nenhum servidor backend ou dependência externa.

---

## 📱 Responsividade

O projeto se adapta a telas menores (abaixo de 1024px):

- A coluna esquerda com a imagem decorativa é **ocultada** em telas pequenas
- O layout centraliza o painel de login/cadastro
- O footer e os textos se ajustam proporcionalmente

---

## 🎨 Identidade Visual

| Elemento | Valor |
|----------|-------|
| Cor principal | `#3c96ed` (azul Instagram) |
| Cor de fundo | `#FAFAFA` |
| Fonte | Arial, Helvetica, sans-serif |
| Bordas | `#e6e6e6` |

---

## 👨‍💻 Autor

Desenvolvido por **João Matheus** como projeto de estudo de HTML e CSS.

---

## 📄 Licença

Este projeto é apenas para fins educacionais e não possui vínculo com o Instagram ou a Meta.
