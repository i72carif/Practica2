### Añadir tratamiento
**ID:** 009
**Descripción:** El secretario añade un nuevo tratamiento al paciente.

**Actores principales:** Secretaría.   

**Precondiciones:**
>+  El paciente debe existir en el sistema.

**Flujo principal:**
>1. El caso de uso comienza cuando el secretario quiere añadir un nuevo tratamiento a un paciente.
>2. El sistema hace una búsqueda del paciente.
>3. El secretario introduce en el sistema el nuevo tratamiento del paciente.


**Postcondiciones:**
>+ El sistema guarda el tratamiento nuevo del paciente aunque ya tenga otro.

**Flujos alternativos:**
>2.a. Si el paciente buscado no existe, salta un mensaje de error donde explica que el paciente buscado ya no existe.   
