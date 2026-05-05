# Wikianabolics - Instalación y configuración completa

Guía paso a paso para descargar, configurar Git y traer el proyecto a una computadora nueva.

---

## 1. Instalar Git

Descargar Git desde:

https://git-scm.com/

Instalar normalmente con la configuración por defecto.

Verificar instalación:

```bash
git --version
```

Si aparece una versión, Git está instalado correctamente.

---

## 2. Instalar Visual Studio Code

Descargar desde:

https://code.visualstudio.com/

Instalar normalmente.

---

## 3. Iniciar sesión en GitHub

Entrar a:

https://github.com/

Iniciar sesión con tu cuenta.

---

## 4. Configurar Git (solo la primera vez en esa PC)

Abrir PowerShell o CMD y escribir:

```bash
git config --global user.name "Manaosfc"
git config --global user.email "esteban.vera1020@gmail.com"
```

Verificar:

```bash
git config --list --no-pager
```

Debe aparecer:

```bash
user.name=Manaosfc
user.email=esteban.vera1020@gmail.com
```

---

## 5. Elegir carpeta donde guardar el proyecto

Ejemplo:

```bash
cd Desktop
```

o

```bash
cd Documents
```

---

## 6. Clonar el repositorio

Descargar el proyecto desde GitHub:

```bash
git clone https://github.com/Manaosfc/escuela-tarea.git
```

Esto crea la carpeta del proyecto.

---

## 7. Entrar al proyecto

```bash
cd escuela-tarea
```

---

## 8. Abrir en Visual Studio Code

```bash
code .
```

Esto abre todo el proyecto.

---

## 9. Traer cambios nuevos

Si hiciste cambios desde otra computadora:

```bash
git pull
```

Esto descarga la última versión.

---

## 10. Guardar cambios y subirlos

Agregar archivos:

```bash
git add .
```

Crear commit:

```bash
git commit -m "Descripción de cambios"
```

Subir cambios:

```bash
git push
```

Si pide iniciar sesión:
- abrir navegador
- autorizar GitHub
- volver a la terminal

---

## 11. Actualizar siempre antes de trabajar

Antes de empezar:

```bash
git pull
```

Así evitás conflictos.

---

## Flujo de trabajo recomendado

Cuando llegás a la escuela:

```bash
git pull
```

Trabajás normalmente.

Cuando terminás:

```bash
git add .
git commit -m "Cambios del día"
git push
```

Cuando volvés a tu casa:

```bash
git pull
```

Y seguís.

---

## Repositorio oficial

https://github.com/Manaosfc/escuela-tarea
