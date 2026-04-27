# Solar String Calculator

Single-page browser calculator that generates viable series/parallel string designs from solar panel and charge-controller specifications. Save named configurations to local storage and copy any option as markdown.

## Usage

Open `index.html` in any modern browser — no build step or server required.

Inputs: battery voltage; panel name, wattage and VOC; charge-controller name, max input voltage and max input wattage; plus design knobs for cold-weather VOC margin and allowed PV oversize. Output is a ranked table of `PpSs` configurations with extras (combiner box, fuses, breaker rating, cable gauge) and a "match" indicator showing controller utilisation.

## Disclaimer

> **Use at your own risk.** This software is provided "as is", without warranty of any kind. It produces electrical-design suggestions from simplified rules and the inputs you supply — review every result before acting on it, and consult a qualified electrician for any installation. See [LICENSE-2.0.txt](LICENSE-2.0.txt) for full terms.

The calculator ignores Isc, panel temperature coefficients, wire run length, and code-specific requirements. Always verify designs against the panel datasheet, controller manual, and your local electrical code before installation.

## License

Apache License 2.0 — see [LICENSE-2.0.txt](LICENSE-2.0.txt).
