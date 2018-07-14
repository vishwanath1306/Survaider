# Survidar:

Developed a full stack application on Flask framework that runs default on the **port: 8025**

Dataset used: http://archive.ics.uci.edu/ml/datasets/Adult

Database: sqlite

![](https://i.imgur.com/sww8r9d.png)
![](https://i.imgur.com/yqoPSCw.png)
![](https://i.imgur.com/1WBQkhK.png)
![](https://i.imgur.com/MkQsYgf.png)

### To Fetch all records from the database:

**Total Row: 32561**

**Total Column: 15**

For example I am running the example with first 30 records according to the filter condition. It takes some time when I try to fetch 32561 rows. If you want to fetch all the 32561 rows from the database , remove the filter condition break statement in query_all() and query_filter() function from Adult class.


![](https://i.imgur.com/zYwGexD.png)
![](https://i.imgur.com/qAH0tqV.png)

### Requirements:

```python
SQLAlchemy==1.2.8
Flask==1.0.2
```

### Install Requirements:

```python
pip install -r setup/requirements.txt
```



