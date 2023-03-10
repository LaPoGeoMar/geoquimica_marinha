# Aulas práticas de Geoquímica

| Platform        | Status                                                                                                                                                                                 |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Linux, macOS, and Windows | [![Tests](https://github.com/juoceano/geoquimica_marinha/actions/workflows/tests.yml/badge.svg)](https://github.com/juoceano/geoquimica_marinha/actions/workflows/tests.yml) |

## Instalação

1. Faça download do *miniconda* com o Python 3 escolhendo a sua plataforma: Linux, macOS ou Windows
   https://docs.conda.io/en/latest/miniconda.html;

![Passo1.png](images/01-miniconda-web-page.png?raw=true)

2. No Windows, clique no arquivo baixado (`Miniconda3-latest-Windows-x86_64.exe`) e    
   siga as instruções na tela ou veja [esse passo a passo](step-by-step-windows.md).
   Não é recomendado instalar para todos os usuário nem colocar o Python do *miniconda* como padrão;

   Para macOS ou Linux abra um **terminal** e, no **diretório** onde foi baixado o *miniconda*,
   execute ``sh Miniconda3-latest-Linux-x86_64.sh`` e siga o [passo a passo](step-by-step-nix.md).


3. Agora você deve fechar e reabrir o terminal.
   Caso tenha dificuldade no terminal recomendamos os [tutoriais 1-3](https://swcarpentry.github.io/shell-novice) do Software Carpentry sobre o shell (terminal).

4. Instale o ``git`` e faça o "clone" do repositório das aulas com

```shell
conda install git
git clone https://github.com/juoceano/geoquimica_marinha.git
```

Essa etapa deve ser feita dentro do diretório onde você queira salvar esse material e que será seu diretório de trabalho futuramente.
Cabe a cada um organizar seus arquivos da melhor forma que achar adequado.
Mas lembrem ondem salvaram o clone das aulas!!!

5. O próximo passo é entrar no diretório e criar o ambiente de aula:

```shell
cd geoquimica_marinha
conda env create --file environment.yml
```

6. Depois do download e instalação dos pacotes do ambiente de aula ative o ambiente com:

```shell
conda activate AULA_GEOCHEM
```

Observe que acima do prompt de comando irá aparecer **(AULA_GEOCHEM)**, mostrando que o mesmo está ativo.

![](images/06-miniconda-env.png?raw=true)



Quem quiser ler mais sobre o ``conda`` e gerenciamento de ambientes recomendamos
[essa lição do Software Carpentry](https://carpentries-incubator.github.io/introduction-to-conda-for-data-scientists/01-getting-started-with-conda/index.html)
sobre o tópico.