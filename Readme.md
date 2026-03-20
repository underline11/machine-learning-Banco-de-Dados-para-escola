#  School Management System Database

Este repositório contém a modelagem de um banco de dados relacional para a administração de instituições de ensino, focando no controle de turmas, alunos e desempenho acadêmico.

##  Estrutura de Dados
O esquema foi projetado para refletir a hierarquia escolar padrão:
- **Professores:** Cadastro de docentes e suas respectivas especialidades.
- **Turmas:** Agrupamento de alunos sob a responsabilidade de um professor.
- **Alunos:** Registro de dados pessoais e vínculo com uma turma específica.
- **Notas:** Sistema de lançamento de avaliações vinculado ao histórico do aluno e à disciplina da turma.

##  Tecnologias
- **MySQL / MariaDB**

##  Diferenciais Técnicos
- **Normalização de Dados:** Separação clara entre as entidades para evitar redundância.
- **Integridade Referencial:** Chaves estrangeiras garantem que um aluno não pertença a uma turma inexistente e que as notas sejam atribuídas corretamente.
- **Flexibilidade:** Estrutura pronta para expansão (como adição de frequências ou horários).
