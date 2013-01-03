ranking-shell-history
=======================

Show ranking for shell(bash/zsh) commands.

Usage
-----------------------

```console
ranking_shell_history [-h] [-n N] [--max-arg-num MAX_ARG_NUM]
                                  [--min-count MIN_COUNT] [--shell {zsh,bash}]
                                  [--version]
                                  [bash|zsh|your history file]
```


zsh

```cosole
$ ranking_shell_history
Read /Users/yonchu/.zsh_history
----------------------------------------
git: 1138
  diff: 140
  add: 129
  log: 62
  status: 62
  remote: 52
  rev-parse: 52
  rm: 46
  e: 41
  submodule: 39
  reset: 39
  mv: 30
  config: 26
  c: 24
  clone: 23
  checkout: 20
  commit: 17
  rev-list: 16
  edit: 16
  ed: 14
  show: 13
  chh: 13
  rebase: 13
  tag: 13
  push: 13
  branch: 12
  help: 11
cd: 1021
vi: 918
echo: 413
  '(up: 32
  "166": 26
  '~/aaa': 13
  $PYTHONPATH: 10
grep: 355
  -r: 28
  -R: 24
  'grep': 13
  'find': 11
mv: 328
brew: 318
  info: 71
  search: 61
  install: 35
  list: 19
  edit: 12
  options: 12
ll: 307
ls: 250
  -la: 23
  -d: 12
rm: 195
  -rf: 51
```

bash

```console
$ ranking_shell_history
Read /Users/yonchu/.bash_history
----------------------------------------
vi: 59
  color256_bash.sh: 23
ll: 55
cd: 42
ls: 40
echo: 25
./color256_bash.sh: 22
brew: 22
bash: 13
env: 11
./color256: 10
```
