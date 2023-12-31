**Work-In-Progress**: [Gerbers produced](https://github.com/mwrnd/HDMI_Breakout/releases/tag/v0.1-alpha) and awaiting testing.


# HDMI Breakout

[HDMI](https://en.wikipedia.org/wiki/HDMI) to [U.FL/UMCC Connector](https://en.wikipedia.org/wiki/Hirose_U.FL) breakout.

[hdmi_pmod](https://github.com/adwranovsky/hdmi_pmod) is a similar project but with a [PMOD](https://en.wikipedia.org/wiki/Pmod_Interface) interface.

![HDMI Breakout PCB](img/HDMI_Breakout.jpg)


# PCB Layout

![HDMI Breakout PCB Layout](img/HDMI_Breakout_PCB_Layout.png)

All differential signals are length-matched to within 1mm, both inter-pair and intra-pair.

I used the KiCad-included symbol and footprint for the [10029449-111RLF](https://www.digikey.com/en/products/detail/amphenol-cs-fci/10029449-111RLF/2785386). The U.FL/UMCC connectors can be [CONUFL001-SMD-T](https://www.trustedparts.com/en/search/CONUFL001-SMD-T) or [U.FL-R-SMT](https://www.trustedparts.com/en/search/U.FL-R-SMT).


# Schematic

![HDMI Breakout Schematic](img/HDMI_Breakout_Schematic.png)


# PCB Layer Stackup

4-Layer PCB stackup taken from [JLCPCB](https://jlcpcb.com/capabilities/pcb-capabilities).

![PCB Layer Stackup](img/Layer_Stackup.png)

100-ohm Differential Impedance parameters were calculated using the [DigiKey Online Calculator](https://www.digikey.com/en/resources/conversion-calculators/conversion-calculator-pcb-trace-impedance).

![PCB Differential Impedance Calculation](img/PCB_Impedance_100ohm_0.2329mm_0.2032mm_on_0.21mm_7628.png)

