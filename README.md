INSERT INTO movie (name, year) VALUES ('Terminator 2', 1986);

INSERT INTO movie (name, year) VALUES ('Terminator 3', 1990);

INSERT INTO movie (name, year) VALUES ('¿Y donde esta lunes?', 2017);

INSERT INTO movie (name, year) VALUES ('Thor: Ragnarok', 2017);

INSERT INTO movie (name, year) VALUES ('Iron Man 3', 2012);

select * from movie order by name desc limit 3;

select * from movie order by year desc limit 3;

alter table movie add column genre varchar(50);

update movie set genre = 'superheroe';

update movie set genre = 'accion' where name like '%Terminator%';

update movie set genre = 'animada' where name='El rey Leon';

update movie set genre = 'ciencia ficcion' where name='¿Y donde esta lunes?';

SELECT distinct(genre) FROM MOVIe;
