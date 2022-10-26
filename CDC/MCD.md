# MCD


## MCD MOCODO

Utilisateur: codeUtilisateur, prénom, nom, email, motDePasse  
CREE, 0N Utilisateur, 11 Quiz  
Quiz: codeQuiz, titre, thème  
APPARTIENT, 0N Quiz, 0N Tag  
Tag: codeTag, nom  

:
COMPOSE, 11 Question, 0N Quiz

Difficulté: codeDifficulté, nom  
DEFINI, 0N Difficulté, 11 Question  
Question: codeQuestion, description, anecdote, wiki  
POSSEDE, 0N Question, 11 Réponse  
Réponse: codeRéponse, description  

:  
:  
:  
VALIDE, 01 Réponse, 11 Question


![MCD-image](./img/mcd-oquiz-img.png)


Lien mocodo: http://mocodo.wingi.net/