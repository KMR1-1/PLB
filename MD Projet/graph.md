"`Vue d'ensemble`"






```mermaid
graph TB;
subgraph Acceuil
intro[Intro]
eval[Evaluation du Projet]
plan[Planifiacation du projet]
documentation[Documentation]
end
plan-->choixregion

subgraph choixregion[Choix de la region]
potentielagricole[Potentiel agricole]
accesressource[Acces aux 
ressources naturelles]
climat[Climat]
end
choixregion-->|une fois la region choisie|techniquestrouver

subgraph techniquestrouver[Techniques pour trouver un terrain]
rechercheligne[Recherche en ligne]
safer[SAFER]
reseauxlocaux[Réseaux Locaux]
horsmarche[Terrains hors marché]
end
techniquestrouver-->|apres avoir trouvé|analyseterrain
climat-->microclimat[Micro-climats]

subgraph analyseterrain[Analyse dy terrain]
legal[Aspect legal]
nuisances[Nuisances]
typeterrain[Type de terrain]
end
analyseterrain-->|aquisistion du terrain|planification
legal-.->plu[PLU]

subgraph planification[Planification]
carte[Cartographie]
zoning[zoning]
organisation[Delimitations]
nettoyage[Nettoyage]
acheminement[Acheminement]
stockage[cabanes de stockage]
secu[Sécurisation]
ressourcess[Ressources necessaire a l'etape suivante]
end
planification-->construction

subgraph construction[Constructions principales]
habitat[Habitat]
ateliers[Ateliers]
reseauenergie[Réseaux d'eau et energie]
plantations[Plantations]
elevages[Elevages]
end
construction-->gestion

subgraph gestion[Gestion]
tache[Taches calendrier]
suivi[Suivi et Evaluation]
elevages[gestion des elevages]
maintenance[Maintenance et Réparations]
dechets[Gestion des dechets]

end






