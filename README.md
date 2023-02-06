Curso:
- nome varchar(20),
- carga_horaria int,
- sala int,
- id_curso int primary key,
- local varchar(15);


Turma:
- turno varchar(5),
- professor varchar(30),
- numero_da_turma int primary key,
- nivel varchar(20),
- quantidade_de_alunos int;


Alunos:
- nome varchar(50),
- email varchar(50),
- celular varchar(15),
- cpf varchar(15) primary key,
- endereco varchar(50);
