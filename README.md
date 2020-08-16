<h1 id="google-spreasheet"><strong>Google Spreasheet</strong></h1>



<h2 id="pré-requis">Pré-requis</h2>

<p>Avant de lancer le programme sur le terminal , il faut tout d’abord installer les <em>gems</em> ci dessous :</p>

<blockquote>
  <p>gem  ‘rubocop’ <br>
  gem  ‘nokogiri’  <br>
  gem  ‘google_drive’ <br>
  gem  ‘json’ <br>
  gem  ‘csv’ <br>
  gem  ‘rubysl-open-uri’</p>
</blockquote>

<p>Ensuite, on les mets à jour grâce à la commande :</p>

<blockquote>
  <p>~$ bundle install</p>
</blockquote>



<h2 id="instruction">Instruction</h2>

<p>Ce projet consiste à enregistrer des emails via un site  dans un fichier JSON , CSV et dans le spreadsheet de Google. </p>

<p>Si l’utilisateur souhaite enregistrer les emails scrappées dans un fichier spreadsheet Voici le lien du fichier  <a href="https://docs.google.com/spreadsheets/d/152kqnXBMHvuWKCSiTd_G_tly13wFB0aFuU-LZPD09BQ/edit#gid=0">Google</a></p>

<h2 id="usage">Usage</h2>

<p>Pour pouvoir lancer correctement le programme sur le terminal , il faut que nous nous mettions tout d’abord dans le dossier ou il y a l’extension <em>.rb </em>. Prenons l’exemple ci dessous :</p>

<blockquote>
  <p>~/Google_Spreadsheet/JSON_scrapper/lib$ </p>
</blockquote>

<p>et ensuite tape  la commande  suivant</p>

<blockquote>
  <p>*$ruby scrapper.rb</p>
</blockquote>

<h2 id="warning">Warning</h2>

<p>L’enregistrement des emails dans chaque fichier pourrait être interrompu si votre connexion est lent pour cela j’ai limité le nombre  des emails scrapées afin de ne pas trop abimer la connexion.</p>

<h2 id="author">Author</h2>

<p>Zo Lalaina ismael Rajaoharimanana <br>
<a href="https://github.com/Ismael148">https://github.com/Ismael148</a></p>