# ⚖️ LexLocal - Sistema de Gestión de Expedientes Judiciales & Vencimientos

Sistema web autónomo, seguro y 100% local (offline-first) diseñado para estudios jurídicos y abogados de la República del Paraguay.

---

## 🔐 Seguridad y Autenticación de Usuarios

El sistema cuenta con un modelo de seguridad por contraseña y control de roles:
* **Autenticación Estricta:** Nadie puede ingresar al perfil de otro usuario sin conocer su contraseña.
* **Perfiles Iniciales de Demostración:**
  * **Dr. Roberto García** (Abogado Senior / Administrador): `dr_garcia` | Contraseña: `garcia123`
  * **Dra. Elena López** (Abogada Asociada): `dra_lopez` | Contraseña: `lopez123`
  * **Carlos Martínez** (Asistente Jurídico): `asistente_martinez` | Contraseña: `martinez123`

---

## 👥 Módulo de Gestión de Usuarios (Exclusivo Administrador)

Cuando inicias sesión con un usuario Administrador (como el **Dr. Roberto García**), se habilita la pestaña superior **«👥 Gestión de Usuarios»**:
1. **Crear Nuevos Usuarios:**
   * Registra nuevos abogados, procuradores, asistentes o pasantes.
   * Asigna nombres de usuario únicos, contraseñas iniciales y colores de avatar.
   * Otorga o revoca permisos de Administrador.
2. **Editar Todos los Perfiles (Incluyendo el Propio):**
   * El administrador puede modificar el nombre, usuario, cargo y **asignar/cambiar contraseñas** de cualquier miembro.
   * Puede editar su **propio perfil** (cambiar su propia clave o nombre) con actualización inmediata de sesión.
   * Ver o comprobar las contraseñas asignadas con el botón de visualización `👁️`.
3. **Eliminar Cuentas:**
   * Revoca el acceso a usuarios que ya no formen parte del estudio (con protección para evitar eliminar la propia cuenta en uso).

---

## 📚 Módulos del Sistema

1. **Gestión de Expedientes y Vencimientos:** Control de plazos fatales (Hoy, Mañana, En la semana), estados procesales y piezas digitales.
2. **Modelos Procesales del Paraguay:** Compendio de escritos forenses (Editorial Intercontinental, La Ley Paraguaya, Biblioteca CSJ y Marcial Riquelme) con copia en un clic, descarga para Word y vinculación a causas.
3. **Auditoría Completa:** Registro inalterable de accesos, creación y edición de perfiles, subida de documentos y modificaciones.
4. **Respaldos Portables (.json):** Exporta e importa la base de datos completa (incluyendo expedientes, historial y todos los usuarios con sus claves).
