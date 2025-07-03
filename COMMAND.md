## Links Utils
- [Markdown Cheatsheet](https://github.com/lifeparticle/Markdown-Cheatsheet)

- [Git Documentation](https://git-scm.com/docs/git/pt_BR)

## Commands Status

- git-status - Exibe o a condição da árvore de trabalho
```bash
git status
```
## Commands Branch
- git-branch - cria
```bash
git branch dev1
```

- --list
Lista os ramos. Com <padrão>... opcional, por exemplo, git branch --list 'maint-*', lista apenas as ramificações que correspondem ao(s) padrão(ões).
```bash
git branch --list
```

- --show-current
Exiba o nome do ramo atual. Na condição onde HEAD esteja desanexado, nada é impresso.
```bash
git branch --show-current
```

- git-checkout - Alterne entre os ramos ou restaure os arquivos da árvore de trabalho
```bash
git checkout dev1
git switch dev2
```

- Com uma opção -m ou -M, <ramo-antigo> será renomeado para <novo-ramo>. Caso o <ramo-antigo> tenha um "reflog" correspondente, ele será renomeado para corresponder ao <novo-ramo>, e uma entrada no "reflog" será criada para lembrar a renomeação do ramo. Se o <novo-ramo> já existir, a opção -M deverá ser usada para impor a renomeação.
- 
```bash
git branch -M <novo-ramo>
```