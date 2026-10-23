# DVORAK-INT — Dvorak Internacional para macOS

Layout de teclado Dvorak con soporte completo de español: acentos, ñ, diéresis y caracteres especiales mediante capas de modificadores.

Creado con [Ukelele](https://software.sil.org/ukelele/).

---

## Capas disponibles

| Capa | Modificador |
|------|-------------|
| Base | (ninguno) |
| Mayúsculas | Shift |
| Caps Lock | Caps Lock |
| Símbolos | Option |
| Símbolos mayúsculas | Shift + Option |
| Symbols caps | Caps Lock + Option |

---

## Instalación

### 1. Descargar el archivo

Descarga `DVORAK-INT.keylayout` de este repositorio.

### 2. Copiar a la carpeta de layouts

**Para todos los usuarios del sistema (recomendado):**

```bash
sudo cp DVORAK-INT.keylayout /Library/Keyboard\ Layouts/
```

**Solo para tu usuario:**

```bash
cp DVORAK-INT.keylayout ~/Library/Keyboard\ Layouts/
```

> Si la carpeta `~/Library/Keyboard Layouts/` no existe, créala primero:
> ```bash
> mkdir -p ~/Library/Keyboard\ Layouts/
> ```

### 3. Cerrar sesión y volver a entrar

El sistema carga los layouts al iniciar sesión. Cierra sesión en macOS y vuelve a entrar (no hace falta reiniciar).

### 4. Activar el layout

1. Abre **Preferencias del Sistema → Teclado → Fuentes de entrada**
2. Haz clic en **+**
3. En la barra de búsqueda escribe `DVORAK-INT`
4. Selecciónalo y haz clic en **Agregar**
5. Actívalo desde la barra de menú (ícono de teclado en la barra superior)

---

## Desinstalación

```bash
# Sistema
sudo rm /Library/Keyboard\ Layouts/DVORAK-INT.keylayout

# Usuario
rm ~/Library/Keyboard\ Layouts/DVORAK-INT.keylayout
```

Cierra sesión y vuelve a entrar para que desaparezca de las opciones.

---

## Licencia

MIT
