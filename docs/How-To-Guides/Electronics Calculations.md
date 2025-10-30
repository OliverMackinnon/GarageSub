### Steps for finding proper cable AWG:

1.  Finding Maximum Allowed Voltage Drop

The ROV needs at least 12V to run. It cannot have above 12 volts. To
find the maximum allowed voltage drop you can use the following formula:

$$V_{drop\ max} = V_{supply} - V_{minimum}$$

Therefore:

$20V - 12V = 8V$ Maximum

2.  Finding Maximum Allowed Resistance

Using Ohm's Law you can find the maximum resistance the tether can have:

$$V_{drop} = IR$$

Rearranging:

$$R = \frac{V_{drop}}{I}$$

Therefore:

$$R = \frac{8V}{50A} = .16\Omega$$

3.  Finding Maximum Resistance per Meter

A circuit required a two wires (a positive and a negative), so the
current must travel twice the length of the tether. When using wire
length this means the voltage is dropping because of resistance getting
there and coming back.

Finding total wire length:

$$L_{total} = 2*L_{tether}$$

$$L_{tether} = 2*100ft = 200ft$$

Converting to meters:

$1\ m = \ 3.28ft$ $\frac{200ft}{3.28\frac{ft}{m}} = 60.98m$

Finding total resistance per meter:

$$\frac{.16\Omega}{60.98m} = .00262\frac{\Omega}{m}$$

4.  Finding current AWG based on chart:
<img width="1865" height="960" alt="image" src="https://github.com/user-attachments/assets/e1fded3f-a896-498b-93ca-04d020759b73" />


Therefore, when using copper wire at minimum, a 9 AWG wire must be use

### Finding necessary battery size:

An education group would like to let students test out a commercial ROV
that runs on around 16V. The onboard electronics use around 1A
regardless of motor use. Each motor at its highest thrust uses around 18
amps. If an ROV is in a vectored configuration at full throttle going
forwards it will have four motors at full thrust. Assuming students want
to see the ROV move fast and therefore only use it at full throttle what
size must a battery be to accommodate a student group using the ROV for
2 hours?

1.  Finding current draw:

$$I = 1A + 4*18A = 73A$$

2.  Finding power:

$$P = I*V$$

$$P = 73A*16V = 1168W$$

3.  Finding energy use:

$$E = P*t$$

$$E = 1168*2h = 2336Wh$$

$$.00262\frac{\Omega}{m}$$

