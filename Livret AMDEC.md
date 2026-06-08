# Livret AMDEC
## Page 1
AMDECBUT2 MPILaetitia Correia
Programme
• Historique• Différentes notions liéesSureté de fonctionnement
• Origine • AMDEC et normes• 3 types d’ AMDECNotions de base sur l’ AMDEC
• Les 8 étapes de la méthodeMéthodologie de l’ AMDEC

## Page 2
1-Sûreté de fonctionnement
Sûreté de fonctionnementDéfinition : « Consiste à:•Evaluer les risques potentiels•Prévoir l’occurrence des défaillances •Tenter de minimiser les conséquences des situations catastrophiques lorsqu’elles se présentent »Nécessite un compromis entre les mécanismes de sureté nécessaires et les coûts économiquesObjectif: 0 accident, 0 arrêt, 0 défaut

## Page 3
Sûreté de fonctionnementHistoriqueApproche intuitiveStatistiques, taux de défaillanceJusqu’aux années 30Loi de Murphy« If anything can go wrong, it will »Années 40Réduction des coûts de maintenance, MTBFAnnées 50Analyse des modes de défaillances et de leurs effetsArbre des causesArbre de défaillanceAnnées 60Analyse des risquesCollecte de données REXAnnées 70ModélisationNouvelles techniques (simulateurs…)Depuis les années 80
Atteinte de l'objectiftechnique pour lequel lesystème a été réaliséFONCTIONNEMENT SÛR SI :Réussite de la missionSécurité du système etde son environnementAbsence d'événement à conséquence catastrophique ou gravesur des éléments du système ou sur sonenvironnementOptimisationFiabilitéDisponibilitéMaintenabilitéSécuritéSûreté de fonctionnement« Remplir sa mission sur une période définie »« Aptitude à être maintenu en état de bon fonctionnement »« Absence ou limitation des risques » (Larousse)« Etre en état de fonctionner dans des conditions données » »

## Page 4
Sûreté de fonctionnementDisponibilitéMTBF:Mean Time Before FailureMTTF: Mean Time To Failure3 concepts pour justifier de la disponibilité:Disponibilité = MTTF / (MTBF+MTTR) MTTR:Mean Time To Repare
2-Notions de base sur l’ AMDEC

## Page 5
Notions de baseOrigine AMDECMéthode d’abord centrée sur les produits, qui s’applique maintenant aussi aux services
•Armée US (dysfonct. des munitions)Référence militaire MIL-P-1629Création en 1949
• Aliments contaminés dans les missions spatiales HACCP• Programme ApolloAnnées 50-60 NASA
• Utilisée par les constructeurs automobiles US (USA, Asie)Années 70
• Application en Europe via les constructeurs automobilesAnnées 80AMDEC = Analyse des Modes de Défaillances, de leurs Effets et Criticités= Equivalent français de la méthode d'origine FMEA :Failure Mode, Effects, and Criticality Analysis
Notions de baseAMDEC et normesDéc 1986Norme X60-510 Août 2006Norme NF EN 60812Octobre 2018 Norme NF EN IEC 60812DéfaillanceMode de défaillanceEffet de défaillanceCriticité d’une défaillanceCessation de l’aptitude d’une entité à accomplir une fonction requiseManière dont un dispositif tombe en panneConséquence de mode de défaillance en termes de fonctionnement, fonction ou état du dispositifCombinaison de la sévérité d’un effet et de la fréquence de son apparition, ou d’autres attributs d’une défaillance comme une mesure de la nécessité d’un traitement ou d’une atténuationTechniques d'analyse de la fiabilité du système –Procédure d'analyse des modes de défaillance et de leurs effets (AMDE)Analyse des modes de défaillance et de leurs effets (AMDE et AMDEC)

## Page 6
Notions de baseAMDECQuestions à se poser:Qu’est-ce qui ne fonctionne pas ?Qu’est-ce qui a arrêté de fonctionner ? Qu’est-ce qui ne répond pas à la sollicitation ?Qu’est-ce qui s’est dégradé progressivement dans le fonctionnement du système ?Le fonctionnement est-il intempestif ?
Notions de base3 types d’ AMDEC
Produit
Process
Moyen

## Page 7
Notions de base3 Finalités communes
Identifier et traiter les causes potentielles de défauts et de défaillance avant qu'ils ne surviennent
Fait ressortir les ACTIONS CORRECTIVES à mettre en œuvre Plan de fiabilisation, de surveillance, de contrôle qualité, de maintenance préventive, de sécurisation…
Vérifier les performances d'un système avant de le mettre en œuvre: analyse exercée aux étapes de la conception et de l'industrialisation
Eviter les défaillances qui ne pourraient plus être éliminées lors des contrôles à postériori en production (matières, tolérances, modes de fabrication, etc.)
1
2
3
Spécificités AMDEC ProduitAnalyse fonctionnelle importante pour bien comprendre comment répondre aux besoins du clientQuelles attentes ?Quelles fonctions ? Pourquoi?Prendre en compte les contraintes issues de l’environnementFonctions classées en deux types:•Fp: Fonctions principales service à rendre•Fc: Fonctions de contraintes sont imposées au produit
5 pourquoi1 fonction = Verbe + complémentDeux méthodesApproche fonctionnelleApproche composants

## Page 8
Spécificités AMDEC ProduitGraphique « Bête à cornes » :Sert à valider le besoin du système
Client premier du systèmeEnvironnant principal potentiellement modifié par le systèmeObjet du systèmeBut premier du systèmePérennité du système
Spécificités AMDEC ProduitExemple :Analyse de fonctions pour un raccord de tuyauterie de machine à laver:Canalisation maisonTuyau machine à laverRaccordFc: -doit résister à la pression-doit être étanche-doit résister aux chocs-doit résister aux efforts de montage-doit comporter les marquages réglementaires …Fp: Assurer la liaison entre les deux canalisations

## Page 9
Spécificités AMDEC ProcessusAnalyse fonctionnelle:Analyser les flux Prendre en compte et analyser toutes les étapes du processus4 types d’effets:-sur l’opération étudiée-sur le process complet-sur le produit-sur le client utilisateurObjectif: Assurer la qualité d’un produit/service en améliorant les opérations de production de celui-ciActions correctives:Orienter les efforts vers les activités du processus et la gamme de productionPeuvent concerner toutes les activités:La fabricationLe stockageLa logistiqueLes phases de contrôle
Spécificités AMDEC MoyenObjectif:Assurer la disponibilité et la sécurité d’un moyen de production en améliorant sa maintenanceAnalyse fonctionnelle: Analyser chaque sous-ensemble de la machine et leurs interactionsEffortsorientés vers la capabilité des machines et les activités de réparationFavorise:•La mise en place de plan de maintenance préventive•L’organisation et la réalisation des actions de maintenance•Les conditions d’intervention

## Page 10
Notions de baseSynthèse des 3 types d’ AMDECMoyenProcessusProduitValide la fiabilité d’un équipementValide la fiabilité du processus de fabricationValide la conformité d’un produit développé par rapport aux exigences clientsMéthodeFonctions de la machinePhases du processusFonctions du produitEléments à étudierConception de moyensIndustrialisationConceptionPhase-Diminuer les temps d’arrêt-Améliorer l’exploitation et la maintenanceAméliorer les opérations de production pour assurer la qualité du produitMeilleure conception, réussie du premier coupGainsMeilleure fiabilité, disponibilitéStabilité des processus, coûts en baisseMeilleure fiabilité des produits, hausse de la satisfaction clientFinalités
Notions de base6 qualités de la méthode
Méthode AMDEC
QUANTITATIVE
PARTICIPATIVE
FORMALISEE
OBJECTIVE
CRITIQUE
QUALITATIVEImaginer tout ce qui peut ne pas allerMesurer la criticité par cotationPermet traçabilité et communication Modes de défaillances / effets / causesTraite de la criticité des défaillances (C= GxOxD)Mise en commun d’expériences et compétence

## Page 11
Notions de baseInconvénients de l’ AMDECMéthode qui demande:Du tempsDe la rigueurUne bonne organisationL’implication de tous les acteurs du groupe+ Compliqué à lire pour une personne non avertieNécessite une synthèse
Notions de basePièges à éviter•Réaliser une AMDEC quand c’est trop tard •Ne pas réviser une AMDEC à temps •Utiliser des termes comme dangereux /risqué / intolérable •Utiliser différentes définitions et interprétations pour les modes de défaillance / causes / effets / risques •Ne pas suivre la mise en place des actions proposées

## Page 12
3-Méthodologie AMDEC
Méthodologie AMDEC8 étapes:
1-Préparation (groupe de travail, périmètre, objectifs…)
2-Décomposition et Analyse fonctionnelle
4-Cotation des défaillances
5-Hiérarchisation des défaillances
6-Actions correctives
7-Réévaluation de la criticité
8-Présentation des résultats
3-Analyse des défaillances, causes et effets= Analyse quantitative = Analyse qualitative

## Page 13
Méthodologie AMDEC2- Décomposition et analyse fonctionnelle2- Analyse des fonctions:Principales
• Fonctions pour lequel le système a été conçuDe contraintes
• Répondent aux interactions avec le milieu extérieurElémentaires
• Assurent les fonctions principales• Sont les fonctions des différents composants élémentaires du système= Besoins de l’utilisateur3- Arbre fonctionnel :SystèmeSous-systèmeElément
Fonctions principalesSous-fonctionsFonctions élémentaires
Grille AMDEC0-1617-3132-64Elément/ FonctionFonction/ ElémentModes de défaillanceCauses de la défaillanceEffets de la défaillanceMode de détectionGravité 1Occurrence 1Détection 1CriticitéIPR1Action corrective Gravité 2Occurrence 2Détection 2CriticitéIPR2Seuils à définirMéthodologie AMDEC2- Décomposition et analyse fonctionnelleExemple: découpage fonctionnel d’un équipement

## Page 14
Méthodologie AMDEC3- Analyse des défaillances - InventaireEtablir la liste des défaillances potentielles :
PRODUIT et MOYEN
Reprendre chaque fonction de l’analyse
Identifier tous les modes de dysfonctionnement possibles
PROCESSUS
Reprendre chaque étape du process
Identifier toutes les non-conformités possiblesDéfaillances THO
Méthodologie AMDEC3- Analyse des défaillances - Inventaire= « Manière dont le système peut s’arrêter de fonctionner, s’écarter des spécifications prévues initialement, fonctionner anormalement, etc. »Un élément défaillant = Ne fonctionne pas du toutNe fonctionne pas au moment où il doit fonctionnerFonctionne au mauvais momentNe s’arrête pas alors qu’il doit stopperNe fonctionne pas à 100% de ses performances attendues…Elément =ProduitPièceComposant

## Page 15
Méthodologie AMDEC3- Analyse des défaillances - InventaireS’exprime en terme physique:FuiteBlocageDéformation CoincementVibrationDesserrageCorrosionPerte de performanceNe s’arrête pasNe démarre pasDépasse une limité tolérée…
Méthodologie AMDEC3- Analyse des défaillances – Recherche des causesCauses de défaillances des moyens de production:+ Causes externes au matériel (amont)Composants mécaniquesComposants hydrauliquesComposants électriques et électromécaniquesCauses de défaillancesContrainte/fatigue mécaniques, états de surfaceVieillissement, mort subite, colmatage, fuitesVieillissement, mort subiteCauses internes matérielTempérature ambiante, pollution (poussières, huile, eau), vibrations, échauffement local, chocsTempérature ambiante, pollution (poussières, huile, eau), vibrations, échauffement local, chocs, coups de bélierPollution (poussière, huile, eau), chocs, vibrations, échauffement local, perturbations électromagnétiques…Causes externes Milieu exploitationConception, fabrication, montage, réglages, contrôle, mise en œuvre, utilisationMontage, réglages, contrôle, mise en œuvre, utilisation, manque d'énergieMontage, réglages, contrôle, mise en œuvre, utilisation, manque d'énergieCauses externes Main d'œuvre

## Page 16
Méthodologie AMDEC4- Cotation des défaillancesEvaluer les critères de risques selon trois critères:
Gravité  (G)du défaut ou de la défaillance
Occurrence (O)Fréquence d’apparition de la défaillance
Détection (D)Probabilité de non-détection de la causeNotes de 1 à 4 (ou  de 1 à 10)Criticité = G x O x D 
Méthodologie AMDEC4- Cotation des défaillances : GravitéCritère« Moyen »Critère« Processus »Critère« Produit »NotePas d’arrêt de productionComposant arrêté mais pas l’installation qui continue à fonctionner en mode dégradéPas d’incidence sur le processus ou les salariésAucune incidence sur la conformité du produit1 Arrêt ≤ 1hEquipement arrêté mais pas la production qui continue à fonctionner en mode dégradéIncidence moyenne sur l’activité ou les salariésProduit non-conforme mais fonctionnel2 1h ≤ Arrêt ≤ 1 jourProduction arrêtée, nécessite une intervention de maintenanceIncidence importante sur l’activité ou les salariésProduit non-conforme non-fonctionnel3 Arrêt > 1 jourProduction arrêtée, impliquant des problèmes graves pour les hommes ou l’installationReport de l’activité ou accident de personnesProduit con-conforme avec mise en danger de l’utilisateur4

## Page 17
Méthodologie AMDEC4- Cotation des défaillances : OccurrenceExemple 2Probabilité d’apparitionExemple 1FréquenceNoteExceptionnel (pas de mémoire de participant)1 à 2 fois par an1Rare (déjà arrivé 1 ou 2 fois)Au moins une fois par mois2Fréquent (déjà arrivé plusieurs fois)Au moins une fois par semaine3Certain (arrivera à coup sûr)Au moins une fois par jour4
Méthodologie AMDEC4- Cotation des défaillances : DétectionExemple 2Exemple 1NoteDétection certaineDétection automatisée (100%)1Détection par l’opérateurDétection humaine2Difficilement détectableDétection aléatoire3IndétectableAucun moyen de détection4

## Page 18
Méthodologie AMDEC5- Hiérarchisation des défaillancesDéfinir les niveaux de criticitéExemples:CriticitéValeurNégligeable : on les laisse de coté1 < C < 8Moyenne : on se pose les questions de les laisser ou conserver8 < C < 14Élevée : il faut trouver des actions à mettre en œuvre et regarder l’importance de mettre en stock les composants ou organes14 < C < 27Interdit : il faut trouver des actions à mettre en œuvre et mettre obligatoirement en stock les composants ou organes27 < C < 641 4 9 162 8 18 323 12 27 484 16 36 6437 - 64 : criticité majeure28 – 36 : criticité importante10 – 27 : criticité mineure1 – 9 : criticité faible
Méthodologie AMDEC7- Réévaluation de la criticité
Comparer la criticité initiale et résiduelle pour vérifier la pertinence des actions définies (efficacité, performance)

## Page 19
Méthodologie AMDEC8- Présentation des résultatsPermet de mettre en avant les éléments critiques et les recommandations
4-Etude de cas AMDEC
Grille AMDEC0-1617-3132-64Elément/ FonctionFonction/ ElémentModes de défaillanceCauses de la défaillanceEffets de la défaillanceMode de détectionGravité 1Occurrence 1Détection 1CriticitéIPR1Action corrective Gravité 2Occurrence 2Détection 2CriticitéIPR2Seuils à définir

