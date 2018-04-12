esse é um conjunto de scripts que configura uma vps para tunelamento ssh ,alguns dos scritps foram criados por min e alguns copiados de outros otimos scripts ja existentes.

nesse pacote de scripts será instalado a squid,configurado o ssh com hosts e permissoes de acesso via aplicativos de vpn! tambem será instalado varias ferramentas adicionais para facilitar a vida de quem é adm de vps para tunelamento.

eu modifiquei para uso proprio em meu dia a dia porem quem quiser pode usar os scripts gratuitamente em suas vps!

tudo foi testado em UBUNTU e DEBIAN, outros sistemas nao garanto compatibilidade.

<a href="https://github.com/extremetips/INSTALADOR-VPS-UBUNTU-DEBIAN/blob/master/Capturar.PNG" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="500" data-original-width="511" src="https://github.com/extremetips/INSTALADOR-VPS-UBUNTU-DEBIAN/blob/master/Capturar.PNG" /></a></div>
<br /></div>

# instalaçao
no terminal copie ou digite comandos abaixo!

<div dir="ltr" style="text-align: left;" trbidi="on">
<span style="background-color: black;"><span style="color: #eeeeee;">wget https://raw.githubusercontent.com/extremetips/net-free/master/vps &amp;&amp; bash vps</span></span></div>

apos instalação digite " menu "

compativel com UBUNTU e DEBIAN

#ATUALIZAÇÕES FEITAS

05/04/18 adicionado menu de acesso rapido a funçoes basicas.

10/04/18 adicionado vnstat,nethogs,nload,htop, speedtest

11/04/18 adicionado OPENVPN multi-login! permite multiplas conexoes usando apenas 1 certificado

11/04/18 OBS: na opção 20 do menu referente ao openvpn, é bom salientar que na primeira vez que voce acessar ele ,será feito a instalação do openvpn primeiro antes de acessar o menu de crição de certificados de usuarios! nas proximas vezes que voce acessar a opção 20 ai ja irá pular direto para o menu openvpn

12/04/18 adicionado ferramenta backup de usuarios e senha do servidor! ferramenta tambem faz backup da base de dados do limitador de conexoes simultaneas " sshkill". opçao 21 do menu!

