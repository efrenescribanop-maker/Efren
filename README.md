Algoritmo CalificacionesPromedio
    Definir nota1, nota2, nota3, promedio Como Real
    Escribir "Escribe la primera calificación"
    Leer nota1
    Escribir "Escribe la segunda calificación"
    Leer nota2
    Escribir "Escribe la tercera calificación"
    Leer nota3
    promedio <- (nota1 + nota2 + nota3) / 3
    
    Escribir "Calificación 1 es: ", nota1
    Escribir "Calificación 2 es: ", nota2
    Escribir "Calificación 3 es: ", nota3
    Escribir "El promedio es: ", promedio
    
    Si promedio >= 7.0 Entonces
        Escribir "APROBADO"
    Sino
        Escribir "NO APROBADO"
    FinSi
    
FinAlgoritmo
