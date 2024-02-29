# Aula 4 e 5 de Desenvolvimento Web
## Passo a passo na linguagem Markdown

**Passo 1:** Criação de conta e instalação do GitHub Desktop:

* Acesse o site <https://github.com/> e faça login ou crie uma conta
* Acesse o site <https://desktop.github.com/> e faça o Download do GitHub Desktop

**Passo 2:** Criação de um repertório:

* Na página do GitHub entre no icone "repositório" e selecione "novo"
* Nomeie o repositório, adicione uma descrição se necessário e vá em "Criar Repositório"
* Copie o link do seu repositório e selecione "Configurar na área de trabalho"

**Passo 3:** Visual Studio Code:

* Abra o aplicativo do Visual Studio e clique em "File"
* Selecione "Open Folder" e selecione a pasta do seu repositório
* Abra um novo arquivo selecionando "New file", nomeie como "README.md" e adicione conteúdo a ele

**Passo 4:** Alterações no GitHub Desktop:

* Abra o GitHub Desktop
* Adicione um nome e uma descrição e selecione commit

**OBS:** um commit registra alterações em um ou mais arquivos em sua ramificação. O Git atribui a cada commit um ID exclusivo, chamado SHA ou hash, que identifica: as mudanças específicas, quando as mudanças foram feitas e quem criou as mudanças.
* Em seguida, faça o push

**OBS:** O git pushcomando leva dois argumentos: um nome remoto, por exemplo,origin e um nome de filial, por exemplo,main. Você normalmente executa git push origin mainpara enviar as alterações locais ao seu repositório online.

**Passo 5:** Criando uma nova Branch:

* No GitHub Desktop, clique em "branch", depois em "Nova branch" e nomei de acordo com sua vontade
* No Visual Studio CODE abra um novo arquivo para poder testar a branch
* No GitHub Desktop adicione um título uma descrição e dê um "commit"

**Passo 6:** Criando um Main:

* No GitHub Desktop selecione "branch" e substitua por "main" novamente
* No Visual Studio crie um segundo arquivo para teste
* No GitHub Desktop adicione um título uma descrição e dê um "commit"

**OBS.:** Todas as alterações feitas dentro dos arquivos podem ser vistas no GitHub Desktop (Lembre-se de ativar o Auto Save)
*OBS. 2:* Os arquivos criados em "branch" e "main" são diferentes e não poderão ser acessados quando main e branch estiverem selecionados respectivamente.

**Passo 7:** Mesclagem:

* Ainda no GitHub Desktop, clique em branch novamente e selecione "Mesclar no branch atual"

**OBS. 3:** Esse é o jeito do Git de unificar um histórico bifurcado

**OBS. 4:** Caso a mesclagem não funcione você pode dar um "Rebase da ramificação atual"

**Passo 8:** Deletando uma branch:

* No GitHub Desktop selecione a branch que deseja apagar e clique em "deletar".