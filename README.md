# Shopping
##Tables

### Table 1: Books
| Book Names | Categories | Price | Published Year|
| -- | -- | -- | -- |
| Java Edition7 | ComputerScience | RS.400 | 2019 |
| Physiology | Medical | RS.800 | 2018 |
| Company Law | Law | RS.700 | 2017 |
| Every One Has A Story | Story Book | RS.200 | 2016 |
| Untold Story of Love | Story Book | RS.500 | 2017 |
 
 #### Feature 1: Display All Books
 Select * from Books;
 
 #### Feature 2: Display All Books - Sort by Price low to high ASC
 Select * from Books ORDER BY Price asc;
 
 #### Feature 3: Display All Books - Sort by Price  high to low DESC
 Select * from Books ORDER BY Price desc;
 
 #### Feature 4: Display All Books - Based on Rage
 Select * from Books where price between 200 and 800;
 
 #### Feature 5: Display All Books - Based on Categories
 Select * from Books where categorie = Story book;
 
 
