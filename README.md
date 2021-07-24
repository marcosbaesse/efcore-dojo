# efcore-dojo

- Projeto focado em praticar e explorar a ferramenta EFCore.
- Não visa gerar exemplos para serem utilizados em produção, nem mesmo boas práticas.

# Estrutura do projeto

O projeto tem como objetivo ser estruturado para funcionar da seguinte forma:

```
/template
/src
 |_ Tema01/
 |_ Tema02/
 |_ Tema03/
 |_ TemaX....
```

Dentro de template está o projeto que será utilizado como base para os Temas que serão abordados.

Dentro de src existirão pastas com projetos dedicados a explorar um tema específico do Roadmap cada.

# Database

Inspirado pelo projeto [JesHansen/.NET-Core-SQLite](https://github.com/JesHansen/.NET-Core-SQLite), vou utilizar o [Chinook database](https://github.com/lerocha/chinook-database) como base de refeência para os exemplos.

# Roadmap

O Roadmap é feito baseado na documentação do EFCore. Não pretendo seguir a documentação a risca, mas ir abordando os temas que foram de meu maior interesse no momento.

O Roadmap será criado à medida que algum tema vai ser explorado, ou que temas venham surgir o interesse de ser abordado futuramente.

- Template: Uma api simples que retorna os dados de uma tabela do SQLite.
- Configurar Chinook Database
- Mapeamentos
- Relacionamentos
