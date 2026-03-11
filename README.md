### <em>Ejercicio Integrador Intermedio</em>
# <b>Validador de Correlativas</b>

### Se proponen los siguientes pasos:

1 - Implementar el diseño en un proyecto Maven.

2 - Generar 2 tests para el método Inscripción#aprobada:
  - Una materia sin correlativas
  - Una materia con correlativas y que el alumno las tenga
  - Otra materia sin correlativas, y que el alumno no las tenga
  
3 - Finalmente implementar el programa, puede seguir el siguiente esquema:

``` java
public static void main(String[] args) {
// Inicializar materias: crear 3 o 4 materias, con y sin correlativas
entre ellas
Collection<Materia> materias = … ;
// Inicializar los alumnos, crear 2 o 3 alumnos, con y sin materias
aprobadas.
// Usar para las materias los MISMOS objetos de la colección de más
arriba
Collection<Alumno> alumnos = … ;
// Leer el archivo parado por parámetros de args y por cada línea
// instanciar un objeto Inscripción, pero para llenar las materias y
alumnos DEBE usar los objetos que creo más arriba
// Imprimir la línea, con el resultado si la inscripción está o no ok
}
```

