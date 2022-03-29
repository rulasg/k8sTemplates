# K8s Templates

## Alias

## k config

``` bash
alias kk=kubectl
```

## Prompt to show namespace

 ``` bash
 kubectl config view --minify --output 'jsonpath={..namespace}';echo
 ```

 ```bash
\[\033[01;33m\]\u\[\033[00m:\[\033[38;5;166m\]\w\[\033[0;32m\]$(parse_git_branch)\[\033[00m\]$
 ```
