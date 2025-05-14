# maquina_virtual_Azure

Primeiramente, acesse a sua conta Azure, posteriormente busque por Máquina vitual na barra de pesquisa e selecione.Ao acessar, caso não tenha alguma, vai aparecer um botaão criar bem visível no meio da tela.

Passos em ordem:

1. Acessar sua conta Azure.
2. Conferir se está no diretório certo.
3. Pesquisar por Máquina virtual
4. Selecionar
5. Apertar em criar

Ao executar esses passos, será aberta algumas seleções, fica a seu critério se deseja configurar uma do zero ou pegar configurações já predefinidas. No meu caso, vou tentar configurar uma.

Agora vamos para o preenchimento das informações:

1. Se ela tiver um pacote de recursos, pode selecionar, no meu caso eu não contenho.
2. Coloque um nome com cuidado no uso de espaços e caracteres não aceitos.
3. Escolha sua zona e região.
   Lembrando!! Região é onde fica uma sede de DataCenter, zonas são conjuntos(geralmente 3) de datacenters dentro de uma região
4. Escolha a quantidade de zonas
5. Escolha a imagem, no meu caso vou escolher o windows server 2022.

Possíveis dúvidas: O que é o estado de hibernação de uma máquina vitural? Segundo o google, é quando você persiste o estado da VM para o disco de software.

# IMPORTANTE

Ao escolher o nome de usuário e a senha, salve com atenção para que não haja problemas de esquecimento depois!!

Por último, escolha as portas de entrada, no meu caso, optei por HTTP(80), RDP (3389).

Como ainda não sei alterar bem nas outras abas, optei por deixar as respostas padrões!!

Aperte em revisar + criar, ao fim, em criar. Espere um tempinho para conferir se ocorreu tudo bem na sua implantação. Vai aparecer, quando estiver concluído "Ver recursos", selecione essa opção para que possamos ir aos últimos passos:

# Acessando a Máquina Virtual

1. Selecione Conectar, posteriormente conectar mais uma vez.
2. Baixar o arquivo rdp
3. Selecione ele e aperte conectar
4. Ao fazer isso vai abrir uma caixinha que deves confirmar e depois vai colocar sua senha.

   Fácil!! Agora acessamos a nossa primeira máquina virtual.
