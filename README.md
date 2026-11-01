<p align="center">
  <img width="240" height="240" alt="CumpaX_logo" src="https://github.com/user-attachments/assets/6c88ae87-6aca-4bf4-8b60-abb7ddd62d08" />
</p>

# CumpaUniversal

> Herramienta práctica para pasar secuencias y líneas de tiempo entre Final Cut Pro, Premiere Pro, DaVinci Resolve y Pro Tools sin perder sincronía ni cortes.

---

### ☕ Apoya el desarrollo / Support the Project

CumpaUniversal es una herramienta gratuita e independiente para la comunidad de montaje y posproducción. Si te ahorra tiempo en tus entregas o proyectos, podés colaborar con su desarrollo:

- 🇦🇷 **Argentina (Mercado Pago / Transferencia en ARS):** [Donar en Cafecito](https://cafecito.app/arielledesmabecerra)
- 🌎 **Internacional (Tarjeta / PayPal en USD):** [Support on Ko-fi](https://ko-fi.com/arielledesmabecerra)

---

## 🇪🇸 Español

### ¿Qué hace CumpaUniversal?
Resuelve los problemas habituales al intercambiar proyectos entre programas de edición y posproducción:

* **Aplanar multicámaras:** Convierte planos multicámara en tomas individuales en pistas estándar, listas para corrección de color (DaVinci Resolve) o posproducción de audio (Pro Tools), sin tomas ocultas ni desfasajes.
* **Armar cortes desde transcripciones:** Carga un archivo de texto o guion con tiempos (timecodes) y genera automáticamente una secuencia preliminar con los fragmentos elegidos o inyecta marcadores para buscar cualquier diálogo al instante.
* **Entregas limpias para sonido (Pro Tools / Avid):** Genera archivos AAF organizados por roles (diálogos, música, efectos), con márgenes de seguridad en cada corte (*handles*) y niveles en 0 dB para que el mezclador empiece a trabajar sin vicios de edición.
* **Reconectar sonido de rodaje:** Reemplaza el audio guía de la cámara por los micrófonos originales del grabador de sonido (corbateros de cada actor, caña/boom) sincronizándolos automáticamente por código de tiempo.
* **Cero riesgo para tu material:** Trabaja en modo de solo lectura; tus archivos originales nunca se tocan ni se sobrescriben.

---

### Flujo de trabajo en 4 pasos
1. **Media:** Arrastrá tu archivo (`.fcpxml`, `.xml`, `.aaf`, `.otio`) y verificá sus pistas, cuadros por segundo y duración.
2. **Multicam:** Aplaná el corte activo o desplegá todas las cámaras en pistas separadas.
3. **Cut / Transcript:** Armá un corte inicial a partir de entrevistas desgrabadas con timecode.
4. **Deliver:** Elegí el formato de destino (Premiere, Final Cut Pro, DaVinci Resolve o AAF para Pro Tools) y seleccioná qué pistas llevar.

---

### Instalación

#### macOS
1. Descargá `CumpaUniversal_1.0.0_universal.dmg` desde [Releases](../../releases).
2. Abrí el archivo y arrastrá el ícono a tu carpeta **Aplicaciones**.
3. **Primera apertura:** Hacé **clic derecho** sobre CumpaUniversal en Aplicaciones y elegí **Abrir**. En el cartel de seguridad, confirmá haciendo clic en **Abrir**.

#### Windows
1. Descargá `CumpaUniversal_1.0.0_x64-setup.exe` o `CumpaUniversal_1.0.0_x64_en-US.msi` desde [Releases](../../releases).
2. Hacé doble clic y completá el asistente habitual de instalación.

---

## 🇺🇸 English

### What is CumpaUniversal?
A dedicated utility designed to seamlessly exchange sequences and timelines between Final Cut Pro, Premiere Pro, DaVinci Resolve, and Pro Tools without sync issues:

* **Flatten Multicam Timelines:** Converts multicam angles into standard single-track cuts ready for color grading (DaVinci Resolve) or audio mixing (Pro Tools).
* **Rough Cuts from Transcripts:** Ingests text files or transcripts with timecodes to assemble rough cuts automatically or add searchable markers across your project.
* **Sound Turnovers for Pro Tools / Avid:** Exports clean AAF deliveries sorted by role (Dialogue, Music, SFX), with customizable edit handles and unity gain (0 dB).
* **Field Recorder Expansion:** Automatically links multi-track location sound (lavaliers, boom) using embedded timecode to replace camera scratch audio.
* **Non-Destructive:** Always operates in read-only mode, generating a new independent file without altering your source project.

---

### 4-Station Workflow
1. **Media:** Drop your sequence file (`.fcpxml`, `.xml`, `.aaf`, `.otio`) to inspect its frame rate, tracks, and duration.
2. **Multicam:** Flatten active camera angles or expand all cameras into parallel tracks.
3. **Cut / Transcript:** Generate a rough cut or search tags from a timecoded interview transcript.
4. **Deliver:** Select your target format (Premiere, FCP, Resolve, or Pro Tools AAF) and filter which tracks or roles to include.

---

### Installation

#### macOS
1. Download `CumpaUniversal_1.0.0_universal.dmg` from [Releases](../../releases).
2. Open the disk image and drag **CumpaUniversal** to your **Applications** folder.
3. **First launch:** **Right-click** the application in Finder and choose **Open**. Confirm by clicking **Open** in the system prompt.

#### Windows
1. Download `CumpaUniversal_1.0.0_x64-setup.exe` or `CumpaUniversal_1.0.0_x64_en-US.msi` from [Releases](../../releases).
2. Double-click to run the setup installer.
