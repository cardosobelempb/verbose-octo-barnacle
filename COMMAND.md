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
- git checkout -b <novo-ramo>
Crie uma nova ramificação chamada <-novo-ramo>, inicie-a em <ponto-de-partida>; e verifique o ramo criado; para obter mais detalhes consulte git-branch[1].
```bash
git checkout -b dev4
```