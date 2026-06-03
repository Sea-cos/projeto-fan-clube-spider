# OP. Aracnídeo - Fan Clube Homem-Aranha 🕷️

> Um site temático e investigativo dedicado ao maior mistério de Nova York

## 📋 Sobre o Projeto

**OP. Aracnídeo** é um fan clube interativo do Homem-Aranha desenvolvido como projeto acadêmico de desenvolvimento web. O site possui uma estética de investigação encoberta, onde os visitantes podem:

- 🕵️ Explorar cronologia de avistamentos documentados
- 📸 Visualizar banco de imagens de avistamentos
- 📝 Se inscrever como agente investigador
- 📊 Acessar dados compilados sobre o herói

### Tema Visual

O design segue uma temática de "operação encoberta" com:
- Paleta de cores em tons de vermelho e preto
- Tipografia industrial (Oswald, Share Tech Mono)
- Interface estilizada como documentos classificados
- Atmósfera cinematográfica e misteriosa

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica do site
- **CSS3** - Estilização avançada e responsiva
- **Fontes Externas** - Google Fonts (Special Elite, Oswald, Share Tech Mono)

## 📁 Estrutura do Projeto

```
projeto-fan-clube-spider/
├── index.html           # Página inicial com hero section
├── conteudo.html        # Página de arquivos e cronologia de avistamentos
├── inscricao.html       # Formulário de inscrição
├── styles.css           # Estilos globais do projeto
├── img/                 # Diretório de imagens
│   ├── spider-man1.webp
│   ├── spider-man2.png
│   ├── spider-sighting1.webp
│   ├── spider-sighting2.webp
│   ├── spider-sighting3.jpg
│   └── icons8-spider-man-new-120.png
└── README.md           # Este arquivo
```

## 📄 Páginas do Site

### 🏠 Página Inicial (index.html)
- Hero section com introdução à operação
- Seção "Sobre a Missão" com contexto do fan clube
- Citação temática do Homem-Aranha
- CTAs para inscrição e visualização de arquivos
- Links de navegação principais

### 📂 Arquivos (conteudo.html)
- Estatísticas (avistamentos, vilões, membros)
- **Cronologia de Avistamentos**: Tabela detalhada com:
  - Data e local do avistamento
  - Descrição da ocorrência
  - Duração
  - Dano colateral
  - Fonte de informação
  - Classificação do incidente
- Galeria com imagens dos avistamentos
- Sistema de badges para categorizar eventos

### 📝 Inscrição (inscricao.html)
Formulário completo com campos:
- Nome completo
- Sexo (com opções variadas)
- Data de nascimento
- E-mail
- Telefone
- Checkbox de termos e confirmação
- Botões para enviar/limpar

## 🎨 Paleta de Cores

| Variável | Cor | Uso |
|----------|-----|-----|
| `--vermelho` | #cc0000 | Elementos principais |
| `--vermelho-escuro` | #8b0000 | Bordas, backgrounds |
| `--vermelho-brilho` | #ff2020 | Hover states |
| `--fundo` | #0a0a0a | Background principal |
| `--fundo-card` | #1a1010 | Cards e containers |
| `--texto` | #e8ddd0 | Texto principal |
| `--texto-fraco` | #8a7a6a | Texto secundário |
| `--amarelo` | #f5c842 | Destaques |

## 🖋️ Tipografia

- **Special Elite** - Fonte decorativa (cursive)
- **Oswald** - Headings e textos destacados (sans-serif)
- **Share Tech Mono** - Labels e dados técnicos (monospace)

## 📱 Design Responsivo

O site é desenvolvido com design mobile-first utilizando:
- CSS Grid para layouts complexos
- Flexbox para alinhamento
- Media queries para diferentes tamanhos de tela
- Imagens otimizadas em WebP

## 👤 Autor

**Marcos Vinicius** - 2026
Projeto acadêmico de desenvolvimento web

## 📌 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/Sea-cos/projeto-fan-clube-spider.git
```

2. Abra o arquivo `index.html` em seu navegador

3. Navegue pelas diferentes seções usando o menu de navegação

## 🔧 Desenvolvendo

### Estrutura de Cores
As cores estão definidas como variáveis CSS em `:root` no `styles.css`. Para alterar o tema:

```css
:root {
  --vermelho: #cc0000;
  /* Modificar conforme necessário */
}
```

### Adicionar Novos Avistamentos
Para adicionar novos registros na cronologia, adicione uma nova `<tr>` na tabela em `conteudo.html`:

```html
<tr>
  <td>Data</td>
  <td>Local</td>
  <td><strong>Descrição</strong></td>
  <td>Duração</td>
  <td>Dano</td>
  <td>Fonte</td>
  <td><span class="badge badge-color">Status</span></td>
</tr>
```

## 📊 Estatísticas do Projeto

- **Linguagens**: HTML (57.2%), CSS (42.8%)
- **Arquivo Principal**: index.html
- **Tamanho**: ~692 KB
- **Criado**: 4 dias atrás
- **Última atualização**: 2026-06-02

## 🚀 Funcionalidades Principais

✅ Navegação sticky com menu responsivo  
✅ Hero section com CTAs destacadas  
✅ Tabela interativa de avistamentos  
✅ Formulário de inscrição funcional  
✅ Galeria de imagens  
✅ Sistema de badges para categorização  
✅ Design temático coeso  
✅ Acessibilidade semântica  

## 📚 Recursos

- [Google Fonts](https://fonts.google.com/)
- [Icons8 - Spider-Man Icons](https://icons8.com/)
- Imagens temáticas de Spider-Man

## 📝 Notas

Este é um projeto educacional desenvolvido com propósitos acadêmicos. O conteúdo é inspirado no universo do Homem-Aranha e construído com foco em demonstrar habilidades de desenvolvimento web front-end.

---

**Operação Aracnídeo · Fan Clube Homem-Aranha · Todos os Avistamentos Reservados** 🕷️
