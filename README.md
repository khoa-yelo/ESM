# ESM

Embed protein with ESM-C model
https://github.com/evolutionaryscale/esm

### Usage 

```
python3 esmc.py input.csv output.pkl
```

input.csv must have at least 2 columns Protein and ID storing protein sequences and ids
output.pkl save a dictionary mapping id to embeddings including mean and max of last and layer 12
