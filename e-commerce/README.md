# The analytical tools and knowledge

## Finding if two products are substitutes or complements
[medium article](https://towardsdatascience.com/retail-analytics-a-novel-and-intuitive-way-of-finding-substitutes-and-complements-c99790800b42) and [author's jupyter notebook example](https://github.com/samread81/Instacart)

Use the shop carts information to analyze, 
To find out how two products are complements, we could use complement ratio, 

### Complement ratio for quantify the complement property
Complement Ratio = $$ \frac {A \bigcap B}{A \bigcup B} $$

The more the this ratio is close 1, the more the A and B are complements

### Substitutes ratio for quantify the substitues property
Substitutes ratio = $$ \frac {A \bigcap B} {\min(A, B)} $$


