Exercíio proposto na aula de javascript da Alpha EdTech sobre "Controle de tempo e áudio"

Descrição da atividade:

Exercício anterior
"Crie uma página web que arme uma bomba (imagem de uma bomba) que “exploda” em 10 segundos, considerando os seguintes critérios:

Utilize o setTimeout para ‘armar a bomba’ (bomba com pavio aceso).
Caso o usuário clique na bomba, utilize o clearTimeout para desarmar a bomba (bomba com pavio apagado).
Caso a bomba não seja desarmada, ao terminar o tempo, deverá explodir, e um som de explosão deve ser executado."

Exercício atual:

Refaça o exercício anterior, aumentando o delay do setTimeout para 60 segundos e adicionando um setInterval que mostre os segundos decrementados de 1 em 1 até a explosão, caso não seja desarmada, considerando que:

A cada “tick” de tempo decrescente, adicione um som de ‘tick’ curto para demonstrar que o tempo está acabando.
Se o usuário clicar na bomba, utilize o clearInterval para desarmar a bomba.
Se o usuário não clicar na bomba, esta deverá explodir (som de explosão) e a contagem do tempo deve parar.
