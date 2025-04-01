# Welcome

## OpenOffice.org 2.4 ReadMe

For latest updates to this readme file, see <http://www.openoffice.org/welcome/readme.html>
Dear User

This file contains important information about this program. Please read this information very carefully before starting work.

The OpenOffice.org community, responsible for the development of this product, invites you to become members. As new users of OpenOffice.org, you will find precious information at this [page](http://www.openoffice.org/about_us/introduction.html).

Also read the sections below about getting involved in the OpenOffice.org project.

## Is OpenOffice.org really free for any user?

OpenOffice.org is free for use by everybody (this includes Government, business, educational and private use). For further details see the license text delivered together with OpenOffice.org or <http://www.openoffice.org/license.html>

## Notes sur l'installation

Configuration système requise :

- Microsoft Windows 98, ME, NT (Service Pack 6 ou version ultérieure), 2000 ou XP
- PC compatible Pentium
- 64 Mo de RAM
- 250 Mo (version CJK : 300 Mo) d'espace libre sur le disque dur
- 500 MB Disk space needed after installation is complete when deleting temporary installer files.
- Résolution d'écran de 800x600 minimum, au moins 256 couleurs

## Problems During Program Startup

Difficulties starting OpenOffice.org (e.g. applications hang) as well as problems with the screen display are often caused by the graphics card driver. If these problems occur, please update your graphics card driver or try using the graphics driver delivered with your operating system. Difficulties displaying 3D objects can often be solved by deactivating the option "Use OpenGL" under 'Tools - Options - OpenOffice.org - View - 3D view'.

You can install OpenOffice.org 2.4 alongside of an older version of OpenOffice.org. If you later choose to deinstall the older version of OpenOffice.org, you must call the installation program of the newer version and choose 'Repair'. This ensures that the new version is correctly registered in your system.

Please note that copy and paste via clipboard between OpenOffice.org 1.x and OpenOffice.org 2.4 might not work in OpenOffice.org format. If that happens, choose 'Edit - Paste Special' and choose a format other than OpenOffice.org, or open the document in OpenOffice.org 2.4 directly.

Please make sure you have enough free memory in the temporary directory on your system and that read, write and run access rights have been granted. Close all other programs before starting the installation.

Note: Please be aware that administrator rights are needed for the installation process.

Note for Windows 98 users only: If you choose to install Java during the OpenOffice.org installation program, the installer will ask you to reboot your system. You should either ignore this message or open the OpenOffice.org installation program again after the reboot.

## ALPS/Synaptics notebook touchpads in Windows

Due to a Windows driver issue, you cannot scroll through OpenOffice.org documents when you slide your finger across an ALPS/Synaptics touchpad.

To enable touchpad scrolling, add the following lines to the "C:\Program Files\Synaptics\SynTP\SynTPEnh.ini" configuration file, and restart your computer:

[OpenOffice.org]
FC = "SALFRAME"
SF = 0x10000000
SF |= 0x00004000

Note: The location of the configuration file might vary on different versions of Windows.

## Ai Squared ZoomText 7.11

Si vous souhaitez utiliser Ai Squared ZoomText avec OpenOffice.org 2.4, vous devez être équipé de la version 7.11 minimum. Seules les versions de Ai Squared ZoomText téléchargées après le 12 juin 2002 offrent les fonctionnalités requises.

## Raccourcis clavier

Vous ne pouvez employer dans OpenOffice.org que des raccourcis clavier (combinaisons de touches) non utilisés par le système d'exploitation. Si une combinaison de touches dans OpenOffice.org ne fonctionne pas selon la description de l'aide d'OpenOffice.org, il est possible que ce raccourci soit déjà utilisé par le système d'exploitation. Pour résoudre de tels conflits, modifiez par exemple les raccourcis définis par votre système d'exploitation. Vous pouvez aussi modifier la plupart des raccourcis définis dans OpenOffice.org. Pour plus d'informations à ce sujet, reportez-vous à l'aide d'OpenOffice.org ou à l'aide de votre système d'exploitation.

## Problèmes lors de l'envoi de documents par e-mails à partir de OpenOffice.org

Il est possible que le programme s'arrête brutalement ou se bloque lorsque vous tentez d'envoyer un document par e-mail en choisissant Fichier - Envoyer - Document par e-mail ou Document comme fichier PDF joint. En effet, le fichier système Windows MAPI (Messaging Application Programming Interface) génère des erreurs avec certaines versions de fichiers. Malheureusement, il est impossible de réduire ce problème à un certain nombre de versions. Pour de plus amples informations, consultez la page <http://www.microsoft.com>, puis tapez "mapi dll" dans le champ de recherche de la Base de connaissances Microsoft.

## Enregistrement

Nous vous remercions de bien vouloir suivre la procédure minimale d'enregistrement du produit lors de l'installation du logiciel. L'enregistrement est facultatif, mais nous vous serions reconnaissants de prendre quelques minutes pour l'effectuer, car les informations fournies aideraient la communauté dans son effort d'amélioration de la suite logicielle et de réponse directe aux besoins des utilisateurs. Pour protéger vos données personnelles, la communauté OpenOffice.org applique une politique de confidentialité stricte. Si vous n'avez pas suivi la procédure d'enregistrement au moment de l'installation du produit, vous pouvez l'effectuer à tout moment en consultant la page <www.openoffice.org/welcome/registration-site.html>

## Enquête auprès des utilisateurs

Nous vous invitons également à répondre à l'enquête destinée aux utilisateurs disponible en ligne. Les résultats de l'enquête permettront à OpenOffice.org de définir plus rapidement des normes de niveau supérieur pour vous offrir la prochaine génération de la suite bureautique. Pour protéger vos données personnelles, la communauté OpenOffice.org applique une politique de confidentialité stricte.

## Support utilisateur

Pour obtenir de l'aide sur la suite bureautique OpenOffice.org 2.0, consultez les archives où vous trouverez des réponses aux questions posées précédemment dans la liste de diffusion <users@openoffice.org> à l'adresse <www.openoffice.org/mail_list.html>. Si vous préférez, publiez vos questions sur la liste <users@openoffice.org>. N'oubliez pas de vous inscrire à la liste de diffusion afin de recevoir une réponse par e-mail.

La section FAQ est également à votre disposition dans la barre de navigation, à gauche sur la page d'accueil d'OpenOffice.org. Les questions les plus courantes se trouvent dans cette Foire aux questions.<http://user-faq.openoffice.org/>.

## Signalement des bogues et problèmes rencontrés

Le site Web d'OpenOffice.org héberge IssueZilla, notre outil de génération de rapports, de suivi et de résolution des bogues et des problèmes. Nous invitons chaque utilisateur à signaler les problèmes qu'il rencontrerait sur une plate-forme particulière. Le signalement systématique des problèmes est l'une des contributions les plus importantes que les utilisateurs peuvent apporter à la communauté pour le développement et l'amélioration constante de la suite logicielle.

## Contribution

Votre participation active au développement de ce grand projet Open Source apporterait beaucoup à la communauté OpenOffice.org.

En tant qu'utilisateur, vous êtes déjà un collaborateur précieux dans le cadre du processus de développement de cette suite bureautique. Nous vous invitons à vous impliquer encore davantage en contribuant aux activités de la communauté sur le long terme. Rejoignez-nous et visitez la page dédiée aux utilisateurs à l'adresse : <www.openoffice.org>

## Way to Start

The best way to start contributing is to subscribe to one or more of the mailing lists, lurk for a while, and gradually use the mail archives to familiarize yourself with many of the topics covered since the OpenOffice.org source code was released back in October 2000. When you're comfortable, all you need to do is send an email self-introduction and jump right in. If you are familiar with Open Source Projects, check out our To-Dos list and see if there is anything you would like to help with at <http://development.openoffice.org/todo.html>.

## Subscribe

Here are a few of the Project mailing lists to which you can subscribe at <http://www.openoffice.org/mail_list.html>

- News: <announce@openoffice.org> *recommended to all users* (light traffic)
- Main user forum: <discuss@openoffice.org> *easy way to lurk on discussions* (heavy)
- Marketing project: <dev@marketing.openoffice.org> *beyond development* (getting heavy)
- General code contributor list: <dev@openoffice.org> (moderate/heavy)

## Join one or more Projects

You can make major contributions to this important open source project even if you have limited software design or coding experience. Yes, you!

At <http://projects.openoffice.org/index.html> you will find projects ranging from Localization, Porting and Groupware to some real core coding projects. If you are not a developer, try the Documentation or the Marketing Project. The OpenOffice.org Marketing Project is applying both guerrilla and traditional commercial techniques to marketing open source software, and we are doing it across language and cultural barriers, so you can help just by spreading the word and telling a friend about this office suite.

You can help by joining the Marketing Communications & Information Network here: <http://marketing.openoffice.org/contacts.html>  where you can provide point communication contact with press, media, government agencies, consultants, schools, Linux Users Groups and developers in your country and local community.

Nous vous souhaitons un agréable travail avec OpenOffice.org 2.4 et espérons vous rencontrer prochainement sur le site Web.

La communauté OpenOffice.org

## Code source modifié / utilisé

Portions Copyright 1998, 1999 James Clark. Portions Copyright 1996, 1998 Netscape Communications Corporation.
