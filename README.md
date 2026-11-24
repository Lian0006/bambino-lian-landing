# Bambino Lian — landing

Sitio estático publicado en **https://bambinolian.com** (Vercel, proyecto `bambino-lian-landing`).

- `index.html` — home (hero, portafolio, servicios, CineIA Pro, contacto)
- `cineia-pro.html` — página del Método CineIA Pro con la lista de espera
- `v2/`, `p2/` — vistas previas del portafolio (540×960, 5–6 s, sin audio) y sus portadas. Si cambias un video, usa un nombre de archivo nuevo: estas carpetas se cachean como inmutables por un año
- `h-*.webp`, `h-destellos.jpg` — capas del hero

Los formularios guardan en Supabase (`waitlist_cineia` y `contact_requests`) con la clave pública,
que solo permite insertar. Cada push a `main` se publica automáticamente en Vercel.

## Cómo publicar cambios

Edita los archivos y haz push a `main`: Vercel publica solo en bambinolian.com en ~1 minuto.
