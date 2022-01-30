# introducaoaogit 💻
Este é um repositório de anotações sobre como utilizar o git.

### Iniciando o Git e criando um commit

### References: https://git-scm.com/book/pt-br/v2

### Comando iniciais:


|           Comandos                                     |       Explicação        | 
|           :---:                                        |---------------------------------------------------------------------------------------|
| `git config --global user.email “seuemail@email.com” ` | configuração do seu **email** que será exibido em seus commits                                                                           |
| `git config --global user.name `                       | configuração do seu **nome** que será exibido em seus commits                                                                                      |
| `git init   `                                          |    cria-se um repositório na pasta selecionada para o arquivos que se quer monitorar  |
| `ls -la`                                                |   exibe todos os  arquivos do diretório selecionado (incluindo os ocultos)             |
| `git add arquivos.extensão`                            |   adiciona um **único** arquivo para STAGED(área de preparo). O arquivo não rastreado (Untracked) passa a ser rastreado                                |
| `git add .`                                            | adiciona **todos** os arquivos do diretório para Staged. Os arquivos não rastreados (Untrackeds)passam a ser rastreados.                                   |
| `git  commit -m “descrição do commit” `                 |ex: "Atualização da classe x”                                                           |



### Entendendo o ciclo de vida do git
![lifecycle](https://user-images.githubusercontent.com/53379935/148708134-5059753d-9dcb-41cb-869d-30c5a544b3fc.png)


![areas](https://user-images.githubusercontent.com/53379935/148708169-90f245c9-c1a3-43af-89f0-0f2e28b16a17.png)
  

 > Depois de adicionados, os arquivos irão para o estado de *Unmodified*, pois agora eles estão sendo monitorados pelo git e a partir daí qualquer modificação irá alterar o estado deles para *Modified*, sendo necessária um novo commit.
 
 
 ### Apontando o respositório criado para o GitHub
 1. Criar respositório no GitHub -> new
 2. Colocar o nome do repositório
 3. Pegar o link HTTPS do repositório no git
 4. **git remote add** origin (endereço htpps criado pelo GitHub do repositório)
 6. **git push origin master** : Envia o repositório local para o repositório no GitHub.
  
