# Snippets - VSCode


##  Documentation

Lien : [***Clique ici***](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

## Information 

 - **Productivité améliorée :**
	 - Les snippets boostent la productivité en automatisant la création de code répétitif, éliminant la saisie manuelle répétée.
 - **Apprentissage facilité :**
   - Les snippets simplifient l'apprentissage en fournissant des exemples et des modèles de code.
 - **Personnalisation :**
   - Les développeurs peuvent créer leurs propres snippets personnalisés pour s'adapter à leurs besoins et préférences.

## Explication 

### Création d'un Snippet 
	

Pour créer une nouveau snippet voici les instructions : 

- Ouvrir VSCODE
- Ctrl + Shift + P
- Snippets: Configure User Snippets
-  New Global Snippets file...
- Insérer un nom pour nomer le fichier sur votre PC

Ensuite un fichier va s'ouvrir , sa devrais resembler a ça :
![Fichier Snippet](https://ibb.co/Y37QW5N)

###  Structure d'un Snippet

```json
"Nom_du_Snippet": { 
	"scope": "type de fichier", 
	"prefix": "préfixe_du_snippet", // OU ["préfixe1", "préfixe2"]
	"body": [ "Code de l'extrait de code ici..." ],
	"description": "Description de l'extrait de code" 
}
 ```

-   `"Nom_du_Snippet"` : Le nom unique de l'extrait de code.
-   `"scope"` : Le type du fichier vous pouvez en indiquez plusieus avec une " , " comme  	 	séparateur. (Si vous voulez mettre tous type de fichier laisser le champs vide)
-   `"prefix"` : Le préfixe qui déclenchera l'extrait lorsque vous commencerez à taper dans VSCode.
-   `"body"` : Le code réel de l'extrait.
-   `"description"` : Une brève description de l'extrait de code.
 
 ### Pour accédez au dossier local de vos snippets

Vous pouvez utilisez le terminal pour vous rendre dans votre dossier snippets.

Windows : 
- ```C:\Users\VotreNomUtilisateur\AppData\Roaming\Code\User\snippets```

Mac : 
 - ``` ~/.config/Code/User/snippets/ ```
 - OU
 - ``` ~/Library/Application\ Support/Code/User/snippets/ ```

Linux : 

 - ``` ~/.config/Code/User/snippets/ ```

> Note : Je n'ai pas vérifier si les chemains sur Mac et Linux marche ...

 
##  Générateur de snippet

 - [snippet-generator](https://snippet-generator.app/)
 - [willwull](https://willwull.github.io/vscode-snippet-generator/)
 - [vscodesnippetgenerator](https://vscodesnippetgenerator.azurewebsites.net/)
