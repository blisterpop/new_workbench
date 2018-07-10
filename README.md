#New Workbench

##Preamble
The purpose of this site is to perform an exercise for the Unix Workbench course.

*The date is 7/10/18*

**Here is the code from some random script** 
```
#!/usr/bin/env bash
# File: simpleif.sh

echo "Start program"

if [[ $1 -eq 4 ]]
then
  echo "You entered $1 - that's what I was looking for"
elif [[ $1 -gt 3 ]]
then
  echo "$1 is a great number"
else
  echo "You entered $1, not what I was looking for."
fi

echo "End program"
```


