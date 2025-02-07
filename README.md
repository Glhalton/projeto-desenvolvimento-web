# Projeto Desenvolvimento Web

## Para adicionar o repositório na sua máquina, exetuce os determinados códigos no terminal:
* Adicione o repositório na sua máquina

`git remote add origin https://github.com/Engenharia-de-Software-da-UEPA/projeto-desenvolvimento-web.git`

## Antes de começar a codar, siga estes passos para atualizar seu repositório

`git status`: Verifica se há alguma alteração no seu repositório local.

`git add nome-do-arquivo || git add .`: estes comandos adicionam os arquivos selecionados para a area de stage (commit). o comando que possui `.` adiciona todos os arquivos modificados para a área de stage (commit).

`git pull origin main`: este comando é para baixar e mesclar as alterações do repositório remoto para o seu repositório local. Se houver conflitos entre as alterações locais e as atualizações do repositório remoto, você precisará resolvê-los manualmente. O Git irá avisá-lo sobre esses conflitos durante o processo de mesclagem.

`git status`: Após a atualização, é uma boa prática verificar o status do seu repositório novamente para garantir que tudo esteja atualizado e em ordem.

`git add .` e `git commit -m "Mensagem do commit"`: Finalize e envie suas alterações (se necessário): Se você fez alterações locais e resolveu quaisquer conflitos, adicione e comite essas alterações novamente.

`git push origin main`: Envie suas alterações para o repositório remoto (opcional): Se você deseja enviar suas alterações locais para o repositório remoto, use o comando git push. 