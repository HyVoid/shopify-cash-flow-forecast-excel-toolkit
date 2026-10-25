[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Toolkit de Control Financiero DTC y Previsión de Flujo de Caja en 12 Semanas | Plantilla Excel para Shopify y Modelo de Conciliación de Liquidaciones
<img width="1920" height="790" alt="image" src="https://github.com/user-attachments/assets/2b140bc1-af18-4481-82c0-d626669f8fe2" />


![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20Sandbox%20%2B%20Excel%20(.xlsx)-success.svg)
![Tool](https://img.shields.io/badge/Category-Ecommerce%20Financial%20Modeling%20%26%20FP%26A-orange.svg)

Una solución todo en uno de **modelado financiero para e-commerce** y **plantilla Excel de previsión de flujo de caja continua de 12 semanas**, diseñada para **tiendas Shopify** y **marcas direct-to-consumer (DTC)**. Este toolkit transforma las **liquidaciones de Shopify** brutas, las **conciliaciones de la cuenta de compensación bancaria**, las **órdenes de compra de inventario (POs)**, las facturas de **cuentas por pagar (AP)** y el **gasto en publicidad de medios pagados (Meta/Google Ads)** en un **marco unificado de planificación de fondo de maniobra y liquidez**. Construido como una **alternativa ligera de soporte a la decisión FP&A** sin código, frente a **sistemas ERP** empresariales de seis cifras e informes contables estáticos de **QuickBooks/Xero**.

**Sin registro. Sin instalación. Prueba interactiva gratuita en tu navegador.**

Pon a prueba al instante los datos operativos de tu tienda en el sandbox gratuito del navegador. Para una gestión de tesorería mensual recurrente, configuración de parámetros personalizada y privacidad total de los datos financieros sin conexión, descarga el libro de Excel de Microsoft totalmente desbloqueado, respaldado por una garantía de devolución de 30 días sin preguntas.

> 🌐 **Lanzar el sandbox web interactivo (sin configuración)**  
> [Prueba las métricas de tu tienda en el simulador DTC de flujo de caja y liquidez gratuito basado en navegador](https://hyvoid.github.io/shopify-cash-flow-forecast-excel-toolkit/)
>
> 📥 **Obtener el modelo operativo offline completo (.xlsx)**  
> [Descarga la plantilla Excel reutilizable de Control Financiero Shopify y Flujo de Caja de 12 Semanas](https://www.theseusworkshop.com/l/iybjto?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=dtc-financial-control-cashflow)

---

## Lo que te ayuda a seguir: puntos de dolor financiero del e-commerce vs. soluciones automatizadas

El software contable estándar sigue la rentabilidad histórica en base devengada, dejando a las marcas en crecimiento ciegas ante las próximas crisis de caja. Este marco de control financiero mapea las fugas operativas específicas directamente sobre métricas de tesorería prospectivas:

| Punto de dolor financiero del e-commerce (intención de búsqueda) | Riesgo de fondo de maniobra subyacente | Módulo toolkit automatizado y KPI seguidas |
| :--- | :--- | :--- |
| **Gestión ciega del saldo bancario:** adivinar la **pista de liquidez** real basándose únicamente en el saldo estático de la cuenta corriente de hoy. | Comprometer demasiado caja en inventario o marketing justo antes de que se solapen las nóminas y las deudas con proveedores. | **Previsión de flujo de caja continua de 12 semanas:** calcula la **liquidez operativa neta** y las **rupturas de reserva de seguridad** escalonando los pagos futuros frente a las entradas esperadas. |
| **Liquidaciones de Shopify no conciliadas:** las ventas brutas en Shopify no coinciden con los depósitos bancarios netos debido a retenciones de pasarela, devoluciones y comisiones. | Fuga de ingresos oculta, contracargos no registrados y errores contables de la **cuenta de compensación** a fin de mes. | **Motor de conciliación de liquidaciones de 3 vías:** rastrea la **varianza de pedido a liquidación**, los **fondos de pasarela en tránsito** y las **excepciones de liquidación no emparejadas**. |
| **Facturas de proveedores duplicadas y errores de AP:** pagar accidentalmente dos veces al mismo transitario o fabricante a lo largo de los ciclos de facturación. | Pérdida directa de fondo de maniobra y cronogramas de **envejecimiento de cuentas por pagar (AP)** distorsionados. | **Módulo de auditoría de AP y verificación de pagos:** marca **ID de facturas duplicadas**, **riesgos de sobrepago** y **transferencias pendientes de aprobación** antes de que la caja salga del banco. |
| **Rotura de stock vs. crisis de caja:** pagar anticipos del 30 % y saldos del 70 % en **órdenes de compra (POs)** semanas antes de que el inventario se convierta en caja. | Insolvencia inducida por el inventario durante los picos de fabricación de Q3/Q4. | **Simulador de impacto de OC de inventario:** somete a prueba de estrés las **condiciones de pago del coste en destino (Net-30/60)** frente a tu **umbral mínimo de reserva de caja**. |
| **Gasto publicitario aislado e informes de ROAS:** los compradores de medios escalan los presupuestos diarios de anuncios de Facebook/Google desconectados del timing real de liquidación bancaria. | **Ratio de eficiencia de marketing (MER)** alto sobre el papel que enmascara una grave quema a corto plazo de tarjetas de crédito y caja. | **Rastreador de liquidez de gasto publicitario integrado:** alinea las **salidas semanales de coste de adquisición de cliente (CAC)** con las **entradas retrasadas de los procesadores de pago**. |

---

## Tutorial de inicio rápido: cómo automatizar tu análisis de flujo de caja y liquidaciones de Shopify

Transforma las exportaciones CSV fragmentadas de tu stack tecnológico de e-commerce en un **panel financiero FP&A** listo para la dirección en cuatro pasos estructurados.

### Paso 1: configura los parámetros base de fondo de maniobra (configuración única)
Abre la hoja **Parameters** para establecer los límites de tesorería de tu empresa. Define tu **reserva mínima de caja de seguridad**, la **moneda de informe**, los **tipos de cambio (FX)**, las condiciones de pago a proveedores predeterminadas y el **horizonte de previsión continua de 12 semanas**. Estas variables globales gobiernan todas las alertas de liquidez posteriores.

### Paso 2: importa datos CSV brutos de e-commerce, banca y contabilidad
Elimina la entrada manual de datos y el copiar-pegar frágil. Exporta los registros de transacciones CSV estándar desde tus plataformas existentes y déjalos caer en las tablas de entrada de Excel estructuradas:
*   **Exportaciones de pedidos de Shopify y liquidaciones de merchant** (ventas brutas, devoluciones, comisiones de pasarela, liquidaciones netas)
*   **Extractos de cuenta corriente comercial y tarjetas de crédito** (exportaciones CSV de Mercury, Chase, Relay o Amex)
*   **Libro mayor y facturas de AP** (exportaciones de **QuickBooks Online**, **Xero** o Bill.com)
*   **Órdenes de compra a proveedores (POs)** (calendarios de producción de SKU, anticipos, fechas de vencimiento de saldos)
*   **Gasto en marketing de rendimiento** (gasto publicitario diario/semanal de **Meta Ads Manager**, **Google Ads** y **TikTok Ads**)

### Paso 3: ejecuta la conciliación automatizada, la auditoría de AP y las pruebas de estrés de liquidez
Navega hasta el **Financial_Dashboard** y las pestañas analíticas. Impulsado por las matrices dinámicas nativas de Excel (`LET`, `MAP`, `LAMBDA`, `XLOOKUP`), el modelo calcula y marca automáticamente:
*   liquidaciones de pasarelas de pago no emparejadas y varianzas de compensación
*   números de facturas de cuentas por pagar (AP) duplicados y alertas de doble pago
*   saldos de caja continuos semana a semana de 12 semanas frente a los umbrales de reserva de seguridad
*   calificaciones de aprobación/suspenso previas a la aprobación para las próximas órdenes de compra de inventario

### Paso 4: fija tu rutina mensual de tesorería (descarga el modelo Excel reutilizable)
Usa el [simulador DTC de flujo de caja gratuito basado en navegador](https://hyvoid.github.io/shopify-cash-flow-forecast-excel-toolkit/) para una prueba diagnóstica inmediata de tus cifras actuales. Una vez que valides cómo el modelo expone las lagunas de caja ocultas, pasa a la hoja de cálculo completa para el control financiero semanal y mensual continuo.

👉 **CTA — construye tu sistema operativo financiero permanente:**  
**[Descarga la plantilla Excel de Control Financiero Shopify y Flujo de Caja desbloqueada (.xlsx)](https://www.theseusworkshop.com/l/iybjto?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=dtc-financial-control-cashflow)** — Diseñada para flujos de trabajo mensuales repetibles. Simplemente pega las nuevas exportaciones CSV sobre las tablas de entrada cada semana; cada estado de conciliación, gráfico continuo de 12 semanas e indicador de riesgo de inventario se actualiza automáticamente sin reescribir una sola fórmula.

---

## Para quién es esto: roles de e-commerce objetivo y casos de uso de alto impacto

Este toolkit cierra la brecha analítica entre la contabilidad histórica (QuickBooks/Xero) y el software de tesorería empresarial pesado (NetSuite/Anaplan). Está diseñado específicamente para decisores concretos que buscan **plantillas de hoja de cálculo para e-commerce** accionables:

*   **CFO de e-commerce y firmas de asesoría de CFO fraccional:**  
    *Caso de uso:* entregar **modelos de previsión de flujo de caja de 13/12 semanas** estandarizados e informes mensuales al consejo en múltiples cuentas de clientes Shopify Plus de 7 y 8 cifras, sin construir hojas de cálculo personalizadas desde cero.
*   **Fundadores DTC, CEO y propietarios de tiendas Shopify:**  
    *Caso de uso:* usar una **plantilla de panel financiero de e-commerce** ligera para responder a la pregunta *«¿Podemos permitirnos esta orden de compra de inventario de 150 mil $ y escalar simultáneamente los anuncios de Meta?»* sin contratar a un analista FP&A a tiempo completo ni pagar tasas de implementación de ERP de seis cifras.
*   **Controladores de e-commerce, contables y directores de contabilidad:**  
    *Caso de uso:* sustituir las hojas `VLOOKUP` manuales propensas a errores por una **plantilla de conciliación de liquidaciones de Shopify automatizada** que empareja las liquidaciones a nivel de pedido con los depósitos bancarios y evita transferencias duplicadas a proveedores.
*   **Planificadores de inventario, directores de cadena de suministro y operaciones:**  
    *Caso de uso:* ejecutar un **simulador de flujo de caja de inventario** durante la preparación de la temporada alta de Q3/Q4 para negociar **condiciones de pago a proveedores Net-30 / Net-60** y dividir los lotes de producción para que los anticipos del coste en destino nunca rompan las reservas mínimas de caja.
*   **Marketers de crecimiento, compradores de medios y agencias de rendimiento:**  
    *Caso de uso:* coordinar el **escalado del gasto en publicidad social pagada** con los **ciclos de conversión de caja (CCC)** reales, garantizando que las campañas agresivas de adquisición de clientes no provoquen congelaciones de fondo de maniobra a corto plazo debido a las retenciones de los procesadores de pago.

*Nota de alcance: este toolkit **no** sustituye a tu libro mayor statutory (QuickBooks, Xero) ni al software de cumplimiento fiscal. Opera como una **capa de soporte a la decisión FP&A** ágil situada sobre tus exportaciones contables existentes.*

---

## Escenarios de e-commerce del mundo real: cuándo desplegar este modelo de flujo de caja

Las cuentas de resultados (P&L) estáticas fallan durante los puntos de inflexión operativos rápidos. Despliega este toolkit ante estos escenarios DTC de alto riesgo:

### Escenario 1: financiación de inventario de temporada alta (Q4 / Black Friday Cyber Monday)
Necesitas emitir una orden de compra de fabricación de 200.000 $ en agosto con un anticipo del 30 % y el 70 % a pagar contra conocimiento de embarque, mucho antes de que los ingresos de BFCM lleguen a tu cuenta bancaria. Usa el **simulador de impacto de inventario** para modelar las caídas semanales de caja exactas y probar si dividir el envío o negociar condiciones Net-45 evita una ruptura de liquidez en la semana 7.

### Escenario 2: escalado rápido de adquisición pagada y gestión del retraso de liquidaciones
Tu ROAS es rentable y escalas el gasto diario en anuncios de Meta y Google de 2.000 $/día a 6.000 $/día. Sin embargo, las plataformas publicitarias cargan tu tarjeta de crédito/banco rápidamente, mientras que las pasarelas de Shopify Payments, PayPal y Compra Ahora Paga Después (BNPL) retienen o retrasan las liquidaciones de 3 a 7 días hábiles. Usa la **previsión de flujo de caja de 12 semanas** para modelar el puente de fondo de maniobra exacto necesario para financiar la brecha de liquidación.

### Escenario 3: auditoría de cuenta de compensación a fin de mes y recuperación de contracargos
Tu panel de Shopify informa 500.000 $ de ventas mensuales brutas, pero tu cuenta corriente solo refleja 442.000 $ de depósitos netos. En lugar de dedicar 15 horas a verificar manualmente las filas de CSV, ejecuta el **motor de conciliación de 3 vías** para aislar de inmediato los pedidos exactos afectados por comisiones de procesadores, devoluciones pendientes, retenciones de reserva o liquidaciones bancarias ausentes.

---

## Comparación de flujos de trabajo: hojas de cálculo manuales y sistemas ERP vs. toolkit automatizado

| Flujo financiero de e-commerce central | Contabilidad manual tradicional (QuickBooks + VLOOKUPs manuales) | Software ERP/tesorería empresarial (NetSuite, HighRadius) | Este toolkit Excel de Control Financiero DTC |
| :--- | :--- | :--- | :--- |
| **Conciliación de liquidaciones de Shopify de pedido a banco** | los controladores exportan CSV manualmente y construyen hojas `VLOOKUP` frágiles que se rompen cuando una liquidación abarca varios pedidos. | Requiere conectores middleware caros (p. ej., Celigo/A2X) y una configuración compleja de reglas de cuenta de compensación. | El **motor de matrices dinámicas automatizado** (`UNIQUE`/`MAP`/`SUMIFS`) aísla al instante las liquidaciones no emparejadas y las varianzas exactas en dólares. |
| **Detección de facturas duplicadas de cuentas por pagar (AP)** | los contables dependen de comprobaciones visuales y descubren las transferencias duplicadas a proveedores solo tras la conciliación bancaria de fin de mes. | Se impone mediante jerarquías rígidas de aprobación de compras que ralentizan las cadenas de suministro DTC ágiles. | El **módulo de revisión de AP en tiempo real** marca los ID de facturas duplicadas y los importes de pago sospechosos antes del desembolso de caja. |
| **Previsión de flujo de caja continua de 12 semanas** | construida sobre hojas de cálculo estáticas actualizadas manualmente que quedan obsoletas en cuanto el gasto semanal real se desvía. | Requiere administradores de FP&A dedicados y semanas de incorporación para configurar las reglas de previsión. | La **línea de tiempo continua auto-desplazable** (`SEQUENCE`/`TODAY`) actualiza automáticamente las proyecciones de liquidez semanales a partir de pegado CSV bruto. |
| **Pruebas de estrés de OC de inventario y fondo de maniobra** | los equipos de operaciones aprueban las OC de fábrica basándose en el saldo bancario de hoy, ignorando las facturas de publicidad y nóminas que se solapan a 6 semanas vista. | Encerrado dentro de módulos MRP complejos desconectados del gasto de marketing en tiempo real y de los retrasos de liquidación de pasarela. | El **simulador de impacto de OC interactivo** modela las fechas de anticipo y saldo frente a tu **reserva de caja de seguridad** configurable. |
| **Tiempo de implementación y coste total de propiedad** | 0 $ de coste de software, pero consume 20–40 horas/mes de mano de obra financiera y de control de alto coste. | De 25.000 $ a más de 100.000 $ de licencia anual más 3–6 meses de implementación por consultores. | **Prueba instantánea en el navegador** + una **plantilla Excel reutilizable** asequible y única, lista en menos de 15 minutos. |

---

## La lógica de negocio y la metodología

Este toolkit no es una plantilla de informes pasiva; está diseñado en torno a cuatro **metodologías establecidas de finanzas corporativas y tesorería**, adaptadas para resolver las vulnerabilidades estructurales del modelo de negocio direct-to-consumer (DTC).

### 1. Resolución del ciclo de conversión de caja (CCC) invertido
En el e-commerce minorista, el **ciclo de conversión de caja (CCC = DIO + DSO - DPO)** está estructuralmente invertido durante las fases de crecimiento. Las marcas desembolsan caja por adelantado para los anticipos de inventario (**días de inventario pendiente**) y el marketing de rendimiento diario, mientras esperan días o semanas a que los procesadores de pago (Stripe, Shopify Payments, PayPal, Affirm) liquiden los fondos (**días de ventas pendiente**). La **contabilidad devengada (GAAP)** tradicional registra los ingresos en el pago, enmascarando graves déficits de timing de caja. Este toolkit impone una **visibilidad de tesorería sobre base de caja**, desplazando las decisiones ejecutivas del beneficio teórico del P&L a la **liquidez de fondo de maniobra** crítica para la supervivencia.

### 2. Conciliación de liquidaciones de comercio de 3 vías determinista
*   **El método:** adapta los **principios de emparejamiento de 3 vías** empresariales al reconocimiento de ingresos del e-commerce mediante la referencia cruzada de tres libros de datos independientes: el **origen del pedido** (ventas brutas/netas de Shopify), el **tránsito de compensación** (informes de liquidaciones de pasarelas de pago) y la **liquidación final** (extractos bancarios comerciales).
*   **El problema de negocio resuelto:** elimina la fuga silenciosa de ingresos y la hinchazón de la cuenta de compensación. Al aislar matemáticamente las varianzas a nivel de transacción, los equipos financieros detectan de inmediato retenciones de reserva de procesadores, contracargos no registrados, pérdidas por conversión de divisas y transferencias bancarias fallidas, sin auditar miles de filas emparejadas.

### 3. Previsión de flujo de caja continua de 12 semanas por el método directo
*   **El método:** implementa el **método directo de previsión de flujo de caja** sobre un **horizonte continuo de 12 semanas** dinámico y auto-avanzado (el estándar institucional para la gestión de reestructuración y el control de tesorería de CFO fraccionales). En lugar de estimaciones porcentuales descendentes, agrega compromisos operativos ascendentes: anticipos de OC programados, nóminas/OPEX recurrentes, velocidad histórica de liquidación y quema publicitaria semanal activa.
*   **El problema de negocio resuelto:** erradica la trampa de la «quiebra rentable». Responde a la pregunta operativa más crítica con seis a ocho semanas de antelación: *«¿Empujarán los saldos de proveedores y las facturas de marketing que se solapan nuestro saldo bancario por debajo de nuestra reserva operativa mínima en la semana 7?»*

### 4. Optimización de inventario y fondo de maniobra basada en restricciones
*   **El método:** utiliza **pruebas de estrés de liquidez basadas en escenarios** (inspiradas en el modelado financiero de la **teoría de restricciones**). Cada orden de compra de inventario propuesta se evalúa frente a dos puertas de caja temporales — la **fecha del anticipo** y la **fecha de liquidación del saldo final** — medidas frente a un **límite de reserva de caja de seguridad** estricto.
*   **El problema de negocio resuelto:** transforma las compras de un conflicto binario *«comprar vs. congelar»* en una palanca de negociación estructurada. Los líderes de cadena de suministro y finanzas pueden determinar matemáticamente si extender las condiciones de proveedores a **Net-30**, dividir la producción en dos lotes escalonados o aplazar una OC 14 días preserva el 100 % de la velocidad de ingresos al tiempo que elimina el riesgo de insolvencia.

---

## El origen: por qué construí este sistema operativo financiero

Muchas marcas Shopify en crecimiento creen que tienen visibilidad financiera porque poseen software contable, cuentas bancarias y paneles de ventas. En la práctica, cada sistema responde a una pregunta aislada:

*   El **software contable (QuickBooks/Xero)** explica lo que ya ocurrió (*registro devengado histórico*).
*   **Shopify Analytics** explica lo que pidieron los clientes (*valor bruto de mercancía*).
*   Los **portales bancarios** muestran dónde está la caja hoy (*instantánea estática*).
*   Los **gestores de anuncios (Meta/Google)** explican dónde se gastó el presupuesto (*coste de adquisición atribuido*).

Ninguno de ellos calcula de forma independiente si las decisiones de compra y marketing de hoy provocarán una crisis de fondo de maniobra dentro de seis semanas. Se pide inventario porque las ventas parecen fuertes; se escalan los presupuestos publicitarios porque el ROAS parece saludable; se pagan las facturas de proveedores porque el saldo de la cuenta corriente de hoy parece alto — hasta que los retrasos de liquidación, los saldos de las OC y las facturas de publicidad colisionan en la misma semana.

**Antes de desplegar este toolkit:**  
Una marca Shopify que genera 480.000 $/mes de ingresos aprueba una OC de inventario de 150.000 $ basándose en un saldo bancario saludable. Tres semanas después, la facturación de anuncios con tarjeta de crédito, los anticipos a proveedores y las liquidaciones de Shopify retrasadas se solapan, haciendo caer la caja por debajo de las necesidades de nómina.

**Después de desplegar este toolkit:**  
La misma OC de 150.000 $ se introduce en el **simulador de impacto de inventario** antes de la aprobación. El modelo marca que la caja final de la semana 7 romperá la reserva de seguridad configurada. La dirección aplaza la mitad del envío dos semanas y negocia condiciones Net-30 con la fábrica. Se cumplen los objetivos de ingresos; el riesgo de crisis de caja queda neutralizado.

---

## Arquitectura del libro y referencia técnica

El libro de Excel sigue un **estándar estricto de modelado financiero de tres capas** que separa las **entradas de datos brutos**, los **motores de cálculo de matrices dinámicas** y la **presentación ejecutiva**. Cada hoja de cálculo tiene una responsabilidad analítica única para evitar la corrupción de fórmulas y garantizar la auditabilidad.

| Nombre de la hoja | Propósito funcional central | Capa de arquitectura |
| :--- | :--- | :--- |
| `Parameters` | ajustes globales de tesorería, umbrales de reserva de seguridad, tipos de FX y horizonte de previsión | **Entrada y configuración** |
| `Shopify_Data` | tabla de importación CSV bruta para pedidos de Shopify, devoluciones, comisiones de pasarela y liquidaciones | **Entrada de datos** |
| `Bank_Transactions` | importaciones de extractos de cuenta corriente comercial y procesadores de pago | **Entrada de datos** |
| `Accounting_Data` | asientos de AP del libro mayor, facturas de proveedores y seguimiento de facturas | **Entrada de datos** |
| `Inventory_Purchases` | órdenes de compra (POs) abiertas, porcentajes de anticipo, plazos de entrega y fechas de vencimiento | **Entrada de datos** |
| `Advertising_Spend` | gasto diario/semanal en medios pagados en Meta, Google, TikTok y agencias | **Entrada de datos** |
| `Reconciliation_Engine` | emparejamiento intersistemas automatizado de liquidaciones de pedido a banco | **Cálculo analítico** |
| `Payment_Review` | detección automatizada de facturas duplicadas y sobrepagos de AP | **Cálculo analítico** |
| `Cash_Flow_Forecast` | proyección directa de liquidez continua de 12 semanas y agregación de quema de caja | **Cálculo analítico** |
| `Inventory_Impact_Simulator` | pruebas de estrés de compras previas a la aprobación frente a reservas de caja de seguridad | **Cálculo analítico** |
| `Financial_Dashboard` | resumen ejecutivo de KPI para CEO/CFO, alertas de excepción y gráficos de liquidez | **Presentación ejecutiva** |

<details>
<summary><strong>Haz clic para expandir: diagramas de flujo de datos, tres trampas financieras y fórmulas de matrices dinámicas de Excel (LET / LAMBDA / MAP / XLOOKUP)</strong></summary>

---

<details>
<summary><strong>Flujo de datos del sistema y arquitectura de validación</strong></summary>

```text
            ┌────────────────────────────┐
            │         Data Input         │
            └─────────────┬──────────────┘
                          │
 Shopify Orders           │
 Bank Transactions        │
 Accounting Entries       │
 Purchase Orders          │
 Advertising Spend        │
 Parameters               │
                          ▼
  ┌───────────────────────────────────────────┐
  │       Analytical Calculation Layer        │
  │                                           │
  │ Reconciliation Engine                     │
  │ Payment Review                            │
  │ Cash Flow Forecast                        │
  │ Inventory Impact Simulator                │
  └───────────────────────┬───────────────────┘
                          │
                          ▼
          ┌───────────────────────────┐
          │ Executive Dashboard (CEO) │
          └───────────────────────────┘
```

El libro bloquea intencionadamente la generación directa de informes desde las entradas CSV brutas. Cada KPI del `Financial_Dashboard` proviene de hojas analíticas validadas, impulsadas por **tablas de Excel** estructuradas — lo que significa que a medida que tu número de filas crece de 100 a 50.000 transacciones, las fórmulas de matrices dinámicas se desbordan y expanden automáticamente sin arrastrar ni copiar celdas.

</details>

---

<details>
<summary><strong>Tres trampas que atrapan incluso a equipos financieros de e-commerce experimentados</strong></summary>

<details>
<summary><strong>Trampa 1 — suponer que el saldo bancario de hoy representa el fondo de maniobra disponible</strong></summary>

*   **La decisión errónea:** aprobar una orden de inventario de 180.000 $ porque la cuenta corriente tiene actualmente 420.000 $ (`$420k - $180k = $240k remaining`).
*   **Por qué falla:** el timing de caja importa más que los saldos estáticos. Tres semanas después, los pagos de saldos a proveedores, las facturas de publicidad, las nóminas y un retraso de liquidación de Shopify de 4 días colisionan en la semana 7, haciendo caer la caja real a **82.000 $** (rompiendo la **reserva de seguridad de 100.000 $**).
*   **Solución del modelo:** evalúa la liquidez proyectada tanto en la semana del anticipo inicial como en la semana del pago final antes de comprometer el dinero:

```excel
=LET(
min_cash,
XLOOKUP(
"Safety_Cash_Reserve",
Parameters[Param_Name],
Parameters[Param_Value],
50000
),
...
)
```

</details>

<details>
<summary><strong>Trampa 2 — tratar cada pedido de Shopify completado como caja cobrada</strong></summary>

* **La decisión errónea:** suponer que 615.000 $ de ventas de Shopify informadas equivalen a 615.000 $ de depósitos bancarios.
* **Por qué falla:** una liquidación puede agrupar varios pedidos; un pedido puede dividirse en liquidaciones parciales; los contracargos y las reservas de pasarela crean varianzas silenciosas.
* **Solución del modelo:** construye un índice de pedidos único y mapea dinámicamente los pagos netos esperados de Shopify frente a las entradas de referencia bancarias agregadas:

```excel
=UNIQUE(
FILTER(
Shopify_Data[Order ID],
Shopify_Data[Order ID]<>""))

```

```excel
=MAP(
A2#,
LAMBDA(order_id,
SUMIFS(
Bank_Transactions[Amount],
Bank_Transactions[Reference ID],
order_id
)))

```

</details>

<details>
<summary><strong>Trampa 3 — confiar en presupuestos mensuales estáticos durante un escalado de alta velocidad</strong></summary>

* **Caso práctico (marca Shopify de 520.000 $/mes):** con 468.000 $ de caja inicial, una OC de 210.000 $ (30 % de anticipo / 70 % de saldo) y 34.000 $/semana de gasto publicitario, los presupuestos mensuales estáticos muestran un trimestre rentable que termina en **299.400 $**. Sin embargo, la **previsión continua de 12 semanas** expone un valle temporal en la semana 7 de **95.800 $** (por debajo del límite de seguridad de 100.000 $). Al aplazar el pago del saldo al proveedor 14 días o dividir la OC en dos lotes, la marca preserva su plena continuidad operativa.

| Semana | Caja inicial | Entrada de caja | Salida de caja | Caja final | Estado de reserva |
| --- | --- | --- | --- | --- | --- |
| Semana 1 | 468.000 $ | 92.400 $ | 97.600 $ | 462.800 $ | seguro |
| Semana 3 | 459.200 $ | 86.700 $ | 158.500 $ | 387.400 $ | seguro |
| Semana 6 | 310.300 $ | 84.900 $ | 176.200 $ | 219.000 $ | seguro |
| **Semana 7** | **219.000 $** | **73.600 $** | **196.800 $** | **95.800 $** | **RUPTURA (por debajo de 100 mil $)** |
| Semana 8 | 95.800 $ | 168.700 $ | 118.500 $ | 146.000 $ | recuperado |
| Semana 12 | 264.600 $ | 170.500 $ | 135.700 $ | 299.400 $ | seguro |

</details>

</details>

---

<details>
<summary><strong>Referencia de fórmulas principales y reglas de validación de entrada</strong></summary>

<details>
<summary><strong>Referencia de fórmulas principales</strong></summary>

* **Generador de línea de tiempo continua de 12 semanas:** `=TODAY()+SEQUENCE(1,12,0,7)`

* **Agregación semanal dinámica de gasto publicitario:**

```excel
=MAP(
C1#,
LAMBDA(
week_start,
SUMIFS(
Advertising_Spend[Cost],
Advertising_Spend[Date],
">="&week_start,
Advertising_Spend[Date],
"<"&week_start+7)))

```

* **Clasificador automatizado de varianza de conciliación:**

```excel
=MAP(
D2#,
LAMBDA(diff,
IFS(
diff=0,
"Matched",
ABS(diff)<0.05,
"Minor Difference",
TRUE,
"Variance")))

```

</details>

<details>
<summary><strong>Reglas de validación de entrada</strong></summary>

| Campo de entrada | Regla de validación integrada | Comportamiento de gestión de errores del sistema |
| --- | --- | --- |
| `Order ID` | Cadena no vacía | Excluido del índice de conciliación dinámica |
| `Invoice Number` | Comprobación de duplicados `COUNTIF` | Activa una advertencia inmediata de pago duplicado de AP |
| `Payment Amount` | Validación numérica estricta | Los registros no numéricos se omiten hasta corregirse |
| `Purchase Order Value` | Valor numérico positivo | Desactiva la simulación de OC para filas inválidas |
| `Prepayment Percentage` | Decimal entre `0%` y `100%` | Activa una advertencia de rango de parámetros |
| `Safety Cash Reserve` | Umbral numérico positivo | Aplica el valor predeterminado de reserva `$50,000` si se omite |

</details>

</details>

</details>


---

## Sobre el creador y más toolkits de soporte a la decisión operativa

Construyo **modelos financieros de Microsoft Excel** ligeros y **toolkits de soporte a la decisión operativa** basados en navegador para entornos empresariales de alta velocidad donde el software fragmentado dificulta una asignación de capital fiable. Cada marco responde a una pregunta fundamental:

> *«¿Qué datos transversales deben existir en un modelo centralizado antes de poder tomar con confianza la próxima decisión financiera de alto riesgo?»*

### Explora otros modelos financieros y operativos de esta serie:

* **Libro de control de costes de proyectos de construcción y costes por trabajo**
* **Motor de decisión de gestión de ingresos y precios de e-commerce**
* **Automatización de liquidaciones y rentabilidad de vendedores de Amazon FBA**
* **Modelo de atribución de marketing multitouch de CRM y Shopify**
* **Modelo financiero de adquisición de inmuebles multifamiliares**
* **Paneles de KPI de FP&A ejecutivos y marcos de previsión continua**

Explora la biblioteca completa de hojas de cálculo de calidad comercial, simuladores web interactivos y guías de implementación en **[Theseus Workshop — Modelado financiero operativo y toolkits Excel de soporte a la decisión](https://www.theseusworkshop.com/)**.

---

## Licencia

Licenciado bajo la **Apache License 2.0**.

Este proyecto puede usarse, modificarse y distribuirse de acuerdo con los términos de la Apache License 2.0.

Consulta el archivo **LICENSE** incluido en este repositorio para obtener la información de licencia completa.
