# X-Village Web Course ToDoList System Homework

輸入待辦事項，若事件完成後可以在左邊的方格打勾，或是點垃圾桶刪除。
點擊兩下是編輯事件功能。

## Heroku
https://x-village-todo-kehsin.herokuapp.com


## Setup

- Run python shell

```sh
python

```

```python
>>> from app import db
>>> db.create_all()
>>> exit()
```

## Usage

### Windows
```sh
set FLASK_APP=app.py
flask run
```

### macOS/Linux
```
export FLASK_APP=app.py
flask run
```



## Authors
[Lee-W](https://github.com/Lee-W/)

## License
[MIT](https://opensource.org/licenses/MIT)
