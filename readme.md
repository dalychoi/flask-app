test.db가 instance folder에 위치해야 함

## Create SQLite files in instance folder #462
## https://github.com/pallets-eco/flask-sqlalchemy/issues/462

root folder에 있는 test.db가 인식되지 않아서 그냥 돌리면 todo를 찾을 수 없다는 에러 발생
그래서 crdb.py를 새로운 db를 만들어보면 instance folder 밑에 만들어짐
기존의 test.db를 instance folder에 copy해보면 기존 db 내용이 보여짐