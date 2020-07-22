---
layout: post
title:  "Update_1: Getting my shit together"
date:   2020-07-23 20:11:31 +0200
categories: meta, ramblings, updates
---

Hey, hace tiempo que no escribo nada. Hace un par de semanas el ordenador muri� (la placa base) y no me qued� m�s remedio que actualizar el rig. Bueno al menos ahora tengo Ryzen y 16GB de ram pero no dinero. Han sido semanas de arreglar cosas, organizar mis archivos de forma obsesivo compulsiva, leer y dem�s. Solo estos �ltimos cuatro d�as he empezado ya a hacer cosas. Aunque sinceramente creo que me obsesiono demasiado con "ser productivo" y todo eso. Mis archivos ahora son coherentes y eso significa que mi flujo de trabajo deber�a mejorar considerablemente. Tambi�n he estado instalando y configurando programas como el editor de texto que estoy usando para escribir esto, pero os ahorrare los detalles s�rdidos, son aburridos. Voy a ense�aros un poco lo que he estado haciendo


## Gamedev

He vuelto a engancharme a programar y hacer cosas con el pc. En concreto, llevo un tiempo ya trabajando con un amigo en un peque�o proyecto de juego indie que espero que vea la luz alg�n d�a. He estado programando un sistema de di�logo que lee archivos JSON para cargar las l�neas de di�logo y ense�arlas por pantalla. Est� muy verde pero fue genial el cargar las pruebas y ver como funcionaba. Aqu� un poco del c�digo escrito en GDScript para el motor Godot:

```func read_file() -> Dictionary:
	var fichero = File.new()
	var dialogo
	fichero.open("res://dialog/test1.json",File.READ)
	dialogo = parse_json(fichero.get_as_text())
	fichero.close()
	return dialogo
```
Esta funci�n lee un archivo JSON y lo devuelve como un diccionario.

Estoy pensando en presentarme a una gamejam que est� celebrando itch.io sobre juegos narrativos. Tengo una idea de historia pero est� muy verde, also tendr�a que hacer el artwork y eso si que me echa bastante para atr�s.

[La jam](https://itch.io/jam/i-cant-write-but-want-to-tell-a-story)

## Lectura

He le�do bastante pero ahora justo acabo de terminar *Silk* de Caitl�n. R. Kiernan. Es una novela de terror ambientada en la subcultura punk y g�tica de la am�rica de los 90. A ratos no sab�a si ponerle un diez o si me estaban tomando el pelo. La he terminado justo hoy y la verdad es que todav�a no tengo claro si me ha gustado o no, pero creo que ha valido la pena. Hoy me empezar� *La narraci�n de Arthur Gordon Pym* la �nica novela de Poe, a ver que tal.

Y por favor, de Kiernan leeos si o si *The drowning girl*, ese libro me ha fascinado.

## Escribir

Hoy he estado rematando un peque�o relato que ten�a aparcado de hace bastante tiempo. En breves subir� alguno.

Bueno, creo que de momento es todo, en breves subir� alguna historia y seguir� por aqu�. A ver si revivo en twitter. Quer�a ense�aros algunas im�genes y corregir un poco el texto pero me duelen los dedos de teclear hoy y adem�s creo que estoy enfermo (No creo que sea COVID). As� que ya nos leemos a la pr�xima.

Thanks!

PD: Creo que enlazar� mi goodreads o algo, estoy bastante activo por ah� �ltimamente.

PD2: Estos escritos no tienen formato ni estilo, sorry. Es el fluir de mis pensamientos y sal� as�.