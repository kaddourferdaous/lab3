# lab3
<h1>Part1 Classification Task:
1. By using scrapping libraries (Scrapy / BeautifulSoup), try to collect text data from several
Arabic web site concerning one topic then prepare your Dataset as Below:
<p>j'ai développé un script Python utilisant BeautifulSoup pour scraper des données textuelles pertinentes depuis des sites arabes, en ciblant un sujet spécifique comme "politique". Ces données ont été structurées dans un fichier CSV</p>
<h1>2. Establish a preprocessing NLP pipeline (tokenization stemming lemmatization, Stop words,
Discretization, etc) of the collected Dataset.</h1>
<p>La pipeline de prétraitement NLP inclut la tokenisation pour diviser le texte en tokens, suivie de la suppression des stop words pour éliminer les mots inutiles. Ensuite, le texte passe par des étapes de stemming ou lemmatisation pour réduire les mots à leur racine ou forme de base, et, si nécessaire, des techniques comme la discrétisation</p>
<h1>3. Train your models by using RNN, Bidirectional RNN GRU and LSTM Architectures and
tuning hyper-parameters to get the best performance.</h1>
<p>J'ai préparé mes données en tokenisant les textes, puis en les convertissant en séquences d'indices avec un tokenizer et en appliquant du padding pour uniformiser la longueur des séquences.
J'ai créé un modèle RNN en ajoutant une couche SimpleRNN, une couche d'Embedding, et une couche dense pour la classification binaire.
J'ai implémenté un modèle Bidirectional RNN en encapsulant une couche SimpleRNN avec Bidirectional pour traiter les séquences dans les deux directions.
J'ai construit des modèles GRU et LSTM en remplaçant la couche récurrente SimpleRNN par GRU ou LSTM, respectivement, pour mieux gérer les séquences longues et améliorer la performance du modèle.</p>
