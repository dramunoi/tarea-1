# Ejercicio de Comandos Básicos de Git

Este ejercicio está diseñado para ayudarte a familiarizarte con los comandos básicos de Git. A continuación se describen los comandos que utilizaremos y su propósito.

## Comandos Básicos de Git

### 1. `git init`
Inicializa un nuevo repositorio de Git en el directorio actual. Este comando crea un subdirectorio `.git` que contiene todos los archivos necesarios para el repositorio.

```bash
git init
```

### 2. `git remote add`
Añade una nueva URL de repositorio remoto con un nombre específico. Este comando permite asociar el repositorio local con un repositorio remoto.

```bash
git remote add <nombre-remoto> <url-remoto>
```

### 3. `git add`
Añade archivos o cambios de archivos al área de preparación (staging area). Esto prepara los archivos para el próximo commit.

```bash
git add <archivo>
# O para añadir todos los archivos modificados:
git add .
```

### 4. `git commit`
Guarda los cambios añadidos al área de preparación en el historial de commits. Cada commit tiene un mensaje descriptivo que explica los cambios realizados.

```bash
git commit -m "Mensaje descriptivo del commit"
```

### 5. `git push`
Envía los commits locales al repositorio remoto. Esto actualiza el repositorio remoto con los cambios realizados localmente.

```bash
git push <nombre-remoto> <rama>
```

### 6. `git pull`
Descarga los cambios del repositorio remoto y los integra en la rama actual del repositorio local. Este comando combina `git fetch` y `git merge`.

```bash
git pull <nombre-remoto> <rama>
```

### 7. `git fetch`
Descarga los cambios del repositorio remoto pero no los integra en la rama actual. Este comando permite ver los cambios remotos sin modificar el historial local.

```bash
git fetch <nombre-remoto>
```

## Pasos del Ejercicio

1. **Inicializar el repositorio:**
   ```bash
   git init
   ```

2. **Añadir el repositorio remoto:**
   ```bash
   git remote add origin <url-del-repositorio-remoto>
   ```

3. **Añadir archivos al área de preparación:**
   ```bash
   git add .
   ```

4. **Hacer un commit de los cambios:**
   ```bash
   git commit -m "Primer commit"
   ```

5. **Enviar los cambios al repositorio remoto:**
   ```bash
   git push origin main
   ```

6. **Descargar e integrar cambios del repositorio remoto:**
   ```bash
   git pull origin main
   ```

7. **Solo descargar los cambios del repositorio remoto:**
   ```bash
   git fetch origin
   ```

## Recursos Adicionales

- [Documentación oficial de Git](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)

