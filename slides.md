---
# try also 'default' to start simple
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://cover.sli.dev
# some information about your slides, markdown enabled
# info:
# apply any unocss classes to the current slide
# class: text-center
# https://sli.dev/custom/highlighters.html
# highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-up
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
colorSchema: dark
aspectRatio: 16/9
themeConfig:
  primary: "#5d8392"
plantUmlServer: "https://www.plantuml.com/plantuml"

layout: quote
---

# Acessibilidade na Web: Criando soluções acessíveis
@phvcandido

---

<div class="flex gap-5 flex-col items-start">

<div class=" p-5 flex-1">

<div class="bg-[#1f1f1fcc] p-2 px-5 rounded flex gap-5 flex-row items-start">
<div class="flex flex-row gap-2 items-center justify-between">
  <span><img src="/images/paulo.jpeg" class="w-20 rounded-full" /></span>
  <div class="flex flex-col">
    Paulo Cândido
    <span class="text-sm">
      @paulhenrique
    </span>
  </div>
  <img src="/images/qr_code.png" class="w-15">
</div>
</div>

```json
{
  "name": "Paulo Cândido",
  "professional": [
    "Senior Frontend Developer e Líder Técnico no CPQD",
    "Palestrante Eventual",
    "Organizador do Front in Campinas",
    "Membro da Liga voluntária do MWPT"
  ],
  "technologies": [
    "React",
    "Vue",
    "Typescript",
    "IA",
    "3D Maps",
    "WebXR",
    "Progressive Web Apps"
  ],
  "likes": ["Animes", "Séries", "The Office", "Music"]
}
```

</div>

</div>

<!-- <div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/paulhenrique" target="_blank" alt="GitHub" title="Abrir perfil no github"
    class="text-xl slidev-icon-btn !border-none !hover:opacity-90">
    <carbon-logo-github />
  </a>
</div>   -->

---
hide: true
---

# Agenda

- O que é interessante de definir em uma arquitetura?


---
layout: quote
---

# Quem sou eu e por que eu vou falar <br/> de <span v-mark.line.red="1">acessibilidade</span>?

--- 
layout: image-right
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/GESU2.jpeg
backgroundPosition: 100%
---

# Grupo de Experiência do Usuário

No CPQD temos o grupo de Experiência Sistêmica do Usuário, composto pelo time de Experiência do Usuário, Mobile e Front-end, este último que sou o líder técnico.

<v-click>

- Qualidade geracional e Design System
- Qualidade e Testes de código
- Incluir e oferecer <span v-mark.line.red="1">Acessibilidade</span>

</v-click>


--- 
layout: image-right
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/levva.jpg
backgroundPosition: 100%
---

# Communities WKND by Levva

No começo de 2024 estive junto a outros profissionais em Campinas na sede da Levva com a palestra **Acessibilidade como Ponto de Inflexão - você tem incluído ou excluído pessoas com seu código?**

--- 
layout: image-left
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/polis_talk2.JPG
---

# Pólis Talk: O papel da tecnologia na promoção da acessibilidade digital
Reuni no Pólis de Alta Tecnologia de Campinas, no Centro de Pesquisa e Desenvolvimento em Telecom., profissionais PCDs para discutir e trazer à tona suas perspectivas e o <br/> 
<span v-mark.line.red="0">Mercado de Acessibilidade Digital</span> 


--- 
layout: image-right
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/frontincampinas.JPG
---

## Front in Campinas 2024

O maior evento de front-end realizado na Região Metropolitanda de Campinas, com mais de 10 horas de conteúdo de Tecnologia de Ponta, Experiência do Usuário, Carreira em Tecnologia e Acessibilidade Digital.

Com parceria e apoio do Google Developers Group de Americana, DEVPIRA - Comunidade Dev de Piracicaba e a NodeBR.

---
layout: image-left
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/tdc.jpg
---

## The Developers Conference

Fui convidado para o maior evento de desenvolvedores do país, o The Developers Conference São Paulo, compondo uma roda de discussão junto com outros especialistas de Acessibilidade Digital e desenvolvimento de software.


---
layout: two-cols-header
---

# IFSP Campus Itapetininga: ProsaIF

Projeto de Software assistivo do Instituto Federal. 

::left::

<div class="w-90">

![image](/images/panda1.jpg)

</div>

Be The Boss 2018

::right::

<div class="w-90">

![image](/images/panda.jpg)

</div>

Be The Boss 2019

---
layout: cover
---

# Para as pessoas sem deficiência, a tecnologia torna as coisas mais fáceis. Para pessoas com deficiência, a tecnologia torna as coisas possíveis.

MARY PAT RADABAUGH - 1993

---
layout: full
---

<iframe width="100%" height="100%" src="https://www.youtube.com/embed/LFiQh-ql0ZM?si=DvndfG_YDYwftAuS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
</iframe>

---
layout: quote
---

# Acessibilidade é, segundo a Lei Brasileira de Inclusão (LBI), a possibilidade e condição de alcance para utilização, com segurança e autonomia, de espaços, mobiliários, equipamentos urbanos, edificações, transportes, informação e comunicação.

Em outras palavras, é um direito que garante acesso a outros direitos.
 
_Uma relação eterna de identificação e eliminação de barreiras._ 

---
layout: quote
---

# Acessibilidade digital é a remoção de quaisquer barreiras que possam impedir a navegação, compreensão e interação de todas <br/> as pessoas na <span v-mark.line.red="0">Web e ambientes virtuais.</span>

---
layout: image-left
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/timbernerslee.webp
---


## O poder da Web está em sua <span v-mark.line.red="1">universalidade</span>. <br/> Um acesso para <span v-mark.line.red="2">qualquer</span> pessoa independentemente de sua capacidade, é um <span v-mark.line.red="3">**aspecto essencial.**</span>

_Tim Berners-Lee, o pai da Web._

---
layout: full
---

## Acessibilidade Digital

<iframe width="100%" height="100%" src="https://www.youtube.com/embed/trdoe4ZtLuA?si=G85eBNVdN5ioWGh_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---
layout: cover
---

# O que envolve a <br/> Acessibilidade Digital?
- Design Inclusivo;
- Compatibilidade com tecnologias assistivas; 
- Legibilidade e percepção;
- Navegação Simplificada; 
- Testes e Feedback; 

---
layout: section
---

# Design Inclusivo

Desenvolver interfaces de usuário, sites, aplicativos e outros conteúdos digitais de forma que sejam intuitivos e fáceis de usar para todos os usuários, independentemente de suas habilidades ou deficiências.

---
layout: image
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/software.jpeg
backgroundSize: contain
---

---
layout: image
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/ux.jpeg
backgroundSize: contain
---

---
layout: center
---

# Design Universal


---
layout: image
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/universal.png
backgroundSize: contain
---

---
layout: image-left
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/tecnologia-assistiva.png
---

# Compatibilidade com tecnologias assistivas

Garantir que os produtos digitais sejam compatíveis com tecnologias assistivas, como leitores de tela para pessoas com deficiência visual, teclados alternativos para pessoas com deficiência motora, e assim por diante.

---
layout: two-cols-header
---

::left::

## Em vez disso

<div class="p-2">

```js
  <span onClick={() => doIt()} className="button">
    Isto não deveria ser um botão
  </span>
```
</div>

::right::

## Faça isso

<div class="p-2">

```js
  <button onClick={() => doIt()}>
    Um botão deve ser um botão
  </button>
```
</div>


---
layout: two-cols-header
---

::left::

## Em vez disso

<div class="p-2">

```js
  <img src="imageaddress" />
```
</div>

::right::

## Faça isso

<div class="p-2">

```js
  <img src="imageaddress" alt="Descreva suas imagens" />
```

</div>

---
layout: center
---

# E as imagens de apresentação? 

Informe ao código que elas são de apresentação: 

```js
  <img src="imageaddress" role="presentation" />
```

---
layout: center
---

# Conheça o WCAG

As Diretrizes de Acessibilidade de Conteúdo da Web (WCAG) 2.1 definem como tornar o conteúdo da Web mais acessível a pessoas com deficiências. Acessibilidade envolve uma ampla gama de deficiências, incluindo deficiências visuais, auditivas, físicas, de fala, cognitivas, de linguagem, de aprendizagem e neurológicas.

[https://www.w3.org/WAI/standards-guidelines/wcag/]
[https://www.w3.org/TR/WCAG22/]


---
layout: quote
---

# Padrões de Design

O exemplo do _button_

[https://www.w3.org/WAI/ARIA/apg/patterns/button/]

---
layout: center
---

# É muito difícil, é ruim de ler e achar o conteúdo
[https://guia-wcag.com/]

---
layout: iframe
url: https://guia-wcag.com/
---


---
layout: quote
---

# Legibilidade e percepção

Utilizar técnicas que melhorem a legibilidade do texto, como contraste adequado entre texto e fundo, e fornecer alternativas para conteúdos audiovisuais para pessoas com deficiência auditiva.
[https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/contraste.jpg]

---
layout: image
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/contraste.jpg
backgroundSize: contain
---

---
layout: iframe
url: https://www.whocanuse.com/
---

---
layout: iframe
url: https://www.facil-iti.fr/#dyslexie
---


---
layout: quote
---

# Navegação Simplificada
Criar uma estrutura de navegação clara e lógica que permita aos usuários encontrar facilmente o que estão procurando, independentemente de suas habilidades cognitivas ou experiência anterior com tecnologia.

---
layout: image
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/storm.png
---

# O paradoxo da tempestade

---
layout: center
---

# A Web Semântica
A queridinha Web 3.0

---
layout: cover
---

# Evolução da Web
- A Web somente Leitura
- Web como uma plataforma
- <span v-mark.circle.red="0">Web Semântica</span>

---
layout: image
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/sites_acessiveis.png
---

---
layout: quote
---

Os organizadores avaliaram 26,3 milhões de sites ativos no país, número 11% maior do que em 2023. Apesar do salto de 0,5% em 2022 para 3,3% em 2023 no sucesso de todos os testes aplicados, <span v-mark.line.red="0">a queda para 2,9% em 2024</span> mostra que ainda há variações significativas que podem ser atribuídas a novos sites e ao momento específico da análise dos dados.

---
layout: image
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/pessoas-com-deficiencia.png
---

---
layout: quote
---

# Impacto da Acessibilidade Digital

A falta de acessibilidade digital exclui milhões de pessoas em todo o mundo. Estudos mostram que uma em cada sete pessoas no mundo tem algum tipo de deficiência, e a acessibilidade digital é crucial para garantir que elas possam participar plenamente da sociedade digital.

---
layout: center
---

# Invertendo o Jogo
Show me the code

---
layout: center
---

# Quais as desculpas?
Vamos Listar 

---
layout: center
---

# dá trabalho validar o código 
Pode até ser verdade

---
layout: image-left
image: https://raw.githubusercontent.com/paulhenrique/acessibilidade-na-web/refs/heads/main/images/eslint.png
backgroundSize: contain
---

<div class="flex align-center justify-center flex-col h-100">

# Seu novo amigo
Se já não for

</div>

---
layout: full
---

![image](/images/eslint-view.png)
## O eslint entrega o que está de errado na validação do código

---
layout: quote
---

# Plugins
- [https://github.com/jsx-eslint/eslint-plugin-jsx-a11y]
- [https://github.com/dequelabs/axe-core]


---

# Valide suas páginas
Mais do que essencial 

![image](/images/tools.png)

---
layout: center
---

# Teste acessibilidade
Testes unitários, impossível viver sem eles

```js
import YourComponent from './YourCOmponent'; 
import {render} from '@testing-library/react';
import { axe, toHaveNoViolations } from 'jest-axe';

expect.extend(toHaveNoViolations);

describe('YourComponent Acessibility Test', () => {
  it('Should not have any accessibility violations', async () => {
    const {container} = render(<YourComponent />);
    const results = await axe(container);
    expect(results).toHaveNoViolations();
  });
});
```

---
layout: center
---

# Faça queries utilizando roles

```js
<div role="dialog"></div>
...
import {render, screen} from '@testing-library/react';

render(<MyComponent />);
const dialogContainer = screen.getByRole('dialog');
```

---
layout: quote
---

# Isso náo é tudo
Ainda há um mundo a ser descoberto, mas por hora 

---
layout: center
---

# Obrigado