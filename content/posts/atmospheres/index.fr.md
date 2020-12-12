---
title: "Atmosphères stellaires dans le solaire comme des étoiles à des longueurs d'onde millimétriques et submillimétriques"
date: 2020-12-11T08:06:25+06:00
hero: /posts/atmospheres/images/alma.jpg
description: Markdown rendering samples
menu:
  sidebar:
    name: Atmosphères stellaires
    identifier: stellaires
    weight: 30s
math: true
---

{{< img src="/posts/atmospheres/images/acena.png" height="316" width="399" float="right" >}}

L'atmosphère des étoiles de type solaire est composée de la photosphère, de la chromosphère, de la zone de transition et de la couronne. La chromosphère est la couche où la température passe de 4000 K à 8000 K et est étudiée aux longueurs d'onde ultraviolette, visible, infrarouge, millimétrique et (sub) -millimétrique (Wedemeyer et al. 2016) [^7].
Les premiers modèles chromosphériques ont été obtenus grâce aux observations ultraviolettes (Vernazza et al. 1981; Avrett & Loeser 2008) [^6] [^1]. Cependant, des observations récentes faites avec le télescope solaire submillimétrique (SST) et le grand réseau millimétrique / submillimétrique Atacama (ALMA) ont montré que la chromosphère a des températures plus basses que celles attendues par les modèles ultraviolets (Linsky 2017). [^2]

Nous avons développé le code KINICH-PAKAL (Tapia-Vázquez, & De la Luz 2020) [^5] qui utilise l'algorithme de Levenberg-Marquard comme méthode d'ajustement non linéaire, PAKAL-MPI comme modèle chromosphérique de l'atmosphère solaire et observations à des longueurs d'onde allant de l'infrarouge au millimètre pour générer un modèle plus précis des chromosphères des étoiles de type solaire.
KINICH-PAKAL nous a permis d'étudier en détail comment les conditions physiques de l'atmosphère évoluent en fonction de sa température effective.
Le développement de ces modèles est nécessaire pour les études sur les disques de débris (White et al. 2018) [^8], étudier les conditions dans lesquelles les éruptions se forment (MacGregor et al., 2018) [^4] et les mécanismes physiques possibles des variations de flux dans le étoiles (Liseau 2019) [^3].

### Références

[^1]: Avrett, E. H., & Loeser, R. 2008, ApJS, 175, 229.
[^2]: Linsky, J. L. 2017, ARA&A, 55, 159.
[^3]: Liseau, R. 2019, arXiv:1904.03043.
[^4]: MacGregor, M. A., Weinberger, A. J., Wilner, D. J., Kowalski, A. F., & Cranmer, S. R. 2018, ApJ, 855, L2.
[^5]: Tapia-Vázquez, F., & De la Luz, V. 2020, ApJS, 246, 5.
[^6]: Vernazza, J. E., Avrett, E. H., & Loeser, R. 1981, ApJS,45, 635.
[^7]: Wedemeyer, S., Bastian, T., Brajša, R., et al. 2016, SSRv, 200, 1.
[^8]: White, J.A., Aufdenberg, J., Boley, A.C., 2018, ApJ,859(2), p.102.