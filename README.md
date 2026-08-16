# ci-cd-labs

Laboratorio 1 - Primer Pipeline de Integración Continua.

Este repositorio contiene un primer pipeline utilizando GitHub Actions.

## Objetivo

Aprender la estructura básica de un pipeline CI/CD y ejecutar automáticamente un pipeline después de realizar un push.

## Estructura

- `app/hello.txt`: archivo de prueba.
- `.github/workflows/pipeline.yml`: configuración del pipeline de GitHub Actions.

## Laboratorio 2

En este laboratorio se implementa un flujo de trabajo utilizando ramas de funcionalidad, Pull Requests y ejecución automática de Integración Continua con GitHub Actions.

### Flujo de trabajo

- Rama principal: `main`
- Rama de funcionalidad: `feature/update-readme`
- Integración mediante Pull Request
- Validación automática mediante GitHub Actions