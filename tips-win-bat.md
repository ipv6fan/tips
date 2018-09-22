# tips

### date and time
```bat
set yyyymmdd=%DATE:~0,4%%DATE:~5,2%%DATE:~8,2%
set hhmmss=%TIME:~0,2%%TIME:~3,2%%TIME:~6,2%
if "%hhmmss:~0,1%"==" " set hhmmss=0%hhmmss:~1,5%
```
