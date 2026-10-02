# MisingaBar — Sistema de Gestão para Bar e Restaurante

Sistema desktop de gestão desenvolvido em **Python** para automatizar e centralizar as principais operações de um bar/restaurante.

> Projeto desenvolvido como aplicação prática de desenvolvimento de software, com foco em gestão de vendas, estoque, mesas, comandas, pagamentos e relatórios.

---

## Sobre o projeto

O **MisingaBar** foi desenvolvido para substituir processos manuais de gestão por uma solução digital integrada.

A aplicação permite controlar produtos, estoque, locais, mesas, comandas, vendas, promoções, pagamentos, caixa e relatórios através de uma única aplicação desktop.

O projeto também inclui **sistema de autenticação**, geração de recibos e preparação da aplicação para distribuição no Windows.

---

## Funcionalidades

- Sistema de login e autenticação
- Cadastro e gestão de produtos
- Controle de estoque
- Gestão de locais e mesas
- Gestão de comandas
- Registro de vendas
- Sistema de promoções
- Controle de pagamentos
- Controle de caixa
- Relatórios de vendas
- Geração e impressão de recibos
- Atualização automática do estoque
- Numeração de vendas
- Empacotamento para Windows

---

## Tecnologias utilizadas

- **Python**
- **Tkinter**
- **ttk**
- **SQLite**
- **SQL**
- **pathlib**
- **os**
- **sys**
- **tempfile**
- **Inno Setup**

---

## Estrutura do projeto

```text
MisingaBar/
│
├── login.py
├── interface.py
├── database.py
├── produtos.py
├── vendas.py
├── estoque.py
├── caixa.py
├── promocoes.py
├── relatorios.py
├── instalador.iss
└── README.md
```

> O banco de dados SQLite utilizado pela aplicação é mantido localmente e não é incluído neste repositório público.

---

## Fluxo básico de uma venda

```text
Login
  ↓
Selecionar local
  ↓
Selecionar mesa
  ↓
Abrir comanda
  ↓
Adicionar produtos
  ↓
Aplicar promoções
  ↓
Calcular total
  ↓
Selecionar pagamento
  ↓
Finalizar venda
  ↓
Atualizar estoque
  ↓
Registrar caixa
  ↓
Gerar recibo
```

---

## Desafios técnicos

Durante o desenvolvimento foram trabalhados:

- Integração entre diferentes módulos Python
- Modelagem e utilização de banco de dados SQLite
- Relacionamento entre tabelas
- Operações CRUD
- Controle automático de estoque
- Gestão de comandas
- Gestão de mesas e locais
- Cálculo de promoções
- Registro de pagamentos
- Autenticação de usuários
- Geração de recibos
- Impressão no Windows
- Tratamento de erros
- Debugging
- Empacotamento da aplicação
- Criação de instalador para Windows

---

## Banco de dados

O sistema utiliza **SQLite** para armazenamento local dos dados.

Entre as entidades utilizadas estão:

- Produtos
- Vendas
- Itens de venda
- Pagamentos
- Caixa
- Movimentos de estoque
- Promoções
- Usuários
- Locais
- Mesas
- Contas de mesas
- Itens de contas
- Dívidas

---

## Impacto do projeto

O MisingaBar centraliza operações que poderiam ser realizadas manualmente, proporcionando:

- Maior organização das operações
- Redução de tarefas manuais
- Melhor controle de estoque
- Melhor acompanhamento das vendas
- Centralização das informações
- Consulta rápida dos dados
- Automatização de processos
- Maior rastreabilidade das operações

---

## Aplicação prática

O projeto foi desenvolvido pensando em uma necessidade real de gestão empresarial.

A aplicação integra diferentes áreas do negócio em um único sistema, permitindo que operações como cadastro de produtos, abertura de comandas, vendas, pagamentos, atualização de estoque e controle de caixa façam parte de um fluxo integrado.

---

## Desenvolvedor

**Aristides Morais**

Desenvolvedor responsável pela concepção, desenvolvimento, integração, testes, debugging e preparação do sistema para distribuição.

### Competências demonstradas

`Python` `SQLite` `SQL` `Tkinter` `CRUD` `Desktop Development` `Database Management` `Debugging` `Software Development` `Windows`

---

## Objetivo do projeto

Este projeto faz parte do meu portfólio de desenvolvimento de software e demonstra a aplicação prática de conhecimentos em:

- Desenvolvimento de aplicações desktop
- Programação em Python
- Bancos de dados relacionais
- Interfaces gráficas
- Automação de processos
- Arquitetura modular
- Tratamento de erros
- Testes e debugging
- Distribuição de software

---

**MisingaBar — Sistema de Gestão para Bar e Restaurante**

Desenvolvido por **Aristides Morais**.
