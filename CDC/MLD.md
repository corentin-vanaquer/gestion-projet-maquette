# MLD

Utilisateur ( <u>codeUtilisateur</u>, prénom, nom, email, motDePasse )  
Quiz ( <u>codeQuiz</u>, titre, thème, #codeUtilisateur )  
APPARTIENT ( <u>#codeQuiz</u>, #codeTag )  
Tag ( <u>codeTag</u>, nom )  
Difficulté ( <u>codeDifficulté</u>, nom )  
Question ( <u>codeQuestion</u>, description, anecdote, wiki, #codeRéponse, #codeQuiz, #codeDifficulté )  
Réponse ( <u>codeRéponse</u>, description, #codeQuestion )  