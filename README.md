Workshop de Git 2024
======================

por [Bernardo Quaresma](mailto:bernardo@tegraf.puc-rio.br)


O que é?
--------

Git é uma ferramenta para gerenciamento distribuído de versões de um projeto composto por conjunto de arquivos e pastas.

Cada modificação em um ou mais arquivos gera uma nova versão do projeto que possui uma apontamento de diferenças para a versão anterior.

O gerenciamento do projeto é considerado distribuiído porque pode ser feito em ramos e máquinas independentes.

Além de armazenamento e versionamento dos arquivos do projeto, o Git oferece uma forma de incorporar modificações feitas no mesmo arquivo de ramos independentes em um ramo principal.


Porque Git?
-----------

A possibilidade de desenvolver e testar novas funcionalidades e melhorias de forma distribuíde e independente facilita a divisão e planejamento do trabalho.

Além disso, infraestruturas como GitHub e GitLab oferecem ferramentas de criação e atribuição de pendências (issues) que dinamizam o gerenciamento de projetos com equipes distribuídas.

Finalmente, com o Git é possível desenhar um fluxo de trabalho comum que reduz a necessidade de comunicação instantânea entre os integrantes do projeto.


Como Usar?
----------

  - Repositórios Remotos x Locais
  - Acessando o repositório de um projeto remoto (GitHub)
  - Criando um Repositório local (Clone)
  - Ramificando o desenvolvimento (Branch)
  - Modificando o ramo local (Stage/Commit)
  - Atualizando o repositório remoto (Push)
  - Integrando os Ramos de Desenvolvimento (Pull/Merge Request)


Exercício
---------

1. Repliquem este projeto (Fork) no GitHub
2. Dividam os tópicos da próxima seção entre vocês
3. Clonem o projeto replicado na máquina de vocês
4. Criem ramos locais nomeando com um breve descrição da pendência que estão resolvendo (Ex: Formatacao)
5. Preencham o tópico atribuído para você (vale consulta)
6. Modifiquem o ramo local com as alterações incluindo uma mensagem que a descreva
7. Atualize o repositório remoto com o ramo criado


Markdown
--------

Markdown é uma forma de escrever arquivos texto seguindo regras que serão seguidas para exibição do texto com formatação.

### Formatação

Tutorial de como formatar o texto de um README. Iremos abordar como colocar o texto em negrito e em itálico. 

#### Itálico

Como colocar o texto de um README para itálico?
 - deve-se colocar a sessão do texto que se quer colocar em itálico entre um asterisco (um asterisco de cada lado). 
 
 Por exemplo: *itálico* ou *texto em itálico*.

#### Negrito

Como colocar o texto de um README para negrito?
 - deve-se colocar a sessão do texto que se quer colocar em negrito entre dois asteriscos (dois asteriscos de cada lado).
 
 Por exemplo: **negrito** ou **texto em negrito**.

#### Bloco de Código
```
bloco de codigo
```
### Listas

#### Listas Numeradas
1. item 1
2. item 2
3. item 3

#### Listas com subitems

Para criar uma lista com subitens é necessário utilizar o caractere '*' ou '-':

* Item 1
  * subitem 1
  * subitem 2
- Item 2
  - subitem 1
  - subitem 2


#### Listas de Tarefas

Para criar uma lista de tarefas é necessário utilizar '-' e '[]', este ultimo podendo ser utilizado dessa forma anterior quando não preenchido ou '[x]' dessa forma quando preenchido :

- [x] Faculdade
- [ ] Estágio 
- [ ] Academia 
- [ ] Estudo

### Tabelas

Para fazer uma tabela é preciso inserir a barra vertical (|) separando as colunas
Um exemplo de código é: 

`|título 1 | título 2 | título 3| `<br/>
`|--|--|--|` <br/>
`| L1 - C1 | L1 - C2 | L1 - C3 |`<br/>
`| L2 - C1 | L2 - C2 | L2 - C3 |`<br/>

| título 1 | título 2 | título 3| 
|:--------:|:--------:|:-------:|
| L1 - C1  | L1 - C2  | L1 - C3 |
| L2 - C1  | L2 - C2  | L2 - C3 |



Anotações
---------

Usem esse espaço para manter uma lista de anotações e dicas como comandos do Git, links do GitHub e exemplos de Markdown.

1.
2.
3.

4. É importante não esquecer o passo a passo. Primeiro fazemos um fork e colocamos os contribuintes com o add. Depois, clonamos e criamos um branch( clicar no botão do meio e depois nos ...). Para fazer o commit, precimos escrever uma mensagem, senão da erro. Após isso, publicamos o branch e crimaos o pull request. Para ele ser feito, adicionamos uma pessoa contribuinte do projeto para revisar e fazer o merge (boas práticas).



