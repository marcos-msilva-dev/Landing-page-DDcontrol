# DDControl – Landing Page

Landing page institucional desenvolvida para a DDControl, empresa de desinsetização de Cuiabá (MT). O projeto foi feito com HTML, CSS e JavaScript puro, sem frameworks ou bibliotecas, e tem como objetivo apresentar os serviços da empresa e direcionar o visitante para o contato via WhatsApp.

Este repositório faz parte do meu portfólio como desenvolvedor front-end.

## Sobre o projeto

A página foi pensada para um público que acessa principalmente pelo celular e busca uma solução rápida. Por isso, a estrutura segue uma sequência simples: apresentação com chamada para contato, serviços, diferenciais, depoimentos, garantia, etapas do atendimento e uma chamada final.

Minha responsabilidade abrangeu toda a parte de front-end: estrutura em HTML, estilização, responsividade e interações em JavaScript.

## Decisões técnicas

- **HTML semântico e SEO básico:** uso de `lang="pt-BR"`, `title` e `meta description` voltados para busca local.
- **CSS com variáveis customizadas:** cores, sombras, raios de borda e transições centralizados em `:root`, o que facilita a manutenção e mantém o visual consistente.
- **Layout responsivo:** construído com Flexbox e Grid, com menu mobile próprio.
- **JavaScript puro:** toda a interatividade foi feita sem dependências, mantendo a página leve.

## Funcionalidades em JavaScript

- **Animações de entrada** com `IntersectionObserver`, incluindo atraso escalonado nos cards por meio do atributo `data-delay`.
- **Rolagem suave** entre seções, com compensação da altura do header fixo.
- **Header que muda de estilo** conforme a rolagem da página.
- **Menu mobile** com alternância de ícone e fechamento automático ao navegar.
- **Botão flutuante do WhatsApp**, exibido após 300px de rolagem.
- **Efeito parallax** leve em elementos decorativos do hero.
- **Navegação centralizada** por atributos `data-section`, com um único handler de rolagem.

## Tecnologias

HTML5, CSS3, JavaScript (ES6+) e Google Fonts (Inter).

## Estrutura

```
├── index.html      # Estrutura e conteúdo
├── styles.css      # Estilos, variáveis e responsividade
├── script.js       # Interações e animações
└── assets/         # Logo e imagens
```

## Como executar

```bash
git clone https://github.com/seu-usuario/ddcontrol.git
cd ddcontrol
```

Abra o `index.html` no navegador ou utilize a extensão Live Server do VS Code. Não há dependências para instalar.

## Pontos de melhoria

Itens que identifiquei para evoluir o projeto:

- Otimizar imagens (formato WebP e `loading="lazy"`).
- Respeitar a preferência `prefers-reduced-motion` nas animações.
- Usar `requestAnimationFrame` ou throttle nos eventos de scroll.
- Adicionar dados estruturados (Schema.org `LocalBusiness`).

## Autor

**Marcos Martins da Silva**
Desenvolvedor

- E-mail: marcos.msilva.work@gmail.com
- LinkedIn: [linkedin.com/in/seu-perfil](https://www.linkedin.com/in/marcos-martins-da-silva-037262415/)
