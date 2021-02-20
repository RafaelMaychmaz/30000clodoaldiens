---
layout: rm_post
title: Ceci est une page de test Markdown
subtitle: "Quelques vidéos durant le 1er confinement pour remercier les commerçants de rester ouvert. Merci et Bravo à eux !"
header-img: assets/images/2020_merci-a-nos-commercants/merci-a-nos-comercants-banner.png
---

# {{ page.title }}

**Suspendisse vitae massa sagittis, suscipit odio quis, condimentum risus. Ut diam risus, congue non metus eget, viverra fringilla nulla. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nullam nisi nulla, tincidunt non iac**


## Titre A
Ci-dessus un exemple d'un titre <tagcode>h2</tagcode>.

*Note: le titre <tagcode>h1</tagcode> est utilisé pour le grand titre global tout en haut de la page.*
### Titre A.1
Ci-dessus un exemple d'un titre <tagcode>h3</tagcode>.
#### Titre A.1.1
Ci-dessus un exemple d'un titre <tagcode>h4</tagcode>.
##### Titre 5 : NOT USED YET
Ci-dessus un exemple d'un titre <tagcode>h5</tagcode>. Ce n'est pas utilisé comme un titre dans ce site.
###### Titre 6 : NOT USED YET
Ci-dessus un exemple d'un titre <tagcode>h6</tagcode>. Ce n'est pas utilisé comme un titre dans ce site.

## Citation

Voici une citation.

<div class="paf">
<blockquote>The man who comes back through the door in the wall will never be quite the same as the man who went out.</blockquote>
<cite>Aldous Huxley</cite>
</div>

Praesent et arcu ac nunc fermentum ultrices. Aliquam eget odio ac tortor imperdiet consequat. Sed purus lorem, semper at auctor id, ullamcorper eu elit. Fusce sed aliquet ante, at tristique arcu. Nulla maximus elementum metus, ac tempor tellus rhoncus in. Sed lacinia accumsan lacinia. In non tortor consequat, placerat felis aliquet, faucibus arcu.
{: .p_loremipsum}

## IMAGES CENTRÉES
Ce § explore les possibilités pour les images imbriquée dans un <tagcode>img</tagcode>.

### Carré
Lorsque l'on écrit le code en Markdown, une balise **P** est ajoutée autour de la balige **IMG**. Si **P** possède dans son style une marge (ex: 10px) alors cela complique la tache pour obtenir une image sans marge. En effet, en tant qu'*inline element* (en terme de display), l'image est alors contenue dans un *block element* **P** qui lui impose sa propre marge (sauf si on applique une *position: 'absolute'*, mais cela pose d'autres soucis).

La solution la plus simple consiste à appliquer un style à la balise **P** contenant l'image. Pour ce faire, on utilise un **kramdown block attribute** afin d'indiquer la classe du **P** (que l'on stylise en CSS ensuite pour enlever la marge dans ce cas spécifique.).

![texte alternatif à l'image](/assets/placeholders/web_square_1500x1500.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros.
{: .p_loremipsum}

### Portrait

Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros.
{: .p_loremipsum}

![texte alternatif à l'image](/assets/placeholders/web_portrait_1.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros.
{: .p_loremipsum}

![texte alternatif à l'image](/assets/placeholders/web_portrait_2.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros.
{: .p_loremipsum}

![texte alternatif à l'image](/assets/placeholders/web_portrait_3.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros.
{: .p_loremipsum}

![texte alternatif à l'image](/assets/placeholders/web_portrait_4.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

D'après les tests, c'est OK pour l'affichage.

### Paysage

![texte alternatif à l'image](/assets/placeholders/web_landscape_1.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

![texte alternatif à l'image](/assets/placeholders/web_landscape_2.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

![texte alternatif à l'image](/assets/placeholders/web_landscape_3.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

## IMAGES FLOTTANTES
Dans un contexte flottant, le texte à côté de l'image doit être important pour ne pas créer d'espace vide entre la fin du texte et le début du paragraphe suivante l'image. Il est même possiblede déborder si on le souhaite; donc il ne faut pas hésiter à faire du remplissage :)

Le deuxième point important pour le cas des images flottantes est que pour avoir un text flow qui reprend normalement après, il faut reinitialiser le context. Cela ce fait en encapsulant l'image flottante et le texte qui va à coté par un **div** comme suit:

{% highlight html %}
<div class="clearfix">
<img class="img_1_portait_floatright" src="ma_super_image.jpg" alt="Texte alternatif à mon image">
<p>Mon super texte qui doit être assez volumineux et qui va à côté de l'image flottante</p>
</div>
{% endhighlight %}

En effet le style CCS associé à cette classe de **div** permet de reprendre un text flow normal ensuite.

### Portrait

#### A droite

<div class="clearfix">
<img class="img_1_portait_floatright" src="/assets/placeholders/web_portrait_1.jpg" alt="Image flottante à droite de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatright" src="/assets/placeholders/web_portrait_2.jpg" alt="Image flottante à droite de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatright" src="/assets/placeholders/web_portrait_3.jpg" alt="Image flottante à droite de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatright" src="/assets/placeholders/web_portrait_4.jpg" alt="Image flottante à droite de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

#### A gauche

<div class="clearfix">
<img class="img_1_portait_floatleft" src="/assets/placeholders/web_portrait_1.jpg" alt="Image flottante à gauche de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatleft" src="/assets/placeholders/web_portrait_2.jpg" alt="Image flottante à gauche de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatleft" src="/assets/placeholders/web_portrait_3.jpg" alt="Image flottante à gauche de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatleft" src="/assets/placeholders/web_portrait_4.jpg" alt="Image flottante à gauche de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

### Landscape

#### A droite

<div class="clearfix">
<img class="img_1_landscape_floatright" src="/assets/placeholders/web_landscape_1.jpg" alt="Image flottante à droite de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_landscape_floatright" src="/assets/placeholders/web_landscape_2.jpg" alt="Image flottante à droite de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_landscape_floatright" src="/assets/placeholders/web_landscape_3.jpg" alt="Image flottante à droite de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

#### A gauche

<div class="clearfix">
<img class="img_1_landscape_floatleft" src="/assets/placeholders/web_landscape_1.jpg" alt="Image flottante à gauche de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_landscape_floatleft" src="/assets/placeholders/web_landscape_2.jpg" alt="Image flottante à gauche de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_landscape_floatleft" src="/assets/placeholders/web_landscape_3.jpg" alt="Image flottante à gauche de 50%">
<p class="p_loremipsum">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p class="p_loremipsum">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p class="p_loremipsum">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>





## FIGURE
Ce § explore les possibilités pour les images imbriquée dans un <tagcode>figure</tagcode>

## Text + Une image flotante

{% highlight html %}
<figure>
  <img src="/assets/placeholders/web_medium_500x500.jpg" alt="Deuxieme image" class="img_1_centered">
  <figcaption>Un placeholder Medium 500 x 500</figcaption>
</figure>
{% endhighlight %}

Pour placer la légende à droite de l'image, il suffit de déclarer <tagcode>img</tagcode> avant <tagcode>figcaption</tagcode>.

<figure class="figure_withsidelegend">
  <img src="/assets/placeholders/web_landscape_3.jpg" alt="Deuxieme image" class="figure_withsidelegend_img">
  <figcaption class="figure_withsidelegend_figcaption">Une légende du côté droit de l'illustration</figcaption>
</figure>

Pour placer la légende à gauche de l'image, il suffit de déclarer <tagcode>figcaption</tagcode> avant <tagcode>img</tagcode>.

<figure class="figure_withsidelegend">
  <figcaption class="figure_withsidelegend_figcaption">Une légende du côté gauche de l'illustration</figcaption>
  <img src="/assets/placeholders/web_portrait_4.jpg" alt="Deuxieme image" class="figure_withsidelegend_img" title=azazeaze>
</figure>

<p class="p_loremipsum">
Praesent et arcu ac nunc fermentum ultrices. Aliquam eget odio ac tortor imperdiet consequat. Sed purus lorem, semper at auctor id, ullamcorper eu elit. Fusce sed aliquet ante, at tristique arcu. Nulla maximus elementum metus, ac tempor tellus rhoncus in. Sed lacinia accumsan lacinia. In non tortor consequat, placerat felis aliquet, faucibus arcu.</p>

## Picture
La balise <tagcode>picture</tagcode> sert à **sélectionner l'image à charger** en fonction de la taille de l'écran (grâce à une *media query*).

**ATTENTION :** La balise <tagcode>picture</tagcode> ne s'occupe pas de la mise en forme pour l'affichage de cette image. Cela est géré directement par la classe dans la balise <tagcode>img</tagcode> contenu à l'intérieur de <tagcode>picture</tagcode>.

L'utilisation de <tagcode>picture</tagcode> se fait plutôt en fonction de considérations artistiques. Exemple:
- Sur un écran large, on charge une photo paysage "grand angle". On profite de la largeur de l'écran pour montrer ainsi l'environnement.
- Sur un écran smartphone, on charge une photo carrée zoomée sur le sujet. Cela permet de mieux voir le sujet principal de la photo.

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
    srcset="/assets/placeholders/web_landscape_3.jpg"
    type="image/jpg"
    media="all and (min-width:1021px)"
    />
    <!-- default image -->
    <img src="/assets/placeholders/web_large_1000x500.jpg" alt="an image of the site" class="img_1_centered"/>
</picture>

<p class="p_loremipsum">
Vivamus id fringilla odio. In et sapien euismod, rhoncus nulla aliquam, viverra justo. Suspendisse vitae massa sagittis, suscipit odio quis, condimentum risus. Ut diam risus, congue non metus eget, viverra fringilla nulla. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nullam nisi nulla, tincidunt non iaculis ut, porta in purus. Donec in sagittis lacus, et luctus nisi. Aenean eu pretium ante. Donec sed turpis volutpat, dignissim lorem in, congue orci. Proin sed vestibulum erat. Nulla malesuada lorem eget feugiat interdum.</p>

<p class="p_loremipsum">
Nulla rhoncus ac leo facilisis pulvinar. Donec quis velit ultrices, volutpat risus id, commodo enim. Nunc volutpat et tellus at eleifend. Mauris mauris tortor, condimentum vel congue vitae, lacinia aliquam urna. Aenean volutpat a massa ac laoreet. Sed fringilla maximus justo vel dictum. Praesent neque magna, lacinia at dignissim eget, varius vel ligula. Suspendisse tincidunt sit amet magna eu dignissim. Integer ornare posuere quam. Maecenas risus quam, facilisis faucibus aliquam pellentesque, volutpat eget nisi.</p>
