# 🏠 HABITARDEV - Fullstack Setup

Este es el entorno de desarrollo para el proyecto Habitar.

## Instalaciones
    - [Node.js](https://nodejs.org) (Versión LTS recomendada)
    R- [NestJS CLI](https://docs.nestjs.com) (`npm i -g @nestjs/cli`)

## 📁 Estructura del Proyecto
- `NEST-back/`: API Rest desarrollada con NestJS (Puerto 4000).
- `NEXT-front/`: Aplicación Frontend con Next.js (Puerto 3000).

## 🚀 Inicio Rápido

1. **Clonar el proyecto y sus sub-módulos:**
   *(Instrucción para el equipo: clonar los repos de back y front dentro de sus respectivas carpetas).*

2. **Instalar todas las dependencias:**
   Desde la raíz `HABITARDEV`, ejecuta:
   ```bash
   npm run install-all
3. **Configura variavles de entorno**
    Crea un archivo .env.local dentro de NEXT-front/ con:
    NEXT_PUBLIC_API_URL=http://localhost:
4. **Correr el entorno de desarrollo:**
    npm run dev
