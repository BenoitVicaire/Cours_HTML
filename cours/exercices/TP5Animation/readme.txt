chatgpt:
Prompt : 
"J'ai un icon en svg, par defaut il est bleu, j'ai moyen de lui faire changer de couleur "facilement" avec du html css? comme avec du texte simple?"
addition 1 : 
"explique moi le contenu de ton code html: 
tout le <svg>"
addition 2 :
j'ai pas compris le d=""
C'est ca qui definis la forme de mon icon?
Moi j'ai un icon au format svg, je peux pas l'importer directement?"

Commentaire : avec ca j'ai compris comment me servir des icon au format SVG et changer leur couleurs (et d'autre chose je suppose, mais la c'était la couleur que je voulais)

Deuxieme prompt : 
Je veux faire une animation a base d'un radial gradient, j'ai choper ce bout de code :
background: #B8005C;
background: radial-gradient(circle,rgba(184, 0, 92, 1) 0%, rgba(0, 8, 163, 1) 50%, rgba(0, 2, 41, 1) 100%);
Donc je j'ai mis dans une animation de la sorte : 
@keyframes hoverbouton {
    0% {background: #B8005C;}
    0% {background-image:radial-gradient:(circle,rgba(184, 0, 92, 1) 0%, rgba(0, 8, 163, 1) 50%, rgba(0, 2, 41, 1) 100%);}
    100% {background-color: #0008A3;}
    100% {color: #D72D1D;}
    /* 100% {border:#D72D1D solid 3px;} */
    100% {translate: -3px -3px;}
Mais ca marche pas, et j'ai plein de message d'erreur sur vscode

Commentaire : sa réponse ma permis de regler et comprendre les problèmes que j'avais, l'erreur de syntaxe de mon radial-gradient:, et l'usage multiple de % qui s'overwrite. Il n'y a pas eu besoin de plus de prompt pour fixer mon bout de code.

PS: aucun copier coller depuis chatgpt, je m'en sers pour m'expliquer ce que je ne comprend pas, mais jamais pour faire à ma place.

