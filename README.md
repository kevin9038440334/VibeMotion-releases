<div align="center">

# VibeMotion

A desktop video editor you can talk to.

**[Download](https://github.com/kevin9038440334/VibeMotion-releases/releases/latest)** · [English](#english) · [Español](#español)

</div>

---

## English

VibeMotion is a video editor with a real timeline, keyframes and motion graphics, plus an editor that listens. You tell it what you want, for example *"tighten the intro, add captions, and put a counter on the 51 countries"*, and Claude makes the edit inside your project while you watch. Each step shows up in the timeline and in the chat, and you can open it, tweak it by hand or undo it.

It runs on your computer and uses your own Claude plan through Claude Code. You don't paste API keys and you don't buy separate AI credits.

> The interface is in Spanish for now. English is on the way.

### What it's good at

- **Talking-head videos and vlogs.** Captions synced word by word, silences removed in one go, titles that appear on the exact word they refer to.
- **Short-form for Reels, TikTok and Shorts.** Seven built-in styles, from soft "aesthetic" vlogs to fast retention edits, each with its own fonts, colors, captions and pacing.
- **Motion graphics.** Animated titles, number counters, callouts, hand-drawn underlines and circles, stickers, zoom punches and transitions.
- **Edits that don't look automated.** Claude watches and listens to your footage before touching it, and checks its own frames for overlapping text, unreadable captions and things too close to the edges.

Export is MP4 at full quality.

### Download

Get the latest version from the [Releases](https://github.com/kevin9038440334/VibeMotion-releases/releases) page.

| System | Version | File |
| --- | --- | --- |
| macOS | 13 Ventura or later, Apple Silicon or Intel | `.dmg` |
| Windows | 10 or 11, 64-bit | `.exe` installer |

Linux isn't supported yet.

### Before you install

VibeMotion uses the Claude Code you have on your machine, so set that up first:

1. You need a **Claude Pro or Max** plan.
2. Install **Claude Code** by following [Anthropic's instructions](https://claude.com/claude-code).
3. Open a terminal, run `claude` and sign in with your plan. You only do this once.

### Installing

**macOS.** Open the `.dmg` and drag VibeMotion into Applications. Early builds may not be notarized yet. If macOS says it can't check the app, Control-click VibeMotion in Applications, choose **Open**, and confirm.

**Windows.** Run the installer. Early builds aren't code-signed yet, so Windows SmartScreen may show a warning. Click **More info**, then **Run anyway**.

The first time you export or the agent reviews a frame, VibeMotion downloads its video renderer (about 90 MB). The first transcription downloads a speech model (about 150 MB). Both are saved, so this happens once.

### Your data

- Projects, media and exports stay on your computer. VibeMotion has no accounts and doesn't collect analytics.
- When you ask Claude for an edit, it receives your message plus what it needs to do the job: the transcript of your clips and the frames it renders to check its work. That goes through Claude Code, under your account and [Anthropic's terms](https://www.anthropic.com/legal).
- VibeMotion never reads or stores your Claude credentials.

Edits count toward your plan's usage, like any other Claude Code session. Long edits on long videos use more.

### System requirements

- macOS 13 or later, or Windows 10/11 (64-bit)
- 8 GB of RAM, 16 GB recommended for long or 4K videos
- About 1 GB of free space for the app and its components, plus room for your projects
- An internet connection for the agent. Editing by hand works offline.

### Questions

**Do I need an Anthropic API key?** No. VibeMotion only works with your Claude plan, through Claude Code.

**Which model does it use?** Whatever your plan offers. You pick the model and the effort level for each project.

**What if the app closes in the middle of an edit?** Everything Claude already did is saved. Open the project again and press **Continuar**: it picks up where it stopped.

**Can I edit while Claude is working?** Yes. Your changes and Claude's are merged, and you can undo any of its steps on their own.

### Reporting a problem

Open an [issue](https://github.com/kevin9038440334/VibeMotion-releases/issues) with your VibeMotion version, your system, and what happened. A screenshot helps a lot.

---

## Español

VibeMotion es un editor de video con línea de tiempo, fotogramas clave y motion graphics de verdad, y con un editor que te escucha. Le dices lo que quieres, por ejemplo *"acorta la intro, pon subtítulos y un contador en los 51 países"*, y Claude hace la edición dentro de tu proyecto mientras lo ves. Cada paso aparece en la línea de tiempo y en el chat, y puedes abrirlo, retocarlo a mano o deshacerlo.

Funciona en tu ordenador y usa tu propio plan de Claude a través de Claude Code. No pegas claves de API ni compras créditos de IA aparte.

### Para qué sirve

- **Videos hablados y vlogs.** Subtítulos sincronizados palabra a palabra, silencios fuera de una vez y títulos que entran justo en la palabra a la que se refieren.
- **Formato corto para Reels, TikTok y Shorts.** Siete estilos incluidos, desde vlogs suaves tipo "aesthetic" hasta ediciones rápidas de retención, cada uno con sus fuentes, colores, subtítulos y ritmo.
- **Motion graphics.** Títulos animados, contadores, señalizaciones, subrayados y círculos a mano, pegatinas, zoom de impacto y transiciones.
- **Ediciones que no parecen automáticas.** Claude mira y escucha tu metraje antes de tocarlo, y revisa sus propios fotogramas para que no haya textos encimados, subtítulos que no se leen ni nada pegado a los bordes.

Exporta en MP4 a máxima calidad.

### Descarga

Baja la última versión desde la página de [Releases](https://github.com/kevin9038440334/VibeMotion-releases/releases).

| Sistema | Versión | Archivo |
| --- | --- | --- |
| macOS | 13 Ventura o posterior, Apple Silicon o Intel | `.dmg` |
| Windows | 10 u 11, 64 bits | instalador `.exe` |

Linux todavía no está soportado.

### Antes de instalar

VibeMotion usa el Claude Code que tienes en tu equipo, así que prepáralo primero:

1. Necesitas un plan **Claude Pro o Max**.
2. Instala **Claude Code** siguiendo las [instrucciones de Anthropic](https://claude.com/claude-code).
3. Abre una terminal, ejecuta `claude` e inicia sesión con tu plan. Solo se hace una vez.

### Instalación

**macOS.** Abre el `.dmg` y arrastra VibeMotion a Aplicaciones. Las primeras versiones puede que aún no estén notarizadas. Si macOS dice que no puede comprobar la app, haz clic con Control sobre VibeMotion en Aplicaciones, elige **Abrir** y confirma.

**Windows.** Ejecuta el instalador. Las primeras versiones todavía no van firmadas, así que SmartScreen puede mostrar un aviso. Pulsa **Más información** y después **Ejecutar de todas formas**.

La primera vez que exportas o que el agente revisa un fotograma, VibeMotion descarga su motor de render (unos 90 MB). La primera transcripción descarga un modelo de voz (unos 150 MB). Quedan guardados, así que solo pasa una vez.

### Tus datos

- Los proyectos, los medios y las exportaciones se quedan en tu ordenador. VibeMotion no tiene cuentas ni recoge estadísticas de uso.
- Cuando le pides una edición a Claude, recibe tu mensaje y lo que necesita para hacerla: la transcripción de tus clips y los fotogramas que renderiza para revisar su trabajo. Eso pasa por Claude Code, con tu cuenta y bajo los [términos de Anthropic](https://www.anthropic.com/legal).
- VibeMotion nunca lee ni guarda tus credenciales de Claude.

Las ediciones cuentan en el uso de tu plan, como cualquier otra sesión de Claude Code. Una edición larga sobre un video largo consume más.

### Requisitos

- macOS 13 o posterior, o Windows 10/11 (64 bits)
- 8 GB de RAM; 16 GB recomendados para videos largos o en 4K
- Alrededor de 1 GB libre para la app y sus componentes, más el espacio de tus proyectos
- Conexión a internet para el agente. La edición a mano funciona sin conexión.

### Preguntas

**¿Necesito una clave de API de Anthropic?** No. VibeMotion solo funciona con tu plan de Claude, a través de Claude Code.

**¿Qué modelo usa?** El que te ofrezca tu plan. Eliges el modelo y el nivel de esfuerzo en cada proyecto.

**¿Y si la app se cierra a mitad de una edición?** Todo lo que Claude ya hizo queda guardado. Vuelve a abrir el proyecto y pulsa **Continuar**: sigue donde se quedó.

**¿Puedo editar mientras Claude trabaja?** Sí. Tus cambios y los suyos se combinan, y puedes deshacer cualquiera de sus pasos por separado.

### Reportar un problema

Abre un [issue](https://github.com/kevin9038440334/VibeMotion-releases/issues) con tu versión de VibeMotion, tu sistema y lo que pasó. Una captura ayuda mucho.

---

<sub>VibeMotion is an independent project and is not affiliated with or endorsed by Anthropic. Claude and Claude Code are trademarks of Anthropic, PBC. · VibeMotion es un proyecto independiente, sin relación ni respaldo de Anthropic. Claude y Claude Code son marcas de Anthropic, PBC.</sub>
