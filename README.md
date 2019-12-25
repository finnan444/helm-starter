# Helm Chart Starter

## Using Helm

For helm3 the starters should be stored in $XDG_DATA_HOME (In Linux $HOME/.local/share/helm). 

```bash
$ git clone https://github.com/finnan444/helm-starter $HOME/.local/share/helm/starters/finnan444
```

## Updates

I update these templates regularly. If you need to fetch the newer version, cd into the directory and run the git pull.

```bash
$ cd $HOME/.local/share/helm/starters/finnan444
$ git pull
```

## Usage

Helm allows the usage of a "template" chart when creating other charts, as follows:

```bash
$ helm create --starter=finnan444/chart NAME
```