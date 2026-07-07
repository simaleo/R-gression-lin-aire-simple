# Regression lineaire simple
La régression linéaire simple est une méthode statistique qui modélise la relation entre deux variables quantitatives : une variable explicative (X) et une variable à expliquer (Y).
Le modèle
On cherche à ajuster une droite qui décrit au mieux le nuage de points :
Y = β0 ​+ β1​X + ε 
    • Y : variable dépendante (à prédire) 
    • X : variable indépendante (explicative) 
    • β₀ : ordonnée à l'origine (valeur de Y quand X = 0) 
    • β₁ : pente (variation de Y pour une augmentation d'une unité de X) 
    • ε : terme d'erreur (résidu), qui capture ce que le modèle ne peut pas expliquer 
Estimation des coefficients
On utilise généralement la méthode des moindres carrés ordinaires (MCO), qui minimise la somme des carrés des résidus (écarts entre les valeurs observées et prédites).





Évaluer la qualité du modèle
    • R² (coefficient de détermination) : proportion de la variance de Y expliquée par X (entre 0 et 1, plus proche de 1 = meilleur ajustement). 
    • Erreur standard des résidus : mesure la dispersion des points autour de la droite. 
    • Test de significativité (test t) sur β₁ pour vérifier si la relation est statistiquement significative. 
Hypothèses du modèle
    1. Linéarité de la relation entre X et Y 
    2. Indépendance des résidus 
    3. Homoscédasticité (variance constante des résidus) 
    4. Normalité des résidus
