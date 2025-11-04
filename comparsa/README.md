# Comparsa de Baile - Estructura de Contenidos

Este repositorio contiene la estructura organizacional para los contenidos de la comparsa de baile, con filiales distribuidas en diferentes ciudades del Perú.

## 📁 Estructura de Carpetas

### 🎵 Canciones (`/canciones`)
Contiene todo el material relacionado con las canciones de la comparsa.

- **`letras/`**: Archivos de texto con las letras de las canciones. Formato recomendado: `.txt` o `.pdf`
- **`audios/`**: Archivos de audio de las canciones. Formatos: `.mp3`, `.wav`, `.m4a`
- **`videos/`**: Referencias y enlaces a videos oficiales publicados en YouTube. Se recomienda crear archivos de texto con los enlaces y descripciones

### 🏢 Filiales (`/filiales`)
Organización por ciudad/filial. Actualmente contamos con 5 filiales activas:

#### Filiales Actuales:
- **Ayacucho** (`/filiales/ayacucho`)
- **Lima** (`/filiales/lima`)
- **Ica** (`/filiales/ica`)
- **Andahuaylas** (`/filiales/andahuaylas`)
- **Huancayo** (`/filiales/huancayo`)

Cada filial contiene las siguientes subcarpetas:

- **`integrantes/`**: Archivos Excel (`.xlsx`) con la información de los miembros de cada filial
  - Incluye datos como nombre, contacto, fecha de ingreso, etc.
  - Se recomienda mantener un archivo actualizado por año o periodo
  
- **`tiktok-reels/`**: Videos cortos y reels de TikTok específicos de cada filial
  - Formato: `.mp4`, `.mov`
  - Nombrar archivos con fecha y descripción breve
  
- **`documentos/`**: Documentación administrativa de cada filial
  - Actas, permisos, certificados, etc.
  - Formatos: `.pdf`, `.docx`, `.xlsx`

### 👕 Vestimenta (`/vestimenta`)
Material relacionado con la vestimenta y merchandising de la comparsa (aplicable a todas las filiales).

- **`general/`**: Diseños, especificaciones y fotos de la vestimenta oficial
  - Incluye patrones, medidas, colores oficiales
  - Fotos de referencia del vestuario completo
  
- **`merchandising/`**: Diseños y materiales para productos promocionales
  - Polos, gorras, stickers, banners
  - Logos y elementos gráficos de la marca

## 🚀 Expansión a Nuevas Filiales

Para agregar una nueva filial, simplemente crear una nueva carpeta dentro de `/filiales` con el nombre de la ciudad, y replicar la estructura estándar:

```
/filiales/nueva-ciudad/
├── integrantes/
├── tiktok-reels/
└── documentos/
```

## 📝 Convenciones de Nomenclatura

### Para archivos de integrantes:
- `integrantes_[ciudad]_[año].xlsx`
- Ejemplo: `integrantes_ayacucho_2024.xlsx`

### Para videos y reels:
- `[YYYY-MM-DD]_[descripcion].mp4`
- Ejemplo: `2024-11-03_ensayo_carnaval.mp4`

### Para documentos:
- `[tipo]_[ciudad]_[fecha].pdf`
- Ejemplo: `acta_lima_2024-11.pdf`

## 🔗 Referencias a YouTube

Para los videos oficiales en YouTube, crear archivos de texto (`.txt`) dentro de la carpeta `/canciones/videos/` con el siguiente formato:

```
Título: [Nombre de la canción/video]
URL: [Link de YouTube]
Fecha de publicación: [YYYY-MM-DD]
Descripción: [Breve descripción]
```

## 📋 Notas Importantes

1. **Archivos de integrantes**: Mantener actualizado el Excel con los datos de cada miembro
2. **Respaldos**: Se recomienda hacer copias de seguridad periódicas
3. **Privacidad**: Los datos personales de los integrantes deben manejarse con confidencialidad
4. **Formatos**: Mantener consistencia en los formatos de archivo mencionados
5. **Organización**: Revisar y organizar el contenido periódicamente

## 📞 Contacto

Para consultas sobre la organización del contenido o sugerencias de mejora, contactar con la coordinación general de la comparsa.

---

**Última actualización**: Noviembre 2024
