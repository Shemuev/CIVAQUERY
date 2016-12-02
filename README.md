# CIVAQUERY

Comandos de [VoiceAttack](www.voiceattack.com) para Elite Dangerous que consultan que cantidad de material, mercancía o dato de ingenieros tienes almacenado en la bodega de carga usando como plataforma la app EDEngineer y sus opciones de servidor local.

### Instalación

Requirimientos:

- [EDEngineer](https://github.com/msarilar/EDEngineer)
- [VAExtensions](https://github.com/Antaniserse/VAExtensions)

Para que las consultas funcionen correctamente es necesario tener instalado y configurado correctamente [EDEngineer](https://cdn.rawgit.com/msarilar/EDEngineer/master/EDEngineer/releases/setup.exe), ya que actualmente no se puede consultar la carga de tu nave usando la información de los logs proporcionados por FDEV.

[VAExtensions](https://github.com/Antaniserse/VAExtensions/releases) es un plugin para Voiceattack que es necesario tener instalado y activado para que los comandos de consulta puedan ser ejecutados correctamente.

Comandos de Voiceattack (Dos ficheros .vap):

- Consultas_para_perfil_principal.vap: Se deberán importar dentro de nuestro perfil principal que usemos para elite Dangerous. Para ello editaremos el perfil e importaremos los comandos dentro.

<p align="center">
  <img src="https://s16.postimg.org/bmm1ikqfp/edit_main_profile.png" alt="Details"/>
</p>
<p align="center">
  <img src="https://s16.postimg.org/raru33vf9/import_commands.pngg" alt="Details"/>
</p>
<p align="center">
  <img src="https://s16.postimg.org/8tstyjq39/import_commands_2.png" alt="Details"/>
</p>

- Consultas Ingenieros.vap: Este es un perfil que deberemos importar completo y cuyo nombre no debe ser modificado.

<p align="center">
  <img src="https://s16.postimg.org/bdt26e311/import_profile.png" alt="Details"/>
</p>

### Funcionalidades

Estos son los comandos de voz que están disponibles para usar.

- "Dime la cantidad de": Después de ejecutar este comando de voz esperaremos un instante para nombrar el material deseado. Como resultado se nos devolverá vía texto hablado la cantidad que tenemos actualmente en nuestra bodega de carga.
- "Dime la descripción de": Después de ejecutar este comando de voz esperaremos un instante para nombrar el material deseado. Como resultado se nos devolverá vía texto hablado la rareza el material acompñado de una pequeña descripción de donde puede ser encontrado.
- "Que tipo es": Después de ejecutar este comando de voz esperaremos un instante para nombrar el material deseado. Como resultado se nos devolverá vía texto hablado de que tipo es el objeto nombrado (Mercancía, material o dato).

##### **AVISO:** Despues de ejecutar cada comando hay que hace una pequeña pausa (1s) para nombrar el material, mercancía o dato que queremos consultar.
