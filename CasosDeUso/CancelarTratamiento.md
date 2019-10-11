### Cancelar tratamiento
**ID:** 010
**Descripción:** El secretario cancela un tratamiento al paciente.

**Actores principales:** Secretaría.   

**Precondiciones:**
>+  El paciente debe existir en el sistema.

**Flujo principal:**
>1. El caso de uso comienza cuando el secretario quiere cancelar un tratamiento a un paciente.
>2. El sistema hace una búsqueda del paciente.
>3. El secretario selecciona el tratamiento de dicho paciente que quiere terminar y lo cancela.


**Postcondiciones:**
>+ El sistema cancela solo el/los tratamientos del cliente que el secretario haya seleccionado.

**Flujos alternativos:**
>2.a. Si el paciente buscado no existe, salta un mensaje de error donde explica que el paciente buscado ya no existe.
