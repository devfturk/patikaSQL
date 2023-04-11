    --TABLE oluşturma
    
    CREATE TABLE employee(
              id SERIAL PRIMARY KEY,
              name VARCHAR(50) NOT NULL,
              birthday DATE,
              email VARCHAR(50)
          );

	  --VERİLER
    
    insert into employee (name, birthday, email) values ('Elka Maudson', '1953-08-12', 'emaudson0@psu.edu');
    insert into employee (name, birthday, email) values ('Marielle Height', null, 'mheight1@github.io');
    insert into employee (name, birthday, email) values ('Nollie Gronauer', '1983-09-21', 'ngronauer2@abc.net.au');
    insert into employee (name, birthday, email) values ('Jayson Currm', '1971-07-04', 'jcurrm3@kickstarter.com');
    insert into employee (name, birthday, email) values ('Lynna Longshaw', '1930-04-05', null);
    insert into employee (name, birthday, email) values ('Jaime Doby', '1990-04-27', 'jdoby5@pen.io');
    insert into employee (name, birthday, email) values ('Nev Pitt', '1998-05-08', 'npitt6@arizona.edu');
    insert into employee (name, birthday, email) values ('Hilly Laingmaid', '1986-06-14', null);
    insert into employee (name, birthday, email) values ('Pearle Gutierrez', '1921-05-23', 'pgutierrez8@google.pl');
    insert into employee (name, birthday, email) values ('Huntington Wilton', '1977-04-14', 'hwilton9@slashdot.org');
    insert into employee (name, birthday, email) values ('Peyter Ricci', null, 'priccia@prweb.com');
    insert into employee (name, birthday, email) values ('Devan Androsik', null, null);
    insert into employee (name, birthday, email) values ('Danna McCambridge', '1956-01-21', 'dmccambridgec@deviantart.com');
    insert into employee (name, birthday, email) values ('Edita McGreal', '1981-02-04', 'emcgreald@amazonaws.com');
    insert into employee (name, birthday, email) values ('Jonis Delatour', null, 'jdelatoure@wordpress.com');
    insert into employee (name, birthday, email) values ('Marv Scoullar', '1962-12-14', 'mscoullarf@macromedia.com');
    insert into employee (name, birthday, email) values ('Lianna Aykroyd', '1940-12-21', 'laykroydg@taobao.com');
    insert into employee (name, birthday, email) values ('Laughton Curgenven', '1959-11-01', 'lcurgenvenh@feedburner.com');
    insert into employee (name, birthday, email) values ('Anabelle Canlin', '1922-05-10', 'acanlini@1und1.de');
    insert into employee (name, birthday, email) values ('Adriena Duckels', '1978-08-26', 'aduckelsj@gizmodo.com');
    insert into employee (name, birthday, email) values ('Codie Aslet', '1986-02-17', null);
    insert into employee (name, birthday, email) values ('Eveleen Dionis', null, null);
    insert into employee (name, birthday, email) values ('Helenka Grogor', '1975-09-01', 'hgrogorm@cbslocal.com');
    insert into employee (name, birthday, email) values ('Kacy Stairmond', '1986-07-28', 'kstairmondn@xinhuanet.com');
    insert into employee (name, birthday, email) values ('Bryce Burtwell', '1998-08-08', 'bburtwello@friendfeed.com');
    insert into employee (name, birthday, email) values ('Pate Topes', '1978-03-14', 'ptopesp@miitbeian.gov.cn');
    insert into employee (name, birthday, email) values ('Lowrance Greatreax', '1978-05-27', 'lgreatreaxq@wikipedia.org');
    insert into employee (name, birthday, email) values ('Schuyler Shelborne', '1983-08-26', 'sshelborner@goo.gl');
    insert into employee (name, birthday, email) values ('Yorgo Joddins', '1922-06-13', 'yjoddinss@blinklist.com');
    insert into employee (name, birthday, email) values ('Thatch McCarl', '1935-07-26', null);
    insert into employee (name, birthday, email) values ('Abigail Durtnel', '1923-06-09', 'adurtnelu@gizmodo.com');
    insert into employee (name, birthday, email) values ('Kalil Rossborough', null, 'krossboroughv@opensource.org');
    insert into employee (name, birthday, email) values ('Morse Scullard', '1990-03-23', null);
    insert into employee (name, birthday, email) values ('Candie Proschke', null, 'cproschkex@marketwatch.com');
    insert into employee (name, birthday, email) values ('Ramona Pedreschi', '1916-05-09', 'rpedreschiy@wsj.com');
    insert into employee (name, birthday, email) values ('Sada Darrigrand', '1911-03-08', 'sdarrigrandz@51.la');
    insert into employee (name, birthday, email) values ('Lynsey Spofford', null, 'lspofford10@imgur.com');
    insert into employee (name, birthday, email) values ('Kelcy Geldert', '1920-08-27', 'kgeldert11@eepurl.com');
    insert into employee (name, birthday, email) values ('Ted Disman', '1931-10-19', 'tdisman12@independent.co.uk');
    insert into employee (name, birthday, email) values ('Minni Tiplady', '1953-10-19', null);
    insert into employee (name, birthday, email) values ('Pattie Di Ruggiero', '1929-07-11', 'pdi14@gmpg.org');
    insert into employee (name, birthday, email) values ('Joan Barby', '1928-01-13', 'jbarby15@friendfeed.com');
    insert into employee (name, birthday, email) values ('Emmalynn Puvia', '1980-07-13', 'epuvia16@google.co.jp');
    insert into employee (name, birthday, email) values ('Aline Damato', null, 'adamato17@wordpress.org');
    insert into employee (name, birthday, email) values ('Darsey Idney', null, 'didney18@sogou.com');
    insert into employee (name, birthday, email) values ('Meta Netley', '1918-07-09', 'mnetley19@example.com');
    insert into employee (name, birthday, email) values ('Tess Burberow', '1913-12-19', 'tburberow1a@storify.com');
    insert into employee (name, birthday, email) values ('Concettina Verni', null, null);
    insert into employee (name, birthday, email) values ('Bradford Gauvin', '1962-03-11', null);
    insert into employee (name, birthday, email) values ('Brandise Wooding', '1976-10-26', null);
    
    -- UPDATE işlemleri
    
      UPDATE employee
      SET name = 'Furkan T'
      WHERE email ='cjewelll@home.pl'
      RETURNING*;

      UPDATE employee
      SET email = 'furkan@turk.com'
      WHERE id = 4
      RETURNING*;

      UPDATE employee
      SET birtday = '1977-05-10'
      WHERE name = 'Judas'
      RETURNING*;

      UPDATE employee
      SET name= 'Deneme'
      WHERE name LIKE 'Z%'
      RETURNING*;

      UPDATE employee
      SET name= 'Olusum'
      WHERE name LIKE 'O%'
      RETURNING*;

      --DELETE işlemleri
      
      DELETE FROM employee
      WHERE name ='ALANAH'
      RETURNING*;

      DELETE FROM employee
      WHERE id=12
      RETURNING*;

      DELETE FROM employee
      WHERE email = 'mpooly5@pcworld.com'
      RETURNING*;

      DELETE FROM employee
      WHERE id=6
      RETURNING*;

      DELETE FROM employee
      WHERE birtday ='2006-07-26'
      RETURNING*;
