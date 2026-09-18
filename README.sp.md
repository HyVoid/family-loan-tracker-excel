[ 🌐 عربي ](README.ar.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Kit de conciliación de préstamos familiares y flujos de fondos: Plantilla Excel de saldo corriente y calculadora de intereses

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](#license)
[![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)](#access)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Financial%20Reconciliation%20Spreadsheet-orange.svg)](#what-it-helps-track)

**Una hoja de cálculo integral de seguimiento de préstamos familiares y conciliación de flujos de fondos. Reconstruye años de transferencias de dinero interfamiliares bidireccionales en un principal corriente rastreable, calcula automáticamente el interés devengado y genera una pista de auditoría transparente para acuerdos financieros personales.**

> **Pruebe la calculadora gratuita basada en web. Para los usuarios que requieren registros financieros permanentes, pistas de auditoría sin conexión y un servicio de cuenta mensual repetido, puede descargar la plantilla Excel totalmente desbloqueada con una garantía de devolución de 30 días.**
>
> 🌐 Abrir en el navegador → [Probar la aplicación web gratuita de seguimiento de préstamos interfamiliares (Demo en vivo)](https://hyvoid.github.io/family-loan-tracker-excel/)
> 
> 📥 Descargar plantilla → [Descargar la plantilla Excel reutilizable para la conciliación de préstamos familiares (Versión sin conexión)](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation)  

## Características principales: Puntos débiles frente a soluciones de seguimiento

En lugar de rastrear transferencias acumulativas que no muestran la verdadera situación financiera, este kit de herramientas convierte registros bancarios dispersos en un calendario de amortización de préstamos estandarizado.

| Punto débil común de seguimiento (El problema) | Cómo esta calculadora lo resuelve (La solución) |
| :--- | :--- |
| **Pérdida de seguimiento del dinero prestado vs. reembolsado históricamente** | Separa los adelantos en efectivo históricos de los reembolsos parciales en todo el libro mayor de transacciones. |
| **Extractos bancarios desordenados introducidos fuera de secuencia** | Reconstruye automáticamente el **saldo de principal corriente** de forma dinámica, independientemente del orden de introducción de datos. |
| **Interés fijo aplicado a saldos cambiantes** | Calcula el **interés devengado** con precisión en cada período pendiente según el saldo diario exacto. |
| **Inflación histórica o tasas de mercado fluctuantes** | Aplica calendarios de tasas de mercado históricas personalizables, emparejando tasas de interés específicas con sus períodos efectivos exactos. |
| **Saldos finales globales inexplicados** | Divide el total pendiente actual en columnas claramente auditables: **Capital principal frente a Interés devengado**. |
| **Extensión manual de fórmulas para nuevos pagos** | Extiende automáticamente la fecha de cálculo a "Hoy", trasladando el total pendiente actual de forma automática. |

## Tutorial de inicio rápido: Cómo reconstruir sus registros financieros

Siga este flujo de trabajo para transformar un historial financiero desorganizado en un balance limpio y auditable. 

**Paso 1: Configurar los parámetros de préstamo e intereses**
Defina su base financiera en el panel de Parámetros. Establezca el símbolo de moneda, la base de conteo de días (por ejemplo, Actual/365), el método de interés compuesto y trace el calendario de tasas de mercado históricas (por ejemplo, coincidiendo con las Tasas Federales Aplicables del IRS o tasas acordadas personalizadas).

**Paso 2: Importe su libro mayor de transacciones históricas**
Pegue sus datos financieros sin procesar en la tabla de entrada. El sistema requiere solo puntos de datos básicos: ID de transacción, Fecha, Dirección de transferencia (Entrada/Salida), Importe y una nota breve. Puede copiar y pegar directamente desde sus archivos CSV de exportación bancaria.

**Paso 3: Genere el calendario de saldos cronológico**
Deje que el motor de cálculo dinámico procese los datos. Ordenará automáticamente todos los registros cronológicamente, estandarizará los flujos de efectivo positivos/negativos, reconstruirá el principal corriente diario y calculará el interés exacto devengado entre cada período de pago.

**Paso 4: Mantenga registros de reembolso en curso**
A medida que se realizan nuevos pagos, simplemente añádalos al final del libro mayor. El motor recalcula instantáneamente el interés devengado y el saldo pendiente total hasta la fecha actual.

👉 **¿Listo para crear un registro permanente?** [Descargar la plantilla Excel](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation) para almacenar de forma segura sus datos financieros privados sin conexión y reutilizar el motor de cálculo para la conciliación mensual en curso.

## Por qué creé esta herramienta de conciliación de fondos familiares

Los arreglos financieros familiares de larga duración (como los padres financiando el pago inicial de un hijo, o hermanos cofinanciando una propiedad) a menudo se desarrollan sin la estructura rígida de un sistema formal de servicio de préstamos.

El dinero se mueve en ambas direcciones a lo largo de los años. Los registros se acumulan en extractos bancarios, mensajes de WhatsApp y la memoria. Finalmente, la pregunta más difícil no es *"¿Cuánto dinero se movió?"* Es:

**"¿Cuál era el saldo pendiente exacto en cualquier fecha histórica dada, y cuánto interés debería haberse devengado contra ese saldo específico?"**

Un simple `SUM()` de transferencias en una hoja de cálculo básica no puede responder esto. Si los registros contienen múltiples adelantos en efectivo seguidos de reembolsos parciales esporádicos, un total básico ignora el *valor temporal del dinero* y la duración que cada dólar permaneció impago. 

Este kit de herramientas convierte en producto el razonamiento financiero detrás de la contabilidad compleja. Convierte una década de transacciones desordenadas y mezcladas en un marco de cálculo estrictamente cronológico y defendible.

## Hoja de cálculo automatizada frente a contabilidad de libro mayor manual

| Obstáculos de contabilidad manual (Sin herramienta) | Conciliación Excel automatizada (Con herramienta) |
| :--- | :--- |
| **Cronología desorganizada:** Calcular saldos corrientes contra entradas de libro mayor fuera de orden causa errores matemáticos acumulativos. | **Ordenamiento automatizado:** El motor de cálculo reordena todo el historial de transacciones por fecha antes de aplicar las fórmulas de interés. |
| **Signos de flujo de efectivo inconsistentes:** Decidir manualmente si una transferencia es un ajuste positivo o negativo conduce a errores en las fórmulas. | **Flujos de efectivo estandarizados:** Las direcciones de transacción (Adelantos frente a Reembolsos) se analizan en una convención de movimiento contable estricta. |
| **Errores de interés estático:** Aplicar una sola tasa de interés fija contra un saldo dinámico de varios años sobrecarga o subcarga el interés. | **Devengo por período dinámico:** El interés compuesto o simple se calcula específicamente en cada período pendiente histórico distinto. |
| **Opacidad de tasas:** Usar una sola tasa combinada oculta la realidad de las tasas de interés macroeconómicas cambiantes a lo largo de una década. | **Mapeo de tasas variables:** Cada período de transacción se empareja automáticamente mediante búsqueda con el calendario de tasas de mercado efectivas definido por el usuario. |
| **Mezcla de datos:** Mezclar el capital y el interés en una columna hace que el número de deuda final sea imposible de auditar o explicar a la familia. | **Segregación de datos:** Los saldos de capital, los límites de interés devengado y los pasivos pendientes totales se calculan en columnas aisladas y transparentes. |

## Usuarios objetivo y casos de uso específicos

Esta hoja de cálculo está diseñada para personas que gestionan relaciones financieras a largo plazo donde las transacciones históricas deben reconstruirse ingeniería inversa en un balance e intereses matemáticamente sólidos. 

**Busque y encuentre su perfil:**
* **Padres y tutores:** Seguimiento de los adelantos en efectivo del *"Banco de Mamá y Papá"*, gestión de plantillas de reembolso de préstamos personales para hijos con términos de interés transparentes.
* **Albaceas y fideicomisarios:** Conciliación de préstamos interfamiliares históricos, documentación de deudas heredadas y generación de pistas de auditoría para distribuciones por sucesión o fideicomisos familiares.
* **Gestores de family office:** Operación de un rastreador de flujo de fondos inter-entidades para monitorear inyecciones de capital informales y retiros en empresas de propiedad familiar.
* **Hermanos y co-inversores:** Mantenimiento de un libro mayor de inversiones conjuntas informal para rastrear quién pagó qué a lo largo de años de propiedad compartida o empresas conjuntas.
* **Entusiastas de las finanzas personales:** Cualquiera que necesite una alternativa robusta al software de contabilidad complejo (como QuickBooks) para liquidar libros de préstamos entre pares (P2P) a largo plazo.

*(Nota: Este kit de herramientas proporciona cálculos de apoyo a la toma de decisiones. No reemplaza los servicios de contabilidad pública certificada (CPA), la documentación legal formal de préstamos ni el asesoramiento de cumplimiento fiscal.)*

## Acerca de la arquitectura

Construyo rastreadores operativos ligeros y plantillas de apoyo a la toma de decisiones para entornos que tienen demasiadas partes móviles para los cálculos mentales, pero carecen de la complejidad para justificar un software ERP empresarial. 

La filosofía de diseño central es simple: **La información debe estructurarse cronológicamente para tomar la siguiente decisión financiera con confianza.** 

Este kit de herramientas rechaza la contabilidad genérica. Es un motor de enfoque estrecho diseñado exclusivamente para reconstruir líneas de tiempo, mapear tasas de interés variables y demostrar la posición pendiente actual exacta de fondos privados.

## Detalles técnicos

<details>
<summary>Para revisores técnicos, practicantes de Excel y colaboradores</summary>

### Arquitectura del libro de trabajo

El libro de trabajo utiliza cinco hojas en cuatro capas funcionales:

| Hoja             | Función                                                                                                  | Entrada / Salida                     |
| ----------------- | ----------------------------------------------------------------------------------------------------- | ---------------------------------- |
| `00_Instructions` | Instrucciones del sistema, información de versión y guía de operación                                      | Estática                             |
| `01_Parameters`   | Supuestos globales, definiciones de dirección, base de conteo de días, método de interés y calendario de tasas de mercado | Entrada manual                       |
| `02_Transactions` | Libro mayor histórico de movimientos de fondos bidireccionales                                                               | Entrada manual + cálculo dinámico |
| `03_CalcEngine`   | Reconstrucción cronológica, principal corriente, emparejamiento de tasas, conteo de días y motor de interés       | Basada en fórmulas                     |
| `04_Summary`      | Saldo pendiente actual y desglose de capital/intereses                                          | Basada en fórmulas                     |

El flujo de datos central es:

```text
01_Parameters
      │
      ├──────────────┐
      │              ▼
      │       02_Transactions
      │              │
      │              ▼
      └──────► 03_CalcEngine
                     │
                     ▼
                 04_Summary
```

El motor de cálculo realiza cuatro operaciones principales:

1. Ordenar las transacciones históricas cronológicamente.
2. Convertir cada transacción en un movimiento firmado estandarizado.
3. Reconstruir el principal corriente y emparejar la tasa de mercado aplicable.
4. Calcular el interés del período y el interés pendiente acumulado.

El resumen luego extrae los resultados más recientes de capital e interés devengado para presentar la posición pendiente actual. La arquitectura fuente define explícitamente la cadena de dependencia de transacción a motor a resumen.  

### Tres trampas que atrapan incluso a los tenedores de registros financieros experimentados

#### Trampa 1 — Tratar las transferencias acumulativas como toda la respuesta

**1. Se tomó una decisión:**
Determinar el importe actualmente pendiente restando los reembolsos totales de los adelantos totales.

**2. El defecto no detectado:**
Esto establece el capital neto pero no dice nada sobre cuánto tiempo permanecieron pendientes los diferentes saldos.

**3. Por qué cambia el resultado:**
El interés depende tanto del capital como del tiempo transcurrido.

**4. Por qué el razonamiento es incompleto:**
Un saldo de $10,000 pendiente durante varios años es económicamente diferente de un saldo de $10,000 que apareció recientemente.

**5. Enfoque corregido:**
Reconstruir el principal corriente después de cada transacción y calcular cada intervalo por separado.

**6. Resultado corregido:**
El resultado actual contiene tanto el capital restante como el interés acumulado atribuible a los períodos históricos.

<details>
<summary>Lógica de la fórmula</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

Esto crea un saldo de principal corriente a partir del vector de movimiento de transacción estandarizado.

</details>

#### Trampa 2 — Aplicar una sola tasa de interés a toda la historia

**1. Se tomó una decisión:**
Aplicar la tasa de mercado asumida de hoy a todo el saldo histórico.

**2. El defecto no detectado:**
La tasa aplicable pudo haber cambiado durante el período histórico.

**3. Por qué cambia el resultado:**
Diferentes períodos pueden tener diferentes tasas anuales.

**4. Por qué el razonamiento es incorrecto:**
Una tasa actual no representa automáticamente cada período histórico.

**5. Enfoque corregido:**
Mantenga un calendario de tasas con fecha efectiva y empareje cada fecha de transacción con la tasa histórica aplicable.

**6. Resultado corregido:**
Cada período se calcula utilizando la tasa definida como efectiva en ese punto de la línea de tiempo.

<details>
<summary>Lógica de la fórmula</summary>

```excel
=MAP(A2#, LAMBDA(d,
    XLOOKUP(
        d,
        '01_Parameters'!$A$13:$A$20,
        '01_Parameters'!$B$13:$B$20,
        0,
        -1
    )
))
```

El modo de coincidencia `-1` recupera la fecha efectiva exacta o la siguiente fecha efectiva menor.

</details>

#### Trampa 3 — Calcular el interés sin reconstruir los intervalos de tiempo

**1. Se tomó una decisión:**
Calcular el interés desde una fecha de transacción hasta una fecha de liquidación fija.

**2. El defecto no detectado:**
Las transacciones posteriores pudieron haber cambiado el capital pendiente durante ese período.

**3. Por qué cambia el resultado:**
El interés debe reflejar el saldo aplicable durante cada intervalo.

**4. Por qué el razonamiento es incorrecto:**
Un cálculo único de fecha a fecha ignora los cambios en el capital entre transacciones.

**5. Enfoque corregido:**
Calcule el número de días desde cada transacción hasta la siguiente transacción, usando hoy como punto final para el último período abierto.

**6. Resultado corregido:**
El interés sigue el saldo histórico reconstruido en lugar de un monto estático asumido.

<details>
<summary>Lógica de la fórmula</summary>

```excel
=LET(
    dates, A2#,
    n, ROWS(dates),
    MAP(SEQUENCE(n), LAMBDA(i,
        IF(
            i = n,
            TODAY() - INDEX(dates, i),
            INDEX(dates, i + 1) - INDEX(dates, i)
        )
    ))
)
```

La transacción final continúa devengando hasta la fecha actual.

</details>

### Escenario de ejemplo

Considere una secuencia histórica simplificada:

| Fecha       | Dirección |  Importe |
| ---------- | --------- | ------: |
| 2020-01-15 | Adelanto   | $20,000 |
| 2020-09-01 | Adelanto   | $10,000 |
| 2021-06-15 | Reembolso |  $8,000 |
| 2022-03-01 | Reembolso |  $5,000 |

El movimiento estandarizado se convierte en:

```text
2020-01-15    +20,000
2020-09-01    +10,000
2021-06-15     -8,000
2022-03-01     -5,000
```

Por lo tanto, el principal corriente se convierte en:

```text
After 2020-01-15    $20,000
After 2020-09-01    $30,000
After 2021-06-15    $22,000
After 2022-03-01    $17,000
```

El cambio analítico importante es que el interés no se calcula contra $17,000 durante todo el período histórico.

En su lugar, el motor reconoce diferentes intervalos de saldo:

```text
$20,000  →  until 2020-09-01
$30,000  →  until 2021-06-15
$22,000  →  until 2022-03-01
$17,000  →  from 2022-03-01 → today
```

Si el calendario de tasas de mercado cambia entre estas fechas, la tasa aplicable a cada intervalo se determina a partir de la tabla de fechas efectivas.

La salida resultante separa:

```text
Net Outstanding Principal
+ Accrued Interest
----------------------
Current Total Outstanding
```

Esto hace que el número final sea explicable: se puede rastrear hasta la secuencia de transacciones, los intervalos de saldo, los supuestos de tasa y los días transcurridos en lugar de ser una cifra de liquidación introducida manualmente.

### Referencia de fórmulas

<details>
<summary>Dirección de transacción → Movimiento neto</summary>

```excel
=LET(
    tx_dates, FILTER(A2:A10000, A2:A10000<>""),
    dirs, FILTER(C2:C10000, A2:A10000<>""),
    amts, FILTER(D2:D10000, A2:A10000<>""),
    out_dir, '01_Parameters'!$B$8,
    in_dir, '01_Parameters'!$B$9,
    MAP(
        dirs,
        amts,
        LAMBDA(d, a,
            IF(d=out_dir, a, IF(d=in_dir, -a, 0))
        )
    )
)
```

**Propósito:** Convierte las direcciones de transacción en un movimiento firmado estandarizado.

**Lógica:** La dirección de adelanto/salida configurada se vuelve positiva; la dirección de reembolso/entrada configurada se vuelve negativa.

</details>

<details>
<summary>Ordenamiento cronológico de transacciones</summary>

```excel
=LET(
    raw_dates, FILTER('02_Transactions'!B2:B10000, '02_Transactions'!A2:A10000<>""),
    raw_mvmt, FILTER('02_Transactions'!E2:E10000, '02_Transactions'!A2:A10000<>""),
    SORTBY(
        HSTACK(raw_dates, raw_mvmt),
        raw_dates,
        1
    )
)
```

**Propósito:** Garantiza que las transacciones históricas se procesen cronológicamente independientemente de su orden de entrada original.

</details>

<details>
<summary>Principal corriente</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

**Propósito:** Construye el saldo de principal corriente a partir de la secuencia de movimiento estandarizado.

</details>

<details>
<summary>Emparejamiento de tasas de mercado históricas</summary>

```excel
=MAP(A2#, LAMBDA(d,
    XLOOKUP(
        d,
        '01_Parameters'!$A$13:$A$20,
        '01_Parameters'!$B$13:$B$20,
        0,
        -1
    )
))
```

**Propósito:** Empareja cada fecha de transacción con la tasa de mercado efectiva aplicable.

**Importante:** La tabla de fechas efectivas debe mantenerse como un calendario de tasas ordenado.

</details>

<details>
<summary>Días del período</summary>

```excel
=LET(
    dates, A2#,
    n, ROWS(dates),
    MAP(SEQUENCE(n), LAMBDA(i,
        IF(
            i = n,
            TODAY() - INDEX(dates, i),
            INDEX(dates, i + 1) - INDEX(dates, i)
        )
    ))
)
```

**Propósito:** Determina el número de días representado por cada intervalo de cálculo.

</details>

<details>
<summary>Interés del período</summary>

```excel
=LET(
    principals, C2#,
    rates, D2#,
    days, E2#,
    day_base, '01_Parameters'!$B$4,
    principals * rates * (days / day_base)
)
```

**Propósito:** Calcula el interés de cada período utilizando el capital reconstruido, la tasa emparejada, los días transcurridos y la base de conteo de días configurada.

</details>

<details>
<summary>Interés devengado</summary>

```excel
=SCAN(0, F2#, LAMBDA(prev_int, curr_int, prev_int + curr_int))
```

**Propósito:** Acumula todo el interés del período histórico en el saldo de interés devengado actual.

</details>

<details>
<summary>Total pendiente corriente</summary>

```excel
=C2# + G2#
```

**Propósito:** Combina el principal corriente y el interés devengado en cada punto de cálculo.

</details>

### Reglas de validación

| Campo / Área              | Regla                                                                | Comportamiento ante errores                                                      |
| ------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| ID de transacción            | Debe identificar cada transacción histórica de forma única                | Los ID duplicados requieren revisión                                        |
| Fecha                      | Debe contener una fecha de transacción válida                               | Fechas inválidas o en blanco pueden impedir un procesamiento cronológico correcto |
| Dirección                 | Debe coincidir con una de las definiciones de dirección configuradas              | Un texto no reconocido puede producir un movimiento incorrecto                 |
| Importe                    | El importe de la transacción histórica debe ser un valor absoluto positivo   | Los importes fuente negativos pueden invertir la convención de signo prevista    |
| Fecha efectiva            | Debe representar el inicio de un período de tasa                       | Fechas incorrectas pueden asignar la tasa histórica errónea                |
| Tasa anual               | Debe introducirse como un porcentaje anual                             | Un formato incorrecto cambia el cálculo de intereses               |
| Base de conteo de días           | La configuración admitida suele ser 360 o 365                      | Una configuración inválida cambia el interés del período                       |
| Área de salida de matriz dinámica | Debe permanecer despejada                                            | Las celdas bloqueantes producen `#SPILL!`                                    |
| Modo de cálculo          | Excel debe permanecer en modo de cálculo Automático                   | El modo manual puede dejar los resultados mostrados desactualizados                       |
| Etiquetas de dirección          | Las definiciones de parámetros y las selecciones de transacción deben coincidir exactamente | Un texto no coincidente puede invertir o anular el movimiento                    |

El diseño fuente identifica específicamente los conflictos de derrame de matriz dinámica, el modo de cálculo manual, las discrepancias de etiquetas de dirección y los problemas de formato como casos operativos de solución de problemas. 

</details>

## La lógica de negocio y la metodología

El modelo se construye en torno a un principio comercial simple: **un saldo financiero histórico es una línea de tiempo, no solo un total.**

Varios métodos trabajan en conjunto:

* **Normalización de transacciones** convierte diferentes direcciones de transacción en una convención de movimiento consistente. Esto evita que el mismo evento financiero se interprete de manera diferente en distintas partes del libro de trabajo.
* **Reconstrucción de saldo corriente** muestra cómo cambió el capital pendiente después de cada transacción. Esto hace visibles los reembolsos parciales y los adelantos adicionales en lugar de enterrarlos en un total acumulativo.
* **Cálculo de interés basado en períodos** vincula el interés al saldo que realmente existió durante cada período. El resultado es más rastreable que aplicar una tasa a un saldo de fin de período.
* **Emparejamiento de tasas con fecha efectiva** permite que los supuestos de tasas de mercado históricas cambien con el tiempo. Se puede introducir una nueva tasa sin reconstruir el libro mayor de transacciones históricas.
* **Separación de capital e intereses** hace que la cifra de liquidación sea explicable. El tomador de decisiones puede distinguir el monto de capital aún pendiente del interés acumulado bajo los supuestos seleccionados.

El resultado es un flujo de trabajo de conciliación práctico: reconstruya primero la posición histórica, aplique segundo los supuestos declarados y presente el saldo actual solo después de haber establecido la línea de tiempo subyacente.

## Otras herramientas de esta serie

Herramientas relacionadas de apoyo a la toma de decisiones comerciales y financieras ligeras están disponibles en la colección de proyectos.

* **Kits de herramientas para decisiones de negocio** — marcos reutilizables basados en Excel para preguntas operativas y financieras recurrentes.
* **Herramientas de planificación financiera y conciliación** — modelos enfocados para convertir registros sin procesar en información financiera lista para la toma de decisiones.
* **Kits de herramientas de construcción y operaciones** — libros de trabajo prácticos para estimación, costos, planificación y control operativo.

Consulte el perfil de GitHub y la colección de productos para la serie más amplia de kits de herramientas.

## Licencia

Este proyecto se publica bajo la **Licencia Apache 2.0**.

Consulte el archivo de licencia del repositorio para los términos y condiciones completos.

