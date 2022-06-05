# Criando um Commit

Aqui coloquei um passo a passo do código para a criação de um commit no Git Bash.

Abra o Explorer em seu computador, no disco C (ou outro de sua preferência, aqui usarei o C como exemplo) crie uma pasta com o nome de trabalho que usará, eu escolhi o nome **workspace**.</br>
Clique com o botão direito do mouse na área do disco C e em **Git Bash here**, ele irá abrir o terminal já dentro da pasta C.</br>
Então no terminal iremos digitar a seguinte sequência de códigos, sempre dando ENTER ao final de cada linha:</br>
**Ls</br>
Cd workspace</br>
Mkdir livro-receitas** (para criar uma pasta dentro, eu dei o nome da pasta de **livro-receitas**, você pode escolher qualquer nome)</br>
**Ls</br>
Cd livro-receitas** (ou o nome da pasta que você colocou)</br>
**Git init</br>
Ls</br>
Ls –a** (para exibir pastas ocultas)</br>
**Cd . git/</br>
Ls</br>
cd ..** (para voltar um nível)</br>
**git config –global user.email alinevs@gmail.com** (substitua o meu email pelo seu email que usou para criar sua conta no GitHub)</br>
**git config –global user.name alinevs09** (substitua o meu nickname alinevs09 pelo o que vc cadastrou quando criou sua conta no GitHub)</br>

Pronto, seu primeiro commit está criado!

