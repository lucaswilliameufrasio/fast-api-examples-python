

## Commands

### Run API examples

``` bash
uvicorn main:app --reload
uvicorn example.with_database.main:app --reload
uvicorn example.with_tests.main:app --reload
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