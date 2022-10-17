# rakugaki
Repository for record of library trial, study, WIP, and others. Most in the repository is incomplete.

## Reference for me
- [Git submodule](https://www.m3tech.blog/entry/git-submodule)

- Submodule add
```shell
git submodule add "ssh://gitlab.example.com/myonyomu/rakugaki-hogehoge-fugafuga.git
```

- Submodule update
```shell
cd rakugaki-xxx
git pull <remote> <branch>
git checkout <branch>
cd ../
git submodule update --recursive
```
