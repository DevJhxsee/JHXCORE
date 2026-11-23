# Preguntas frecuentes

### ¿Qué plan de Claude necesito?
Como mínimo **Claude Pro** (también sirven Max, Team y Enterprise), con acceso a Claude Code. JHX//CORE vincula tu cuenta con el *token de validación* de Claude, y Anthropic solo lo entrega a cuentas con suscripción: **con el plan gratuito no se puede generar**. JHX//CORE no vende ni incluye ningún plan: usa el tuyo.

### ¿Tengo que instalar Claude Code aparte?
No. El instalador ya trae Claude Code adentro. Si hay una versión más nueva, JHX//CORE te lo avisa y **te pregunta antes** de actualizarlo.

### ¿Dónde se guarda mi token?
Cifrado, en tu propio equipo (o dentro de la memoria, si la instalaste en un USB). Se abre únicamente con tu PIN de 6 números y nunca viaja a ningún servidor del autor.

### Olvidé mi PIN. ¿Se puede recuperar?
No. Por seguridad el PIN no se guarda en ningún lado. Tendrás que vincular tu cuenta otra vez (botón «vincular») y crear un PIN nuevo.

### ¿Qué es «evitar copias»?
Una protección que liga tu sesión de Claude a tu instalación. Si alguien copia o mueve la carpeta, la sesión vinculada se cierra y hay que vincular otra vez. Es opcional en «este equipo» y **obligatoria** en memorias y discos externos. Más detalles en [docs/evitar-copias.md](docs/evitar-copias.md).

### Moví la carpeta yo mismo y me pide vincular otra vez. ¿Es un error?
No. Con «evitar copias», mover la carpeta cuenta como copiarla. Vincula de nuevo y listo.

### ¿Puedo usarlo en varios PC?
Sí: instálalo en una **memoria USB o disco externo** («memoria o disco externo» en el instalador) y llévalo contigo. En cada PC abres el programa y pones tu PIN.

### ¿Cómo se actualiza?
El programa busca versiones nuevas al abrir, las comprueba con la firma del autor y te pregunta antes de instalarlas. También puedes pulsar el botón «actualizar JHX//CORE». Tus datos se conservan.

### Windows dice «Windows protegió su equipo». ¿Es seguro?
Ese aviso sale con programas nuevos que no tienen firma de editor comercial. Si descargaste el instalador de la página de [Releases](../../releases) de este repositorio, pulsa **Más información → Ejecutar de todas formas**.

### ¿Cómo lo desinstalo?
Cierra JHX//CORE y borra su carpeta (`JHXCORE`). Si creaste accesos directos, bórralos también. Tu token vive dentro de esa carpeta, así que desaparece con ella.

### Algo no funciona
Usa el botón **«reportar un problema»** del programa o abre un [reporte en GitHub](../../issues/new/choose).
