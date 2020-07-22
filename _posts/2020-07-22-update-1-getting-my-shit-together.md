---
layout: post
title:  "Update_1: Getting my shit together"
date:   2020-07-23 20:11:31 +0200
categories: meta, ramblings, updates
---

Hey, hace tiempo que no escribo nada. Hace un par de semanas el ordenador murió (la placa base) y no me quedó más remedio que actualizar el rig. Bueno al menos ahora tengo Ryzen y 16GB de ram pero no dinero. Han sido semanas de arreglar cosas, organizar mis archivos de forma obsesivo compulsiva, leer y demás. Solo estos últimos cuatro días he empezado ya a hacer cosas. Aunque sinceramente creo que me obsesiono demasiado con "ser productivo" y todo eso. Mis archivos ahora son coherentes y eso significa que mi flujo de trabajo debería mejorar considerablemente. También he estado instalando y configurando programas como el editor de texto que estoy usando para escribir esto, pero os ahorrare los detalles sórdidos, son aburridos. Voy a enseñaros un poco lo que he estado haciendo


## Gamedev

He vuelto a engancharme a programar y hacer cosas con el pc. En concreto, llevo un tiempo ya trabajando con un amigo en un pequeño proyecto de juego indie que espero que vea la luz algún día. He estado programando un sistema de diálogo que lee archivos JSON para cargar las líneas de diálogo y enseñarlas por pantalla. Está muy verde pero fue genial el cargar las pruebas y ver como funcionaba. Aquí un poco del código escrito en GDScript para el motor Godot:

```func read_file() -> Dictionary:
	var fichero = File.new()
	var dialogo
	fichero.open("res://dialog/test1.json",File.READ)
	dialogo = parse_json(fichero.get_as_text())
	fichero.close()
	return dialogo
```
Esta función lee un archivo JSON y lo devuelve como un diccionario.

Estoy pensando en presentarme a una gamejam que está celebrando itch.io sobre juegos narrativos. Tengo una idea de historia pero está muy verde, also tendría que hacer el artwork y eso si que me echa bastante para atrás.

[La jam](https://itch.io/jam/i-cant-write-but-want-to-tell-a-story)

## Lectura

He leído bastante pero ahora justo acabo de terminar *Silk* de Caitlín. R. Kiernan. Es una novela de terror ambientada en la subcultura punk y gótica de la américa de los 90. A ratos no sabía si ponerle un diez o si me estaban tomando el pelo. La he terminado justo hoy y la verdad es que todavía no tengo claro si me ha gustado o no, pero creo que ha valido la pena. Hoy me empezaré *La narración de Arthur Gordon Pym* la única novela de Poe, a ver que tal.

Y por favor, de Kiernan leeos si o si *The drowning girl*, ese libro me ha fascinado.

## Escribir

Hoy he estado rematando un pequeño relato que tenía aparcado de hace bastante tiempo. En breves subiré alguno.

Bueno, creo que de momento es todo, en breves subiré alguna historia y seguiré por aquí. A ver si revivo en twitter. Quería enseñaros algunas imágenes y corregir un poco el texto pero me duelen los dedos de teclear hoy y además creo que estoy enfermo (No creo que sea COVID). Así que ya nos leemos a la próxima.

Thanks!

PD: Creo que enlazaré mi goodreads o algo, estoy bastante activo por ahí últimamente.

PD2: Estos escritos no tienen formato ni estilo, sorry. Es el fluir de mis pensamientos y salé así.