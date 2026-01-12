**Assistant de Voyage Personnel**

Un sondage révèlait que 6 Français sur 10 désiraient se rendre en vacances lors de l'année 2025. **Pour cette année 2026, êtes-vous plus voyage à la montagne ou bien voyage à la plage ?** 

Pour vous aider à choisir votre prochain lieu de vacances, nous avons réalisé un outil permettant d'aiguiller plus de 40 millions de Français à choisir leur destination en fonction de leurs critères.🚂

Nous avons répertorié une base de données sur RStudio afin de créer un **Assistant de Voyage Personnel avec plusieurs facteurs**. 

Pour que cet assistant puisse déterminer votre prochain lieu de vacances, il faut télécharger le script R et la base de données ci-joint. 
Une fois installés, il suffit de lancer le modèle pour qu'une page s'ouvre vous demandant de renseigner vos différents critères. Vous recevrez alors une **liste de trois destinations** correspondant le mieux à vos attentes.  
Pour affiner votre choix, un onglet permet de sélectionner les deux critères les plus pertinentes selon vos envies. 

Voici les facteurs utilisés pour notre Assistant de Voyage Personnel : 

- 🏔️ **Le type de voyage** , répértoriant le style et envie de la personne pour effectuer un voyage.
- 👥 **L'accompagnant** , afin de savoir si l'utilisateur aimerait partir seul ou à plusieurs. 
- 📅 **Le mois de départ** , pour savoir quand est-ce que l'utilisateur souhaite partir en vacances.
- ☀️ **Le climat souhaité** , pour déterminer la préférence de la personne.
- 🧳 **La fréquentation touristique** , afin de connaitre le niveau de tolérance face aux nombres d'individus.
- 🎯 **L'activité favorite** , dans le but de connaitre ce que la personne aime faire en premier lieu.

Dès le départ, il a fallu traduire notre base de données qui provenait du site **"Kaggle"** pour qu'elle puisse répondre aux attentes des 40 millions de voyageurs francophones. Ensuite, nous avons construit l'Assistant de Voyage Personnel.
Pour élaborer cet outil, nous l'avons construit afin qu'il puisse annoncer trois destinations qui se rapprochent le plus des critères renseignés. 
Nous avons également mis un score exprimé en pourcentage pour indiquer la compatibilité pour chaque destination, exprimé en pourcentage, afin de faciliter le choix de l'utilisateur.
Une fois les trois destinations proposées, l’outil offre la possibilité de sélectionner les deux critères prioritaires, afin de désigner la meilleure destinartion du voyage.

De la part de l'Assistant de Voyage Personnel ainsi que de notre équipe, **nous vous souhaitons un excellent voyage** !
