# Intégration continue

L'intégration continue (de l'anglais : Continuous integration, CI), est un ensemble de pratiques utilisées en génie logiciel consistant à vérifier à chaque modification de code source que le résultat des modifications ne produit pas de régression dans l'application développée.

Les pipelines d'automatisation des logiciels via des forges dédiées (par exemple, [github](https://docs.github.com/en/actions/about-github-actions/about-continuous-integration-with-github-actions)) facilitent la mise en place de l'IC. Cependant, une définition minutieuse du pipeline lui-même est nécessaire.

Un pipeline typique (qui peut être défini comme un [flux de travail](https://docs.github.com/en/actions/writing-workflows) github, par exemple) se compose des étapes suivantes :
  1. Une *pull request* a été faite par l'un des contributeurs
  2. Le code modifié est soumis à toutes les suites de tests disponibles.
  3. Si tous les tests sont réussis, le nouveau code est automatiquement fusionné dans la version actuelle du code.

