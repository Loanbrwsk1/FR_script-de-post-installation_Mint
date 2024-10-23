

/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\

VEUILLEZ NE PAS DÉBRANCHER LA CLÉ USB DURANT TOUT LE PROCESSUS (si sur clé USB)

VEUILLEZ AVOIR UNE CONNEXION STABLE ET ASSEZ RAPIDE (min. 2 Mo/s)

LE SCRIPT PEUT ETRE LANCÉ PLUSIEURS FOIS

/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\/!\



Lancer la programme:
    - Double-cliquez sur le fichier "lancer-la-configuration-de-Mint.sh"
    - Appuyez sur "Lancer dans un terminal" tout à droite

Il vous sera demandé votre mot de passe, puis on vous demandera d'écrire un "Nouveau mot de passe". Ce mot de passe est pour le compte administrateur (root). Si vous ne voulez pas l'activez, n'écrivez rien et appuyez simplement sur Entrée 2 fois.



Vous pouvez chiffrer le dossier personnel (si ce n'est pas fait à l'installation) /!\ Pas sans risques : cela pourrait supprimer des données personnelles (si présentes dans votre dossier personnel) mais cela reste très rare /!\ : il est impératif de vous connecter en root (administrateur). Pour ce faire:
    - Paramètres > Fenêtre de connexion (tout en bas) > onglet Utilisateurs > cocher Permettre la connexion manuelle (que vous pourrez décocher après si vous le voulez) 
    - Redémarrez l'ordinateur.
    - Fermez votre session (si vous vous êtes connectés) et cliquez sur "Ouvrir une session", entrez root en nom d'utilisateur et le mot de passe que vous avez défini au début de la configuration (si fait). Puis, exécutez chiffrer-dos-perso.sh avec double-clique puis "Lancer".


/\ Si vous ne vous souvenez plus de votre mot de passe root (administrateur), ou si vous ne l'avez pas défini, vous pouvez le réinitialiser avec la commande "sudo passwd root" /\



Vous pouvez activer l'option "Activer le verrouillage du pavé numérique" dans les options de l'écran de connexion (paramètres) pour verrouiller le pavé numérique sur l'écran de verrouillage.



Si vous voulez désactiver le fond d'écran dynamique ou le modifier :
    - Paramètres
    - Extensions 
    - Cliquez sur le moins en bas pour le désactiver // Cliquez sur la roue dentée pour le modifier 



Suite à la configuration, des alias seront disponibles. Un alias est une chaine de caractères qui va exécuter une commande longue pour gagner du temps. Voici ceux que vous pourrez utiliser : 


||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
|               |                                |                                                                                   |   
|   Exécutez    |   pour effectuer               |   Exemple                                                                         |
|               |                                |                                                                                   |
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
|               |                                |                                                                                   |
|   maj         |   sudo apt upgrade -y          |   maj -> mise à jour du système                                                   |
|   install     |   sudo apt install -y          |   install <app> -> installe l'application <app>                                   |
|   remove      |   sudo apt remove -y           |   remove <app> -> supprimer l'application <app>                                   |
|   fmaj        |   flatpak update -y            |   fmaj -> mise à jour de flatpak                                                  |
|   fs          |   flatpak search               |   fs <mot-cle> -> recherche les flatpak contenant <mot cle>                       |
|   finstall    |   flatpak install flathub -y   |   finstall <ID> -> installe le flatpak avec l'identifiant <ID> depuis flathub     |
|   fremove     |   flatpak remove -y            |   fremove <ID> -> supprime le flatpak avec l'identifiant <ID>                     | 
|               |                                |                                                                                   |
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||




=======================================================================================================================================

                                                        Personnalisation de Mint

=======================================================================================================================================


Pour afficher le dossier wallpapers (~/Images/) dans la fenêtre des fonds d'écran :
    - clic droit sur le bureau > modifier l'arrière plan du bureau
    - appuyez sur le "+" en bas à gauche
    - allez dans Images
    - séléctionnez wallpapers
    - cliquez sur ouvrir en bas à droite


Si vous souhaitez personnaliser Mint plus en profondeur, regardez cette playlist : 
https://youtube.com/playlist?list=PL-xp5bZmT8148dNSbLTQBhEntfp_HeXfu&si=HTQfktPsC7zkXVnr
