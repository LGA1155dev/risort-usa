# U.S.A Resort

Landing page de um resort fictício localizado no Arizona, Estados Unidos, desenvolvida com HTML, CSS e JavaScript. O projeto explora design premium, animações de scroll, interações dinâmicas e uma experiência de navegação imersiva.

## Sobre o projeto

O U.S.A Resort é um projeto de interface web inspirado em sites de resorts de luxo, com uma identidade visual que combina tons naturais, tipografia editorial, imagens cinematográficas e animações suaves.

A proposta é simular a experiência de um resort no deserto do Arizona, apresentando hospedagem, experiências, planos de assinatura e uma simulação de reserva.

O projeto foi desenvolvido como uma experiência de front-end, explorando técnicas modernas de CSS e JavaScript para criar uma interface visualmente sofisticada e interativa.

## Demonstração

- **Site:** https://risort-usa.vercel.app/
- **Repositório:** https://github.com/LGA1155dev/risort-usa

## Funcionalidades

- Landing page com vídeo de fundo
- Navegação interativa
- Animações de entrada durante a rolagem
- Efeitos de parallax
- Barra de progresso de scroll
- Cards interativos de experiências
- Planos de assinatura selecionáveis
- Modal de confirmação de plano
- Formulário de simulação de reserva
- Validação de datas de check-in e check-out
- Cálculo de quantidade de noites
- Layout responsivo para desktop, tablet e mobile
- Efeitos Glassmorphism
- Animações de bordas e gradientes
- Suporte à preferência de redução de movimento

## Tecnologias utilizadas

| Tecnologia | Utilização |
|---|---|
| HTML5 | Estrutura e organização do conteúdo |
| CSS3 | Layout, responsividade, animações e efeitos visuais |
| JavaScript | Interatividade, manipulação do DOM e lógica dos componentes |
| SVG | Elementos gráficos vetoriais |
| Google Fonts | Tipografia Hanken Grotesk e Instrument Serif |
| Vercel | Hospedagem e publicação |

## Recursos técnicos explorados

### CSS

- CSS Grid
- Flexbox
- Media Queries
- CSS Custom Properties
- `clamp()`
- `backdrop-filter`
- `transform`
- `transition`
- `@keyframes`
- `conic-gradient()`
- `@property`
- Pseudo-elementos `::before` e `::after`
- Mask e composição de máscaras
- Gradientes
- Glassmorphism

### JavaScript

- Manipulação do DOM
- Event Listeners
- Intersection Observer API
- `requestAnimationFrame`
- `matchMedia`
- Manipulação de classes CSS
- Validação de formulários
- Controle de modais
- Interações baseadas em scroll

## Seções do projeto

### Hero

Apresentação principal do resort com vídeo de fundo, identidade visual, localização e chamada para reserva.

### O Resort

Seção editorial de apresentação, com descrição do estabelecimento e indicadores ilustrativos.

### Experiências

Cards visuais apresentando experiências fictícias, como trilhas nos cânions, piscinas infinitas e noites de estrelas.

### Planos

Apresentação de três planos de assinatura:

- Essencial
- Oásis
- Mirante

Os planos possuem preços e benefícios ilustrativos, além de interação para seleção e confirmação.

### Avaliações

Área de depoimentos fictícios para representar a experiência dos hóspedes.

### FAQ

Seção de perguntas frequentes com informações ilustrativas sobre hospedagem e planos.

### Reserva

Formulário interativo para simular a seleção de datas, quantidade de hóspedes e consulta de disponibilidade.

> O formulário de reserva é demonstrativo. Não existe integração com backend, banco de dados, sistema real de disponibilidade ou pagamento.

## Experiência e animações

O projeto utiliza diferentes recursos para tornar a navegação mais fluida e imersiva.

- **Glassmorphism:** superfícies translúcidas com desfoque de fundo.
- **Scroll reveal:** elementos surgem conforme entram na área visível da tela.
- **Parallax:** movimentação de elementos em velocidades diferentes durante a rolagem.
- **Scroll progress:** indicador visual de progresso da página.
- **Hover effects:** transições e efeitos visuais nos cards.
- **Plan selection:** feedback animado durante a seleção dos planos.
- **Modal:** confirmação da escolha com transições de entrada e saída.

## Responsividade

A interface foi projetada para se adaptar a diferentes tamanhos de tela.

- Desktop: layout amplo, grids e navegação horizontal.
- Tablet: reorganização de cards e espaçamentos.
- Mobile: conteúdo empilhado, formulários adaptados e áreas de interação maiores.

O projeto também considera a preferência `prefers-reduced-motion`, reduzindo animações para usuários que preferem menos movimento.

## Como executar localmente

### Pré-requisitos

- Git
- Navegador atualizado
- Python 3 (opcional, para servidor local)

### 1. Clone o repositório

```bash
git clone https://github.com/LGA1155dev/risort-usa.git
```

### 2. Entre na pasta

```bash
cd risort-usa
```

### 3. Execute o projeto

Você pode abrir o arquivo `index.html` diretamente no navegador.

No Linux:

```bash
xdg-open index.html
```

Ou iniciar um servidor local com Python:

```bash
python3 -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

Para encerrar o servidor, pressione `Ctrl + C`.

## Estrutura do projeto

```text
risort-usa/
├── index.html
├── videos/
│   └── background.mp4
├── .gitattributes
└── LICENSE
```

| Arquivo | Descrição |
|---|---|
| `index.html` | Estrutura, estilos e lógica principal da aplicação |
| `videos/` | Recursos de vídeo utilizados no projeto |
| `videos/background.mp4` | Vídeo de fundo da página |
| `.gitattributes` | Configurações de atributos do Git |
| `LICENSE` | Licença do projeto |

## Design

A identidade visual foi inspirada em resorts de luxo localizados em regiões desérticas, combinando elementos naturais e uma estética editorial minimalista.

### Características

- Paleta de tons areia, bronze e cores naturais
- Tipografia editorial
- Grandes imagens cinematográficas
- Espaçamento amplo
- Cards com bordas arredondadas
- Transparências e desfoque
- Gradientes suaves
- Microinterações
- Animações sutis

### Tipografia

- Hanken Grotesk
- Instrument Serif

A combinação de tipografia sans-serif e serifada cria contraste entre elementos funcionais e títulos de destaque.

## Objetivo de desenvolvimento

O projeto foi criado para explorar técnicas modernas de desenvolvimento front-end, especialmente:

- Construção de interfaces responsivas
- Animações utilizando CSS e JavaScript
- Interações baseadas em scroll
- Manipulação de eventos
- Desenvolvimento de componentes visuais
- Validação de formulários
- Experiência do usuário (UX)
- Interface do usuário (UI)

O desenvolvimento também contou com auxílio do Claude, utilizado como ferramenta de apoio durante a implementação e experimentação de recursos visuais e interativos.

## Melhorias futuras

- [ ] Backend para gerenciamento de reservas
- [ ] Banco de dados para hospedagem e disponibilidade
- [ ] Sistema de autenticação
- [ ] Integração de pagamentos
- [ ] Internacionalização
- [ ] Melhorias de acessibilidade
- [ ] Otimização de mídia
- [ ] Gerenciamento real de reservas

## Aviso

O U.S.A Resort é um projeto fictício desenvolvido para fins educacionais e de portfólio.

O resort, os preços, os planos, as avaliações, os depoimentos e as informações de disponibilidade são ilustrativos.

Nenhuma reserva ou transação real é realizada pela aplicação.

## Licença

Consulte o arquivo `LICENSE` para obter informações sobre a licença de utilização do projeto.

---

<img width="1422" height="747" alt="usarisort" src="https://github.com/user-attachments/assets/8a0753fc-a5ba-479f-a116-a2e13f1f5876" />




Desenvolvido por [LGA1155dev](https://github.com/LGA1155dev).
