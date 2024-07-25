estados dos arquivos rastreados pelo GIT:
- Untracked : Arquivos que acabaram de ser criados, não rastreados
- Unmodified (Tracked): Arquivo não alterado
- Modified (Tracked): Arquivo alterado
- Staged (Tracked): Arquivos preparados subir

Ambientes do GIT: 
- Repositório remoto(Servidor), Geralmente no GITHUB
- Área de trabalho (Ambiente de Desenvolvimento), diretorio onde esta sendo trabalhado o codigo
- Área de Staging (Ambiente de Desenvolvimento), área onde antecessora ao commit onde os arquivos estão sendo preparados
- Repositorio local (Ambiente de Desenvolvimento), área onde os arquivos commitados estão sendo preparados para envio ao repositório remoto

Modificações de estado do GIT:
- Usando o comando 'git add' apos criar um arquivo novo: Untracked -> Staged / Área de trabalho -> Área de Staging
- Arquivo foi alterado : Unmodified -> Modified
- Usando o comando 'git add' em arquivo modificado : Modified -> Modified
- Arquivo não foi modificado e foui removido : Unmodified -> Untracked
- Arquivo foi commitado : Staged -> Unmodified / Repositorio local -> Área de Staging

[git-commands](https://github.com/IvanilsoDaSilva/git-commands) 