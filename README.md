# Laboratorio 5: Inductor y capacitor
Integrantes: Caillamara Leonardo, González Ariel
## 1. OBJETIVOS

### Objetivo general:
* Comparar el comportamiento de capacitores e inductores en circuitos AC y DC por medio de la experimentación. 

### Objetivos específicos:
*	Medir valores de V0 y corriente en AC y DC 
*	Interpretar el comportamiento de la señal en circuitos AC mientras existe una variación de frecuencias.

## 2. MARCO TEÓRICO

### Capacitores e inductores

#### Capacitores

Un capacitor es un componente del circuito eléctrico cuya principal característica es almacenar energía a modo de campo eléctrico.

Básicamente un capacitor consta de dos placas conductoras separadas por un dieléctrico.

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Capacitor.png)

#### Inductores

Un inductor es un componente perteneciente a un circuito eléctrico cuya principal característica es almacenar energía como campo magnético. Los inductores están constituidos por un alambre enrollado alrededor de un núcleo.

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Inductor.png)


## 3. EQUIPOS Y MATERIALES

* **Proteus:** Programa de simulación de circuitos.
* **Protoboard:** Es una placa de pruebas en la que se pueden insertar elementos electrónicos. En este caso Proteus utiliza un plano infinito como protoboard.
* **Resistencias eléctricas:** Elemento eléctrico que se opone al paso de corriente.
* **Cables puente:** Cables de ayuda para realizar conexiones provisionales.
* **Multímetro:** Es un instrumento analógico o digital portátil que se usa para medir directamente magnitudes eléctricas.
* **Fuente AC:** Dispositivo que provee energía a un circuito  de corriente alterna.
* **Capacitor e inductor:** Componentes eléctricos revisados en el marco teórico de este trabajo.

## 4. PROCEDIMIENTO

4.1 Construya en el circuito mostrado en la Figura 1. 

a. Utilice el osciloscopio para observar el voltaje 𝑉o variando la frecuencia entre los
valores de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los valores pico de las ondas observadas.

b. Utilice un multímetro para medir el voltaje 𝑉􀯢 variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.

c. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la frecuencia entre los valores 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Figura1.png)

4.2 Construya el circuito mostrado en la Figura 2 y realice las mismas mediciones de los ítems del numeral anterior y presente los resultados.

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Figura2.png)

## 5. TABLAS DE MEDICIÓN Y CÁLCULOS

### Tabla 5.1 Medición de voltaje Vo y corriente de la figura 1.

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Capacitancia0.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Capacitancia10.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Capacitancia50.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Capacitancia100.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Capacitancia500.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Capacitancia1000.png)

### Tabla 5.2 Medición de voltaje Vo y corriente de la figura 2.

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Inductancia0.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Inductancia10.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Inductancia50.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Inductancia100.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Inductancia500.png)

![](https://github.com/ArielAGH/Laboratorio5/blob/main/Img/Inductancia1000.png)

Los cálculos respectivos están en la carpeta denominada Cálculos y las simulaciones realizadas en la carpeta Anexos. Para el cálculo del error en cada caso se usa la siguiente fórmula:

![](https://github.com/KevinCaillamara/Laboratorio_2/blob/main/Im%C3%A1genes/formula_error.png)


## 6. ANÁLISIS DE RESULTADOS

1.- Para cada uno de los circuitos anteriores, elabore una tabla con los resultados de las diferentes mediciones de voltaje realizadas con el osciloscopio, multímetro y las
calculadas en el trabajo preparatorio. Compare y comente los resultados obtenidos
tomando en cuenta las distintas frecuencias utilizadas.

En todo el experimento se pudo apreciar el aumento de la amplitud  en Vo a medida que  aumentaba la frecuencia  en la fuente de poder. 
Cuando la frecuencia  se colocaba en 0 Hz (continua) automáticamente no existían lecturas de voltaje y corriente esto es debido a que idealmente  y según lo calculado  para encontrar reactancia inductiva  y capacitiva   se puede determinar que con frecuencia cero  XL es cero  y Xc  tiende al infinito pero para este ultimo en la simulación se toma como cero.

2.- En cada uno de los circuitos anteriores, utilice los resultados de las mediciones de corriente y el voltaje realizados con el multímetro para calcular la reactancia 𝑋 = (Vo/I)en cada una de las frecuencias y también para calcular los valores de 𝐿eq y 𝐶eq según sea el caso.

Los cálculos requeridos para los datos solicitados se encuentran en la carpeta Cálculos.

## 7. PREGUNTAS

### 1.- Justifique los errores cometidos en las mediciones.

Los errores encontrados en esta práctica son debido a que al momento de calcularlos influye mucho los decimales que son utilizados, además de que la sensibilidad del propio simulador no es tan buena, aún así el simulador cumple con su cometido.

### 2.- ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

En corriente continua el comportamiento del capacitor primero se carga al máximo luego  actúa como un circuito abierto en cambio la bobina cuando está totalmente cargada funciona como un cortocircuito entre sus dos terminales.
  
### 3.- ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

Ambos tienen un comportamiento de carga y descarga en función de la onda que los atraviesa, es decir que cuando el valor de la onda es mayor el capacitor se carga de tensión y cuando el valor de la onda es menor empieza a descargarse entregando tensión. Para las bobinas es un proceso igual pero estas se cargan generando un campo magnético. 

### 4.- ¿Qué cree usted que ocurriría con el voltaje 𝑉o y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

Únicamente la impedancia variaría. Dependiendo de los valores de dichos capacitores e inductores ya que estos formarían una impedancia equivalente. En el circuito que tiene incluido capacitores la tensión se retrasa y mientras que en el circuito donde utilizan bobinas la corriente es la que se retrasa. Esto sucede debido a que el capacitor tiene cierta oposición al paso de la tensión porque este debe cargarse por ende existe dicho retraso, mientras que las bobinas en cambio tienen cierta oposición al paso de la corriente.

### 5.- ¿Qué son los valores eficaces de voltaje y corriente?

Es el valor útil que el circuito aprovecha es decir es la misma tensión o corriente que el circuito usaría si este fuera alimentado con una fuente DC.

## 8. CONCLUSIONES

En conclusión, los circuitos que incluyen capacitores o inductores influyen directamente en el ángulo de desfase entre la corriente y la tensión.

El comportamiento de inductores y capacitores es distinto en corriente continua como alterna, pero lo más destacable es que en corriente continua estos elementos se mantienen cargados mientras que en corriente alterna existe una continua carga y descarga de dichos elementos.

## 9. BIBLIOGRAFÍA

* Durán, J. (2012). *Electrotecnia*. Barcelona: Editorial Lexus.
* Fraile, J. (2012). *Circuitos eléctricos*. Madrid: Editorial Pearson.
* Maldonado, A. (2016). *Tecnología eléctrica*. Quito: Poli Ediciones.
* Sadiku, M. (2006). *Fundamentos de circuitos eléctricos*. México: Editorial Mc Graw Hill.
* Thomas, L. (2007). *Principios de circuitos eléctricos*. México: Editorial Pearson.
