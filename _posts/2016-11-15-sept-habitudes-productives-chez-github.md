---
title: Les sept habitudes des gens super efficaces chez GitHub
description: >
  Il y a une culture très particulière du travail chez GitHub. Voici sept
  comportements que Ben Balter a pu observer au cours de ces dernières années.
  Selon lui, cela rend certaines personnes plus efficaces. À adapter à votre
  contexte.
image: /assets/img/2016/11/github-office.jpg
source:
  title: Seven habits of highly effective GitHubbers
  url: http://ben.balter.com/2016/09/13/seven-habits-of-highly-effective-githubbers/
  author: Ben Balter
---

Au delà des simples compétences, j'ai pu m'apercevoir en participant à des
projets open-source comme [Jekyll](https://github.com/jekyll/jekyll) que
l'attitude et l'intention jouaient un rôle déterminant dans la réussite d'un
projet. Ce que décrit @benbalter, je le vis au quotidien à distance en
collaborant avec quelques employés de GitHub et je fais en sorte de l'appliquer
au sein de l'équipe de [Sud Web](https://sudweb.fr).
{: .lead }

L'action doit toujours prendre le pas sur les discussions et il est hors de
question de faire perdre du temps à ses camarades. Le focus est toujours porté
sur le produit et l'intérêt des utilisateurs. Cette philosophie n'est pas propre à
GitHub, mais j'ai trouvé les comportements décrits dans cet article importants à
souligner, aussi j'espère que sa lecture vous aidera à vous recentrer sur les
choses essentielles et qu'au final, vous serez plus efficaces dans vos projets
en équipe, tout en prenant soin de privilégier des rapports à la fois pros et
humains.

---

![Sceau officiel de l'Octocat]({{ page.image | relative_url }})

J'ai commencé à travailler chez GitHub lorsque nous n'étions qu'une centaine de
personnes. Il y a quelques semaines, nous avons dépassé les 600. Beaucoup de
choses ont changé, y compris les personnes (et ma fonction à plusieurs
reprises), mais il y a aussi des choses qui n'ont pas changé. GitHub a une
approche du travail très particulière et étant donné que je me suis démené
dernièrement pour décrire cette culture à mes collègues, j'ai décidé de
documenter quelques-uns des points communs que j'ai pu identifier à plusieurs
reprises chez les GitHubbers les plus performants. Il y en a surement plus de
sept mais je ne pouvais pas laisser passer un tel titre d'article. Donc voici au
moins *quelques-unes* des qualités qui, je pense, rendent les employés de GitHub
plus efficaces et plus performants au final.

## 1. Professionnel, mais pas formel

Il y a une différence entre être professionnel et être formel. Être
professionnel, c'est déterminé par sa maîtrise du métier. Les professionnels
sont efficaces. Ils sont méthodiques. Ils sont systématiques. Ils sont
organisés. Les professionnels prennent une tâche en charge sans se laisser
distraire par des problèmes personnels ou insignifiants. Le formalisme c'est une
adhésion rigoureuse à des règles et des conventions, souvent aux dépends de
l'efficacité. Le formalisme c'est de la rigidité. C'est être avant tout être
concerné par le cérémonial plus que la substance. C'est se focaliser sur les
apparences externes plutôt que sur sa véritable mission.

Vous pouvez être professionnel sans être formel. Lorsque vous recevez une
proposition de correction, vous pouvez répondre avec tact, vous rendre utile et
donner la preuve de vos prouesses techniques sans commencer votre réponse par
"*Madame, Monsieur, j'accuse réception de votre demande de fusion en date du 2
novembre 2015…*". Vous pouvez utiliser des emojis, des GIFs animés et un ton
résolument humain pour faire vos affaires, [^emoji] tout en restant totalement
concentré et précis comme un orfèvre sur votre tâche. Les gens de chez GitHub
les plus efficaces connaissent la différence entre professionnalisme et
formalisme, ils sont toujours professionnels et adoptent le formalisme seulement
si la situation l'exige. [^suit]

## 2. Livrez tôt, livrez souvent

S'il y a une phrase qui résume bien l'efficacité des ingénieurs de chez GitHub,
c'est "*ne laissez pas le mieux être l'ennemi du bien*", cette maxime peut
s'appliquer à n'importe quel autre corps de métier. Dans nos développements,
nous utilisons tous les jours ce qu'on appelle les "feature flags", qu'on
pourrait résumer comme une ligne de code qui va nous permettre de livrer une
fonctionnalité à une équipe, à l'ensemble des équipes internes ou à un
sous-échantillon d'utilisateurs d'un clic de souris. Presque systématiquement, à
chaque fois qu'une nouvelle fonctionnalité est développée, elle est montrée à
l'équipe en charge des premiers retours. Après un (ou plusieurs) aller-retours
pour l'améliorer, elle est livrée en interne pour passer de nouveaux tests et,
si tout se passe bien, elle est déployée petit à petit aux utilisateurs. Encore
une fois, nous utilisons ce flux de travail pour du code, mais il n'y a aucune
raison pour ne pas appliquer la même méthode pour un document, une politique ou
un programme. Pour résumer, vous voulez livrer une version 0.1 pas 1.0 (et vous
définissez vos attentes en conséquence).

Cela a diverses implications. D'abord, beaucoup d'idées ne passeront pas le
stade de la simple idée, de la *pull request*, de la livraison à l'équipe ou
même de la phase de livraison à toutes les équipes. Cependant il est largement
préférable de constater que la solution n'est pas adaptée avant qu'elle
atterrisse dans la branche `master` plutôt que de s'en apercevoir une fois que
les utilisateurs prennent cette fonctionnalité comme acquise. Une des pires
choses que vous pouvez faire c'est de vouloir "cacher" du code de peur d'avoir
des retours négatifs. Ensuite, il est également important de trouver un
équilibre entre les interminables optimisations et sempiternelles retouches
d'une part et l'impact potentiel ou l'amélioration apportée pour vous assurer
que vous progressez dans la bonne direction d'autre part. Même si une revue de
code révèle qu'un script interne pourrait être réécrit de manière plus compacte,
vous devez décider si votre temps ne serait pas mieux employé à vous concentrer
sur autre chose, même si vous savez que ce n'est pas encore parfait (et que ça
ne le sera peut-être jamais). C'est OK. Les GitHubbers efficaces [montrent leur
travail très tôt pour bénéficier de retours
immédiats](http://ben.balter.com/2014/11/06/rules-of-communicating-at-github/#surface-work-early-for-feedback).
Ils mettent rapidement de petites incrémentations de fonctionnalités à
disposition des utilisateurs. S'ils s'efforcent de tendre vers la perfection,
ils n'attendent pas de l'avoir atteinte pour livrer. *Itérez*, pour reprendre
une expression à la mode.

## 3. Si vous remarquez quelque chose, dites quelque chose

Très tôt, vous apprendrez que [le plus dur dans le développement logiciel c'est
de trouver le problème, pas de le
résoudre](https://en.wikipedia.org/wiki/Linus%27s_Law). Chez GitHub nous avons
une tradition bien ancrée, celle de "livrer à l'équipe" des fonctionnalités pour
un jour, une semaine ou même quelques mois, pour mieux comprendre comment cette
fonctionnalité sera utilisée dans le contexte de travail d'une personne. [Nous
faisons partie de nos utilisateurs les plus
critiques](/2016/08/30/dix-facons-de-rendre-un-produit-excellent/#3-buvez-votre-propre-champagne),
l'idée étant que quand quelque chose va de travers, nous en soyons les premiers
informés. Que ce soit une fonctionnalité uniquement destinée à un usage interne
ou une fonctionnalité qui est présente dans le produit depuis des années, nous
préférons que ce soit quelqu'un de chez nous qui constate (et remonte) le
problème, plutôt que ce soit un utilisateur qui en fasse les frais.

[Remonter des incidents ne coûte rien](http://ben.balter.com/2014/11/06/rules-of-communicating-at-github/#nobody-gets-fired-for-delbuying-ibmdel-opening-an-issue)
et il est facile de les clore s'ils s'avèrent infondés. Si vous remarquez
quelque chose de bancal, même si vous n'êtes pas certain que ce soit un problème
ou non, signalez l'incident et mettez l'équipe en charge en copie. Dans le
meilleur des cas, ils vous diront merci et déclarerons l'incident clos. Dans le
pire des cas, sans avoir à écrire une seule ligne de code, vous venez
d'améliorer le produit (en exposant un problème qui serait sinon passé
inaperçu). Et vous pouvez pousser le concept un peu plus loin [en vous inspirant
de cette règle des Boy
Scouts](http://programmer.97things.oreilly.com/wiki/index.php/The_Boy_Scout_Rule).
Lorsque vous corrigez une anomalie ou que vous implémentez une nouvelle
fonctionnalité, laissez toujours le code plus propre qu'à votre arrivée,
indépendamment de qui avait écrit le code crade à l'origine. Les développeurs
efficaces s'approprient le produit dans son intégralité et s'investissent
personnellement dans sa réussite lorsqu'ils voient que quelque chose pourrait
être amélioré (même s'ils n'en sont pas directement responsables).

## 4. Curiosité et amélioration personnelle

La curiosité est la première qualité d'un
[hacker](http://ben.balter.com/2013/02/04/what-is-a-hacker/#the-hacker-way).
Certaines personnes sont obsédées par une idée qui ne demande qu'à être testée,
que ce soit avec du code, une politique, des systèmes ou des process. Pour ces
gens, le monde est plein de problèmes en attente d'être résolus. Tout comme les
athlètes recherchent le plaisir de dépasser leurs limites physiques, les hackers
sont à la recherche de sensations et veulent repousser leurs limites (et celles
de leurs outils) au delà de ce qu'on connait, de ce qui a déjà été résolu et de
ce qui est possible.

Chez GitHub, cela fait longtemps que nous récompensons cette curiosité. Plus
formellement, nous avons des séances de lecture recompensées où les GitHubbers
sont encouragés à affiner leur technique en permanence (et à en apprendre de
nouvelles). Au delà de ça, il y a l'idée que si vous tombez sur quelque chose
que vous ne savez pas ou que vous ne comprenez pas, vous pouvez (et vous
devriez) prendre le temps de l'assimiler. Cela peut être une nouvelle partie
d'une application, un tout nouveau langage ou une toute nouvelle techno. La pire
chose que vous puissiez faire, c'est de baisser les bras ou de vous considérer
bloqué parce que vous êtes face à quelque chose d'inconnu. Nos employés les plus
performants nourrissent cette curiosité et essaient en permanence de
s'améliorer, sur les plans à la fois personnel et professionnel.

## 5. Toujours prêt à aider (mais savoir quand dire "non")

Une des premières choses qui m'a marqué quand j'ai rejoint GitHub, c'était que
mes nouveaux collègues étaient toujours prêts à m'aider. Je pouvais débarquer
sur n'importe quel canal de discussion (nous utilisons la messagerie instantanée
pour tout ou presque), poser une question sur un sujet qui ne m'était pas
familier et quelques secondes plus tard, plusieurs GitHubbers arrêtaient ce
qu'ils étaient en train de faire pour m'aider, pas juste pour m'expliquer
comment il fallait faire ce que j'essayais d'accomplir hein, non, ils
m'accompagnaient dans l'ensemble de la démarche. Plus tard, j'ai pu constater
des habitudes similaires et parallèles de longue date, de sur-documentation de
son travail, pour s'assurer que les futures générations de Hubbers puissent
poursuivre les efforts entrepris. Ce dévouement, cette façon de s'effacer pour
permettre aux autres d'être plus aptes à contribuer constituait la règle en
vaste majorité, pas l'exception.

Pour être tout à fait honnête, "soyez toujours prêts à aider", c'est un tantinet
exagéré. Les GitHubbers les plus performants savent aussi quand dire "non" à une
demande. Au bout d'un moment, vous vous apercevez qu'on vous offre plus
d'opportunités que vous n'avez de temps pour les honorer. Cela signifie que vous
devez prioriser les demandes qui auront l'impact le plus important et décliner
le reste. Vous apprendrez vite à dire "non" aux tâches à faible impact pour vous
attaquez à celles qui ont un impact plus fort (et prenez bien soin de faire de
même quand vous demandez de leur temps aux autres).

Nous sommes tous experts en quelque chose : une partie du code de l'application,
un process, un sujet en particulier ou ce truc que vous avez fait la semaine
dernière. Les GitHubbers efficaces prennent le temps de partager leur
connaissance pour s'assurer que les autres Hubbers seront encore plus efficaces.

## 6. Contribuez à l'économie de la valorisation

Sans doute influencé par
[Rework](https://www.amazon.com/dp/B002MUAJ2A/?tag=benbalter-20) qui suggère
que, pour quelqu'un qui se surpasse, dans bien des cas, une reconnaissance
publique sera une réponse plus appropriée qu'une récompense purement monétaire,
[^rework] on peut dire que GitHub contribue quelque part à une économie de la
valorisation. Ce que je veux dire par là, c'est que la valorisation (au sens
émotionnel du terme) est la monnaie qui rend les interactions quotidiennes
possibles chez GitHub. Pendant longtemps, ça a pris la forme d'un remerciement
public chaque vendredi (par exemple merci à Ben pour avoir pris le temps de
m'apprendre tel truc), mais comme vous pouvez vous en douter, il est difficile
de continuer ainsi lorsque votre entreprise est en forte croissance.

Aujourd'hui, l'économie de la valorisation prend souvent différentes formes :
des commandes ChatOps amusantes avec des ✨, des billets sur notre blog interne
et une culture d'entreprise où on remercie ouvertement qui de droit, soit sur un
ticket en cours de résolution, soit par message privé ou indirectement via un
manager. Cela peut également prendre d'autres formes. Ce n'est pas pour rien que
les annonces de nouvelles fonctionnalités sont rédigées par l'équipe à l'origine
de la fonctionnalité, plutôt que par un compte d'entreprise impersonnel. Les
personnes les plus performantes chez GitHub ont bien compris qu'elles sont plus
efficaces quand elles travaillent en équipe et font en sorte de faire savoir que
les contributions de leurs collègues sont appréciées, pas seulement pour
reconnaître et louer les efforts de leurs collègues mais également pour
perpétrer cette tradition et inciter les autres à faire de même.

## 7. Honnêteté, intégrité et authenticité

Chez Github nous avons pour habitude d'utiliser des phrases comme "parle comme
un humain" et "dans le doute, sois chic". En partant du principe que personne
n'est parfait, ce sont bien plus que des nouveaux buzzwords. [^authentic] À
l'extérieur, cela se traduit par voir les [marchés comme des
conversations](http://www.cluetrain.com/book/markets.html) avec des employés de
chez GitHub qui font office de proxies humains. En interne, nous partageons tous
le sentiment que l'action est beaucoup plus parlante que les mots. C'est une
chose de dire que vous serez transparent ou collaboratif, c'est autre chose de
travailler de manière ouverte, de fournir des occasions de participer et, au
final, d'implémenter les retours que vous recevez.

Bien qu'ici, à Washington D.C, il y ait une forte tradition de se montrer
exubérant en toute circonstance — "*Je suis tellement raviii de te voir!*" —
même si tout le monde sait que ce n'est pas le cas, et d'utiliser un double
discours pour se moquer d'une bévue passée, chez GitHub, il est primordial de
rester fidèle aux valeurs de l'entreprise (et aux siennes). En cas de
comportement hypocrite et incohérent, quelle qu'en soit sa portée, vous pouvez
en payer le prix fort, en tout cas en terme de confiance et de capital
sympathie.

C'est valable autant pour une anomalie technique qu'une défaillance humaine, les
deux prennent généralement la forme d'une rétrospective ou d'un post-mortem,
dénués de reproche. Nous croyons également implicitement en une volonté de
travailler en passant outre notre propre égo, d'avoir des conversations
difficiles (rendues encore plus difficiles par le fait de travailler à distance)
même si vous n'en avez pas envie. Les personnes efficaces chez GitHub parlent
ouvertement, que ce soit en positif ou en négatif et elles font toujours ce
qu'elles ont dit qu'elles feraient (ou ce que les autres devraient faire).

Voilà, ce sont donc quelques-unes des caractéristiques que j'ai pu relever chez
les employés de GitHub performants depuis quelques années. J'ai essayé de
décrire quelques-uns des aspects les plus liés à la culture du travail chez
nous. La situation est peut être différente chez vous. Je me suis dit que je
pourrais partager mes observations dans l'espoir qu'elles puissent aider à vous
rendre également plus performant, à la fois sur GitHub et ailleurs.

---

## Notes

[^suit]: Concrètement, j'ai porté un costume pendant une bonne partie de mes trois premières années chez GitHub. J'ai également beaucoup utilisé des expressions comme "jusqu'à présent". Même dans nos écrits légaux, nous nous efforçons de tendre vers une lisibilité pour les humains plutôt que d'avoir recours au traditionnel ton obscur du législateur.

[^rework]: Vous devriez vraiment lire [Rework](https://www.amazon.com/dp/B002MUAJ2A/?tag=benbalter-20), mais pour résumer, lorsque vous mettez sur une pied d'égalité le fait de faire quelque chose que vous aimez et une compensation formelle, le fait de faire cette chose que vous aimez devient un but en soi car la valeur financière plus tangible supplante la valeur émotionnelle et intellectuelle moins tangible, une fois que vous vous détournez de l'activité.

[^emoji]: Je dirais que les emojis et les GIFs animés peuvent aider à faire le job, particulièrement pour les équipes distribuées, en surcompenssant le ton qui est souvent perdu via les medias les moins aptes à véhiculer des émotions.

[^authentic]: C'est vrai, bien que tous les *millenials* préfèrent des expériences "#authentiques".
