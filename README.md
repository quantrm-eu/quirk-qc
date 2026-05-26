# <a href="http://algassert.com/quirk">Quirk <img src="doc/favicon.ico" alt="Icon" title="Icon" /></a>

> Refactored from &mdash; https://github.com/strilanc/quirk  Demo available on **[quantrm.eu/quantum-simulator](https://quantrm.eu/quantum-simulator)**.

Quirk is a toy quantum circuit simulator, intended to help people in learning about quantum computing.

If you want to quickly explore the behavior of a small quantum circuit, Quirk is the tool for you.


(If you're still trying to understand what a quantum circuit *even is*, then I recommend the video series [Quantum Computing for the Determined](https://www.youtube.com/playlist?list=PL1826E60FD05B44E4).
Quirk assumes you already know background facts like "each wire represents a qubit".)

**Defining features**:

- Runs in web browsers.
- Drag-and-drop circuit editing.
- Reacts, simulates, and animates in real time.
- Inline state displays.
- Bookmarkable / linkable circuits.
- Up to 16 qubits.

**Notable limitations**:

- Can't recohere measured qubits (because measurement is implemented as a hack based on the [deferred measurement principle](https://en.wikipedia.org/wiki/Deferred_Measurement_Principle)).

**Try it out**:

**[quantrm.eu/quantum-simulator](https://quantrm.eu/quantum-simulator)** (QuantRM) &mdash; or the upstream demo at **[algassert.com/quirk](http://algassert.com/quirk)**

# Examples

**Basic usage demo**:

![Demo](/doc/README_Demo.gif)

**Grover search circuit** with chance and sample displays (showing that the chance of success increases):

![Grover search](/doc/README_Grover.gif)

**Quantum teleportation circuit** with Bloch sphere displays (showing that the qubit at the top has ended up at the bottom):

![Quantum teleportation](/doc/README_Teleportation.gif)
