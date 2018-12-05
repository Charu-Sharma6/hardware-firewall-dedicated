---

copyright:
  years: 2017
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# Contournement des règles de pare-feu

Pour contourner les règles de pare-feu :

1. Depuis votre navigateur, ouvrez le [Portail client ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://control.softlayer.com/){: new_window} et connectez-vous à votre compte.
2. Dans la navigation du portail client, accédez à **Réseau > Gestion IP > VLAN** et cliquez sur l'unité pare-feu que vous souhaitez contourner.
3. Sur la page **Détails de l'unité**, dans l'onglet **Configuration**, vous pouvez utiliser le menu déroulant **Actions** pour sélectionner **Paramétrer mode de contournement de route** ou, à la section **Statut :**, vous pouvez cliquer sur **Contourner les Règles**. 

	Une autre option consiste à contourner le pare-feu en cliquant sur **Route Autour**. Dans tous les cas, vous obtiendrez une boîte de dialogue de confirmation. Cliquez sur **Oui** pour confirmer l'action. Le contournement des règles prend environ deux minutes pour entrer en vigueur. En mode contournement, la zone "Statut" indique "Routage AUTOUR du pare-feu".

## Réactivation des règles

Pour réactiver les règles, suivez les instructions ci-dessus pour accéder à l'onglet **Configuration** de l'unité, cliquez sur le menu déroulant **Actions** et sélectionnez **Paramétrer mode de contournement de route**. Vous obtenez alors une boîte de dialogue de confirmation. Cliquez sur **Oui** pour confirmer l'action. La zone "Statut" revient à "Routage À TRAVERS le pare-feu" en l'espace de deux minutes.
