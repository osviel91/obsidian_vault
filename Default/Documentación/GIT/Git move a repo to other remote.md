```
$ git clone --bare https://git.fedorahosted.org/the/path/to/my_repo.git
$ cd my_repo.git
$ git push --mirror https://github.com/my_username/my_repo.git
$ cd ..
$ rm -rf my_repo.git
```