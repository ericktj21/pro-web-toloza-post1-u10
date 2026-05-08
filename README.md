# U10 Post 1 - Suite de pruebas con JUnit, Mockito y JaCoCo

## Requisitos
- Java 17
- Maven 3.9+

## Estructura
- src/main/java/com/proweb/tareas: entidad, repositorio, servicio y controlador
- src/test/java/com/proweb/tareas: pruebas unitarias, web y repositorio
- img/: capturas de evidencia

## Ejecutar pruebas
```bash
mvn test
```

## Cobertura JaCoCo
```bash
mvn clean test jacoco:check
```
Reporte: target/site/jacoco/index.html

## Evidencias (colocar en img/)
- img/checkpoint1.png (tests unitarios con Mockito)
- img/checkpoint2.png (tests @WebMvcTest y @DataJpaTest)
- img/checkpoint3.png (reporte JaCoCo)
