# Loophole tutorial

2023/02 - leonardopellizzon

## Command

scaricare .tar.gz:
```
sudo wget https://github.com/loophole/cli/releases/download/1.0.0-beta.15/loophole-cli_1.0.0-beta.15_linux_arm64.tar.gz
```

estrarre la cartella:
```
tar -xf loophole-cli_1.0.0-beta.15_linux_arm64.tar.gz
```

entrare nella cartella:
```
cd loophole-cli_1.0.0-beta.15_linux_arm64/
```

spostare il file in /usr/local/bin:
```
sudo mv loophole /usr/local/bin
```

torna indietro:
```
cd ../..
```

entra nella cartella /usr/lacal/bin:
```
cd /usr/local/bin/
```

dai i permessi:
```
chmod +x loophole
```

torna indietro:
```
cd ~
```

modifica il file bashrc:
```
sudo nano .bashrc
```

incolla alla fine il seguente testo e premi ^X e Y per uscire e salvare:
```
export PATH=$PATH:/urs/local/bin/loophole
```

inizia ad usare loophole:
```
loophole http [porta] --hostname [dominio]
```
