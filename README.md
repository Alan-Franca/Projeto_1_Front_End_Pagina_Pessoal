# Minha identidade na Web — Alan França

Projeto individual de página pessoal, com **HTML5 e CSS3**, duas páginas e recursos locais. Disciplina: Front-end Web, 2026/2.

## Abrir

Extraia a pasta completa do ZIP e abra `index.html` no navegador. Não precisa instalar dependências nem usar servidor. Imagens e áudio funcionam sem internet; apenas os links externos precisam de conexão.

## Estrutura

```text
projeto1_pagina_pessoal/
├── index.html
├── README.md
├── paginas/interesses.html
├── css/estilo.css
├── imagens/avatar.svg
├── imagens/galaxia.svg
├── midias/sinal-orbital.wav
└── capturas/
    ├── principal.png
    └── interesses.png
```

## Páginas e recursos

- **Principal:** apresentação de Alan, avatar, sobre mim, lista de três interesses, lista ordenada de três objetivos, tabela de estudos com três linhas e formulário demonstrativo.
- **Complementar:** hobby de ficção científica/Star Wars, ilustração espacial, ideias de projetos e áudio com controles nativos.
- As duas páginas usam `header`, `nav`, `main`, `section` e `footer`, um `h1` por página, títulos nas seções e caminhos relativos de ida e volta.
- CSS externo compartilhado, adaptação a telas pequenas, rótulos de formulário, textos alternativos, foco visível e link para pular a navegação.
- Formulário com nome, e-mail e mensagem; o botão é `type="button"`. **Os dados não são enviados.**
- Sem JavaScript, frameworks, cadastro ou banco de dados.

## Fontes dos recursos

- **Avatar e paisagem espacial:** ilustrações vetoriais originais criadas pelo assistente para este projeto. O avatar é simbólico e não representa uma fotografia de Alan.
- **Sinal orbital:** áudio original de 12 segundos, sintetizado pelo assistente com ondas senoidais; formato WAV, mono, 44,1 kHz. Não utiliza música, falas ou gravações de terceiros e não é uma trilha oficial de Star Wars.
- **Referências de estudo:** [HTML no MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTML) e [CSS no MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS).
- **Referência do hobby:** [site oficial de Star Wars](https://www.starwars.com/). O projeto não possui vínculo oficial com Lucasfilm ou Disney.

## Uso de IA e personalização

O usuário pediu uma página baseada no plano do Projeto 1, mantendo HTML5 e CSS3, e confirmou **Alan França** como nome de apresentação. O assistente preparou a estrutura, os textos-base, o CSS, as ilustrações, o áudio e a verificação técnica.

**Antes da entrega:** personalize o texto “Sobre mim”, os interesses, os objetivos e o conhecimento atual da tabela com suas próprias informações e palavras. Esses conteúdos são propostas iniciais, não uma biografia confirmada. Star Wars foi mantido como tema sugerido a partir da conversa anterior. Leia e compreenda o código para explicar suas escolhas.

## Verificação técnica

Registro dos testes realizados pelo assistente:

- Abertura direta das duas páginas em Chrome, com imagens e CSS locais.
- Links de seção e navegação de ida e volta entre as páginas.
- Links externos conferidos em suas páginas de destino: MDN HTML, MDN CSS e Star Wars.
- Larguras de 1440, 768, 390 e 320 pixels, sem rolagem horizontal da página; a tabela tem rolagem própria no celular.
- Hierarquia de títulos, listas, tabela, imagens com `alt` e rótulos dos campos.
- Navegação com Tab, link de salto e foco visível.
- Reprodução e pausa do WAV pelos controles do navegador, sem autoplay.
- Botão demonstrativo sem envio e atributo `type="email"` no campo de e-mail.
- Cópia da pasta em outro local, verificando caminhos relativos, imagens e áudio.
- Capturas das duas páginas para documentação.

Não inclua RGM, endereço, telefone ou documentos na página. Caso exigidos, forneça-os apenas no canal privado de entrega indicado pelo professor.
