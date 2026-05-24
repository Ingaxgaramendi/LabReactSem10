# 🐾 Laboratorio Semana 10

## Ingredientes :

### Rivera Anderson

### Carbajal Carlos

### Huancca Yojhan

Proyecto desarrollado con React + Vite como parte del curso de Desarrollo Frontend.

La aplicación simula una pequeña tienda virtual de productos para mascotas, aplicando conceptos básicos de React como:

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

## 🧩 Componente creado

![Componente](./capturas/componentecard.png)

---

## 🔄 Props enviadas al componente

![Props](./capturas/propsenvios.png)

---

## 🧹 Proyecto limpio

![Proyecto limpio](./capturas/proyectolimpio.png)

---

## ⚙️ Uso de estados y eventos

![Estados](./capturas/usodeestados.png)

---

# 📚 Conceptos aplicados

✅ Componentes React  
✅ Props  
✅ useState  
✅ Eventos con onClick  
✅ Renderizado dinámico  
✅ Estructura limpia del proyecto  
✅ Git y GitHub

---
