# Cómo publicar el portafolio de Alejandra Vaca

## Qué incluye este paquete
- `index.html` — el sitio web completo
- `content.json` — **todo el contenido editable** (textos, datos, links)
- `admin/` — panel de administración (Decap CMS)
- `netlify.toml` — configuración de hosting

---

## Pasos para publicar (una sola vez)

### 1. Crear cuenta en GitHub
Ir a https://github.com y crear una cuenta gratuita.

### 2. Crear un repositorio
- Click en "New repository"
- Nombre: `portafolio-alejandra` (o cualquier nombre)
- Visibilidad: **Public** (requerido para Netlify gratis)
- Click en "Create repository"

### 3. Subir los archivos
En la página del repo recién creado, click en "uploading an existing file" y arrastra toda la carpeta de archivos.
- Confirmar con "Commit changes"

### 4. Conectar con Netlify
- Ir a https://netlify.com → "Add new site" → "Import an existing project"
- Elegir GitHub, autorizar, seleccionar el repositorio
- En "Build settings": dejar todo como está, click en "Deploy site"
- En ~1 minuto el sitio estará en una URL tipo `nombre-random.netlify.app`

### 5. Activar el panel de administración
En Netlify, ir a:
1. **Site configuration → Identity** → "Enable Identity"
2. Bajar hasta **Git Gateway** → "Enable Git Gateway"
3. En **Identity → Registration** → cambiar a "Invite only"
4. Click en "Invite users" → ingresar TU email → "Send"
5. Revisa tu email y acepta la invitación → crea tu contraseña

### 6. Listo — editar el contenido
Entrar a `tu-sitio.netlify.app/admin/` e iniciar sesión.
Desde ahí puedes editar todo: textos, experiencia, skills, foto, etc.
Los cambios se guardan en GitHub y el sitio se actualiza automáticamente en ~30 segundos.

---

## Dominio propio (opcional)
En Netlify → Domain management → Add custom domain.
Puedes comprar un dominio en https://www.niagahoster.cl o https://www.godaddy.com.

---

## Preguntas frecuentes

**¿Puedo subir mi foto?**
Sí. En el admin, dentro de "Hero", hay un campo "Foto de perfil" con botón de upload.

**¿Puedo agregar más empresas al timeline?**
Sí. En el admin, en "Experiencia (timeline)" puedes agregar, editar o eliminar filas.

**¿Cuánto cuesta?**
El hosting en Netlify es **gratuito** para este tipo de sitio.
Solo pagarías si contratas un dominio personalizado (~$15 USD/año).
