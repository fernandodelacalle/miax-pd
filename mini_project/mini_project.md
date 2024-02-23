---
marp: true
theme: default
paginate: true
---

<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>

# Mini Proyecto

---
## Mini Proyecto
- Crea un repositorio de git. Cada paso sera un commit.
- Genera una api con dos métodos, uno método post que reciva un nombre y un método get que devuelva nombres. No hace falta codificar la logica por ahora.
- Dockeriza el API y genera un docker-compose. Usa un volumen para el directorio del código.
- Añade al compose la base de datos mongo y la interfaz mongo-express.
- Modifica el código del API para que se guarde el nombre en una coleccion.
- Modifica el API para que devuelva todos los nombres.

---