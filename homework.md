# SQL Homework

## Questions

1. Return ALL the data in the 'movies' table.
  - SELECT * FROM movies;
2. Return ONLY the name column from the 'people' table
  - SELECT name FROM people;
3. Oops! Someone at CodeClan spelled James' name wrong! Change it to reflect the proper spelling (change 'Jasmse Cox' to 'James Cox').
  - UPDATE people SET name = 'James Cox' WHERE name = 'Jasmse Cox';
4. Return ONLY your name from the 'people' table.
  - SELECT name FROM people WHERE id = 3;
5. The cinema is showing 'Batman Begins', but Batman is DC, not Marvel! Delete the entry from the 'movies' table.
  - DELETE FROM movies WHERE title = 'Batman Begins';
6. Create a new entry in the 'people' table with the name of one of the instructors.
  - INSERT INTO people (name) VALUES ('Jarrod');
7. Winston Ingram, has decided to hijack our movie evening, Remove him from the table of people.
  - DELETE FROM people WHERE name = 'Winston Ingram';
8. Somehow the list of people includes two people named 'Fred'. Change these entries to the proper names ('Jack Jarvis', 'Victor McDade')
  - UPDATE people SET name = 'Jack Jarvis' WHERE id = 9;
  - UPDATE people SET name = 'Victor McDade' WHERE id = 13;
9. The cinema has just heard that they will be holding an exclusive midnight showing of 'Guardians of the Galaxy 2'!! Create a new entry in the 'movies' table to reflect this.
  - INSERT INTO movies (title, year, show_time) VALUES ('Guardians of the Galaxy 2', 2017, '00:00');
10. The cinema would also like to make the Guardian movies a back to back feature. Update the 'Guardians of the Galaxy' show time from 12:10 to 21:30
  - UPDATE movies SET show_time = '21:30' WHERE title = 'Guardians of the Galaxy';
## Extension

1. Research how to delete multiple entries from your table in a single command.
