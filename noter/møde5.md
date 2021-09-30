# Vores input

- Vis DaLUKE's robusthedstal
- Tal om rapport vs. evt. artikel: Skal vi to forskellige, hvor rapport er en 10-siders, mere grundig beskrivelse? Hvor meget må rapporten antage, at læseren ved om DaLUKE? Den evt. artikel: Hvor målrettet en undersøgelse skal den være? Hvad med at præsentere DaLUKE som et case til at opnå bedst mulig NLP i begrænset-ressouce sprog og så præsentere forskellige eksperimenter med konklusioner om dataaugmentering, eksplicit/implicit viden og fart/performance-tradeoff?
- RoBERTa virker nu med ord-accuracy
- Vi er igang med at få en træning igang, problemer med EPYC
- Dimensioner: Vi har styr på PCA, og har en mulig løsning med fire V-matricer
- Det er ikke lykkedes mig at lave tidssammenligning med eksterne modeller

# Mødereferat
- Robusthed og bias: DaLUKE ligger fint, lad os undersøge, hvilken del af BERT modellerer navne?
- Data: Det virker ikke lige nu med HPC'en: Databygningsscript dør og går i zombie-mode
- Dimensioner: Det giver god mening at have flere value og summe over dem
- Artikel kan godt være rapporten til kurset
- Artiklens pointe kunne være at lavressource => en masse problemer 
- Kan overveje lavrangsapproksimation af laveredimensionelle i inferens
- Tidssammenling er udfordrende; vi må nok fokusere på at sammenligne vores egne modeller
