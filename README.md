# TCC Theme Ideas

O TCC Theme Ideas é uma plataforma que  tem como objetivo ajudar alunos de graduação ou de cursos em que precise desenvolver  o Trabalho de Conclusão de Curso (TCC) e  que tenham dificuldades em encontrar um tema. Ao buscar um tema em uma determinada área, o aluno terá como resposta, o nome da pessoa que indicou e se é um/a professor/a ou aluno/a, o tema sugerido, uma breve descrição e  links de artigos, isso vai auxiliar o aluno na sua escolha, além de ter uma base de material para iniciar seus estudos e a produção do seu Trabalho de Conclusão de Curso. Além disso, a plataforma pode auxiliar professores que desejam orientar alunos com temas de TCC na sua área de pesquisa, assim como alunos que já concluíram o TCC, podem sugerir a continuação da sua pesquisa.

---
## How to run

  > Cloning the repository
  ```bash
    # Cloning repository
    git clone https://github.com/rubensojunior/tcc-theme-ideas.git
  ```
  > Accessing project
  ```bash
    cd tcc-theme-ideas
  ```
  > Download dependencies
  ```bash
    yarn
  ```
  > Running server project
  ```bash
    # Accessing server
    cd packages/server

    # Run migrations to create the tables
    yarn typeorm migration:run

    # Run server
    yarn dev:server
  ```
  > Running mobile project
  ```bash
    # Accessing mobile
    cd packages/mobile

    # Running emulador
    yarn android

    # Running mobile
    yarn start
  ```
  
