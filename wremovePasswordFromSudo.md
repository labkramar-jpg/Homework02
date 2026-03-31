### 1. Open sudoers file

```bash
sudo visudo
```


### 2. Add line and save changes

```eugene ALL=(ALL) NOPASSWD: ALL```

### 2. Verify that sudo no longer asks for a password

```sudo ls```

```Output:
dir1
dir2
file1.txt
notes.md
parent
```
