2.1.2 Linux
Em qualquer sistema Linux, pode-se utilizar o gerenciador de pacotes da
respectiva distribuição para instalar o Git. Basta executar o código de instalação
de sua respectiva distribuição.
Debian
Em uma sessão de terminal Linux de distribuições Debian (Ubuntu, Mint),
execute o código abaixo. Adicione o ppa para obter a versão mais recente do
Git.
sudo add-apt-repository ppa:git-core/ppa
sudo apt-get update
Agora, execute o comando abaixo para instalação do Git. Siga as instruções
do prompt de comando, primeiro confirmando a instalação dos pacotes e suas
dependências, depois confirmando a instalação do pacote git-core.
sudo apt-get install git git-core git-man git-gui git-doc \
ssh openssh-server openssh-client
git --version
Para adicionar ferramentas complementares, execute:
sudo apt-get install gitk mel