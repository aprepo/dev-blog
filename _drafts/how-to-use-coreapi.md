# How to use coreapi?

[coreapi](http://www.coreapi.org/) is nifty little library for interacting with REST APIs. However, it is seriously lacking documentation. Making notes while learning.

## Version of coreapi
At the time of writing the coreapi is at version 2.3.3

## Authentication
```python
import coreapi
from coreapi.auth import BasicAuthentication

client = coreapi.Client(auth=BasicAuthentication(username='johdoe', password='seCReTWodr!'))
```


