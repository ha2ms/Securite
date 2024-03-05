
# Présentation de Dashboard OpenVAS

>Afin d'accroitre le niveau de sécurité d'une infrastructure, il existe une multitude d'outil libre et puissants dont il est fort intéressant de se munir, nous permettant ainsi d'identifier les différentes failles possiblement présentes au sein de l'infrastructure.
>
> Voici l'exemple d'un de ces outils, nommé OpenVas (GreenBone actuellement), nous permettant de réaliser cette tâche via un système de scan réseau ainsi que d'un affichage de résultat par monitoring.
> Nous avons donc simuler le réseau d'une entreprise comprenant de multiple failles de sécurités afin de pouvoir tester l'efficacité d"OpenVAS.
> 
> ---

> ## Résultat du Dashboard: 
>![](https://i.postimg.cc/zDgGfYcf/Dashboard.png)
> 
> Plusieurs Panels Graphiques offrant un champ visuelle intéressant et par conséquents de détecter très rapidement les différentes anomalies présentes.
> D'autres Panels plus textuels permettant eux d'aller un peu plus dans la précision du type d'anomalie une fois celle-ci détecté.
> 
> ### Typologie de Pannels:
> - **Vulnérabilités par Hôtes**
>    - Ces Panels nous indiques le nombres de vulnérabilités identifié sur un ensembles d'hôtes.
> - **Résultats par Sévérité**
>    - Ce type de Pannel donne un aperçu très clair sur la hiérarchie des différentes failles de sécurité présentes, et ainsi prioriser ses actions de contre-mesure aux potentiels menaces. Le nombre de failles n'étant pas toujours aussi pertinentes que la criticité de celles-ci.
> - **Résultat par Secteurs (Services)**
>       - Au delà de la sévérité, les Panels nous indiquant les service impacté par une vulnérabilité sont également très intéressant, en identifiant le service impacté l'on peut cerner bien plus efficacement l'impact et la solution à mettre en place. Ainsi par exemple si la faille identifié par OpenVAS concerne tous les services **SSH** de l'infrastructure, il sera plus aisé de constater qu'il s'agit probablement d'une mise-à-jour qui n'a pas été effectué en temps et en heure. 
> - **CVE par dates de créations**
>    - Ce Panel peut être intéressant pour mieux comprendre la présence d'une faille au sein d'un système, en connaissant la date et l'évolution de certaines CVE, l'on est mieux à même de comprendre et d'identifier les contre-mesures pertinentes à apporter.
> 
> ---

>  ## Rapport de Résultats
>  Une fois les différentes anomalies détectées sur notre Dashboard principale, l'on peut pousser davantage l'investigation en vérifiant le Rapport de Résultats comme nous le montre l'image ci-dessous.
>  ![](https://i.postimg.cc/jS4FQcMf/Report.png)
>   
>   Ainsi nous pouvons explorer de manière très précise l'ensemble des vulnérabilités par niveau de criticité pour chacun des hôtes de l'infrastructure.
>    
>    ---
