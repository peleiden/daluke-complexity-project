# Noter til kompleksitetsreduktion

Hvad er vores plan med kompleksitetsreduktion?
- At lave en mere tids/hukommelses-effektiv inferensmodel?
- At lave en model, der overfitter mindre på entities?

Den første er overkommelig; den anden er interessant sideeffekt.
Der er en masse litteratur med effektive transformere: https://arxiv.org/pdf/2009.06732.pdf
Her er f.eks. performere populære, men der er også mange andre.
Det er dog ikke helt sikkert, at dette er egnet her.

Til gengæld er der frugtbar litteratur inden for pruning og destillation:
https://arxiv.org/pdf/2004.03844.pdf
Jeg synes, det ser mest lovende ud for destillation. 
