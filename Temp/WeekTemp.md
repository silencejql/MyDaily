```dataview
table 项目号, 项目名称, 工作内容
from "MyDaily/Daily"
where file.ctime >= date(today) - dur(7 days)
sort file.ctime desc
```
