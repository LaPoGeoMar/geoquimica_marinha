a) do diretório onde baixou o *miniconda* digite ``sh Miniconda3-latest-Linux-x86_64.sh``;

![](images/02-miniconda-install.png?raw=true)

b) para revisar a licença **ENTER** até passar todo o texto,
   e quando perguntado para aceitá-la digite **yes** e **ENTER** novamente;

c) quando perguntado sobre o diretório da instalação aperte **ENTER** para aceitar o padrão;

![](images/03-miniconda-license-directory.png?raw=true)


d) a última pergunta é para executar o ``conda init``, escolha **yes** e pronto!

![](images/04-miniconda-init.png?raw=true)

Pode ser necessário fechar o terminal e abrir novamente.
Para confirmar se o ``conda`` está corretamente instalado digite:

```shell
which conda
```

você dever ver algo assim,

![](images/05-miniconda-which.png?raw=true)


Se você usa muito o terminal e não quer o ambiente ``base`` ativado o tempo todo você pode executar:

```shell
conda config --set auto_activate_base false
```


Caso tenha dificuldade no terminal recomendamos os [tutoriais 1-3](https://swcarpentry.github.io/shell-novice) do Software Carpentry sobre o shell (terminal).