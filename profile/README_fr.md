## Bienvenus sur PolySource 👋

PolySource est une organisation non officielle dont le but est de proposer des outils numériques open source pour les étudiants de l'EPFL.

* [English version](https://github.com/polysource-projects/.github/blob/main/profile/README.md)
* [French version](https://github.com/polysource-projects/.github/blob/main/profile/README_fr.md)

## Gestion des services

Pour garder une organisation efficace, tous nos projets sont :
- ✅ entièrement open source
- ✅ déployables via un fichier `captain-definition` (support de Dockerfile et de Docker Compose) 
- ✅ si le service est à destination des étudiants en bachelor, en français (dont le README et la documentation)
- ✅ en anglais si le public est plus global

Si vous souhaitez ajouter votre service :
* 💥 créer un fork du repository [polysource-projects/apps](https://github.com/polysource-projects/apps)
* 💥 modifier le fichier `apps.json` (ajouter votre service)
* 💥 ouvrir une Pull Request

Merci également de nous indiquer si vous souhaitez :
* 🚚 déplacer votre repo personnel vers le GitHub organisation, et être ajouté dans l'organisation pour continuer de le modifier (préféré)
* ✂️ que l'on fork votre repo personnel vers le GitHub organisation

Dans tous les cas, pour des questions d'efficacité, de sécurité et de maintenance, nous ne déploierons que des repositories ajoutés dans le compte GitHub organisation.

🔥 Une fois la Pull Request acceptée, votre service sera automatiquement déployé vers un sous-domaine polysource.ch avec un certificat SSL et un déploiement automatique à chaque commit.

En cas de question, n'hésitez pas à nous contacter via contact@polysource.ch ou en ouvrant une issue sur le repository [polysource-projects/apps](https://github.com/polysource-projects/apps).
Par exemple, si vous ne savez pas comment créer un fichier `Dockerfile` ou `captain-defition` pour votre projet, nous pourrons très probablement le faire pour vous.

## Notes

* dans la mesure du possible, essayez de garder un maximum d'abstraction pour chacun de votre projet. Par exemple, si votre web app a besoin de scraper people.epfl.ch ou un autre site, préférrez créer un scraper universel réutilisable pour d'autres projets (même s'il ne supporte que les 1-2 fonctionnalités qui vous sont utiles), plutôt que d'intégrer le code du scraper directement dans votre appli. (vous serez bien contents que votre appli continue de fonctionner même si le site change parce que quelqu'un continue de mettre à jour le scraper 😉)
