# 🚀 Requerimientos para Desarrollar con Laravel

Este documento describe los requisitos necesarios para configurar un entorno de desarrollo con Laravel en un entorno local.

---

## 📌 1. Sistema Operativo

- Windows 10 / 11 (64 bits)
- Linux (Ubuntu recomendado)
- macOS

---

## 📌 2. Servidor Local

Se recomienda utilizar **XAMPP** que incluye:

- Apache
- MySQL / MariaDB
- PHP

Asegurarse de que estén activos:

- ✅ Apache
- ✅ MySQL

---

## 📌 3. PHP

- Versión mínima requerida: **8.1**
- Versión recomendada: **8.2 o 8.3**

Verificar versión instalada:

```bash
php -v
```

### Extensiones necesarias habilitadas en `php.ini`:

- OpenSSL
- PDO
- Mbstring
- Tokenizer
- XML
- Ctype
- JSON
- BCMath
- Fileinfo

---

## 📌 4. Composer

Administrador de dependencias de PHP.

Verificar instalación:

```bash
composer -V
```

Descarga oficial:
https://getcomposer.org

---

## 📌 5. Node.js

Necesario para manejar Vite y los recursos frontend.

- Versión mínima: **18**
- Recomendado: **20 o superior**

Verificar versión:

```bash
node -v
npm -v
```

---

## 📌 6. Base de Datos

Laravel soporta:

- MySQL 5.7+
- MySQL 8+ (Recomendado)
- PostgreSQL
- SQLite
- SQL Server

Si usas XAMPP:
- MySQL
- phpMyAdmin

---

## 📌 7. Git (Recomendado)

Para control de versiones.

Verificar instalación:

```bash
git --version
```

---

# 🛠 Instalación del Proyecto Laravel

## 1️⃣ Crear proyecto

```bash
composer create-project laravel/laravel nombre-proyecto
```

## 2️⃣ Ingresar al proyecto

```bash
cd nombre-proyecto
```

## 3️⃣ Instalar dependencias frontend

```bash
npm install
```

## 4️⃣ Ejecutar servidor local

```bash
php artisan serve
```

## 5️⃣ Ejecutar Vite

```bash
npm run dev
```

---

# 📊 Versiones Recomendadas

| Software  | Versión Mínima | Recomendado |
|-----------|---------------|-------------|
| PHP       | 8.1           | 8.2 / 8.3   |
| Node.js   | 18            | 20+         |
| MySQL     | 5.7           | 8.0+        |
| Composer  | Última        | Última      |

---

# ✅ Entorno Listo

Si todos los requisitos están correctamente instalados, el proyecto Laravel debería ejecutarse sin problemas en:

```
http://127.0.0.1:8000
```

---
