# Landing Page | Arquitetura

Landing page institucional para apresentar o trabalho de um escritório de arquitetura, divulgar projetos e serviços e facilitar o contato com potenciais clientes.

## Objetivo do projeto

Reunir em uma única página as principais informações para quem procura serviços de arquitetura: apresentação profissional, portfólio, tipos de serviço, etapas de trabalho, depoimentos e formas de contato. A navegação foi organizada para levar o visitante dessas informações até o formulário de contato.

## Desafio

O principal desafio foi apresentar diferentes tipos de conteúdo — projetos residenciais e comerciais, serviços, processo de trabalho e contato — de forma clara e coesa em uma única página. 

A solução também precisava funcionar em telas menores, manter a navegação simples e não depender de uma estrutura complexa ou de JavaScript.

## O que foi alcançado

- Página institucional com navegação entre seções.
- Apresentação profissional e ilustração de planta baixa criada com CSS.
- Portfólio com seis projetos e imagens locais.
- Seções de serviços, etapas de trabalho e depoimentos.
- Formulário com campos para coletar informações iniciais sobre o projeto.
- Layout responsivo, estados de foco visíveis e suporte à preferência por movimento reduzido.
- Estrutura simples, sem dependências de frameworks ou backend próprio.

## Tecnologias

- **HTML5** para a estrutura e o conteúdo da página.
- **CSS3** para o layout, a identidade visual, a planta baixa ilustrativa e os ajustes responsivos.
- **Google Fonts** para as famílias tipográficas Archivo e IBM Plex Sans.
- **Google Gemini** para geração de imagens fictícias, livre de direitos autorais.

## Estrutura do projeto

```text
.
├── index.html
├── style.css
├── img/
│   ├── Apartamento Vila Mariana.jpeg
│   ├── Café Pinheiros.jpeg
│   ├── Casa de Campo.jpeg
│   ├── Casa Jardim das Acácias.jpeg
│   ├── Clínica Odontológica.jpeg
│   └── Sobrado Butantã.jpeg
└── README.md
```

- `index.html`: conteúdo, seções, navegação e formulário.
- `style.css`: estilos, componentes visuais e regras para telas menores.
- `img/`: imagens usadas no portfólio.
- `README.md`: documentação do projeto.

## Observações

- O site é estático e não possui backend próprio.
- O formulário usa atributos do Netlify Forms; o recebimento de envios depende da publicação em um site configurado no Netlify.
- Antes de publicar, revise e substitua informações de contato, dados profissionais, depoimentos, preços e demais conteúdos de exemplo.
- As fontes do Google Fonts precisam de acesso à internet para serem carregadas.

## Contexto acadêmico

Projeto desenvolvido para fins acadêmicos no curso Senac EAD, na disciplina Web Standards.