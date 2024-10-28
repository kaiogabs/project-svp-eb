<p align="center">
<img src="https://camo.githubusercontent.com/3b58e34f4607c08fad1787cfed025ca8adae420722d089a630a89bc6e8c8f748/68747470733a2f2f692e696d6775722e636f6d2f75626c454e32682e706e67" height="100" data-canonical-src="https://i.imgur.com/ublEN2h.png" style="max-width: 100%;">


<div align="center">

<h1 tabindex="-1" class="heading-element" dir="auto">
  <a href="https://github.com/kaiogabs/project-svp-eb">Projeto de Reformulação e Criação de Site</a><br>Exército Brasileiro
</h1>


<div align="center">
  <h2>📋 Sobre o Projeto</h2>
</div>
<p align="justify">
Este projeto foi desenvolvido para documentar a migração de um site da versão Joomla 3 para Joomla 5, incluindo a reformulação visual e funcional do site existente e as criações de novas páginas. O trabalho seguiu as diretrizes do <strong>Padrão Digital do Governo Brasileiro</strong>, utilizando um template adequado a partir das especificações disponíveis em <a href="https://www.gov.br/ds/">Padrão Digital de Governo</a> para Joomla, com a atual versão do Joomla (5.2.0, neste momento), e foi implementado em <strong>PHP</strong> com um banco de dados <strong>MySQL</strong>.
</p>

<div align="center">

<h2> 🛠 Tecnologias Utilizadas</h2>

| CMS                | Linguagens                | Banco de Dados | Template                  | Arquitetura                |
|--------------------|---------------------------|----------------|---------------------------|-----------------------------|
| Joomla (3 ➔ 5)     | PHP, JavaScript, CSS, HTML | MySQL          | Padrão Digital EB Brasil   | MVC (Model-View-Controller) |

</div>

<h2> 📁 Estrutura do Projeto</h2>

#### 1. Migração do Joomla 3 para Joomla 5
   - **Ambiente Seguro**: Configuração completa para transferência segura dos dados.
   - **Instalação e Configuração**: Joomla 5 em ambiente compatível.
   - **Transferência e Compatibilidade**: Adaptação de dados e plugins para a nova versão, incluindo tabelas de banco de dados.

#### 2. Instalação e Configuração do Template Padrão Digital EB Brasil
   - Adaptação e customização do template EB Brasil com foco nas diretrizes visuais do governo.
   - Compatibilidade com Joomla 5 e ajustes de layout e estilos CSS.

#### 3. Reformulação do Conteúdo e Estrutura
   - **Atualização de Links e Navegação**: Experiência de usuário aprimorada com acessibilidade.
   - **Mensagens e Estrutura de Conteúdo**: Reestruturação para refletir a identidade e diretrizes de comunicação do Exército.
   - **SEO e Performance**: Otimizações para garantir desempenho rápido e visibilidade nas buscas.

## 🌐 Criação do Site

A construção do site foi realizada do zero, visando proporcionar uma experiência de usuário excepcional, com um design moderno e responsivo que atende aos padrões de acessibilidade e usabilidade. Os principais aspectos do projeto incluem:

- **Design Responsivo**: Implementação de um layout adaptativo utilizando CSS Flexbox e Grid, garantindo uma experiência de navegação fluida e intuitiva em diversos dispositivos, desde smartphones a desktops. Isso assegura que todas as informações e serviços sejam facilmente acessíveis independentemente do tamanho da tela.
- **Integração Social e Acessibilidade**: Implementação de botões e widgets de redes sociais, facilitando o compartilhamento de informações e promovendo a interação com o público. O site foi desenvolvido com foco em acessibilidade, seguindo as diretrizes do Modelo de Acessibilidade de Governo Eletrônico (eMAG), permitindo que todos os cidadãos, independentemente de suas capacidades, tenham acesso pleno aos serviços e informações.
- **Conformidade com Diretrizes Governamentais**: Todo o desenvolvimento foi realizado em conformidade com os objetivos do Padrão Digital de Governo, assegurando que as propriedades digitais sejam organizadas de maneira clara e compreensível, promovendo a transparência e a confiança nas informações disponibilizadas.

## 🖼 Capturas de Tela
*Insira capturas de tela do antes e depois e do design final do site para ilustrar as mudanças realizadas.*

---

## 🗂 Estrutura de Pastas

```plaintext
empresa-site/
│
├── README.md               # Documentação do projeto
├── original_site/          # Arquivos e estado original Joomla 3
│   └── assets/             # Imagens e arquivos de mídia original
├── organizado_site/        # Joomla 3 organizado antes da migração
│   ├── templates/          # Templates organizados e customizados
│   └── components/         # Componentes personalizados
├── novo_site/              # Site Joomla 5 finalizado
│   ├── templates/          # Template padrão EB Brasil e customizações
│   ├── components/         # Componentes customizados para Joomla 5
│   ├── css/                # Estilos personalizados
│   ├── js/                 # Scripts JavaScript para funcionalidades
│   └── media/              # Imagens e arquivos de mídia final
├── database/               # Scripts e backups do banco de dados MySQL
├── docs/                   # Documentação e guias adicionais
└── imagens/                # Capturas de tela do projeto
