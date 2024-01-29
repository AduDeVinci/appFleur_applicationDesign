# Application Design - Project 1

Reproduction du design des Fleurs sur figma
![Vue sur Emulateur](https://github.com/AduDeVinci/appFleur_applicationDesign/assets/144226487/a110805f-048d-4592-9bb1-a83b2d5950a9)


# Technologies utilisées  
Android - Kotlin et XML


# Difficultées rencontrées et résolutions  
J'ai rencontré des problèmes notamment avec l'émulateur qui mettait énormément de temps à se lancer et encore plus à se mettre à jour. Je travaillais donc principalement avec l'onglet design qui apparait quand on split le code. Lorsque j'ai fini par lancé l'émulateur, certaines images ne s'affichaient pas. J'ai dû changé 
```
app:srcCompat="@drawable/image"
```
to
```
android:src="@drawable/image"
```
Au final, le design est fidèle à ce qui était demandé, bien qu'il n'y ait pas d'intéractivité. 

Une autre difficulté a été au sujet de l'ombre. Celui-ci a cependant été résolu. L'élévation a marché parfaitement pour les cards avec les plantes, un peu moins bien pour le bouton compris dans le linear layout parent. Aussi, j'ai créé une une forme (le bouton) avec un effet ombre qui n'est qu'une deuxième forme en-dessous.

Enfin, une dernière difficulté concernait le fait que les plantes dépassent des cartes sous la ligne d'onglet. Cela a été résolu en les enveloppants dans un layout extérieur à la carte et groupant le tout.


# Bonus  
Je n'ai pas fait d'élément bonus, j'ai simplement commencé à reproduire le même design avec  JetPack Compose pour découvrir les deux technologies

