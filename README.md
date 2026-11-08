# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** Delmy Emperatriz Aquino de Molina
- **Carné:** N/A
- **Correo institucional:** N/A
- **Asignatura:** Seguridad en Aplicaciones
- **Fecha:** 8/11/2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas, registro de eventos de autenticación y detección de incidentes, incluyendo el cálculo de las métricas MTTD y MTTR.

## 3. Estructura del proyecto

```text
 laboratorio-las/
   ├──  templates/
   │   ├──  login.html
   │   └──  registro.html
   ├──  venv/
    ├──  app.py
    ├──  crearDB.py
    ├──  detector.py
    ├──  eventos.log
    ├──  respuesta.log
    └──  usuarios.db
 README.md
```

## 4. Ejecución del proyecto

**Paso 1.** Clonar el repositorio.

```bash
git clone https://github.com/DELM24/lab-seguridad-mttd-mttr-DA.git
```

**Paso 2.** Ingresar al proyecto.

```bash
cd lab-seguridad-mttd-mttr-DA/laboratorio-las
```

**Paso 3.** Crear y activar el entorno virtual e instalar dependencias.

```bash
python -m venv venv
venv\Scripts\activate
pip install flask
pip show flask
```

**Paso 4.** Ejecutar la aplicación.

```bash
python app.py
```

