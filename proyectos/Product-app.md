## Proyecto de Productos

1. Creamos los  modulos

- ng g m auth ( ng generate module auth)
- ng g m products
- ng g m material

2. Creamos nuestros componentes correspodiente al "auth"

 - ng g c auth/pages/registro
 - ng g c auth/pages/login 

Nota: propiedad del settings.json "explorer.compactFolders": false,

3. Crear los componentes del products

 - ng g c products/pages/add-product
 - ng g c products/pages/search
 - ng g c products/pages/product-id
 - ng g c products/pages/home

 4. Creando el Error 404
  **Dentro de una carpeta llamada "shared"**
  - ng g c shared/error404