#  NexusFin - FIAP


O **NexusFin** é uma interface de dashboard moderna e minimalista voltada para a gestão de finanças pessoais e corporativas. Este projeto foi desenvolvido como parte do Challenge corporativo na FIAP, aplicando conceitos avançados de Front-End, responsividade e fidelidade de design.

---

Funcionalidades da Interface

* **Módulo de Registro:** Área dedicada para o lançamento e controle de lucros e despesas de forma simplificada.
* **Módulo Banco:** Tela preparada para futura integração e conectividade simulada com APIs bancárias.
* **Módulo Análise:** Seção voltada para a geração de relatórios analíticos e acompanhamento de gráficos financeiros.
* **Painel de Perfil:** Menu superior responsivo com identificação do usuário e atalhos rápidos de navegação.

---

Tecnologias e Arquitetura Aplicadas

A estrutura foi planejada seguindo as melhores práticas de desenvolvimento web, dividindo responsabilidades entre marcação estrutural e folhas de estilo:

* **HTML** Estrutura limpa e organizada para melhor acessibilidade.
* **Tailwind CSS:** Utilizado para toda a estilização utilitária, grids dinâmicos e controle de responsividade.
* **CSS:** Arquivo separado para estilizações específicas de efeitos de sombra pesada (`card-shadow`) e efeito neon (`icon-glow`).
* **Componentes SVG:** Todos os ícones e elementos gráficos foram codificados diretamente em formato vetorial inline para eliminar mídias externas e garantir resiliência contra quebras de imagem.

---

Responsividade Completa

O layout adapta-se perfeitamente a diferentes tamanhos de tela (Desktops, Tablets e Smartphones):
* **Mobile First / Adaptação:** O grid de três colunas dos cards se empilha verticalmente de forma automática em resoluções menores.
* **Otimização de Espaço:** Elementos textuais secundários do cabeçalho ocultam-se inteligentemente em viewports mobile para priorizar as ações principais.

---

Organização dos Arquivos

```text
├── CSS/
│   └── style.css      # Estilizações customizadas de efeitos e fontes
├── index.html         # Estrutura HTML principal com Tailwind integrado
└── README.md          # Documentação do repositório
