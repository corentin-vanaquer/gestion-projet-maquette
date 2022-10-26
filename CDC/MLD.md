# MLD

Utilisateur ( <u>codeUtilisateur</u>, prénom, nom, email, motDePasse )  
Quiz ( <u>codeQuiz</u>, titre, thème, <u>#codeUtilisateur</u> )  
APPARTIENT ( <u>#codeQuiz</u>, <u>#codeTag</u> )  
Tag ( <u>codeTag</u>, nom )  
Difficulté ( <u>codeDifficulté</u>, nom )  
Question ( <u>codeQuestion</u>, description, anecdote, wiki, <u>#codeRéponse</u>, <u>#codeQuiz</u>, <u>#codeDifficulté</u> )  
Réponse ( <u>codeRéponse</u>, description, <u>#codeQuestion</u> )  

## Tables de DB

user ( id, first_name, last_name, email, password )  
quiz ( id, title, theme, user_id )  
tag ( id, name )  
difficulty ( id, name )  
question ( id, description, anecdote, wiki, answer_id, quiz_id, difficulty_id )  
answer ( id, description, question_id )  
quiz_has_tag ( id, quiz_id, tag_id )  
