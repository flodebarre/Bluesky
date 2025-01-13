---
layout: post
title:  "Se lancer sur Bluesky"
date:   2024-11-23
categories: bluesky
---

Bienvenue sur Bluesky !  
(Si vous n'avez pas encore de compte, allez voir [cette page]({% post_url 2024-11-22-QuitterXpourBluesky %}#openbsky)).  

Ce réseau ressemble à Twitter/X sur la forme, mais avec quelques différences notables.

## Bluesky, une plateforme ouverte

### Un code ouvert

Bluesky est *open source* : le [code](https://github.com/bluesky-social/) est ouvert, ce qui permet le développement de nombreuses applications [tierces](https://github.com/fishttp/awesome-bluesky). Si vous étiez fan de Tweetdeck, il existe par exemple un équivalent, [deck.blue](https://deck.blue).

NB : Vous pouvez (et devriez) créer des mots de passe spécifiques à ces applications tierces pour les utiliser ("[App password](https://bsky.app/settings/app-passwords)") : pas besoin de leur donner votre mot de passe principal Bluesky.   
<!--
![Capture d'écran du menu de paramètres pour mettre en place un mot de passe d'application]({{ site.baseurl }}/assets/img/bsky_apppwd.png)  
-->

Toutes les données publiées sur Bluesky sont [accessibles](https://docs.bsky.app) publiquement et librement. Notez en particulier que l'information des comptes que vous bloquez est publique.   
<blockquote class="bluesky-embed" data-bluesky-uri="at://did:plc:727oeq2js3j7ukz3tndao4sd/app.bsky.feed.post/3lb3uzxotxs2w" data-bluesky-cid="bafyreiehyo5ungvcnrchwl73smj7b75rohgn6wrtam6x37hsiwdtbb5wbm"><p lang="en">Exploring the full bluesky firehose, in three dimensions: firehose3d.theo.io<br><br><a href="https://bsky.app/profile/did:plc:727oeq2js3j7ukz3tndao4sd/post/3lb3uzxotxs2w?ref_src=embed">[image or embed]</a></p>&mdash; Theo Sanderson (<a href="https://bsky.app/profile/did:plc:727oeq2js3j7ukz3tndao4sd?ref_src=embed">@theo.io</a>) <a href="https://bsky.app/profile/did:plc:727oeq2js3j7ukz3tndao4sd/post/3lb3uzxotxs2w?ref_src=embed">November 16, 2024 at 10:56 PM</a></blockquote><script async src="https://embed.bsky.app/static/embed.js" charset="utf-8"></script>

### Une plateforme ouverte aux autres

Il est possible de communiquer avec d'autres plateformes, notamment sur le Fediverse, si les instances ont autorisé les liens. [Bridgy Fed](https://fed.brid.gy/docs#bluesky-get-started) permet notamment de créer des connexions. Par exemple, le compte `@flodebarre.bsky.social` peut être suivi sur Mastodon à l'adresse `@flodebarre.bsky.social@bsky.brid.gy`.  

## Fils d'actu (Feeds)

Sur Twitter/X, vous aviez deux types de présentation des tweets : anté-chronologique ("Abonnements") et via l'algorithme de X ("Pour vous", qui était devenu celui par défaut). Sur Bluesky, vous choisissez ! Vous organisez ce que vous voulez voir via les Fils d'actu ou Feeds.

Par défaut, si votre compte est récent, vous avez d'abord le Fil "[Discover](https://bsky.app/profile/bsky.app/feed/whats-hot)", un fil algorithmique, puis "Suivi" (Following), un fil anté-chronologique. Vous pouvez vous abonner à d'autres fils et réorganiser leur ordre via le menu "Fils d'actu". Quelques exemples :  
-  le fil "[Quiet Posters](https://bsky.app/profile/why.bsky.team/feed/infreq)" vous montrera les posts des personnes que vous suivez mais qui ne postent pas souvent (et dont les rares posts peuvent être noyés parmi ceux des personnes plus prolifiques) ;  
-  le fil "[Popular with Friends](https://bsky.app/profile/bsky.app/feed/with-friends)" vous montre des posts ayant du succès auprès des personnes que vous suivez ou qui vous suivent ;  
-  le fil "[Mentions](https://bsky.app/profile/did:plc:wzsilnxf24ehtmmc3gssy5bu/feed/mentions)" contient les posts qui vous répondent, mentionnent, ou citent. On est parfois débordé par les notifications et c'est un bon moyen de ne pas manquer des interactions ;  
-  le fil "[Science](https://bsky.app/profile/bossett.social/feed/for-science)" contient les posts de scientifiques (qui y postent spécifiquement en utilisant l'émoji tube à essai 🧪).   

N'hésitez pas à explorer les (très) nombreux fils existants !

Si vous épinglez un fil, il sera disponible directement en tant qu'onglet en haut de votre page.  
<img align="center" src="{{ site.baseurl }}/assets/img/bsky_feeds-tabs.png" title = "Des exemples d'onglets" alt = "Capture d'écran des onglets en haut du site Bluesky">

Les autres fils auxquels vous êtes abonné·e sont disponibles via le menu "Fils d'actu". Vous pouvez modifier l'ordre des fils à votre convenance en utilisant les flèches.     
<img align="center" src="{{ site.baseurl }}/assets/img/bsky_feeds-menu.png" title = "Des exemples de fils" alt = "Capture d'écran du menu fils d'actu">

Il est aussi possible de créer soi-même de nouveaux fils d'actu, soit en les [codant](https://docs.bsky.app/docs/starter-templates/custom-feeds) directement, ou avec des outils comme [Bluesky feed creator](https://blueskyfeedcreator.com/help#synced-lists).

## Kits de démarrage (Starter Packs)

Les kits de démarrage permettent de proposer une liste de personnes à suivre : on peut suivre d'un clic tous les comptes proposés. Les kits ont énormément contribué à la connectivité du réseau des contacts, en tout cas dans la communauté scientifique. Par exemple, en <a href= "https://go.bsky.app/HM6CfJ5">voici un</a> pour suivre des chercheurs et chercheuses de France en écologie et biologie évolutive.

### Comment les trouver   
-  Vous pouvez en voir passer dans vos contacts ; n'hésitez pas à les repartager pour leur donner de la visibilité.  
<blockquote class="bluesky-embed" data-bluesky-uri="at://did:plc:73aicoale2mqwrap63rdzwep/app.bsky.feed.post/3l3ticna2av2x" data-bluesky-cid="bafyreib44nu7dmdmgklpzijglbqcwto4rkr5l36o7epvpzwytppecrof3y"><p lang="en">I couldn&#x27;t find one so I just made it myself:

A starter pack to find global public health and epidemiology folks on Bluesky.

Feel free to suggest people who may be missing.
go.bsky.app/ARRb7Xn<br><br><a href="https://bsky.app/profile/did:plc:73aicoale2mqwrap63rdzwep/post/3l3ticna2av2x?ref_src=embed">[image or embed]</a></p>&mdash; Saloni (<a href="https://bsky.app/profile/did:plc:73aicoale2mqwrap63rdzwep?ref_src=embed">@scientificdiscovery.dev</a>) <a href="https://bsky.app/profile/did:plc:73aicoale2mqwrap63rdzwep/post/3l3ticna2av2x?ref_src=embed">September 11, 2024 at 12:40 AM</a></blockquote><script async src="https://embed.bsky.app/static/embed.js" charset="utf-8"></script>

-  Il existe des annuaires ([ici](https://blueskydirectory.com/starter-packs/), et un plus récent [ici](https://blueskystarterpack.com)) des kits de démarrage, pratique pour rechercher des kits correspondant à vos intérêts.  

-  Enfin, vous pouvez [créer](https://bsky.social/about/blog/06-26-2024-starter-packs) votre propre kit à partager, via l'onglet correspondant sur votre page de profil.  
![Capture d'écran de l'onglet Kit de démarrage]({{ site.baseurl }}/assets/img/bsky_StarterPack-create.png).

### Comment savoir les kits dans lesquels on est

Si vous êtes ajouté·e à un kit de démarrage populaire, vous verrez un afflux soudain d'abonnements. Vous pouvez retrouver les kits (et listes) auxquels vous appartenez via une application tierce, [Clearsky](https://clearsky.app) (onglet LISTS).  
NB : Clearsky a été souvent en panne mi novembre suite à la croissance brutale du réseau.

## Modération

### Le nuclear block

La fonction de blocage sur Bluesky a été surnommée "nuclear block" : elle coupe les interactions entre le compte bloqué et le compte bloqueur, même pour les comptes extérieurs. Personne ne peut plus voir les réponses sur Bluesky (contrairement à Twitter/X, où le compte bloqué restait visible aux extérieurs, qui pouvaient continuer à répondre à la suite).

La philosophie actuelle du réseau est de ne pas entrer dans des discussions agressives, mais de bloquer les trolls directement.

### Masquer des comptes ou des mots

Vous pouvez masquer (<i>mute</i>) des comptes ou des mots particuliers. Vous pouvez les définier dans Paramètres, Modération.  
![Capture d'écran de l'option pour masquer des mots]({{ site.baseurl }}/assets/img/bsky_mute.png)

### Détacher les citations  

Si un compte a cité un de vos posts, vous avez la possibilité de retirer votre post de la citation, en cliquant sur les trois points horizontaux en bas à droite du post qui vous cite. Cette fonctionnalité vise à éviter ce qu'on appelle le "quote tweet dunking", quand un compte influent met en avant un autre compte pour s'en moquer ou appeler au harcèlement.    
![Capture d'écran de l'option pour détacher un post cité]({{ site.baseurl }}/assets/img/bsky_Post-detach.png)

Vous pouvez aussi choisir, dès la composition du post, de ne pas permettre les citations.  
![Capture d'écran de l'option de pas autoriser les citations]({{ site.baseurl }}/assets/img/bsky_Post-citations.png)

### Retirer des abonné·es n'est pas possible

Contrairement à Twitter / X, il n'est pas possible de retirer des abonné·es. Si vous bloquez puis débloquez un compte, il sera toujours abonné au vôtre.  
(La raison est [technique](https://github.com/bluesky-social/social-app/issues/1160#issuecomment-1677642129) : chaque compte publie des listes d'abonnés et des listes de comptes bloqués ; on ne peut pas modifier la liste d'un autre compte.)

### Listes de modération

Vous pouvez créer et/ou vous abonner à des listes de modération (par exemple [ici](https://bsky.app/profile/uneheuredepeine.bsky.social/lists/3lbjyqbak3u2a)), qui permettent de bloquer ou de masquer (mute) tous les comptes qui y sont référencés.    

⚠️ Il n'est pas possible de débloquer ou démasquer un compte en particulier, c'est tout ou rien pour le moment (ce qui peut poser problème si un compte que vous vouliez suivre est ajouté à la liste).

## Autres astuces    

-  Les membres de l'enseignement supérieur et de la recherche en France utilisent le mot dièse `#HelloESR` pour se présenter.  
-  Si vous incluez une URL dans un post, une fois que l'aperçu s'est affiché, vous pouvez retirer l'URL du texte (c'est pratique pour gagner de la place) (h/t [Saloni](https://bsky.app/profile/scientificdiscovery.dev/post/3lbfpkm7srk2k))  
-  Vous pouvez dérouler un fil et l'afficher dans une page avec l'outil [Skyview](https://skyview.social) (comme ThreadReaderApp sur Twitter / X, mais sans les pubs).
