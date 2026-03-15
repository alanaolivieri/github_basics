# Instrucciones

Cada equipo trabajará sobre este único [`README.md`](README.md).

Dentro de este documento hay varios temas de actualidad.
Cada equipo deberá:

1. Desde consola:
- clonar el repo
- entrar a la carpeta del repo
- comprobar que están en main
- actualizar main
- crear su propia rama
- cambiarse a esa rama
    - completar únicamente su sección en el [`README.md`](README.md)
    - escribir un comentario sobre su tema
    - añadir al menos una imagen desde la [carpeta images](./images/)
- hacer add, commit y push

2. Desde web:
- abrir un Pull Request

La práctica está pensada para que el contenido sea muy simple y el foco esté en el proceso de trabajo en equipo.

## Temas

Cada equipo trabajará sobre uno de estos temas, agregará una descripción sobre el tema a abordar e imágenes para complementar, pero trabajará solo en la sección correspondiente:

1. [Deporte](README.md#1-deporte)
2. [Política](README.md#2-política)
3. [Naturaleza](README.md#3-naturaleza)
4. [Medicina](README.md#4-medicina)
5. [Cine](README.md#5-cine)
6. [Arte](README.md#6-arte)
7. [Tecnología](README.md#7-tecnología)
8. [Educación](README.md#8-educación)
9. [Economía](README.md#9-economía)
10. [Viajes](README.md#10-viajes)

## Normas de la práctica

- No se trabaja directamente en main
- Cada equipo debe crear su propia rama
- Cada equipo debe editar solo su sección
- No se deben modificar secciones de otros equipos
- Cada equipo debe abrir un único Pull Request
- El merge lo hacemos al final y dirigido
- Si hay errores, se corrigen en la misma rama antes del merge
- Cada imagen debe tener nombre único
- No borrar imágenes de otros
- No renombrar archivos ajenos
- No puede tocar títulos de otros temas
- No puede mover secciones
- No puede borrar separadores

## Qué haremos al final

- Revisaremos cada Pull Request
- Comprobaremos que cada equipo tocó solo su parte
- Verificaremos que la/s imagen/es funciona/n
- Aprobaremos los cambios correctos
- Haremos el merge final a main

Esto simula un flujo profesional real donde no todo el mundo fusiona cambios directamente en la rama principal.

## Comandos útiles para la práctica

- Clonar el repositorio
```bash
git clone https://github.com/usuario/github-team-practice.git
cd github-team-practice
```
- Ver estado del repositorio
```bash
git status
```
- Ver rama actual
```bash
git branch
```
- Ver todas las ramas
```bash
git branch -a
```
- Crear una rama nueva y cambiarte a ella
```bash
git checkout -b nombre-rama
```
- Cambiar de rama
```bash
git checkout main
```
- Actualizar rama
```bash
git pull
```
- Añadir cambios
    - solo a readme:
```bash
git add README.md
```
    - a todo:
```bash
git add .
```
- Hacer commit
```bash
git commit -m "Mensaje descriptivo"
```
- Subir rama al repositorio remoto
```bash
git push origin nombre-rama
```
- Ver historial resumido
```bash
git log --oneline
```
- Ver diferencias
```bash
git diff
```
- Mezclar con main
```bash
git merge main
```

## Revisiones en GitHub web.

- PR
    - Al hacer push, GitHub normalmente muestra un botón tipo: ``Compare & pull request``
    - También se puede entrar manualmente en:
        - pestaña ``Pull requests`` -> botón ``New pull request``
    - Elegir ramas a comparar: 
        >base: main

        >compare: team/deporte

    - Escribir título y descripción
    - Crear el PR clicando ``Create pull request``

- Revisar PR
    - Entrar en el Pull Request e ir a la pestaña ``Files changed`` y revisar:
        - que tocaron solo su sección
        - que la imagen carga bien
        - que el markdown quedó bien
        - que no rompieron otra parte del ``README``

- Cómo aprobarlo
    - Clicar en ``Review changes``
        1. ``Comment``: Dejar comentario, pero no se aprueba ni se rechaza
        2. ``Approve``: Se aprueba el PR
        3. ``Request changes``: Se pide que corrijan algo antes de aceptar

- Cómo hacer el merge final
    - Clic en ``Merge pull request`` y ``Confirm merge``


**Mini flujo visual**
```txt
Rama del equipo
   ↓
Push
   ↓
Pull Request
   ↓
Revisión
   ↓
Approve o Request changes
   ↓
Merge a main
```

[Ir al Readme](README.md)