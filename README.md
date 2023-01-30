# resilia-banco-de-dados

Proposta:

A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos.



Perguntas:

Existem outras entidades além dessas três?
- Sim. As entidades do banco de dados são definidas à partir das necessidades, no banco de dados da Resilia, por exemplo, há a necessidade da criação de pelo menos 6 entidades: Instituição, Cursos, Alunos, Turmas, Disciplinas e Facilitadores.

Quais são os principais campos e tipos?
- Os principais campos são as chaves, e os principais tipos são: int e varchar

Como essas entidades estão relacionadas?
- Para identificar os relacionamentos, determinei o número de referência de uma entidade em outra.
1:1 uma entidade relaciona-se com uma outra
1:N uma entidade relaciona-se com várias outras
N:N várias entidades relacionam=se com várias outras
