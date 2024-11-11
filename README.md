# Caso de Uso: Ver a un Médico en la Clínica San Juan

## Actores:
- **Paciente**
- **Médico**

## Descripción:
Este caso de uso describe el proceso en el que un paciente visita al médico para una consulta en la Clínica San Juan.

## Precondiciones:
- El paciente debe estar registrado en el sistema.
- El paciente tiene una obra social válida.

## Flujo Principal:
1. El paciente ingresa a la clínica y se registra en el sistema si no está registrado.
2. El paciente solicita una cita con un médico disponible y elige la fecha y hora.
3. El sistema verifica la disponibilidad del médico y confirma la cita.
4. El paciente llega a la cita y es atendido por el médico.
5. El médico realiza la consulta y proporciona recomendaciones si es necesario.
6. El paciente paga por la consulta, ya sea a través de su obra social o de forma directa.
7. El sistema emite una factura por los servicios prestados, incluyendo detalles de la obra social si corresponde.

## Flujo Alternativo:
- Si el paciente no tiene obra social, se le cobra el monto completo de la consulta.

## Postcondiciones:
- La consulta se registra en el sistema.
- El paciente tiene una factura generada.

## Requerimientos Especiales:
- El sistema debe manejar tanto pagos directos como pagos por obra social.
