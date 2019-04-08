# SQL-Experience
The SQL Experience is an assigned project for the Introduction to Database Systems course at the University of Houston. The final project consisted of 3 sub-assignments. Each assignment contained a list of tasks which should be accomplished by using one or a combination of multiple SQL statements.

## What the File is
Each file is separated by the number corresponding to each assignment number. I unfortunately do not have the permission yet to post the assignment questions (but that will explain the few lines that say "-----3"). 
```
SQL> 
SQL> ----3
```

After the assignment number, the actual statement will take up the next few lines 
```
SQL> select stf_name, stf_salary, round(stf_salary - (select avg(stf_salary) from MIS3376.sxsw_staff),0) as "Computed Difference"
  2  from MIS3376.sxsw_staff
  3  order by 1 asc;

```
and at the very end will be the output of the code.
```
STF_NAME                  STF_SALARY Computed Difference
------------------------- ---------- -------------------
Ada Lovelace Z.                 2500                 261
Alan Turing P.                  2500                 261
Charles Babbage L.              2195                 -44
Christine Nguyen H..            1500                -739
Danny Jimenez R.                2000                -239
Dave Mathews L.                 1250                -989
David Ferety U.                 1900                -339
Dee Jones R.                     800               -1439
Donna Murphy C.                 2000                -239
Ginger Murphy                   2650                 411
Jeffery Bezos T.                7500                5261
Julio Montango T.               3400                1161
Larry Johnson G.                2500                 261
Mary Smith K.                   2149                 -90
Mohammed Bang M.                1535                -704
Samual Yu N.                    1260                -979
Thomas Kahn U.                  2050                -189
Tim Cooke M.                    1950                -289
William Gates T.                 900               -1339

19 rows selected. 
```

## Viewing the Code
When you download the file, it will download as a .lst. Right-click the file and depending on your OS, open the file with whatever the basic text editing software is. I highly recommend opening the .lst files using a word processing software such as Microsoft Word or the Mac OS Pages.

## About the Author
My name is Andre DeGuzman. I usually respond to Dre, but if you do happen to call me Andre, I will freak out because I'll think I've done something wrong. At the time of this upload (April 2019), I am a senior at the University of Houston. I am pursuing a BBA degree in Management Information Systems. If you'd like to know more about me or see more of my work, visit my website at [dredeguzman.com](https://www.dredeguzman.com).
