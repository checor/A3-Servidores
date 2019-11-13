# A3-Servidores

## Pasos para iniciar servidor SSH

1. Actualizar repositorios `apt-get update`
2. Instalar servidor ssh `apt-get install ssh-server`
3. Modificar configuracion en /etc/ssh/sshd_config
4. Iniciar servidor `service ssh start`

## Conexion con cliente

1. Instalar cliente
2. ssh -p <puerto> usuario@host 
