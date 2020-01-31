What is a JOIN:  Start from this view of a JOIN: Creating a megatable from two tables based on attributes. The tables under question can already exist or be created on the fly

## Classic Join
- select * from table1 join table2 on table1.attribute = table2.atribute

## Complex Join
- select * from (_any_subquery_selection) on_the_fly_just_created_tableA join (_any_subquery_selection) on_the_fly_just_created_tableB on on_the_fly_just_created_tableA.attribute = on_the_fly_just_created_tableB.atribute

