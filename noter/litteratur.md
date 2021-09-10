# Litteratur

## Metoder til forbedring af transformer-køretid

### Udbredt metode 1: Approksimeret, hurtig attention
- Tay et al: "Efficient Transformers: A Survey" (https://arxiv.org/pdf/2009.06732.pdf). Gennemgang og taksonomi af et dusin tranformer alternativer. Her er målet stort set for alle at gøre attention <O(n). Det er oftest sparse patterns eller kernels, der erstatter prikproduktattention. Navnlig longformer (fixed patterns) og performer (kernel vha. random features) har fået opmærksomhed. 

### Udbredt metode 2: Vidensdestillering (transfer-læring)
- Sanh et al: "DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter". 40% færre parametre, 60% hurtigere, 95% GLUE. Findes en multilingual version heraf allerede brugt på dansk 

### Udbredt metode 3: Pruning
- Sajjad et al: "On the Effect of Dropping Layers of Pre-trained Transformer Models". 40% færre parametre, op til 50% hurtigere, 98% GLUE.

