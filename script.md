# Les Scripts

Avec PowerShell il est possible de faire des [scripts](https://github.com/aletrou/Cours-Linux/blob/main/d%C3%A9finitions.md) pour automatiser certaines tâches.

Il y a deux manières de faire pour créer un script :
* Utiliser l'éditeur de script intégré à Windows : PowerShell ISE
* Utiliser un autre éditeur, tel que Visual Studio Code

PowerShell a quatre types d'autorisation différents :
* Restricted : aucun script ne peut être exécuté.
* AllSigned : seuls les scripts signés peuvent être exécutés.
* RemoteSigned : les scripts téléchargés depuis Internet doivent être signés pour être exécutés. Les scripts présents sur votre poste de travail ne sont pas concernés et peuvent être exécutés.
* Unrestricted : aucune restriction.

Pour créer un script et pouvoir l'exécuter, il faut s'assurer que PowerShell n'est pas en mode restreint. Pour vérifier cela puis le changer, il faut se servir de `Get-ExecutionPolicy` (pour vérifier les autorisations), et, si besoin, de `Set-ExecutionPolicy "Autorisation Voulue"` (pour régler le mode d'autorisation sur celui qu'on veut.).

---------------------------------------------------------------------------

## Sommaire

1. [Quelques définitions](https://github.com/aletrou/Cours-Linux/blob/main/d%C3%A9finitions.md)

2. [Histoire du PowerShell](https://github.com/aletrou/Cours-Linux/blob/main/histoire.md)

3. [Commandes](https://github.com/aletrou/Cours-Linux/blob/main/commandes.md)

4. [Script](https://github.com/aletrou/Cours-Linux/blob/main/script.md)
