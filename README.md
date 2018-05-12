### Overview

Tiny script to print the next 30 business-days in Japan to stdout. 
Saturdays, Sundays, Holidays print as a blank line.


### Usage

```
docker run -v "$PWD":/usr/src/myapp -w /usr/src/myapp ruby ruby jp-business-day.rb
```


### Demo

```
$ docker run -v "$PWD":/usr/src/myapp -w /usr/src/myapp ruby ruby jp-business-day.rb 10



 5/14日(月)
 5/15日(火)
 5/16日(水)
 5/17日(木)
 5/18日(金)


 5/21日(月)
 5/22日(火)
```