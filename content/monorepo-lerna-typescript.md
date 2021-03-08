+++
title = "Monorepo lerna + typescript"
description = "Monorepo lerna + typescript"
date = 2021-03-05
draft = true
[taxonomies]
tags = ["react", "lerna", "typescript", "monorepo"]
[extras]
+++

![](https://images.unsplash.com/photo-1547954575-855750c57bd3?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MXwxNDIyNzR8MHwxfHNlYXJjaHwyM3x8Y29kZXxlbnwwfHx8&ixlib=rb-1.2.1&q=80&w=1080)

Este ultimo tiempo e estado codeando un proyecto, este lo empece de forma simple, pero a medida que fueron agregando funcionalidades o posibles utilidades me di cuenta que ya no podía ser un simple proyecto. Así que investigando llegue a los Monorepos.

En este Post les quiero contar cual fue mi motivación por pasar mi proyecto a **monorepo** y mi experiencia en el camino.

> *Este proyecto se esta desarrollando dentro de mi trabajo, así que por esta razón no podré por ahora mostrar código de este. Pero no te preocupes, que intentare ejemplificar con ejemplos libres.*

## Definamos que son los **Monorepos**

> In revision control systems, a **monorepo** ("mono" from Greek μόνος, mónos, 'single, alone' and "repo" short for repository "Repository (version control)")) is a software development strategy where code for many projects is stored in the same repository "Repository (version control)").
> 
>  — <cite>[https://en.wikipedia.org/wiki/Monorepo](https://en.wikipedia.org/wiki/Monorepo)</cite>

Un mono repo es un repositorio que en su interior maneja N cantidad de paquetes relacionados entre si dentro de un mismo scope, este scope sigue la misma lógica que los de npm, los cuales pueden ser para definir una empresa o los módulos que pertenecen a una misma solución.

## Mi experiencia

En un momento te explicare cual es el ambiente que utilicé y como son los primeros pasos para armar este ambiente. Pero por ahora te comentare el por que tome la decisión de que mi proyecto sea un **monorepo**.

En es te caso mi experiencia es desde un proyecto que ya estaba iniciado, que ya tenia una lógica y un set de características ya pensadas, así que ten esto en cuenta ya que el iniciar un proyecto directamente como **monorepo** en mi opinión no es lo mismo, por que cuando empiezas un proyecto o una solución desde 0 puede que no tengas claro cuales son sus alcances o sus funcionalidades.

Como te comentaba, mi proyecto inicio de forma simple, solo se buscaba solucionar un dolor al momento de generar un template de correo y con el tiempo se le a añadido una mayor complejidad y posible usos, tanto así que ahora lo pienso mas como un mini framework que como una herramienta temporal.

