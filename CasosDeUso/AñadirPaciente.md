### **Añadir paciente**
**ID:** 001 **Descripción:** Se añaden los datos de un nuevo paciente.

**Actores principales:** Secretaría

**Precondiciones:**
>* El paciente no debe estar registrado.

**Flujo principal:**
>1. El Secretario quiere agregar un nuevo paciente.
>2. El sistema comprueba la existencia del paciente.
>3. Introduce los datos basicos del paciente pedidos por el sistema.

**Postcondiciones:**
>* Se guardan los datos del nuevo paciente y se crea un historial vacío.

**Flujos alternativos:**
>2.a. Si existe el paciente, se muestra un mensaje de que ya existe.

>3.a. Si no rellena los campos obligatorios, se muestra un mensaje de que no ha añadido.
