# TP_Semana2_EDWEB
Trabajo practivo Semana 2 de Estandares de desarrollo WEB

# Landing Page - StreamHub

Este repositorio contiene la landing page de una pagina de stramming de peluculas **StreamHub** creada a partir de una plantilla HTML gratuita.

## Branches

- **main**: Contiene la plantilla original sin modificar.
- **first-version**: Contiene la landing page modificada con los servicios, imágenes y estilos propios.

## Cómo ver la página localmente

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/JoelGiannini/TP_Semana2_EDWEB.git
   cd TP_Semana2_EDWEB
   ```

2. Cambiar a la rama que querés probar:

   ```bash
   git checkout landing-version
   ```

3. Abrir el archivo `index.html` en tu navegador:

   - Hacer doble clic sobre `index.html`  
   **O**  
   - Ejecutar con un servidor local (opcional, recomendado para probar JS):
     ```bash
     python3 -m http.server 8000
     ```
     Luego abrir `http://localhost:8000` en cualquier navegador.

> **Nota:** Cambiando la rama con `git checkout` podés probar tanto la plantilla original (`main`) como la landing modificada (`landing-version`).

## Cómo hacerla pública

Esta página se puede desplegar con **GitHub Pages**:

1. Ir al repositorio en GitHub → Configuración → Pages.
2. Seleccionar la branch que querés publicar (`main` o `first-version`) y la carpeta `/` como directorio raiz.
3. GitHub generará un enlace público tipo:  
   `https://joelgiannini.github.io/TP_Semana2_EDWEB/`

## Licencia

Todo se hizo bajo licencia MIT la cual respeta las ideas del software libre

## Respecto a imagenes utilizadas
Las imagenes del sitio son solamente demostratibas para el trabajo, El sitio no esta pensado para ningun fin lucrativo.

## Créditos

- Plantilla original descargada de: [https://plantillashtmlgratis.com/en/home/](https://plantillashtmlgratis.com/en/home/)
