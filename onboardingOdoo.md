# Aprendendo odoo

*Tudo aqui gira em torno de um [mini projeto para gerenciamento de uma biblioteca](https://github.com/rvl016/Odoo-Library-Module)*

## Models
1. Entendimento basico do ORM do odoo

    1. ~~Basic Fields~~

    *Entendido os argumentos básicos de um field: `readonly`, `store`, `string`, `compute` e `default`.*

    2. ~~Relational Fields~~

    *Entendido o significado dos relacionamentos `One2many`, `many2One` e `Many2many`, e como eles são refletidos em um objeto do model.*

    3. Related Fields

2. ~~Entendimento de alguns decorators do módulo `api`~~

*Entendido o uso de decorators `constrains` e `depends`.* 


## Actions e views

### Menus
1. ~~Entendimento básico da estruturação~~

  *Entendido a hierarquia de tags `menuitem` e como ela se reflete na UI*

### Actions
1. ~~Entendimento básico do funcionamento~~

*Entendido que para um `menuitem` aparecer na UI, é preciso a associação de uma action através do argumento `action`*

2. Entendimento de outras funções além da associação a uma view

### Views

1. Uso de `button` 
2. Uso de `field`

    1. ~~Uso básico~~
    2. Uso de `widgets`

3. Uso de `groupby`


#### tree (list)
1. ~~Entendimento da estruturação básica~~
2. Uso de `button` (para um ou mais records)

#### forms
1. ~~Entendimento da estruturação básica~~

  *Uso de `sheet`, `groups`*

2. Entendimento de como esconder fields computados no form de criação de record
3. Uso de outras tags, como `notebook` e `page`
4. Entendimento de como usar views para exibição de relacionamentos *2many

#### kanban
1. Entendimento da estruturação básica

#### activity
1. Entendimento da estruturação básica

### Groups (permissões de usuários)
1. Aplicação no framework em geral

### Data
1. ~~Criação de dados em .xml~~
   
  *Uso de campos relacionais (como declarar relacionamentos) e uso de eval para datetime*

# Extendendo módulos do odoo

*Definição de um projeto que extenda algum módulo do odoo (o que e qual?)*

## Models
1. Criar um modelo com herança de outro
2. Entendimento dos diferentes tipos de herança

## Views

1. Criar uma view herdada
    1. Uso de `xpath` para manipulação do .xml existente

### Templates
1. Entendimento do uso de templates

# Uso do odoo fora da plataforma

## Routers
1. Exposição de uma API a partir do odoo

## Views
1. Uso de `QWeb`
2. Uso de javascript (**versão odoo??**) e HTML (**é o QWeb??**) para criar o cliente.
3. Consumo da API por um site odoo (**Faz sentido??**)
