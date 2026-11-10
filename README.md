# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** Henry Alexander Jimenez Bonilla
- **Carné:** JB25002
- **Correo institucional:** henryalexanderj@yahoo.com
- **Asignatura:** Lenguajes de programación con aspectos de seguridad
- **Fecha:** 08/11/2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python y Flask, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas mediante hashing, registro de eventos de autenticación en logs y un sistema de detección y respuesta ante incidentes que calcula las métricas MTTD (Mean Time to Detect) y MTTR (Mean Time to Respond).

## 3. Estructura del proyecto

```text
Laboratorio-C-digo-Seguro-y-Modelo-OWASP/
├── templates/
│   ├── login.html
│   └── registro.html
├── app.py
├── crearDB.py
├── detector.py
├── eventos.log
├── respuestas.log
├── usuarios.db
└── README.md
```
## 4. Ejecución del proyecto

**Paso 1.** Clonar el repositorio.

```bash
git clone https://github.com/jmenzh-b/Laboratorio-C-digo-Seguro-y-Modelo-OWASP.git
```

**Paso 2.** Ingresar al proyecto.

```bash
cd Laboratorio-C-digo-Seguro-y-Modelo-OWASP
```

**Paso 3.** Instalar las dependencias.

```bash
python detector.py
```

**Paso 4.** Ejecutar la aplicación.

```bash
python app.py
```
