  # Objectif de la Journée 


  ## Debuter la formation 
	     1. Apprendre à utiliser markdown pour formater les rapports 
	     Pour cela j'ai lu la documentation sur (https://github.com/mattcone/markdown-guide/blob/master/cheat-sheet.md)
	     et regarder quelques videos sur youtube   
	     
	     2. Analyser la page d’accueil `Artur.art` en exploitant les elements Html sur devtools 
	     La page est composée de plusieurs éléments html notament les elements html suivants
	     `<html> <head> <title> <body> <div> <noscript> <iframe> <span> <p> <href> <button> <section> <header>
	     <Nav> <svg> <nav> <ul> <li> <img> <footer> <h1> <h6>`
	
	     On a la structure typique
	      <HTML> precise la langue de la page "eng-CA"
	      <Head> contient les métadonnées, les liens vers les feuilles de style css et des lien vers les scripts JavaScript, et <title> le titre de la page 
	      <body>
		contient le contenu de la page : 
		en haut le header contient une barre de navigation <nav> qui contient à son tour les menus 
		chaque menus contient des liens vers d'autres pages et en haut à gauche le logo de la page contenu dans une balise <img>.
		les thématiques de la page sont regroupées dans des section <section> construites avec Elementor,
	        les images sont contenues dans des elements <img>
	        en bas de la page toujours dans le body l'element <footer> qui contient les elements de bas de page comme la localisation, les informations sur 
                artur ainsi que d'autres infos
		`La page ne s'adapte pas avec toutes les tailles de navigateur
		sur Edge dès qu'on réduit la taille de la page la section en haut disparait et la taille de video ne s'ajuste pas à la taille de video holder qui 
                est presente sous forme de telephone mobile comme illustré dans le screen shot en dessous.`
  

	   ![alt text](https://github.com/user-saoussen/markdown/blob/main/Capture%20d%E2%80%99%C3%A9cran%202024-10-09%20221928.png)

               quand on reduit la taille de la page L'apparence de menus est mal organisée, on voit des copies de la page d'accueils ainsi que l'ancien page d'accueil et il s'affiche en francais alors qu'il était en anglais

	
![alt text](https://github.com/user-saoussen/markdown/blob/main/Capture%20d%E2%80%99%C3%A9cran%202024-10-09%20225040.png)
              
sur google chrome le meme probleme de menu se presente, la vido s'ajuste bien à la taille de son holder 

par rapport à la taille des écrans:
Pour une tablette 768*525 on tombe directement sur la caroussel donc la partie du haut ne s'affiche pas est le menu n'est pas bien organisé
https://github.com/user-saoussen/markdown/blob/0d59dd4b105ec92708f623209cfb789a5a157fb2/Capture%20d%E2%80%99%C3%A9cran%202024-10-09%20235405.png
Pour un mobile 425*525 , 375*525 et 320*525 l'affichage est correcte

pour un ordinateur portable 1024*525 on tombe directement sur la caroussel donc la partie du haut ne s'affiche pas est le menu n'est pas bien organisé

