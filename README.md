Etapas realizadas na atividade:

1- Leia o arquivo ‘videos-stats.csv'  no dataframe 'df_video' com cabeçalho e inferindo o esquema 
2- Altere os valores nulos dos campos 'Likes', 'Comments' e 'Views' para o valor 0
3- Leia o arquivo ‘comments.csv' no dataframe 'df_comentario' com cabeçalho e inferindo o esquema
4- Calcule a quantidade de registros do df_video e df_comentario
5- Remova os registros do df_video e df_comentario quem possuem o campo 'Video ID' nulos e calcule novamente a quantidade de registros
6- Remova os registros apenas do df_video quem possuem o campo 'Video ID' duplicados
7- Converta os campos Likes, Comments e Views para 'int' no dataframe df_video
8- Converta os campos Likes e Sentiment para 'int' no dataframe df_comentario, além disso, altere o nome do campo Likes para 'Likes Comment'
9- Crie o campo 'Interaction' no dataframe df_video, com a soma dos campos Likes, Comments e Views 
10- Converta os campos 'Published At' para 'date' no dataframe df_video
11- Crie o campo 'Year' no dataframe df_video, extraindo apenas o ano do campo 'Published At'
12- Mescle os dados df_comentario no dataframe df_video em relação ao campo Video ID e crie o dataframe df_join_video_comments
13- Leia o arquivo ‘USvideos.csv' no dataframe 'df_us_videos' com cabeçalho e inferindo o esquema
14- Mescle os dados df_us_videos no dataframe df_video em relação ao campo Title e crie e visualize o dataframe df_join_video_usvideos
15- Verifique a quantidade de campos nulos em todos os campos do dataframe df_video
16- Remova a coluna '_c0' e salve o dataframe df_video como 'videos-tratados-parquet' no formato parquet e adicione o cabeçalho nos dados
17- Remova a coluna '_c0' e salve o dataframe df_join_video_comments como 'videos-comments-tratados-parquet' no formato parquet e adicione o cabeçalho nos dados
18- Faça o download e envie o arquivo “tratamento.ipynb”  com todas as etapas concluídas para o seu tutor.
