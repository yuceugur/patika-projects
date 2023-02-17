# ODEV 8
1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```SQL
CREATE TABLE employee
(id INTEGER NOT NULL,
name VARCHAR(50) NOT NULL,
birthday DATE,
email VARCHAR(50));
```
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```SQL
insert into employee (id, name, birthday, email) values (1, 'Gun', '1906/12/01', 'gyanshonok0@wordpress.com');
insert into employee (id, name, birthday, email) values (2, 'Shay', '1905/09/29', 'sdiglin1@hubpages.com');
insert into employee (id, name, birthday, email) values (3, 'Dianne', '1960/08/11', 'dtompkins2@answers.com');
insert into employee (id, name, birthday, email) values (4, 'Barret', '1912/05/07', null);
insert into employee (id, name, birthday, email) values (5, 'Addie', '1947/05/18', 'aatack4@goodreads.com');
insert into employee (id, name, birthday, email) values (6, 'Kamila', null, 'kokelly5@liveinternet.ru');
insert into employee (id, name, birthday, email) values (7, 'Richmond', '1973/05/19', 'rjasiak6@answers.com');
insert into employee (id, name, birthday, email) values (8, 'Sanderson', '1984/02/07', 'schandlar7@so-net.ne.jp');
insert into employee (id, name, birthday, email) values (9, 'Lisbeth', '2002/01/15', 'lmallia8@scribd.com');
insert into employee (id, name, birthday, email) values (10, 'Felita', '1919/01/08', 'fboeter9@hp.com');
insert into employee (id, name, birthday, email) values (11, 'Zelda', '2008/02/28', 'zkimbera@gravatar.com');
insert into employee (id, name, birthday, email) values (12, 'Danyelle', '1987/05/13', 'dmaginotb@posterous.com');
insert into employee (id, name, birthday, email) values (13, 'Verene', '1998/12/11', 'vizhakc@japanpost.jp');
insert into employee (id, name, birthday, email) values (14, 'Valdemar', '1987/01/28', 'vwarlawed@upenn.edu');
insert into employee (id, name, birthday, email) values (15, 'Hildagard', '1984/09/26', 'hdominiake@angelfire.com');
insert into employee (id, name, birthday, email) values (16, 'Alison', '1910/08/23', 'adalgettyf@theatlantic.com');
insert into employee (id, name, birthday, email) values (17, 'Marisa', '1996/06/23', 'mforsterg@opensource.org');
insert into employee (id, name, birthday, email) values (18, 'Leonhard', '1981/12/08', 'lwandsh@linkedin.com');
insert into employee (id, name, birthday, email) values (19, 'Deloris', '1956/07/05', 'dmatuskiewiczi@techcrunch.com');
insert into employee (id, name, birthday, email) values (20, 'Dre', '1962/05/04', 'dmolesj@zdnet.com');
insert into employee (id, name, birthday, email) values (21, 'Claudie', '1970/12/13', null);
insert into employee (id, name, birthday, email) values (22, 'Trude', '1940/01/30', 'trozierl@aol.com');
insert into employee (id, name, birthday, email) values (23, 'Ulrick', '1985/08/22', 'uthoriusm@examiner.com');
insert into employee (id, name, birthday, email) values (24, 'Hadley', '1962/03/01', null);
insert into employee (id, name, birthday, email) values (25, 'Eadie', '1949/11/15', 'escottinio@upenn.edu');
insert into employee (id, name, birthday, email) values (26, 'Salim', '1945/09/17', 'shiomp@army.mil');
insert into employee (id, name, birthday, email) values (27, 'Tann', '1938/06/07', 'tharradenceq@discuz.net');
insert into employee (id, name, birthday, email) values (28, 'Max', '1945/11/05', 'mbeavenr@google.nl');
insert into employee (id, name, birthday, email) values (29, 'Alard', null, 'aespleys@hatena.ne.jp');
insert into employee (id, name, birthday, email) values (30, 'Mord', null, 'msurmanwellst@lycos.com');
insert into employee (id, name, birthday, email) values (31, 'Obadias', '2003/12/12', 'ogroomeu@cnn.com');
insert into employee (id, name, birthday, email) values (32, 'Sauncho', '1975/12/03', 'sminchinv@mysql.com');
insert into employee (id, name, birthday, email) values (33, 'Bella', '1947/02/11', 'bsoigouxw@123-reg.co.uk');
insert into employee (id, name, birthday, email) values (34, 'Eldredge', '1976/12/12', null);
insert into employee (id, name, birthday, email) values (35, 'Lazaro', null, 'lmanny@typepad.com');
insert into employee (id, name, birthday, email) values (36, 'Nanny', '1956/06/26', 'nphinz@edublogs.org');
insert into employee (id, name, birthday, email) values (37, 'Kaia', '1960/08/30', 'kscholes10@china.com.cn');
insert into employee (id, name, birthday, email) values (38, 'Ignaz', '1993/07/26', 'ilothlorien11@jimdo.com');
insert into employee (id, name, birthday, email) values (39, 'Brandi', '1998/06/03', 'bnafzger12@themeforest.net');
insert into employee (id, name, birthday, email) values (40, 'Vin', '1974/04/05', 'vperks13@cisco.com');
insert into employee (id, name, birthday, email) values (41, 'Obadias', '1981/07/22', 'osmidmor14@nydailynews.com');
insert into employee (id, name, birthday, email) values (42, 'Eudora', '1971/05/01', 'epashen15@google.it');
insert into employee (id, name, birthday, email) values (43, 'Carole', null, 'civanisov16@nsw.gov.au');
insert into employee (id, name, birthday, email) values (44, 'Gracia', '1924/05/02', 'galywen17@mail.ru');
insert into employee (id, name, birthday, email) values (45, 'Guenna', '2008/01/24', null);
insert into employee (id, name, birthday, email) values (46, 'Biddy', '1993/03/22', 'bregnard19@delicious.com');
insert into employee (id, name, birthday, email) values (47, 'Lanie', '1967/02/01', 'llottrington1a@vimeo.com');
insert into employee (id, name, birthday, email) values (48, 'Perry', '2003/12/01', 'patchly1b@cyberchimps.com');
insert into employee (id, name, birthday, email) values (49, 'Ignaz', '1993/10/13', 'idoornbos1c@mit.edu');
insert into employee (id, name, birthday, email) values (50, 'Kali', '1996/02/08', 'kyakunchikov1d@goo.ne.jp');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```SQL
UPDATE employee
SET name = 'Ugur',
	email = 'uguryuce@yclr.com'
WHERE id = 3
RETURNING *
```

```SQL
UPDATE employee
SET name = 'Melike',
	birthday = '2000/11/29'
WHERE id = 6
RETURNING *
```

```SQL
UPDATE employee
SET name = 'lokman',
	email = 'lok@man.com',
    birthday = '1945/3/23'
WHERE name = 'Mord'
RETURNING *
```

```SQL
UPDATE employee
SET name = 'Oldest',
	email = 'oldest@man.com'
WHERE birthday = '1919/01/08'
RETURNING *
```

```SQL
UPDATE employee
SET name = 'Emco',
	email = 'emco@cos.com'
WHERE email = 'sminchinv@mysql.com'
RETURNING *
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```SQL
DELETE FROM employee
WHERE email = 'oldest@man.com'
RETURNING *
```

```SQL
DELETE FROM employee
WHERE id = 34
RETURNING *
```

```SQL
DELETE FROM employee
WHERE name = 'Emco'
RETURNING *
```

```SQL
DELETE FROM employee
WHERE birthday = '1945/3/23'
RETURNING *
```

```SQL
DELETE FROM employee
WHERE id BETWEEN 30 AND 32
RETURNING *
```