# 🌸 Projeto Viva Mulher — Roda de Conversa

Site institucional do **Projeto Viva Mulher**, um projeto de extensão do **CEUB** dedicado a criar um espaço de escuta, afeto e sororidade entre mulheres. A proposta é simples: uma roda de conversa onde não existe cabeceira — todas estão no centro.

> 💗 *"A roda não tem cabeceira. Nela, todas estamos no centro."*

## 💕 Sobre o projeto

A Roda de Conversa nasceu da vontade de criar pontes entre mulheres de diferentes histórias, classes, raças e contextos, unidas pelo desejo comum de se ouvir e se fortalecer. O site apresenta o propósito do projeto, os temas discutidos nas rodas, o blog com reflexões, informações sobre o próximo encontro e a equipe de alunas envolvidas.

## 🎀 Estrutura do site

O site é uma página única (`index.html`) com as seguintes seções:

| Seção | Descrição |
|---|---|
| 🌺 **Início (Hero)** | Apresentação do projeto e chamadas para ação |
| 💞 **Propósito** | Missão e valores (escuta ativa, espaço seguro, sororidade, transformação) |
| 📝 **Blog / Posts** | Cards com reflexões sobre feminismo, sororidade, saúde mental e ativismo |
| 🗓️ **Próxima Roda** | Data, horário, formato e tema do próximo encontro online |
| 🏷️ **Temas** | Nuvem de tags com os assuntos discutidos nas rodas |
| 🌷 **Sobre / Quem somos** | História do projeto e carrossel com as alunas participantes |
| 👣 **Footer** | Links, redes sociais e contato |

## 🩷 Tecnologias utilizadas

- **HTML5** — estrutura semântica da página
- **CSS3** puro (sem frameworks) — variáveis CSS, grid, flexbox, animações com `IntersectionObserver`
- **JavaScript vanilla** — menu mobile, carrossel de alunas, tags clicáveis e formulário de inscrição
- **Google Fonts**: `Playfair Display` (títulos) e `DM Sans` (corpo do texto)

Não há dependências, build step ou bibliotecas externas — é um projeto 100% estático.

## 🌹 Paleta de cores

O visual usa tons de rosa, remetendo ao acolhimento e à identidade do projeto:

| Variável | Cor |
|---|---|
| `--rose` | `#d4537e` 🌸 |
| `--rose-dk` | `#72243e` 🍷 |
| `--rose-lt` | `#fbeaf0` 🤍 |
| `--rose-md` | `#f4c0d1` 💗 |
| `--rose-bg` | `#fdf5f8` |

## 📁 Estrutura de arquivos

```
VivaMulher/
├── index.html        # Página principal (HTML + CSS + JS inline)
└── imagens/           # Fotos do blog, logo e fotos das alunas
```

## 💻 Como executar localmente

Por ser um site estático, basta abrir o arquivo `index.html` diretamente no navegador, ou servir a pasta com qualquer servidor HTTP simples:

```bash
# usando Python
python -m http.server 8000

# ou usando a extensão Live Server do VS Code
```

Depois acesse `http://localhost:8000`.

## 🌷 Redes sociais

- 📷 [Instagram](https://www.instagram.com/projetovivamulherceub)
- 💬 [WhatsApp](https://wa.me/5561995793905)

---

💕 *Projeto de extensão CEUB · Feito com afeto*