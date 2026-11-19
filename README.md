# Gestão de Projetos COTAA — SANESUL

Aplicativo web para acompanhamento e controle de projetos de automação, telemetria, software, eficiência de bombeamento e balanço hídrico da **COTAA** (Coordenadoria Técnica de Automação e Ativos) — **SANESUL** (Empresa de Saneamento de Mato Grosso do Sul).

---

## 🎯 Funcionalidades

- **Painel Geral (Dashboard):**
  - Indicadores-chave (KPIs): Total de Projetos, Fornecedores Parceiros, Categorias e Maturidade do Funil.
  - Gráfico de barras de distribuição por categoria técnica.
  - Indicador circular de avanço geral do funil.
  - Execução percentual por etapa do funil.

- **Projetos & Acompanhamento:**
  - Tabela completa de projetos com ordenação, busca textual e filtros dinâmicos por categoria.
  - Indicador visual das etapas com status interativo (clique direto nos círculos para marcar/desmarcar).
  - Modal de detalhes completos e edição de todos os campos.
  - Histórico de evolução e registro de anotações com data e hora.

- **Pipeline Kanban:**
  - Visualização em colunas por etapa do processo de contratação/piloto.
  - Botão de avanço rápido para mover o projeto para a próxima fase.

- **Diretório de Contatos:**
  - Lista de fornecedores, pessoas de contato, telefones, e-mails e projetos relacionados.

- **Exportação & Persistência:**
  - Exportação de dados para planilha em formato **CSV/Excel** (com codificação UTF-8 e BOM).
  - Persistência contínua dos dados no `localStorage` do navegador.

---

## 🎨 Identidade Visual (SANESUL)

Desenvolvido respeitando a paleta e padrões visuais oficiais da SANESUL e do Governo de Mato Grosso do Sul:
- **Azul Corporativo SANESUL:** `#0075BC`
- **Azul Celeste / Água:** `#00ADEF`
- **Verde Limão MS:** `#95C11E`
- **Ciano / Títulos:** `#1D96B7`
- **Âmbar / Destaques:** `#FA9801`

---

## 🚀 Como Executar

O aplicativo é 100% estático (Single Page Application - SPA) e não requer instalação de bancos de dados ou dependências complexas:

1. Basta abrir o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox).
2. Ou servir via qualquer servidor HTTP local:
   ```bash
   # Exemplo via Python:
   python -m http.server 8080

   # Ou via Node:
   npx serve .
   ```
