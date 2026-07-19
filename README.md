# Laboratorio de Automatización con Ansible y Docker

## Objetivo de la práctica
El objetivo de este laboratorio es desplegar una infraestructura mínima basada en dos servidores Linux utilizando contenedores Docker y administrar su aprovisionamiento, gestión de archivos y configuración de manera automatizada mediante Playbooks de Ansible.

## Comandos para iniciar los contenedores
Para levantar el entorno de servidores simulados en segundo plano, ejecute:
```bash
docker compose up -d
```

Para verificar que ambos servidores (`server1` y `server2`) se encuentran activos y escuchando de forma óptima:
```bash
docker ps
```

## Comando para Ejecutar el Playbook
Para iniciar el aprovisionamiento automatizado, la creación de estructuras de directorios organizadas mediante bucles (`loops`), generación de reportes con datos del sistema y la validación condicional requerida en el parcial, ejecute la orquestación completa con el siguiente comando:
```bash
ansible-playbook -i inventory.ini playbook.yml
```

## Captura de Pantalla
<img width="1461" height="106" alt="image" src="https://github.com/user-attachments/assets/f010fdfb-410b-424c-b366-662b6af99238" />
