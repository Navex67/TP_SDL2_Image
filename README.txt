Suivre les étapes pour pouvoir afficher l'image SDL en FPC :

1 - Prenez tous les fichiers sauf Chapter3_SDL2.pas et .exe et l'image
2- Mettez les fichiers selectionné dans votre dossier FPC (C:\FPC\3.0.0\bin\i386-win32)
3 - Ensuite prenez l'image mettez la dans un dossier image par exemple peu importe l'emplacement
4 - Crée un nouveau programme en pascal, le compiler et incomporé le code du .pas dans votre programme
5 - Dans le code changer le chemin de l'image par votre chemin a cette ligne :  
sdlTexture1 := IMG_LoadTexture( sdlRenderer, 'trump.bmp' );
						ici


6-compiler et normalement l'image devrait s'afficher ;)