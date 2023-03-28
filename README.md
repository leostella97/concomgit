# Conceitos e Comandos Git

## Conceitos Git
O Git é um sistema de <b>controle de versão distribuído</b>, amplamente utilizado na <i>área de desenvolvimento de software</i>. Ele permite que você <b>acompanhe as alterações</b> em um conjunto de arquivos ao longo do tempo, além de <b>facilitar a colaboração</b> entre membros de uma equipe.

Com o <b>Git</b>, você pode <b>criar um repositório</b> para <i>armazenar</i> seus arquivos de projeto e usar comandos como <b>"commit"</b> e <b>"push"</b> para <i>enviar suas alterações</i> para o repositório. Outros membros da equipe podem então <b>"clonar"</b> o repositório para <i>trabalhar em seus próprios computadores</i> e enviar suas próprias alterações.

O Git também inclui recursos avançados, como a capacidade de criar <b>"ramificações" (branchs de outras branch)</b> para experimentar diferentes abordagens para um problema, <b>sem afetar</b> o código principal. Além disso, ele possui uma ampla gama de ferramentas para ajudá-lo a solucionar problemas e colaborar com sua equipe de maneira eficaz.


## Comandos
<b>• git init:</b> Inicializa um repositório Git em um diretório local.
<br>
<b>• git add nome_do_arquivo:</b> Adiciona um arquivo específico ao índice (staging area) para ser commitado posteriormente.
<br>
<b>• git add . :</b> Adiciona todos os arquivos alterados e novos ao índice (staging area) para serem commitados posteriormente.
<br>
<b>• git commit -m "mensagem de commit":</b> Confirma as alterações feitas no repositório com uma mensagem descritiva.
git status: Mostra o estado atual do repositório e quais arquivos foram modificados ou adicionados.
<br>
<b>• git log:</b> Mostra o histórico de commits realizados no repositório.
<br>
<b>• git branch:</b> Lista todas as ramificações (branches) criadas no repositório.
<br>
<b>• git checkout nome_da_branch:</b> Muda para uma branch específica.
<br>
<b>• git merge nome_da_branch:</b> Combina as alterações de uma branch com a branch atual.
<br>
<b>• git push:</b> Envia as alterações feitas localmente para o repositório remoto.
<br>
<b>• git pull:</b> Atualiza o repositório local com as alterações feitas no repositório remoto.
<br>
<b>• git clone url_do_repositório:</b> Clona um repositório remoto para o seu computador local.