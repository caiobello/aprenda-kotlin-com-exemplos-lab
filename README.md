# Aprenda Kotlin Com Exemplos: Desafio de Projeto (Lab)

Desafio de Projeto criado para avaliação do conteúdo técnico explorado no repositório [aprenda-kotlin-com-exemplos](https://github.com/digitalinnovationone/aprenda-kotlin-com-exemplos). **Nesse contexto, iremos abstrair o seguinte domínio de aplicação:**

**A [DIO](https://web.dio.me) possui `Formacoes` incríveis que têm como objetivo oferecer um conjunto de `ConteudosEducacionais` voltados para uma stack tecnológica específica, preparando profissionais de TI para o mercado de trabalho. `Formacoes` possuem algumas características importantes, como `nome`, `nivel` e seus respectivos `conteudosEducacionais`. Além disso, tais experiências educacionais têm um comportamento relevante ao nosso domínio, definido pela capacidade de `matricular` um ou mais `Alunos`.**

##

Este código em Kotlin é um exemplo de um sistema de gerenciamento de formação educacional. Ele permite a criação de formações com diferentes níveis de dificuldade e conteúdos educacionais, e a matrícula e desmatrícula de usuários nessas formações.

O código consiste em uma enumeração que define os níveis de conhecimento (iniciante, médio e avançado)<br> 
Uma classe que representa um usuário com seu nome e duas classes de dados: ConteudoEducacional e Formacao.

A classe ConteudoEducacional representa um conteúdo educacional com um nome e duração em minutos. <br>
A classe Formacao representa uma formação com um nome, nível de dificuldade, uma lista de conteúdos educacionais e uma lista de usuários inscritos.

O programa tem a função main() que cria alguns usuários, conteúdos educacionais e formações, e executa algumas matrículas e desmatrículas para demonstrar o uso do sistema.

A função matricular() da classe Formacao permite a matrícula de um usuário na formação.<br>
A função desmatricular() permite a desmatrícula. Ambas as funções verificam se o usuário já está matriculado ou não na formação.

O código está organizado e inclui comentários explicativos para ajudar na compreensão do código.
