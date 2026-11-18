# MouseCFG

Script opensource para el scyrox v8 entre otros
Doble click en Mouse cfg.cmd. 
El .ps1 tiene que quedar al lado.
No instala nada. 
Los cambios quedan en el mouse y el script se cierra.

Escribe (protocolo CompX, el de Mouse cfg para esta familia):
  Scyrox V8 y V8S
  Lamzu Atlantis (cable, receptor 1k y 4k)
  Teevolution Terra Pro
  VGN Dragonfly F2
  GravaStar Mercury
  Noir Gear M1-NEX
  Pulsar con VID 3710 (mapa de DPI de Pulsar)
  cualquier otro 3554/3710 con canal de config, como CompX generico

El resto del catalogo (Logitech, Razer, SteelSeries, G-Wolves, y mas)
se reconoce con list / mice y NO se modifica.
VXE/ATK R1 y Pulsar XS-1 / Pro tampoco se escriben: otro protocolo.

Nivel activo = el escalon de DPI que el mouse esta usando ahora.
El boton de DPI del mouse cambia de nivel. dpi cambia solo ese numero.

Cerra S-Center / Lamzu / Pulsar Hub / Chrome antes de correrlo.
Dongle directo al USB de la mother para 4k y 8k.

Ejemplos:
  Mouse cfg.cmd status
  Mouse cfg.cmd rate 1000
  Mouse cfg.cmd dpi 1600
  Mouse cfg.cmd lod 0.7
  Mouse cfg.cmd preset valorant

preset valorant pone el Hz mas alto que el mouse acepte, 1600 DPI si entra
en el rango, LOD mas bajo, competitive on, motion sync off, debounce 0.
En el Scyrox V8 eso es 8k, 1600, LOD 0.7.

Open-source script for the Scyrox V8, among others. Double-click `Mouse cfg.cmd`. The `.ps1` file must be kept in the same folder. It does not install anything; changes are applied directly to the mouse, and the script then closes.

Compatible devices (using the CompX protocol—the one employed by `Mouse cfg` for this product family): Scyrox V8 and V8S, Lamzu Atlantis (wired, 1k, and 4k receiver), Teevolution Terra Pro, VGN Dragonfly F2, GravaStar Mercury Noir, Gear M1-NEX, Pulsar mice with VID 3710 (using the Pulsar DPI map), and any other 3554/3710-based device with a configuration channel (such as generic CompX devices).

Other products (Logitech, Razer, SteelSeries, G-Wolves, etc.) will be detected via the `list / mice` command but cannot be modified. The VXE/ATK R1 and Pulsar XS-1/Pro are also unsupported, as they use a different protocol.

"Active level" refers to the specific DPI step currently in use by the mouse. The physical DPI button on the mouse cycles through these levels; the `dpi` command modifies only that specific value.

Close S-Center, Lamzu software, Pulsar Hub, and Chrome before running the script. For 4k and 8k polling rates, connect the dongle directly to a USB port on the motherboard.

Examples: `Mouse cfg.cmd status`, `Mouse cfg.cmd rate 1000`, `Mouse cfg.cmd dpi 1600`, `Mouse cfg.cmd lod 0.7`, `Mouse cfg.cmd preset valorant`.

The `preset valorant` command sets the polling rate to the highest value supported by the mouse, sets the DPI to 1600 (if within the supported range), minimizes the LOD (Lift-Off Distance), enables "competitive" mode, disables "motion sync," and sets the debounce time to 0. For the Scyrox V8, this results in 8k polling, 1600 DPI, and an LOD of 0.7.
