# Fussion Fitness — Oro Verde

Sistema de gestión del gimnasio: Recepción, rutina del alumno y panel de administración.
Sitio estático (HTML, CSS y JavaScript) conectado a Supabase. Se publica en Vercel.

- `recepcion.html`: PC del mostrador, ingreso por DNI.
- `ver-rutina.html?socio=<id>`: link personal de cada alumno.
- `login.html` e `index.html`: panel de administración.
- `planificacion.html`: rutina de la semana por nivel (Inicial, Medio, Avanzado).

Turnos fijos: cada socio tiene su horario en la ficha (Alta / Editar socio); desde su link puede
borrarse o cambiarse hasta 2 horas antes.

La clave de Supabase que figura en las páginas es la publicable: los datos de los socios
están protegidos por las políticas de la base (RLS).
