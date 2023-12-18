1 id int unsigned primary_key(notnull unique) autoincrement
2 brand varchar notnull
3 color varchar notnull
4 km mediumInt-unsigned notnull
5 weight smallInt double(7,2) unsigned null
6 price int unsigned notnull decimal (9,2)
7 description text null
8 year smallInt unsigned notNull
9 discount_percentace tinyInt notNull default(0)
10 image_url Text varchar notnull
