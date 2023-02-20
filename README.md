# DESAFIO: Modelo de domínio e ORM

# Sobre o desafio

### Premissas

- Principal premissa foi dar introdução ao modelo de domínio, e Mapeamento do objeto-relacional, fazendo um seeding na mão com auxilio do banco de dados H2 para realizar as consultas.
- É um sistema que possui um modelo de domínio relativamente simples,
porém abrangente, ou seja, que explore vários tipos de relacionamentos entre as
entidades de negócio (muitos-para-um, muitos-para-muitos, etc.).
- O sistema possibilita a aplicação de vários conhecimentos importantes das
disciplinas de fundamentos.
- O sistema contem as principais funcionalidades que se espera de um
profissional iniciante deve saber construir, tais como telas de cadastro e fluxos de
caso de uso.


## 

### Visão geral do sistema

Deseja-se construir um sistema para gerenciar as informações dos participantes das atividades de um
evento acadêmico. As atividades deste evento podem ser, por exemplo, palestras, cursos, oficinas
práticas, etc. Cada atividade que ocorre possui nome, descrição, preço, e pode ser dividida em vários
blocos de horários (por exemplo: um curso de HTML pode ocorrer em dois blocos, sendo necessário
armazenar o dia e os horários de início de fim do bloco daquele dia). Para cada participante, deseja-se
cadastrar seu nome e email.


### Respeitando o seguinte Modelo Conceitual:

![image](https://user-images.githubusercontent.com/88008441/220119527-2ee1b369-730f-4aa2-b2da-2e2ef1e94d5a.png)

### Instância dos dados do seeding

![image](https://user-images.githubusercontent.com/88008441/220119658-e02b77bc-78e8-4011-bda6-a0a4d624499a.png)


# Tecnologias utilizadas

- Java
- Spring Boot
- JPA / Hibernate
- Maven
- Banco H2

# Como executar o projeto

Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/PauloSergioo/Desafio-Clientes-CRUD

```

# Educador

[DevSuperior - Escola de programação](https://devsuperior.com.br/)

[![DevSuperior no Instagram](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/ig-icon.png)](https://instagram.com/devsuperior.ig) ![DevSuperior no Youtube](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/yt-icon.png)
