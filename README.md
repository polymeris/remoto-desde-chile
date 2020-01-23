
# remoto-desde-chile
Guías y recursos para trabajo remoto desde Chile. En general enfocado a desarrolladores y profesiones afines.

---

⚠️ **Ninguno de nosotros es abogado, ni asesor financiero o tributario. La información en este repositorio NO constituye asesoramiento de ningun tipo. Consulta con un profesional.** ⚠️

---


## Encuentra trabajo

### Formas de trabajo

A grandes rasgos tienes 3 opciones:

1. Trabajar independiente (como _contractor_), sea freelanceando para varias empresas o para una sola. Algunas empresas te tratarán como un empleado más aunque técnicamente no lo seas, aunque probablemente no recibas los beneficios que reciben los locales, como seguros de salud.
2. Crear una empresa individual en el extranjero y auto-contratarte en esta. Esto puede tener muchos beneficios financieros, pero es una opción mucho más engorrosa.
3. Trabajar para una empresa chilena que preste servicios a un tercero en el extranjero. Esto te ahorra la pega de buscar tus propios proyectos y clientes, pero tienes que tener cuidado: muchas de estas empresas chilenas funcionan como moledoras de carne, no te pagan si no tienes un proyecto, y cuando lo tienes cortan una buena tajada (40% a veces!)

Esta guía en general se enfoca en la primera opción.

### Preparación

TODO

### Dónde encontrar trabajo

TODO

## ¿Cuánto cobro?

Harto. Por favor, aprovecha que hay demanda de desarrolladores y cobra caro, nos beneficia a todos que "desarrollador/a en Chile" no sea sinónimo de bajo presupuesto.

GitLab es transparente con sus salarios y tiene [una calculadora online](https://about.gitlab.com/handbook/people-group/global-compensation/calculator/), para que lo uses de punto de partida. Parte negociando con un 20-30% más de lo que dice la calculadora.

Si trabajas como freelancer por hora o día, cobra el doble, tienes que pagar las horas que pasarás buscando proyectos y el tiempo que te dejarán esperando.

## Recibe tu sueldo

### Métodos

#### Transferwise

Limitaciones:
* para Chile, hay un monto máximo mensual

Ventajas:
* relativamente barato
* todo online

#### Cuenta en el extranjero

Limitaciones:
* dificil (o imposible) de abrir, dependiendo del país.
* no es una solución completa ya que igual tienes que enviar el dinero a Chile de alguna manera

Ventajas:
* probablemente más simple para tu empleador
* puedes ahorrar/invertir en el extranjero

#### Transferencia Bancaria Internacional

El empleador te envía un pago (conocido por los bancos como "remesa") el cual llega a Chile directamente a tu banco. Para que te puedan enviar este dinero a tu nombre, tienes que entregar los siguientes datos a tu empleador:

    Name: Tu nombre completo
    ID: 11.111.111-1 (tu rut)
    Beneficiary Account: xx-xxx-xxxxx-xx (el número de tu cuenta)
    Bank: Banco de Chile - Santiago de Chile
    Branch: Ahumada 251 - Santiago
    Swift Code: Swift code de tu banco (consultar con ejecutivo de cuentas)

**Tip**: No es muy común recibir pagos del extranjero, por lo que muchas veces los ejecutivos no tienen idea de esta información. Para evitar confusiones, siempre nombrar la palabra "remesa" al referirse a tu pago.

Puedes recibir tus pagos en cualquier cuenta corriente o vista (ejemplo: [Cuenta RUT](https://www.bancoestado.cl/imagenes/_personas/productos/cuentas/cuenta-rut-home.asp)) que tengas. Sin embargo, siempre consulta con tu ejecutivo de cuentas para proceder. Otra opción es obtener cuenta corriente en dólares y recibir el dinero ahí.

En ambos casos, los datos que debes enviar son los mismos, pero el funcionamiento (como obtienes finalmente tu dinero) es distinto:

##### *Cuenta Corriente* o *Cuenta Vista en Chile*, en pesos chilenos (CLP)

Una vez le pasaste los datos de transferencia a tu empleador:

- él hará una transferencia del pago (en dólares) de su banco al tuyo.
- el pago se demora 1 o dos días hábiles "en llegar".

Ahora el dinero está a tu nombre, en Chile y en tu banco... pero no en tu cuenta. Recuerda que te llegaron USD, así que no puedes pasarlo directamente a tu cuenta en CLP. ¿Qué hacer?

- BancoEstado (Cuenta RUT):
  - debes llamar por teléfono al banco para preguntar si te llegó una remesa. Si llegó...
  - debes ir a una surcursal de BancoEstado que tenga "Banca Internacional".
  - habla con el ejecutivo de "inversiones" de la sucursal (toma número para esta fila y para caja, BancoEstado se llena mucho...)
  - el ejecutivo te generará un Voucher que debes pagar en caja (son las comisiones del Banco, 0.6%)
  - con el número que ya sacaste, espera tu turno en Caja.
  - en Caja, paga la comisión del Banco y aquí puedes pedir los dólares en efectivo o que te abonen los dólares a tu cuenta vista. Los dólares en efectivo te sirven por si quieres venderlo a alguien que te de más dinero por ellos.

- BancoEdwards/Chile:
  - Lo mismo que con banco estado, solo que te llega un correo automáticamente diciendo que ya que llegó el pago 🥰 
  - La comisión es MUY parecida (~0.6%).
  
Nota personal: creo que en todos los bancos va a ser parecido. Espero que alguno tenga opción para hacer este trámite _remotamente_... sin embargo, si vas a recibir muchos sueldos, es mejor recibir en una cuenta corriente en dólares.

##### Cuenta corriente en Chile, en dólares

TODO.
                         
## Paga impuestos, salud y cotizaciones

### Emisión de boletas

Suponiendo que la empresa para la que trabajas no tiene presencia legal en Chile, debes emitir boleta de honorarios via [la página web del SII](http://homer.sii.cl/). Elige la opción que el contribuyente emisor (tú) retiene el Pago Provisional Mensual.

![El contribuyente emisor será quien se encargue de la retenció del porcentaje vigente de Pago Provisional Mensual](img/sii-retencion-emisor.png)

El SII tiene un RUT especial para empresas extranjeras: 44.444.446-0. En el campo de región puedes poner cualquier cosa, pero la dirección debería ser la real de la empresa.

Si te pagan en dólares, usa la [tabla dólar-peso del SII](http://www.sii.cl/valores_y_fechas/dolar/dolar2020.htm) para convertir el total.

### Impuestos mensuales

Si tu retuviste el Pago Provisional Mensual al emitir la boleta, debes declarar (**y, muy importante, pagar!**) impuestos mensuales usando el formulario F29 [la web del SII](http://homer.sii.cl/). La página calcula el monto por ti a partir de las boletas electrónicas del mes anterior, y luego puedes pagar online con tu banco. Cuando se habla de "devolución de impuestos" este es el dinero que se te devuelve, si sobra algo luego de tramitar tu declaración de impuestos anual.

### Cotizaciones mensuales

Tienes la opción de pagar AFP y Salud mensualmente o anualmente. Más abajo se explica como pagarlas anualmente.

(TODO: explicar pago mensual usando previred)

### Declaración anual

La "operación renta" es el cálculo y pago de impuestos y cotizaciones que cada año tienes que hacer del año anterior. Por ejemplo en Abril del 2021 paga impuestos sobre lo que ganaste el año 2020.
Si eres independiente en esta ocasión también tienes que pagar tus cotizaciones (TODO buscar excepciones).

El cálculo del monto exacto es bastante complicado, pero **simplificando mucho** la idea general es que de la suma de lo que pagaste mensualmente se le restan los impuestos, salud y AFP. Si sobra, te devuelven. Si falta, te lo cobran.

El SII te prepara una propuesta de formulario F22 con la información que tiene de tus pagos mensuales y lo que le informan diversas instituciones.

La empresa para la que trabajas en el extranjero tendrá que declarar lo que te paga también. Es probable que para esto te pidan una declaración de que no pagas impuestos allá, y que tu te haces responsable por pagar tus impuestos en Chile. En el caso de empresas de EEUU esto se hace con [el formulario W-8](https://www.irs.gov/pub/irs-pdf/fw8ben.pdf).

#### Impuestos en la declaración anual

Hay distintos tipos de impuestos anuales, pero si tu ingreso principal es por boletas a una empresa extranjera, te interesa el _Impuesto Global Complementario_. Este se aplica sobre la base imponible, esto es, lo que ganaste el año anterior, menos todas las cosas que le puedas deducir, como cotizaciones, APV, gastos presuntos, etc. 

Todo esto el SII lo calcula por ti, pero si quieres saber cuanto pagarás (...TODO: explicar como calcular en base a tabla)

#### Cotizaciones en la declaración anual

Las cotizaciones de los trabajadores independientes se calculan en su declaración de renta anual. Entre los años 2019 y 2027 puedes elegir entre una cotización total o parcial. El 2019 la cotización parcial fue 5% de la total e irá subiendo todos los años.

Si pagas total, la AFP corresponde a 10% de tu base imponible (que es lo que ganaste el año anterior con un tope de aprox 80UF por mes), más la comisión de la AFP. Por ejemplo si ganaste 1 millón al mes, y la comisón de AFP es 1.5% pagarás `$1.000.000 * 12 * 0,1115 ~= $1.340.000`, mientras que si ganaste 3 millones al mes pagarás lo mismo que si ganaras 2.3 millones, que es aproximadamente el tope: `$2.300.000 * 12 * 0,115 ~= $3.000.000`.

El monto que pagas en salud, si optas por total depende del plan de Isapre que tengas, o si estás en Fonasa pagas un 7%, también considerando la base imponible del párrafo anterior.

Si optas por cotización parcial, pagarás mucho menos, pero quedarás con cobertura parcial de salud a menos que pagues la diferencia durante el año. Y obviamente, ahorras menos en tu AFP. El porcentaje que pagas en cotización parcial comparado con total es:

| Año  | Porcentaje |
|------|------------|
| 2020 | 17%        |
| 2021 | 27%        |
| 2022 | 37%        |
| 2023 | 47%        |
| 2024 | 57%        |
| 2025 | 70%        |
| 2026 | 80%        |
| 2027 | 90%        |

Además de AFP y Salud, pagas algunas cosas chicas como seguros de invalidez y de accidentes de trabajo.

El SII tiene [algunos ejemplos online](http://www.sii.cl/destacados/renta/2019/casos_declarar.html) para entender mejor esta diferencia.

## Stock options/RSUs

Primero, nuevamente el disclaimer: Estas cosas son complicadas y puedes perder **mucha** plata invirtiendo y/o pagando impuestos. Si tienes stock options o algo así, asume que todo lo que dice aquí es falso y habla con profesionales financieros y tributarios.

Stock options y RSUs son beneficios que te dan algunas empresas como complemento de tu sueldo. La idea es que si a la empresa le va bien, tu también ganas.

Los stock options en general son entregados por startups, y consisten en la _opción_ de comprar acciones a un precio determinado, el llamado _strike price_. En caso de que la empresa crezca, se asume que el valor real de las acciones irá aumentando mientras el strike price se mantiene. Si el startup falla (que es probable!) o su valor no aumenta, las opciones **no valen nada**.

Por ejemplo te podrían ofrecer 30.000 options con un strike price de $1 cuando entras a trabajar. 4 años después, la empresa se vende (o entra a la bolsa) y sus acciones valen $5. En principio, esto significa que puedes _ejercer_ tus opciones por $30.000 y venderlas por $150.000, ganando $120.000, menos impuestos.

¿Porqué "en principio"? Porque hay muchos factores que pueden cambiar esto. Por ejemplo, en algunos casos la empresa tiene que levantar capital en malas condiciones y se ve obligada a emitir _preferred stock_ a los nuevos inversionistas. Luego la empresa se vende y los empleados con acciones comunes y corrientes no reciben un peso. Como dije, es complicado, asesórate.

Además, típicamente no te dan todo las opciones o RSUs inmediatamente, si no que te las van entregando gradualmente en un proceso que se llama [vesting](https://carta.com/blog/what-is-stock-vesting/).

Para ejecer tus stock options eventualmente tendrás que tener dólares (o la moneda en la que se vendan las acciones), para poder pagarle a tu empresa. Si quieres poder hacerlo, probablemente te conviene ir ahorrando dólares desde un comienzo y encontrar una manera de transferir que no sea excesivamente cara, usando uno de los métodos descritos en "Recibe tu sueldo" pero a la inversa.

Las RSUs en general son entregadas por empresas que ya son públicas o más establecidas. Es parecido a tener un stock option con strike price de $0, esto es, no tienes que ejercerlas, te dan las acciones directamente.

## Tengo más preguntas

Pásate por el canal #remoto de [el slack de devschile](https://devschile.cl/).
