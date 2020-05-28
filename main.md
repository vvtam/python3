MainFunction.py

```PYTHON
def main():
    print("hello world!")

if __name__ == "__main__":
    main()

print("Guru99")

print("Value in built variable name is:  ",__name__)
```

output

```
hello world!
Guru99
Value in built variable name is:   __main__
```



PythonImport.py

```python
import MainFunction

print("done")
```

output

```
Guru99
Value in built variable name is:   MainFunction
done
```



直接运行MainFunction.py

`__name__=__main__` if为true，main会运行

import后运行，PythonImport.py

`__name__=模块名字，文件名`

