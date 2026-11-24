# Bambino Lian — landing

Sitio estático publicado en **https://bambinolian.com** (Vercel, proyecto `bambino-lian-landing`).

- `index.html` — home (hero, portafolio, servicios, CineIA Pro, contacto)
- `cineia-pro.html` — página del Método CineIA Pro con la lista de espera
- `v/`, `p/` — videos y portadas del portafolio
- `h-*.webp`, `h-destellos.jpg` — capas del hero

Los formularios guardan en Supabase (`waitlist_cineia` y `contact_requests`) con la clave pública,
que solo permite insertar. Cada push a `main` se publica automáticamente en Vercel.
