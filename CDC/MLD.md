# MLD

Utilisateur ( codeUtilisateur, prénom, nom, email, motDePasse )  
Quiz ( codeQuiz, titre, thème, #codeUtilisateur )  
APPARTIENT ( #codeQuiz, #codeTag )  
Tag ( codeTag, nom )  
Difficulté ( codeDifficulté, nom )  
Question ( codeQuestion, description, anecdote, wiki, #codeRéponse, #codeQuiz, #codeDifficulté )  
Réponse ( codeRéponse, description, #codeQuestion )  

## Tables de DB

user ( id, first_name, last_name, email, password )  
quiz ( id, title, theme, user_id )  
tag ( id, name )  
difficulty ( id, name )  
question ( id, description, anecdote, wiki, answer_id, quiz_id, difficulty_id )  
answer ( id, description, question_id )  
quiz_has_tag ( id, quiz_id, tag_id )  
