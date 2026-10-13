# Sua Historinha — Livro Personalizado para Crianças

> Clone da landing page e quiz interativo do site [criar.historinhapersonalizada.online](https://criar.historinhapersonalizada.online/).

## 📖 Sobre o Projeto

Este projeto é uma réplica da aplicação web do **Sua Historinha**, um funil interativo focado na criação de livros infantis personalizados. A aplicação guia o usuário através de um quiz passo a passo com pré-visualização dos traços físicos da criança e geração de narrativa customizada, integrando prova social, upsells e checkout.

## 🚀 Funcionalidades

- **Funil de Quiz em Etapas**:
  1. **Intro & Prova Social**: Apresentação visual, depoimentos e carrossel de fotos reais.
  2. **Dados Básicos**: Nome da criança e faixa etária.
  3. **Aparência Física**: Gênero, tom de pele, cor e tipo de cabelo, e cor dos olhos (com seleção visual interativa).
  4. **Tema & Moral**: Ensinamento da história (Amizade, Fé, Obediência).
  5. **Cenário**: Floresta Encantada, Reino Encantado, Fazendinha, Fundo do Mar ou cenário livre customizado.
  6. **Personalidade**: Informações para enriquecer a história.
  7. **Dedicatória**: Nome de quem presenteia e e-mail de entrega.
  8. **Upsells (Adicionais)**: Versão para colorir e entrega expressa.
  9. **Simulação de Criação**: Barra de progresso animada com micro-perguntas de engajamento.
  10. **Resultado & Paywall**: Mockup 3D interativo do livro gerado em tempo real, cronômetro de urgência e bônus.
  11. **Checkout Embutido**: Tela de pagamento inspirada na Kiwify com Pix (QR Code e Copia e Cola) e Cartão de Crédito.

## 🛠️ Tecnologias Utilizadas

- **HTML5** semântico
- **CSS3** puro com CSS Variables, animações e layout responsivo mobile-first
- **JavaScript (ES6+)** para controle de estados, validações dinâmicas, renderização condicional e cálculos do pedido
- **ImageKit CDN** para carregamento otimizado de imagens e assets

## 💻 Como Rodar Localmente

Como se trata de uma aplicação web estática, não é necessária nenhuma instalação complexa.

### Opção 1: Abrir diretamente no navegador
Basta dar um duplo clique no arquivo `index.html` ou abri-lo pelo seu navegador favorito.

### Opção 2: Com Python
```bash
# Na pasta do projeto:
python -m http.server 8000
```
Acesse em: `http://localhost:8000`

### Opção 3: Com Node.js / npx
```bash
npx serve .
```

### Opção 4: VS Code Live Server
Abra a pasta no VS Code e clique com o botão direito em `index.html` -> **Open with Live Server**.

## 📁 Estrutura de Arquivos

```
historinha-personalizada/
├── index.html       # Aplicação completa (HTML, CSS e JS)
├── .gitignore       # Arquivos ignorados pelo Git
└── README.md        # Documentação do projeto
```

## 📄 Licença & Aviso

Este repositório foi criado para fins de estudo e preservação de layout. Todos os direitos de marcas e conteúdos pertencem aos seus respectivos proprietários.
