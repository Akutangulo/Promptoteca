# 📖 Promptoteca

**Promptoteca** es una aplicación web para organizar, filtrar y reutilizar prompts de manera sencilla.  
Los prompts se almacenan en un archivo JSON estructurado y se pueden buscar por categorías o tipo.  
Con un clic, copias el prompt y lo pegas directamente en tu modelo de lenguaje (LLM) favorito.  

---

## ✨ Características

- 📂 Gestión centralizada de prompts en `prompts.json`.  
- 🔎 Filtrado por **categorías** y **tipos** de prompt.  
- ⚡ Copia rápida de prompts al portapapeles.  
- 🖥️ Interfaz simple, ligera y responsive.  
- 🤝 Proyecto abierto y modificable bajo licencia MIT.  

---

## 🚀 Demo

👉 [Promptoteca en akutangulo.com](https://akutangulo.com)  
👉 [Promptoteca en chatsbots.es](https://chatsbots.es)  

---

## 📦 Instalación

Clona el repositorio:

```bash
git clone https://github.com/Akutangulo/Promptoteca.git
cd Promptoteca
````

Abre el archivo `index.html` en tu navegador o súbelo a tu servidor web.

---

## 🛠️ Uso

1. Edita el archivo `prompts.json` con tus propios prompts.
   El formato recomendado es el siguiente:

   ```json
   {
     "prompts": [
       {
         "categorias": ["habituales"],
         "tipo": ["prompt", "asistente"],
         "titulo": "Prompt de ChatGPT para que recuerde la conversación y seguir con ella",
         "contenido": "Hola de nuevo, vamos a continuar, puedes leer la conversacion? \n Te acuerdas de lo que estabamos haciendo?"
       },
       {
         "categorias": ["redaccion"],
         "titulo": "Corregir redacciones",
         "contenido": "Escribe con claridad y concisión. La ortografía y gramática son importantes."
       },
       {
         "categorias": ["programacion", "habituales"],
         "titulo": "Escribir código completo",
         "contenido": "Escribe el código completo de principio a fin y proporciona todo el bloque de código sin omitir partes. \n Tienes todo el código necesario para realizar esta misión, no delegues esta responsabilidad en nadie."
       }
     ]
   }
   ```

2. Guarda los cambios en `prompts.json`.

3. Abre la aplicación en tu navegador.

4. Filtra, busca y copia el prompt que necesites.

---

## 📖 Licencia

Este proyecto está bajo la licencia **MIT**.
Puedes usarlo, modificarlo y compartirlo, siempre que mantengas la atribución al autor original.

© 2025 [Oscar Navarro - Akutangulo](https://akutangulo.com)
Repositorio: [Promptoteca en GitHub](https://github.com/Akutangulo/Promptoteca)

---

## 🙌 Créditos

Desarrollado por **Oscar Navarro** (Akutangulo).
Más proyectos en:

* 🌐 [akutangulo.com](https://akutangulo.com)
* 🤖 [chatsbots.es](https://chatsbots.es)
* 🐙 [GitHub @Akutangulo](https://github.com/Akutangulo)
¿Quieres que también te genere el archivo **LICENSE** con el texto oficial de MIT y tu nombre incluido al inicio?
```
