### **UNIVERSIDADE FEDERAL DO RIO GRANDE DO NORTE**

### **CENTRO DE ENSINO SUPERIOR DO SERIDÓ**

### **DEPARTAMENTO DE COMPUTAÇÃO E TECNOLOGIA**

### **CURSO DE BACHARELADO EM SISTEMAS DE INFORMAÇÃO**

**Jaine de Senna Santos**  
**José Rubens de Oliveira Júnior**
**Maria das Graças Dias Amorim** 


## **TCC Theme Ideas**


**Caicó – RN**  
**2020**

## Introducão

Este documento possui como objetivo definir e elencar as necessidades e características (requisitos) do sistema TCC Theme Ideas, assim como todos os elementos envolvidos em seu desenvolvimento e utilização, como perfis de usuários, riscos.

O TCC Theme Ideas é uma plataforma web que tem como objetivo ajudar alunos de graduação ou de cursos em que precise desenvolver Trabalho de Conclusão de Curso(TCC) e que tenham dificuldades em encontrar um tema.

## Histório de Revisões
Data     |     Versão  |   Descrição  | Autor |
---------| ----------- | ---------- | ------|
14/12/2020 | 1.0 | Documento Inicial | Jaine, José Rubens e Maria |


## Perfis dos Usuários

O sistema poderá ser utilizado por diversos usuários. Temos os seguintes perfis/atores:

Perfil     | Descrição   |
---------  | ----------- |
Administrador | Este usuário realiza os cadastros base e pode realizar qualquer função.
Docentes | Este usuário pode sugerir um tema para TCC, como também disponibilizar links de artigos.
Discente | Este usuário pode realizar seu cadastro na plataforma, assim como buscar por temas, pesquisando pelo curso e a área ou pode sugerir um tema também para outros alunos.

## Lista de Requisitos Funcionais

Requisito  | Descrição   | Ator |
---------  | ----------- | ---------- |
RF01 - Cadastro de usuário   | O usuário poderá fazer seu cadastro inserindo os dados: nome, sobrenome, e-mail e senha | Usuário |
RF02 - Alterar cadastro de tema  | O usuário poderá alterar os dados relacionados ao tema que ele sugeriu como: sugestão de tema, curso, área, descrição e links de artigos | Docente e Discente |
RF03 - Consultar cadastro de usuário | O usuário poderá consultar seus dados cadastrados e as informações cadastradas relacionadas ao tema que ele sugeriu como: foto do perfil, nome, e-mail, curso, sugestão de tema, área do tema, descrição de tema e links de artigo| Discente e Docente|
RF04 - Excluir cadastro de usuário   | O usuário poderá excluir seu cadastro | Docente e Discente |
RF05 - Login de usuário| O  usuário após o seu cadastro, poderá acessar a plataforma com seu login com: e-mail e senha | Docente e Discente |
RF06 - Usuário pode redefinir senha| Caso o usuário esqueça sua senha, ele poderá redefinir sua senha utilizando o e-mail que informou no cadastrado | Docente e Discente |
RF07 - Cadastrar tema de TCC | O usuário poderá cadastrar um tema informando os dados: nome, curso, sugestão de tema, descrição, área do tema, adicionar links de artigos e informar se é um usuário discente ou docente  | Discente e Docente |
RF08 - Alterar tema de TCC |O usuário poderá alterar um tema ao qual ele cadastrou  | Docente e Discente |
RF09 - Remover tema de TCC | O usuário poderá remover um tema ao qual ele cadastrou | Discente e Docente |
RF010 - Buscar tema de TCC |O usuário poderá buscar por um tema de acordo com curso, tipo de usuário e área  | Docente e Discente |
RF011 - Listar tema de TCC | O usuário poderá listar um tema de TCC |Discente e Docente |
RF012 - Listar todos os temas de TCC | O usuário poderá listar todos os temas de TCCs  cadastrados | Discente e Docente  |
RF013 - Sugerir tema de TCC |O usuário poderá sugerir temas de TCC  | Docente e Discente |
RF014 Detalhar informações cadastradas do tema de TCC -| O usuário poderá visualizar informações mais detalhadas sobre o tema | Discente | 
RF015 - Favoritar tema de TCC | O usuário pode favoritar um tema da qual ele tenha gostado | Discente|


## Lista de Requisitos Não-Funcionais

Requisito  | Descrição   | Ator |
---------  | ----------- | ---------- |
RF01 - Cadastro de usuário   | O usuário poderá fazer seu cadastro inserindo os dados: nome, sobrenome, e-mail e senha | Usuário |
RF02 - Alterar cadastro de tema  | O usuário poderá alterar os dados relacionados ao tema que ele sugeriu como: sugestão de tema, curso, área, descrição e links de artigos | Docente e Discente |
RF03 - Consultar cadastro de usuário | O usuário poderá consultar seus dados cadastrados e as informações cadastradas relacionadas ao tema que ele sugeriu como: foto do perfil, nome, e-mail, curso, sugestão de tema, área do tema, descrição de tema e links de artigo| Discente e Docente|
RF04 - Excluir cadastro de usuário   | O usuário poderá excluir seu cadastro | Docente e Discente |
RF05 - Login de usuário| O  usuário após o seu cadastro, poderá acessar a plataforma com seu login com: e-mail e senha | Docente e Discente |
RF06 - Usuário pode redefinir senha| Caso o usuário esqueça sua senha, ele poderá redefinir sua senha utilizando o e-mail que informou no cadastrado | Docente e Discente |
RF07 - Cadastrar tema de TCC | O usuário poderá cadastrar um tema informando os dados: nome, curso, sugestão de tema, descrição, área do tema, adicionar links de artigos e informar se é um usuário discente ou docente  | Discente e Docente |
RF08 - Alterar tema de TCC |O usuário poderá alterar um tema ao qual ele cadastrou  | Docente e Discente |
RF09 - Remover tema de TCC | O usuário poderá remover um tema ao qual ele cadastrou | Discente e Docente |
RF010 - Buscar tema de TCC |O usuário poderá buscar por um tema de acordo com curso, tipo de usuário e área  | Docente e Discente |
RF011 - Listar tema de TCC | O usuário poderá listar um tema de TCC |Discente e Docente |
RF012 - Listar todos os temas de TCC | O usuário poderá listar todos os temas de TCCs  cadastrados | Discente e Docente  |
RF013 - Sugerir tema de TCC |O usuário poderá sugerir temas de TCC  | Docente e Discente |
RF014 Detalhar informações cadastradas do tema de TCC -| O usuário poderá visualizar informações mais detalhadas sobre o tema | Discente | 
RF015 - Favoritar tema de TCC | O usuário pode favoritar um tema da qual ele tenha gostado | Discente|


## Lista de Requisitos Não-Funcionais

Requisito                                 | Descrição   |
---------                                 | ----------- |
RNF001 - Deve ser acessível via navegador | Deve abrir perfeitamente no Firefox e no Chrome. |
RNF002 - Consultas deve ser eficiente | O sistema deve executar as consultas em milissegundos |
RNF003 - Log e histórico de acesso e funções | Deve manter um log de todos os acessos e das funções executadas pelo usuário |
RNF004 - Interface de fácil navegação | O software terá uma interface de fácil navegação, onde os usuários poderão utilizá-lo sem muitas dificuldades;|
RNF005 - Sistema operacional Windows ou Linux |O computador deve ter como Sistema Operacional uma dessas 2 opções.
RF006 - Conexão com a internet |  	Deve manter uma conexão ativa com a Internet.



## Riscos

Tabela com o mapeamento dos riscos do projeto, as possíveis soluções e os responsáveis.

Data | Risco | Prioridade | Responsável | Status | Providência/Solução |
------ | ------ | ------ | ------ | ------ | ------ |
19/09/2020 | Não entregar o sistema completo | Alta | Todos | Vigente | Fazer esforço pra tentar entregar as funcionalidades no prazo definido. |
19/09/2020 | Ausência por qualquer motivo do cliente | Média | Gerente | Vigente | Planejar o cronograma tendo em base a agenda do cliente |
28/09/2020 | Divisão de tarefas mal sucedida | Baixa | Gerente | Vigente | Acompanhar de perto o desenvolvimento de cada membro da equipe |
28/09/2020 | Implementação de protótipo com as tecnologias | Alto | Todos | Resolvido | Encontrar tutorial com a maioria da tecnologia e implementar um caso base do sistema |


