# SQL-Odev-8
SQL modülü kapsamındaki Odev 8
1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee(
  
  id INTEGER,
	
  name VARCHAR(50) NOT NULL,
	
  birthday DATE
  
  email VARCHAR(100),
	
  );

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Tad', '1981-05-14', 'tlorryman0@booking.com');

insert into employee (id, name, birthday, email) values (2, 'Nari', '1986-08-25', 'nkierans1@rakuten.co.jp');

insert into employee (id, name, birthday, email) values (3, 'Niven', '1981-01-30', 'nlease2@imageshack.us');

insert into employee (id, name, birthday, email) values (4, 'Raddie', '2010-08-06', 'rchadwin3@foxnews.com');

insert into employee (id, name, birthday, email) values (5, 'Shaun', '1984-09-18', 'swillmont4@mediafire.com');

insert into employee (id, name, birthday, email) values (6, 'Gregory', '2004-03-12', 'grossiter5@eventbrite.com');

insert into employee (id, name, birthday, email) values (7, 'Jeremy', '1983-12-01', 'jbackman6@printfriendly.com');

insert into employee (id, name, birthday, email) values (8, 'Bevvy', '1987-08-19', 'bstrowan7@purevolume.com');

insert into employee (id, name, birthday, email) values (9, 'Jae', '2007-07-26', 'jcribbin8@ucoz.com');

insert into employee (id, name, birthday, email) values (10, 'Daria', '1990-12-10', 'dheape9@cisco.com');

insert into employee (id, name, birthday, email) values (11, 'Tedra', '2001-10-15', 'twilliama@usgs.gov');

insert into employee (id, name, birthday, email) values (12, 'Gussi', '2020-04-14', 'ggavozzib@macromedia.com');

insert into employee (id, name, birthday, email) values (13, 'Cristie', '1981-04-12', 'cwillischc@reverbnation.com');

insert into employee (id, name, birthday, email) values (14, 'Amalee', '1986-01-19', 'adadged@engadget.com');

insert into employee (id, name, birthday, email) values (15, 'Josias', '2017-06-04', 'jmatyasheve@networkadvertising.org');

insert into employee (id, name, birthday, email) values (16, 'Isaac', '2011-05-08', 'ifolgerf@army.mil');

insert into employee (id, name, birthday, email) values (17, 'Bearnard', '1988-02-22', 'bherkessg@people.com.cn');

insert into employee (id, name, birthday, email) values (18, 'Etty', '1993-11-27', 'eskryneh@berkeley.edu');

insert into employee (id, name, birthday, email) values (19, 'Smith', '1994-05-16', 'sknucklesi@yandex.ru');

insert into employee (id, name, birthday, email) values (20, 'Aland', '2001-11-08', 'ahitzmannj@senate.gov');

insert into employee (id, name, birthday, email) values (21, 'Shem', '2019-08-30', 'sbothwellk@icq.com');

insert into employee (id, name, birthday, email) values (22, 'Johannes', '1993-03-22', 'jgawnel@illinois.edu');

insert into employee (id, name, birthday, email) values (23, 'Kiri', '2005-07-22', 'kbauchopm@bluehost.com');

insert into employee (id, name, birthday, email) values (24, 'Tabby', '1996-12-11', 'tskirlingn@123-reg.co.uk');

insert into employee (id, name, birthday, email) values (25, 'Philis', '2011-01-06', 'pstaddingo@deviantart.com');

insert into employee (id, name, birthday, email) values (26, 'Kermit', '1999-04-02', 'kceschip@networksolutions.com');

insert into employee (id, name, birthday, email) values (27, 'Meridith', '2016-06-21', 'mmckimmq@trellian.com');

insert into employee (id, name, birthday, email) values (28, 'Gilda', '1989-03-16', 'gmoughtonr@time.com');

insert into employee (id, name, birthday, email) values (29, 'Farrell', '2003-01-18', 'focuolahans@drupal.org');

insert into employee (id, name, birthday, email) values (30, 'Umeko', '2006-11-12', 'ukasert@addtoany.com');

insert into employee (id, name, birthday, email) values (31, 'Rockey', '1984-04-23', 'rmacgiffinu@clickbank.net');

insert into employee (id, name, birthday, email) values (32, 'Jacinta', '1982-01-08', 'jpuntv@free.fr');

insert into employee (id, name, birthday, email) values (33, 'Romona', '2007-12-02', 'rheatleyw@cisco.com');

insert into employee (id, name, birthday, email) values (34, 'Rabbi', '1997-12-04', 'rbeigx@unesco.org');

insert into employee (id, name, birthday, email) values (35, 'Nicolas', '1981-02-19', 'nduffy@miitbeian.gov.cn');

insert into employee (id, name, birthday, email) values (36, 'Selene', '1992-06-05', 'sgoolyz@newsvine.com');

insert into employee (id, name, birthday, email) values (37, 'Gabriel', '2006-02-14', 'goulner10@nytimes.com');

insert into employee (id, name, birthday, email) values (38, 'Cristy', '2006-03-14', 'cjozefowicz11@hibu.com');

insert into employee (id, name, birthday, email) values (39, 'Beaufort', '1988-10-30', 'bsemon12@mapy.cz');

insert into employee (id, name, birthday, email) values (40, 'Devin', '1993-06-09', 'dmayne13@sciencedaily.com');

insert into employee (id, name, birthday, email) values (41, 'Palm', '2000-09-29', 'pproschke14@nba.com');

insert into employee (id, name, birthday, email) values (42, 'Rosanna', '2021-11-27', 'rshovel15@tripod.com');

insert into employee (id, name, birthday, email) values (43, 'Shirlene', '1986-06-24', 'sschukraft16@amazon.com');

insert into employee (id, name, birthday, email) values (44, 'Janela', '2018-04-23', 'jbosence17@europa.eu');

insert into employee (id, name, birthday, email) values (45, 'Ofella', '2020-10-16', 'oedinburgh18@xing.com');

insert into employee (id, name, birthday, email) values (46, 'Elna', '1996-05-14', 'edyster19@scribd.com');

insert into employee (id, name, birthday, email) values (47, 'Maddalena', '1996-11-09', 'mhurburt1a@cpanel.net');

insert into employee (id, name, birthday, email) values (48, 'Joella', '1989-09-14', 'jlangran1b@zimbio.com');

insert into employee (id, name, birthday, email) values (49, 'Kip', '1993-12-04', 'kjosefowicz1c@hatena.ne.jp');

insert into employee (id, name, birthday, email) values (50, 'Garvin', '2006-10-01', 'galvarez1d@chronoengine.com');


3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee

    SET name='XXXX',
    
        birthday='1993-05-06',
        
        email='xxxx@xx.com',

WHERE id=1;

UPDATE employee

    SET name='YYYY',
    
        birthday='1993-08-12',
        
        email='yyyy@yy.com',

WHERE id=2;

UPDATE employee

    SET name='ZZZZ',
    
        birthday='1995-05-10',
        
        email='zzzz@zz.com',

WHERE id=3;

UPDATE employee

    SET name='TTTT',
    
        birthday='1992-05-12',
        
        email='tttt@tt.com',

WHERE id=4;

UPDATE employee

    SET name='WWWW',
    
        birthday='1991-05-08',
        
        email='wwww@ww.com',

WHERE id=5;

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee

WHERE id IN (1,2,3,4,5)

RETURNING *;
