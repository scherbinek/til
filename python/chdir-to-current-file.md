# Change working directory to current path of python file

When starting e python script from VSCode then it is mostyl startet from root. But most references are from it python file.

Therefore it helps to switch the working directory explicitly to its python file which is executed.

```python
import os
# change working directory to the location of this file
os.chdir(os.path.dirname(os.path.abspath(__file__)))
```
