# Arch Hyprland Config

> Mis configuraciones personales de Arch Linux + Hyprland — respaldo, control de cambios y evidencia de que Linux sí se puede aprender.

---

## Stack

| Componente | Herramienta |
|---|---|
| Sistema operativo | Arch Linux |
| Compositor / WM | [Hyprland](https://hyprland.org/) (Wayland) |
| Barra de estado | [Waybar](https://github.com/Alexays/Waybar) |
| Terminal | [Kitty](https://sw.kovidgoyal.net/kitty/) |
| Pantalla de bloqueo | [Hyprlock](https://github.com/hyprwm/hyprlock) |
| Fondo de pantalla | [Hyprpaper](https://github.com/hyprwm/hyprpaper) |
| Lanzador de apps | [Rofi](https://github.com/davatorium/rofi) |
| Info del sistema | [Fastfetch](https://github.com/fastfetch-cli/fastfetch) |

---

## Estructura

```text
.config/
├── hypr/
│   └── hyprland.conf       # Configuración principal del compositor
├── waybar/                 # Barra de estado (módulos, estilos CSS)
├── kitty/
│   └── kitty.conf          # Terminal con soporte GPU
├── rofi/
│   └── powermenu.rasi      # Menú de apagado personalizado
└── fastfetch/
    └── config.jsonc        # Info del sistema al abrir terminal
```

---

## Propósito del repositorio

- **Respaldo versionado** — si rompo algo, `git checkout` y listo
- **Registro de cambios** — ver cómo fue evolucionando el setup
- **Referencia personal** — documentar qué hace cada configuración y por qué
- **Demostración práctica** — evidencia real de uso de Linux, no solo decirlo

---

## Estado actual

En progreso. Las configuraciones base ya están funcionando. Próximamente:

- [ ] Integrar [Hyprlook](https://github.com/hyprwm/hyprlook) (en cuanto esté listo)
- [ ] Sidebar vertical personalizada
- [ ] Widgets de monitoreo del sistema
- [ ] Refinar el estilo general
- [ ] Agregar Hyprlock y Hyprpaper al repo

---

## Screenshots

> Próximamente — cuando el setup esté más refinado.

---

## Instalación / Uso

Este repo **no es un instalador automático**, es un respaldo personal. Si quieres usar alguna configuración:

```bash
# Clonar el repo
git clone https://github.com/Dev-CyberByte/arch-hyprland-config.git

# Copiar lo que necesites a tu ~/.config
cp -r arch-hyprland-config/.config/hypr ~/.config/
cp -r arch-hyprland-config/.config/waybar ~/.config/
# ... y así con los demás
```

> Revisa cada archivo antes de copiar — algunas rutas o configuraciones pueden ser específicas de mi hardware.

---

## Autor

**Juan Pablo Olivares** — [@Dev-CyberByte](https://github.com/Dev-CyberByte)

---

*"Aprendiendo que Arch no es difícil."*h
