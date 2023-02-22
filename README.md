# Instalador de Press-Ticket en Modo Localhost sin SSL

### Descarga y Instalar

En primer lugar, debe descargarlo:


```bash
sudo apt -y update && apt -y upgrade
sudo apt install -y git
git clone https://github.com/manuprado9/Press-Ticket-Installer.git
```

Ahora, todo lo que tienes que hacer es hacerlo ejecutable:

```bash
sudo chmod +x ./Press-Ticket-Installer/Press-Ticket
```

### Uso

Después de descargarlo y hacerlo ejecutable, debe ir al directorio del instalador y **ejecutar el script** con **SUDO**:

```bash
cd ./Press-Ticket-Installer
```
Antes de Empezar a instalar si quiere pude crear un archivo config y ponga las claves que usted quiera. De no hacerlo se generaran aleatoriamente las claves guardandose en este archivo.

```bash
sudo nano config
```
**Pegue este texto y agregue sus claves**
```bash
deploy_password=
mysql_root_password=
db_pass=
```
Ejecute el instalador.

```bash
sudo ./pressticket
```

* Usuario: 
```bash
admin@pressticket.com.br  
```
* Contraseña: 
```bash
admin
```
