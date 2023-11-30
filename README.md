# Question-projet

1.Quel est l'hyperviseur utilisé ?
- Proxmox VE

2.L'hyperviseur est-il de type 1 ou 2, justifie ta réponse.
- hyperviseur est de type 1 , il s'installe directement sur le matériel physique d'un serveur et ne nécessite pas de système d'exploitation hôte .


3.A quoi correspondent VMBR2/5/6 ? donnes moi les étapes techniques pour pouvoir les
mettrent en place sur l'infrastrucure
- sur le shema VMBR2/5/6 correspondent au bridge , les etapes techniquee sont acceder au noeud sur lequel on veut configurer le bridget reseau cliquer sur "reseau " puis sur "ajouetr "
puis configurer le bridge ( nom, type , interface ..) ensuite valider les changemtn est redemarer le service .


4.Quel est le rôle de pi-hole sur l'infrastructure ? 


5.Quand un developpeur rejoins le VPN dédié pour eux, peuvent t-il accéder à internet 
à travers le VPN ?


6.Quand un administrateur rejoins le VPN dédié pour eux (pfSense) peuvent t-il accéder à 
internet à travers le VPN ? 


7.Le Domain Controller à "patte" dans chaque réseau de l'infrastructure, si le DC se trouvent uniquement sur le réseau WAN, comment pouvez vous permettre la résolution des noms de domaine depuis le réseau LAN et OPT1 ? Détails au maximum les étapes.


8.Quelles sont les étapes à réaliser de la part d'un technicien lors de la prise en charge d'un ticket à travers Jira ?


9.Quel est le rôle de HaProxy sur l'infrastructure? cite un exemple.


10.Dans quel répertoire se trouve la configuration du service HaProxy ? 


11.Pour se connecter au ressources de votre infrastructure, quel méthode dominante est utilisé ? RADIUS, LDAP, Local ? 


12.Détails moi la méthode pour pouvoir surveiller (monitorer) un équipement sur l'infrastructure ?
