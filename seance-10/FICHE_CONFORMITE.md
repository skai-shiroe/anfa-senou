# Fiche de conformité — Application mobile passagers Anfa

## 1. Finalité du traitement
L'application collecte la position GPS pour proposer le trajet le plus proche, l'historique 
de paiements mobile money pour gérer les abonnements, et le numéro de téléphone comme 
identifiant de compte. Cette finalité est déterminée et limitée : améliorer le service de 
transport sans détourner les données vers d'autres usages comme le profiling commercial.

## 2. Données collectées et leur sensibilité
Position GPS (données de géolocalisation en temps réel), historique de paiements mobile money 
(données financières sensibles), numéro de téléphone (donnée d'identification). La plus sensible 
est l'historique de paiements car il révèle le comportement financier et le niveau de revenu. 
Le GPS est également très sensible car il permet de suivre les déplacements d'une personne.

## 3. Base légale applicable
Loi togolaise 2019-014 sur la protection des données s'applique. Pour le GPS : consentement 
+ intérêt légitime. Pour le numéro de téléphone : exécution du contrat d'utilisation. Pour 
l'historique de paiements : consentement explicite + obligation légale (lutte anti-blanchiment). 
Si l'application cible des ressortissants UE, le RGPD s'appliquerait également en complément.

## 4. Durée de conservation
Numéro de téléphone : tant que le compte est actif + délai légal de prescription (5-10 ans). 
GPS : 24h maximum après le trajet (principe de minimisation). Historique de paiements : 10 ans 
selon la réglementation financière togolaise. Ces durées sont justifiées par des obligations 
légales et des finalités précises.

## 5. Hébergement et souveraineté
Les données doivent être hébergées au Togo ou dans l'espace CEDEAO avec clause de transfert 
adéquate. Héberger chez un cloud américain violerait la loi togolaise car le Patriot Act 
permet aux autorités américaines d'accéder aux données sans contrôle judiciaire local, 
portant atteinte à la souveraineté du Togo.

## 6. Droit des personnes concernées
Les passagers doivent pouvoir exercer leurs droits (accès, rectification, effacement). 
Cependant, le système technique actuel d'Anfa basé sur HDFS n'a pas de mécanisme natif 
de purge granulaire des données personnelles, rendant difficile l'exercice du droit à 
l'effacement sans développement spécifique.