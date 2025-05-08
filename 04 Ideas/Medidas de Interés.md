Materia:: [[Ingeniería Económica]]

 "El peso de hoy no es equivalente al peso del mañana"

El cambio del dinero a través del tiempo. 
*modelos* que describen cómo es la compensación a través del tiempo. 
### Modelo de interés 
- Interés simple
- Interés compuesto
### Modelo de descuento 
- Descuento simple 
- Descuento compuesto 
### Modelo de fuerza de interés 
- Fuerza de interés constante 
- Fuerza de interés variable 
## Función de acumulación
Es la que describe el valor del dinero a través del tiempo
$$a(t)\text{   }, t \geq 0$$
Nos va a indicar el valor de 1 unidad monetaria en $t$ 


- El tiempo siempre va en el eje horizontal 
- La gráfica representa el valor del dinero $a(t)$ en el tiempo ($t$)
### Propiedades de $a(t)$
1. En $t = 0$, $a(t)= 1$; Por lo tanto $a(0) = 1$
2. Si el interés es cada periodo es positivo, la función será creciente ($i \geq 0$, $a(t)$ es creciente)
3. Si el interés se pasa de forma continua, $a(t)$ es función continua. 
 - [ ]  Insertar la Gráfica faltante 

> "El saldo se mantiene constante en cada periodo, aumenta cuando se ganan intereses"


> " Representa que el dinero cambia constantemente en el tiempo"

**Tasa de interés**: La cantidad de dinero que será pagado al final de un periodo cuando una cantidad inicial de dinero es invertida en $t= 0$

![[Pasted image 20240123184444.png]]

$$\begin{matrix}
a(0) = 1, I_1 = a(1)- a(0) = 1.04 - 1 = 0.04 \\
a(1) = 1.04, I_2 = a(2)- a(1) = 1.07 - 1.04 = 0.03 \\
a(2) = 1.07, I_3 = a(3) - a(2) = 1.12 - 1.07 = 0.05
\end{matrix}$$
Donde: 
$I =$ Monto de interés 


$$
i_2 = \frac{1.04 -1}{1}= 0.04(100) = 4 \% 
$$ 
Definición tasa de interés efectiva en el t-esimo periodo $[t-1,t]$ 
- Indica el porcentaje (de forma decimal) de cambio en un periodo 
 $$
i_t = \frac{a(t)-a(t-1)}{a(t-1)} \\
i_2 = \frac{a(2)- a(2-1)}{a(2-1)} \\
 ''= \frac{a(2)-a(1)}{a(1)} \\
''= \frac{1.07 - 1.04}{1.04} = \frac{0.03}{1.04} = 0.0288 \\
i_3= \frac{1.12-1.07}{1.07} = \frac{0.05}{1.07} = 1.67 \\
$$

$$\frac{\text{Monto de intereses ganado}}{\text{Monto al inicio del periodo}}$$
- Es aquí donde es evidente que para obtener el monto de intereses ganado es muy fácil obtenerlo mediante la diferencia entre el monto obtenido en el periodo actual menos el anterior (Para así dejar únicamente lo obtenido por los intereses) 

$$\text{Inversión inicial} = \text{Capital} = \text{K}$$
## Función de monto 
$$\text{"Amount Function"} = A(t)$$
Denotará el monto acumulado a tiempo $t$ de la cantidad $K$ invertida en el tiempo $0$ 
$$A(0)= K$$
$$A(0) = K\frac{a(0)}{1}$$
$$A(t) = Ka(t)$$
- La última es la fórmula que se emplea para obtener la Función de monto, lo anterior son solo comprobaciones
- Como $a(0) = 1 \rightarrow A(0)= Ka(0)= K$
$$ I_t = A(t)- A(t-1) = \text{Ganancia} $$
$$i_t = \frac{A(t)- A(t-1)}{A(t-1)} = \text{Tasa de interés}$$
$$I_1 = 504-500 = 4 = A(1)- A(0)$$
$$i_1 = \frac{504-500}{500} = 8 \times 10^{-3} = 0.8\%$$
