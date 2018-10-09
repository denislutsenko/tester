### Endpoints description
|  Endpoint  | HTTP methods | 
| ---------- | ------------ |
|/users | POST - register new user |
|/categories | GET, POST|
|/categories/{id} | GET, PUT, DELETE | 
|/test-pools | GET, POST |
|/test-pools/{id} | GET, PUT, DELETE | 
|/test-pools/{id}/test| GET - starts a test and saves it to **/test-pools/{id}/tests** |
|/test-pools/{id}/tests | GET - returns all tests that were generated for a given test-pool |
|/test-pools/{id}/questions | POST |
|/test-pools/{id}/questions/{id} | GET, PUT, DELETE | 
