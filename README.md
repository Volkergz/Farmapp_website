
# Farmapp - Website

Farmapp es una aplicación orientada al seguimiento de la injesta de medicamentos, permitiendo llevar un control medico al alcance de tu mano. Con un diseño simple y facil de comprender para la mayoria de usuarios, esta permite la creación de una cuenta personal, donde se puede generar una serie de alarmas que seran notificadas en el dispositivo, las cuales tambien pueden ser marcadas para validar que se haya ingerido dicho medicamento.

## 👨‍💻 Instalación 

Sigue estos pasos para configurar y ejecutar el proyecto **Farmapp** en tu entorno local.

### Pre-requisitos

Asegúrate de tener instalado lo siguiente en tu máquina:

- [Python](https://www.python.org/) (versión 3.13.x o superior)
- [Git](https://git-scm.com/)

### Pasos a seguir

Primero, abre una terminal o cmd (windows).

* Instalar virtualenv (Manejador de 'Virtual Environments')

```bash
pip install virtualenv
```

* clona el repositorio del proyecto desde GitHub.

```bash
git clone https://github.com/HaleymHidalgo/Farmapp_website.git
```

*  Accede al directorio del proyecto clonado

```bash
cd AutosDelMar
```

* Cree un ambiente virtual

```bash
virtualenv <nombre-ambiente>
```

* Active el ambiente virtual

```bash
.\<nombre-ambiente>\Scripts\activate
```


* Instale las dependecias del proyecto

```bash
pip install -r requirements.txt
```

* Inicie el servidor de desarrollo
```bash
py manage.py runserver
```
#### El servidor se ejecutará en http://localhost:8000. Abre esta URL en tu navegador para ver el proyecto en acción.

## 👀 Team Members

* Haleym Hidalgo
* Dondup Berrios
