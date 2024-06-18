# FastAPI

### Installing FastAPI & Uvicorn
$ `pip install fastapi` <br>
$ `pip install 'uvicorn[standard]'`

### Running API
$ `uvicorn main:app --reload` -> main is the filename

### FastAPI request types
- GET => Get gome data
- POST => Create some data
- UPDATE => Update data
- DELETE => Delete data

### Sample API Code
```
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def root():
    return { "hello": "nayan" }
```
- hello => key
- nayan => value
- get => GET (FastAPI Request type)

