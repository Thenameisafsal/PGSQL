psql <command>  -> initialize the cli of postgres
arguments:
  -U <username> -> username
  -p <port> -> set port config
  -f <file_path of .sql file>
  
\c <db_name> -> connect the database
\t - tuple only mode
\d - view the databases

insert into <tb_name> (col1,col2...col n) values (val1,val2,...);

alter table <tb_name> add columns (col_name type constraints);
