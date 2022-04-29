

## Data shift 

create a table 1 to provide cohort information before switching to another dataset!

label shift: label was 'type 2 diabetes', but now it's become 'diabetes'. p0(y|x) is not the same as p1(y|x)

covariate shift: p0(x) is not the same as p1(x)

- adversarial perturbations: add a small noise, the classification of image becomes different. e.g. melanoma
- q(x,y) = q(x)p(y|x), where p(y|x) is pre-trained conditional distribution
- Transfer learning
  - linear model: original representation, modify weights. Min L(w, d)+lambda(w, w_old) so that new w is close to w_old

when changing setting

- population difference: diseases for older population (diabetes), trained for older population and applied in a younger 
- calibration of instruments (machines), set up differently; procedures could be different

