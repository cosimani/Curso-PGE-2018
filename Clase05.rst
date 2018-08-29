.. -*- coding: utf-8 -*-

.. _rcs_subversion:

Clase 05 - PGE 2018
===================
(Fecha: 30 de agosto)

**Clase genérica con argumento por defecto**

.. figure:: images/clase03/por_defecto.png

**Declaración adelantada**

.. figure:: images/clase03/declaracion_adelantada.png

**Miembros estáticos**

.. figure:: images/clase03/miembros_estaticos.png


Ejercicio 4:
============

- Definir la clase LineaDeTexto que herede de QLineEdit
- Sobrecargar el operator+ operator= y el contructor copia para que se puede ejecutar la siguiente línea de código:
	
.. code-block:: c
	
	linea = linea1 + linea2;  
	// Los tres son objetos LineaDeTexto y la suma devuelve un LineaDeTexto con los textos concatenados
	

Ejercicio 5:
============

- Incorporar LineaDeTexto a un proyecto de Qt para promocionarlo en QtDesigner
- Crear un Formulario con QtDesigner que tenga 4 LineaDeTexto promocionadas
- El formulario será para alta de personas
- Un campo para Nombre, otro para Apellido, para DNI y uno para Nombre completo.
- Esta última LineaDeTexto concatenará en tiempo real el nombre y apellido usando el operator+ de LineaDeTexto


MiniExamen de preguntas múltiples
=================================

:Tarea para Clase 6:
	Completar y estudiar exhaustivamente la clase Listado

	Estudiar sobrecarga de operadores y templates

	Ver `Tutorial Qt QVector <https://www.youtube.com/watch?v=Z9u2yDPh57U>`_ de `Videos tutoriales de Qt <https://www.youtube.com/playlist?list=PL54fdmMKYUJvn4dAvziRopztp47tBRNum>`_

	Ver `Tutorial Qt QList <https://www.youtube.com/watch?v=xx5wIjUwlg8>`_ de `Videos tutoriales de Qt <https://www.youtube.com/playlist?list=PL54fdmMKYUJvn4dAvziRopztp47tBRNum>`_

	Ver `Tutorial C++ vector <https://www.youtube.com/watch?v=dNb468_AJQI>`_ de `Videos tutoriales de C++ <https://www.youtube.com/playlist?list=PL54fdmMKYUJvS32aLptKVC0AH9bwsavzi>`_


