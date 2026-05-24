# 🐾 Laboratorio Semana 10

## Ingredientes :

### Rivera Anderson

### Carbajal Carlos

### Huancca Yojhan

Proyecto desarrollado con React + Vite como parte del curso de Desarrollo Frontend.
aplicando conceptos básicos de React como:

- Componentes
- Props
- Estados
- Eventos
- Renderizado dinámico

---

# 🚀 Tecnologías utilizadas

- ⚛️ React
- ⚡ Vite
- 🟨 JavaScript
- 🎨 CSS

---

# 📸 Capturas del proyecto

# Yojhan huancca

### 1. Vista inicial

![Vista inicial](https://raw.githubusercontent.com/Ingaxgaramendi/LabReactSem10/main/docs/01.png)

### 2. Favicon configurado

Se agrego un icono personalizado en la pestana del navegador usando un archivo SVG en la carpeta `public`.

Ruta de imagen: `docs/02favicon.png`

![Favicon](https://raw.githubusercontent.com/Ingaxgaramendi/LabReactSem10/main/docs/02favicon.png)

### 3. Componente Card

Se creo una tarjeta reutilizable para mostrar el nombre y la descripcion.

Ruta de imagen: `docs/03.compoentes.png`

![Componente Card](https://raw.githubusercontent.com/Ingaxgaramendi/LabReactSem10/main/docs/03.compoentes.png)

### 4. Uso de props

El componente `Card` recibe los valores `title` y `description` desde `App.tsx`.

Ruta de imagen: `docs/04.carpProps.png`

![Props en Card](https://raw.githubusercontent.com/Ingaxgaramendi/LabReactSem10/main/docs/04.carpProps.png)

### 5. Manejo de estado

Se agrego `useState` para controlar el contador de likes. Cada tarjeta tiene su propio estado y aumenta al presionar el boton.

Ruta de imagen: `docs/05.manejostado.png`

![Manejo de estado](https://raw.githubusercontent.com/Ingaxgaramendi/LabReactSem10/main/docs/05.manejostado.png)

## Codigo principal

### Componente Card

```tsx
import { useState } from "react";

type CardProps = {
  title: string;
  description: string;
};

function Card({ title, description }: CardProps) {
  const [likes, setLikes] = useState(0);

  const handleClick = () => {
    setLikes(likes + 1);
  };

  return (
    <div className="card">
      <h3>{title}</h3>
      <p>{description}</p>
      <button className="button" onClick={handleClick}>
        Likes {likes}
      </button>
    </div>
  );
}

export default Card;
```

# Anderson rivera

# 📦 Instalación

## Clonar el repositorio

git clone https://github.com/Ingaxgaramendi/PetcareReact.git

## Entrar al proyecto

```bash
cd PetcareReact
```

## Instalar dependencias

```bash
npm install
```

## Ejecutar el proyecto

```bash
npm run dev
```

---

## 🧹 Proyecto limpio

![Proyecto limpio](./docs/proyectolimpio.png)

## 🧩 Componente creado

![Componente](./docs/componentecard.png)

---

## 🔄 Props enviadas al componente

![Props](./docs/propsenvios.png)

---

---

## ⚙️ Uso de estados y eventos

![Estados](./docs/usodeestados.png)

---

# Carbajal Carlos

## 1. Proyecto creado con React + Vite

Se inició el proyecto usando React con Vite.

![React Vite](docs/react.png)

---

## 2. Proyecto limpio

Se eliminó la plantilla inicial de Vite y se dejó una base limpia para comenzar el desarrollo.

![Home limpio](docs/home_limpio.png)

---

## 3. Primera versión de la pantalla principal

Se creó la primera vista de la aplicación CineSpoilerS.

![Home v0](docs/home%20v_0.png)

---

## 4. Mejora visual de la interfaz

Se aplicó una interfaz oscura, minimalista y más atractiva.

![Home v1](docs/home_v1.png)

---

## 5. Interfaz principal mejorada

Se mejoró la portada principal con mejor distribución visual.

![Home v2](docs/home_v2.png)

---

## 6. Catálogo de películas

Se agregó la cartelera de películas disponibles para comprar tickets.

![Home v3](docs/home_v3.png)

---

## 7. Componente Card

Se creó un componente reutilizable para mostrar cada película como una tarjeta.

![Componente Card](docs/CARD.png)

---

## 8. Envío de props

Se evidencia el envío de datos desde el componente padre hacia el componente hijo usando props.

![Props](docs/PROPS.png)

---

## 9. Manejo de estado

Se utilizó `useState` para manejar el estado del carrito de compras.

![Evidencia estado](docs/EVIDENCIA_ESTADO.png)

---

## 10. Carrito de compras

El carrito muestra los tickets agregados, la cantidad y el total a pagar.

![Carrito de compras](docs/carrito_compras.png)

# 📚 Conceptos aplicados

✅ Componentes React  
✅ Props  
✅ useState  
✅ Eventos con onClick  
✅ Renderizado dinámico  
✅ Estructura limpia del proyecto  
✅ Git y GitHub

---
