(sec:thermodynamics)=
# Thermodynamics

## Namelist options (`&thermodynamics`)

| Option        | Default   | Possible Values                   | Description |
| ------------- | --------- | --------------------------------- | ----------- |
| `lmoist`      | `.true.`  | $x \in \{$`.true.`, `.false.`$\}$ | Switch for calculation of moisture fields. |
| `chi_half`    | `0.5`     | $x \in \R$, $0 \leq x \leq 1$     | Wet, dry of intermediate (default) mixing over the cloud edge. |
| `lconstexner` | `.false.` | $x \in \{$`.true.`, `.false.`$\}$ | Keep the exner function constant in time, calculated from the initial pressure profile. |
| `lbaseexner`  | `.false.` | $x \in \{$`.true.`, `.false.`$\}$ | Switch to use the base pressure profile in the exner function. |
| `lnoclouds`   | `.false.` | $x \in \{$`.true.`, `.false.`$\}$ | Switch to disable computation of liquid water specific humidity. |
