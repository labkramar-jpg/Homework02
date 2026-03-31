# Linux File Manipulation Commands
## mkdir

```bash
mkdir hw_files
mkdir -p parent/child

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
## touch
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


## head

```bash
head file1.txt
```
Output:
```text
line 1
line 2
```


```bash
head -n 1 file1.txt
```
Output:
```text
line 1
```

## tail

```bash
tail file1.txt
```
Output:
```text
line 1
line 2
```


```bash
tail -n 1 file1.txt
```
Output:
```text
line 2
```

```bash
tail -f file1.txt
```


## ls

```bash
ls
ls -lh
ls -la
ls -l
```
Output:
```text
total 16
drwxrwxr-x 2 eugene eugene 4096 Mar 30 05:39 dir1
drwxrwxr-x 2 eugene eugene 4096 Mar 30 05:39 dir2
-rw-rw-r-- 1 eugene eugene   12 Mar 30 05:02 file1.txt
-rw-rw-r-- 1 eugene eugene    0 Mar 30 04:33 file2.txt
-rw-rw-r-- 1 eugene eugene    0 Mar 30 04:33 notes.md
drwxrwxr-x 3 eugene eugene 4096 Mar 30 05:39 parent
```

## tree

```bash
tree
tree -L 2
```

Output:
```text
├── dir1
├── dir2
├── file1.txt
├── file2.txt
├── notes.md
└── parent
    └── child
```

## less

```bash
less file1.txt
```

Output:
```text


line1
line2
file1.txt (END)
```

## nano

```bash
nano file1.txt
```

## rm

```bash
rm file1.txt
rm -f file2.txt
rm -r dir1
rm -rf dir2
```

## rmdir

```bash
rmdir empty_dir
```
