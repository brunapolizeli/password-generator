[🇺🇸 English](README.md) | [🇧🇷 Português](README.pt-BR.md)

# Password Generator

Este repositório contém um pequeno gerador de senhas para web que gera duas senhas aleatórias por ação. O projeto tem como foco a prática de layout de interface, estilização e lógica básica de interação com JavaScript.

[**Demo ao vivo — password-generator-three-theta-70.vercel.app**](https://password-generator-three-theta-70.vercel.app/)

---

## Visão Geral do Projeto

Este é um projeto individual do Scrimba Full Stack Path. Um [design do Figma](https://www.figma.com/design/NEj9JDycMjF3XKXq7swoc9/Random-Password-Generator--New-version-?node-id=0-1&t=qcjnhnh8hwwarZhX-1) foi fornecido como referência de layout, mas o design visual foi intencionalmente modificado. Todo o HTML, CSS e JavaScript foi escrito manualmente para praticar a tradução de um design para código e a separação entre estrutura, estilo e lógica.

---

## Funcionalidades

- Geração de senhas acionada por botão, com duas senhas geradas por vez
- Comprimento da senha definido pelo usuário, com valores mínimo e máximo obrigatórios
- Conjunto de caracteres construído com base nas opções selecionadas pelo usuário
  - Letras minúsculas sempre incluídas, com opções para letras maiúsculas, números e símbolos
- Senhas geradas utilizando apenas os tipos de caracteres atualmente selecionados
- Funcionalidade de copiar a senha ao clicar
- Modal de confirmação visual após a cópia
- Modal pode ser fechado pelo botão de fechar ou ao clicar fora dele
- Feedback visual durante as interações do usuário
- Interface minimalista em tema escuro, com foco em legibilidade

---

## Estrutura do Projeto

```text
password-generator/
├── index.html
├── index.css
├── index.js
└── README.md
```

---

## Tecnologias Utilizadas

- HTML5
- CSS3
  - Flexbox
- JavaScript (vanilla)

---

## Melhorias Planejadas

- Refinamentos de interface e espaçamento

---

## Licença

Este projeto está licenciado sob a [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). É livre para uso, compartilhamento e adaptação para fins não comerciais, com atribuição.
