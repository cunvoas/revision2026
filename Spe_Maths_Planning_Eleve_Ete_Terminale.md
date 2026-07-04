# ☀️ Programme d'Été — Spécialité Mathématiques Terminale
## 1h30 par jour, 5 jours par semaine — Pour préparer sa terminale

> **Objectif** : Arriver serein en terminale avec des bases solides, surtout sur les SUITES (priorité n°1 du programme)
> **Rythme** : 1h15 de travail actif + 15 min de révision/vidéo chaque jour
> **Total** : ~60h de travail sur 8 semaines

---

## 📋 Mode d'emploi

```
🕐 1h30 par jour = 
   • 10 min  → Réactivation (petit quiz/rappel de la veille)
   • 30 min  → Cours (lire, regarder vidéo, prendre notes)
   • 35 min  → Exercices (progressifs, chronométrés)
   • 15 min  → Correction + fiche révision
```

| Symbole | Signification |
|---|---|
| 📺 | Vidéo à regarder |
| 📝 | Exercice écrit |
| ✅ | Corrigé disponible |
| 🔑 | Point clé à retenir |
| 💻 | Activité Python/calculatrice |

---

# 📅 Semaine 1 — SUITES (Priorité absolue)

### Jour 1 — Vocabulaire & suites explicites
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Rappels suites 1ère](https://www.youtube.com/watch?v=CDMol9f8vgc) | 10 min |
| 📖 | **Cours** : Suite = fonction ℕ→ℝ. Modes de génération : explicite u_n=f(n) / récurrente u_{n+1}=f(u_n). Arthmétique : u_{n+1}=u_n+r, u_n=u_0+nr, S_n=n(u_0+u_n)/2. Géométrique : u_{n+1}=q×u_n, u_n=u_0×q^n, S_n=u_0×(1−q^{n+1})/(1−q) | 20 min |
| 📝 | **Exos** : Soit u_n=3n²−2n+1. Calculer u_0, u_1, u_5. Nature ? Soit v_n arithmétique, r=−2, v_0=10. Calculer v_10 et S_10. Soit w_n géométrique, q=1.5, w_0=100. Calculer w_4 et S_4. | 30 min |
| ✅ | **Correction** : Vérifier chaque résultat. Repérer les erreurs de signe. | 15 min |
| 🔑 | **Fiche** : Notes formules suites arithmétiques & géométriques + domaines | 15 min |

### Jour 2 — Suites définies par récurrence
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Calcul des premiers termes](https://www.youtube.com/watch?v=MJv7_pkFcdA) | 8 min |
| 📖 | **Cours** : u_{n+1}=f(u_n). Méthode graphique (toile d'araignée). Attention : il faut un premier terme + une relation. Représentation : placer u_0 sur l'axe, tracer f, construire u_1=f(u_0), etc. | 22 min |
| 📝 | **Exos** : u_{n+1}=2u_n+3, u_0=1. Calculer u_1, u_2, u_3. Même chose pour v_{n+1}=√(v_n+5), v_0=0. Conjecturer le sens de variation sur les premiers termes. | 35 min |
| ✅ | **Correction** | 15 min |
| 💻 | **Python** : Programmer le calcul des 10 premiers termes d'une suite récurrente | 10 min |

### Jour 3 — Sens de variation
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Cours suites Terminale](https://www.youtube.com/watch?v=MJv7_pkFcdA) (début) | 15 min |
| 📖 | **Cours** : Deux méthodes : (1) u_{n+1}−u_n → étudier le signe. (2) Si u_n>0, u_{n+1}/u_n → comparer à 1. Suite croissante ⇔ ∀n, u_{n+1}≥u_n. Décroissante ⇔ ∀n, u_{n+1}≤u_n. | 25 min |
| 📝 | **Exos** : Étudier variations de u_n=2n²−5n+3 (signe de u_{n+1}−u_n). u_n=3^n/(n+1) (méthode quotient). u_{n+1}=½u_n+2, u_0=1 (conjecture graphique puis preuve). | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 4 — Raisonnement par récurrence
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Démonstration par récurrence](https://www.youtube.com/watch?v=R3Vsbifexak) | 12 min |
| 📖 | **Cours** : Principe : Initialisation (P(0) vraie) + Hérédité (P(n)⇒P(n+1)) → P vraie ∀n. Structure de rédaction obligatoire. | 20 min |
| 📝 | **Exos** : Soit u_n définie par u_0=2, u_{n+1}=u_n+3. Montrer par récurrence que u_n=3n+2. Soit v_{n+1}=3v_n+1, v_0=0. Montrer que v_n=(3^n−1)/2. | 38 min |
| ✅ | **Correction** — Vérifier chaque étape de la rédaction | 15 min |
| 🔑 | **Fiche** : Structure type d'une récurrence + 3 exemples rédigés | 5 min |

### Jour 5 — Suites arithmético-géométriques & bilan semaine 1
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Exercice bac suites](https://www.youtube.com/watch?v=MJv7_pkFcdA) (2e partie) | 15 min |
| 📖 | **Cours** : Suite u_{n+1}=au_n+b (a≠1). Méthode : trouver α tel que α=aα+b (point fixe), poser v_n=u_n−α. Alors v_n est géométrique de raison a. | 20 min |
| 📝 | **Exos** : u_{n+1}=0.6u_n+40, u_0=10. Déterminer α, v_n, forme explicite u_n, limite. | 30 min |
| ✅ | **Mini-test** 30 min : 2 exos sur les suites (récurrence + arithmético-géométrique) | 30 min |
| 📝 | **Auto-correction** | 15 min |

> **🎯 Objectif semaine 1** : Maîtriser les suites arithmétiques/géométriques, la récurrence, les bases des suites récurrentes

---

# 📅 Semaine 2 — SUITES (Suite) — Le cœur de l'analyse

### Jour 6 — Notion de limite d'une suite
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Limites de suites](https://www.youtube.com/playlist?list=PLSOFOcyBRpIhr1jogSEza8lFSJ8sFCuKb) (v1-v2) | 14 min |
| 📖 | **Cours** : Définition intuitive : "u_n tend vers ℓ si pour tout intervalle ouvert contenant ℓ, tous les termes sont dedans à partir d'un certain rang". Limites de référence : 1/n→0, 1/n²→0, 1/√n→0. q^n : si q>1 → +∞, si −1<q<1 → 0, si q≤−1 → pas de limite. | 25 min |
| 📝 | **Exos** : Sans calculatrice : lim 1/(n+1), lim 3−5/n, lim (0.8)^n, lim (−0.9)^n, lim (1.1)^n, lim (2n+3)/(n−1). | 35 min |
| ✅ | **Correction** | 16 min |

### Jour 7 — Opérations sur les limites
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Limites suites](https://www.youtube.com/watch?v=aSBGk_GEEew) | 15 min |
| 📖 | **Cours** : Tableaux des opérations (somme, produit, quotient). Formes indéterminées : ∞−∞, 0×∞, ∞/∞, 0/0. Technique : factoriser par le terme dominant. | 25 min |
| 📝 | **Exos** : lim (n²+3n)/(2n²−n+1). lim (3n−√n)/(5n+2). lim (n+1)/n! → montrer vers 0. lim (√(n²+2n)−n) | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 8 — Théorèmes de comparaison & des gendarmes
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Théorème des gendarmes](https://www.youtube.com/watch?v=qIBlhdofYFI) | 10 min |
| 📖 | **Cours** : Comparaison : u_n≤v_n avec lim u_n=+∞ ⇒ lim v_n=+∞. Gendarmes : u_n≤w_n≤v_n avec lim u_n=lim v_n=ℓ ⇒ lim w_n=ℓ. Inégalité de Bernoulli : (1+h)^n ≥ 1+nh pour h>−1. | 25 min |
| 📝 | **Exos** : En utilisant le théorème : lim (sin n)/n. lim (1+1/n)^n. lim (2^n)/(n+1). lim (n cos n)/(n²+1). | 40 min |
| ✅ | **Correction** | 15 min |
| 🔑 | **Fiche** : Tableau des FI + stratégies de factorisation + gendarmes | 5 min |

### Jour 9 — Convergence monotone & suite majorée/minorée
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Théorème convergence monotone](https://www.youtube.com/watch?v=rttQIYOKCRQ) | 12 min |
| 📖 | **Cours** : Suite majorée (u_n≤M), minorée (u_n≥m), bornée. Théorème fondamental : toute suite croissante majorée converge. Toute suite décroissante minorée converge. Suite croissante non majorée → +∞. | 25 min |
| 📝 | **Exos** : Soit u_n=3−1/n. Montrer qu'elle est majorée, croissante, convergente. Soit v_{n+1}=√(v_n+2), v_0=0. Montrer 0≤v_n≤2, croissante, convergence. Déterminer limite (point fixe ℓ=√(ℓ+2) ⇒ ℓ=2). | 38 min |
| ✅ | **Correction** | 15 min |

### Jour 10 — Suites récurrentes (méthode complète) & bilan semaine 2
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Suites récurrentes méthode complète](https://www.youtube.com/playlist?list=PLSOFOcyBRpIhr1jogSEza8lFSJ8sFCuKb) (v7-10) | 20 min |
| 📖 | **Cours** : Méthode type bac : ① Étudier f (domaine, variations, point fixe f(ℓ)=ℓ) ② Montrer u_n∈I stable ③ Monotonie (signe f(x)−x sur I) ④ Convergence ⇒ passage à la limite ⇒ f(ℓ)=ℓ | 15 min |
| 📝 | **Mini-test** 40 min : 2 sujets type bac sur les suites (récurrence + récurrente + limite) | 40 min |
| ✅ | **Correction commentée** | 15 min |
| 🔑 | **Fiche résumé chapitre suites 1 page** : Définitions, formules, méthodes, théorèmes | 15 min |

> **🎯 Objectif semaine 2** : Maîtriser limites, gendarmes, convergence monotone, suites récurrentes

---

# 📅 Semaine 3 — FONCTIONS : Limites, continuité, TVI

### Jour 11 — Limites de fonctions (rappel 1ère + nouveau)
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Limites de fonctions](https://www.youtube.com/watch?v=MJv7_pkFcdA) | 15 min |
| 📖 | **Cours** : Limite finie/infinie en +∞/−∞/en un point. Asymptote horizontale/verticale. Factorisation par le terme de plus haut degré. | 25 min |
| 📝 | **Exos** : lim_{x→+∞} (3x²−2x+1)/(x²+5). lim_{x→+∞} (√(x+1)−√x). lim_{x→2} (x²−4)/(x−2). | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 12 — Continuité & TVI
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Continuité TVI](https://www.youtube.com/watch?v=rttQIYOKCRQ) | 12 min |
| 📖 | **Cours** : Une fonction est continue si sa courbe se trace sans lever le crayon. Toute fonction dérivable est continue. Théorème des valeurs intermédiaires (TVI) : si f continue sur [a,b] et k entre f(a) et f(b), alors ∃c∈[a,b] tel que f(c)=k. | 25 min |
| 📝 | **Exos** : f(x)=x³−3x+1. Montrer que f(x)=0 a exactement 3 solutions réelles (tableau variations + TVI répété). f(x)=e^x+x−2. Montrer qu'il existe une unique solution. Encadrer à 0.1 près. | 38 min |
| ✅ | **Correction** | 15 min |

### Jour 13 — Fonction exponentielle (révision 1ère)
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Fonction exponentielle](https://www.youtube.com/playlist?list=PLSOFOcyBRpIibAHTL_6vipZQog_LPaRDN) | 15 min |
| 📖 | **Cours** : Rappels : exp(x) unique fonction telle que f'=f et f(0)=1. Propriétés : exp(a+b)=exp(a)exp(b), exp(x)>0, limite en +∞ = +∞, en −∞ = 0. Dérivée e^{u(x)} = u'(x)e^{u(x)}. | 25 min |
| 📝 | **Exos** : Simplifier e^{2x}×e^{−3x}/(e^{x+1}). Dériver f(x)=e^{−3x+2}, g(x)=xe^{x}. Étudier variations f(x)=e^x/x. | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 14 — Dérivation (compléments terminale)
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Dérivation](https://www.youtube.com/watch?v=MJv7_pkFcdA) | 15 min |
| 📖 | **Cours** : Rappels dérivées usuelles (x^n, exp, 1/x, √x). Dérivée d'une composée : (g∘f)' = f'×g'∘f. Dérivée seconde et convexité. | 25 min |
| 📝 | **Exos** : Dériver f(x)=sin(3x+2), g(x)=e^{−x²}, h(x)=ln(x²+1). Tableau variations complet f(x)=(2x+1)/(x−3). | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 15 — Bilan semaine 3 : Limites, TVI, exponentielle, dérivation
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Mini-test** 40 min : 3 exercices mélangeant limites, TVI, exponentielle, dérivée | 40 min |
| ✅ | **Auto-correction** | 20 min |
| 🔑 | **Fiche** : Tableau dérivées + TVI + limites de référence | 30 min |

> **🎯 Objectif semaine 3** : Maîtriser limites fonctions, TVI, exponentielle, dérivées composées

---

# 📅 Semaine 4 — LOGARITHME, TRIGO & CONVEXITÉ

### Jour 16 — Fonction logarithme népérien
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Logarithme népérien](https://www.youtube.com/watch?v=MJv7_pkFcdA) (extrait) | 15 min |
| 📖 | **Cours** : ln(x) définie sur ]0,+∞[, ln(ab)=ln a+ln b, ln(a/b)=ln a−ln b, ln(a^n)=n ln a. ln(1)=0, ln(e)=1. Dérivée ln'(x)=1/x. ln(x) +∞ → +∞, 0⁺ → −∞. Croissances comparées : ln x / x → 0 en +∞, x ln x → 0 en 0⁺. | 25 min |
| 📝 | **Exos** : Simplifier ln(2)+ln(8)−ln(4). Résoudre ln(3x−2)=1. Dériver f(x)=ln(x²+3x). Étudier variations f(x)=x−ln x. | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 17 — Logarithmes & limites
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Logarithmes](https://www.youtube.com/playlist?list=PLSOFOcyBRpIhr1jogSEza8lFSJ8sFCuKb) | 12 min |
| 📖 | **Cours** : Les 4 limites à connaître : lim_{0⁺} ln x = −∞, lim_{+∞} ln x = +∞, lim_{+∞} ln x/x = 0, lim_{0⁺} x ln x = 0. Composée ln(u) : dérivée u'/u définie si u>0. | 22 min |
| 📝 | **Exos** : lim_{x→+∞} ln x / x². lim_{x→0⁺} x² ln x. lim_{x→+∞} (ln x)²/x. lim_{x→1} ln x/(x−1). Dériver f(x)=ln(√(x+1)). | 35 min |
| ✅ | **Correction** | 16 min |
| 🔑 | **Fiche** : Propriétés ln + 4 limites à connaître | 5 min |

### Jour 18 — Fonctions sinus et cosinus
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Fonctions trigo](https://www.youtube.com/watch?v=MJv7_pkFcdA) (extrait) | 12 min |
| 📖 | **Cours** : sin'(x)=cos(x), cos'(x)=−sin(x). Sinus impair, cosinus pair. Périodiques 2π. Bornées entre −1 et 1. Dérivée composée : sin'(ax+b)=a cos(ax+b). | 25 min |
| 📝 | **Exos** : Dériver f(x)=sin(3x), g(x)=cos²x, h(x)=sin(x)/x. Étudier variations f(x)=2cos x−x sur [0,2π]. lim_{x→0} sin(3x)/(2x) = 3/2. | 38 min |
| ✅ | **Correction** | 15 min |

### Jour 19 — Convexité
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Convexité](https://www.youtube.com/watch?v=MJv7_pkFcdA) (extrait) | 10 min |
| 📖 | **Cours** : f convexe ⇔ f''(x)≥0 (courbe au-dessus tangentes). f concave ⇔ f''(x)≤0 (courbe en-dessous). Point d'inflexion : f'' change de signe. Convexité de référence : e^x convexe, ln(x) concave, x² convexe. | 25 min |
| 📝 | **Exos** : f(x)=x³−3x²+x. Calculer f'', convexité/concavité, points d'inflexion. Montrer que pour tout x, e^x ≥ 1+x (convexité). | 38 min |
| ✅ | **Correction** | 15 min |

### Jour 20 — Bilan semaine 4 : Logarithme, trigonométrie, convexité
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Mini-test** 40 min : 4 petits exercices (ln, trigo, convexité) | 40 min |
| ✅ | **Correction** | 20 min |
| 🔑 | **Fiche** : Formulaire ln + dérivées trigo + convexité | 30 min |

> **🎯 Objectif semaine 4** : Maîtriser ln, bases trigonométrie, convexité, croissances comparées

---

# 📅 Semaine 5 — GÉOMÉTRIE DANS L'ESPACE & COMBINATOIRE

### Jour 21 — Vecteurs dans l'espace & repérage
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Géométrie dans l'espace](https://www.youtube.com/watch?v=naOM6YG6DJc) | 15 min |
| 📖 | **Cours** : ℝ³, vecteurs (x,y,z), somme, multiplication scalaire, norme, colinéarité. Points alignés si vecteurs colinéaires. Milieu, distance entre deux points. | 25 min |
| 📝 | **Exos** : Soient A(1,2,3), B(4,−1,2), C(7,−4,1). Montrer que A,B,C sont alignés. Soient D(0,1,2), E(3,−2,4). Calculer distance DE et coordonnées milieu. | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 22 — Droites et plans dans l'espace
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Géométrie espace](https://www.youtube.com/playlist?list=PLSOFOcyBRpIiu1OyY8Qj90QTyRQF7Rdfg) | 15 min |
| 📖 | **Cours** : Représentation paramétrique d'une droite : M = A + t×v (t∈ℝ). Équation cartésienne d'un plan : ax+by+cz+d=0. Vecteur normal au plan : n=(a,b,c). Si trois points non alignés → plan. | 25 min |
| 📝 | **Exos** : Soit droite passant par A(1,−2,3), vecteur (2,−1,4). Écrire paramétrique. Vérifier si B(3,−3,7) est dessus. Soit plan P : 2x−3y+z−5=0. Vérifier si A, B, C dedans. | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 23 — Orthogonalité & distances
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Distance point à plan](https://www.youtube.com/watch?v=1b9FtX4sCmQ) | 10 min |
| 📖 | **Cours** : Distance d'un point à un plan : d(M,P)=|ax₀+by₀+cz₀+d|/√(a²+b²+c²). Projeté orthogonal : plus court chemin du point au plan. | 25 min |
| 📝 | **Exos** : Plan : x−2y+2z−3=0, point M(1,1,1). Distance M au plan. Point M(−1,0,2). Distance au plan 2x+2y−z+3=0. Intersection plan & droite. | 38 min |
| ✅ | **Correction** | 15 min |

### Jour 24 — Combinatoire & dénombrement
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Combinatoire](https://www.youtube.com/watch?v=MJv7_pkFcdA) (extrait) | 12 min |
| 📖 | **Cours** : Factorielle n! = n×(n−1)×…×1. Arrangement : A(n,k) = n!/(n−k)! (ordre important). Combinaison : C(n,k) = n!/(k!(n−k)!) (ordre pas important). Coefficients du binôme de Newton. Triangle de Pascal. | 25 min |
| 📝 | **Exos** : Calculer 5!, C(7,3), A(5,2). Développer (a+b)^4. Nombre de podiums (3) parmi 10 athlètes. Nombre de comités de 4 parmi 12. | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 25 — Bilan semaine 5 : Géométrie, combinatoire
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Mini-test** 40 min : géométrie espace (paramétriques, plans, distance) + combinatoire | 40 min |
| ✅ | **Correction** | 20 min |
| 🔑 | **Fiche** : Formules géométrie espace + combinatoire | 30 min |

> **🎯 Objectif semaine 5** : Maîtriser bases géométrie ℝ³, plans, distances, dénombrement

---

# 📅 Semaine 6 — PRIMITIVES, INTÉGRALES & PROBAS

### Jour 26 — Primitives
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Primitives](https://www.youtube.com/watch?v=MJv7_pkFcdA) (extrait) | 12 min |
| 📖 | **Cours** : F est une primitive de f si F' = f. Tableau primitives : x^n → x^{n+1}/(n+1), 1/x → ln|x|, e^x → e^x, sin x → −cos x, cos x → sin x. Primitive de u'e^u = e^u, u'/u = ln|u|. | 25 min |
| 📝 | **Exos** : Donner une primitive de f(x)=3x²+2x−1, g(x)=5e^{−2x}, h(x)=3/(x+1). Trouver F telle que F'=f et F(0)=2. | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 27 — Calcul intégral
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Calcul intégral](https://www.youtube.com/watch?v=MJv7_pkFcdA) (extrait) | 15 min |
| 📖 | **Cours** : ∫_a^b f(x)dx = F(b)−F(a). Propriétés : linéarité, relation de Chasles, positivité (si f≥0 alors ∫f≥0). Valeur moyenne : (1/(b−a))∫_a^b f. Aires entre deux courbes : |f−g|. | 25 min |
| 📝 | **Exos** : ∫_0^1 x² dx, ∫_1^2 1/x dx, ∫_0^π sin x dx, ∫_0^1 e^x dx. Calculer aire entre y=x et y=x² sur [0,1]. | 35 min |
| ✅ | **Correction** | 15 min |
| 💻 | **Python** : Méthode des rectangles pour approcher ∫_0^1 x² dx | 5 min |

### Jour 28 — Loi binomiale (rappel 1ère)
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Loi binomiale](https://www.youtube.com/playlist?list=PLSOFOcyBRpIhr1jogSEza8lFSJ8sFCuKb) | 15 min |
| 📖 | **Cours** : Schéma de Bernoulli : n répétitions indépendantes, succès probabilité p. X = nb de succès → B(n,p). P(X=k)=C(n,k)×p^k×(1−p)^{n−k}. E(X)=np, V(X)=np(1−p). | 25 min |
| 📝 | **Exos** : X∼B(10,0.3). P(X=3), P(X≤2), E(X), V(X). Un dé truqué (P(6)=0.2) lancé 8 fois. Probabilité d'obtenir exactement deux 6. | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 29 — Somme de variables aléatoires
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Somme variables aléatoires](https://www.youtube.com/watch?v=GweMOVratYI) | 12 min |
| 📖 | **Cours** : Si X,Y indépendantes : E(X+Y)=E(X)+E(Y), V(X+Y)=V(X)+V(Y). Généralisation à n variables. Si X_i∼Bernoulli(p) indépendantes, alors S_n=∑X_i∼B(n,p). | 25 min |
| 📝 | **Exos** : Un dé bien équilibré lancé 3 fois. Soit X=nb de 6, Y=nb de 1. Calculer E(X+Y), V(X+Y). 100 lancers pièce équilibrée → E(S_n), V(S_n). | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 30 — Bilan semaine 6 : Primitives, intégrales, probabilités
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Mini-test** 40 min : primitives + intégrale + probas | 40 min |
| ✅ | **Correction** | 20 min |
| 🔑 | **Fiche** : Tableau primitives + intégrales + formules probas | 30 min |

> **🎯 Objectif semaine 6** : Maîtriser les primitives usuelles, bases intégration, loi binomiale

---

# 📅 Semaine 7 — ÉQUATIONS DIFFÉRENTIELLES & RÉVISIONS

### Jour 31 — Équations différentielles y'=ay et y'=ay+b
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Équations différentielles](https://www.youtube.com/watch?v=MJv7_pkFcdA) (extrait) | 15 min |
| 📖 | **Cours** : y'=ay → solution générale y(t)=Ce^{at}. y'=ay+b → y(t)=Ce^{at}−b/a. Condition initiale → C déterminé. Modélisation : croissance bactéries (y'=ky), désintégration radioactive (y'=−λy), loi de Newton (refroidissement). | 25 min |
| 📝 | **Exos** : Résoudre y'=3y, y(0)=2. Résoudre y'=−2y+6, y(0)=4. Un matériau radioactif : y'=−0.002y. Au bout de combien d'années reste-t-il 50% ? | 35 min |
| ✅ | **Correction** | 15 min |
| 💻 | **Python** : Tracer les solutions numériquement (méthode Euler simple) | 10 min |

### Jour 32 — Applications équations différentielles
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Hedacademy** — [Équations différentielles](https://www.youtube.com/playlist?list=PLSOFOcyBRpIiu1OyY8Qj90QTyRQF7Rdfg) | 12 min |
| 📖 | **Cours** : Problèmes concrets : médicament dans le sang (y'=−ky), population avec contrainte (y'=ay−b), refroidissement T'(t)=k(T−T_amb). Savoir poser équation, résoudre, interpréter. | 25 min |
| 📝 | **Exos** : Café à 80°C, ambiant 20°C. T'(t)=−0.1(T−20). Température après 10 min ? Au bout de combien de temps 40°C ? | 38 min |
| ✅ | **Correction** | 15 min |
| 🔑 | **Fiche** : Équations différentielles + applications modélisation | 15 min |

### Jour 33 — Concentration & loi des grands nombres
| Bloc | Activité | Durée |
|---|---|---|
| 📺 | **Yvan Monka** — [Inégalité Bienaymé-Tchebychev](https://www.youtube.com/watch?v=_ZzxgjAxrt4) | 15 min |
| 📖 | **Cours** : Inégalité de Bienaymé-Tchebychev : P(|X−E(X)|≥δ) ≤ V(X)/δ². Loi des grands nombres : la moyenne empirique converge vers l'espérance. Sondages, échantillonnage, fluctuations. | 25 min |
| 📝 | **Exos** : Une pièce (P(pile)=0.5) lancée 100 fois. Majorer P(|S_n−50|≥20) avec BT. Même chose avec 10000 lancers. Conclusion sur les sondages. | 35 min |
| ✅ | **Correction** | 15 min |

### Jour 34 — Grand oral maths — Préparation
| Bloc | Activité | Durée |
|---|---|---|
| 📖 | **Prépa** : Choisir 2 questions parmi : "Comment modéliser une population avec une suite ?", "Pourquoi la loi des grands nombres permet-elle les sondages ?", "Comment les équations différentielles modélisent-elles la radioactivité ?", "À quoi sert le TVI ?". | 30 min |
| 📝 | **Écrire un plan** : Introduction (contexte), développement (définitions, théorèmes, exemple chiffré), conclusion (limites, prolongements). | 30 min |
| 🗣️ | **Oral blanc** 10 min : présenter une question au chrono. S'enregistrer si possible. | 30 min |

### Jour 35 — Bilan semaine 7 : Équations diff., concentration, oral
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Mini-test** 40 min : équations différentielles + Bienaymé-Tchebychev | 40 min |
| ✅ | **Correction** | 20 min |
| 🔑 | **Fiche** : Résumé équations différentielles + formule Bienaymé-Tchebychev | 30 min |

> **🎯 Objectif semaine 7** : Maîtriser équations différentielles, inégalité de concentration, préparer oral

---

# 📅 Semaine 8 — BILAN GÉNÉRAL & TEST FINAL

### Jour 36 — Synthèse analyse (suites + fonctions + intégrales)
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Exercices révisions** 1h30 : 1 suite récurrente (complète), 1 fonction (ln ou exp), 1 intégrale + primitive | 1h30 |

### Jour 37 — Synthèse géométrie + probas
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Exercices révisions** 1h30 : 1 problème géométrie espace (droite, plan, distance), 1 problème proba (binomiale + Bienaymé-Tchebychev) | 1h30 |

### Jour 38 — SUJET BLANC n°1 (1h30)
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Exercice 1** — Suites (40 min) : u_{n+1}=0.5u_n+5, u_0=4. Étude complète → point fixe, convergence, limite. | — |
| 📝 | **Exercice 2** — Fonctions (30 min) : f(x)=ln x − 1/x. Ensemble de dérivée, TVI, variations. | — |
| 📝 | **Exercice 3** — Géométrie (20 min) : Plan P : x−y+2z−3=0, droite D. Intersection ? Distance ? | — |

### Jour 39 — SUJET BLANC n°2 (1h30)
| Bloc | Activité | Durée |
|---|---|---|
| 📝 | **Exercice 1** — Primitives/Intégrales (30 min) : Calculer ∫_0^1 x e^x dx, ∫_1^e ln x dx. | — |
| 📝 | **Exercice 2** — Probabilités (30 min) : Problème loi binomiale + convergence. | — |
| 📝 | **Exercice 3** — Équations différentielles (15 min) : y' = −0.5y + 10, y(0)=5. | — |
| 📝 | **Exercice 4** — Convexité (15 min) : f(x)=x⁴−6x². Points d'inflexion. | — |

### Jour 40 — Bilan final & perspectives
| Bloc | Activité | Durée |
|---|---|---|
| ✅ | *Correction détaillée des 2 sujets blancs* — comparer avec barème | 45 min |
| 📝 | **Grille d'auto-évaluation à remplir** (voir ci-dessous) | 15 min |
| 📖 | **Rédiger ses objectifs de rentrée** : "Cette année, je veux progresser sur…" | 10 min |
| 🔑 | **Constitution du classeur de rentrée** : trier fiches, ranger par chapitre | 20 min |

---

## 📊 Grille d'auto-évaluation finale

À remplir honnêtement après la semaine 8 pour savoir où tu en es :

| Compétence | 😰 À retravailler | 🙂 Moyen | 💪 OK | 🏆 Maîtrise |
|---|---|---|---|---|
| Suites arithmétiques/géométriques (calculs, formules) | | | | |
| Raisonnement par récurrence (rédaction complète) | | | | |
| Limite de suite (q^n, 1/n^k, opérations) | | | | |
| Théorème des gendarmes / comparaison | | | | |
| Convergence monotone (croissante + majorée) | | | | |
| Suite récurrente u_{n+1}=f(u_n) — méthode complète | | | | |
| Limites de fonctions (factorisation, FI) | | | | |
| TVI (montrer existence/unicité solution) | | | | |
| Fonction exponentielle (dérivée, limites, variations) | | | | |
| Dérivée composée (sin, exp, ln) | | | | |
| Logarithme népérien (propriétés, dérivée, limites) | | | | |
| Convexité (f'', point d'inflexion) | | | | |
| Fonctions sinus / cosinus (dérivée, limites) | | | | |
| Géométrie espace (vecteurs, plans, paramétriques) | | | | |
| Distance point à plan | | | | |
| Combinatoire (factorielle, C(n,k), binôme) | | | | |
| Primitives usuelles | | | | |
| Calcul intégral (∫_a^b, propriétés) | | | | |
| Loi binomiale (P(X=k), E, V) | | | | |
| Somme variables aléatoires | | | | |
| Équations différentielles (y'=ay+b) | | | | |
| Inégalité Bienaymé-Tchebychev | | | | |

---

## 🔑 Liens YouTube — Accès rapide

| Chaîne | Lien | Contenu |
|---|---|---|
| **Yvan Monka** | https://www.youtube.com/@ymonka | 1900+ vidéos, tous niveaux |
| **Playlist Terminale spé** | https://www.youtube.com/c/YMONKA/playlists?view=50&shelf_id=3 | Cours complets par chapitre |
| **Hedacademy** | https://www.youtube.com/@hedacademy | Cours dynamiques, questions type bac |
| **Playlist Suites Terminale** | https://www.youtube.com/playlist?list=PLSOFOcyBRpIhr1jogSEza8lFSJ8sFCuKb | 10 vidéos clés |

---

## 👨‍🏫 Notes pour le professeur

Ce planning été est conçu pour :
- **2 semaines sur les suites** (priorité) — c'est le socle
- **1-2 jours par notion phare** du programme de terminale
- **Mini-test chaque vendredi** pour auto-évaluation
- **2 sujets blancs en semaine 8** avant la rentrée
- L'élève peut sauter un jour (week-end) et rattraper → 1h30×5j = 7h30/semaine max

Si un élève a des difficultés :
- Semaine 1-2 → insister sur les suites (récurrence + variations + limites)
- Semaine 3 → bien maîtriser exponentielle avant logarithme
- Semaine 5 → géométrie : beaucoup de formules à apprendre
- Semaine 7-8 → prioriser les sujets blancs sur la révision

---

> **Document préparé pour l'été précédant la Terminale — Spécialité Mathématiques**
> **Chaînes YouTube recommandées** : Yvan Monka (M@ths et tiques) · Hedacademy
> **Charge** : 1h30/jour · 5j/semaine · 8 semaines
> **Objectif** : Aborder tout le programme de terminale en mode "découverte + consolidation"
