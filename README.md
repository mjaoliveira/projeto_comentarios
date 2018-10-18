# projeto_comentarios

my sql

create database projetos_comentarios
default character set utf8
default collate utf8_general_ci;

create table mensagens(
id int auto_increment primary key not null,
data_msg datetime,
nome varchar(50) not null,
msg text
)default charset = utf8;