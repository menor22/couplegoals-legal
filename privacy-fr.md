---
title: Politique de confidentialité
permalink: /fr/privacy/
lang: fr
---
# Politique de confidentialité

**Date d’entrée en vigueur :** 5 juin 2026
**Dernière mise à jour :** 22 octobre 2026

La présente politique de confidentialité explique comment Yannick Ormen (« nous » ou « CoupleGoals ») collecte, utilise et protège les informations lorsque vous utilisez l’application mobile CoupleGoals (l’« App ») ou ouvrez un lien d’invitation sur couplegoals.ch.

Nous respectons votre vie privée et tenons à être transparents sur les données que nous traitons. Pour toute question, écrivez-nous à **contact@couplegoals.ch**.

*Version anglaise : https://couplegoals.ch/privacy. En cas de divergence, la version anglaise fait foi.*

---

## 1. Qui est responsable du traitement ?

Le responsable du traitement des données personnelles collectées via CoupleGoals est :

**Yannick Ormen**
20E route de Vandoeuvres
1223 Cologny
Suisse

E-mail : contact@couplegoals.ch

Nous sommes établis en Suisse et traitons les données personnelles conformément à la loi fédérale sur la protection des données (LPD, révisée en 2023) et, lorsqu’il s’applique, au Règlement général sur la protection des données de l’UE (RGPD).

---

## 2. Qui peut utiliser CoupleGoals ?

CoupleGoals est conçue pour les adultes en couple. Vous devez avoir **au moins 18 ans** pour créer un compte et utiliser l’App. Nous ne collectons pas sciemment de données personnelles concernant des personnes de moins de 18 ans. Si vous pensez qu’une personne mineure nous a transmis des données personnelles, contactez-nous et nous les supprimerons.

---

## 3. Quelles informations collectons-nous ?

Nous ne collectons que les informations nécessaires au fonctionnement de l’App. Plus précisément :

### 3.1 Informations que vous nous fournissez

- **Informations de compte :** votre adresse e-mail (utilisée pour la connexion) et un nom d’affichage de votre choix. Votre vrai nom n’est pas requis.
- **Identifiants d’authentification :** si vous vous connectez avec Google ou Apple, ces services nous transmettent un identifiant unique et votre adresse e-mail. Nous ne recevons pas votre mot de passe.
- **Données du couple :** lorsque vous formez un couple avec votre partenaire, nous enregistrons le lien entre votre compte et le sien.
- **Contenu que vous créez :** les défis, tâches, événements, réactions (« Sparks ») et notes que vous créez dans l’App. Ce contenu est partagé entre vous et votre partenaire.
- **Saisies facultatives :** titres, dates et notes facultatives des événements, noms de personnes facultatifs (par exemple, à qui est l’anniversaire).
- **Informations d’achat (si vous vous abonnez) :** le paiement est entièrement géré par Apple ; nous ne recevons jamais vos coordonnées de carte ou bancaires, votre identifiant Apple ni votre adresse de facturation. Par l’intermédiaire de RevenueCat (voir la section 6.5), nous recevons l’état de votre abonnement : la formule choisie, les dates d’achat, de renouvellement et d’expiration, s’il sera renouvelé, si un problème de paiement ou un remboursement a eu lieu, la boutique et les identifiants de transaction d’Apple. Ces informations sont liées à l’identifiant de votre compte, et non à votre nom ou à votre e-mail. Votre partenaire voit que votre couple a accès à l’App, et grâce à qui, mais jamais aucune information de paiement.
- **Photo de profil (facultative) :** si vous ajoutez une photo de profil, elle est enregistrée dans Firebase Storage, réduite à 512 pixels au maximum, visible uniquement par vous et votre partenaire, et supprimée lorsque vous supprimez votre compte.

### 3.2 Informations collectées automatiquement

- **Informations sur l’appareil :** type d’appareil, version du système d’exploitation, version de l’App et langue de l’appareil. Elles servent à assurer le bon fonctionnement de l’App sur votre appareil.
- **Jetons de notification push :** un jeton unique généré par le service de notifications push d’Apple (via Firebase Cloud Messaging), qui nous permet d’envoyer des notifications sur votre appareil. Vous pouvez désactiver les notifications à tout moment dans les réglages de votre appareil.
- **Statistiques d’utilisation (pseudonymisées) :** avec PostHog (voir la section 6.2), nous enregistrons la manière dont l’App est utilisée : des actions comme « a validé un défi », « a ouvert les Réglages », « a ouvert une notification » ou « a vu l’écran d’abonnement », les écrans que vous consultez, les événements liés à l’abonnement et à l’essai (début, renouvellement, résiliation, expiration, remboursement, problème de paiement ; début et fin de l’essai), ainsi que des rapports d’erreur techniques lorsqu’un problème survient dans l’App. Chaque événement est lié à un identifiant de compte aléatoire et, une fois en couple, à un identifiant de couple aléatoire — jamais à votre nom, à votre e-mail ou à votre photo, ni à ce que vous écrivez (titres de défis, notes, messages). Les événements comportent aussi un contexte technique : modèle d’appareil, versions du système d’exploitation et de l’App, langue, fuseau horaire, type de réseau (Wi-Fi ou mobile) et le fait qu’il s’agisse ou non d’une version de test de l’App. Les prix ne sont jamais enregistrés. PostHog est configuré pour ne pas conserver votre adresse IP, et nous ne l’utilisons pas pour vous localiser. Vous pouvez désactiver ces statistiques à tout moment dans l’App (Réglages → Confidentialité → Partager les statistiques d’utilisation) : dès lors, plus aucun événement d’utilisation n’est enregistré à votre sujet, ni depuis l’App ni depuis nos serveurs.
- **Liens et codes d’invitation :** lorsque vous ouvrez un lien d’invitation (couplegoals.ch/invite/), la page compte une visite : le type d’appareil (iPhone, Android ou autre), la langue de la page et si le lien contenait un code. Le code lui-même ne quitte jamais votre navigateur. Ce comptage est transmis à PostHog sans identifiant permettant de le relier à vous ou à d’autres visites, et sans votre adresse IP. Pour limiter les abus, notre serveur compte les tentatives : les visites de la page d’invitation par adresse IP et, lorsque vous saisissez le code de votre partenaire dans l’App, les tentatives par compte, par adresse IP et par code saisi. Les adresses IP et les codes ne sont conservés que sous une forme hachée avec une clé secrète (une transformation à sens unique), jamais en clair, avec l’heure des tentatives. Ces données sont supprimées automatiquement, normalement dans les deux jours suivant la dernière tentative. La page d’invitation ne dépose aucun cookie et ne charge aucun script, police ni traceur de tiers.

### 3.3 Informations que nous ne collectons pas

Nous ne collectons pas : vos contacts, votre localisation, votre microphone, votre appareil photo, vos données biométriques, vos données de santé, vos coordonnées de carte de paiement ou bancaires, ni votre historique de navigation en dehors de l’App. (La seule image que nous enregistrons est la photo de profil facultative que vous choisissez d’ajouter — voir la section 3.1.)

---

## 4. Comment utilisons-nous vos informations ?

Nous utilisons vos informations pour :

- Fournir les fonctionnalités essentielles de l’App (créer les comptes, former les couples, enregistrer et synchroniser votre contenu partagé, envoyer les notifications).
- Vous donner accès, à vous et à votre partenaire, aux fonctionnalités payantes auxquelles vous vous êtes abonnés, maintenir cet accès à jour lorsque vous changez de partenaire ou restaurez un achat sur un autre appareil, et détecter lorsque vous payez tous les deux pour le même couple afin de vous en informer.
- Vous envoyer des notifications sur l’activité de votre partenaire (avec votre consentement — géré dans les réglages de notification de votre appareil).
- Classer vos défis (par exemple, à quel moment de la journée ils se font) et écrire les textes de leurs rappels (voir la section 6.4).
- Assurer la sécurité, prévenir la fraude et résoudre les problèmes techniques.
- Comprendre, de manière globale, comment l’App est utilisée afin de l’améliorer.
- Vous contacter au sujet de votre compte ou de changements importants de l’App (uniquement si nécessaire).

Nous n’utilisons pas vos données à des fins publicitaires. Nous ne vendons ni ne louons vos données personnelles à quiconque.

---

## 5. Bases juridiques du traitement (utilisateurs soumis au RGPD)

Si vous vous trouvez dans l’Union européenne, au Royaume-Uni ou dans une autre juridiction soumise à une législation équivalente au RGPD, les bases juridiques de nos traitements sont :

- **Exécution du contrat (art. 6, par. 1, let. b RGPD) :** pour vous fournir les services de l’App, y compris l’abonnement que vous avez souscrit.
- **Intérêts légitimes (art. 6, par. 1, let. f RGPD) :** pour assurer la sécurité, prévenir la fraude et améliorer l’App d’une manière qui ne porte pas atteinte à vos intérêts en matière de vie privée.
- **Consentement (art. 6, par. 1, let. a RGPD) :** pour les notifications push et toute fonctionnalité facultative que vous activez expressément.

Vous pouvez retirer votre consentement à tout moment, sans que cela affecte les traitements effectués auparavant.

---

## 6. Avec qui partageons-nous vos données ?

Nous partageons des données avec les prestataires suivants, qui agissent en tant que sous-traitants pour notre compte :

### 6.1 Firebase (Google LLC)
Nous utilisons Firebase Authentication (connexion), Firestore (stockage des données), Cloud Functions (logique serveur) et Cloud Messaging (notifications push). Vos données sont stockées dans la région multirégionale européenne de Firebase (`eur3`), qui regroupe des centres de données en Belgique et aux Pays-Bas. Politique de confidentialité de Google : https://policies.google.com/privacy

### 6.2 PostHog (PostHog Inc.)
Nous utilisons PostHog Cloud (instance UE) pour les statistiques d’utilisation. Ces données sont stockées à Francfort, en Allemagne. Politique de confidentialité de PostHog : https://posthog.com/privacy

### 6.3 Service de notifications push d’Apple (Apple Inc.)
Utilisé pour envoyer les notifications push sur votre appareil. Politique de confidentialité d’Apple : https://www.apple.com/legal/privacy/

### 6.4 Anthropic (Anthropic PBC)
Pour classer vos défis (par exemple, à quel moment de la journée ils se font) et écrire les textes de leurs rappels, nous envoyons à l’API Claude d’Anthropic les titres de vos défis non privés, sans nom ni identifiant de compte. Rien d’autre n’est envoyé : aucun compteur ni aucune activité, et jamais de noms, d’identifiants de compte, de notes, de messages entre vous (y compris les Sparks), de textes de récompense ou de gage, ni de défis privés. Les défis choisis dans le catalogue intégré, avec leur titre inchangé, ne sont pas envoyés. Selon ses conditions commerciales, Anthropic traite ces données pour notre compte et ne peut pas les utiliser pour entraîner ses modèles. Politique de confidentialité d’Anthropic : https://www.anthropic.com/legal/privacy

### 6.5 RevenueCat (abonnements)
Nous utilisons RevenueCat, Inc. (États-Unis) pour gérer les abonnements souscrits sur l’App Store. RevenueCat reçoit l’identifiant technique de votre compte (pas votre nom ni votre e-mail), vos informations d’achat et d’abonnement transmises par Apple, ainsi que des données techniques (modèle d’appareil, version de l’App, système d’exploitation, pays, adresse IP). Ces données sont hébergées aux États-Unis. Le transfert est régi par l’accord de traitement des données de RevenueCat, qui intègre les clauses contractuelles types de la Commission européenne, adaptées au droit suisse (LPD). Les événements d’abonnement (par exemple « abonnement commencé » ou « renouvelé », sans prix ni information de paiement) sont également enregistrés dans nos statistiques d’utilisation (section 6.2), sous le même identifiant de compte. Politique de confidentialité de RevenueCat : https://www.revenuecat.com/privacy

Apple traite votre paiement en tant que responsable du traitement indépendant, selon sa propre politique de confidentialité : https://www.apple.com/legal/privacy/

Nous ne communiquons vos données personnelles à aucun autre tiers. Nous ne partageons aucune donnée à des fins publicitaires.

---

## 7. Où vos données sont-elles stockées ?

Vos données sont stockées principalement dans l’Union européenne (Belgique, Pays-Bas et Allemagne), auprès des prestataires énumérés à la section 6. Certaines métadonnées peuvent transiter par d’autres régions pour des raisons techniques (par exemple l’acheminement des notifications push d’Apple). Nos prestataires disposent de garanties reconnues pour ces transferts (clauses contractuelles types, décisions d’adéquation le cas échéant).

Les fonctionnalités décrites à la section 6.4 font exception à ce stockage prioritairement européen. Les données qui y sont décrites (titres des défis non privés, sans nom ni identifiant de compte) sont envoyées à l’API Claude d’Anthropic et traitées sur l’infrastructure d’Anthropic aux États-Unis. Aucun nom, identifiant de compte ni autre contenu n’y est joint. Notre utilisation de l’API Claude est régie par les conditions commerciales d’Anthropic (Commercial Terms of Service), qui intègrent par renvoi l’avenant relatif au traitement des données d’Anthropic (Data Processing Addendum) ; cet avenant intègre les clauses contractuelles types de la Commission européenne (avec leurs équivalents britannique et suisse) dans la mesure requise par le droit de la protection des données applicable, comme garantie pour ce transfert. Les défis choisis dans le catalogue intégré ne sont pas envoyés.

Les abonnements constituent une seconde exception. RevenueCat reçoit aux États-Unis les données décrites à la section 6.5 ; l’App se connecte à RevenueCat à son démarrage, même si vous ne vous abonnez jamais. Aucun contenu que vous créez dans l’App (défis, tâches, événements, notes, photos) n’est envoyé. Le transfert est régi par l’accord de traitement des données de RevenueCat, qui intègre les clauses contractuelles types de la Commission européenne, adaptées au droit suisse (LPD).

---

## 8. Combien de temps conservons-nous vos données ?

- **Comptes actifs :** aussi longtemps que votre compte existe.
- **Comptes supprimés :** lorsque vous supprimez votre compte dans l’App, vos données personnelles sont effacées de nos bases de données actives dans un délai de 30 jours. Certaines données peuvent subsister brièvement dans des sauvegardes chiffrées (jusqu’à 90 jours) avant d’être définitivement écrasées.
- **Informations d’achat :** aussi longtemps que votre compte existe. Lorsque vous supprimez votre compte, notre copie est supprimée et nous demandons à RevenueCat de supprimer votre fiche client. Apple conserve ses propres données sur vos achats selon sa politique de confidentialité, et nous pouvons conserver des rapports financiers d’Apple qui ne vous identifient pas, comme l’exige le droit comptable.
- **Statistiques d’utilisation :** les événements d’utilisation sont conservés 12 mois, puis supprimés. Lorsque vous supprimez votre compte, votre profil statistique est supprimé ; les événements déjà enregistrés sont conservés jusqu’à la fin de cette période, liés uniquement à l’identifiant de compte aléatoire, et plus aucun nouvel événement n’est enregistré.
- **Comptages anti-abus :** les comptages de tentatives décrits à la section 3.2 (liens et codes d’invitation) sont supprimés automatiquement, normalement dans les deux jours suivant la dernière tentative.
- **Données envoyées à Anthropic (section 6.4) :** Anthropic les supprime dans un délai de 30 jours, sauf si ses systèmes de sécurité automatisés les signalent comme contraires à sa politique d’utilisation (elles peuvent alors être conservées jusqu’à 2 ans) ou si la loi impose une conservation plus longue. La classification et les textes de rappel produits sont enregistrés avec votre défi et supprimés avec lui. Les faits généraux qu’elle écrit et qui passent nos vérifications (par exemple « 15 minutes par jour, c’est environ 91 heures par an ») peuvent être conservés, sans titre, nom ni identifiant de compte, et réutilisés dans les rappels d’autres défis.

---

## 9. Vos droits

En vertu de la LPD et, le cas échéant, du RGPD, vous avez le droit :

- **D’accès** aux données personnelles que nous détenons à votre sujet.
- **De rectification** des données inexactes ou incomplètes.
- **D’effacement** (« droit à l’oubli ») de vos données personnelles — directement dans l’App (Réglages → Supprimer le compte) ou en nous contactant.
- **De limitation** de certains traitements ou **d’opposition** à ceux-ci. Vous pouvez vous opposer aux statistiques d’utilisation directement dans l’App (Réglages → Confidentialité → Partager les statistiques d’utilisation).
- **À la portabilité** — recevoir vos données dans un format lisible par machine.
- **De retirer votre consentement** pour tout traitement fondé sur celui-ci.
- **D’introduire une réclamation** auprès d’une autorité de contrôle. En Suisse : le Préposé fédéral à la protection des données et à la transparence (PFPDT, https://www.edoeb.admin.ch). Dans l’UE : votre autorité nationale de protection des données.

Pour exercer l’un de ces droits, écrivez-nous à **contact@couplegoals.ch**. Nous vous répondrons dans un délai de 30 jours.

---

## 10. Suppression du compte

Vous pouvez supprimer votre compte CoupleGoals à tout moment depuis l’App (Réglages → Supprimer le compte). Une confirmation claire vous est présentée avant la suppression. **Cette action est irréversible.**

**Ce qui est supprimé.** Votre profil et votre photo de profil, vos validations, les défis que vous avez créés en solo, ainsi que les tâches, listes et événements que vous avez ajoutés. Une liste que vous avez créée n’est conservée que si votre partenaire y a ajouté des éléments : elle lui est alors transférée, et les éléments que vous y avez ajoutés sont supprimés. Votre profil statistique est également supprimé, et plus rien n’est enregistré à votre sujet ; les événements d’utilisation déjà enregistrés ne sont conservés que jusqu’à la fin de leur durée de conservation (section 8), liés à un identifiant aléatoire, et non à votre nom ou à votre e-mail.

**Ce que votre partenaire conserve.** CoupleGoals est une application à deux : certaines données sont donc partagées. La suppression de votre compte ne supprime pas les données propres à votre partenaire : ses validations, ses propres défis, ainsi que les tâches, listes et événements qu’il ou elle a ajoutés lui restent. Les défis que vous faisiez ensemble continuent à son nom. Les défis passés restent dans son historique, où vous n’apparaissez plus que comme « Compte supprimé », sans votre nom ni votre photo. Les paris entre vous prennent fin sans résultat : personne ne gagne ni ne perd, et aucune récompense ni aucun gage ne s’applique.

**Information de votre partenaire.** Votre partenaire est informé une seule fois, dans l’App, que votre compte a été supprimé, avec votre nom d’affichage. Ce nom est effacé dès qu’il ou elle a vu l’information, et au plus tard après 30 jours.

**Abonnements.** La suppression de votre compte n’annule pas un abonnement App Store : Apple continue de facturer jusqu’à ce que vous le résiliiez dans les réglages de votre identifiant Apple (Réglages → votre nom → Abonnements). L’App vous le rappelle avant la suppression de votre compte, avec un lien vers ces réglages. Vos informations d’achat sont supprimées avec votre compte (section 8).

Après la suppression, vos données personnelles sont effacées de nos bases de données actives dans un délai de 30 jours. Voir la section 8 pour la conservation dans les sauvegardes.

---

## 11. Sécurité

Nous prenons des mesures techniques et organisationnelles raisonnables pour protéger vos données, notamment :

- Le chiffrement en transit (HTTPS / TLS pour toutes les requêtes réseau).
- Le chiffrement au repos (assuré par les infrastructures de Firebase, PostHog et RevenueCat).
- Des contrôles d’accès limitant qui peut lire vos données (seuls vous et votre partenaire voyez votre contenu partagé ; seuls des administrateurs autorisés ont accès à l’infrastructure).
- Des revues de sécurité et des mises à jour régulières.

Aucun système n’est parfaitement sûr. En cas de violation de la sécurité des données vous concernant, nous vous en informerons, ainsi que l’autorité de contrôle compétente, conformément au droit applicable (dans les 72 heures selon le RGPD).

---

## 12. Protection des mineurs

CoupleGoals n’est pas destinée aux personnes de moins de 18 ans. Nous ne collectons pas sciemment de données personnelles concernant des mineurs. Si vous apprenez qu’une personne mineure a utilisé l’App, contactez-nous afin que nous puissions supprimer ses données.

---

## 13. Modifications de la présente politique

Nous pouvons mettre à jour la présente politique de confidentialité de temps à autre. Dans ce cas, nous modifierons la date de « Dernière mise à jour » ci-dessus et, pour les changements importants, nous vous en informerons dans l’App ou par e-mail. Continuer à utiliser l’App après une modification vaut acceptation de la politique mise à jour.

---

## 14. Contact

Pour toute question relative à la confidentialité, toute demande concernant vos données ou pour signaler un problème :

**Yannick Ormen**
E-mail : contact@couplegoals.ch
Adresse postale : 20E route de Vandoeuvres, 1223 Cologny, Suisse

Nous nous efforçons de répondre dans un délai de 30 jours.

---

*La présente politique de confidentialité a été mise à jour pour la dernière fois le 20 octobre 2026. Un historique versionné est disponible sur https://github.com/menor22/couplegoals-legal.*
