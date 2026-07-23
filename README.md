# Flurolab VR - Simulador 360° de Hemodinamia

Simulador interactivo de realidad virtual 360° para tecnólogos médicos en radiología intervencionista.

## 🏥 Laboratorios Disponibles

| Laboratorio | Equipo | Escenas | Hotspots |
|-------------|--------|---------|----------|
| **Discovery** | Angiografo Discovery GE | 5 | 26 |
| **Allura** | Angiografo Allura Philips | 4 | 23 |

## 🚀 Despliegue en GitHub Pages

### Paso 1: Crear repositorio
1. Ve a [github.com](https://github.com) y crea un nuevo repositorio
2. Nombre sugerido: `flurolab-vr`
3. Público (para que GitHub Pages funcione)

### Paso 2: Subir archivos
Sube todo el contenido de esta carpeta al repositorio:

```
flurolab-vr/
├── index.html              ← Menú principal
├── discovery/
│   ├── index.html
│   └── images/
│       ├── 01_entrada.jpg
│       ├── 02_discovery.jpg
│       ├── 03_comando.jpg
│       ├── 04_comando_lateral.jpg
│       └── 05_proteccion.jpg
├── allura/
│   ├── index.html
│   └── images/
│       ├── 01_entrada.jpg
│       ├── 02_mesa.jpg
│       ├── 03_comando.jpg
│       └── 04_proteccion.jpg
└── README.md
```

### Paso 3: Activar GitHub Pages
1. En tu repo, ve a **Settings** → **Pages**
2. Source: selecciona **Deploy from a branch**
3. Branch: selecciona `main` → `/ (root)`
4. Guarda

### Paso 4: Acceder
Espera 1-2 minutos y accede a:
```
https://TU-USUARIO.github.io/flurolab-vr/
```

## 📱 Uso para Alumnos

1. Abrir el link en navegador (Chrome, Firefox, Edge)
2. Elegir laboratorio: **Discovery** o **Allura**
3. Arrastrar para mirar alrededor (360°)
4. Clic en círculos azules (?) para ver info técnica
5. Usar flechas (← →) o botones para navegar entre escenas

## 🛠️ Tecnologías

- [Pannellum](https://pannellum.org/) - Viewer 360°
- HTML5 + CSS3 + Vanilla JS
- GitHub Pages (hosting gratuito)

## 📄 Licencia

Flurolab Academy © 2026
