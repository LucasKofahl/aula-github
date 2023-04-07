ORDEM/"REGRAS" DO GIT

Iniciar - git init 
  PS:dentro da pasta do projeto, vai ter uma pasta .git invisivel

  REVER "como configurar o git"



Git add (file) ou . (ponto) - colocar o arquvo selecionado para o status de stage ou todos os aquivos modificados (quando usado o ponto (.))

Git commit -m ("nome do commit" entre aspas) - faz commit dos arquivos no stage

Git status - mostra o stado dos arquvos, se estão em work progress ou em stage

Git log - mostra todos o commits feitos

HEAD - indico no log qual o ultimo commit feito, o commit que vc parou/fez

Git diff - mostra quais foram as alterações feitas linha a linha

Git restore (file) ou . (ponto) - reverte todas as modificações feitas no arquivo ou arquivos 

Git restore --staged (file) ou . - Voltando do Stage

Git reset --soft HEAD~1 - tira o ultimo commit feito

Git rm -r --cached - para resetar o cache do git, em casos de tirar um arquivo do ignore e fazer push

git ignore - seria como uma pasta, que tudo que esta lá dentro, sera ignorado e não será enviado para o github (até vai, mas seria como uma lista de arquivos ignorados, não sendo possível ver seu código ou no caso de pastas o que tem desntro delas)

Gitkeep
