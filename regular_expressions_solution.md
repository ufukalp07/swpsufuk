**Exercise 1**
```bash
ls ~/ | grep '^[A-Z]'
```
**Exercise 2**
```bash
ls -a ~/ | grep '^\.'
```
**Exercise 3**
```bash
ls -a ~/ | grep '^\.' | wc -l
```
**Exercise 4**
```bash
ls ~/ | grep '^[a-zA-Z]*$'
```
**Exercise 5**
```bash
ls ~/ | grep '^[^A-Z]*$'
```
**Exercise 6**
```bash
ls ~/ | grep -v '\.[a-zA-Z]\{3\}$'
```
**Exercise 7**
```bash
ls /etc | grep '^c.*y$'
```
**Exercise 8**
```bash
ls /etc | grep 'ss'
```
**Exercise 9**
```bash
ls ~/ | grep '^.\{1\}[A-Z].\{1\}[A-Z].e$'
```
**Exercise 10**
```bash
ls ~/ | grep '^[a-zA-Z0-9]\{4\}$'
```
**Exercise 11**
```bash
ls /var/log | grep '\.log$'
```
