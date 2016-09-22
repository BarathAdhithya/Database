# Database
TableCreation

create table PRODUCT
(
id varchar2(20) Primary key,
name varchar2(30) not null,
descrition varchar,
)

create table SUPPLIER
(
id varchar2(20) Primary key,
name varchar2(30) not null,
address varchar2(100),
)

create table CATEGORY
(
id varchar2(20) Primary key,
name varchar2(30) not null,
descrition varchar,
)
