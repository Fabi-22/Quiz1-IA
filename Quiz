# Actividad de Clase: Analizando Agentes de IA con Hugging Face Spaces

## Objetivo

Explorar aplicaciones reales de Inteligencia Artificial en **Hugging
Face Spaces** y analizarlas desde la perspectiva de los **agentes
racionales**.

Al finalizar la actividad, los estudiantes deberán ser capaces de:

-   Identificar los componentes **PEAS** de un agente.
-   Clasificar las propiedades del entorno.
-   Proponer qué tipo de programa de agente podría implementarse detrás
    del sistema.
-   Justificar sus respuestas.

------------------------------------------------------------------------

## Instrucciones

1.  Ingresen a **https://huggingface.co/spaces**.
2.  Exploren diferentes Spaces.
3.  Seleccionen uno que les parezca interesante.
4.  Interactúen con el sistema durante algunos minutos.
5.  Completen la siguiente ficha de análisis.

------------------------------------------------------------------------

# Ficha de análisis

## 1. Nombre del Space Editor Omni 2.0

**Nombre:** Fabiola Valencia Barrios 

**Enlace:** https://huggingface.co/spaces/selfit-camera/Omni-Image-Editor

------------------------------------------------------------------------

## 2. ¿Qué hace el agente?

Describa en dos o tres líneas cuál es la función del sistema.

El sistema te pide que cargues una imagen la cual necesita alguna edición, describes exactamente que necesitas eliminar, cambiar, editar o añadir y el lo realiza, te da una imagen nueva con el cambio solicitado.

------------------------------------------------------------------------

## 3. Análisis PEAS

  Elemento          Respuesta
  ----------------- ----------------------------------------------------
  **Performance**   ¿Qué significa que el agente haga bien su trabajo?
  Que la edición solicitada se realice correctamente, que el resto de la imagen no se distorsione, que el resultado se vea bien y de buena calidad (nota el mensaje, y que lo haga rápido.

  **Environment**   ¿Con qué interactúa el agente?
  La interfaz web de Hugging Face Space, la imagen subida y el texto de instrucción escrito.

  **Actuators**     ¿Qué acciones produce?
  La generación y visualización de la imagen editada; también la opción de "Usar como entrada" para añadir otra edición.

  **Sensors**       ¿Qué información recibe como entrada?
  La imagen cargada y el texto de instrucción de la edición que se necesita.

------------------------------------------------------------------------

## 4. Clasificación del entorno

Complete la siguiente tabla y justifique brevemente cada respuesta.

  Propiedad      Clasificación     Justificación
  -------------- ----------------- ---------------
  Observable     Parcial.          El agente solo ve la imagen y el texto que el usuario le da; no conoce el contexto completo, puede darle una instrucción ambigua. 
  Determinista   No                Tiene componentes aleatorios, la misma instrucción sobre la misma imagen puede producir resultados ligeramente distintos cada vez.
  Episódico      Sí                Cada edición es independiente; se sube una imagen, se pide un cambio, se entrega un resultado.
  Estático       Sí                Mientras el agente edita, la imagen no cambia sola ni aparecen nuevos datos externos.
  Discreto       Sí                El usuario elige entre instrucciones y botones concretos, es decir opciones limitadas, no valores infinitos.
  Conocido       Sí                El funcionamiento del sistema es conocido por quienes lo diseñaron, es decir conteien reglas y modelo definidos.

------------------------------------------------------------------------

## 5. ¿Qué tipo de programa de agente creen que es?

Seleccione la opción que consideren más adecuada y explique por qué.

-   Agente de reflejo simple
-   Agente basado en modelo
-   Agente basado en objetivos
-   Agente basado en utilidad
-   Agente con aprendizaje

> **Importante:** No existe una única respuesta correcta. Lo importante
> es justificar la elección a partir del comportamiento observado.

Pra mi en este caso Agente basado en objetivos, ya que el sistema recibe un objetivo explícito por parte del usuario y genera una acción orientada específicamente a cumplir ese objetivo, en lugar de reaccionar con una regla fija. El agente debe entender qué se le pide y planear cómo transformar la imagen para lograrlo, evaluando si el resultado cumple con lo solicitado. 

------------------------------------------------------------------------

# Discusión en clase

Después de las presentaciones, discutiremos preguntas como:

-   ¿Dos Spaces diferentes pueden compartir el mismo tipo de entorno?
-   ¿Es posible saber con certeza qué tipo de agente implementa un Space
    únicamente observándolo?
-   ¿Qué diferencia existe entre el comportamiento observable de un
    agente y su implementación interna?

------------------------------------------------------------------------

# Reto adicional

Encuentre un Space que pueda clasificarse como:

1.  **Totalmente observable, determinista y episódico.**
Space: Perceiver Image Classification.
Enlace: https://huggingface.co/spaces/nielsr/perceiver-image-classification
Este Space permite subir una imagen para descubrir sus categorías más probables, ya que el modelo analiza la imagen y devuelve las 5 clasificaciones posibles principales.
Totalmente observable: ve toda la imagen completa, no le falta información.
Determinista: la misma imagen siempre da las mismas 5 categorías.
Episódico: cada imagen se clasifica sola, sin relación con las anteriores.

2.  **Parcialmente observable, estocástico y secuencial.**
Space: Gradio Chatbot (por gradio-templates)
Enlace: https://huggingface.co/spaces/gradio-templates/chatbot
En este Space se escribe un mensajes y opcionalmente se define un prompt de sistema, luego se ajusta la longitud de respuesta, la temperatura y el top-p para moldear las respuestas de la IA.

Parcialmente observable: solo conoce el texto escrito, no toda la intención del usuario.
Estocástico: la temperatura configurable hace que la misma pregunta pueda dar respuestas distintas.
Secuencial: cada respuesta depende de los mensajes anteriores del chat.

------------------------------------------------------------------------

# Rúbrica (10 puntos)

| Criterio | Puntos |
|-----------|:------:|
| Descripción correcta del Space | 2 |
| Identificación de PEAS | 3 |
| Clasificación del entorno | 3 |
| Justificación del tipo de agente | 2 |
| **Total** | **10** |

------------------------------------------------------------------------


