---
title: "The Fidelity Loop : Expérience immersive en VR"
description: "Expérience WebVR immersive croisant l'univers angoissant de la série Severance avec l'identité acoustique de Bang & Olufsen."
pubDate: "2026-01-31"
heroImage: "/portfolio/images_projets/severance/fidelity_loop_hero.jpg"
tags: ["Design & UI", "Développement Web", "Audiovisuel & 3D"]
---

## Le Projet
**The Fidelity Loop** est une expérience en réalité virtuelle conçue pour répondre à une problématique singulière : comment traduire la "pureté sonore" et l'immatériel d'une marque audio haut de gamme comme Bang & Olufsen à travers une interface numérique ? 

La réponse prend la forme d'une immersion narrative s'appropriant l'esthétique clinique et les codes de la série *Severance*. L'utilisateur est plongé dans un environnement corporatif aseptisé où le son devient le seul repère, mêlant le design scandinave luxueux à une atmosphère volontairement dérangeante.

## Le Concept
L'expérience repose sur le concept de **"mise en abyme"**. L'univers entier est présenté comme une simulation générée par la technologie B&O pour tester les sens de l'utilisateur.

* **Le Puzzle Audio :** Le joueur interagit avec une console B&O pour reconnecter physiquement des câbles. Chaque connexion réactive une "piste" sonore (basse, mélodie, percussions) afin de reconstruire un mixage parfait en temps réel.
* **Dissociation et Malaise :** L'ambiance joue sur l'absurde, la confusion et la curiosité anxiogène. Le parcours traverse des espaces liminaux oppressants (le bureau clinique "Innie", l'ascenseur de transition, les "Backrooms" sombres).
* **La Boucle Infinie :** La fin de l'expérience déclenche un violent glitch visuel qui ramène le joueur au début du jeu avec de subtils changements sonores, renforçant le thème de l'enfermement infini.

## Réalisation Technique
Le projet a été développé pour être accessible directement sur navigateur via **WebXR** (framework A-Frame), garantissant une accessibilité maximale tout en étant optimisé pour les casques autonomes (Meta Quest).

* **Environnement 3D :** Modélisation sur-mesure (Blender) des espaces et du mobilier dans un style "Low Poly" épuré et minimaliste, pensé pour respecter les strictes contraintes de performance du web.
* **Sound Design Spatialisé :** L'expérience auditive est au cœur du gameplay. Tous les sons (musiques multicanales, voix, ambiances horrifiques) sont traités en audio 3D et justifiés de manière diégétique par les enceintes B&O intégrées au décor.
* **Interactivité :** Développement de composants JavaScript personnalisés pour la gestion de la physique des câbles, la détection de proximité (Hand Tracking), et la chorégraphie mathématique des événements narratifs.

## Aperçu et Liens
L'expérience est jouable directement dans votre navigateur (au clavier et à la souris sur PC) ou avec un casque de réalité virtuelle compatible WebXR.

🔗 **[Tester l'expérience : The Fidelity Loop](https://kelian83.github.io/cube-project/)**

![Image 1](/portfolio/images_projets/severance/capture1.png)
![Image 2](/portfolio/images_projets/severance/capture2.png)