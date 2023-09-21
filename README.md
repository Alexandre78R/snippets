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

## Explication - Pour accédez au dossier local de vos snippets

Vous pouvez utilisez le terminal avec la commande CD pour vous rendre dans votre dossier.

Windows : 
- ```C:\Users\VotreNomUtilisateur\AppData\Roaming\Code\User\snippets```

Mac : 
 - ``` ~/.config/Code/User/snippets/ ```
 - OU
 - ``` ~/Library/Application\ Support/Code/User/snippets/ ```

Linux : 

 - ``` ~/.config/Code/User/snippets/ ```

## Explication - Création d'un Snippet

```json
"Nom_du_Snippet": { 
	"scope": "type de fichier", 
	"prefix": "préfixe_du_snippet", // OU ["préfixe1", "préfixe2"]
	"body": [ "Code de l'extrait de code ici..." ],
	"description": "Description de l'extrait de code" 
}
 ```

-   `"Nom_du_Snippet"` : Le nom unique de l'extrait de code.
-   `"scope"` : Le type du fichier vous pouvez en indiquez plusieus avec une " , " comme  	 	séparateur.
-   `"prefix"` : Le préfixe qui déclenchera l'extrait lorsque vous commencerez à taper dans VSCode.
-   `"body"` : Le code réel de l'extrait.
-   `"description"` : Une brève description de l'extrait de code.
 
##  Générateur de snippet

 - [snippet-generator](https://snippet-generator.app/)
 - [willwull](https://willwull.github.io/vscode-snippet-generator/)
 - [vscodesnippetgenerator](https://vscodesnippetgenerator.azurewebsites.net/)