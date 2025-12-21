# Low-Cost 555-Timer Boost Converter

# Summary
A 6 V → 22 V boost converter designed using a 555 ic timer switching topology to help a local business reduce supply costs. The final design met the voltage requirement using inexpensive, easily sourced components via reputable businesses.

# Background
This small local business sells light boxes but found their way of purchasing the LEDs that go inside to be inefficient and sourced cheaper light strips, however the newer strips run off 24v. They needed to somehow get their traditional 6v up to ~24v as cheaply as possible otherwise resort back to their traditional way. This is where I came in and helped by designing a boost converter that could take that 6v and boost it up to 22v as cheaply as possible. I reduced their cost by ~$2 which seems insignificant, but is actually roughly 10% of a sale. 

# Technical Overview
 * Input: 6v (4xAA cells)
 * Output goal: 25v
 * Control: 555 timer in astable mode
 * Key comnponents:
   * R1: 22k&ohm;
   * R2: 8.2k&ohm;
   * Rbias: 100k&ohm;
   * R3: 100&ohm;
   * L1: 220&mu;H
   * D1: 1N5819
   * MOSFET: IRLZ44N
   * C1: 100nF
   * C2: 10&mu;F
   * Ct: 2.2nF
   * C3: 100nF
   * C4: 100&mu;F
   * C5: 10nF
 * Measured preformance
   * Output voltage: 22.1v
   * Load size: 
   * Efficiency estimate: 

  # Future Work
