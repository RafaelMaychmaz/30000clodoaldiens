---
layout: rm_post
title: Ceci est une page de test Markdown
subtitle: "Quelques vidéos durant le 1er confinement pour remercier les commerçants de rester ouvert. Merci et Bravo à eux !"
header-img: assets/images/2020_merci-a-nos-commercants/merci-a-nos-comercants-banner.png
---

# {{ page.title }}

**Suspendisse vitae massa sagittis, suscipit odio quis, condimentum risus. Ut diam risus, congue non metus eget, viverra fringilla nulla. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nullam nisi nulla, tincidunt non iac**

## Titre 1
Suspendisse vitae massa sagittis, suscipit odio quis, condimentum risus. Ut diam risus, congue non metus eget, viverra fringilla nulla. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nullam nisi nulla, tincidunt non iaculis ut, porta in purus. Donec in sagittis lacus, et luctus nisi. Aenean eu pretium ante. Donec sed turpis volutpat, dignissim lorem in, congue orci. Proin sed vestibulum erat. Nulla malesuada lorem eget feugiat interdum. 

### Titre 2
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris in vestibulum turpis. Nullam quis odio nec erat finibus rutrum. Phasellus at pretium diam. Quisque volutpat, urna in ultrices gravida, arcu mi luctus ligula, et volutpat nunc sem at nulla. Vivamus sit amet eros arcu. Donec luctus pellentesque tellus, porta efficitur magna tempor in. Maecenas eleifend eget libero eget cursus. Mauris vitae ultrices ligula. Fusce placerat rutrum sem ac interdum. Curabitur egestas ante vitae diam vestibulum, eu finibus nisl luctus. Cras sem magna, imperdiet vel ligula quis, semper sagittis elit. Pellentesque ullamcorper metus ac tortor accumsan tincidunt.

#### Titre 3
Sed in magna non sem laoreet hendrerit sed a urna. Sed pretium id leo sit amet commodo. Proin luctus lacus mollis, pharetra dui et, rutrum nunc. Aenean nec metus dui. Praesent ac lorem sed ante rhoncus auctor quis et velit. Donec porta, felis eu porttitor consectetur, massa est maximus nisl, id pharetra ipsum eros non metus. Nulla aliquet consectetur tellus sit amet bibendum. Nullam sed sodales massa. Nullam rutrum, massa non posuere gravida, mauris nisl ultricies nisi, non dictum ex arcu sed erat. Aliquam volutpat libero at vulputate pulvinar. Fusce vel bibendum nunc, ut aliquet purus. Vivamus convallis pulvinar justo a auctor.

## IMAGES CENTRÉES
### Carré
Lorsque l'on écrit le code en Markdown, une balise **P** est ajoutée autour de la balige **IMG**. Si **P** possède dans son style une marge (ex: 10px) alors cela complique la tache pour obtenir une image sans marge. En effet, en tant qu'*inline element* (en terme de display), l'image est alors contenue dans un *block element* **P** qui lui impose sa propre marge (sauf si on applique une *position: 'absolute'*, mais cela pose d'autres soucis).

La solution la plus simple consiste à appliquer un style à la balise **P** contenant l'image. Pour ce faire, on utilise un **kramdown block attribute** afin d'indiquer la classe du **P** (que l'on stylise en CSS ensuite pour enlever la marge dans ce cas spécifique.).

![texte alternatif à l'image](/assets/placeholders/web_square_1500x1500.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

<p style="color:lightgray;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros. </p>

### Portrait

<p style="color:lightgray;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros. </p>

![texte alternatif à l'image](/assets/placeholders/web_portrait_1.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

<p style="color:lightgray;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros. </p>

![texte alternatif à l'image](/assets/placeholders/web_portrait_2.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

<p style="color:lightgray;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros. </p>

![texte alternatif à l'image](/assets/placeholders/web_portrait_3.jpg "Description de l info-bulle image"){:class="img_1_centered"}
{: .pContainerOfImage}

<p style="color:lightgray;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. In aliquet porta ante, ac maximus lectus vestibulum ac. Mauris vel nisi aliquam, blandit purus sed, blandit libero. Mauris vitae lacus condimentum, varius nulla eget, pellentesque leo. Phasellus id nulla malesuada, dignissim ante at, fringilla tortor. Quisque facilisis mauris quis arcu ullamcorper laoreet. Pellentesque in dolor in elit aliquam interdum et eu turpis. Mauris facilisis purus accumsan, interdum erat vel, consequat libero. Nulla lobortis ullamcorper purus. Donec congue, orci eget rhoncus pharetra, sem dolor eleifend urna, sit amet varius urna odio eget eros. </p>

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

### Portrait

#### A droite

<div class="clearfix">
<img class="img_1_portait_floatright" src="/assets/placeholders/web_portrait_1.jpg" alt="Image flottante à droite de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatright" src="/assets/placeholders/web_portrait_2.jpg" alt="Image flottante à droite de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatright" src="/assets/placeholders/web_portrait_3.jpg" alt="Image flottante à droite de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatright" src="/assets/placeholders/web_portrait_4.jpg" alt="Image flottante à droite de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

#### A gauche

<div class="clearfix">
<img class="img_1_portait_floatleft" src="/assets/placeholders/web_portrait_1.jpg" alt="Image flottante à gauche de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatleft" src="/assets/placeholders/web_portrait_2.jpg" alt="Image flottante à gauche de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatleft" src="/assets/placeholders/web_portrait_3.jpg" alt="Image flottante à gauche de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_portait_floatleft" src="/assets/placeholders/web_portrait_4.jpg" alt="Image flottante à gauche de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

### Landscape

#### A droite

<div class="clearfix">
<img class="img_1_landscape_floatright" src="/assets/placeholders/web_landscape_1.jpg" alt="Image flottante à droite de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_landscape_floatright" src="/assets/placeholders/web_landscape_2.jpg" alt="Image flottante à droite de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_landscape_floatright" src="/assets/placeholders/web_landscape_3.jpg" alt="Image flottante à droite de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

#### A gauche

<div class="clearfix">
<img class="img_1_landscape_floatleft" src="/assets/placeholders/web_landscape_1.jpg" alt="Image flottante à gauche de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_landscape_floatleft" src="/assets/placeholders/web_landscape_2.jpg" alt="Image flottante à gauche de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

<div class="clearfix">
<img class="img_1_landscape_floatleft" src="/assets/placeholders/web_landscape_3.jpg" alt="Image flottante à gauche de 50%">
<p style="color:lightgray;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel orci pulvinar, iaculis purus non, vehicula quam. Suspendisse suscipit vulputate accumsan. Etiam ac turpis iaculis, faucibus magna sodales, malesuada metus. Vestibulum auctor libero orci, a vulputate quam consequat sit amet. Mauris pretium, eros et finibus faucibus, tellus mi imperdiet arcu, non iaculis lacus arcu at magna. Curabitur sed purus lobortis, interdum mi feugiat, semper dolor. In mi massa, tempus vel cursus a, varius at quam. Suspendisse a mauris at ex semper fermentum ut eget ex. Cras id odio egestas, efficitur leo eu, tincidunt dui. Pellentesque ut sapien feugiat, lacinia est efficitur, egestas erat. Suspendisse vestibulum lectus nec fringilla porttitor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Aenean maximus, lectus at interdum congue, libero nunc auctor tortor, at facilisis nunc quam et lacus.</p>
<p style="color:lightgray;">
Nulla facilisi. Maecenas ligula leo, accumsan non ipsum ac, fringilla euismod orci. Morbi luctus purus eget leo ultrices, non ultricies justo venenatis. Donec a urna sit amet justo fermentum condimentum eget sed tortor. Vestibulum ipsum risus, pulvinar et ex eget, tristique placerat nulla. Integer porttitor lobortis posuere. Morbi lobortis mattis tortor. Aenean auctor sit amet leo gravida pellentesque. Donec tortor lacus, dictum eu purus eu, laoreet bibendum enim.</p>
<p style="color:lightgray;">
Vivamus ut rhoncus sapien, et consectetur mi. Integer at dignissim sapien. Proin viverra leo sit amet urna varius condimentum. Curabitur dignissim accumsan pulvinar. Sed accumsan a nisi in porta. Proin tincidunt massa mi. Curabitur accumsan, nunc mollis venenatis tempor, neque lorem sollicitudin sapien, vel fringilla libero felis ac dui. Etiam et vestibulum odio.</p>
</div>

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

