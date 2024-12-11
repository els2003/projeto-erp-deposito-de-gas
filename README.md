# Projeto de um ERP para depósito de gás.

## Tecnologias:

Codeigniter4, PHP, JavaScript, AJAX, jQuery, MySQL, SQL, Bootstrap5, CSS3 e HTML5.
Biblicotecas de JavaScript: Flatpickr, DataTables, ApexCharts e jQuery Mask.

## Funcionalidades:

### - Clientes
Controle, edição, remoção, armazenamento de dados e informações, estimativas da próxima venda, registro de vendas.
### - Fornecedores
Controle, edição, remoção, armazenamento de dados e informações, registro de compras.
### - Usuários
Controle, edição, remoção, armazenamento de dado, funções, visibilidade e acessos estabelecidos pela função do usuári.
## - Autenticação e Autorização
Acesso por login, controle da visibilidade e acesso dos usuarios de acordo com sua função.
### - Vendas
Registro, manipulação, dados estatísticos completos, controle de preço de custo variável por lotes (FIFO), estimativa de vendas, incremento de lucro liquido nas contas movimento, atualização de estoque, etc.
### - Financeiro
Registro, criação e edição de métodos de pagamentos, contas movimento, planos de conta, etc.
### - Contas a pagar
Registro das contas, manipulação, dados estatísticos, lançamento, baixas com decremento nas contas movimento, planos de contas para a conta, etc.
### - Estoque
Registro, manipulação, marcação, dados estatísticos.
### - Compras
Registro, manipulação, dados estatísticos, lançamento de contas a pagar, 
### Transações Financeiras
Todas transações financeiras e fluxos monetários (vendas, pagamentos de despesas, transferências, retiradas, entradas) são registradas detalhadamente e por completo (totalmente rastreável e reversível).
### D.R.E.
Dados da Demonstração do Resultado de Exercício precisos, detalhados e relatando a saúde financeira de empresa.
### Mais...
Funcionalidade que se conectam e trabalham juntas para o funcionamento da aplicação, segurança, velocidade de carregamento, validação de dados e regras de negócio.

## Funcionalidades Técnicas:

### - Segurança
O sistema conta com proteção CSRF e limite de requests por IP.
Alteração de senha com deslogamento de todos dispositivos logados ao sistema na conta do usuário.
Validação dos dados de entrada para implementar e adequar as regras de negócio e ao banco de dados.
### - Velocidade
As páginas tem os seus conteudos divididos em blocos de conteúdo, os quais após o carregamento da página fazem solicitações AJAX ao sistema usando a JavaScript Fetch API, e após a resposta do backend apresentam as informações conforme o programado (Gráficos, dados, tabelas, etc.).


Projeto freelance para o desenvolvimento de um sistema de gerenciamento para uma empresa distribuidora de botijões de gás.
Atualmente o sistema está em produção e teste da sua primeira versão (v1.0.0), está gerando registros.
O sistema permite a expansão de novas funcionalidades e campos, para adaptação e updgrades futuros.
