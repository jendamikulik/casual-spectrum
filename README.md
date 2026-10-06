# Causal Spectrum — one seed

Živý svědek konečné Shannonovy věty (sandwich L ≤ H(S) ≤ L + (1 + log₂ e)/2)
plus Lean 4 formalizace v `finite-shannon/`.

## Spuštění

```bash
npm install
npm run dev
```

- `/` — instrument (stromy, greedy peel, CDF, sandwich) a stažení projektu
- `/dukaz` — článek k důkazu

## Lean

```bash
cd finite-shannon
lake build
```

Vyžaduje Lean 4 podle `finite-shannon/lean-toolchain`.
Soubory v `finite-shannon/CausalSeed/`: Entropy, Spectrum, Gap, Note, SecondOrder.
`lake build` neobsahuje mathlib; Lake ho stáhne podle `lake-manifest.json`.
