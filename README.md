# Linux Commands Practice

A quick reference for basic Linux CLI tasks.

## Commands

```
# 1. Create & rename
mkdir test_dir
touch test_dir/example.txt
mv test_dir/example.txt test_dir/renamed_example.txt

# 2. View file contents
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd

# 3. Search patterns
grep "root" /etc/passwd

# 4. Zip & unzip
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir

# 5. Download file
wget https://finecalorie.com/sample.txt

# 6. Permissions
touch secure.txt
chmod 444 secure.txt

# 7. Environment variable
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```

---
Author: Shantum Sharma
```
