# Introduction

[Webpack](https://webpack.js.org/) simplifie le développement web en résolvant un problème fondamental: l'empaquetage du code (*bundling*)
Webpack prend en entrée des ressources Javascript, CSS et HTML ... et les transforment dans un format qui est facile à consommer pour un navigateur web. Réalisé efficacement, ce processus nous facilite beaucoup les choses dans le développement web.

Etant orienté configuration, Webpack n'est pas l'outil le plus facile à apprendre, mais il est incroyablement puissant. Le but de se livre est vous permettre de démarrer avec webpack, et de le maitriser.

## Qu'est-ce que Webpack ?

Les navigateurs web sont conçus pour interpréter de l'HTML, du CSS et du Javascript. Plus un projet grossis et évolue, plus le suivi et la configuration de tout ces fichiers deviens pénible à gérer à la main.
Webpack a été conçu pour répondre à ces problématiques. La gestion de la complexité des ressources web est un des problèmes les plus important du développement web. Résoudre ce problème avec élégance, nous aide donc beaucoup.

Webpack n'est pas le seul empaqueteur de code (*bundler*) disponible, en fait un certain nombre d'outils ont émergé. Des orchestrateurs de tâches (*task runner*), comme Grunt and gulp sont un exemple d'outils de haut niveau. Souvent le problème est que vous devez écrire les workflows à la main. Déléguer cette responsabilité à un **bundler** est déjà un pas en avant.

{pagebreak}

### How Webpack Changes The Situation

Webpack adopte une nouvelle approche. Il vous permet de voir votre project comme un graphe de dépendances. Vous pourriez par exemple disposer d'un fichier `index.js` qui référencerait les dépendances du projet au travers des directive standard telles que `require` et `import`. Vous pouvez également faire référence aux feuilles de styles et autres ressources de l'applications de la même manière. 

Webpack s'occupe du traitement de ce graphe pour vous en produisant des fichiers de sorties que vous spécifierez dans la configuration. Cette approche déclarative est très polyvalent mais complique l'apprentissage.

Une fois que vous commencez à comprendre comment il marche, webpack est un outil indispensable. Ce livre a été conçu pour vous accompagner dans la courbe d'apprentissage initial et bien au delà.

## Ce que vous apprendrez

Ce livre se positionne comme [un complément de la documentation officielle de webpack](https://webpack.js.org/) et vous mènera à la maitrise de l'outil.

Entre autres sujets abordés, vous apprendrez à concevoir une configuration modulaire qui répondra à vos besoins de développement et de mise en production. Les techniques avancées décrites dans ce livre vous permettront de tirer le maximum de la version 4 de webpack.

{pagebreak}

## Comment ce livre est organisé

Cet ouvrage commence par vous expliquer ce qu'est webpack. Ensuite, vous appréhenderez webpack sous divers angles de vues. Vous apprendrez à concevoir votre propre configuration  de webpack en utilisant les techniques de base qui vous seront démontrés au fur et à mesure.



The book has been split into the following parts:

Ce livre est composé des parties suivantes:

* **Developing** gets you up and running with webpack. This part goes through features such as automatic browser refresh and explains how to compose your configuration so that it remains maintainable.
* **Environnement de développement** vous permettra de démarrer avec webpack. Cette section parcours des fonctionnalite telle que le rafraîchissement automatique du navigateur et explique comment construire votre configuration afin d'assurer sa maintenabilité.

* **Styling** puts heavy emphasis on styling related topics. You will learn how to load styles with webpack and how to introduce techniques such as autoprefixing into your setup.
* **Styles** explore les sujets liés aux styling de votre application. Vous apprendrez à charger des feuilles de styles avec webpack, tout en incluant des techiques utiles comme la génération automatique de prefixes.

**Importation de ressources** entre en profondeur dans la configuration de **loader** webpack, ce qui vous permettra d'importer des images, des polices, du javscript...
* **Loading** explains webpack’s loader definitions in detail and shows you how to load assets such as images, fonts, and JavaScript.
* 
* **Chargement des ressources**
* **Building** introduces source maps and the ideas of bundle and code splitting. You will learn to tidy up your build.
* **Empaquetage de code**
* **Optimizing** pushes your build to production quality level and introduces many smaller tweaks to make it smaller. You will learn to tune webpack for performance.
* **Optimisation**
* **Output** discusses webpack’s output related techniques. Despite its name, it’s not only for the web. You see how to manage multiple page setups with webpack and pick up the basic idea of Server Side Rendering.
* **Fichiers de sortie**
* **Techniques** discusses several specific ideas including dynamic loading, web workers, internationalization, deploying your applications, and consuming npm packages through webpack.
* **Astuces**
* **Extending** shows how to extend webpack with loaders and plugins.
* **Personnalisation**

---

Finally, there is a short conclusion chapter that recaps the main points of the book. It contains checklists of techniques from this book that allow you to methodically go through your projects.

---


The appendices at the end of the book cover secondary topics and sometimes dig deeper into the main ones. You can approach them in any order you want depending on your interest.

---

The *Troubleshooting* appendix at the end covers what to do when webpack gives you an error. It covers a process, so you know what to do and how to debug the problem. When in doubt, study the appendix. If you are unsure of a term and its meaning, see the *Glossary* at the end of the book.

## Who Is The Book For

You should have basic knowledge of JavaScript, Node, and npm. If you know something about webpack, that’s great. By reading this book, you deepen your understanding of these tools.

---

If you don’t know much about the topic, consider going carefully through the early parts. You can scan the rest to pick the bits you find worthwhile. If you know webpack already, skim and choose the techniques you find valuable.

---

In case you know webpack well already, there is still something in the book for you. Skim through it and see if you can pick up new techniques. Especially read the summaries at the end of the chapters and the concluding chapter of the book.

## Book Versioning

Given this book receives a fair amount of maintenance and improvements due to the pace of innovation, there's a versioning scheme in place. Release notes for each new version are maintained at [the book blog](https://survivejs.com/blog/). You can also use GitHub *compare* tool for this purpose. Example:

```
https://github.com/survivejs/webpack-book/compare/v2.1.7...v2.4.0
```

The page shows you the individual commits that went to the project between the given version range. You can also see the lines that have changed in the book.

---

The current version of the book is **2.4.0**.

## Getting Support

If you run into trouble or have questions related to the content, there are several options:

---

* Contact me through [GitHub Issue Tracker](https://github.com/survivejs/webpack-book/issues).
* Join me at [Gitter Chat](https://gitter.im/survivejs/webpack).
* Send me an email at [info@survivejs.com](mailto:info@survivejs.com).
* Ask me anything about webpack at [SurviveJS AmA](https://github.com/survivejs/ama/issues).

If you post questions to Stack Overflow, tag them using **survivejs**. You can use the hashtag **#survivejs** on Twitter for the same result.

## Additional Material

You can find more related material from the following sources:

* Join the [mailing list](https://eepurl.com/bth1v5) for occasional updates.
* Follow [@survivejs](https://twitter.com/survivejs) on Twitter.
* Subscribe to the [blog RSS](https://survivejs.com/atom.xml) to get access interviews and more.
* Subscribe to the [Youtube channel](https://www.youtube.com/channel/UCvUR-BJcbrhmRQZEEr4_bnw).
* Check out [SurviveJS related presentation slides](https://presentations.survivejs.com/).

## Acknowledgments

Big thanks to [Christian Alfoni](http://www.christianalfoni.com/) for helping me craft the first version of this book. This is what inspired the entire SurviveJS effort. The version you see now is a complete rewrite.

This book wouldn’t be half as good as it's without patient editing and feedback by my editors [Jesús Rodríguez](https://github.com/Foxandxss), [Artem Sapegin](https://github.com/sapegin), and [Pedr Browne](https://github.com/Undistraction). Thank you.

This book wouldn’t have been possible without the original "SurviveJS - Webpack and React" effort. Anyone who contributed to it deserves my thanks. You can check that book for more accurate attributions.

Thanks to Mike "Pomax" Kamermans, Cesar Andreu, Dan Palmer, Viktor Jančík, Tom Byrer, Christian Hettlage, David A. Lee, Alexandar Castaneda, Marcel Olszewski, Steve Schwartz, Chris Sanders, Charles Ju, Aditya Bhardwaj, Rasheed Bustamam, José Menor, Ben Gale, Jake Goulding, Andrew Ferk, gabo, Giang Nguyen, @Coaxial, @khronic, Henrik Raitasola, Gavin Orland, David Riccitelli, Stephen Wright, Majky Bašista, Gunnari Auvinen, Jón Levy, Alexander Zaytsev, Richard Muller, Ava Mallory (Fiverr), Sun Zheng’an, Nancy (Fiverr), Aluan Haddad, Steve Mao, Craig McKenna, Tobias Koppers, Stefan Frede, Vladimir Grenaderov, Scott Thompson, Rafael De Leon, Gil Forcada Codinachs, Jason Aller, @pikeshawn, Stephan Klinger, Daniel Carral, Nick Yianilos, Stephen Bolton, Felipe Reis, Rodolfo Rodriguez, Vicky Koblinski, Pyotr Ermishkin, Ken Gregory, Dmitry Kaminski, John Darryl Pelingo, Brian Cui, @st-sloth, Nathan Klatt, Muhamadamin Ibragimov, Kema Akpala, Roberto Fuentes, Eric Johnson, and many others who have contributed direct feedback for this book!
