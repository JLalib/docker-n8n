# 🚀 n8n - Workflow Automation Tool

![173571060-9f2f6d7b-bac0-43b6-bdb2-001da9694058](https://github.com/user-attachments/assets/09821573-f5e1-446d-b7d9-5292c6d48750)  

Este repositorio contiene la configuración de **n8n**, una herramienta de automatización de flujos de trabajo de código abierto.  
Además de la guía de instalación con **Docker** y **Docker Compose**, aquí encontrarás **flujos listos para usar** que puedes descargar, importar y explorar directamente en tu instancia de n8n.  

👉 **Te invitamos a descargar y probar los flujos incluidos en este repositorio para inspirar tus propias automatizaciones.**  

---

## 📦 Instalación rápida con Docker  

```bash
docker volume create n8n_data

docker run -it --rm --name n8n -p 5678:5678   -v n8n_data:/home/node/.n8n   docker.n8n.io/n8nio/n8n
```

---

## ⚙️ Instalación con Docker Compose  

1. Crea el archivo `docker-compose.yml` con la configuración deseada.  
2. Inicia el contenedor:  

```bash
docker compose up -d
```

---

## 🔄 Clonando este repositorio  

```bash
git clone https://github.com/JLalib/docker-n8n.git n8n
cd n8n
docker compose up -d
```

---

## 🎬 Vídeo tutorial en YouTube  

Mira la guía en video para entender cómo configurar y usar n8n:  
➡️ [Ver tutorial en YouTube](https://youtu.be/QlZ8ox77MoM)  

---

## 📂 Flujos incluidos  

En este repositorio encontrarás una carpeta con **workflows preconfigurados** listos para importar a tu instancia de n8n.  
Solo necesitas:  

1. Descargar el archivo `.json` del flujo.  
2. Importarlo desde la interfaz de n8n.  
3. ¡Explorar, modificar y automatizar!  

---

![n8n-screenshot](https://github.com/user-attachments/assets/1c6932c2-33c9-47c2-b380-59f9be1b2b5d)  
