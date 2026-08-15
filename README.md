# ElectriCalc Pro — Support

Twelve electrical calculators for electricians, solar installers and engineers.

**[Support page](https://aneagoe87.github.io/electricalc-pro-support/)** ·
**[Privacy policy](https://aneagoe87.github.io/electricalc-pro-support/privacy.html)**

## Get help

Email **andrei.costin.neagoe@gmail.com**, or [open an issue](https://github.com/aneagoe87/electricalc-pro-support/issues).

For a calculation that looks wrong, include the numbers you entered — that is
usually enough to reproduce it immediately. Otherwise your device model, iOS
version and the app version (Settings → About) help.

## The calculators

| Tool | What it works out |
|---|---|
| Voltage Drop & Cable Sizing | Drop across a run for 1-phase, 3-phase and DC |
| Cable Ampacity & Derating | Capacity after ambient, grouping, insulation, install method |
| Motor Sizing | Full load amps and inverse-time breaker size |
| Short Circuit | Fault current at a transformer secondary |
| Conduit Fill | Maximum conductors for a conduit |
| Earth Conductor | Protective conductor by table and adiabatic equation |
| Power Factor Correction | Capacitor bank size to reach a target cos φ |
| Lighting | Fixture count by the lumen method |
| PV String Sizing | Modules per string inside the inverter DC window |
| Solar Yield | Monthly and yearly production via PVGIS |
| Battery Bank | Off-grid capacity from load and autonomy |
| Ohm's Law | V, I, R and P from any two |

## Frequently asked

**Why does the recommended cable differ from my usual answer?**
The app checks two limits, not one — voltage drop *and* current-carrying capacity
after derating. It sizes to whichever governs and tells you which. Most
calculators only check drop.

**Why is the DC voltage drop percentage blank?**
DC has no standard nominal voltage; a 12 V bank and a 600 V string are both DC.
Enter the actual bus or string voltage. The drop in volts is always shown.

**Does it work offline?**
Eleven of twelve tools run entirely on device. Only Solar Yield needs a
connection, to query PVGIS.

**IEC or NEC?**
Both, in different places. Cable sizing, ampacity and earthing follow IEC 60364;
conduit fill and breaker selection follow NEC tables. Each screen notes its basis.

## Privacy

No accounts, no analytics, no advertising, no tracking. The only data ever leaving
your device is a set of coordinates sent to PVGIS when you tap Calculate Yield.
Full detail in the [privacy policy](https://aneagoe87.github.io/electricalc-pro-support/privacy.html).

## Accuracy

Results are estimates for planning. Verify against the applicable standard, the
manufacturer's data and local regulations before installing.

---

*Independent app, not affiliated with or endorsed by the IEC, the NFPA, or the
European Commission's PVGIS service.*
