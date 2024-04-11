# Projeto_BarberShop1.0 

Fizemos um web-site utilizando flask em python, além de outras tecnologias, como html, css, javascript e mysql workbench, que simula o agendamento para uma barbearia, no software temos funcionalidades como: 
Escolher o barbeiro;
O tipo do corte;
O horário que deseja;

### VISUAL STUDIO CODE
```
Barbearia/
│
├── static/
│   ├── css/
│   │   ├── agendast.css
│		│   ├── cadastroStyle.css
│   │   ├── escolhast.css
│   │   ├── footer.css
│   │   ├── global.css
│   │   ├── home.css
│   │   ├── loginStyle.css
│   │   ├── style.css
│   │   └── valorst.css
│   │
│   └── js/
│   │    └── main.js
│   │
│   └── img/
│   
├── templates/
│   ├── agenda.html
│		├── cadstre-se.html
│   ├── cadastro.html
│   ├── contact.html
│   ├── escolha.html
│   ├── FAQ.html
│   ├── footer.html
│   ├── homepage.html
│   ├── indexOrigin.html
│   └── valor.html
│
├── app.py
├── dao.py
└── model.py

```

### MYSQL WORKBENCH

```sql
CREATE TABLE Agendamento (
    NOME VARCHAR(20),
    DIA DATE,
    Horário DATETIME
);

```
