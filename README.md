

## Commands

### Run API examples

``` bash
uvicorn main:app --reload
uvicorn example.with_database.main:app --reload
uvicorn example.with_tests.main:app --reload
```

### Run API with Docker

``` bash
docker build -t fast-api .
docker run -d --name fast-api-examples -p 8000:80 fast-api
```

### Run Tests

``` bash
pytests

```

### Generate requirements.txt

``` bash
pip install pipreqs
pipreqs example/with_database

```