# chess 3D

<p align="left"> <a href="https://developer.mozilla.org/en-US/docs/Web/blender" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=blender" alt="blender" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/cplusplus" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=cpp" alt="cplusplus" width="40" height="40"/> </a></p>

⭐ **DESCRIPTION :** Jeu d’échec en 3D avec interface 2D et rendu en temps réel.

⭐ **CONTEXTE :** Jeu développé lors de ma deuxième année à l’IMAC dans le cadre d’un projet qui fusionne les cours de C++ avancé et de Synthèse d’Image.

⭐ **OBJECTIF :** L’objectif de ce projet était de réaliser un jeu d’échec en 3D avec une interface en 2D qui interagit directement avec le plateau 3D en temps réel. L’interface 2D devait être implémentée avec ImGui, une bibliothèque permettant de créer des interfaces utilisateurs. Le plateau 3D, quant à lui devait être développé en openGL.

⭐ **CE QUE J'AI DÉVELOPPÉ :**
- interface 2D sous la forme d’un plateau de jeu d’échec interactif
- plateau 3D qui s’actualise en temps réel et se synchronise avec l’interface 2D
- modélisation 3D des pièces et du plateau sur Blender
- implémentation des règles et des contraintes de chaque pion

⭐ **DÉFI TECHNIQUE :** La principale problématique a été de garder l'interface ImGui et le rendu OpenGL synchronisés à chaque coup : un déplacement validé sur l’interface 2D devait immédiatement se répercuter sur la position des pièces en 3D, sans décalage ni état incohérent. Pour ça, j'ai centralisé l'état du plateau dans une seule structure de données : un tableau de pointeurs, lu à la fois par l'interface et par le moteur de rendu.
