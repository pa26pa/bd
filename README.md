# create table Livros (
 id_livro int primary key auto_increment,
 titulo varchar(200) not null,
 autor varchar(300) not null,
 ano_publicacao int,
 quantidade_estoque int
);

insert into Livros (titulo,autor,ano_publicacao,quantidade_estoque) values 
('yeyyy','Machado de Assis',1899,150),
('Amanhecer na Colheita', 'Suzzane Collins', 2025, 200),
('Jogos Vorazes','Suzanne Collins', 2008,29);

select * from Livros; 

select * from Livros where ano_publicacao > 2000;

select * from Livros order by titulo asc;
