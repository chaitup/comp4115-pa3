2a)
   mysql> select area(66);
    +---------------+    |     area(7)   |    +---------------+    |         153.9 |    +---------------+
    1 row in set (0.00 sec)
   mysql> select area(100);    +----------------+    |    area(100)   |    +----------------+    |        31400.0 |    +----------------+    mysql> select area(1.2);	+----------------+	|    area(1.2)   |	+----------------+	|            4.5 |	+----------------+		1 row in set (0.00 sec)
	mysql> select area(4);	+--------------+	|    area(4)   |	+--------------+	|           50 |	+--------------+		1 row in set (0.00 sec)
	
2b)
    mysql> select  time(10800);
    +-----------------------+    |  time(10800)          |    +------------- ---------+    | 3 Hours, 0 Minutes, 0 Seconds    |    +------------- ---------+
    1 row in set (0.00 sec)
    mysql> select  time(7320);
    +----------------------+    |  time(7320) |    +----------------------+    |  2 Hours, 2 Minutes, 0 Seconds   |    +----------------------+
    1 row in set (0.00 sec)		mysql> select  time(6890);    +----------------------+    |  time(6890) |    +----------------------+    |  1 Hours, 54 Minutes, 50 Seconds |    +----------------------+    	1 row in set (0.00 sec)    mysql> select  time(56890);    +----------------------+    |  time(56890) |    +----------- -----------+    |  15 Hours, 48 Minutes, 10 Seconds|    +---------- ------------+    1 row in set (0.00 sec)	 part 4:a)mysql> CALL proctwo('Bouloucos');mysql> CALL proctwo('Suri');mysql> CALL proctwo('Randi');mysql> CALL proctwo('kroon');b)mysql> CALL procgen('F');+----------+| count(*) |+----------+|   120051 |+----------+1 row in set (0.10 sec)mysql> CALL procgen('M');+----------+| count(*) |+----------+|   179973 |+----------+1 row in set (0.11 sec)c)mysql> CALL procavg('d001');+-------------+| avg(salary) |+-------------+|  71913.2000 |+-------------+1 row in set (2.77 sec)Query OK, 0 rows affected (2.78 sec)mysql> CALL procavg('d005');+-------------+| avg(salary) |+-------------+|  59478.9012 |+-------------+1 row in set (3.11 sec)Query OK, 0 rows affected (3.11 sec)mysql> CALL procavg('d008');+-------------+| avg(salary) |+-------------+|  59665.1817 |+-------------+1 row in set (3.10 sec)Query OK, 0 rows affected (3.11 sec)

	