# user2007

blog/
│
├── assets/                # Recursos estáticos (imagens, fontes, ícones, etc.)
│   ├── images/            # Imagens usadas no blog
│   ├── css/               # Arquivos de estilos CSS
│   ├── js/                # Scripts JavaScript
│   └── fonts/             # Fontes personalizadas
│
├── content/               # Conteúdo do blog (posts, páginas, etc.)
│   ├── posts/             # Posts em formato Markdown ou HTML
│   └── pages/             # Páginas estáticas (ex.: Sobre, Contato)
│
├── components/            # Componentes reutilizáveis (ex.: cabeçalhos, rodapés, etc.)
│   ├── Header.js
│   ├── Footer.js
│   └── PostCard.js
│
├── layouts/               # Layouts padrão (estrutura geral das páginas)
│   ├── BlogLayout.js
│   └── PageLayout.js
│
├── public/                # Arquivos públicos acessíveis diretamente pela URL
│   ├── robots.txt         # Arquivo para motores de busca
│   └── favicon.ico        # Ícone do site
│
├── styles/                # Estilos globais (CSS/SASS)
│   ├── global.css         # Estilos globais
│   └── theme.css          # Temas do site
│
├── utils/                 # Funções utilitárias (ex.: formatação de datas, SEO)
│   └── helpers.js
│
├── api/                   # Back-end ou integração com APIs (opcional)
│   ├── posts.js           # Integração para buscar posts
│   └── comments.js        # Integração para comentários
│
├── config/                # Configurações do projeto
│   ├── siteConfig.js      # Configurações do blog (ex.: título, descrição)
│   └── env/               # Variáveis de ambiente
│
├── node_modules/          # Dependências do projeto (gerado pelo npm/yarn)
│
├── .gitignore             # Arquivos a serem ignorados pelo Git
├── package.json           # Dependências e scripts do projeto
├── README.md              # Documentação do blog
└── index.html             # Ponto de entrada (caso seja estático)
