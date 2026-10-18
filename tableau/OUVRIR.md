# Ouvrir le classeur Tableau

Ouvrir `EcoBati.twbx` dans Tableau Desktop ou Tableau Public 2026.1 ou version compatible. Les trois feuilles et le tableau de bord utilisent les données CSV embarquées. Si nécessaire, reconnecter la source à `Data/consommations.csv`.

Le champ calculé central est `SUM([Consommation_kwh]) / SUM([Surface_m2])`. Comme la surface est présente une fois par bâtiment et par mois, ce ratio est une intensité mensuelle pondérée, même sur plusieurs années. Il ne faut pas le présenter comme une intensité annuelle.

Les mesures sont fictives et ne constituent pas un diagnostic réglementaire. Le notebook et le rapport détaillent la couverture incomplète et les hypothèses.

Le XML et les chemins du paquet sont contrôlés ; ouverture, actualisation, filtres et rendu restent à valider dans Tableau, absent de cet environnement. Aucun résultat d'exécution native n'est revendiqué.

Documentation : https://help.tableau.com/current/pro/desktop/en-us/save_savework_packagedworkbooks.htm
