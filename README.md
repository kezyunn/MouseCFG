# MouseCFG
Script opensource para el scyrox v8 entre otros
Doble click en Mouse cfg.cmd. El .ps1 tiene que quedar al lado.
No instala nada. Los cambios quedan en el mouse y el script se cierra.

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
