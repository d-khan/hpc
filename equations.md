# Equations

## Q = CV

**The amount of electric charge needed to bring a capacitor (or a CPU wire) to a certain voltage depends on its capacitance and the voltage applied.**

Think of it this way:
* Q (Charge): How much electric charge is needed or stored. Measured in coulombs (C).
* C (Capacitance): How much charge the capacitor or wire can hold for each volt. Measured in farads (F).
* V (Voltage): The electrical pressure that causes charge to move. Measured in volts (V).

Imagine a tiny wire connected to a transistor.

Suppose:
* The wire has a capacitance of 2 picofarads (pF).
* We want to raise its voltage from 0 V to 1 V.

$$ Q = CV $$

$$ Q = 2 \times 10^{-12} \times 1 $$

$$ Q = 2\ \text{picocoulombs} $$

If we reduce the capacitance of a transistor or wire, we need less charge to change its voltage.

Less charge movement generally means less energy consumed during switching.

Remember: \(Q=CV\) tells us how much charge must be moved to establish a given voltage across a capacitance.


## Energy Stored in a Capacitor

$$
E = \frac{1}{2}CV^2
$$

**The amount of electrical energy stored in a capacitor when it is charged to a given voltage.**

Where:
- **E** = Energy stored (joules, J)
- **C** = Capacitance (farads, F)
- **V** = Voltage (volts, V)


### Derivation

Start with the charge equation:

$$
Q = CV
$$

Electrical energy is charge multiplied by voltage.
When charging an initially empty capacitor, the voltage
increases from 0 to V.

The average voltage with respect to charge is:

$$
V_{\mathrm{average}} = \frac{0+V}{2} = \frac{V}{2}
$$

Therefore:

$$
E = Q \times V_{\mathrm{average}}
$$

$$
E = Q \times \frac{V}{2}
$$

Substitute Q = CV:

$$
E = CV \times \frac{V}{2}
$$

Finally:

$$
E = \frac{1}{2}CV^2
$$

#### Example: CPU Wire

Suppose:
- Capacitance = 2 picofarads (pF)
- Voltage = 1 volt (V)

$$
E = \frac{1}{2}(2 \times 10^{-12})(1)^2
$$

$$
E = 1 \times 10^{-12}\,\mathrm{J}
$$

$$
E = 1\,\mathrm{pJ}
$$

**Meaning:** The CPU wire stores 1 picojoule of
energy when charged from 0 V to 1 V.

