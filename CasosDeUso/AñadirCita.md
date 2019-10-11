### **Añadir cita**
**ID:** 008 **Descripción:** Se añade una cita con el paciente.

**Actores principales:** Secretaría

**Precondiciones:**
>* El paciente debe estar registrado.

**Flujo principal:**
>1. El Secretario quiere añadir una cita.
>2. El sistema comprueba la existencia del paciente.
>3. Introduce los datos requieridos de la cita.

**Postcondiciones:**
>* Se guardan los datos de la nueva cita en la lista de citas.

**Flujos alternativos:**
>2.a. Si existe el paciente, se muestra un mensaje de que ya existe.

>3.a. Si no rellena los campos obligatorios, se muestra un mensaje de que no ha añadido.
