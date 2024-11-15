# Python

Python es uno de los lenguajes de programación con más crecimiento en los últimos años, su campo de aplicación es tan amplio que ve desde la robótica hasta el desarrollo web, ciberseguridad e Inteligencia Artificial

## Temario

### Conceptos Basicos

* Sintaxis
* Data Types

### Manejo de datos

* Base de datos
* ORM

### Matematicas

Las bases de matematicas son importantes acontinuacion dejo material de estudio en khanacademy

* [Álgebra 1 | Matemáticas | Khan Academy](https://es.khanacademy.org/math/algebra "‌")
* [Álgebra 2 | Matemáticas | Khan Academy](https://es.khanacademy.org/math/algebra2 "‌")
* [Cálculo avanzado 1 (AP Calculus AB) | Matemáticas | Khan Academy](https://es.khanacademy.org/math/ap-calculus-ab "‌")
* [Cálculo avanzado 2 (AP Calculus BC) | Matemáticas | Khan Academy](https://es.khanacademy.org/math/ap-calculus-bc "‌")
* [Álgebra lineal | Matemáticas | Khan Academy](https://es.khanacademy.org/math/linear-algebra "‌")

# Huggin Face

Hugging Face, es de las empresas y plataformas más importantes en el boom de la IA, podemos definir la plataforma como un repositorio tipo github de modelos, esta plataforma tambien nos ofrece librerias y hasta infraestructura cloud para trabajar con modelo de AI.

## Temario

### Huggingface hud

* Crea una cuenta en https://huggingface.co/
* spaces : Esta es una herramienta para implementar demos de ML, a grades rasgos es nos permite desplegar proyectos pequeños con AI https://huggingface.co/docs/hub/spaces-overview
* spaces : Esta es una herramienta para implementar demos de ML, a grades rasgos es nos permite desplegar proyectos pequeños con AI https://huggingface.co/docs/hub/spaces-overview

### Huggingface Api

* Proyecto 1 : Utilizando una api de hugginface de un modelo llm crea una aplicacion donde el usuario pueda pueda realizar preguntas y el modelo le responda.
* Proyecto 2 : implemente multiples modelos, utilizando la api cree una clase que le permite iterar de un modelo llm a otro.

### Introduccion a Transformers

Transformer se presentó por primera vez en la [Attention is all you need](https://dl.acm.org/doi/10.5555/3295222.3295349) en 2017 por Vaswani et al.

* Los modelos de transformador funcionan según el principio de predicción de la palabra siguiente
    * Los Transformers no solo predicen la palabra siguiente, pero este princio es clave en los modelo GPT que se usan en ChatGPT
    * A partir de un mensaje de texto del usuario, el modelo puede inferir cuál es la palabra más probable que seguirá a esta entrada.
*  Arquitectura de un modelo de transformador
    * Embedding
        * La entrada de texto se divide en tokens
        * Los tokens son vectores numéricos
        * Captan el significado semántico de las palabras
        * embeddings posicionales
    * Transformer Block
        * Procesa y transforma los datos de entrada
        * Cada bloque incluye
        * Mecanismo de atención
            * Es un componente clave de los Transformers que calcula qué partes del texto son más relevantes en un contexto dado.
            * La atención incluye una operación matemática llamada atención escalada por productos punto (scaled dot-product attention).
            * Identifica relaciones entre palabras
        * Capa MLP (perceptrón multicapa)
            * Una red feed-forward
                * Procesa la información en una dirección, de la entrada a la salida, sin bucles ni conexiones de retroalimentación.
            * MLP procesa tokens de forma independiente.
            * Enruta la información entre los tokens.
            * Refina la representación de cada token
* Probabilidades de salida:
    * Utiliza capas lineales y softmax
    * Transforma las incrustaciones procesadas
    * Genera probabilidades
    * Permite predecir los tokens siguientes

# Ingeniería de Prompt

La Ingeniería de Prompt es la práctica de diseñar, estructurar y optimizar las entradas (o prompts) utilizadas para interactuar con modelos de lenguaje, como los de OpenAI o Hugging Face, con el fin de obtener respuestas precisas, relevantes y alineadas con un objetivo específico.

En esencia, es el arte y la técnica de "hablar" con un modelo de IA para aprovechar al máximo su capacidad.

