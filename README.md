### Unlock Bootloader
##### Scripts para desbloquear el bootloader en dispositivos xiaomi motorola y huawei uselo con cuidado sepa lo que hace esto es para desarroladores a futuro puede que agregue mas marcas de dispositivos 

### Dependencias 

```shell
sudo yay -S adb
```

### Ejecutar script de xiaomi y poco 
```shell
sudo python3 xiaomi.py
```
### Ejecutar script de motorola
```shell
sudo bash motorola.sh
```
### Ejecutar script de huawei
##### tienes que compilar `huawei.c`
##### ejecute este comando `gcc huawei.c -o exec`
##### despues que compile se creara un archivo `exec` ese archivo lo ejecutaras de esta manera

```shell
./exec
```
##### Inicia sesion con tu cuenta mi en el script de xiaomi y poco. Para motorola se necesita el codigo y en huawei no necesitaras de codigos porque huawei cerro la pagina donde daban el codigo y no elimine los archivos y carpetas que se generan en la carpeta donde tienes los scripts. 
