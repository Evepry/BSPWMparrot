# ENV - My BSPWMparrot Modificado - Script Parrot

Este es mi arhivo de intalacion de BSPWMparrot Modificado,
mencion al creador del repositorio original del cual realize la modificacion xJackSx, el cual hace mencion honorifica a  Mr. Pr1ngl3s, por su gran colaboración. Y un saludo a S4VITAR.

Tambien una mencion al creador del reeepositorio original del cual me guie para realizar la el documento de README, yorkox0

## Modificaciones relaizadas

- Se añadio la siguiente linea a <kbd> ~/.config/bspwm/bspwmrc </kbd> para reconocer teclado latinoamericano

```bash
setxkbmap latam
```

- Se agrego un fondo de pantalla distinto

- Se sustitullo en <kbd> ~/.config/sxhkd/sxhkdrc </kbd> el atajo de reinicio de bspwm

```bash
#comando nuevo

# salir de bspwm
super + alt + q
	bspc quit

# reiniciar bspwm con super + <
super + less
	bspc wm -r
```

```bash
#comando original

# quit/restart bspwm
super + alt + {q,r}
	bspc {quit,wm -r}
```

<kbd> Nvim no esta incluida en el scripts </kbd> 

# Instalacion

```bash
git clone https://github.com/Evepry/BSPWMparrot.git
```

```bash
cd BSPWMparrot
```

```bash
chmod +x install.sh
```

```bash
./install.sh
```

## Utilidades:
- **bspwm**: Tiling Window Manager.
- **zsh**: Shell.
- **powerlevel10k**: Tema de la zsh.
- **polybar**: Herramienta rápida y fácil de usar para crear barras de estado.
- **polybar-themes**: Temas para la polybar.
- **compton**: Es un compositor para X y una bifurcación de xcompmgr-dana.
- **rofi**: Selector de ventana y lanzador de aplicaciones.
- **feh**: Visor de imágenes ligero, configurable y versátil.
- **Hack Nerd Font**: Fuente.
- **fzf**: Buscador difuso de línea de comandos de propósito general.

- **sxhkd**: Es un "demonio" que escucha los eventos del teclado y ejecuta comandos.
- **sxhkd**: Simple X HotKey Daemon, y es un programa ligero para gestionar atajos de teclado en entornos gráficos basados en X11.

## Shortcuts (atajos de teclado)
<kbd>Windows</kbd> + <kbd>Enter</kbd> : Abrir la consola (gnome-terminal).  
<kbd>Windows</kbd> + <kbd>W</kbd> : Cerrar la ventana actual.  
<kbd>Windows</kbd> + <kbd> < </kbd> : Reiniciar la configuración del bspwm.  
<kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>Q</kbd> : Cerrar sesión.  
<kbd>Windows</kbd> + <kbd>(⬆⬅⬇➡)</kbd> : Moverse por las ventanas en la workspace actual.  
<kbd>Windows</kbd> + <kbd>D</kbd> : Abrir el Rofi. <kbd>Esc</kbd> para salir.  
<kbd>Windows</kbd> + <kbd>(1,2,3,4,5,6,7,8,9,0)</kbd> : Cambiar el workspace.  
<kbd>Windows</kbd> + <kbd>T</kbd> : Cambiar la ventana actual a modo "terminal" (normal). Nos sirve cuando la ventana está en modo pantalla completa o flotante.  
<kbd>Windows</kbd> + <kbd>M</kbd> : Cambiar la ventana actual a modo "completo" (no ocupa la polybar). Presione la mismas teclas para volver a modo "terminal" (normal).  
<kbd>Windows</kbd> + <kbd>F</kbd> : Cambiar la ventana actual a modo pantalla completa (ocupa todo incluyendo la polybar).  
<kbd>Windows</kbd> + <kbd>S</kbd> : Cambiar la ventana actual a modo "flotante".  
<kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>(1,2,3,4,5,6,7,8,9,0)</kbd> : Mover la ventana actual a otro workspace.  
<kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>(⬆⬅⬇➡)</kbd> : Cambiar el tamaño de la ventana actual (solo funciona si está en modo terminal o flotante).  
<kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>(⬆⬅⬇➡)</kbd> : Cambiar la posición de la ventana actual (solo funciona en modo flotante).  
<kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>G</kbd> : Abrir Google Chrome (es necesario instalarlo primero).  
<kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>(⬆⬅⬇➡)</kbd> : Mostrar una preselección para luego abrir una ventana (una terminal, Google Chrome, un archivo, etc.). <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Space</kbd> para deshacer la preselección.  

## Configuración manual:
- Video by s4vitar: https://www.youtube.com/watch?v=mHLwfI1nHHY

## Créditos
- Autor: Evepry
- Inspirado en S4vitar
