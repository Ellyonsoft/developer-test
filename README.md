# 🧪 Test Técnico - Desarrollador JavaScript / React.js
## ⏱ Tiempo estimado: 1.5 - 2 horas

Este repositorio contiene la solución al test técnico para evaluar habilidades en **JavaScript puro** y **React.js**.

## 📁 Estructura del Proyecto

```
.
├── logic-js/        # Soluciones de lógica en JavaScript puro
│   └── logic.js
│
├── clock-app/       # Aplicación en React: Reloj dinámico
│   ├── public/
│   ├── src/
│   └── ...
│
└── README.md        # Este archivo
```

---

## ✅ Parte 1: Lógica en JavaScript

**Archivo:** `logic-js/logic.js`

Se incluyen las siguientes funciones implementadas:

1. `filterEvenNumbers(arr)` – Filtra números pares
2. `countOccurrences(arr)` – Cuenta ocurrencias en un arreglo
3. `myMap(arr, callback)` – Mapea con una función personalizada
4. `delayedHello(name, delay)` – Ejecuta una función con delay
5. `extractValues(arr, key)` – Extrae valores de objetos por clave

**Ejecutar:**

```bash
cd logic-js
node logic.js
```

---

## ⚛️ Parte 2: Reloj en React

**Carpeta:** `clock-app/`

Se construyó un componente funcional `<Clock />` que:

- Muestra la hora actual (actualizada cada segundo)
- Permite pausar y reanudar el reloj
- Indica si el reloj está activo o pausado
- Usa `useState` y `useEffect`
- Tiene estilos simples con Tailwind CSS (opcional)

### 📦 Cómo iniciar el proyecto

Instalar dependencias:

```bash
cd clock-app
npm install
```

Iniciar servidor:

```bash
npm run dev   # Si usaste Vite
# o
npm start     # Si usaste create-react-app
```

Ver en: [http://localhost:3030](http://localhost:3030) o el puerto que indique el CLI.

---

## 🔗 Requisitos de entrega

✅ Subida a cuenta GitHub
✅ Invitar al correo ``obed@ellyonsoft.io``
✅ Este README completado  
✅ Commits organizados
✅ Código comentado si es necesario

---

## 💬 Notas del Candidato

(Si deseas agregar algo sobre decisiones técnicas, dificultades o mejoras, escríbelo aquí.)

---
