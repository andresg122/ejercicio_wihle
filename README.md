# ejercicio_wihle
~~~
inicio 
  n <= o
  c <= 0
  p <= 0
  t <= 0
  MQ t <= 3000000
    lea "cuanto va abonar ?", f
    Si f > 0 entonces 
      n <= n + 1 
      t <= t + f 
      Si f > = 10000 entonces 
        p <= p + 1 
      fin Si 
    Sino 
      c <= c + 1
    fin Si 
  fin MQ
  pr = t / n 
  esc "El total de aportes es de &" + t
  esc "El promedio de los aportes es de $" + pr
  esc "La cantidad de estudiantes que donaron" + n + " estuantes"
  esc "La cantidad de estudiantes que no donaron" + c + " estuantes"
  esc "Los estudiantes que aportaron más que $10.000" + p + " estudiantes"
  esc "se ha alcanzado la meta "
fin   
~~~
 ### Diagrama de flojo 
 
<a href="https://ibb.co/ft0PvMV"><img src="https://i.ibb.co/rMy1skK/ab81c033-5618-4277-9239-406b00884bac.jpg" alt="ab81c033-5618-4277-9239-406b00884bac" border="0"></a>
