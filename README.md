# neurolab-hbase

![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png)

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
