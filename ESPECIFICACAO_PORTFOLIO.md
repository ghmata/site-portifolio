# 📄 Especificação Técnica e de Conteúdo — Portfólio Gabriel Hipólito

> **Objetivo deste documento:** Servir como guia completo para o desenvolvedor front-end implementar o site de portfólio. Contém todas as seções, textos finais (copywriting), design system e instruções de comportamento da interface.

---

## 1. 🧭 Estrutura de Navegação (Sitemap)

O site será uma **Single Page Application (SPA)** com scroll suave. A navegação fixa no topo terá os seguintes âncoras:

```
[Logo/Nome] ———— [A Abordagem] ———— [Case Studies] ———— [Arsenal Técnico] ———— [Contato] ———— [WhatsApp CTA]
```

| Ordem | Seção ID          | Label no Menu     | Descrição Resumida                                    |
| ----- | ----------------- | ----------------- | ----------------------------------------------------- |
| 1     | `#hero`           | —                 | Hero Section com headline e CTA principal.            |
| 2     | `#abordagem`      | A Abordagem       | Proposta de valor e diferenciais.                     |
| 3     | `#cases`          | Case Studies      | Grid de projetos em estilo Bento Grid.                |
| 4     | `#stack`          | Arsenal Técnico   | Ícones das tecnologias dominadas.                     |
| 5     | `#contato`        | Contato           | Formulário simples + links sociais + WhatsApp fixo.   |

---

## 2. ✍️ Copywriting Final (Textos Prontos para Uso)

### 2.1 Header / Navbar

- **Logo/Nome:** `Gabriel Hipólito` (usar fonte display, peso bold)
- **CTA do Menu (Botão Destacado):** `Fale no WhatsApp →`

---

### 2.2 Hero Section (`#hero`)

**Eyebrow (Tag superior ao título):**
> `Desenvolvedor Fullstack & Especialista em Automação`

**Headline Principal (H1):**
> `Eu construo sistemas que tiram problemas do seu caminho.`

**Subheadline (Parágrafo de apoio):**
> `Você não precisa de mais código no mundo. Você precisa de uma solução que funcione. Sou Gabriel Hipólito — transformo processos manuais em sistemas inteligentes que economizam tempo, reduzem erros e geram resultados reais para o seu negócio.`

**CTA Primário (Botão Grande):**
> `Ver Case Studies ↓`

**CTA Secundário (Link sutil):**
> `ou fale diretamente comigo no WhatsApp`

---

### 2.3 Seção "A Abordagem" (`#abordagem`)

**Título da Seção (H2):**
> `Menos Código. Mais Resultado.`

**Subtítulo:**
> `Minha metodologia para entregar soluções que realmente funcionam.`

**Bloco de 3 Colunas (Cards de Metodologia):**

| # | Ícone Sugerido | Título do Card                   | Descrição                                                                                                |
|---|----------------|----------------------------------|----------------------------------------------------------------------------------------------------------|
| 1 | 🎯             | **Foco no Problema Real**        | Antes de escrever uma linha de código, eu mergulho na sua dor de operação. Entendo o fluxo, os gargalos e o que realmente precisa ser resolvido. |
| 2 | ⚙️             | **Arquitetura à Prova de Balas** | Construo sistemas robustos com tratamento de erros, validações e lógica que não quebra no primeiro cenário inesperado. |
| 3 | 📈             | **Entrega Orientada a Valor**    | Meu sucesso é medido pelo seu retorno: horas economizadas, erros eliminados e processos mais ágeis. Métricas, não features. |

---

### 2.4 Seção "Case Studies / Projetos" (`#cases`)

**Título da Seção (H2):**
> `Case Studies: Problemas Resolvidos`

**Subtítulo:**
> `Cada projeto abaixo nasceu de uma dor real. Clique para explorar a solução.`

---

#### **PROJETO 1: CONCAN — Sistema de Gestão de Manifestos de Carga**

| Campo               | Conteúdo                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Tag/Categoria**   | `Gestão de Operações` `Mobile-First`                                                                                                             |
| **Nome do Produto** | `CONCAN`                                                                                                                                         |
| **Headline**        | `Recebimento de carga aérea sem papel e sem atrasos.`                                                                                            |
| **O Problema**      | Conferência manual de manifestos de carga gerava retrabalho, erros de digitação e atrasos na liberação de materiais.                            |
| **A Solução**       | Sistema web com importação automática de PDFs, dashboard de conferência em tempo real e sincronização colaborativa via Google Sheets.           |
| **Destaques**       | ✅ Importação automática de PDFs  •  ✅ Dashboard de status ao vivo  •  ✅ Sincronização Google Sheets  •  ✅ Interface Mobile-First              |
| **Stack**           | `Python` `Flask` `SQLite` `Bootstrap 5` `Google Sheets API`                                                                                      |
| **Link GitHub**     | `https://github.com/ghmata/concan`                                                                                                               |

---

#### **PROJETO 2: LOCAMIL — Sistema de Gestão de Locadora de Veículos**

| Campo               | Conteúdo                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Tag/Categoria**   | `Gestão de Ativos` `CRM`                                                                                                                         |
| **Nome do Produto** | `LOCAMIL`                                                                                                                                        |
| **Headline**        | `Controle total da sua frota com um clique.`                                                                                                     |
| **O Problema**      | Controle de locações em planilhas dispersas, sem validação de conflitos de datas, e gestão financeira manual propensa a erros.                  |
| **A Solução**       | Sistema completo com dashboard interativo, validação automática de disponibilidade, cálculo de diárias e exportação de relatórios em múltiplos formatos. |
| **Destaques**       | ✅ Dashboard de status por veículo  •  ✅ Validação de conflitos de datas  •  ✅ Cálculo automático de valores  •  ✅ Exportação SQL/CSV/JSON      |
| **Stack**           | `Python` `Flask` `SQLAlchemy` `SQLite` `Bootstrap 5`                                                                                             |
| **Link GitHub**     | `https://github.com/ghmata/locamil`                                                                                                              |

---

#### **PROJETO 3: COMREC — Sistema de Gestão de Recebimento de Materiais**

| Campo               | Conteúdo                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Tag/Categoria**   | `Comunicação Interna` `Workflow`                                                                                                                 |
| **Nome do Produto** | `COMREC`                                                                                                                                         |
| **Headline**        | `Requisições rastreadas do início ao fim.`                                                                                                       |
| **O Problema**      | Comunicação descentralizada entre setores para requisição de materiais, sem rastreabilidade de status e sem histórico de ações.                 |
| **A Solução**       | Plataforma web com múltiplos perfis de acesso (Emissor, TSRE, Admin), sistema de chat integrado por requisição e dashboards personalizados por papel. |
| **Destaques**       | ✅ Multi-role (Emissor, TSRE, Admin)  •  ✅ Chat integrado por requisição  •  ✅ Histórico completo de ações  •  ✅ Dashboards personalizados       |
| **Stack**           | `Python` `Flask` `Flask-Login` `SQLAlchemy` `Bootstrap 5`                                                                                        |
| **Link GitHub**     | `https://github.com/ghmata/sistema-comrec`                                                                                                       |

---

#### **PROJETO 4: PDF EXTRACT PRO — Automação RPA Desktop**

| Campo               | Conteúdo                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Tag/Categoria**   | `Automação (RPA)` `Desktop`                                                                                                                      |
| **Nome do Produto** | `PDF Extract Pro`                                                                                                                                |
| **Headline**        | `Milhares de PDFs para Excel. Sem travar. Sem erro.`                                                                                             |
| **O Problema**      | Extração manual de dados de centenas de PDFs era lenta, propensa a erros, e scripts simples falhavam ao encontrar arquivos corrompidos.         |
| **A Solução**       | Aplicação Desktop robusta com interface gráfica moderna (Dark Mode), processamento em lote, segregação automática de PDFs escaneados e relatórios de falhas. |
| **Destaques**       | ✅ Processamento em lote massivo  •  ✅ Tolerância a falhas (não para no erro)  •  ✅ Relatório de arquivos problemáticos  •  ✅ Interface thread-safe |
| **Stack**           | `Python` `Tkinter` `Camelot` `Pandas` `OpenPyXL`                                                                                                 |
| **Link GitHub**     | `https://github.com/ghmata/Conversor_PDF-EXCEL`                                                                                                  |

---

#### **PROJETO 5: BNCC PRO — Planejador de Aulas com IA**

| Campo               | Conteúdo                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Tag/Categoria**   | `Inteligência Artificial` `EdTech`                                                                                                               |
| **Nome do Produto** | `Planejador BNCC Pro`                                                                                                                            |
| **Headline**        | `IA que planeja sua aula. Você só ensina.`                                                                                                       |
| **O Problema**      | Professores gastavam horas criando planos de aula que atendessem à BNCC, com códigos de habilidades, adequações e metodologias ativas.          |
| **A Solução**       | SaaS EdTech com IA Generativa (Google Gemini) que recebe o contexto da turma e gera planos completos, com compliance legal (Leis 10.639/03 e 11.645/08), jogos pedagógicos e exportação para PDF. |
| **Destaques**       | ✅ IA Generativa (Google Gemini)  •  ✅ Compliance BNCC automático  •  ✅ Módulo de Gamificação  •  ✅ Exportação HTML/PDF                         |
| **Stack**           | `Python` `Flask` `Google Gemini API` `JavaScript` `TailwindCSS`                                                                                  |
| **Link GitHub**     | `https://github.com/ghmata/Gerador_de_Plano_de_Aula`                                                                                             |

---

### 2.5 Seção "Arsenal Técnico" (`#stack`)

**Título da Seção (H2):**
> `Arsenal Técnico`

**Subtítulo:**
> `As ferramentas que uso diariamente para resolver problemas.`

**Lista de Tecnologias (com ícone sugerido):**

| Tecnologia         | Ícone Sugerido (Devicon/Simple Icons) | Categoria        |
| ------------------ | ------------------------------------- | ---------------- |
| Python             | `devicon-python-plain`                | Backend          |
| Flask              | `devicon-flask-original`              | Framework        |
| JavaScript         | `devicon-javascript-plain`            | Frontend         |
| HTML5              | `devicon-html5-plain`                 | Markup           |
| CSS3               | `devicon-css3-plain`                  | Styling          |
| TailwindCSS        | `devicon-tailwindcss-plain`           | Styling          |
| Bootstrap          | `devicon-bootstrap-plain`             | UI Framework     |
| SQLite             | `devicon-sqlite-plain`                | Database         |
| PostgreSQL         | `devicon-postgresql-plain`            | Database         |
| Git                | `devicon-git-plain`                   | Versionamento    |
| GitHub             | `devicon-github-original`             | Versionamento    |
| Pandas             | `devicon-pandas-plain`                | Data Science     |
| Machine Learning   | Ícone customizado (cérebro/chip)       | IA               |
| Google Gemini API  | Ícone customizado (estrela/Gemini)     | IA               |
| VS Code            | `devicon-vscode-plain`                | Ferramentas      |

---

### 2.6 Seção "Contato" (`#contato`)

**Título da Seção (H2):**
> `Vamos Conversar?`

**Subtítulo:**
> `Tem um problema que precisa de solução? Me conta. Respondo em até 24 horas.`

**Formulário (Labels):**
- Nome: `Seu nome`
- E-mail: `Seu melhor e-mail`
- Mensagem: `Descreva seu desafio ou projeto...`
- Botão Submit: `Enviar Mensagem`

**Links Sociais:**
- GitHub: `github.com/ghmata`
- LinkedIn: *(adicionar se houver)*
- E-mail: *(adicionar se houver)*

**WhatsApp Flutuante (Texto no Tooltip/Hover):**
> `Fale direto comigo!`

---

## 3. 🎨 Design System (Guia de Estilo)

### 3.1 Paleta de Cores

| Token Name         | HEX Value   | Uso                                      |
| ------------------ | ----------- | ---------------------------------------- |
| `--bg-primary`     | `#0a0a0a`   | Fundo principal (quase preto)            |
| `--bg-secondary`   | `#141414`   | Fundo de cards e seções alternadas       |
| `--bg-glass`       | `rgba(30, 30, 30, 0.7)` | Glassmorphism em cards/modais   |
| `--text-primary`   | `#f0f0f0`   | Texto principal (off-white)              |
| `--text-secondary` | `#a0a0a0`   | Texto secundário (cinza médio)           |
| `--accent-emerald` | `#10b981`   | Acento para sucesso, CTAs, hovers        |
| `--accent-violet`  | `#8b5cf6`   | Acento para IA, tecnologia, destaques    |
| `--border-subtle`  | `#2a2a2a`   | Bordas sutis de cards                    |
| `--gradient-hero`  | `linear-gradient(135deg, #10b981 0%, #8b5cf6 100%)` | Gradiente para títulos ou fundos de destaque |

---

### 3.2 Tipografia

| Elemento       | Fonte Sugerida       | Peso   | Tamanho (Desktop) | Tamanho (Mobile) |
| -------------- | -------------------- | ------ | ----------------- | ---------------- |
| H1 (Hero)      | `Inter` ou `Outfit`  | 800    | 3.5rem - 4rem     | 2rem             |
| H2 (Seções)    | `Inter` ou `Outfit`  | 700    | 2.5rem            | 1.75rem          |
| H3 (Cards)     | `Inter` ou `Outfit`  | 600    | 1.5rem            | 1.25rem          |
| Body Text      | `Inter`              | 400    | 1rem              | 1rem             |
| Small / Tags   | `Inter`              | 500    | 0.75rem           | 0.75rem          |
| Navbar Links   | `Inter`              | 500    | 0.9rem            | 0.85rem          |

**Import (Google Fonts):**
```css
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');
/* ou */
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;500;600;700;800&display=swap');
```

---

### 3.3 Componentes de Estilo

#### **Glassmorphism (Cards de Projeto)**
```css
.glass-card {
  background: rgba(30, 30, 30, 0.6);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 16px;
}
```

#### **Bento Grid (Layout dos Projetos)**
```
Layout sugerido (Desktop - 4 colunas):

+-------------------+-------------------+
|      CONCAN       |      LOCAMIL      |
|    (2 colunas)    |    (2 colunas)    |
+-------------------+-------------------+
|  COMREC  | PDF EXTRACT | BNCC PRO     |
| (1 col)  |  (1 col)    |  (2 col)     |
+----------+-------------+--------------+

O grid deve adaptar para 1 coluna em mobile (stacked).
```

#### **Sombra e Elevação**
```css
.elevated {
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.4);
}

.elevated-hover {
  box-shadow: 0 12px 40px rgba(16, 185, 129, 0.15); /* Emerald glow */
}
```

---

## 4. ⚡ Instruções de Comportamento para o Desenvolvedor

### 4.1 Navbar (Menu de Navegação)

| Comportamento                     | Descrição                                                                                     |
| --------------------------------- | --------------------------------------------------------------------------------------------- |
| **Posição**                       | `position: fixed; top: 0; z-index: 1000;`                                                     |
| **Background Inicial**            | `transparent` (sobre a Hero Section).                                                         |
| **Background após Scroll**        | Ao rolar ~80px, aplicar `background: rgba(10,10,10,0.9); backdrop-filter: blur(8px);`         |
| **Transição**                     | `transition: background 0.3s ease, box-shadow 0.3s ease;`                                     |
| **Scroll Suave**                  | `scroll-behavior: smooth;` no `<html>`. Links do menu usam âncoras `href="#secao"`.           |
| **CTA WhatsApp no Menu**          | Botão sempre visível, com `background: var(--accent-emerald)` e `border-radius: 9999px;` (pill shape). |

---

### 4.2 Cards de Projeto (Case Studies)

| Comportamento                     | Descrição                                                                                     |
| --------------------------------- | --------------------------------------------------------------------------------------------- |
| **Estado Padrão**                 | Borda sutil `1px solid var(--border-subtle)`. Background `var(--bg-glass)`.                   |
| **Hover - Transform**             | `transform: translateY(-8px) scale(1.02);`                                                    |
| **Hover - Borda**                 | Borda ganha cor `var(--accent-emerald)` ou `var(--accent-violet)` dependendo da categoria.    |
| **Hover - Sombra**                | Aplicar `box-shadow: 0 15px 40px rgba(16, 185, 129, 0.2);` (glow sutil).                      |
| **Transição**                     | `transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease;`              |
| **Link**                          | Card inteiro é clicável e redireciona para o repositório GitHub (abre em nova aba).           |
| **Tags (Categoria)**              | Pequenos badges com `background: rgba(139, 92, 246, 0.2); color: var(--accent-violet);` para IA, e emerald para Gestão. |

---

### 4.3 Botão de WhatsApp Flutuante

| Comportamento                     | Descrição                                                                                     |
| --------------------------------- | --------------------------------------------------------------------------------------------- |
| **Posição**                       | `position: fixed; bottom: 24px; right: 24px; z-index: 9999;`                                  |
| **Tamanho**                       | ~56px de diâmetro (círculo).                                                                  |
| **Cor**                           | `background: #25D366;` (verde oficial do WhatsApp).                                           |
| **Ícone**                         | Usar ícone SVG do WhatsApp em branco.                                                         |
| **Hover**                         | `transform: scale(1.1);` + leve `box-shadow: 0 8px 25px rgba(37, 211, 102, 0.4);`             |
| **Animação de Entrada**           | Aplicar um leve `pulse` ou `bounce` a cada ~10s para chamar atenção sutil.                    |
| **Tooltip (Opcional)**            | Ao hover, mostrar tooltip à esquerda: "Fale direto comigo!".                                  |
| **Link**                          | `href="https://wa.me/55XXXXXXXXXXX?text=Olá! Vi seu portfólio e gostaria de conversar."` (substituir pelo número real). |

---

### 4.4 Seção Arsenal Técnico

| Comportamento                     | Descrição                                                                                     |
| --------------------------------- | --------------------------------------------------------------------------------------------- |
| **Layout**                        | Grid de ícones (5-6 colunas desktop, 3 mobile).                                               |
| **Ícones**                        | Usar Devicon (`<i class="devicon-python-plain"></i>`) ou Simple Icons.                        |
| **Hover em Ícones**               | `filter: brightness(1.3);` + `color: var(--accent-emerald);`                                  |
| **Tooltip**                       | Mostrar nome da tecnologia ao hover.                                                          |

---

### 4.5 Hero Section

| Comportamento                     | Descrição                                                                                     |
| --------------------------------- | --------------------------------------------------------------------------------------------- |
| **Background**                    | Gradiente sutil escuro ou imagem abstrata de baixa opacidade (onda, grid, partículas).        |
| **Animação Opcional**             | Efeito de partículas mínimas (usar biblioteca leve como `particles.js` em modo sutil) OU gradiente animado. |
| **Texto**                         | Entrada com `fade-in` e leve `translateY`.                                                    |

---

### 4.6 Acessibilidade & Performance

| Item                              | Instrução                                                                                     |
| --------------------------------- | --------------------------------------------------------------------------------------------- |
| **Semantic HTML**                 | Usar `<header>`, `<main>`, `<section>`, `<footer>`. `<h1>` único (Hero).                      |
| **Alt Text**                      | Todos os ícones decorativos devem ter `aria-hidden="true"`. Ícones funcionais devem ter `aria-label`. |
| **Fontes**                        | Usar `font-display: swap;` no import do Google Fonts.                                         |
| **Imagens**                       | Usar formato WebP quando possível. Lazy loading em imagens abaixo do fold.                    |
| **Cores**                         | Garantir contraste mínimo de 4.5:1 (texto sobre fundo). Ambas as cores primárias passam.      |

---

## 5. 📱 Responsividade (Breakpoints Sugeridos)

| Breakpoint       | Largura         | Comportamento                                  |
| ---------------- | --------------- | ---------------------------------------------- |
| Mobile           | `< 640px`       | Grid 1 coluna. Navbar vira menu hamburger.     |
| Tablet           | `640px - 1024px`| Grid 2 colunas. Navbar horizontal compacta.    |
| Desktop          | `> 1024px`      | Grid 4 colunas (Bento). Navbar completa.       |

---

## 6. 🔗 Assets Necessários

1. **Logo:** Criar versão texto estilizada "Gabriel Hipólito" ou monograma "GH".
2. **Ícone WhatsApp:** SVG branco (disponível em Simple Icons).
3. **Ícones de Tecnologias:** CDN Devicon ou ícones locais otimizados.
4. **Imagem de Fundo Hero (Opcional):** Grid abstrato ou gradiente mesh.

---

## 7. ✅ Checklist Final para o Desenvolvedor

- [ ] Navbar fixa com transição de background no scroll.
- [ ] Hero Section com headline impactante e CTAs.
- [ ] Seção "A Abordagem" com 3 cards de metodologia.
- [ ] Seção "Case Studies" em Bento Grid com 5 projetos.
- [ ] Efeito de hover nos cards (translate + glow).
- [ ] Seção Arsenal Técnico com grid de ícones.
- [ ] Seção Contato com formulário simples.
- [ ] Botão WhatsApp flutuante com animação sutil.
- [ ] Dark Mode Premium aplicado em todo o site.
- [ ] Responsivo (mobile-first ou desktop-first, mas funcional em todos).
- [ ] Scroll suave implementado.
- [ ] Acessibilidade básica garantida.

---

**Fim da Especificação.**

> Este documento deve ser entregue ao desenvolvedor front-end (ou Claude Sonnet) para implementação. Todos os textos são finais e prontos para uso.
