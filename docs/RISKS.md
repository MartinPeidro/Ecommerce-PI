# Riesgos globales


1. **Validación incompleta**: El script valida formatos básicos, pero no garantiza que los datos existan en la realidad (ejemplo: un email puede tener  formato correcto pero no existir).
2. **Errores humanos**: Si el usuario introduce datos en un idioma o formato no contemplado, puede fallar la validación.
3. **Dependencia de expresiones regulares**: Si las regex no están bien diseñadas, podrían permitir valores incorrectos.
