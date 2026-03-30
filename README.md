# Linux File Manipulation Commands
## mkdir

```bash
mkdir hw_files

ls
```
Output:
```text
Desktop    Downloads  Music     Public     Videos
Documents  hw_files   Pictures  Templates
```


## cd and pwd

```bash
cd hw_files
pwd
```

Output:
```text
/home/eugene/hw_files
```

---


```bash
touch file1.txt
touch file2.txt notes.md
ls
```

Output:
```text
file1.txt  file2.txt  notes.md
```

## cat

```bash
echo "line 1" > file1.txt
echo "line 2" >> file1.txt
cat file1.txt
```
Output:
```text
line 1
line 2
```

```bash
cat -n file1.txt
```

Output:
```text
1  line1
2  line2
```
