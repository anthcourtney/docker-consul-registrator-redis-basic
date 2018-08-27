# docker-consul-registrator-redis-basic

This repository contains a basic docker-compose based environment which tests the registration of redis with consul using registrator.

# Basic Usage

```
$ docker-compose up -d && docker-compose logs test
```

If successful, this should result in output similar to the following:

```
# docker-compose logs test
Attaching to docker-consul-registrator-basic_test_1
test_1         | ============================= test session starts ==============================
test_1         | platform linux2 -- Python 2.7.14, pytest-3.7.3, py-1.5.4, pluggy-0.7.1
test_1         | rootdir: /tmp, inifile:
test_1         | collected 2 items
test_1         | 
test_1         | tmp/test_consul.py ..                                                    [100%]
test_1         | 
test_1         | =========================== 2 passed in 0.31 seconds ===========================

```
