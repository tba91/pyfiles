# pyfiles
management for files with python

## Quickstart
### simple usage:
```
from pyfiles.file import File

file = File('some/file.example')

print(file.path)
-> Path('some/file.example)
```

### permissions:
```
print(file.permission.owner)
-> 'rwx'

print(file.permission.onwer.is_executable)
-> True

print(file.permission.onwer.is_writable)
-> True

print(file.permission.onwer.is_readable)
-> True
```

### content:
```
for line in file.content.read_only():
    print(line)
```



