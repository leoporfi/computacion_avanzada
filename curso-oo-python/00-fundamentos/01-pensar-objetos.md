# 🎯 **Enunciado “detective de objetos”**  
(Formato historia corta + ficha de trabajo)

---

### 📖 **Historia: “El caos del sábado en la pizzería de Don Luca”**  

> Llegó el mediodía del sábado y la puerta de “Don Luca” no paraba de sonar.  
> Primero entró **Julieta**, que siempre pide una *Margarita* sin albahaca.  
> Después **el señor Oscar** pidió dos *Napolitanas* para llevar y dejó su número de socio en la tarjeta fidelización.  
> Mientras tanto, **Matías** (el cadete) anotó en un papelito: *“calle 59 nº 1230, dos pizzas, $3 200”* y salió pitando.  
> En la cocina, **Luis** extendió masa, le puso salsa, muzza y rodajas de tomate; cuando terminó, le gritó a **Carla** (cajera): *“¡La de Julieta está lista!”*.  
> Carla anotó con una tilde verde en la planilla *“Pedido 126 – Margarita – ENTREGADO”* y le dijo al cliente: *“Son $1 500, ¿efectivo o débito?”*.  
> A las 14:30 **Don Luca** sacó su calculadora y empezó a sumar los papelitos: *“Hasta ahora 126, 127, 128… y el total del día da $18 700”*.  
> De repente apareció **Matías** todo agitado: *“Perdí el papelito del 127, no sé cuánto cobrarle al cliente”*.  
> Don Luca suspiró: *“Otra vez lo mismo… necesitamos un sistema que no dependa de mis sumas y de la memoria de Matías”*.

---

### 🔍 **Ficha de trabajo: “Convertí el caos en código”**

1. **Subrayá** (o resaltá) en el texto **cada sustantivo** que creas que debe convertirse en una **clase**.  
   *Ejemplo: ya está hecho con **Julieta** → clase `Cliente`.*

2. **Encontrá los verbos** que describen **acciones** que esas clases deberían hacer.  
   *Ejemplo: “anotó” → método `agregar()`, “cobrar” → método `cobrar()`.*

3. **Agrupá** los sustantivos que parecen **lo mismo**; elegí un nombre único para la clase.  
   *Ejemplo: papelito, planilla, número 126 → todo es parte de `Pedido`.*

4. **Escribí al lado de cada clase qué datos necesitás guardar de ella**.  
   *Ejemplo: `Pizza` → nombre, precio_base, ingredientes.*

5. **¿Qué número aparece más veces?** Ese será tu **identificador único** (`id` o `número_de_pedido`).

6. **¿Qué reglas de negocio encontrás?**  
   - *“Dos pizzas”* → un pedido puede tener **más de una pizza**.  
   - *“$3 200”* → hay que **calcular un total**.  
   - *“Sin albahaca”* → los **ingredientes pueden variar**.

7. **Dibujá un mini-diagrama** (cajitas y flechas) con las clases que descubriste.

---

### ✅ **Lista rápida de verificación** (auto-evaluación)
| Pregunta | ¿Lo hiciste? |
|----------|--------------|
| ¿Identificaste al menos 3 clases? | ☐ |
| ¿Alguna tiene un método que calcule algo? | ☐ |
| ¿Viste la necesidad de un “número” único? | ☐ |
| ¿Anotaste quién depende de quién? (ej. Pedido usa Pizza) | ☐ |

---

### 🎨 **Versión creativa para pegar en el aula**
> **“Cada historia es un rompecabezas de objetos. Tu misión: sacar las piezas sin que Don Luca pierda la cuenta otra vez”**.

*(La semana que viene transformaremos esas piezas en código Python real.)*
