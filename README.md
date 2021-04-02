# Test-Repro
… image

As per https://docs.docker.com/engine/reference/builder/#copy,

```
All new files and directories are created with a UID and GID of 0, unless the optional --chown flag specifies a given username, groupname, or UID/GID combination to request specific ownership of the copied content
```

so a user should ensure that the default user `jenkins` owns the copied files.
