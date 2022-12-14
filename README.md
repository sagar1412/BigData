

## Open HBase terminal and execute the codes below

### General Shell Commands
 - To enable HBase shell
```
hbase shell
```
 - Check HBase status
 ```
 status
 ```
 - Check HBase version
 ```
 version
 ```
 - Check HBase user
 ```
 whoami
 ```
- Create a new table
```
create 'table1', 'tablerow', 'tablecol'
```
- Insert values into the table
```
put 'table1', 'tablerow', 'tablecol', 10
put 'table1', 'tablerow', 'tablecol', 15
```
- Drop table
```
disable 'table1'
drop 'table1'
```
