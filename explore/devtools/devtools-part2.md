1. The issue is that document.getElementbyID is a string, and not a number. So we were adding strings
2. I would fix it by typecasting. 
![Fix](../../expand/screenshots/fix.png)