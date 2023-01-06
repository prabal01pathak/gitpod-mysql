# command to start the mysql

docker run --name some-mysql -e MYSQL_ROOT_HOST=% -e MYSQL_ROOT_PASSWORD=my-secret-pw -p 3306:3306 -p 33060:33060  mysql:latest

# run 
```py
python3 app.py
```