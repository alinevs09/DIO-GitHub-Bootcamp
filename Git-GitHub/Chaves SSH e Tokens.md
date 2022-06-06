# Chaves SSH e Tokens 🔐

As Chave SSH são uma forma de conceber uma conexão segura e encriptada entre duas máquinas. Uma chave pública (da nossa máquina) e uma chave privada. No site do Github, nas configurações é possível ir na opção SSH Keys e gerar uma chave.

Iremos usar o Git Bash para gerar as chaves, no terminal Git Bash digitar o comando:</br>

<b>ssh-keygen –t ed25519 –c <i>*alinevs@gmail.com*</i></b> (No lugar do meu email você colocará o seu, que usou para fazer o cadastro no GitHub).</br>
Ele mostrará o local onde ficarão as chaves na máquina (as pastas ocultas).</br>
Clique Enter novamente, ele irá pedir a senha do GitHub, coloque a senha e clique Enter novamente.</br>
Digite **Cd /c/users/aline/.ssh/** (Enter)</br>
**ls** (Enter)</br>
Ele vai mostrar o código da chave pública e da chave privada, é bom anotar esses códigos em algum lugar próximo.</br>
Digitar: **Cat (colocar a chave pública).pub** (Enter)</br>
Ele vai mostrar a chave pública completa, copiar tudo e será esse código que será usado no Github.</br>
No Github em SSH Keys, colocar no título: minha máquina, e em key: colar esse código gerado no terminal.</br>
Voltar no Git Bash e digitar:</br>
**Ls** (Enter)</br>
**Pwd** (Enter)</br>
**Eval $(ssh-agent –s)** (Enter)</br>
Agora irá mostrar um número agente pid.</br>
Digite **ls** (Enter)</br>
**Ssh-add (digitar o código da chave privada)** (Enter)</br>
Digitar senha (Enter)</br>
No Github vai clonar um repositório.</br>
Na parte de cima da página ao lado direito tem um botão verde chamado **<>Code**, clicando nele aparecem algumas opções de endereços, clique em SSH e copie o código gerado.</br>
Volte no terminal bash, digite **git clone (cole o código aqui)** (Enter)</br>
Escolha **Yes** (Enter)</br>
Digite **Ls** (Enter)</br>
Aparece um endereço github e está pronto.</br>

