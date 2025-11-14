# Portfólio Victor Hugo

Landing page desenvolvida em HTML e CSS para apresentar meus projetos e forma de trabalho. O layout foi inspirado em experiências Webflow e foca em storytelling simples, com seções bem delimitadas e chamadas claras para contato.

## Destaques do projeto

- **Hero com CTA direto:** resume a proposta de valor e leva ao formulário de contato.
- **Cases escolhidos:**
  - *Login seguro*: API em Spring Boot (Maven) + front-end clean com fluxo de autenticação completo.
  - *AjudeAqui*: marketplace para conectar prestadores de serviços a quem precisa de ajuda, projeto acadêmico SENAI.
- **Processo e serviços:** texto curto mostrando como conduzo descoberta, design, desenvolvimento e handoff.
- **Contato acessível:** formulário com campos essenciais e botão de envio destacado.
- **CTA final:** reforça disponibilidade para novos trabalhos freelas.

## Estrutura

```
portfolio/
├── src/
│   └── assets/
│        ├── icons/
│        ├── images/
│        └── styles/
│             └── global.css
│   └── pages/
│       ├── index.html
│       └── style.css
└── README.md
```

- `index.html`: marcação semântica organizada por seções (`section-block`, `section-content`, `project-card`, etc.).
- `style.css`: controla o layout responsivo, gradientes, tipografia e componentes reutilizáveis.

## Tecnologias

- HTML5 semântico
- CSS puro (flex/grid, clamps para tipografia/spacing)
- Assets em SVG/PNG

## Próximos passos

- Adicionar capturas reais ou GIFs dos projetos.
- Escrever estudos de caso completos com métricas.
- Conectar o formulário a um backend ou serviço de emails.

Sinta-se à vontade para reutilizar a estrutura ou enviar PRs com melhorias. :rocket:
