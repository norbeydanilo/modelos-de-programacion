# Proyecto final: asignación de casos (uso del docente)

**Curso:** Modelos de Programación

El proyecto final tiene **dos casos equivalentes**. Cada grupo recibe uno, con el enunciado completo (`23a` o `23b`). La rúbrica, el método, la entrega y la sustentación son idénticos.

## 1. Por qué los casos son equivalentes

Ambos casos tienen las mismas seis funcionalidades (F1 a F6) y el mismo banco de catorce problemas (P1 a P14), con la misma distribución por categoría. Solo cambia el vocabulario.

| Elemento | Caso A: NodoCowork | Caso B: CineAndes |
|---|---|---|
| Qué se ofrece | Espacios (escritorio, sala, auditorio) | Funciones en salas (2D, 3D, VIP) |
| Lo que se crea | Reserva | Compra de boletas |
| Complementos combinables (Decorator) | Servicios adicionales (proyector, café, grabación) | Combos de confitería (crispetas, gaseosa, nachos) |
| Variación de tarifa (Strategy) | Por hora, por día, membresía, promoción | General, estudiante, día del cine, socio |
| Tipos con reglas propias (Factory) | Tipos de espacio | Tipos de sala |
| Validaciones encadenadas (Chain) | Horario, aforo, disponibilidad, membresía | Función no iniciada, sillas libres, máximo de boletas, edad |
| Estados (State) | Pendiente, confirmada, cancelada, finalizada | Pendiente, confirmada, cancelada, utilizada |
| Sistema externo lento (Proxy) | Calendario externo | Cartelera del distribuidor |
| Paquetes anidados (Composite, extra) | "Piso completo" | "Combo familiar" o "maratón" |
| Datos de ejemplo mínimos | 4 espacios de 3 tipos | 4 funciones en 3 tipos de sala |
| Cambio en vivo posible | Nueva tarifa o nuevo servicio adicional | Nueva tarifa o nuevo combo |

## 2. Cómo asignar

Propongo una regla simple y verificable, para que nadie sienta que el caso fue escogido a conveniencia:

1. Ordenen los grupos por **número de inscripción** (o por orden alfabético del primer apellido del primer integrante).
2. Los grupos de **posición impar** reciben el **Caso A**, y los de **posición par** el **Caso B**. Así queda balanceado aunque el número de grupos sea impar (el último queda en A).
3. El caso **no se cambia** una vez asignado, salvo que el grupo proponga por escrito un caso propio y el docente lo apruebe (el enunciado lo permite).

Si prefieren un sorteo, escriban A y B en papeles (mitad y mitad) y que cada grupo saque uno en clase.

## 3. Tabla de asignación

| Grupo | Integrantes | Caso | Enlace al repositorio |
|---|---|---|---|
| 1 | | A | |
| 2 | | B | |
| 3 | | A | |
| 4 | | B | |
| 5 | | A | |
| 6 | | B | |

(Agreguen filas según el número de grupos.)

## 4. Para tener en cuenta en la sustentación

- Con dos casos, **los grupos no pueden copiarse el código con solo cambiar nombres** entre casos distintos, pero sí dentro del mismo caso. Revisen el historial de commits y pidan explicar decisiones de diseño.
- El **cambio en vivo** se adapta al caso. Ejemplos listos:
  - Caso A: "agreguen una tarifa con 20 % de descuento para estudiantes" o "agreguen el servicio adicional 'impresión'".
  - Caso B: "agreguen una tarifa con 20 % de descuento para estudiantes" o "agreguen el combo 'dulces'".
- Un diseño bien hecho resuelve cualquiera de los dos agregando **una clase y una línea de configuración**.

---

*Modelos de Programación*
