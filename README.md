 Hi, I’m @NoraCPU


# GROMACS input files

Create an unwrapped trajectory where molecules remain intact near the boundary by typing:

```bash
# Unwrap trajectory and ensure molecules near boundaries are intact
${gmx} trjconv -f AA.xtc -s AA.tpr -o AA-molecule.xtc -pbc mol <<EOF
0
EOF
```
