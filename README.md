Integrantes:
Igor Grave Teixeira - RM567663
Renan dos Reis Santos - RM568540

## Verve - Elevate Your Network

    "Platform of the future for future jobs"

O Verve é uma aplicação front-end de networking profissional moderna. O projeto consiste em uma landing page interativa e perfis de usuários detalhados, focando em uma experiência de usuário fluida e um design limpo.

## Sobre o Projeto

Este projeto foi desenvolvido como uma interface estática para demonstrar habilidades em HTML e CSS. A aplicação apresenta uma página inicial com um carrossel de "vozes" da comunidade e permite a navegação para páginas de perfis individuais, onde as informações dos profissionais são exibidas de forma dinâmica através de abas.

## Funcionalidades

    Landing Page Responsiva: Cabeçalho com navegação, seção "Hero" e rodapé informativo.

    Carrossel Infinito (CSS Only): Um slider contínuo na página inicial exibindo os usuários da plataforma.

    Perfis Interativos: Páginas individuais para cada usuário (ex: Xen, Ming Xi, Margaret) com um sistema de navegação por abas (Sobre, Experiência, Pessoal) controlado por JavaScript.

    Animações Suaves: Transições de fade-in e efeitos de hover nos cartões de perfil e botões.

    Design System: Uso de variáveis CSS (:root) para consistência de cores, fontes e espaçamentos.

## Tecnologias Utilizadas

    HTML5: Estrutura semântica das páginas.

    CSS3: Estilização avançada com Flexbox, Variáveis CSS e Animações (@keyframes).

    JavaScript (Vanilla): Lógica para manipulação do DOM na troca de abas dos perfis.

    Fontes: Google Fonts (Poppins).

verve-network/
│
├── index.html                # Página Principal (Landing Page)
├── LICENSE                   # Licença do projeto
│
└── src/
    ├── assets/
    │   └── imgs/             # Imagens do projeto (ícones, fotos de usuários)
    │
    ├── css/
    │   ├── style.css         # Estilos da Landing Page
    │   └── profile-style.css # Estilos específicos dos Perfis
    │
    └── pages/                # Páginas de perfil individuais
        ├── profile1.html
        ├── profile2.html
        ├── profile3.html
        └── ... (até profile10.html)
