# Página de Construcción Futurista

Una página de "Sitio en Construcción" moderna y futurista con cuenta regresiva hasta el 24 de enero de 2025. El diseño es totalmente responsivo y cuenta con animaciones suaves y efectos visuales atractivos.

## Características

- ⏳ Cuenta regresiva dinámica hasta la fecha de lanzamiento
- 🎨 Diseño futurista con efectos de resplandor
- 📱 Totalmente responsivo (móvil, tablet, PC)
- ✨ Animaciones suaves
- 🌈 Efectos de degradado modernos

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript
- Vite (como bundler)

## Estructura del Proyecto

```
proyecto/
├── css/
│   ├── styles.css
│   └── responsive.css
├── src/
│   └── countdown.js
├── index.html
├── package.json
└── README.md
```

## Instalación

1. Clona el repositorio:
```bash
git clone [URL-del-repositorio]
```

2. Navega al directorio del proyecto:
```bash
cd [nombre-del-proyecto]
```

3. Instala las dependencias:
```bash
npm install
```

4. Inicia el servidor de desarrollo:
```bash
npm run dev
```

## Desarrollo

Para trabajar en el proyecto:

1. El servidor de desarrollo se iniciará en `http://localhost:5173`
2. Los archivos principales están organizados en:
   - `index.html` - Estructura principal
   - `css/styles.css` - Estilos principales
   - `css/responsive.css` - Estilos responsivos
   - `src/countdown.js` - Lógica de la cuenta regresiva

## Construcción para Producción

Para construir el proyecto para producción:

```bash
npm run build
```

Los archivos de producción se generarán en el directorio `dist/`.

## Personalización

- La fecha objetivo se puede modificar en `src/countdown.js`
- Los colores principales se pueden ajustar en las variables CSS en `css/styles.css`
- Los breakpoints responsivos se pueden modificar en `css/responsive.css`

## Autor

Diseñado y desarrollado por Milton Rey

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.