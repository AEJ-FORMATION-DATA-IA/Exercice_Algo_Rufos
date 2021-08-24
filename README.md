# Exo_Algo_Rufos


*********EXERCICE 1 ************
###___ Calculer le taux de contamination de la CI

<!-- Resolution -->

AlgoTauxContamination;

var
{ Nbre_contam_CI, Nbre_contam_Mnde,TauxCI} : réels;

Début

Afficher ("Veillez entrer le nombre de contaminé en CI : ");
Saisir(Nbre_contam_CI); 
Afficher ("Veillez entrer le nombre de contaminé en dans le     monde : ");
Saisir (Nbre_contam_Mnde);

TauxCI=(Nbre_contam_CI/Nbre_contam_Mnde,TauxCI)x100

Afficher("Le taux de contamination est :",TauxCI "%");
