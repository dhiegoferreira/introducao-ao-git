# introducaoaogit 💻
Este é um repositório de anotações sobre como utilizar o git.

### Iniciando o Git e criando um commit

#### Comandos:
- $ git init  : cria-se um repositório na pasta selecionada para o arquivos que se quer monitorar 
- $ ls -a (exibe arquivos ocultos)
- $ git add arquivos.extensão : adiciona  os arquivos que se deseja monitorar
- $ git  commit -m “nome para o commit”  ex: Initial project version”
- $ git config --global user.email “dhiegoferreira31415@gmail.com”
- $ git config --global user.name ![areas](https://user-images.githubusercontent.com/53379935/148708168-f857c1ab-98b9-4042-8526-74ed280ce28c.png)

- $ git add * (adiciona todos os arquivos do diretório selecionado)

### Entendendo o ciclo de vida do git
![lifecycle](https://user-images.githubusercontent.com/53379935/148708134-5059753d-9dcb-41cb-869d-30c5a544b3fc.png)


![areas](https://user-images.githubusercontent.com/53379935/148708169-90f245c9-c1a3-43af-89f0-0f2e28b16a17.png)

  -$ git add arquivo.extensao : adiciona o arquivo para STAGED(área de preparo). O arquivo não rastreado (Untracked) passa a ser rastreado. (Pronto para o commit).
  -$ git add* : adiciona todos os arquivos do diretório para Staged. Os arquivos não rastreados (Untrackeds) passam a ser rastreados e prontos para commitar.
  -$ git commit -m "nome da alteração referente a esse commit"
  
 !Agora os arquivos irão para o estado de *Unmodified*, pois agora eles estão sendo monitorados pelo git e a partir daí qualquer modificação irá alterrar o estado deles para *Modified*
 
 
 ### Apontando o respositório criado para o GitHub
 - 1. Criar respositório no GitHub -> new
 - 2. Colocar o nome do repositório
 - 3. Pegar o link https do repositório git

*  $ **git remote add** origin "endereço htpps criado pelo gitgub do repositório
*  $ **git remote -v** : retorna a lista de repositório cadastrados
*  $ **git push origin master** : Envia o repositório local para o repositório no GitHub.
  
