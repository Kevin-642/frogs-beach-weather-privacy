# Politique de confidentialité de Frog's Beach

Dernière mise à jour : 6 octobre 2026

Frog's Beach affiche les prévisions météo et marines d'un lieu choisi par
l'utilisateur. L'application ne demande aucun compte et n'intègre actuellement
ni publicité, ni télémétrie, ni vente de données personnelles.

## Données utilisées

Selon les fonctions choisies, l'application traite :

- le nom d'un lieu recherché ;
- la position approximative ou précise, uniquement après autorisation et quand
  l'utilisateur appuie sur « Utiliser ma position » ;
- les coordonnées du lieu afin de demander les prévisions terrestres et
  marines ;
- la dernière prévision affichée, enregistrée localement pour le mode hors
  connexion ;
- le dernier classement sanitaire annuel affiché, conservé localement au
  maximum 30 jours et uniquement réutilisé à proximité du lieu enregistré.

La position n'est pas relue en arrière-plan. La recherche manuelle reste
disponible lorsque la permission de localisation est refusée.

## Services tiers

Frog's Beach utilise les services Open-Meteo suivants :

- API de géocodage pour rechercher un lieu ;
- Forecast API pour la température, le ressenti, le vent et l'indice UV ;
- Marine Weather API pour la température de l'eau, les vagues et les courants.

La ville ou les coordonnées sélectionnées sont transmises à Open-Meteo par
HTTPS. Le fournisseur peut recevoir des informations techniques comme
l'adresse IP conformément à ses propres conditions :
<https://open-meteo.com/en/terms>

La résolution du nom du lieu depuis la position peut également utiliser le
service de géocodage du système Android ou iOS.

Lorsque le backend optionnel Frog's Beach est configuré, les coordonnées du
lieu choisi lui sont transmises par HTTPS. Ce service interroge les données
publiques de qualité des sites de baignade publiées sur data.gouv.fr et, si
l'accès serveur est configuré, les observations de bouées Météo-France. Aucun
identifiant secret n'est inclus dans l'application. Une observation de bouée
n'est jamais conservée dans le cache hors connexion.

## Soutien volontaire

Lorsque l'utilisateur appuie sur « Offrir un café à la grenouille »,
Frog's Beach ouvre le site externe Ko-fi. Ce soutien est ponctuel, facultatif
et ne débloque aucune fonctionnalité ni aucun contenu dans l'application.
Frog's Beach ne recueille, ne traite et ne vérifie aucune donnée de paiement ;
Ko-fi et son prestataire de paiement appliquent leurs propres conditions.

## Sécurité de baignade

Les données météo et marines sont des sorties de modèles. Elles ne constituent
ni une autorisation de baignade, ni un drapeau officiel, ni une aide à la
navigation. Lorsque aucune source officielle locale n'est connectée,
l'application l'indique explicitement et invite à vérifier les panneaux,
sauveteurs et autorités sur place. Dans les zones couvertes du Pays Basque et
des Landes, l'utilisateur peut choisir d'ouvrir dans son navigateur le site
officiel Kalilo ou Plages Landes. Aucune consultation de ces sites n'a lieu
sans cette action volontaire.

## Stockage et suppression

La dernière prévision, le lieu associé et le dernier classement sanitaire
annuel sont enregistrés uniquement sur l'appareil. Ils sont remplacés lors
d'une nouvelle consultation. Le classement sanitaire mis en cache n'est pas
réutilisé pour un lieu éloigné. L'utilisateur peut supprimer ces données en
effaçant les données de l'application dans les paramètres du système ou en la
désinstallant.

## Contact

Frog's Beach fait partie de l'écosystème Frog développé par Kévin.

Pour toute question relative à cette politique : <mailto:kevin.portais@gmail.com>.

