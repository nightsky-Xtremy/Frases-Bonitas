# 💖 Frases Bonitas

**Desarrollador:** nightsky-Xtremy
**Versión:** 1.0
**Plataforma:** Linux (Debian/Ubuntu/Mint)
**Formato de distribución:** `.deb`

---

## 🌟 Descripción

**Frases Bonitas** es una app sencilla y encantadora que te regala frases motivacionales aleatorias con solo un clic.

Ideal para:

* Inspirarte en cualquier momento 💡
* Alegrar tu día 😄
* Disfrutar de mensajes positivos sin complicaciones

La aplicación **no requiere abrir la terminal** y es muy ligera para tu sistema.

---

## ✨ Características

* **Botón interactivo:** Haz clic en **“¿Quieres leer algo bonito?”** y recibe una frase diferente.
* **Frases aleatorias:** Cada clic es una nueva dosis de motivación.
* **Interfaz gráfica simple:** Fácil de usar para todos los usuarios.
* **Ligera:** No ocupa muchos recursos del sistema.

---

## 🖥️ Instalación

1. Descarga el archivo `.deb` de **Frases Bonitas**.
2. Abre la terminal en la carpeta donde se encuentra el archivo (o haz doble clic sobre él para usar el instalador gráfico).
3. Instala con:

```bash
sudo dpkg -i FrasesBonitas.deb
```

4. Si hay dependencias faltantes, corrige con:

```bash
sudo apt-get install -f
```

5. Abre **Frases Bonitas** desde tu menú de aplicaciones.

---

## 📦 Dependencias

Antes de ejecutar la aplicación, asegúrate de tener instaladas estas dependencias:

### Sistema

```bash
sudo apt install python3 libgtk-3-dev
```

### Python y GTK3

```bash
sudo apt install python3-gi python3-gi-cairo gir1.2-gtk-3.0
```

### Librerías opcionales (si es necesario)

```bash
sudo apt install python3-pip
pip3 install --user Pango
```

### Verificación

```bash
python3 -c "import gi; gi.require_version('Gtk', '3.0'); from gi.repository import Gtk; print('GTK3 OK')"
```

Si imprime `GTK3 OK`, entonces la aplicación debería funcionar correctamente.

---

## 🚀 Uso

1. Abre la aplicación.
2. Haz clic en **“¿Quieres leer algo bonito?”**.
3. ¡Disfruta de tu frase motivacional! 💬
4. Haz clic nuevamente para una nueva frase cada vez.

**Ejemplo de frase:**

> “La felicidad no es algo hecho. Viene de tus propias acciones.”

---

## 🤝 Contribuciones

Si quieres agregar nuevas frases o mejorar la app:

1. Clona el repositorio.
2. Agrega frases en la lista dentro del código.
3. Envía un pull request ✨

---

## 📝 Licencia

Este proyecto está bajo la licencia **Creative Commons CC0 1.0 Universal (CC0 1.0)**. Puedes copiar, modificar y distribuir el software incluso con fines comerciales sin pedir permiso.
