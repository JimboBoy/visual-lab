# Visual Lab 🎨

Creative coding experiments. Each idea lives in its own branch.

## ⚠️ RULES — READ BEFORE EVERY COMMIT!!!

1. **main = NUR README!!!** Kein Code auf main. Nie. Niemals.
2. **Jede Skizze = eigener Branch** `idea/<tech>/<name>`
3. **GitHub Pages = NUR auf den Branch der aktuellen Skizze umstellen!!!** Nicht auf main!!!
4. **NIE Code auf main pushen!!!** Nie!!! Niemals!!!

## Experiments

| Branch | Description |
|---|---|
| `idea/three-js/first-sketch` | 🍩 Pastel Donut — Three.js donut with sprinkles and floating particles |
| `idea/three-js/nebula-gradient` | 🌀 Nebula Blob — Morphing blob with simplex noise and iridescent shader |

## How to view

Clone the branch you want:

```bash
git clone -b idea/three-js/nebula-gradient https://github.com/JimboBoy/visual-lab.git
```

## How to add a new sketch

```bash
git checkout main
git checkout -b idea/<tech>/<name>
# create index.html
git add index.html
git commit -m "feat: <description>"
git push origin idea/<tech>/<name>
```

**⚠️ NEVER push code to main!!! Only README.md on main!!!**
