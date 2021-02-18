---
layout: rm_post
title: Ceci est une page de test Markdown
subtitle: "Quelques vidéos durant le 1er confinement pour remercier les commerçants de rester ouvert. Merci et Bravo à eux !"
header-img: assets/images/2020_merci-a-nos-commercants/merci-a-nos-comercants-banner.png
---

# {{ page.title }}

**Suspendisse vitae massa sagittis, suscipit odio quis, condimentum risus. Ut diam risus, congue non metus eget, viverra fringilla nulla. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nullam nisi nulla, tincidunt non iac**

## Titre 2
Suspendisse vitae massa sagittis, suscipit odio quis, condimentum risus. Ut diam risus, congue non metus eget, viverra fringilla nulla. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nullam nisi nulla, tincidunt non iaculis ut, porta in purus. Donec in sagittis lacus, et luctus nisi. Aenean eu pretium ante. Donec sed turpis volutpat, dignissim lorem in, congue orci. Proin sed vestibulum erat. Nulla malesuada lorem eget feugiat interdum. 

## Titre 2
Sed fringilla maximus justo vel dictum. Praesent neque magna, lacinia at dignissim eget, varius vel ligula. Suspendisse tincidunt sit amet magna eu dignissim. Integer ornare posuere quam. Maecenas risus quam, facilisis faucibus aliquam pellentesque, volutpat eget nisi.

### Titre 3
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris in vestibulum turpis. Nullam quis odio nec erat finibus rutrum. Phasellus at pretium diam. Quisque volutpat, urna in ultrices gravida, arcu mi luctus ligula, et volutpat nunc sem at nulla. Vivamus sit amet eros arcu. Donec luctus pellentesque tellus, porta efficitur magna tempor in. Maecenas eleifend eget libero eget cursus. Mauris vitae ultrices ligula. Fusce placerat rutrum sem ac interdum. Curabitur egestas ante vitae diam vestibulum, eu finibus nisl luctus. Cras sem magna, imperdiet vel ligula quis, semper sagittis elit. Pellentesque ullamcorper metus ac tortor accumsan tincidunt.

#### Titre 4
Sed in magna non sem laoreet hendrerit sed a urna. Sed pretium id leo sit amet commodo. Proin luctus lacus mollis, pharetra dui et, rutrum nunc. Aenean nec metus dui. Praesent ac lorem sed ante rhoncus auctor quis et velit. Donec porta, felis eu porttitor consectetur, massa est maximus nisl, id pharetra ipsum eros non metus. Nulla aliquet consectetur tellus sit amet bibendum. Nullam sed sodales massa. Nullam rutrum, massa non posuere gravida, mauris nisl ultricies nisi, non dictum ex arcu sed erat. Aliquam volutpat libero at vulputate pulvinar. Fusce vel bibendum nunc, ut aliquet purus. Vivamus convallis pulvinar justo a auctor.

#### Une image 600x600 : en pleine largeur sur smartphone / centrée sur PC

Lorsque l'on écrit le code en Markdown, une balise **P** est ajoutée autour de la balige **IMG**. Si **P** possède dans son style une marge (ex: 10px) alors cela complique la tache pour obtenir une image sans marge. En effet, en tant qu'*inline element* (en terme de display), l'image est alors contenue dans un *block element* **P** qui lui impose sa propre marge (sauf si on applique une *position: 'absolute'*, mais cela pose d'autres soucis).

La solution la plus simple consiste à appliquer un style à la balise **P** contenant l'image. Pour ce faire, on utilise un **kramdown block attribute** afin d'indiquer la classe du **P** (que l'on stylise en CSS ensuite pour enlever la marge dans ce cas spécifique.).

![texte alternatif à l'image](/assets/placeholders/web_medium_600x600.jpg "Description de l info-bulle image")
{: .pContainerOfImage}

D'après les tests, c'est OK pour l'affichage.

#### Des images larges

Une image de 1500x500 pour commencer.

![Image large 1](/assets/placeholders/web_large_1000x500.jpg "Description de l info-bulle image")
{: .pContainerOfImage}

Puis une image de 1600x900 pour voir ce que cela change.

![Image large 2](/assets/placeholders/web_large_1600x900.jpg "Description de l info-bulle image")
{: .pContainerOfImage}

#### Text + Une image flotante

<figure>
  <img src="/assets/placeholders/web_medium_500x500.jpg" alt="Deuxieme image">
  <figcaption>Un placeholder Medium 500 x 500</figcaption>
</figure>

Praesent et arcu ac nunc fermentum ultrices. Aliquam eget odio ac tortor imperdiet consequat. Sed purus lorem, semper at auctor id, ullamcorper eu elit. Fusce sed aliquet ante, at tristique arcu. Nulla maximus elementum metus, ac tempor tellus rhoncus in. Sed lacinia accumsan lacinia. In non tortor consequat, placerat felis aliquet, faucibus arcu.

Voici une citation.

<div class="paf">
<blockquote>The man who comes back through the door in the wall will never be quite the same as the man who went out.</blockquote>
<cite>Aldous Huxley</cite>
</div>

Praesent et arcu ac nunc fermentum ultrices. Aliquam eget odio ac tortor imperdiet consequat. Sed purus lorem, semper at auctor id, ullamcorper eu elit. Fusce sed aliquet ante, at tristique arcu. Nulla maximus elementum metus, ac tempor tellus rhoncus in. Sed lacinia accumsan lacinia. In non tortor consequat, placerat felis aliquet, faucibus arcu.

Nulla rhoncus ac leo facilisis pulvinar. Donec quis velit ultrices, volutpat risus id, commodo enim. Nunc volutpat et tellus at eleifend. Mauris mauris tortor, condimentum vel congue vitae, lacinia aliquam urna. Aenean volutpat a massa ac laoreet. Sed fringilla maximus justo vel dictum. Praesent neque magna, lacinia at dignissim eget, varius vel ligula. Suspendisse tincidunt sit amet magna eu dignissim. Integer ornare posuere quam. Maecenas risus quam, facilisis faucibus aliquam pellentesque, volutpat eget nisi.

Vivamus id fringilla odio. In et sapien euismod, rhoncus nulla aliquam, viverra justo. Suspendisse vitae massa sagittis, suscipit odio quis, condimentum risus. Ut diam risus, congue non metus eget, viverra fringilla nulla. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nullam nisi nulla, tincidunt non iaculis ut, porta in purus. Donec in sagittis lacus, et luctus nisi. Aenean eu pretium ante. Donec sed turpis volutpat, dignissim lorem in, congue orci. Proin sed vestibulum erat. Nulla malesuada lorem eget feugiat interdum. 

# Titre 1
## Titre 2
### Titre 3
#### Titre 4
##### Titre 5
###### Titre 6 : NOT USED YET
Maecenas mattis interdum lacus, non ornare ex pellentesque ac. Mauris consequat risus cursus convallis luctus. Nam odio elit, tincidunt quis lectus ut, tristique accumsan lorem.

<p>CECI EST UN TEST DE PICTURE</p>

<div class="rm_fullwidth">
    <picture>
        <source
        srcset="/assets/placeholders/web_medium_600x600.jpg"
        type="image/jpg"
        media="all and (max-width:600px)"
        />
        <source
        srcset="/assets/placeholders/web_large_1000x500.jpg"
        type="image/jpg"
        media="all and (min-width:601px) and (max-width:1200px)"
        />
        <source
        srcset="/assets/placeholders/web_large_1600x900.jpg"
        type="image/jpg"
        media="all and (min-width:1021px)"
        />
        <!-- default image -->
        <img src="/assets/placeholders/web_large_1000x500.jpg" alt="an image of the site" />
    </picture>
</div>

