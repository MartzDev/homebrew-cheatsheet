# 🍺 Homebrew Cheat Sheet — Comandos útiles para macOS

## 🔍 Información general
| Comando | Descripción |
|----------|--------------|
| `brew --version` | Muestra la versión actual de Homebrew. |
| `brew doctor` | Revisa tu instalación y te sugiere correcciones. |
| `brew config` | Muestra configuración interna (ruta, Ruby, CPU, etc.). |
| `brew update` | Actualiza Homebrew (no los paquetes). |
| `brew upgrade` | Actualiza todos los paquetes instalados. |
| `brew upgrade <paquete>` | Actualiza un paquete específico. |
| `brew cleanup` | Elimina versiones viejas y archivos temporales. |
| `brew cleanup -n` | Muestra qué se borraría sin eliminar nada. |
| `brew analytics off` | Desactiva las métricas anónimas. |

---

## 📦 Gestión de paquetes (formulae)
| Comando | Descripción |
|----------|--------------|
| `brew search <nombre>` | Busca paquetes disponibles. |
| `brew info <paquete>` | Muestra detalles (versión, instalación, dependencias). |
| `brew install <paquete>` | Instala un paquete. |
| `brew reinstall <paquete>` | Reinstala un paquete. |
| `brew uninstall <paquete>` | Desinstala un paquete. |
| `brew list` | Lista todos los paquetes instalados. |
| `brew list <paquete>` | Muestra los archivos instalados por ese paquete. |
| `brew deps <paquete>` | Muestra las dependencias de un paquete. |

---

## 🧰 Gestión de apps gráficas (Casks)
| Comando | Descripción |
|----------|--------------|
| `brew install --cask <app>` | Instala una aplicación (.app) de escritorio. |
| `brew uninstall --cask <app>` | Desinstala una app instalada con cask. |
| `brew list --cask` | Lista las apps instaladas con cask. |
| `brew info --cask <app>` | Información del cask. |
| `brew search --cask <nombre>` | Busca apps disponibles como casks. |

💡 **Ejemplo:**
```bash
brew install --cask visual-studio-code
brew uninstall --cask google-chrome
```

---

## 🧹 Mantenimiento y limpieza
| Comando | Descripción |
|----------|--------------|
| `brew cleanup` | Limpia versiones antiguas y cachés. |
| `brew autoremove` | Elimina dependencias que ya no son necesarias. |
| `brew doctor` | Diagnostica problemas comunes. |
| `brew update-reset` | Restaura Homebrew a un estado limpio (si algo se rompe). |

---

## 🧭 Rutas útiles
| Descripción | Ruta |
|--------------|------|
| Instalaciones de fórmulas | `/opt/homebrew/Cellar/` |
| Aplicaciones (casks) | `/Applications` o `~/Applications` |
| Caché de descargas | `~/Library/Caches/Homebrew` |
| Configuración principal | `/opt/homebrew` |

---

## 🧩 Diagnóstico y depuración
| Comando | Descripción |
|----------|--------------|
| `brew doctor` | Diagnóstico de la instalación. |
| `brew missing` | Muestra dependencias faltantes. |
| `brew outdated` | Muestra qué paquetes tienen actualizaciones disponibles. |
| `brew log <paquete>` | Muestra el historial de cambios de un paquete. |

---

## 🧪 Comandos menos comunes pero útiles
| Comando | Descripción |
|----------|--------------|
| `brew pin <paquete>` | Evita que se actualice ese paquete. |
| `brew unpin <paquete>` | Permite que se actualice de nuevo. |
| `brew tap` | Lista repositorios (taps) adicionales. |
| `brew tap <usuario/repositorio>` | Añade un tap extra. |
| `brew untap <usuario/repositorio>` | Elimina un tap. |

---

## 🗂 Gestión de dependencias
| Comando | Descripción |
|----------|--------------|
| `brew deps <paquete>` | Lista las dependencias de un paquete. |
| `brew uses <paquete>` | Muestra qué otros paquetes dependen de él. |

---

## 🧠 Pro tip
Puedes obtener ayuda detallada sobre cualquier comando usando:
```bash
brew help <comando>
```
Por ejemplo:
```bash
brew help cleanup
```

---

© 2025 — Guía rápida creada con ayuda de ChatGPT.
