# 🍗 KFC Clone PRO

Proyecto educativo que replica la interfaz y funcionalidades básicas del sitio web de KFC Colombia. Desarrollado con HTML, CSS y JavaScript vanilla, sin frameworks externos.

---

## 📁 Estructura del proyecto

```
public/
├── assets/
│   ├── COMBOS.png
│   ├── fundador1.jpg
│   ├── pollo1.jfif
│   ├── pollo2.png
│   ├── pollo3.jfif
│   ├── pollo5.png
│   ├── pollo6.jfif
│   ├── pollo7.webp
│   ├── pollo8.jfif
│   ├── pollo9.jfif
│   └── pollo10.jfif
├── css/
└── index.html
package.json
package-lock.json
server.js
```

---

## ✨ Funcionalidades

- **Header completo** con barra de navegación, selector de ubicación y enlaces rápidos
- **Hero section** con llamada a la acción
- **Menú principal** con tarjetas de productos y precios en COP
- **Modales dinámicos** para cada sección:
  - 📦 Hacer pedido (domicilio o recogida en tienda)
  - 📞 Formulario de contacto
  - 📍 Lista de restaurantes con buscador
  - 📖 Historia de KFC (línea de tiempo)
  - 🔍 Buscador de productos del menú
  - 👤 Perfil de usuario con historial de pedidos
  - 🔐 Login / Registro de cuenta
  - 🍗 Menú completo por categorías
  - 🔥 Promociones activas
- **Autenticación simulada** con `localStorage`
- **Búsqueda en tiempo real** de restaurantes y productos
- **Integración con Google Maps** para búsqueda de tiendas por ubicación

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura y semántica |
| CSS3 | Estilos, variables, animaciones |
| JavaScript  | Lógica, DOM, localStorage |
| Google Fonts | Tipografías Oswald y Roboto |
| Node.js + server.js | Servidor local para desarrollo |

---

## 🚀 Instalación y uso

1. Clona el repositorio:
   ```bash
   git clone <url-del-repositorio>
   cd <nombre-del-proyecto>
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Inicia el servidor local:
   ```bash
   node server.js
   ```

4. Abre el navegador en `http://localhost:3000` (o el puerto configurado en `server.js`).

---

## 📍 Restaurantes incluidos (Bogotá)

El proyecto incluye datos de 10 puntos KFC en Bogotá:

- KFC Andino, Gran Estación, Titan Plaza, El Retiro
- KFC Calima, Centro Mayor, Santafé, Bulevar Niza
- KFC Hayuelos, Palatino

---

## 🧾 Menú disponible

| Categoría | Ejemplos |
|---|---|
| 🍗 Pollos | Bucket Familiar, Pollo Crujiente, XL, BBQ |
| 🍔 Burgers | Classic, Doble, Wrap Crispy, BBQ Deluxe |
| 🥣 Combos | Burger + Papas + Bebida, Familiar 10 pzas |
| 🍟 Extras | Nuggets, Alitas, Papas, Coleslaw |
| 🥤 Bebidas | Coca-Cola, Jugo, Agua, Limonada |

---

## ⚠️ Aviso legal

> Este proyecto es estrictamente **educativo y sin fines comerciales**. KFC, sus logos, nombres y marcas asociadas son propiedad de **Yum! Brands**. Este clon no está afiliado, patrocinado ni respaldado por KFC o cualquiera de sus subsidiarias.

---

## 👤 Autor
Maria Alexandra Jimenez Avila-136871
