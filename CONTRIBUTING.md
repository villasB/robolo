# Como contribuir com este projeto

Antes de contribuir com o desenvolvimento de qualquer projeto do SMIR-IMT, 
por favor primeiro discuta as mudanças planejadas criando um issue. Em todas as
suas interações com os nossos projetos, por favor leia e siga nosso 
[Código de Conduta](#codigo-de-conduta)

# Índice
1. [Criando um issue](#criando-issues)
  1. [Template](#issue-template)
  2. [Example of a good issue](#example-task-rows-should-have-a-maximum-width)
2. [Pull requests](#processo-de-pull-request)
3. [Code of Conduct](#condigo-de-conduta)

# Criando um issue

Para sugerir uma mudança para o projeto Robôlo é obrigatória a criação de um 
issue, o que pode ser feito através do nosso 
[Issue Tracker](https://github.com/imt-smir/robolo/issues). Esse é o ponto de
entrada para a sua contribuição.

Criar um issue de alta qualidade é fundamental para a discussão e aceitação de
sua contribuição. Um bom issue deve sempre conter as seguintes informações:

 1. Uma descrição detalhada do issue
     - Para problemas e bugs, uma descrição detalhada de como reproduzí-lo.
     - Para adições de novos features, adicione uma descrição detalhada da sua
     proposta.
 2. Um checklist de tarefas de desenvolvimento

## Issue template
```
[Title of the issue or feature request]

Detailed description of the issue. Put as much information as you can, potentially
with images showing the issue or mockups of the proposed feature.

If it's an issue, add the steps to reproduce like this:

Steps to reproduce:

1. Open Endeavour
2. Create a task
3. ...

## Development Tasks

* [ ]  development tasks

```

This is an example of a good and informative issue:

---
<pre>
<h1>Example: Task rows should have a maximum width</h1>

When using a very wide window, task rows grow super wide currently, because they
always take up the entire width of the window. This is not great for window sizes
larger than about 600px.

<img src="https://gitlab.gnome.org/World/Endeavour/uploads/a414239a44c5b2714634df5cb85a7a78/too-wide.png" width="400px" />

This is how it would look with a maximum width of 650px:

<img src="https://gitlab.gnome.org/World/Endeavour/uploads/7dfc77b1c3cc942cf1977770ea15b198/too-wide-fixed.png" width="400px" />

<h3>Design Tasks</h3>
* [x] Define how much rows should expand horizontally

<h3>Development Tasks</h3>
* [ ] Implement maximum-width rows

<h3>QA Tasks</h3>
* [ ] Rows don't grow horizontally above 650px
* [ ] No regressions were introduced

</pre>

---

# Pull Request Process

1. Garanta que o seu código compila/roda.
2. Se está adicionando novas interfaces ao projeto, elas devem estar
   devidamente documentadas.
3. As mensagens de commit devem ter a seguinte formatação:

```
   Linha de Resumo

   Um parágrafo explicando o problema e o seu contexto.

   Outro parágrafo explicando a sua solução.

   <link para o issue>
```

4. Os pull requests serão integrados apenas após a revisão de algum dos
   professores do projeto.

---

# Código de conduta

Endeavour is a project developed based on GNOME Code of Conduct. You can read it below:

## Summary

GNOME creates software for a better world. We achieve this by behaving well towards
each other.

Therefore this document suggests what we consider ideal behaviour, so you know what
to expect when getting involved in GNOME. This is who we are and what we want to be.
There is no official enforcement of these principles, and this should not be interpreted
like a legal document.

## Advice

 * **Be respectful and considerate**: Disagreement is no excuse for poor behaviour or personal
     attacks. Remember that a community where people feel uncomfortable is not a productive one.

 * **Be patient and generous**: If someone asks for help it is because they need it. Do politely
     suggest specific documentation or more appropriate venues where appropriate, but avoid
     aggressive or vague responses such as "RTFM".

 * **Assume people mean well**: Remember that decisions are often a difficult choice between
     competing priorities. If you disagree, please do so politely. If something seems outrageous,
     check that you did not misinterpret it. Ask for clarification, but do not assume the worst.

 * **Try to be concise**: Avoid repeating what has been said already. Making a conversation larger
     makes it difficult to follow, and people often feel personally attacked if they receive multiple
     messages telling them the same thing.


In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

---

# Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
