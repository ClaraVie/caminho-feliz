# ESGFuture — Landing Page

Landing page institucional sobre práticas ESG (Environmental, Social and Governance), desenvolvida com HTML e CSS puros, sem dependências externas.

---

## Visão Geral

A página apresenta os conceitos, pilares e métricas do ESG de forma clara e visual, com seções pensadas para comunicar valor a investidores, empresas e profissionais da área de sustentabilidade.

---

## Estrutura de Arquivos

```
/
├── index.html          # Estrutura e conteúdo da página
├── styles.css          # Estilos e paleta de cores
├── img-product.png     # Imagem da seção de produto (gerada por IA)
├── favicon.png         # Ícone da aba do navegador
└── README.md           # Este arquivo
```

---

## Seções da Página

| Seção | Descrição |
|---|---|
| **Nav** | Barra de navegação fixa com links internos |
| **Hero** | Apresentação principal com chamada para ação |
| **Números** | Estatísticas de impacto do ESG no mercado |
| **Pilares** | Cards dos três pilares: Ambiental, Social e Governança |
| **Por que ESG** | Benefícios e vantagens competitivas da adoção |
| **Produto** | Apresentação da plataforma ESGFuture com imagem |
| **Métricas** | 8 indicadores com barras de progresso |
| **CTA** | Formulário de captura de e-mail |
| **Footer** | Links e informações da empresa |

---

## Paleta de Cores

| Variável CSS | Valor | Uso |
|---|---|---|
| `--green` | `#3a7d5c` | Cor principal, links |
| `--green-light` | `#52a87b` | Botões, destaques |
| `--green-soft` | `#eaf5ef` | Fundos suaves, ícones |
| `--blue` | `#4a7fa5` | Pilar Social, label de métricas |
| `--amber` | `#b07d3a` | Pilar Governança |
| `--dark` | `#2c3a35` | Títulos e textos principais |
| `--gray` | `#7a8f87` | Textos secundários |

---

## Como Usar

1. Clone ou baixe os arquivos do projeto
2. Mantenha todos os arquivos na mesma pasta
3. Abra `index.html` diretamente no navegador

Nenhuma instalação, servidor ou dependência é necessária.

---

## Personalização

### Trocar cores
Todas as cores estão definidas como variáveis CSS no topo de `styles.css` dentro de `:root { }`. Basta alterar os valores lá para aplicar mudanças em toda a página.

### Adicionar/remover seções
Cada seção no `index.html` está delimitada por comentários como `<!-- ── HERO ── -->`, facilitando a localização e edição.

### Trocar a imagem do produto
Substitua o arquivo `img-product.png` por outra imagem com o mesmo nome, ou atualize o atributo `src` da tag `<img>` dentro da seção `#produto` no `index.html`.

---

## Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — variáveis, grid, flexbox, media queries
- Sem frameworks, sem JavaScript, sem dependências externas