---
translationKey: index
order: 1
lang: fr
createdAt: 2026-09-15T09:41:00.000Z
ldType: WebPage
name: Accueil
metadata:
  title: Car-Pro.app — Le copilote intelligent pour les professionnels du VO
  description: Solution tout-en-un pour les professionnels du véhicule d'occasion — photos, stock, annonces, prix du marché, facturation.
---

:::: section {.palette--contrast .bleed-bg .text-center .breathe}

# _Car_-Pro._app_

Le copilote intelligent pour les professionnels du VO { .h3 }
::::

::: section

## Tu es un professionnel du VO?

Découvre une solution pensée pour simplifier ton quotidien et booster ton activité. { .font-size-[--step-1] }

{% image src="/_images/screenshot_2026-09-15_15-17-01-crop.webp", alt="Tableau de bord principal de l'app", loading="eager" %}

:::

{% sectionBuilder class="how-it-works width-prose flow space:--py-section" %}
{% sectionHeader  %}
## Comment ça marche

**5' chrono pour ajouter un véhicule à ton stock et publier ton annonce** { .size-h4 .palette--pop }
{% endsectionHeader %}
{% twoColumns fixedSide="fixedRight", type="fixedFluid", class="container" %}
{% twoColumnsItem  %}
### 1. Prends des photos

Envoie quelques photos des **documents de bord** ainsi que **du véhicule**.

Capture-les directement avec ton smartphone, charge-les depuis tes dossiers ou transfère-les depuis un message Whatsapp.

Les photos dédiées à l'annonce sont **automatiquement séparées** de celles des documents.

**Toutes les infos du véhicule sont retrouvées automatiquement.**
{% endtwoColumnsItem %}
{% twoColumnsItem  %}
{% image src="/_images/screen-mobile-add_photos.webp", alt="Ajoute des photos. L'application détecte automatiquement les documents.", width=300 %}
{% endtwoColumnsItem %}
{% endtwoColumns %}
{% twoColumns fixedSide="fixedRight", type="fixedFluid", class="container" %}
{% twoColumnsItem  %}
### 2. Ajoute à ton stock

Tu achètes le véhicule? En **un clic**, ajoute-le à ton stock avec toutes les infos techniques et administratives le concernant.

Ajoute ton prix d'achat et de vente, et **suis ton stock en un coup d'œil**.

On te propose même un **comparateur intégré** pour vérifier les prix de véhicules similaires sur le marché.
{% endtwoColumnsItem %}
{% twoColumnsItem  %}
<video controls width="300">
  <source src="/assets/files/demo-mobile-stock.mp4" type="video/mp4" />

  Download the
  <a href="/assets/files/demo-mobile-stock.mp4">MP4</a>
  video.
</video>
{% endtwoColumnsItem %}
{% endtwoColumns %}
{% twoColumns fixedSide="fixedRight", type="fixedFluid", class="container" %}
{% twoColumnsItem  %}
### 3. Ton annonce est prête!

**On rédige ton annonce avec ton style habituel** et on prépare tout pour que tu n'aies plus qu'à cliquer sur "Envoyer".

Ton annonce est automatiquement publiée sur **toutes tes plateformes préférées** en un clic.

Tu souhaites modifier le prix par la suite? Facile! Modifie-le directement depuis l'application et il sera mis à jour sur toutes les plateformes.
{% endtwoColumnsItem %}
{% twoColumnsItem  %}
{% image src="/_images/ads-publishing-preview.webp", alt="preview publication multi-plateformes", width=300 %}
{% endtwoColumnsItem %}
{% endtwoColumns %}

{% endsectionBuilder %}

:::: section { #contact-section .palette--pop-contrast .box .width-prose .text-center .breathe .px-body }

## **Contacte-nous vite pour une démonstration gratuite!** { .h3 }

L'application sera bientôt disponible pour une sélection restreinte de marchands en accès privé.

<div class="box prose breathe-section h4">
{% link url="tel:+32472944611", type="external" %}+32 472 944 611{% endlink %}

{% htmlPartial "email-link.njk" %}

</div>

{% htmlPartial "contact-form.njk" %}

::::

{% sectionGrid  %}
{% sectionHeader  %}
## Et ce n'est qu'un avant-gout...
{% endsectionHeader %}
{% grid type="switcher", widthWrap="24.9rem", class="width-prose" %}
{% gridItem  %}
### Déjà opérationnel

- Planification et gestion du stock
- Suivi du prix d'achat et de vente
- Affiche A4 imprimable pour le véhicule
- Synchronisation Carpass
- Facturation simplifiée
- …
{% endgridItem %}
{% gridItem  %}
### À Venir

- Analyse des prix du marché
- Un Trade inter-marchands
- …
{% endgridItem %}
{% endgrid %}

{% endsectionGrid %}

{% partial "galery-screens.md" %}

<style>
@container (width < 90vw) {
  .how-it-works .fixed-fluid:nth-child(odd) > div:first-child {
    order: 2;
  }
}
</style>
