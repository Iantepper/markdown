# Caso de Uso: Ver a un Médico en la Clínica San Juan

| **Elemento**          | **Descripción**                                                                                 |
|-----------------------|-------------------------------------------------------------------------------------------------|
| **Actores**           | Paciente, Médico                                                                                 |
| **Descripción**       | El paciente visita a un médico en la clínica para una consulta. El médico atiende al paciente y se genera una factura. |
| **Precondiciones**    | - El paciente está registrado en el sistema.<br>- El paciente tiene una obra social válida.      |
| **Flujo Principal**   | 1. El paciente se registra en el sistema si no lo está.<br>2. El paciente solicita una cita con un médico.<br>3. El sistema verifica la disponibilidad del médico y confirma la cita.<br>4. El paciente llega a la cita y es atendido por el médico.<br>5. El médico realiza la consulta y ofrece recomendaciones si es necesario.<br>6. El paciente paga por la consulta (mediante obra social o pago directo).<br>7. El sistema emite una factura por los servicios prestados, incluyendo detalles de la obra social si corresponde. |
| **Flujo Alternativo** | - Si el paciente no tiene obra social, se le cobra el monto completo de la consulta.             |
| **Postcondiciones**   | - La consulta se registra en el sistema.<br>- El paciente recibe la factura generada.           |
| **Requerimientos Especiales** | - El sistema debe gestionar pagos directos y pagos por obra social.                  |
