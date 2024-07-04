# Como actualizar CounterStrikeSharp en CS2
- [x] Descargar [CSSHARP LINUX WITH RUNTIME](https://github.com/roflmuffin/CounterStrikeSharp/releases)

- [x] Descomprimir CSSHARP en el escritorio.

- [x] Preparar CSSHARP para su actualización.
```
Este paso consiste en eliminar determinadas carpetas para no perder
toda la configuración del servidor,simplemente tenemos que dejar dentro de
counterstrikesharp las siguientes carpetas.

├── counterstrikesharp
│   ├── api
│   ├── bin
│   ├── dotnet
│   └── gamedata
│
├── metamod
│   ├── bin
│   ├── counterstrikesharp.vdf
│   ├── metaplugins.ini
│   └── README.txt
├── metamod.vdf
└── metamod_x64.vdf

Ya con esto realizado podemos subir la carpeta de CSSHARP a nuestro servidor y verificar que todo  este funcionando. 
```
## Metamod
- [x] En el caso de no funcionar CSSHARP realizar este paso.
      > Dentro de `game/csgo/` tendremos que buscar el archivo `gameinfo.gi` y agregar la siguiente linea de esta forma `Game csgo/addons/metamod/`
![gameinfo.gi](https://docs.cssharp.dev/images/gameinfogi-example.png)      








[histeriaservers](https://www.histeriaservers.com.ar)![Histeria Icon.](https://cdn.discordapp.com/attachments/1221848988593164351/1255433756307619881/871442630897205328_1.png?ex=667dc60c&is=667c748c&hm=036ee038f7fe1cc4ba80fa7feb64b562718b4e5a528d5d4f25160ac18e81f39c&)
