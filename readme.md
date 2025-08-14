#README

We've turned off the ability to report issues directly on this repo and do not monitor PRs.

Provide feedback here: https://aka.ms/provide-feedback

Or, if you are a trainer with a microsoft.com email address, please create a ticket in AzDO.

# Guide de l’utilisateur GitHub pour les Microsoft Certified Trainer (MCT)

Les services cloud, tels que Microsoft Azure, sont fréquemment mis à jour, ce qui entraîne des problèmes pour les Microsoft Certified Trainers (MCT), car ils enseignent des cours et les étapes de labos ne correspondent plus à nos services cloud. . En raison de la fréquence des modifications et du fait qu’il est possible qu’il n’y ait aucune notification lorsque des modifications se produisent, il peut être difficile pour l’équipe de développement de cours d’identifier et d’ajuster rapidement les modifications apportées au labo.

Pour résoudre ces problèmes, nous utilisons GitHub afin de publier les étapes du labo et les scripts de labo pour les cours traitant des services cloud comme Azure. L’utilisation de GitHub permet aux MCT et aux auteurs du cours de maintenir le contenu du labo à jour avec les modifications apportées au service cloud. L’utilisation de GitHub permet aux MCT de fournir des commentaires et des suggestions en matière de modifications apportées au labo et les auteurs de cours peuvent ensuite rapidement mettre à jour les étapes du labo et les scripts.

Lorsque vous vous préparez à enseigner ces cours, vous devez vérifier que vous utilisez les dernières étapes et scripts de labo en téléchargeant les fichiers appropriés à partir de GitHub.

Ce guide de l’utilisateur est destiné aux MCT qui ne connaissent pas GitHub. Il offre des étapes pour se connecter à GitHub, télécharger et imprimer les matériels de cours, mettre à jour les scripts utilisés par les étudiants dans des labos et expliquer comment vous pouvez veiller à ce que le contenu d’un cours reste à jour.

> **Remarque** : La prise en charge de Microsoft Learning pour l’accès aux fichiers sur GitHub et la prise en charge de la navigation sur le site GitHub sont limitées aux instructeurs MCT qui enseignent ce cours.

Vous ne devez pas utiliser GitHub pour évoquer le contenu technique dans le cours ou la façon de préparer le cours ou ses labos. Il est particulièrement destiné à traiter les modifications dans les labos.

 
> **Remarque** : Pour répondre aux commentaires généraux sur le cours et les versions de démonstration, ou sur la préparation du cours, veuillez utiliser les forums MCT.

## Sections

- [Terminologie GitHub](https://microsoftlearning.github.io/MCT-User-Guide/terminology/)

- [Réception des notifications de mise à jour et collaboration sur des projets](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/)

- Suggérer des modifications ou signaler un problème concernant les instructions d’un labo

## Terminologie GitHub

GitHub présente une terminologie que vous ne connaissez peut-être pas. La liste suivante comprend les termes et concepts utilisés dans ce document. Toutefois, pour obtenir la liste complète des termes GitHub, reportez-vous au [Glossaire GitHub](https://docs.github.com/en/get-started/quickstart/github-glossary).

| Terme| Explication |
| - | - |
| Git et GitHub| Git est un programme open source de suivi des modifications et GitHub est une solution/un site basé sur Git. Il existe d’autres sites web et solutions utilisant Git comme back-end. Vous utiliserez principalement GitHub pour des projets de développement open source (publics) et il est gratuit pour ces projets. Toutefois, si vous souhaitez utiliser GitHub pour des projets privés, et non open source, vous devez vous inscrire à une version payante. |
| Référentiel| Chaque projet dans GitHub se trouve dans un référentiel. Un référentiel comprend tous les fichiers d’un projet, notamment la documentation. Il prend également en charge l’historique des révisions. Un référentiel peut être public ou privé. Vous pouvez avoir une copie locale du référentiel sur votre disque dur d’ordinateur. Vous pouvez également l’utiliser dans GitHub. |
| Markdown| Il s’agit d’un format de fichier texte que vous pouvez utiliser pour créer une documentation. Il est basé sur du texte et très simple à mettre à jour, ce qui facilite son utilisation pendant la collaboration. GitHub l’affiche ensuite au format HTML. |
| GFM (GitHub Flavored Markdown)| Il existe de nombreuses variantes ou versions du format de fichier Markdown. La version GitHub, communément appelée GFM, est l’une des variantes les plus courantes de Markdown. Si vous souhaitez obtenir plus d’informations sur GFM et sur la façon dont vous pouvez utiliser le format Markup pour vos documents GFM, consultez « Bien démarrer l’écriture et la mise en forme sur GitHub » sur https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/. |
| Duplication (fork)| Il s’agit d’une copie d’un autre référentiel qui réside dans votre compte GitHub, par rapport à une branche qui réside dans le référentiel d’origine. Consultez « Branche » directement ci-dessous. |
| Branche| Il s’agit de la copie d’un référentiel qui réside dans le même référentiel que l’original. Vous pouvez fusionner une branche avec l’original. |
| Récupérer| Il s’agit du processus de récupération d’une copie des dernières modifications d’un référentiel en ligne. Toutefois, une extraction ne fusionne pas les modifications. |
| Extraction| Il s’agit du processus d’extraction des dernières modifications d’un référentiel en ligne et de leur fusion avec les modifications locales. |
| Fusionner (Merge)| Il s’agit du processus d’extraction des modifications d’une branche et de leur application à une autre. Il inclut la récupération de modifications à partir d’un référentiel en ligne, puis leur application à la version locale de ce référentiel. |
| Demande de tirage| Il s’agit d’un ensemble de modifications proposées à un référentiel soumis par un utilisateur. Les propriétaires ou collaborateurs d’un référentiel peuvent ensuite accepter ou rejeter la demande de tirage (pull request). |
| Envoi (push)| Il s’agit du processus d’envoi ou de soumission de vos modifications locales au référentiel en ligne. |
| Collaborateur| Il s’agit d’un utilisateur GitHub disposant des autorisations nécessaires pour ajouter, supprimer ou modifier le contenu d’un référentiel. |

## Réception de notifications de mise à jour, suggestion de modifications et collaboration sur des projets

Vous pouvez configurer votre expérience GitHub pour recevoir des notifications lorsque des mises à jour se produisent sur un référentiel GitHub. Il existe plusieurs façons de vous inscrire à des notifications, et beaucoup d’entre elles sont liées aux nombreuses façons dont vous pouvez collaborer sur un projet. Pour recevoir des notifications, vous pouvez effectuer les actions suivantes.

| Action| Description |
| - | - |
| [Surveiller des référentiels](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/watching/)| Lorsque vous surveillez un référentiel, GitHub vous abonne automatiquement aux notifications pour toutes les nouvelles demandes de tirage (pull request) ou problèmes créés pour ce référentiel spécifique. Vous surveillez automatiquement tous les référentiels que vous créez ou pour lesquels vous êtes collaborateur. |
| [Demande de tirage (pull request)](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Lorsque vous créez une demande de tirage (pull request) et que vous proposez que les propriétaires d’un référentiel acceptent une modification que vous apportez, vous vous abonnez automatiquement pour recevoir les notifications concernant la discussion associée sur la demande de tirage (pull request). Si vous souhaitez créer une demande de tirage (pull request), vous devez d’abord créer une branche. |
| [Commentaires](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Lorsque vous envoyez des commentaires sur la demande de tirage (pull request) d’une autre personne, GitHub vous abonne automatiquement au forum se rapportant à ce commentaire, ou vous pouvez vous abonner manuellement au forum. |
| [Problèmes](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Un problème correspond à une suggestion, une question ou une requête qui se rapporte à un référentiel. Chaque problème dispose de sa propre discussion et vous pouvez vous abonner à des problèmes, ou GitHub vous abonne automatiquement aux problèmes que vous créez. |
| [Mentions](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/mention/)| Quand un autre utilisateur vous mentionne dans une conversation en utilisant votre nom d’utilisateur GitHub ([@username](https://github.com/username)), GitHub vous abonne automatiquement à la discussion. |

> **Remarque** : Vous pouvez modifier la façon et le moment où vous recevez des notifications et vous pouvez également vous désabonner d’une ou de toutes les discussions.

## Signaler des problèmes ou suggérer des modifications à apporter aux instructions d’un labo

Si vous avez une suggestion ou rencontrez une erreur dans un labo, vous pouvez envoyer une demande de tirage (pull request) et signaler un problème. Si vous connaissez déjà le correctif de l’erreur, nous vous recommandons d’envoyer une demande de tirage ( pull request). Sinon, signalez un problème.

| Action| Description |
| - | - |
| [Demande de tirage (pull request)](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Lorsque vous créez une demande de tirage (pull request) et que vous proposez que les propriétaires d’un référentiel acceptent une modification que vous apportez, vous vous abonnez automatiquement pour recevoir les notifications concernant la discussion associée sur la demande de tirage (pull request). Si vous souhaitez créer une demande de tirage (pull request), vous devez d’abord créer une branche. |
| [Commentaires](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Lorsque vous envoyez des commentaires sur la demande de tirage (pull request) d’une autre personne, GitHub vous abonne automatiquement au forum se rapportant à ce commentaire, ou vous pouvez vous abonner manuellement au forum. |
| [Problèmes](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Un problème correspond à une suggestion, une question ou une requête qui se rapporte à un référentiel. Chaque problème dispose de sa propre discussion. Vous pouvez vous abonner à des problèmes ou GitHub vous abonne automatiquement aux problèmes que vous créez. |
