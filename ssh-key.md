Schlüsselpaar generieren

´´´shell
ssh-keygen -b 4096
´´´

Öffentl. Schlüssel auf Server übertragen
´´´shell
ssh-copy-id -i ~/.ssh/key.pub <user>@<host>
´´´

Testen
´´´shell
ssh -i .ssh/key <user>@<host>
´´´
