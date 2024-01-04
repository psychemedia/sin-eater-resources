---
jupytext:
  formats: ipynb,md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---
# Through the 1880s and early 1890s

Throughout the 1880s, occasional references to the sin-eater occurs in various *Notes and Queries* style columns, along with occasional reference works on folklore that make mentions of the tradition although add nothing of real substance to our understanding of it.

Of these full length works, two publications perhaps stand out in particular: Paxton Hood's *Christmas Evans*, which added nothing new but did garner some attention, as well as provoking a brief exchange in the *Christian World* periodical, and the publication of an edited edition of Aubrey's manuscripts, *Remaines of Gentilisme* by James Britten.

## Around and About

In Salopian Shreds and Patches in Eddowe's Journal of [May 12th, 1880](https://www.britishnewspaperarchive.co.uk/viewer/bl/0001502/18800512/132/0006), p6, Bagford's observations on Aubrey are noted and comment is passed on no mention of salt.

```{admonition} *Eddowe's Journal*, May 12th, 1880
:class: dropdown
> SALOPIAN SHREDS AND PATCHES.
>
> THE SIN EATER (Feb. 19,1879).
>
> A story never loses in the repetition. Bagford (1714), who copied from Aubrey's Collections, says, "Within the memory of our Fathers in Shropshire, in those Villages adjoining to Wales, when a Person dyed there was notice given to old sire, for so they called him, who presently repar’d to the Place where the deceased lay and stood before the Door of the House, where some of the Family came out and furnished him with Cricket [a low stool] on which he sat down facing the Door. Then they gave him a Groat, which he put in his pocket, a Crust of Bread, which eat, and a full bowle of ale, which he drank off at a draught. After this he got up from the cricket and pronounced with composed Gesture, 'The ease and rest of the soul departed, for which would pawn his soul'" —(Leland’s Collect., I., lxxvi). There is not a syllable about salt, and the custom may have been derived from the Welsh, as it prevailed only in the marches. The Pardon bowl was in use in some the larger monasteries, K. Witlaf left his horn for the monks of Croyland to quaff his health on his anniversary, and the citizens of Chichester drink wine round the city cross, and the cathedral choristers at his tomb partook of a bowl of milk pleasantly seasoned by the will of Bishop Shirborne. A relic of the custom survives in drinking the memory of the Dead.
>
> Mackenzie E. C. Walcott.
```

Over in the *Shrewsbury Chronicle* of [October 8th, 1880](https://www.britishnewspaperarchive.co.uk/viewer/bl/0000401/18801008/138/0005), p5,  Aubrey's text was reprinted, quoting the 1818 edition *Kennet's Parochial Antiquities*, albeit whilst making an error in the name of the minister Gwin, misnaming him *Govin*. Exactly the same text as the *Shrewsbury Chronicle* text, along with the misnaming of *Govin*, appears in volume 2 of *The Antiquary* of [October, 1880](https://archive.org/details/sim_antiquary-a-magazine-devoted-to-the-study-of-the-past_1880-10_2/page/174/mode/2up?q=Leland+%22sinne-eater%22), p174-5.

```{code-cell}
:tags: [remove-input]
# Load in token level side-by-side differencer
from jb_utils.diffsidebyside import show_diffs
x1='''"In the county of Hereford was an old custom at funerals to hire poor people, who were to take upon them all the sins of the party deceased, and were called "sin-eaters." One of them, I remember, liv'd in a cottage on Rosse highway. The manner was thus: "When the corps was brought out of the hous, and laid on the biere, a loaf of bread was delivered to the sinne eater over the corps, as allso a mazar bowle (a gossips bowl of maple) full of beer, which he was to drink up, and six pence in mony, in consideration whereof he took upon him *ipso facto* all the sinns of the defunct, and freed him or her from walking after they were dead. In North Wales the sinne eaters are frequently made use of ; but there, instead of a bowl of beer, they have a bowl of milk. This custom was by some people observed even in the strictest time of the presbyterian government. As at Dyndar *volens nolens* the parson of the parish, the relations of a woman deceased there had this ceremony punctually performed according to her will. The like was done in the City of Hereford in those times, where a woman kept, many years before her death, a mazar bowl for the sinne-eater ; and in other places in the county, as allso at Brecon, at Llangors, where Mr. Govin, the minister, about 1640, could not hinder this superstition. Methinks doles to poor people, with mony at funerals, have some resemblance of the sinne-eating. Doles at funerals were continued at gentlemen's funerals in the west of England till the civil warrs ; and so in Germany, at rich men's funerals, doles are in use, and to every one a quart of strong and good beer." (Aubrey of Gentilisme, M.S.) — *Kennet's Parochial Antiquities.*'''

x2='''In the county of Hereford was an old custom at funerals to hire poor people, who were to take upon them all the sinns of the party deceased, and were called sin-eaters. One of them I remember liv'd in a cottage on Rosse high-way. The manner was thus : when the corps was brought out of the hous, and laid on the biere, a loaf of bread was delivered to the sinne eater over the corps, as allso a mazar bowle (a gossips bowl of maple) full of beer, which he was to drink up, and six pence in mony, in consideration whereof he took upon him *ipso facto* all the sinns of the defunct, and freed him or her from walking after they were dead. In North Wales the sinne eaters are frequently made use of ; but there, instead of a bowl of beer, they have a bowl of milk. This custom was by some people observed even in the strictest time of the presbyterian government. As at Dyndar, *volens nolens* the parson of the parish, the relations of a woman deceased there had this ceremony punctually performed according to her will. The like was done in the city of Hereford in those times, where a woman kept, many years before her death, a mazar bowl for the sinne-eater ; and in other places in this county, as allso at Brecon, at Llangors, where Mr. Gwin the minister, about 1640, could not hinder this superstition. Methinks doles to poor people, with mony at funerals, have some resemblance of the sinne-eating. Doles at funerals were continued at gentlemen's funerals in the west of England till the civil warrs ; and so in Germany, at rich men's funerals, doles are in use, and to every one a quart of strong and good beer. Aubrey of Gentilisme, MS.'''
show_diffs(x1.replace('.',''), x2.replace('.',''),
           "Excerpt from *Shrewsbury Chronicle*",
           "Excerpt from Kennet's *Parochial Antiquities*")
```

In passing, we might also note the announcement of a new Welsh-English dictionary by D. Silvan Evans, as noted by the *Aberystwyth Observer* of [December 6th, 1884](https://www.britishnewspaperarchive.co.uk/viewer/bl/0003437/18841206/037/0004).

> New Welsh-English Dictionary
>
> All Welshmen students of the Welsh language will learn with pleasure that the Rev Professor Silvan Evans' Welsh-English Dictionary is now in the press, the first two sheets already been printed. The work will be published by Mr Spurrell, Carmarthen. Mr Evans English-Welsh Dictionary, published at Denbigh, was issued from the press nearly thirty years ago. The present work will be far superior to anything of the kind over attempted, and will largely supplement the previous great works.

Elsewhere, in *"A column of Antiquarian chit-chat relating to the county of Brecknock"* that was *Old Brecknock chips*, in the edition of [May 27th, 1887](https://journals.library.wales/view/2028388/2028501/1#), one curious correspondent enquired:

> QUERIES.
>
> THE WELSH "SIN EATER.
>
> "I have been told that this old custom used to obtain in some parts of Breconshire. Didn't one of the Awbreys (possibly John, the antiquary) write something about the "Sin Eaters?" What did it all mean, and where did it take place ? LLANGORSE EEL.

```{index} single: Red Dragon ; querying Roberts' Aubrey reference, 1884
```
### *Red Dragon*, 1884-6

In the Red Dragon of [November, 1884](https://archive.org/details/reddragon01wilkgoog/page/476/mode/2up?q=sin), p477, one curious reader picking up on the major review article on the sin-eater by Askew Roberts thay had appeared May, 1883, volume III edition, enquiring about the actual reference in Aubrey to the sin-eater:

> Notes and Queries
>
> The Sin Eater. —
>
> In the Red Dragon vol. iii., p. 450, appears a paper by Mr. Askew Roberts, J.P., Oswestry, on "The Sin Eater," in which it is stated that "John Aubrey, who flourished between 1626 and 1700, is the man to whom all later 'historians' are indebted for the prevalence of the custom" [Sin Eating]. Can anyone give me a reference to that part of Aubrey wherein this custom is dealt with? Brand, in his *Popular Antiquities*, quotes Aubrey, or professes to quote him in substance, but does not (at least not in my copy) give a reference. I possess a first edition of the Miscellanies ("collected by J. Aubrey, Esq.; London, printed for Edward Castle, next Scotland Yard Gate, by Whitehall, 1696"), but I have not been able to find a single word in them relative to the custom in question.
>
> Cardiff. Black-letter Folio.

A response appeared in the [vol VII, January 1885](https://journals.library.wales/view/2062893/2066723/102#?xywh=-743%2C345%2C3517%2C2320) edition, p89:

> The Sin Eater (vi.—477).—
> 
> "Black Letter Folio" will find reference to this custom in a book entitled The Remaines of Gentilisme and Judaisme, by John Aubrey, 1686-87 (London, 1881, 8vo.) On page 35 of this work the author mentions the practice as existing in Hereford in his time where he saw the Sin-Eater, who was "a long, leane, ugly, lamentable poor raskal." This custom, "though rarely used in our dayes, yet by some people was observed / continued even in the strictest time of ye Presbyterian government." He also states it was practised at Llangorse, in Brecon, where "Mr. Gwin, the minister, about 1640, could not hinder ye performing of it. I believe this custome was heretofore used all over Wales. This custom (methinks) alludes something to the scape-goat of ye old lawe. See Lev., chap, xvi., verse 21, 22."
> 
> *London.* AP IFAN

A year on from the November, 1884, query in the [November, 1885](https://journals.library.wales/view/2062893/2067842/110#?cv=110&m=53&h=sin-eater) edition, was a "do your homework" reply, p511:

> REPLIES.
> 
> The Sin Eater (vi.—477; vii.—89).—
> 
> Had "Blackletter Folio" referred to Brand, he would have found there all the information needed. Bagford's letter relative to the antiquities of London, printed in Leland's Collectanea, vol. I., and dated February 15th, 1714, has the following :— 
> ...
> *Oswestry.* Geo. H. Brierley.

The Bagford letter, as well as Aubrey, quoted in Brand, are included in the letter, along with a more extensive quote from Brand than the one provided by the previous correespondent in the chain, Ap Ifan.

```{admonition} Bagford and Brand, reprinted in *Red Dragon*, November, 1885
:class: dropdown

> "Within the memory of our fathers, in Shropshire, in those villages adjoyning to Wales, when a person dyed, there was notice given to an old Sire (for so they called him), who presently repaired to the place where the deceased lay, and stood before the door of the house, when some of the Family came out and furnished him with a cricket, on which he sat down facing the door. Then they gave him a Groat, which he put in his pocket; a crust of Bread, which he eat; and a full howle of Ale, which he drank at a draught. After this he got up from the cricket, and pronounced with a composed gesture *the ease and rest of the Soul departed, for which he would pawn his own Soul*. This I had from the ingenious John Aubrey, Esq., who made a collection of curious Observations, which I have seen and is now remaining in the hands of Mr. Churchill, bookseller. How can a man think otherwise of this, than that it proceeded from the ancient Heathens ?" Brand then gives the passage from *The Remains of Gentilism and Judaism* to which allusion is made at the latter reference by "Ap Ifan," and which, complete, reads as follows :—
> 
> " In the County of Hereford was an old Custome at Funeralls to hire poor People, who were to take upon them the Sinnes of the Party deceased. One of them (he was a long, leane, ugly, lamentable poor Raskal) I remember lived in a Cottage on Rosse high-way. The manner was, that when the Corps was brought °ut of the House, and laid on the Biere, a Loaf of Bread was brought out and delivered to the Sinne Eater, over the Corps, as also a Mazar Bowie, of Maple, full of Beer (which he was to drink up), and Sixpence in money; in consideration whereof he took upon him, *ipso facto*, all the Sinnes of the defunct, and freed him or her from walking after they were dead. This custome alludes, methinks, something to the Scape-Goat in the old lawe, Levit. chap, xvi., 21, 22. 'And Aaron shall lay both his hands on the head of the live Goate, and confesse over him all the iniquities of the Children of Israel, and all their transgressions in all their sins, putting them upon the head of the Goate, and shall send him away by the hand of a fit man into the Wilderness. And the Goat shall bear upon him all their iniquities unto a Land not inhabited ; and he shall let the Goat goe into the Wilderness.'
> 
> "This Custome (though rarely used in our days) yet by some people was observed even in the strictest time of the Presbyterian Government, as at Dynder (*volens molens* the parson of the Parish) the kindred of a Woman deceased there had this Ceremonie punctually performed, according to her Will; and also *he like was done at the City of Hereford in those times, where a Woman kepte lriany years before her death a Mazard Bowie for the Sinne Eater ; and the like in °ther places in this Countie ; as also in Brecon ; e.g., at Llanggors, where Mr. Gwin, the Minister, about 1640, could not hinder the performance of this ancient Custome. I believe this Custom was used heretofore all over Wales."
```

With several of the steps in the documented evidence chain recalled, a correspondent in the next edition of [December, 1885](https://journals.library.wales/view/2062893/2067949/112#), p617, also brings in a reference to Fosbroke's *Agriconensia* of 1821:

> The Sin Eater (vi.—477 ; vii.—89 ; viii.—511).—
> 
> Some time ago (I have lost the reference) there was a "Note" in the Red Dragon on the curious old custom of sin eating. The subject, if I recollect, was not very fully discussed, and perhaps the following remarks may be not without interest. They are taken from a curious book called *Agriconensia, or Archaeological Sketches of Ross*, by a Herefordshire antiquary named Fosbroke. It is a small volume, written apparently as a companion to Gilpin's *Wye Tour*, with which, in the copy I picked up the other day at a bookstall, it is bound. After mentioning various customs, he says, " It appears that so late as the 17th century there was in the villages adjoining to Wales an old man called the 'Sin Eater ;' and his office was, for a trifling compensation, to pawn his own soul for the ease and rest of the soul departed." Ellis, the editor of the Popular Antiquities, has extracted the following curious passage from the Lansdowne Manuscripts concerning a "Sin Eater" who "lived in a cottage on Rosse highway."
> ...
> *Cambridge.* W.A.

For some reason, the *"In the county of Hereford ...  This custom alludes, methinks, something to the Scape Goat in the old Lawe, Leviticus, chap, xvi., v. 21, 22."* is also reprited.

Note also that the provided reference to *"Agriconensia"* should correctly be given as *"Ariconensia"*.

Finally, we note that the letter of  November, 1885, also prompted a reply in the [Vol. IX, No. 1, January, 1886](https://journals.library.wales/view/2062893/2068170/113#?xywh=-781%2C52%2C3517%2C2320) edition, p98:

> REPLIES
> 
> The Sin Eater (vi.—477 ; vii.—89 ; viii.—511).—
> 
> I wish some of your correspondents would either drop all personalities, or make sure of their ground before indulging in them. In your November number Mr. Geo. H. Brierley (Oswestry),replying to a question of mine on this subject, begins by saying that "had 'Blackletter Folio' referred to Brand he would have found there all the information needed.". It is bad enough to impute ignorance of Brand to a man when he really deserves it, as I, on this occasion at any rate, most certainly do not, for I say in the very query to which Mr. Brierley replies (vi.—477), that "Brand in his Popular Antiquities quotes Aubrey. . . . but does not (at least not in my copy) give a reference."
> 
> *Cardiff* Blackletter Folio.


### *Cardiff Times*, 1885

In late spring and early summer of 1885, there was a brief flurry of correspondence on the topic of the sin-eater in the *Cardiff Times*, initiated by a reader who saw mention of it in the  *Newcastle Weekly Chronicle* and wrote as follows in the edition of  [May 16th, 1885](https://newspapers.library.wales/view/3422645/3422650/74/), p5:

> Questions
> 
> In a late issue of the *Newcastle Weekly Chronicle* (which paper, by the way devotes an entire page to Notes and Queries) I read an account of a superstition, which, it was alleged, used to be prevalent in parts of Wales; that is, that after a death occurred in a house, a professional, known as the "sin-eater," for a certain fee, agreed to take off all the deceased person's sins, by placing on his corpse a loaf of bread which he (the sin-eater) afterwards devoured ; the finale being that the operator was hunted from the house by the bereaved family, after the manner of the scapegoat of the Bible. I have since seen an article in which the alleged Welsh custom of sin-eating is discredited, and it is therein stated that no instance of the kind has ever been verified. Some of the many thousands of your readers who belong to the principality may be able to give some clue to the origin of the myth or, if not a myth, some  cases in which the custom was practised.
> 
> J. Stroud, Gloucester.

A response appeared in the [June 6th, 1885](https://newspapers.library.wales/view/3422672/3422677/86/) edition, p5, signed off by *EDITOR*, referring the question to Wirt Sikes' *British Goblins*, and quoting freely from it.

```{admonition} Wirt Sikes, *British Goblins*, quoted in *Cardiff Times*, June, 1885
:class: dropdown

> Local Notes and Queries
>
> AN EXTRAORDINARY WELSH SUPERSTITION.' —
> 
> For a good account of Welsh superstitions, I would refer "J., Stroud," to Wirt Sykes's British Goblins."  Referring to the "Sin-eater," he says :—" Well-informed Welshmen have denied that any such custom as that of the Sin-eater ever existed in Wales at any time, or in the border shires; and it must not be assertej that they are wrong, unless we have convincing proof to support the assertion. The existing evidence in support of the belief that there were ones Sin- eaters in Wales I have carefully collated, and (excluding hearsay and second-hand accounts), it is here reproduced. The first reference to the Sin-eater anywhere to be found is in the Lansdowne MSS. in the British Museum, in the handwriting of John Aubrey, the author. It runs thus:— 'In the county of Hereford was an old custom at funerals to hire poor people, who were to take upon them the sins of the party deceased. One of them (he was a long, lean, ugly, lamentable poor rascal), I remember, lived in a cottage on Rosse highway. The manner was that when the corpse was brought out of the house, and laid on the bier, a loaf of bread was brought out, and delivered to the Sin-eater over the corpse, and also a mazard bowl of maple, full of beer [which he was to drink up), and sixpence in money, in consideration whereof he took upon him, *ipso facto*, all the sins of the defunct, and freed him or her from walking after they were dead.' Aubrey adds, 'and this custom, though rarely used iu our days, yet by some people was observed in the strictest time of the Presbyterian Government; as at Dynder (*nolens volens* the parson of the parish), the kindred of the woman deceased there, had this ceremony punctually performed, according to-her will: and also the like was done at the city of Hereford, in those times, where a woman kept many years before her death a mazard bowl for the Sin-eater; and the like in other places in this country as also in Brecon, e.g., at Llangors, where Mr Gwin, the minister, about 1640, could not hinder the performance of this custom. I believe,' says Aubrey, 'this custom was heretofore used all over Wales.' He states further,—' A.D. 1686: This custom is used to this day in North Wales.' Upon this Bishop White Kennet made this comment:—' It seems a remainder of this custom which lately obtained at Amersden, in the county of Oxford, where, at the burial of every corpse, one cake, and one flaggon of ale, just after the interment, were brought to the minister in the church porch. No other writer of Aubrey's time, either English or Welsh, appears to have made any reference to the Sin-eater in Wales; and equal silence prevails throughout the writings of all previous centuries. Since Aubrey, many references to it have been made, but never, so far as I can discover, by any writer in the Welsh language— a singular omission, if there ever was such a custom; for, concerning every other superstitious practice commonly ascribed to Wales, the Welsh have written freely." EDITOR.

```

A further response in the edition of [July, 25th, 1885](https://newspapers.library.wales/view/3422735/3422740/122/), p5, attempted to develop the scapegoat idea a little further. The answer includes evidence from *"a trusted authority"* that appears to be the *Once a Week* quotation used in *Eddowes' Journal* of  [December 12th, 1862](https://www.britishnewspaperarchive.co.uk/viewer/bl/0001467/18621210/017/0002):

> ANSWERS.
>
> AN EXTRAORDINARY WELSH SUPERSTITION.
> 
> The great majority of your readers will have read the account of the "scapegoat" ceremony recorded in the Sacred Volume. Some, too, will remember a striking parallel custom (or, to put it more correctly, a parallel custom with a disparity) observed by the North American Indians. From goat to dog, and from dog to man, are remarkable bounds; but here is an account of a human "scapegoat" from a trustworthy authority :—
>
>...
> 
> H., Newport, Monmouthshire.

Here's how the text ascribed to the *trustworthy authority* compares:

```{code-cell}
:tags: [remove-input]
x7="""In a certain county in Wales, some years ago when a person died, his friends sent for the 'sin-eater' of the district, who, for half-a-crown, *took upon himself the sins of the deceased*, by the simple process of eating them. A loaf of bread was provided, which the 'sin-eater' first placed upon the dead man's chest, then muttered some incantations over it, finally eating it. By this he was believed to have taken from the deceased the heavy weight of his sins, appropriating them to himself, for which act of kindness he was regarded by everybody as an outcast. After the ceremony was finished, and he had received his pay, the 'sin-devourer' vanished in double-quick time, it being the usual custom for the bereaved friends to belabour him with sticks.
"""

x8="""While on the subject of deaths, I must mention singular superstitious custom which lingered, not very long ago, in some of the secluded mountain-vales of Carmarthenshire. When person died his friends sent for the sin-eater of the district, who, for the small sum of half a crown, actually took upon himself the sins of the deceased, by the simple process of eating them. The plan of operation was this :— A loaf of bread was provided, which the sin-eater first placed upon the dead person's chest, then muttered some incantations over it, finally eating it. Will it be credited that he was believed to have taken from the defunct the heavy weight of his sins, and to appropriate them to himself, for which act of kindness he was regarded by everybody as a tabooed outcast? Indeed, immediately after the ceremony was finished, and bad received his pay, he vanished in double quick time, it being usual custom for the friends to belabour him with sticks-if they could catch him.
"""

show_diffs(x7.replace('.','').replace('*','').replace("'",''),
           x8.replace('.','').replace('*','').replace("'",''),
           "Excerpt from *Cardiff Times*",
           "Excerpt from *Once A Week* / *Eddowes' Journal*")
```

### Eddowes' Journal, 1888

In [May 9th, 1888](https://www.britishnewspaperarchive.co.uk/viewer/bl/0001504/18880509/121/0004) edition of Eddowes' Journal, p4, an excerpt from  [*In Praise of Ale*](https://archive.org/details/inpraisealewith00marcgoog/page/92/mode/2up?q=sin+eater), 1888, p93-4, by W. T. Marchant, quotes the letter in Leland's *Popular Antiquities* as described in Hone’s *Year Book* of 1832.

```{admonition} Eddowes' Journal, May 9th, 1888, Quoting *In Praise of Ale*, Quoting *Hone's Year Book*, Quoting Leland's *Collectanea*
:class: dropdown
SIN EATING

In a letter dated 1715, printed in Leland's collection, it is stated that, within the memory of the writer's father, in those villages adjoining Wales, when a person died notice was given an old sire or village patriarch, who straightway repaired to the house of monrning and sat down on "a cricket or stool, facing the fire; then one of the family of the deceased gave the sin eater a groat which he put his pocket, a crust bread which he ate, and full bowl of ale which he drank off at a draught. Finally he rose from the cricket, and with confused gesture pronounced the ease and the rest of the soul departed for which would pawn his own soul". In Hereford, according to Aubrey, "The sin eater ate his bread and drank his bowl of beer over the corpse, and his fee was 6d. instead of 4d. Bishop Kennet, to whom Aubrey's manuscripts passed, added to them a note that a remainder of this custom lingered the beginning of the eighteenth century in the parish of Amersham, in the county of Bucks.

*In Praise of Ale. By W. T. Marchant.*
```

Comparing the text to Hone's text, we see a couple of notable difference amongst some minor ones (including the typographical error *monrning* rather than *mourning*) that arise from a surface rewriting the text:

```{code-cell}
:tags: [remove-input]
x3="""a cricket or stool, facing the fire; then one of the family of the deceased gave the sin eater a groat which he put his pocket, a crust bread which he ate, and full bowl of ale which he drank off at a draught. Finally he rose from the cricket, and with confused gesture pronounced the ease and the rest of the soul departed for which would pawn his own soul"""

x4="""a cricket (or stool), on which he sat down facing the door. Then they gave him a groat, which he put in his pocket; a crust of bread, which he ate; and a full bowl of ale, which he drank off at a draught." After this, he got up from the cricket, and pronounced, with a composed gesture, 'the ease and rest of the soul departed, for which he would pawn his own soul.'
"""

show_diffs(x3.replace('.',''),x4.replace('.',''),
           "Excerpt from *Eddowes / Praise of Ale*",
           "Excerpt from Hone's *Year Book*")
```

Firstly, we note the that Eddowes has the sin-eater facing the *fire* rather than the *door*.

Secondly, we note that the *"__composed__ gesture"* has become a *"__confused__ gesture"* . This is *not* and OCR error: the difference is between the actual publised texts.

To try to track down the point at which the change occurred, we can then compare the text from *Eddowes Journal* with that of the the original *In Praise of Ale* text.

*Red deletions are deltions from the original text in __In Praise of Ale__. Green additions are changes added in the __Eddowes' Journal__ quotation.*

```{code-cell}
:tags: [remove-input]
x6="""In a letter dated 1715, printed in Leland's collection, it is stated that, within the memory of the writer's father, in those villages adjoining Wales, when a person died notice was given an old sire or village patriarch, who straightway repaired to the house of monrning and sat down on "a cricket or stool, facing the fire; then one of the family of the deceased gave the sin eater a groat which he put his pocket, a crust bread which he ate, and full bowl of ale which he drank off at a draught. Finally he rose from the cricket, and with confused gesture pronounced the ease and the rest of the soul departed for which would pawn his own soul". In Hereford, according to Aubrey, "The sin eater ate his bread and drank his bowl of beer over the corpse, and his fee was 6d. instead of 4d. Bishop Kennet, to whom Aubrey's manuscripts passed, added to them a note that a remainder of this custom lingered the beginning of the eighteenth century in the parish of Amersham, in the county of Bucks."""

x5="""Probably the most peculiar of the many quaint customs which our ancestors kept up was the funeral one of sin eating. In a letter dated 1715, printed in Leland's Collection, it is stated that, within the memory of the writer's father, in those villages adjoining Wales, when a person died notice was given to an old "sire" or village patriarch, who straightway repaired to the house of mourning and sat down on a "cricket," or stool, facing the door ; then one of the family of the deceased gave the sin-eater a groat, which he put in his pocket, a crust of bread which he ate, and a full bowl of ale which he drank off at a draught. Finally, he rose from the cricket, and with a composed gesture pronounced "the ease and rest of the soul departed, for which he would pawn his own soul". In Hereford, according to Aubrey, the sin-eater ate his bread and drank his bowl of beer over the corpse, and his fee was sixpence instead of fourpence. Bishop Kennett, to whom Aubrey's manuscripts passed, added to them a note that a remainder of this custom lingered at the beginning of the eighteenth century in the parish of Amersham, in the county of Bucks. There, at the burial of every corpse, a cake and a flagon of ale were brought to the clergyman in the porch ; but this refection was not served until after the interment."""

from jb_utils.diff_match_patch import diff_match_patch
from IPython.display import HTML
differ = diff_match_patch()
diff = differ.diff_main(x5.replace('.',''),x6.replace('.',''))
display(HTML(differ.diff_prettyHtml(diff)))

```

(ANTQS)=
## *The Antiquities of Laugharne, Pendine*, Mary Curtis, 1880

In a self-published work on [*The antiquities of Laugharne, Pendine, and their neighbourhood, Carmarthenshire, Amroth, Sandersfoot, Cilgetty, Pembrokeshire, South Wales*](https://archive.org/details/antiquitiesoflau00curt/page/206/mode/2up?q=funeral), published in second edition at least in 1880, Mary Curtis describes the following custom All Hallows custom in which parishioners might learn the names of who was to die in the following year (p206-7):

> They had this very remarkable custom : — I was informed by a respectable farmer of Eglwyscummin parish, who died in old age in 1875, that his father told him that there was a person appointed to every church, whose office was to go to the church on All Hallows Eve to hear the names of those who would die the next year, called. An old woman of this town, dead now sixty years, is remembered by some old people as going on this eve to Laugharne church to stand by the chancel window, where they say she distinctly heard the names pronounced. She said that, as she had been once to hear the names called, she was bound to go at every future eve. I was told by one of the most respectable and esteemed old inhabitants of this town, that in his presence some one said to her, that a lady then dangerously ill, and given over, would die. She said, "No ; for her name was not called." She did recover and live many years. And another time she foretold that a funeral of a person would take place shortly in Laugharne church, which it did. In Cardiganshire, on All Hallows Eve, it was the custom to sit in the porch of the church to see those pass through who should die that year. I am not quite sure that this was not on St. John's day, 24th June. I give no opinion, though I would not declare them falsehoods, or the results of imagination. Which is the worst to believe — too much or too little ? Some people, deeming themselves very wise and superior to such credulity, with a wonderfully wise look, condemn these as mere superstitions.

Of death tradition themselves, Curtis describes appropriate behaviour for showing respect for the dead  (p213-7):

> When a death occurred, a boy was sent round the town and neighbourhood to give notice, and invite to the sitting up ; he rang a small bell to draw attention. People were expected to come to the funerals in their neighbourhood, even without invitation; families would be offended if they did not.

The way the Welsh treat their dead, with respect and kindness, is noted, as are the "watch" stye traditions:

> There is something very beautiful in the care the Welsh show for the dead, and in their customs at burials. It proves their kindliness and reverential feeling. They think it wanting in feeling to leave the dead body in the room by itself for a single instant. The face was exposed, a number of candles kept burning all night, and those who came to sit up brought presents of tea, sugar, and candles. An old inhabitant of this town, who died 20 years ago, aged 89, was at a wake kept in a room of the old inn, called the Dials, now in ruins.

But even in death, so might traditions of youthful life might also be observed:

> During the night, in presence of the departed, a number of men and women, she said, played different games. One was called "Trounsing;" it was like blind-man's buff. If the young man who was blindfolded caught a young woman, she was his sweetheart for that year.

But even by the 1880s, these traditions were lapsing:

> No more remains of these customs in Laugharne, except the presents of candles, etc., which friends do bring.

The gathering for the funeral procession involved an element of hospitality, and once again it is easy to see how the over-zealous fan of the sin-eating tradition might claim elements of this behaviour as a relic of that ritual:

> A large number of people followed the deceased to the church. They assembled outside the house ; cake and mulled beer were offered to all ; four chairs were placed outside to rest the coffin on ; the clerk of the church gave out two or three verses of a hymn, and all sang ; as they passed to the church they sang the remainder. This custom prevailed to within 50 or 60 years. I remember, in 1871, an old inhabitant, at the funeral of his niece, having cake and mulled beer for the company assembled before his house.

The placing of flowers and herbs on the coffin was also observed:

> In Laugharne a number of people still attend funerals ; there is something very pleasing in this last attention paid to the departed. How often of an afternoon do you hear the slow, measured tread of a large company passing down the ancient town to the last resting-place ! I hope it will long be heard. They placed rosemary and laurel on the coffin. A white rose sometimes placed on the grave of a virgin ; the red rose for those distinguished for benevolence and other social qualities.

The procession route, and ritual observations made along the the way, is also described:

> In days a little further back they used on the way to church to rest the coffin, at intervals, on resting-stones, and would put down the coffin at every crossway, kneel down, and repeat the Lord's Prayer ; they did the same at entering the churchyard. The route funerals took at this period, and position of these stones, are known. A path, called the "funeral path" once went through "Hollis Stone field," which is at the back of Llansadurnen church and by the Hugden road ; it joins the fields belonging to Capthorne farm, and is near a farm — "Tavern Devlas." This was the ancient route for funerals coming from the houses about here to Llansadurnen church ; for the Hugden road was then in a bad condition in winter. The four stones forming the resting-stone still remain in Hollis Stone field. One large square stone, with the surface only visible, has a circle carved in the middle of it with an inner circle. Another large square one, sunk in the ground too, has a small round hollow in its middle, generally filled with water. In olden times they used to throw pins into the water here, then take them out to prick their warts, believing it was a sure cure. The two other stones are so deeply buried that only a portion is seen. The sketch here represents them. Another resting-stone stood on "Resting Stone Hill," which is on the opposite side of the road to where the Broadway Mansion was, and overlooks the ground that house occupied. To go to it, you enter a gate on the left hand of Broadway road coming from Laugharne, and nearly opposite the two curiously bent trees, which are in grounds of Broadway Mansion. From this gate you go straight up the slope of the hill, called "Dell Grove;" rails go up on your left all the way, dividing Dell Grove from the Paddock. Near the top of the hill you have to pass through a gate which leads into Resting Stone Hill. The road now bends to the left after leaving this gate ; then goes along the hill to another gate by which you enter another road. At the edge of it, and on your left, stood the resting-stone, about 150 yards from the gate just mentioned. It was five tons in weight, two feet high, four feet wide, six long. Continuing along this road, you come to another gate, through which this road passes along a field to a gate opening on to Sir John's Hill. Dell Grove is beneath Resting Stone Hill ; Portland Field lies just beneath the field next to Resting Stone Hill. This is the ancient road by which the people of the marsh passed to and fro to Laugharne when the Broadway road beneath was too bad to traverse, and by which funerals from Llansadurnen passed to Laugharne church. When they arrived at Sir John's Hill, they crossed it, and went down the road which leads out by the line of houses at Gosport ; but instead of coming out there, they took the dirty lane on the right, which is at the back of those houses, and passes by Gosport House to the Strand, which lane is the old route I have described in Part VIII. When funerals came by the ancient route I have there noticed, which is by Little Madras Hill, issuing out opposite Kingaddle into the main road ; before entering this road they rested the coffin by this hill, just where the roads meet, that is at the cross roads, and sang a hymn. An inhabitant told me she remembered their doing this. I thought, when I stood on this spot, where so many a one that had fell asleep had rested on their way to their last resting-place, with voices rising up from this elevated spot, what a glorious place it was for such an act of worship ! — in the midst of the beautiful works of the Creator, Swelling hills stretch in all directions ; the undulating line of hills ending in a point on the fine sands of Pendine. Before them, a village perched on the extreme point of a hill, its white cots, hay-stacks, and church-spire peeping through the trees : below, the pleasant green fields. On the right. Fern Hill, with its dark patch of trees, gives a pleasant change to the scene ; on the left Coigan rises, clothed with a thick wood on its slope, which has been destroyed lately. Beyond the hills, hard by, are the distant hills, where flitting gleams of sunshine disclose sweet patches of green. The Perselau mountain far away, with its peaks grey and shadowy, shuts in the prospect ; the everlasting hills around, the great deep beneath. A lady of this town remembers a resting-stone by the Mariner’s Corner, turning to Victoria Street.

Following the burial, observances to respect the deceased at the place of their burial were observed:

> Their care of the dead did not end here ; they planted the grave of the relative with shrubs and flowering plants. This is an ancient custom, still observed in Wales. It is a pleasing scene, on Easter eve, when those who have relatives buried in Laugharne churchyard, are busy putting the graves in order. Every Saturday or Sunday, throughout the year, that any kind of flower or green is to be had, they lay crosses or crowns or bunches of flowers on the graves. Tradition says it had its origin in the people being told they would not be happy unless they cleaned the graves for Sunday. An author, writing in 1803, says : "So great is the reverence the Welsh have for the resting-places of the dead, that no one is ever known to touch a flower on a grave; it was considered sacrilege."

The lack of respect in current generations is then contrasted with the older, traditional behaviour:

> It were well if some of the present generation did imitate their exemplary ancestors ; we do sometimes hear of flowers stolen from the graves.

As we have already encountered, the route that a funeral procession would take was often followed *prior* to funeral by a corpse candle, or even a funeral rehearsal. And Curtis observes the same traditional belief:

> A strong belief exists in the diocese of St. Davids, that lights "traverse the road by which the dead will be carried to burial." The funeral procession too is seen previously, and the mourners distinctly recognized. One tradition says, they appear in answer to the prayer of St. Lanon. She desired that the people might be warned before death came, and so have time to prepare themselves. Another says, it was in consequence of Bishop Ferrars, who was burnt at the stake in Caermarthen, declaring that if his doctrine was true, a light would go before the death of every person in the diocese of St. Davids.

Curtis notes that this legend is widely recognised one:

> I have received many relations of these appearances from parties of great respectability, and whose veracity and freedom from fanciful imagination I am sure of.

And so, another example is given:

> An inhabitant of Laugharne, of a most respectable old family of the place, himself universally esteemed, told me that as he was walking one evening on the St. Clears road, he saw in the distance two lights moving across a field, and enter the Pilgrim Church by the river. A person who was with him saw them as well. At another time he saw a funeral procession go into this church.

And another, which describes how the sight of the light could be seen as predictive of a death shortly to follow:

> A member of a most respectable, substantial family of Pendine related this to me. Her brother, with his little son, was on a visit to her family. This son was suddenly seized with fever about eleven o'clock, and in great danger. The father for a while was walking before the house, when he saw a small light in the churchyard of Pendine, moving towards the church porch, and going into the church. He saw it inside the church ; it came out and passed to the tomb of his family ; there it stood fixed. The child died soon after. On the spot where the light had rested the child was buried. He had disbelieved, now he believed in the lights.

And yet another, which hints at a more portentous observation:

> A member of the same family gave me the following : Her husband was very near his end, when she said to him, "There is a curious little light on the Strand ; what can it be?" He replied, "It is the light before death ; it is for me."

Curtis further observes that is is not just in Wales that this traditional belief appears to hold true:

> That it may not be thought by disbelievers that it is only Welsh superstition, and confined to Wales, I will finish the list with another which occurred in England a short time ago. A dignitary of the Church of England was dying; suddenly a very vivid light illumined the room, so much so that the man-servant was obliged to shade his eyes with his hand. He who was dying said, "Look !" After this he seemed done with earth, and had no wish to be read to, or to have any human help. The light vanished as suddenly as it came. His daughter was in the room, and saw the light, and told this to a friend of my cousin's. My family have known this clergyman many years. An old inhabitant related this — Fifty-four years ago, as some working men at mid-day in summer were cutting wheat in a field near Eglwyscummin church, they saw a funeral coming along the path in the direction of the church. While it passed they lay down. Among the mourners they recognized persons resident in the parish, and an old woman walking last, carrying green plants in a handkerchief to put on the grave. Soon after an inhabitant died. His funeral went by this path, with the same people as mourners, and the woman with plants, just as the men had seen. The relater of this was one of the most respected persons in the place.

For Curtis, the belief still appeared to be a contemporary one, around the 1880s:

> An old woman of Laugharne said to me that she continually saw those lights. It seems from all I hear that they are seen as much as ever. I must give this singular one : A gentleman belonging to a county family of Pembrokeshire, was some years ago returning in his carriage to his home in Tenby from the railway. He was inside. With the coachman sat a tenant of the lady from whom I had this story. Between Narberth and Templeton, they perceived through the darkness of the evening a black mass moving towards them. As it approached they saw it was a funeral. The horses now plunged and reared ; the carriage was overturned ; the coachman and the tenant thrown over the hedge into the field, much bruised ; the gentleman escaped without injury. My friend who related this had it from her tenant himself.

```{index} single: Thiselton Dyer, T. F. ; Domestic Folk-lore, 1881
```
(DFKLD)=
## *Domestic Folk-lore*, T. F. Thiselton Dyer, 1881

In [*Domestic Folk-lore*](https://archive.org/details/b24884558/page/n4/mode/2up?q=sin-eater), 1881, the rather splendidly named Revered Thomas Firminger Thiselton Dyer also describes several traditions relating to death and burial, including the traditional use of salt (p59-63):

> Again, the interval between death and burial has generally been associated with various superstitious fears and practices. Thus, as soon as the corpse is laid out there is still a widespread custom of placing a plate of salt upon the breast, the reason being no doubt to prevent the body swelling ; although there is a belief that it acts as a charm against any attempt on the part of evil spirits to disturb the body.

Several Scottish traditions are also described:

> Pennant tells us that formerly in Scotland, "the corpse being stretched on a board and covered with a coarse linen wrapper, the friends laid on the breast of the deceased a wooden platter, containing a small quantity of salt and earth, separate and un-mixed ; the earth an emblem of the corruptible body, the salt as an emblem of the immortal spirit." Mr. Napier, in his "Folk-Lore of the West of Scotland," points out that we may find another explanation for the plate of salt on the breast in the "sin-eaters," persons who, in days gone by, when a person died, were sent for to come and eat the sins of the deceased. On their arrival their first act was to place a plate of salt and one of bread on the breast of the corpse, repeating a series of incantations, after which they devoured the contents of the plates. By this ceremony the deceased person was supposed to be relieved of such sins as would have kept his spirit hovering about his relations to their discomfort and annoyance.

One intriguing tale suggests that fresh corpses were once believed to have divinatory powers:

> It is customary, especially among the poor, for those who visit a house while the dead body is lying in it to touch the corpse, thereby showing that they owe the departed one no grudge. This practice, in all probability, originated in the belief that a corpse would bleed at the touch of the murderer, constant allusions to which we find in old authors.

Watching over corpses is recognised as a custom still contemporary to the 1880s:

> The practice of watching the dead body until its burial is not yet obsolete, a custom indeed which, among the Irish, is even still occasionally the scene of the most unseemly revelries, those present often-times indulging in excessive drinking and riotous merry-making. In days gone by, however, this practice was attended with every mark of respect to the deceased one, the leading idea being to see that the devil did not carry off the body.

As regards funerals and the funeral procession, some of which we have not previously heard described:

> Lastly, since the formation of cemeteries, many of the quaint old funeral customs which formerly existed in many of our country villages have passed away. Now-a-days, the "last act," as the committal of the body to the grave has been termed, has been shorn of much of its pomp. Thus, in the North of England it was customary, only a few years ago, to carry "the dead with the sun" to the grave, a practice corresponding with the Highland usage of making "the deazil," or walking three times round a person, according to the course of the sun.

We might also note that sometimes, such traditions may offer something of a surprise to a cleric in charge of the funeral:

> On one occasion, in the village of Stranton, near West Hartlepool, the vicar was standing at the churchyard gate, awaiting the arrival of the funeral procession, when, much to his surprise, the entire group, who had come within a few yards of him, suddenly turned back and marched round the churchyard wall, thus traversing its west, north, and east boundaries. On inquiring the reason of this extraordinary procedure, one of the mourners quickly replied, "Why, ye wad no hae them carry the dead again the sun ; the dead maun ay go wi' the sun."

A similar custom appears to hail from Wales, although I haven't yet tracked down the original Pennant reference:

> This is not unlike a Welsh custom mentioned by Pennant, who tells us that when a corpse was conveyed to the churchyard from any part of the town, great care was always taken that it should be carried the whole distance on the right-hand side of the road.

The payment to the cleric, the *parson's penny*, as we heard described in Wirt Sike's *British goblins*, is also mentioned, along with a possible variant, the *spade money*:

> A curious custom, which still survives at Welsh funerals, is termed "the parson's penny." After reading the burial service in the church, the clergyman stands behind a table while a psalm is being sung. In the meantime each of the mourners places a piece of money on the table for his acceptance. This ceremony is regarded as a token of respect to the deceased, although it was no doubt originally intended to compensate the clergyman for praying for the soul of the departed. In some Welsh parishes a similar custom, called "spade-money," is observed. As soon as the corpse has been committed to its resting-place, the grave-digger presents his spade as a receptacle for donations, these offerings, which often amount to a goodly sum, being regarded as his perquisites.

Finally, a traditional belief, the echoes of which may provide us with routes into local stories based on the graves to be found in the north side of church graveyards:

> From time immemorial there has been a popular prejudice among the inhabitants of rural villages against "burial without the sanctuary." This does not imply in unconsecrated ground, but on the north side of the church, or in a remote corner of the church-yard. The origin of this repugnance is said to have been the notion that the northern part was that which was appropriated to the interment of unbaptised infants, excommunicated persons, or such as had laid violent hands upon themselves. Hence it was generally known as "the wrong side of the church." In many parishes, therefore, this spot remained unoccupied while the remaining portion of the churchyard was crowded. White, in his "History of Selborne," alluding to this superstition, says that as most people wished to be buried on the south side of the churchyard, it became such a mass of mortality that no person could be interred "without disturbing or displacing the bones of his ancestors." A clergyman of a rural parish in Norfolk says : — "If I were on any occasion to urge a parishioner to inter a deceased relative on the north side of the church, he would answer me with some expression of surprise, if not of offence, at the proposal, 'No, sir, it is not in the sanctuary.'"

```{index} single: Britten, James ; editor, Remaines of Gentilisme, 1881
```
```{index} single: Aubrey, John ; Remaines of Gentilisme, ed. J. Britten, 1881
```
(AUBGT)=
## John Aubrey, *Remaines of Gentilisme*, 1881

A long time in the coming, 1881 also saw the publication by *The Folk-Lore Society* of [*Remaines of Gentilisme and Judaisme*](https://archive.org/details/remainesgentili01aubrgoog/page/n12/mode/2up) by John Aubrey, "Printed from Lansdowne manuscript 231 in the British Museum", and edited by James Britten.

Some of Aubrey's "observations" on occult and supernatural matters had been previously published as [*Miscellanies*, Collected by J. Aubrey, Esq.](https://archive.org/details/miscellanies00aubr/page/n1/mode/2up), "printed for Edward Castle, next Scotland Yard Gate, by Whitehall", in 1696, but that collection had made no mention of that lamentable fellow from the Rosse highway. This collection undoubtedly contributed to later opinions of him regarding his credulity.

But now for the first time we have a collection that provides us us a relatively direct form access to Aubrey's text without having to visit the British Library and view the original manuscript.

```{admonition} "Remains of Gentilisme and Judaisme", Review
:class: seealso dropdown

A review of the work appeared in *Notes and Queries* of September 9th, 1881, [Vol 4 Iss 80, p38-9]:

> NOTES ON BOOKS, &c.
> *Remains of Gentilisme and Judaisme.* By John Aubrey, 1686-7. Edited by James Britten. (Folk-lore Society.)
>
> Folk-lore Record. Vol. III. Part II. (Same Society.)
>
> AUBREY was a credulous person, He seems to have received with confidence almost everything, however wonderful, which any one told him with a grave face. This is an unhappy form of character for any one to possess who is desirous of instructing his fellow creatures in any original thought, but it was in many ways useful to him as a collector of folk-lore. Had Aubrey been in any sense a critic it is to be feared that he would have rejected much that we now value highly. A little power of comparison and analysis would, however, have been useful to him in one direction. Aubrey thought, as most persons of his generation did, that nearly all our popular mythology was derived from Roman or Biblical sources. This we now know to be an error, and to some of us it must seem a very strange one. It was not, however, unnatural for those whose literary culture was confined almost solely to the classical tongues to assume that all popular knowledge and superstition had come from those languages which had been the source of almost all the knowledge which they themselves esteemed. John
Aubrey could not be aware of the high value which would be set on every relic of — religion and science by those who came after him, and he is not to be blamed for having left unrecorded so much of that which we are quite certain he knew, nor for having communicated what he did preserve in a most uninviting form. On the other hand, it is strange that he should have thought such "old wives' fables" in any way worthy of serious thought. His contemporaries we know counted it mere folly, but we owe to this unwisdom of his one of the most important collections we possess. If, indeed, he had done nothing more than preserve for future use the wild Yorkshire soul dirge beginning,
>
> " This can night, this ean night,  
> Every night and awle,"
>
> we should have been much in his debt. It has been often printed, notably by Sir Walter Scott in his *Minstrelsy of the Scottish Border*, and by Mr. Atkinson in his *Glossary of the Cleveland Dialect* ; it has, perhaps, however, not as yet received all the attention it deserves. The " Brig o' Dread...no brader than a thread," over which souls have to pass, seems to point to the Arabic tradition of the bridge of Al Sirât, which is laid over the midst of hell, and is finer than a hair and sharper than the edge of a sword, across which all have to pass ere they enter paradise or hell. It is important to know whether the idea of this bridge is the common property of the Aryan and Semitic peoples, or whether it was introduced into our mythology in the Middle Ages by contact with the East. We believe the former hypothesis to be the true one. It was until recently the common opinion that almost all our folk-lore which could be paralleled by the traditions of Oriental lands had been imported by the Crusaders. In numberless cases this has been shown to be a false assumption, and we have little doubt that it will be proved to be so in this case. It is as impossible to point out all the important facts garnered in this strange miscellany as it would be to direct attention to all the good things in one of Dr. Smith's dictionaries. We may mention, however, that groaning trees, wax images for magic, men who were invulnerable, and boy bishops are all illustrated, The editing has been done with the most scrupulous care, and there are many apt notes. The part before us of the Folk-lore Record contains papers by Dr. George Stephens, Miss Evelyn Carrington, Mr. H. C. Coote, and other well-known students of the popular mythology. The two English folk-tales are of much interest, and the account of a rural wedding in Lorraine has amused us very much.

```

In his preface to the work, written from Isleworth, in February 1881, James Britten sets the scene (p.iv-v):

> The *Remaines* while containing much of value, are not of equal merit throughout. Aubrey had the faculty of collection rather than that of selection, and he was clearly inclined to be credulous, and thought to be so by some of his most noteworthy contemporaries.

This opinion does not belong solely to the editor:

> The great naturalist John Ray, for example, expresses himself plainly on this head in a letter printed by Aubrey in the *Natural History and Antiquities of Surrey* (v. 410). He says : —
>
> "I think (if you can give me leave to be free with you) that you are a little too inclinable to credit strange relations. I have found men that are not skilful in the history of nature very credulous, and apt to impose upon themselves and others, and therefore dare not give a firm assent to anything they report upon their own authority, but are ever suspicious that they may either be deceived themselves, or delight to teratologize (pardon the word), and to make show of knowing strange things."

There is evidence of Aubrey's own response to such criticism:

> In the same work, however (iv. 407, Appendix), Aubrey gives the following justification of his conduct : —
>
> "It may seem nauseous to some that I have raked up so many old western proverbs, which I confess I disdain not to quote. Pliny himself being not afraid to call them oracles, lib. 18, cap. 4: 'Ac primum omnium oraculis majore ex parte agemus, quae non in alio vitae genere plura certiorave sunt.' For proverbs are drawn from the experience and observation of many ages, and are the ancient natural philosophy of the vulgar, preserved in old English and Norse rhymes handed down to us, and which I set as instantiae crucis, for our curious modem philosophers to examine, and give διολις  to their 'Ολις."

That Aubrey *did* collect write down his observations, no matter how credulous he was, is, however, to be valued:

> At the present day, whatever we may think of Aubrey's credulity, all folk-lorists are glad that he did not "disdain to quote" the proverbs, sayings, and traditions of the people.

Britten then explains some of the challenges he faced in providing a criticcal view when editing the papers and commenting upon them:

> With regard to the notes which I have here and there added, a word or two of explanation seems needed. When I undertook to edit the work at the request of the Council of the Folk-Lore Society, I had hoped that these would be much more numerous, and that I should have obtained much help in my work from those who were far more fitted than myself to undertake the task. I regret to say that, although the work was sent in slip-proof to all the Members of the Council, I have received no assistance whatever from the greater number of them. I do not wish to be imderstood as complaining of this want of assistance — I know too well what it is to be more than fully occupied — but I mention this as tending to explain the fewness of the notes.  

And so we turn to the republished papers themselves.

The first reference, [p19](https://archive.org/details/remainesgentili01aubrgoog/page/n34/mode/2up?q=sinne) appears to be a pair of Latin dedications that I have to yet translate correctly (machine generated translations leave something to be desired!)

> Sinne Eaters [see p. 33]
>
> Jam tamen extincto cineri sua dona ferebant;  
> Compositiq' nepos busta piebat avi. — [F. v. 425-6] 
>
> -----
>
> Signaq' dat digitis medio cum pollice junctis;  
> Occurrat tacito ne levis umbra sibi.  
> Terq' manus puras fontana perluit unda;  
> Vertitur, et nigras accipit ore fabas.  
> Aversusq' jaci: sed dum jacit, Haec ego mitto;  
> His, inquit, redimo meq' meosq' fabis.  
> Hoc novies dicit, nec respicit: umbra putatur  
> Colligere, et nullo terga vidente sequi.— .[F. v. 433-440.]

The next reference is  made by *"W. K."*, Bishop White Kennett, one time owner of the manuscripts, on [p24](https://archive.org/details/remainesgentili01aubrgoog/page/n40/mode/2up?q=sinne):

> Sinne Eaters
>
> It seems a remainder of this custom which lately obtained at Amersden, in the county of Oxford, where at the burial of every corps one cake and one flaggon of Ale just after the interrment were brought to the minister in the Ch. porch. W. K.

The mention directly follows a description of offertory customs at funerals on p23:

>Offertories at funeralls.
>
> These are mentioned in the Rubrick of ye ch. of Engl. ComonPrayer-booke : but I never sawe it used, but once at Beaumaris, in Anglesey ; but it is used over all the Counties of North-Wales. But before when the corps is brought out of Doores, there is Cake & Cheese, and a new Bowle of Beere, and another of Milke with ye Anno Dni ingraved on it, & ye parties name deceased, wch one accepts of on the other side of ye Corps ; & this Custome is used to this day, 1686, in North Wales,`[From this to the end of the paragraph is added by Dr. Kennett. — Ed.]` where a small tablet or board is fixt near the Altar, upon which the friends of ye defunct lay their offerings in mony according to their own ability and the quality of the person deceased. This custom proves a very happy augmentation to some of the very poor vicars, and is often the best part of their maintenance.

And if we look to the item directly preceding *that*, also on p23, we see a reference to *soul cakes*:

```{index} single: Soul cake ; Aubrey, John
```

> *Soule-Cakes*
>
> In Salop, &c. die oïum Animarum (All-Soules-day Novemb. 2d) there is sett on the Board a high heap of Soule-cakes, lyeing one upon another like the picture of the Sew-Bread in the old Bibles. They are about the bignesse of 2d cakes, and n'ly all the visitants that day take one ; and there is an old Rhythm or saying,
>
> A Soule-cake, a Sonle-cake,  
> Have mercy on all Christen soules for a Soule-cake.
>
>This custome is continued to this time. This putts me in mind of the Feralia dict, à ferendis ad tumulum epulis: id quod forant [ferunt ?] tunc epulas ad sepulchrum quibus jus ibi parentare. Feralia deiun manium dies in Febr. Had Ovid continued his Fastorum to Novemb: in probabiliiy we should have found such a kind of custome used at that time sc. Novemb: 2d.
>
> Mdm. Seed-cakes, for the Ploughmen, after Sowing is donne; I thinke, All-Saints' night, or Eve. Also Cakes at Home-harvest.

The more complete sin-eater reference, with which we are familiar, comes at [pp.35-6](https://archive.org/details/remainesgentili01aubrgoog/page/n50/mode/2up):

```{index} ! single: sin eater ; Aubrey, John
```

```{admonition} Aubrey on *Sinne-Eaters*,  *Remaines of Gentilisme*, ed. J. Britten, 1881
:class: note dropdown
> Sinne-eaters. [See pp. 18, 22]
>
> In the County of Hereford was an old Custome at funeralls to hire/have poor people, who were to take upon them all the sinnes of the party deceased. One of them I remember lived in a cottage on Rosse-high way. (He was a long, leane, ugly, lamentable poor raskal.) The manner was that when the Corps was brought out of the house and layd on the Biere ; a Loafe of bread was brought out, and delivered to the Sinne-eater over the corps, as also a Mazar-bowle of maple (Gossips bowle) full of beer, which he was to drinke up, and sixpence in money, in consideration whereof he tooke upon him (ipso facto) all the Sinnes of the Defunct, and freed him (or her) from walking after they were dead. This custome alludes (methinkes) something to the Scape-goate in ye old Lawe. Leviticus, cap. xvi. verse 21, 22. "And Aaron shall lay both his hands on the head of the live goate and confesse over him all yw iniquities of the children of Israel, and all their transgressions in all their sins, putting them upon the head of the goat, and shall send him away by the hand of a fitt man into the wildernesse. And the goat shall bear upon him all their iniquities, unto a land not inhabited : and he shall let the goat goe into the wildernesse." This Custome (though rarely used in our dayes) yet by some people was observed/continued even on the strictest time of ye Presbyterian goverment: as at Dynder, volens nolens the Parson of ye Parish, the kinred/relations of a woman deceased there had this ceremonie punctually performed according to her Will : and also the like was donne at ye City of Hereford in these times, when a woman kept many yeares before her death a Mazard-bowle for the Sinne-eater ; and the like in other places in this Countie ; as also in Brecon, e, g. at Llangors, where Mr. Gwin the minister about 1640 could no hinder ye performing of this ancient custome. I believe this custome was heretofore used over all Wales.
>
> See Juvenal Satyr, vi. [519-521,] where he speakes of throwing purple thread into ye river to carry away ones sinne.
>
> In North-Wales, the Sinne-eaters are frequently made use of; but there, insted of a Bowle of Beere, they have a bowle of Milke.
>
> Methinkes, Doles to Poore people with money at Funeralls have some resemblance of that of ye Sinne-eater. Doles at Funeralls were continued at Gentlemens funeralls in the West of England till the Civil-warre. And so in Germany at rich mens funerals Doles are in use, and to every one a quart of strong and good Beer. — Cramer.
```

At last, then, general access to a copy of Aubrey's writings had been made available. But it is perhaps noteable that the publication of the book, and the mention of the Sinne-Eater it contained, did not direclty lead to a a flurry of indigant correspondence around the topic.

## Paxton Hood's *Christmas Evans : the preacher of Wild Wales*, 1881

Although Aubrey's edited manuscripts perhaps had a rather limited appeal, and a limited ability to generate controversy, another book was published in 1881 that *did* generate interest in the sin-eater topic.

The Reverend Edwin Paxton Hood was a non-conformist minister and prolific author. Several of his works took the form of biographies of other non-conformists. One such character, Christmas Evans, who presumbaly took his name from his birthdate, 25th December, 1766 – was a noted Welsh minister with a gift for preaching. He was the subject of his 1881 book [*Christmas Evans : the preacher of Wild Wales, his country, his times and his contemporaries*](https://archive.org/details/christmasevanspr00hood/page/22/mode/2up?q=sin-eater).

In the chapter on *Characteristics of Welsh Preaching*, p22-24, Paxton Hood has cause to comment on the tradition of the sin-eater as surviving despite the activities of a wave of great Christian preachers in the first half of the 19th century:

> In a word, it is impossible, knowing Wales as we know it in our own day, to form any very distinct idea of the country as it was when these great preachers arose ; and, when the tides of a new spiritual life rolled over the Principality, the singular relics of even heathenish superstition were loitering still among the secluded valleys and mountains of the land. No doubt, the proclamation of the Gospel, and the elevated faith which its great truths bring in its train, broke the fascination, the charm, and power of many of these ; but they lingered even until within the last forty or fifty years, — indeed, the superstition of the Sin-Eater is said to linger even now in the secluded vale of Cwm-Aman, in Caermarthenshire.

Paxton Hood's description of the tradition appears to owe, originally at least, to John Murray’s 1860 work, [*A handbook for travellers in South Wales and its borders*](https://archive.org/details/ahandbookfortra07firgoog/page/n30/mode/2up?q=sin), with its mention of the fee of 2s 6d and the "fact" that was hounded out after performing the ceremony *"with blows and kicks"*.

> The meaning of this most singular institution of superstition was, that when a person died, the friends sent for the Sin-Eater of the district, who, on his arrival, placed a plate of salt and bread on the breast of the deceased person ; he then uttered an incantation over the bread, after which, he proceeded to eat it, — thereby eating the sins of the dead person ; this done, he received a fee of two-and-sixpence, — which, we suppose, was much more than many a preacher received for a long and painful service. Having received this, he vanished as swiftly as possible, all the friends and relatives of the departed aiding his exit with blows and kicks, and other indications of their faith in the service he had rendered. A hundred years since, and through the ages beyond that time, we suppose this curious superstition was everywhere prevalent.

If we display a side-by-side view to inspect the difference between the texts, we can spot the areas of similarity directly:

`````{admonition} Comparing the Texts
:class: dropdown

````{panels}
<p><strong>Excerpt from Paxton Hood, <em>Christmas Evans</em></strong>

</p><p>the superstition of the sin-eater is said to linger even now in the secluded vale of <span style="background: #69E2FB;">cwm-aman,</span> in <span style="background: #69E2FB;">caermarthenshire the meaning of this most singular institution of superstition was, that</span> when a person died, the friends sent for the sin-eater of the district, <span style="background: #69E2FB;">who,</span> on his <span style="background: #69E2FB;">arrival,</span> placed a plate of salt <span style="background: #69E2FB;">and bread</span> on the breast of the <span style="background: #69E2FB;">deceased person ;</span> he then <span style="background: #69E2FB;">uttered</span> an incantation over the bread, <span style="background: #69E2FB;">after which,</span> he <span style="background: #69E2FB;">proceeded to eat it, —</span> thereby eating the sins of the dead person <span style="background: #69E2FB;">;</span> this done, he received <span style="background: #69E2FB;">a</span> fee of <span style="background: #69E2FB;">two-and-sixpence, — which, we suppose, was much more than many a preacher received for a long</span> and <span style="background: #69E2FB;">painful service having received this, he</span> vanished as <span style="background: #69E2FB;">swiftly</span> as <span style="background: #69E2FB;">possible, all</span> the friends <span style="background: #69E2FB;">and relatives</span> of <span style="background: #69E2FB;">the departed aiding his exit with</span> blows and kicks, <span style="background: #69E2FB;">and other indications</span> of <span style="background: #69E2FB;">their faith in</span> the <span style="background: #69E2FB;">service</span> he <span style="background: #69E2FB;">had rendered</span> a <span style="background: #69E2FB;">hundred years since, and through the ages beyond that time, we suppose this curious superstition</span> was <span style="background: #69E2FB;">everywhere prevalent</span> </p>
---
<p><strong>Excerpt from John Murray, <em>Handbook for Travellers in South Wales</em></strong>

</p><p>the superstition of the sin-eater is said to linger even now in the secluded vale of <span style="background: #69E2FB;">cwm amman</span> in <span style="background: #69E2FB;">carmarthenshire</span> when a person died, the friends sent for the sin-eater of the district, <span style="background: #69E2FB;">who</span> on his <span style="background: #69E2FB;">arrival</span> placed a plate of salt on the breast of the <span style="background: #69E2FB;">deceased, and on the salt a piece of bread</span> he then <span style="background: #69E2FB;">muttered</span> an incantation over the bread, <span style="background: #69E2FB;">which</span> he <span style="background: #69E2FB;">finally eat,</span> thereby eating the sins of the dead person this done, he received <span style="background: #69E2FB;">the</span> fee of <span style="background: #69E2FB;">2s 6d,</span> and vanished as <span style="background: #69E2FB;">quickly</span> as <span style="background: #69E2FB;">he could,</span> the friends <span style="background: #69E2FB;">helping his departure by the aid</span> of <span style="background: #69E2FB;">sundry</span> blows and kicks, <span style="background: #69E2FB;">if they could catch him ; for as it was believed that he took upon himself the sins</span> of the <span style="background: #69E2FB;">defunct,</span> he <span style="background: #69E2FB;">was looked upon as</span> a <span style="background: #69E2FB;">social pariah for whom nothing</span> was <span style="background: #69E2FB;">too bad</span> </p>
````

The Paxton Hood version offers nothing new and no significant corruptions, perhaps other than representing the original *muttering* of the curse as *uttering*:

`````

```{admoniton} A horse's head as a sign of social delinquency
:class: seealso

As well as referring to the sin-eater tradition, Paxton Hood also makes passing reference to a "horse's head" tradition that is used to castigate a "social delinquent":

> Another odd custom was the manner in which public opinion expressed itself on account of any domestic or social delinquency. A large crowd assembled before the house of the delinquent, one of whom was dressed up in what seemed to be a horse's head ; the crowd then burst forth into strong vituperative abuse, accompanying the execrations with the rough music of old kettles, marrow-bones, and cleavers ; finally, the effigy of the sinner was burnt before the house, and the sacred wrath of the multitude appeased. The majesty of outraged opinion being vindicated, they dispersed.

This stands in contrast to the New Year's Eve *Mari Lwyd* tradition, which is a far more light hearted and celebratory affair, but closely resembles the {term}`Cefyl Pren` tradition identified in Murry's *Handbook for travellers in South Wales*, specifically:

> Another curious custom is still in existence — that of the Cefyl Pren, which occurs in cases where popular indignation is excited by any gross infringement of domestic rights or proprieties. A large crowd, one of whom is dressed up with a horse's head, assembles before the door of the delinquent, who, after undergoing an immense amount of vituperation and a hideous noise of old kettles and cleavers, is at length burnt in effigy, by which the sacred wrath of the people is at length appeased.
```

```{index} double: correspondence, Christian World ; Eynon Davies, T.
:name: CHWLD:correspondence:1882:eynondavies
```
### Paxton Hood Challenged by T. Eynon Davies in *Christian World*

Hood's mention that the tradition was said *to linger even now in the secluded vale of Cwm-Aman, in Caermarthenshire* was a claim that could not be allowed to go unchallenged, howewer, as a letter from T. Eynon Davies, the Congregational Minister in Cwmamman, to the editor of *Christian World* ([Thursday 09 February, 1882, p4](https://www.britishnewspaperarchive.co.uk/viewer/bl/0004838/18820209/023/0004)) makes clear, noting that the claim had presumably raised issue in the Welsh language press:

> CARMARTHENSHIRE HEATHENISM.
>
> (To the Editor of the Christian World.)
>
> Sir— In Mr. Paxton Hood's new work, " Christmas Evans. the Preacher of Wild Wales." there is one startling statement, to which I desire to call the attention of the genial and accomplished author.
>
> It has provoked discussion in the Welsh press, but as Mr. Hood does not presumably include a wide knowledge of Welsh among his many accomplishments, it is but fair that his attention should be called to the matter in his own tongue. Hence my addressing you, Sir. In the early part of the book, Mr. Hood refers to a Welsh custom of laying a dish of bread and salt upon the dead body in a house of mourning, and in due course a certain official called a " sin-eater" appeare on the scene, who for a consideration of half-a-crown eats the bread (representing the sins of the deceased) off the dish, and is then driven out of the house by the friends and relatives of the departed.
>
> Then it is added that this piece of heathenism has now totally disappeared from Wales excepting the district of Cwmammun, in Carmarthenshire!

The minister then disputes Paxton Hood's claim in no uncertain terms:

> May I be allowed to say that the good people of Cwmamman, Carmartbenshire, never heard of this "sin-eater" until thy were startled by this revelation in Mr. Hood's book? Some octogenarians whom I have questioned have never seen a " sin-eater," neither have yhey heard their parents nor their grand-parents ever refer to this custom, and I can assure the readers of " Christmas Evans " that for at least 120 years no " sin-eater ' has been known or heard of in Cwmamman.

He goes on to explain how Cwmannan is not some primitive settlement in the back of the beyond:

> This picture of the place most give English readers a very " wild" notion, in all conscience, of " wild Wales;" but perhaps you will allow me to say that we are not so benighted as we are made to appear. We are a law-abiding. chapel going people. We have our railway and postal and telegraphic services to connect us with the world. We read our daily and weekly newspapers, and aspire even to monthlies and quarterlies. We are educated in politics and religion at least up to the average standard. Nowhere in England, from coast to coast, will you find Liberalism and Nonconformity comparatively stronger than they are to-day at this obscure little Cwmamman. This is not Welsh braggadocio but sober fact. In our political struggles, Liberalism is overwhelmingly triumphant; and our "census of worshippers," if compared with your city and town returns, would have your averages far behind. This, then, is hardly the right sort of place for a " sin-eater."

He closes with a request that Paxton Hood does the honourable thing and retract the claim, or make some other amend:

> I am quite sure Mr. Hood will be as sorry as any one to find that he has been the means of pinning this unheard of "sin-eater on to us, and thus injuring our fair fame in the sight of the world. In future editions of " Christmae Evans " (or may be sooner) I trust Mr. Hood will make the *amende honorable* to which we are entitled.— I am, &c., T. EYNON DAVIES, Congregational Minister. Cwmamman, Feb. 4, 1882.

At the time, it seems as if Paxton Hood was in the United States of America, as his response in the *Christian World* of [Thursday 27 April 1882, p7](https://www.britishnewspaperarchive.co.uk/viewer/bl/0004838/18820427/042/0007) :

> Letter from the Rev Paxton Hood
>
> Sir,— Your kindness in inserting my last as a Christmas card, and many expressed wishes, both on this side and yours, to hear from me again in the same way, encourage me to contribute another memory of the season as an " Easter offering." I have been now for two months residing on the spot from whence I date this letter— an immediate and one of the wealthiest suburbs of Boston. Few neighbourhoods can be more enchanting, although I, of course, have not seen it in its splendour, and the variegated gorgeousness of its summer gieries. I should call it a delicious New England village, but Newton is in reality a city, and is familiarly known as the City of Villages ; its population is about 25,000. Some of your readers, and my friends, will be interested to know that not a drop of intoxicating liquor is to be openly purchased in the entire city, excepting at the druggists' for medical purposes. I have visited in most of the representative households of the neighbourhood, and have mingled freely in all the beet society here, and I have not seen in any house anything more intoxicating than ice cream or frozen pudding, through whose huge blocks, however, I have cut my way as through Alpine passes. I am told, however, that shout twenty-five per cent. of the population of the city are not abstainers, and although not a public-house is anywhere to be seen, there are private houses where liquors can be illegally purchased, end only last night a raid was made by the police on seventeen of these, and illicit traffic summarily stopped

His response to Eynon Davies' letter was to go into a holding position:

> I feel that this letter is becoming lengthy; but I must not close it without a reference to some remarks which have been made in the *Christian World*, as to my accuracy in some matters of detail; and especially I would refer to those on the superstition of the *Sin Eater*, mentioned in my " Life of Christmas Evans." Entirely removed as I am from my library, it is clear I cannot here refer to my authorities ; but I did not speak without authority—authority which I am sure all would acknowledge—in the archeology of Welsh superstitions or legends. I will attempt to do both myself and my brotherly critic justice on this matter as soon as I can get at my books after my return to England, which will, I hope, be early in June.
>
> ...
>
> Edwin Paxton Hood.  
> Newton, Massachusetts, U. S. America.  
> April 14, 1882.

A few weeks later, another Welsh reader grudgingly came to Paxton Hood's defence, in the [Thursday 18 May, 1882, p7](https://www.britishnewspaperarchive.co.uk/viewer/bl/0004838/18820518/050/0007) issue of *Christian World*:

> THE "SIN-EATER" IN WALES.
>
> (To the Editor of the Christian World.)
>
> Sir,—Like many another Welshman, I entertained considerable doubt as to the accuracy of Mr. Paxton Hood's statement, in his readable book on "Christmas Evans", respecting the heathenish practice of "sin-eating" in the principality. Regarding myself as tolerably well acquainted with the history and customs of my country, I was quite prepared to look out for and endorse the repudiation of your ministerial correspondent some weeks ago as affecting a certain locality referred to in the book. Since then, however. I find in a magazine article, appearing as lately as the year 1866, an allusion to this very custom. The subject is that of the peculiarities of Welsh funerals, the clergyman officiating at the one specially instanced being a Rev. Mr. Davies, who had for many years acted as secretary to Mr. Pennant, the antiquarian and Welsh historian. This gentleman, in subsequent conversation with the lady-writer, quotes Mr. Pennant as an authority for his statement to this custom, "once general," as he avers, "throughout Wales and the border counties." The form observed on the occasion was this: "The body was laid on the bier outside the house; a plate of salt placed on the breast, and a piece of bread laid on the top of the salt; the bread was handed to the man, styled the ' Sin-eater,' over the corpse, and also a bowl of maplewood which was full of milk, which he drank. He was then presented with a sixpence, and he declared that he took upon him all the sins of the deceased person, and would save him from ' walking' after he was dead." This custom was supposed to have had its origin from the scapegoat mentioned in Leviticus. "There was," he added, "some years ago, a most disreputable old fellow liviing in a wild and lawless district in Carmarthenshire, whom I have heard spoken of as 'Sin-eater,' though I am thankful to say that, for many years, he had not been called upon to exercise his fearful calling." We may reasonably assume from this that Mr. Paxton Hood was substantially correct in his data, though perhaps inaccurate in the specific allusion. I am, &c., M. E. H. Chester. May 11,1882.

Although no mention is made of Eynon Davies' earlier request for a withdrawal, or at least a correction, of the  claim that the sin-eater tradition continued in Cumamman, the [third edition](https://archive.org/details/christmasevansp00hooduoft/page/22/mode/2up?q=sin+eater), published in 1888, does include an additional footnote referring the sin-eater which directs to the reader to *"See Note at end of Chapter, page 39."*, which then proceeds as follows:

> *Note to "Cwm-Aman" page 23.*
> 
> Dr. Thos. Rees, in a letter to the Editor of the *Dysgedydd*, Rev. Herber Evans, says, "That although bred and born within ten miles of Cwm-Aman, he had never heard of this ridiculous superstition."

When the book came to the attention of the editor in *Bye-Gones* of [February 15th, 1882](https://journals.library.wales/view/2092910/2094771/9#?xywh=-1532%2C-191%2C5763%2C3801), p18, it was almost  as if they were keeping a look out for such references. The resulting note can quite easily be read as mocking.

> Mr. Paxton Hood has made a discovery which many more experienced archaeological authorities have sought after, and failed in the search. In a life of the Rev. Christmas Evans, he has recently written, he tells us that there still exists in Caermarthenshire "the Sin Eater," a personage once universal in Wales. We thought that belief was finally scotched in the Academy discussion a few years ago. Such an accommodating official does not and never did exist in Wales, and the only authority (?) for supposing that one ever existed on the borders was old Aubrey, who tells of a "leane, hungry raskel" in Herefordshire.

Several years later, remark was also made in *Cymru Fu*, or to give it its full title, *Cymru fu :  notes and queries relating to the past history of Wales and the border counties*, [Vol I, Part II, p92](https://journals.library.wales/view/2111106/2111178/35#?xywh=-1634%2C-1%2C6151%2C4057), dated February 25th, 1888]:

> SOME OLD WELSH FUNERAL CUSTOMS.
>
> Reading Paxton Hood's *Christmas Evans* — a good book, but inclined to exaggeration— I found the following :— "The superstition of the Sin-Eater is said to linger even now [about 1881] in the secluded Vaie of Cwm-Aman, in Carmarthenshire. The meaning of this most singular institution was that, when a person died, the friends sent for the Sin-Eater of the district, who, on his arrival, placed a plate of salt and bread ön the breast of the deceased person; he then uttered an incantation over thie bread, after which he proceeded to eat it— thereby eating the sins of the dead person ; this done he received a fee of two-and-sixpence. . . Having received this, he vanished as swiftly as possible, all the friends and relatives of the departed aidinj his exit with blows and sticks, and other indications oî their faith in the service he had rendered. A hundred years since, and through the ages beyond that time, we suppose this superstition was everywhere prevaient."
>
> NONCON-QUILL

Three months later, in the issue dated [May 5th, 1888](https://journals.library.wales/view/2111106/2111178/109#?xywh=718%2C463%2C2289%2C1510), p166, a further noted directed readers to Blackwood's Magazine for more details:

> NOTES. THE SIN-EATER
>
> (*ante* Feb. 25. 1888).
>
> I find in a volume of Blackwood's (Nov., 1875) a little more information on this interesting superstition. The writer says :—
>
> 'The Scapegoat is a dark and narrow superstition still surviving in North and South Wales and the Borders. It is hard to say which is the most degraded, the employers or the employed in the transaction. (A man who gains his livíng by such services, is hired when a funeral takes place, is given a loaf of bread and a maple bowl of beer or tnilk, and a sixpence, for which he bears away all the sins of the deceased and prevents him or her walking after death.) The scapegoat in this case is currently called a 'Sin-eater.' Of such it would be no stretch of imagination to believe that like Sion-y-Cuit, the Welsh Faust, they had sold themselves to the devil."
>
> M. E. C. F.

(OEHEL)=
## Charles Elton's *Origins of English history*, 1882

Charles Elton's [*Origins of English history*](https://archive.org/details/originsofenglish00elto/page/176/mode/2up?q=sin), first published in 1882, with a second edition in 1890, was a broad raninging work that amongst other things sought to place various traditions in the context of wider history starting with prehistoric times, and then progressing through the classical period and thence to the "English conquest".

Included in the work, at the end of Chapter VII., p181-2, on *"Pre-Celtic Ethnology"* we have a mention of ancient Welsh cursing wells, followed by a review, based on *British Goblins* of the sin-eater tradition.

> In the same connection we may mention the "Cursing-wells," where the jealous and disappointed might imprecate destruction, as at the Altar of the "Mount of Cursing," on the basket and store of their neighbour, "the fruit of his body and the fruit of his field." It was thought that by performing the rites of an impious service, by casting in a pin or a pebble inscribed with the enemy's name, the spirit of the well would cause the victim to pine and die unless the curse should be willingly removed. [St. Elian's Well in Denbighshire is described as "the head of the Cursing-wells." A full description of the ceremonies will be found in Mr. Sikes' recent work upon the Welsh folk-lore, Brit. Gobl. 355. Among the authorities cited are Camb. Pop. Antiq. 247; Archeol. Cambr. ist Ser. i. 46. Compare Souvestre's account of the Chapel of *Nôtre Dame de la Haine* at Tréguier in Brittany. *"Une chapelle dedice a Notre-Dame de la Haine existe toujoiirs pres de Tregide?; et le peuple n'a pas cesse de croire a la puissance des prieres qui y sont faites. Parfois encore, vers le soir, on voit des ombres honteuses se glisser furtivement vers ce triste édifice place au haut d'un coteau sans verdure. Ce sont des jeunes pupilles lassés de la surveillance de leurs tuteurs, des veillards jaloux de la prosperité d'un voisin, des femmes trop rudement froissées par le despotisme d'un mari, qui viennent la prier pour la mort de l'objet de leur haine. Trois 'Ave' dévotememt répétés, amènent irrévocablement cette mort dans l'année." Derniers Bretons, i. 92. See as to Cursing-stones in Devon and Ireland, N. & Q., 5, v. 223, 363.]
>
> Our last example of these abnormal usages shall be taken from the superstition of the Sin-eater, which certainly prevailed in Herefordshire, though it may be doubtful whether it extended to the neighbouring parts of Wales. "In the County of Hereford," said Aubrey, "it was an old custom at funerals to hire poor people who were to take upon them the sins of the person deceased. The manner was that, when the corpse was brought out of the house and laid upon the bier, a loaf of bread was brought out and delivered to the Sin-eater over the corpse, as also a Mazard-bowl of maple-wood full of beer which he was to drink up, and sixpence in money, in consideration whereof he took upon him *ipso facto* all the sins of the defunct and freed him or her from walking after they were dead." [Aubrey, in the "Remains of Gentilisme," published by the Folk-lore Society; Sikes, British Goblins, 325; Hone, Year-book, 858. "I remember," says Aubrey, "one of these Sin-eaters, he was a long, lean, ugly, lamentable poor rascal, and lived in a cottage on Ross highway. This ceremony, though rarely used in our days, yet by some people was observed in the strictest days of the Presbyterian government."] Mr. Wirt Sikes in his work upon Welsh Folklore, cited an apposite passage from Schuyler's Travels in Turkestan [Turkestan, ii. 28.]: "One poor old man seemed constantly engaged in prayer. On calling attention to him, I was told that he was an '*iskatchi*' a person who gets his living by taking on himself the sins of the dead, and thenceforth devoting himself to prayer for their souls : he corresponds to the Sin-eater of the Welsh border."

```{index} single: Notes & Queries ; correspondence, 1883
:name: NANDQ:1883
```
## Notes & Queries, 1883

A couple of years after *Christmas Evans* was first published, an eagle-eyed, if tardy, correspondent to *Notes and Queries*, [Vol 7 Iss 159, January 13th, 1883](https://archive.org/details/sim_notes-and-queries_1883-01-13_7_159/page/24/mode/2up?q=sin), p25, also picked up on the reference and provided a new note on the matter, directly quoting Paxton Hood and perhaps unaware of previous mentions of the tradition in earlier volumes of *Notes & Queries*, although cognisant of similar other traditions reported elsewhere.

> Welsh Folk-lore: The Sin-Eater.— The following curious scrap of folk-lore occurs in the Rev. Paxton Hood’s book on Christmas Evans, the Preacher of Wild Wales (London, Hodder & Stoughton, 1881) :—
>
> "The superstition of the Sin-Eater is said to linger even now in the secluded vale of Cwm-Aman, in Caermarthenshire. The meaning of this most singular in-stitution of superstition was, that when a person died, the friends sent for the Sin-Eater of the district, who, on his arrival, placed a plate of salt and bread on the breast of the deceased person; he then uttered an incantation over the bread, after which he proceeded to eat it— thereby eating the sins of the dead person; this done, he received a fee of two-and-sixpence—which, we suppose, was much more than many a preacher received for a long and painful service. Having received this, he vanished as swiftly as possible, all the friends and relatives of the departed aiding his exit with blows and kicks, and other indications of their faith in the service he had rendered. A hundred years since, and through the ages beyond that time, we suppose this curious superstition was everywhere prevalent."
>
> Cf. "Old Yorkshire Customs," "N. & Q.," 6th S. vi. 146, 273.
>
> Frederick E, Sawyer. Brighton

```{admonition} Old Yorkshire Customs, *Notes and Queries*, 1882
:class: dropdown
The other notetes referred to are *Notes & Queries* [6th S. Vol 6 Iss 138, August 9th, 1882](https://archive.org/details/sim_notes-and-queries_1882-08-19_6_138/page/146/mode/2up), p146:

> Old Yorkshire Customs,—
>
> A few days ago I received a letter from a friend, who holds the office of coroner in the North Riding, which is worth quoting. He says: "I held an inquest the other day at —— on a man who hanged himself; on the breast of the corpse was a plate of salt— a thing rarely seen now. The object is to scare away evil spirits." Brand mentions the custom as being common in his day in Northumberland, and gives a quotation from Moresin’s *Depravatae Religionis Origo*, 1594, "Salem abhorrere constat Diabolum," &c., which bears out my correspondent's statement as to the motive with which the act was done in this case. Such a survival, in the nineteenth century, of an old custom is curious and deserves placing on record in "N. & Q."
>
>John H. Chapman, F.S.A. Lincoln's Inn.

and [Vol 6 Iss 144, August 30th, 1882](https://archive.org/details/sim_notes-and-queries_1882-09-30_6_144/page/272/mode/2up), p273

> Old Yorkshire Customs (6th S. vi. 146).
>
> The practice of placing a plate of salt on the breast of a corpse is a general one among the labouring classes of Dudley and that district, though there it is done not with the object indicated by Mr. Chapman, but with the idea that it acts as a disinfectant and purifies the apartment. B. R.
>
> The custom to which my friend Mr. Chapman refers is perhaps more common than he supposes. It was followed in my own house some years ago (without my previous knowledge or sanction), but I found that in addition to the plate of salt on the breast there was a larger vessel of salt under the bed on which the corpse was laid. I have always heard that the reason for placing the plate of salt on the breast was that given by Mr. Chapman's correspondent, who is, if I may guess at his identity, well acquainted with North Yorkshire traditions. C. G. C.
Richmond, Yorkshire.
>
> I remember seeing a corpse some twenty years since at Lower Heyford, Oxfordshire, on the breast of which was placed a pewter plate containing salt. On inquiring for what purpose it was placed there the female in attendance said it was to prevent the corpse swelling. G. J. Dew.
Lower Heyford, Oxon.
>
> See the Rev. T. F. Thiselton Dyer's Domestic Folk-lore, pp. 59, 60. F. C. Birkbeck Terry. 

```

The *Notes & Queries* correspondence was also noted in the [January 19th, 1883](https://newspapers.library.wales/view/3336622/3336627/24/), edition of *The Cambrian*, where on p5, a correspondent directly quoted the correspondence:

> Frederick E. Sawyer calls attention in *Notes and Queries* to the following folk-lore, which occurs in the Rev. Paxton Hood's book on "Christmas Evans, the Preacher of Wild Wales":— "The superstition of the Sin-Eater ...

In the [March, 1883 edition, p282](https://archive.org/details/reddragonnation00wilkgoog/page/282/mode/2up?q=sin), of the Red Dragon, Paxton Hood's sin-eater reference is also discussed:

> A correspondent calls attention to a curious scrap of folk lore occurring in the Rev. Paxton Hood's book on *Christmas Evans, the Preacher of Wild Wales* published a couple of years ago. According to the author "the superstition of the Sin-Eater is said to linger even now in the secluded vale of Cwm-Aman, in Carmarthenshire. The meaning of this most singular superstition was that when a person died the friends sent for the Sin-Eater of the district, who, on his arrival, placed a plate of salt and bread on the breast of the deceased person ; he then uttered an incantation over the bread, after which he proceeded to eat it, thereby *eating the sins of the dead person*. This done he received a fee of two-and-sixpence, which we suppose was much more than many a preacher received for a long and painful service. Having received this he vanished as swiftly as possible, all the friends and relatives of the departed aiding his exit with blows and kicks and other indications of their faith in the service he had rendered. A hundred years since, and through the ages beyond that time, we suppose this curious superstition was everywhere prevalent."

In no uncertain terms, Paxton Hood's assertions are refuted:

> It would be difficult to say upon what ground the Rev. Paxton Hood founded the generalisation contained in the last sentence, unless it be that he is neither a close nor a profound reasoner. But what there ought to be no difficulty about is the proof or disproof of the existence of the custom referred to in the vale of Cwm-Aman or in any other part of the Principality.

The author also wonders about the propensity for folk other than the Welsh to introduce notions about Welsh behaviour to the Welsh:

> It is a singular, and by no means creditable fact, that our acquaintance with things happening at our very doors should be so often the result of the observation of strangers.

A plea, of a sort, is then made, for Welsh correspondents to provide further evidence about this tradition:

> Contributions having for their subject any scrap of curious old Welsh customs or folk lore will be always welcome to the editor of the National Magazine. Perhaps in this matter of the "Sin-Eater," of which we should like to obtain other and more authentic information than the Rev. Paxton Hood can give, some correspondent, like "Tal-a-hên," may come to our rescue.

It would be useful to know what sort of contributor *Tal-a-hên* was to know whether this plea is entirely serious!

The article was remarked upon in *Bye-Gones* of [March 14th, 1883](https://archive.org/details/byegonesrelating1882unse/page/204/mode/2up?q=sin), p205:

> Current Notes
>
> Dr. Ollivant, the late Bishop of Llandaff, forms the subject of the memoir and portrait in the Red Dragon for March. ... That disreputable old fellow, "The Sin Eater," who we thought was killed long ago, has, it seems, only been scotched, for he crops up again in the number before us !

In the [Vol 7 Iss 174, April 28th, 1883](https://archive.org/details/sim_notes-and-queries_1883-04-28_7_174/page/334/mode/2up) edition of *Notes & Queries*, p334, in a contribution relating to *"Welsh Folk-Lore"*, and indexed as such, guides readers to Leland's *Collectanea*:

> Welsh Folk-Lore : the Sin-Eater (6th S., vii. 25).—I have just stumbled on the following passage in Leland’s *Collectanea*, vol.i. p. lxxvi (ed. 1774), *à propos* of this matter :—
> 
> "Within the memories of our fathers in Shropshire in thore villages adjoyning Wales, when a Person dyed, there was notice given to an old Sire (for so they call'd him) who presently repair'd to the place where the deceased lay and stood before the Door of the House, when some of the Family came out and furnished him with a Cricket on which he sat facing the Door. Then they gave him a Groat which he put in his Pocket, a Crust of Bread which he eat, and a full Bowle of Ale which he drank off at a draught. After this he got up from the Cricket and pronounced with a composed gesture, 'The ease and rest of the Soul departed, for which he would pawn his own Soul.' This I had from the ingenious John Aubrey, Esq.; who made a collection of curious Observations, which I have seen, and is now remaining in the Hands of Mr. Churchill the Bookseller."
> 
> I have since looked through Aubrey's Miscellanies, but find no mention of the subject.
> W. B. N.

This correspondence is picked up on in note from [Vol 8 Iss 196, September 29th, 1883](https://archive.org/details/sim_notes-and-queries_1883-09-29_8_196/page/254/mode/2up), p255, which provides further references already familiar to us, along with a reference to a possibly relevant illustration, although I have not, as yet, been able to find a scanned version of that illustration:

> Welsh Foik-Lore: the Sin-Eater (6th S., vii. 25, 334).—See Hone’s *Year Book*, col. 858, where the passage from Leland’s *Collectanea* quoted by W. B. N. is given as forming part of a letter from John Bagford, dated 1715; and where the reader is also referred to the Lansdowne MSS. in the British Museum for statements concerning sin-eating in Aubrey's own handwriting. The subject was briefly discussed in "N. & Q.," 1st S. iv. 211, a correspondent being referred by the editor to Ellis's edition of Brand's *Popular Antiquities*, vol. ii. p. 155, for information under this head. The custom has, I suspect, been passed over intentionally by the Rev. Peter Roberts in his Cambrian Popular Antiquities, 8vo, 1815; but an aquatint illustration at p. 177 of that work presents us with the ceremony of dispensing food and drink over the coffin to a man who, receives ate kneeling upon one knee. Pennant says that
>
> "it was customary when the corpse was brought out of the house and laid upon the bier for the next-of-kin, be it widow, mother, sister, or daughter (for it must be a female), to give, over the coffin, a quantity of white loaves in a great dish, and sometimes a cheese with a piece of money stuck in it, to certain poor persons. After
that they presented in the same manner a coup of drink, and required the person to drink a little of it immediately."
>
> This seems to indicate a form of "sin-eating."
>
> ALFRED WALLIS.

A second piece of correspondence under the same header references Aubrey:

> John Aubrey has three passages concerning sin-eaters in his *Remaines of Gentilisme and Judaisme*, which was edited and most excellently annotated by Mr. James Britten for the Folk-lore Society in 1881. The passages occur at pp. 19, 24, 35.
> 
> Edward Peacock.  
> Bottesford Manor, Brigg.

References to Paxton Hoods work continued to have echoes into the 1890s. In a somewhat hotch-potch letter to the editor of *The Cambrian* dated [October 16th, 1891](https://newspapers.library.wales/view/3339249/3339256/62/), p7, correspondent *H.* wrote in the *Welsh Notes From Notees and queries* section:

> ...
>
> ... E. L. Blenkinsopp remembers that he read of an Englishman who went into a church in Wales, where, during the sermon, whenever the devil was named the people spat, as expressing abhorrence. Paxton Hood, in his book on Christmas Evans, gives an account of the Sin-Eater, a superstition which is said "to linger even now in the secluded vale of Cwm-Aman, in Carmarthenshire." The district has (or better, perhaps, had) a Sin-Eater, who, on the death of a person, was sent for, and be, on his arrival, placed a plate of salt and bread on the breast of the deceased. He then uttered an incantation over the plate, and afterwards proceeded to eat the bread, and this done, he was supposed to have eaten the sins of the dead person. After receiving a fee of two-and-sixpence for his services, be hurriedly departed, aided by the cuffs and kicks of those in the house. This curious custom was formerly observed in Yorkshire and elsewhere.
> ...
>
> H.

A correspondent from London replied in the edition of [October 30th, 1891](https://newspapers.library.wales/view/3339267/3339270/19/), p3, recalled another traditional tale:

> OLD-WORLD SUPERSTITIONS.
>
> TO THE EDITOR OF "THE CAMBRIAN."
>
> Sir,- The remarks made by "H," in his letter referring to the sin-eater," spoken of by Paxton Hood in his book on Christmas Evans, clear up a mystery which has puzzled me for years, whenever my mind has reverted to it. It would probably be twenty years ago, I cannot remember the exact date, but no doubt many in Swansea will remember the circumstance, that Mrs. Hopkins, an old Swansea resident, and mother of the late Mr. Thomas Hopkins, at the time a member of the Swansea Town Council, died suddenly at her residence in High-street - her husband kept a small public-house there, the name of which I also forget. I was one of the first to enter the dwelling after the sad event, and my first view of the corpse, was to find the deceased, fully dressed (just as she was carried upstairs from the bar where she died) lying on her back in bed, on her breast being placed a plate, pewter I think it was, and on the plate were sprinkled crumbs of bread and some salt. The deceased could scarcely have been dead a quarter of an hour when I saw this, and I could never understand why the plate and its contents were placed where I saw them. I subsequently sat on the inquest, and intended to make inquiries into what struck me as curious, but fearing to pry unnecessarily into domestic susceptibilities, I refrained from doing so. I now find, from the letter of "H." in last week's Cambrian, what I never knew before, that the circumstance of the plate, salt, and bread had reference to the old Welsh superstition spoken of by Paxton Hood in his book already referred to, and fully explained in the interesting letter to which I now allude. If my memory serves me, I think the Hopkinses were a Cardigan family, but of this I am not quite certain.-Yours, &c.
>
> J. C. MANNING. London.

```{index} single: Bye-Gones ; articles, 1882-3
:name: BYGNS:1882-3
```
## Bye-Gones, 1882-3

```{index} double: Bye-Gones ; Popish Ceremonies Existing in Wales
:name: BYGNS:popish
```
A series of articles on *Popish Ceremonies Existing in Wales*, over several issues of Bye-Gones ([May 17th, 1882, p64-5](https://journals.library.wales/view/2092910/2094824/5#?xywh=-1532%2C-117%2C5763%2C3800), [June 7th, 1882](https://journals.library.wales/view/2092910/2094841/#?xywh=-464%2C207%2C4906%2C3235), [July 5th, 1882](https://journals.library.wales/view/2092910/2094856/#?xywh=-1532%2C-369%2C5763%2C3801), [July 12th, 1882](https://journals.library.wales/view/2092910/2094856/2#?xywh=-860%2C-91%2C4002%2C2639)) describes various Catholic rituals.

The first installment opens with claim of the continued practice of Catholic ceremonies, and goes on to offer a consideration of death and burial rites:

> POPISH CEREMONIES STILL EXISTING IN WALES.
>
> The Rev. Canon Richards said, in his lecture at St. Joseph's, Swansea, on the recent Church Congress, that the old faith, or Popery, still lingers in men's hearts and memories, and that even now the people retain in Wales many practices once belonging to the old religion. That this is so amongst the members of the Established Church is an acknowledged fact, but that such practices still exist amongst the Welsh Nonconformists may at the first be questioned. I have long observed these strange but contradictory rites with no small interest, and possibly the pointing of them out may lead others to the same line of observation.
>
> I will first confine myself to death and burial rites. We have much that surrounds these events that must have come down to us from the times when the holy fathers were the masters of the ceremonies.

No mention is made of the sin-eater, but we do see several rituals described that we have mant in related forms previously. For example, the *wake*:

> *The Gwylnos*, or watchnight, or "Wake," is still an important service in some parts of Wales, and the form of procedure varies in several localities. This takes place on the night preceding the funeral. The neighbours and friends meet about 7 p.m. in the room wherein the body has been laid. The walls of the chamber or room being covered over with linen sheets with laurel leaves pinned on to the sheets, two leaves so placed that they take the form of the letter T or a cross, at the head and feet of the body are placed a lighted candle. In a Nonconforming neighbourhood on the borders of Pembroke, Cardigan, and Carmarthen counties, it was customary up to within 30 years, to put a lighted candle on a plate placed on the chest of the body during the *Gwylnos*, whilst placing a plate full of salt on the body was pretty general in Montgomeryshire at one time. When the friends had arrived a portion of Scripture was read and hymns sung, and prayers offered alternately with the hymns ; when, about 9 o'clock, after several friends had offered up prayer, the *Gwylnos* closed, and the friends returned to their several homes. To bury without a *Gwylnos* was considered a mark of great disrespect to the relatives and to the departed.

The offering of prayers, as well as doles, is also described:

> When Anne Griffiths of Dolwar fach, the great hymnologist, attended a funeral of a relative of the writer's she at once proceeded to the room where, on a bed, the body lay, When kneeling at the bedside she offered up a long silent prayer. At the same funeral the husband of the departed one caused a near relative to distribute a large sum of money amongst the poor people that had come to receive the dole that was thus divided previous to the "lifting of the body;" otherwise taking the body from the house to be buried. It is also customary to read a portion of Scripture and to pray, the body having been first brought from the room and placed on chairs, or on the bier at the door of the house.

Funeral processions and the church funeral service also get a mention, along with a note about payment made to the priest at the end of the service:

> On starting from the house the company of mourners raise up their voices in a mournful hymn, and they continue singing for some distance as they leave the house. On approaching the church another hymn is sung, until the body is borne near to the Lych gate, where the officiating minister meets the funeral procession, the bells, as the funeral approaches the church, ringing the funeral toll. After the service is concluded in the church, the friends make an offering to the clergyman, this being made on a special table fixed to the altar railing.

Graveside rituals are then considered, along with an after-party:

> At the grave, again, another offering is made, on the sexton’s spade. Every one attending where the offering custom prevails is expected to uphold, as in duty bound, the usage, by contributing his quota. Formerly on retiring from the grave, which had been decorated with the laurel and box evergreens, friends retired to the village ale-house, sometimes called the "Church House," or "Ty'n-y-llan," where it was the custom to drink the "funeral ales" to the comfort of the relatives and the profit of the landlord, who, in no very remote times, was commonly the parish clerk.

Ritural observances continued even in the week or weeks after the burial:

> The first Sunday following the burial of the dead was called the "funeral Sunday," or the "second burial Sunday," when a special service was held, a funeral sermon delivered, and the departed largely received the encomiums of the minister, and the relatives were publicly "prayed for." At the close of the service I have known the relatives go to the grave, and there kneel for some time.

Rituals associated with watching over the body are also described:

> Another ceremony of some peculiarity, but now nearly obsolete, is *Gwylio y Corph* (watching the body). This is simply the sitting up all night in the room wherein the body is laid, of one or more of the neighbours who volunteers to do this duty. And this is done each succeeding night from death until burial. Drink at one time must have been freely supplied to the *Gwyliwr*, or watchman, hence the adage, "Hawdd yf a wyl ei wely." "He who watches his resting place will drink freely."

It seems that a special funeral cocktail might also have been customary, as were "funeral cakes":

> So much was the "drink" considered as part of the ceremonies at death and burial, that a special drink — strong home-brewed ale, strongly flavoured with spice and lemon — was provided, in a special vessel called a tankard. This was "served" with the "funeral cakes" just before starting with the body from the house. The Rev. W. Maddock Williams, in his interesting sketch of the parish of Llanfechain says, in reference to this custom, in describing the sacramental vessels belonging to the church, "It had long been the custom to permit it (the large flagon) to be used at funerals in the parish, for the purpose of handing out to each of the attendants on the occasion the spiced drink, wine or ale, as the case may be. Such a desecration of the sacred vessel was peremptorily resisted by the present Rector (the Rev. M. Williams) at his entrance upon the incumbency, but not without his incurring much obloquy, and giving much offence." (Mont: Coll: vol. v.)
>
> Gypt.
>
> (To be continued).

It is perhaps also worth noting here the tradition of "bride ale".

```{admonition} Bride Ale
:class: seealso

For example, Brand's [*Popular antiquities*](https://archive.org/details/b29328561_0002/page/142/mode/2up?q=bride+ale), 1849 edition, p143

> Bride-ale, bride-bush, and bride-stake are nearly synonymous terms, and all derived from the  circumstance  of the bride's selling ale on the wedding-day, for which she received, by way of contribution, whatever handsome price the friends assembled on the occasion chose to pay her for it. The expense of a bride-ale was probably defrayed by the relations and friends of a happy pair, who were not in circumstances to bear the charges of a wedding-dinner.

```

Sometimes you just have to wonder about the propensity to just "retweet" based on recent exposure to a topic, either contemporary or historical, that has been covered repeatedly, and described in various indices, but of which certain correspondents are unaware. And so it is that in *Bye-gones* of [April 25th, 1883](https://archive.org/details/byegonesrelating1882unse/page/222/mode/2up?q=sin), p223, we get the following query:

> THE SIN EATER.
> 
> You have more than once referred to the practice of Sin-Eating in Wales and the Borders, as resting only on the authority of Aubrey, and totally discredited by modern Welshmen. In an article I recently referred to as appearing in the *Oswestry Advertizer* for Sep. 22, 1858, something akin to the custom is mentioned, by an intelligent correspondent, who describes the custom as ancient. He says "Previous to a funeral, it was customary when the corpse was brought out of the house, and laid upon the elor, or bier, for the next of kin, be it widow, mother, sister, or daughter (for it must be a female) to give over the coffin a number of white loaves, in a great dish, and sometimes a well-made Welsh cheese, with a piece of money stuck in it, to certain poor persons. After that they presented in the same manner a cup of drink, and required the person to drink a little of it immediately. When that was done all knelt down, and the Minister, if present, repeated the Lord’s Prayer." Any reader who could quote his father or grandfather as an actual witness of a ceremony such as this, or even an approach to it, would confer a boon on Welsh Archaeology !
>
> H. B.

*There do not appear to be any archived copies of the Oswestry Avertiser available for 1858 in the British Newspaper Archive.*

Correspondence then continued in the [May 9th, 1883 issue](https://archive.org/details/byegonesrelating1882unse/page/232/mode/2up?q=sin), pp233-4

> REPLIES.
>
> THE SIN EATER IN WALES (April 25, 1883.)
>
> The question has been asked in Bye-gones if some of the funeral customs within the memory of those now living do not point to a more pronounced ceremony on the part of our forefathers ? One writer states — but only on hearsay — that last century it was usual, when the corpse was brought out of the house, and laid upon the *Elor*, or bier, for the next of kin of the feminine gender "to give over the coffin a number of white loaves, in a great dish, and sometimes a Welsh cheese with a piece of money stuck in it, to certain poor persons. After which a cup of drink was presented also over the coffin, of which a little was to be drunk immediately. When this was done the minister knelt down and said the Lord’s Prayer." No one has corroborated this from the definite information of father or grandfather ; but they have spoken of a more modified form of, perhaps, the same ceremony, within their own recollection. Less than half a century ago it was usual at every 'respectable' funeral to have made up into packets, a couple of bits of cake — one of rich plum, and the other plain — wrapped in black-edged paper and sealed with black wax. One of these was presented to each of the invited guests, who took it home unopened. At funerals of less pretention a "large round biscuit, the size and form of an ordinary tea-saucer, inverted, took the place of the packet of cake. These were 'served' to each of the parties attending the funeral (by one of the most respectable men present) on a tray called the 'Hand-board,' or 'Server.' The ceremony was gone through just before 'Raising the Body.' After this the 'Tankard' of hot-spiced ale was offered to each person present. This was made of pewter, and had a lid : everyone was expected to take a sip." In narrating this in Bye-gones of May 17, 1882, the writer also called attention to a note in the history of the parish of Llanfechain, published in *Mont : Coll :* in 1872. He became rector in 1851, and found it was usual to allow one of the sacramental vessels a silver flagon presented to the parish in 1691) to be used in place of the customary tankard — a custom he at once denounced, to the no small chagrin of the parishioners ! How far these customs form a lingering remnant of the Sin Eater, your readers must judge for themselves.
>
> R. Rosse Tewk, B.A.

```{admonition} Revd. Maddock Williams in *Montgomeryshire Collections* ("Mont: Coll: vol v."), 1872
:class: dropdown

https://books.google.co.uk/books?id=zMNAAQAAMAAJ&pg=PA235#v=onepage&q&f=false

Placing the quote by Revd. Maddock Williams in its full context in volume V of the Pwys Land Clu b *Collections historical & archaeological relating to Montgomeryshire and its borders* published by the Powys-Land Club* of 1872, we refer to the article
*"A Slight Historical and Topographical Sketch of The Parish of Llanfechain, in the County of Montgomery", p234-5:

> The sacramental vessels belonging to the church are of a better order than are generally to be found in old parishes. They consist of (1) a handsome and massive silver flagon, calculated to contain about three pints, with an appropriate lid. It is inscribed "Ex on Oweni Lyod, Rectoris de Llanfechen, 1691;" (2) a good silver chalice with a cover, constituting a convenient paten. It has the following inscription on it:– "The gif of Mary Kynaston, the daughter of Humphrey Kynaston, of Bryngwyn, Esq.;" (3) a fair sized silver plate given by Mrs. Mary Roberts, and inscribed, "Ex dono M.R., 1682;" and (4) a small silver chalice, inscribed "The Cup of Llanfechain." This last has been much battered, the injuries having in all probability been occasioned by its conveyance to and fro for the adminisatration of the Holy Communion to the sick and aged. Whether this was the chalice enumerated in the terrier returned in A.D. 1705, and represented as having a *covering to it*, cannot now be ascertained. All account of such a chalice is wanting in the terrier, A.D> 1774; but it was found here, such as it is, by the present rector, but without any *covering*.
> 
> A curious fact connected with the large flagon must be here adverted to. It had long been the custom to permit it (the large flagon) to be used at funerals in the parish, for the purpose of handing out to each of the attendants on the occasion the spiced drink, wine or ale, as the case may be. Such a desecration of the sacred vessel was peremptorily resisted by the present Rector at his entrance upon the incumbency, but not without his incurring much obloquy, and giving much offence."
```

```{index} single: Rhys, John ; editor, Tours in Wales, 1883
```
(TIWPN:1883)=
## Pennant's *Tours in Wales*, Edited by John Rhys, 1883

We have already brifly alluded to the work of John Rhys, the original Jesus Professor of Celtic at the University of Oxford and a founding Fellow of The British Academy; his name is memorialised by the [Sir John Rhys Memorial Lectures](https://www.thebritishacademy.ac.uk/events/lectures/listings/sir-john-rhys-memorial-lectures/), first delivered in 1925, which are still presented to this day, by way of his two volume work *"Celtic Folklore: Welsh and Manx"* in 1901.

```{admonition} Sir John Rhys
:class: seealso dropdown

https://en.wikipedia.org/wiki/John_Rhys
https://en.wikipedia.org/wiki/Jesus_Professor_of_Celtic

```

Rhys also published several other works, including an edited version of Pennant's [*Tours in Wales with notes, preface, and copious index*](https://archive.org/details/toursinwales03penn/page/150/mode/2up?q=funeral) of 1883.

One section, at pp150-1, reviewed religious customs, perhaps notably *without* reference to the sin-eater tradition:

> Previous to a funeral, it was customary, when the corpse was brought out of the house and laid upon the bier, for the next of kin, be it widow, mother, sister, or daughter (for it must be a female) to give, over the coffin, a quantity of white loaves, in a great dish, and sometimes a cheese, with a piece of money stuck in it, to certain poor persons. After that they presented, in the same manner, a cup of drink, and required the person to drink a little of it immediately. When that was done, they kneeled down; and the minister, if present, said the Lord's Prayer: after which, they proceeded with the corpse; and at every cross-way, between the house and the church, they layed down the bier, knelt, and again repeated the Lord's Prayer; and did the same when they first entered the church-yard. It is also customary, in many places, to sing psalms on the way; by which the stillness of rural life is often broken into, in a manner finely productive of religious reflections.
>
> To this hour, the bier is carried by the next of kin; a custom considered as the highest respect that filial piety can pay to the deceased. This was a usage frequent among the *Romans* of high rank; and it was thought a great continuance of the good fortune which had attended *Metellus Macedonicus* through his whole being, that when he had, in the fulness of years, passed out of life by a gentle decay, amidst the kisses and embraces of his nearest connections, he was carried to the funeral pile on the shoulders of his four sons [*Valer. Max. lib. vii. c. i.*]; and, let me add, that each of them had enjoyed the greatest offices of the commonwealth [*Pliaii, Hist. Nat. lib. vii. c. 74.*].
>
> Among the *Welsh* it was reckoned fortunate for the deceased if it should rain while they were carrying him to church, that his bier might be wet with the dew of heaven.
>
> In some places it was customary for the friends of the dead to kneel, and say the Lord's Prayer over the grave, for several *Sundays* after the interment; and then to dress the grave with flowers.

```{index} single: Burne, Charlotte S. ; editor, Shropshire Folk-lore, 1883-5
:name: SHFLK
```
## Shropshire Folk-lore, 1883-1885

With a [first part](https://archive.org/details/shropshirefolkl00burngoog/page/n20/mode/2up) published in 1883, a [second part](https://archive.org/details/shropshirefolkl00jackgoog/page/n150/mode/2up?q=sin-eater) in 1885, and a [third part](https://archive.org/details/shropshirefolkl01jackgoog/page/n14/mode/2up) in 1886, *Shropshire Folk-Lore – A Sheaf of Gleanings* was an edited work by Charlotte S. Burne based on the collections of Georgina Frederica Jackson, compiler of the [Shropshire word-book](https://archive.org/details/shropshirewordb01jackgoog), *"a glossary of archaic and provincial words, etc., used in the county"* in 1879.

A review from the *Saturday Review* of Part II of the work was rerprinted in the [April 29th, 1885](https://journals.library.wales/view/2092910/2095345/17#?xywh=59%2C1879%2C2588%2C1707) edition of Bye-gones, p209-11:

> SHROPSHIRE FOLK-LORE.
>
> The following interesting review of Part II. of Miss Burne's "Shropshire Folk-Lore" has appeared in the Saturday Review :— Inexperienced people might suppose that, the necessary materials being given, it would be easy to write an entertaining book on folk-lore ; but this is far from being the case. It is almost as difficult to make a book of folk-lore readable as a book of anecdotes or a book of jokes, and, at best, the folk-lore book is more useful as furnishing materials for historians, novelists, and poets, than as a book to be read at first hand by those who wish to be entertained. It is interesting enough to read of a local superstition, but a superstition with variations soon becomes wearisome. Yet the faithful compiler of a work on folk-lore is obliged to explain that in one part of the country it is considered unlucky to see one magpie, while in another it is unlucky to see two ; that in some places three, and in others four, foretell the birth of a boy ; that four augur a wedding, according to certain authorities, and a death according to others, and that it is a question whether all these prognostications are not upset by a wise saying which begins "One for anger, two for luck," and so on. Furthermore he has to state that there are experts who consider the superstitions about magpies equally applicable to crows. Of this sort of reading it is possible to have too much ; but the unlucky folk-lore-monger is bound to produce every variety of his wares, unless he wishes to hear his work called incomplete. The merciful critic is inclined, therefore, to take up a book of folk-lore with feelings of charitable pity for its author. He would be even more sorry for himself if he thought he were going to read it through; but of doing this he rarely has any intention, as a book of folk-lore is easily reviewed by a little dipping and a good deal of skipping. The author of the specimen before us, however, has done her work so well that she has no need to ask mercy from her critics, and her reviewer who comes to skip will stay to read.
>
> ...
>
> [p210-11]
>
> Miss Burne observes that Shropshire people still have a superstition that the croaking of a raven portends death, particularly if the raven flies over a house. She would have been confirmed in her opinion if she had heard an old Shropshire servant consoling her invalid master, with whom she was sitting up one night, by informing him that he would soon be in heaven because on the previous day she had heard a raven crying "corpse, corpse," as it flew over the house. The greater part of the folk-lore collected in this volume is connected with deaths, diseases, and weddings. With regard to the former, there is certainly no exaggeration in the remark that "thirty or forty years ago it was no very uncommon thing among the more ignorant folk to take the pillow from under a sick person's head (after the fashion of Mrs Gamp) 'to make him die the easier.'" The thirty or forty years might have been left out, and, unless we have been greatly misinformed, the pillow has not only been taken from under a sick Salopian's head, but held tightly over it afterwards, with the laudable intention of "helping him to die." Those who have had much to do with the Shropshire poor will not be altogether disinclined to believe a story given in a foot-note which might try the credulity of the inhabitants of other counties. "An old man at Baschurch," we are told, had been " very ill, but in no immediate danger of death." The curate was, therefore, rather surprised one day at finding the patient dead ; but his affectionate widow volunteered the following account of his demise :— "He tried so hard, but he couldna die ; he tried an' tried, but he couldna, so I got a piece o' tape an' put it roun' his neck an' drawed it tight, an' he went off like a lamb." A Shropshire rector once told us that he had called on a dying parishioner, and had scarcely begun a conversation with him when his wife begged him to talk to her instead, saying to her husband, " Now don't you waste your time talking ; you get on with your dying."
>
> ...
>
> Miss Burne's book on the folk-lore of Shropshire would not have been complete if she had made no mention of the tradition of the Sin-eater— a poor man who, for a small consideration, is said to have been ready to take upon himself the responsibility of all the sins of any dead person; but she very properly adds that the authorities in support of this tradition are somewhat questionable. Shropshire and Welsh archaeologists have fiercely contested the question whether any such custom ever existed, and antiquaries must be content to leave the matter open.
>
> Miss Burne very often quotes and refers to a work called *Bye-Gones*, which was edited by Mr Askew Roberts, "than whom," she tells us, "few men could be more respected in life or regretted in death." This book consists simply of reprints from a column devoted to notes, queries, and replies about folk-lore in the *Oswestry Advertizer*, a cleverly edited Liberal newspaper, well known in Shropshire and North Wales. The example set in this respect by the *Oswestry Advertizer* is well worthy of imitation by other local newspapers, for *Bye-Gones*, of which there are now many volumes, is itself a very valuable book of folk-lore, and if in every county in England the editor of a newspaper would employ somebody on a work of this kind, an immense amount of interesting and valuable information might be amassed. There are other books besides *Bye-Gones* and her other quoted authorities which we think Miss Burne might have found useful and so many local customs owe their origin to religious rites and uses of pre-Reformation periods that she would have done well to have had by her a good work on ecclesiastical customs and popular religious practices, subjects with which she does not seem familiar. We wish, too, that she had had the opportunities—opportunities hard to get—of learning the private ghost-stories of the Shropshire country houses; for the county is rich in such legends, but its inhabitants are very reticent in communicating them to strangers.
>
> Much of the folk-lore attributed here to Shropshire is common to other counties ; but it would be impossible to sift out what is exclusively Salopian. Such customs as the giving back of a small sum on a purchase for luck, pinching for new clothes, decorating churches, and the observance of May Day, are equally well known in other parts of England, and many of the superstitions noticed in this volume must be familiar to every body; but upon the whole this second part of Miss Burne's work is written with great ability; it ought to find a place in every library in Shropshire, whether public or private, and an inhabitant of any English county would be hard to please if he could not find a good deal in it both to amuse and interest him. A third part has yet to be published treating of several important subjects connected with folk-lore. We are also promised some addenda and corrigenda, and, best of all, an index— a most important matter in a work of this kind. Miss Burne apologizes for the delay in the appearance of the second part; but, as she herself admits, "the work has gained thereby," for when a well-disposed antiquary reads a book about the folk-lore of his own neighbourhood, he is tempted to send some additional information to the writer, and he generally yields to this temptation. Our advice, therefore, to the author of *Shropshire Folk-lore* is not to be in a hurry about publishing the third part.

Referring to the text of Part II, we see that various death customs are described, including various food rituals p306:

> This distribution of 'cakes and ale' at funerals is often alluded to in old writings.
>
> 'Deal on, deal on, ye merry men all,  
> Deal on your cake and your wine ;  
> Whatever is dealt at her funeral to-day  
> Shall be dealt to-morrow at mine.'
>
> *Fair Margaret and Sweet William*; PERCY, Reliques.

```{admonition} Thomas Percy, *Reliques of ancient English poetry*, 1765
:class: seealso dropdown
Thomas Percy's *Reliques of ancient English poetry: consisting of old heroic ballads, songs, and other pieces of our earlier poets, (chiefly of the lyric kind.) Together with some few of later date* was a three volume work originally published in 1765 ([volume 1](https://archive.org/details/reliquesancient06percgoog/page/n8/mode/2up), [volume 2](https://archive.org/details/reliquesancient00dodsgoog), [volume 3](https://archive.org/details/reliquesancient35percgoog/page/n7/mode/2up)), and republished in several editions in the years thereafter.

A folio manuscript edition, s *Bishop Percy's folio manuscript. Ballads and romances*, edited by John W. Hales, M.A. and Frederick J. Furnivall, M.A., was published in 1867 in three volumes ([volume 1](https://archive.org/details/bishoppercysfol03percgoog/page/n10/mode/2up), [](https://archive.org/details/bishoppercysfol00percgoog/page/n10/mode/2up), [third volume](https://archive.org/details/bishoppercysfol01percgoog/page/n10/mode/2up)).
```

Burne observes that many of the customs may have taken the form of doles:

> Anciently, the food and drink were 'dealt' not so much by way of a refreshment for the mourners, as of a gift to the poor to purchase their prayers for the departed soul. At other times the dole consisted of money, collected from all the attendants at the funeral, and afterwards bestowed upon the poor. This custom prevailed in Shropshire as late as 1723. In that year Sir John Wolryche of Dudmaston (Sheriff of Shropshire in 1716) was drowned in the Severn near his own house. The amount of the 'dole-money' collected at his burial was unusually large, and so grateful was it to his mother's feelings, as an expression of respect to her son's memory and sympathy with herself, that while she gave an equal sum to the poor, she preserved the actual coins given at the burial, laid upon the broad dish on which they had been offered, by her bedside to the day of her death, in 1765, forty-two years after the death of her son, and sixty-four after that of her husband. `[Blakeway, Sheriffs of Shropshire (1831), p. 170. Mr. Blakeway says these offerings were still customary in North Wales when he wrote, but they seem (see Brand, *Antiquities*, II. 208) to have there been made rather for the benefit of the parson than of the poor. No doubt they were once intended to purchase masses for the repose of the soul of the deceased.]`

The practice of the sin-eater is represented as a particularly gruesome variant of this tradition, and is accepted, on trust, from Aubrey:

> One very curious and repulsive outgrowth from the custom of funeral doles must here be noticed, as by some it has been set down as a Shropshire practice. I mean the well-known account of the Sin-eater, taken from Aubrey's *Remains*, in which, let me point out, there is no reference made to Shropshire at all, I will quote the passage in full.

The *Sinne Eaters* section of *Remaines of Gentilisme*, presumably taken from Britten's edited 1881 edition, is then reprinteds.

```{admonition} *Shropshore folk-tales*, quoting Aubrey, *Remaines of Gentilisme*
:class: dropdown
> SINNE-EATERS.
> 
> 'In the County of Hereford was an old Custome at funeralls to (hire) have poor people, who were to take upon them all the sinnes of the party deceased. One of them I remember lived in a cottage on Rosse high-way. (He was long, leane, ugly, lamentable poor raskel.) The manner was that when the Corps was brought out of the house and layd on the Biere, a Loafe of bread was brought out, and delivered to the Sinne-eater over the corps, as also a Mazer-bowle of maple (Gossips bowle) full of beer, whch he was to drinke up, and sixpence in money, in consideration whereof he tooke upon him (*ipso facto*) all the Sinnes of the Defunct, and freed him (or her) from walking after they were dead. This custome alludes (methinkes) something to the Scapegoate in ye old Lawe.  Leviticus, cap. xvi. verse 21. 22. ... This Custome (though rarely used in our dayes) yet by some people was (observed) continued even in the strictest time of ye Presbyterian government : as at Dynder, volcns nolens the Parson of ye Parish, the (kinred) relations of a woman deceased there had this ceremonie punctually performed according to her Will : and also the like was donne at ye City of Hereford in these times, when a woman kept many yeares before her death a Mazard-bowle for the Siune-eater ; and the like in other places in this Countie; as also in Brecon, e. g. at Llangors, where Mr. Gwin the minister about 1640 could no hinder ye performing of this ancient customme. I believe this customme was heretofore used over all Wales.
> 
> 'See Juvenal Satyr. VI. (519 — 521), where he speakes of throwing purple thread into ye river to carry away ones sinne. In North Wales, the sinne eaters are frequently made use of ; but there, insted of a Bowle of Beere, they have a bowle of Milke. Methinkes, Doles to Poore people with money at Funeralls have some resemblance of that of ye Sinne-eater. Doles at Funeralls were continued at Grentlemens funeralls in the West of England till the Civil-warre. And so in Germany at rich mens funeralls Doles are in use, and to every one a quart of strong and good Beer. — Cramer.' `[Aubrey, *Remains of Gentilisme and Judaisme* (F. L. S.), p. 35.]`
```

The identification of the tradition with *Shropshire* is laid squarely at the hands of Bagford:

> The connection of this custom with Shropshire rests on the authority of John Bagford, whose letter on the subject is dated Feb. 1st, 1714 — 15. He says, 'Within the memory of our Fathers, in Shropshire, in those villages adjoyning to Wales, when a person dyed, there was notice given to an old Sire (for so they called him) who presently repaired to the place where the deceased lay, and stood before the door of the house, when some of the Family came out and furnished him with a Cricket, on which he sat down facing the door. Then they gave him a Groat, which he put in his pocket ; a Crust of Bread, which he eat ; and a full bowle of Ale, which he drank off at a draught. After this, he got up from the Cricket and pronounced, with a composed gesture, *the ease and rest of the Soul departed, for which he would pawn his own Soul*. This I had from the ingenious John Aubrey, Esq., who made a Collection of curious Observations, which I have seen, and is now remaining in the hands of Mr. Churchill, the bookseller.' `[Leland's *Collectanea*, ed. Hearne, p. lxxvi. Quoted in BRAND, *Antiquities*, II. 198.]`

However, doubt is raised as to the veracity of the claim:

> It will be seen that Bagford is therefore but a second-hand authority, whose account was committed to writing some thirty years after Aubrey's own. It is singular, to say the least of it, that no other writer has ever even alluded to such a practice. `[But in 1852 Mr. Matthew Moggridge of Swansea asserted at the Cambrian Archaeological Society's Annual Meeting, that the custom had then been recently practised in the parish of Llandebie, Caermarthenshire. See Wirt Sikes, *British Goblins*, p. 826.]` Aubrey has always been noted for his romance and credulity, yet it seems hardly possible that he could have misunderstood a matter which he relates so circumstantially and apparently from personal knowledge. It is easier to believe that in some wild and remote places the custom of giving doles to the poor was kept up after the precise nature of the benefit to the soul of the dead man (expected in pre-Reformation days) had been forgotten, and that among ignorant people it was corrupted into the debasing superstition which Aubrey describes. But Salopians will be slow to believe that his story concerns their county until further evidence be forthcoming.

The commentary then proceeds to other, more recent instances, of funeral dole traditions:

> Much later than Aubrey's time, the funeral dole survived in North Wales in its more primitive and innocent form. Pennant in his *History of Whiteford* describes the nearest female relative of the dead giving bread, cheese, ale, and money to the poor over the coffin, and Mr. Wirt Sikes reproduces a curious 18th-century print of such a scene. `[Brand, Antiquities, II. 211 ; *British Goblins*, 323.]`

The citation of Pennant's'*History of Whiteford* as the source of the tradition for the nearest female relative providing the gift is incorrect. The reference actually appears in {ref}`TIWPN:1783`.

```{figure} ../resources/images/British_goblins_food_over_coffin_p323.png
---
name: British_goblins_food_over_coffin_p323
---
"Giving food over the coffin", in *British Goblins, Wirt Sikes, 1880, p323.
```

Still existent variants of the tradition in the region were then identified, along with a pleas for "further research needed":

> The funeral sponge-cakes of North Shropshire are still, or were recently, in use in Wales also`[*Ibid.*, p324]`. It is much to be wished that the subject of the ceremonial use of cakes could be farther investigated.`[E. g. we have Wedding, or, as it used to be called, Bride Cake, Christening Cake, Yule Cake, Twelfth Cake, Simnel Cakes, Soul Cakes, etc. : to say nothing of the divinations and magical remedies in which the baking of specially compounded cakes (as the Dumb Cake) plays a part.]` One cannot but suspect that the funeral cakes were in their first origin not a dole to purchase prayers, but a part of the ceremonial of the pagan burial-feasts; of which we really seem to retain other traces in Shropshire, to judge from the following passage in a letter addressed by the Rev. G. L. Wasey to Miss Jackson in 1873. He speaks of course of the neighbourhood of Bridgnorth.

```{index} single: Archaeologia Cambrensis ; extracts from a MS. of an ancient date
```
(ARCHC:manuscript)=
## *Archaeologia Cambrensis*, "Manuscript"

In [Vol 2 Iss 6, April, 1885](https://archive.org/details/sim_archaeologia-cambrensis_1885-04_2_6/page/152/mode/2up), p151-5, we find an article entitled *"Extracts from a MS. of an ancient date giving some customs and usages in North Wales"* that is reminiscent of material appearing in Pennant. It closes with the mention that the contents "relate to the diocese of St. Asaph", so is this perhaps the "MS, book of a Bp. of St. Asaph, written about a century ago" that was mentioned in The British magazine article on *Ancient Usages and Customs in North Wales* of 1835?

> ...
>
> The night before a dead body is to be interred the friends and neighbours of the deceased resort to the house the corpse is in, each bringing with them some small piece of meat, bread, or drink (if the family be something poor); but more especially candles, whatever the family is; and this night is called Wyl Nos, whereby the country people seem to mean a Watching Night ; their going to such a house they say is "i wilio'r corph", *i.e.*, to watch the corpse. But "wylo" signifies to weep and lament, aud so "wyl nos" may be a night of lamentations. While they stay together on these nights they are either singing psalms or reading some part of the holy scriptures. [Llanyeil.]
>
> Whenever anybody comes into the room where a dead corpse lyes, especially the wyl nos and the day of its interment, the first thing he does, he falls upon his knees by the corpse, and saith the Lord’s Prayer. [Llanycil custom.]
>
> Pence and half-pence (in lieu of little rolls of bread, which heretofore generally, and by some still are given on these occasions) are now distributed to the poor who flock in great numbers to the house of the deceased before the corpse is brought out. [Ysceifiog custom.]
>
> When the corpse is brought out of the house, laid upon the bier, and covered before it be taken up, the next of kin to the deceased— widow, mother, daughter, or cousin (never done by a man)— gives across over the corpse to one of the poorest neighbors two or three little loaves of bread and a cheese with a piece of money stuck in it, and then a new wooden cup of drink (all which things are brought upon a large dish and reached over the corpse to the poor body, who returns thanks for them, and blesses God for the happiness of the soul of his friend or neighbour departed), [Llangollen], which some will require the poor body that receives it immediately to drink a little of. When this is done, the minister (if present) saith the Lord’s Prayer, and then they get forward toward church. [Llanycil.]

```{danger}
The preceding paragraph closely resembles Pennant's *Tours in Wales*, 1783, p338:

> PREVIOUS to a funeral, it was customary, when the corpse was brought out of the house and laid upon the bier, for the next of kin, be it widow, mother, sister, or daughter (for it must be a female) to give, over the coffin, a quantity of white loaves, in a great dish, and sometimes a cheese, with a piece of money stuck in it, to certain poor persons. After that they present, in the same manner, a cup of drink, and require the person to drink a little of it immediately. When that is done, all present kneel down; and the minister, if present, says the Lord's Prayer: after which, they proceed with the corpse; and at every cross-way, between the house and the church, they lay down the bier, kneel, and again repeat the Lord's Prayer; and do the same when they first enter the church-yard. It is also customary, in many places, to sing psalms on the way; by which the stillness of rural life is often broken into, in a manner finely productive of religious reflections.
```

The excerpts from the manuscript then continue:

> And all along from the house to ye churchyard, at every cross way, the bier is laid down and the Lord’s Prayer rehearsed ; and so, when they come first into the churchyard, before any of the verses appointed in the service be said. [Yskeifiog.]
>
> Some particular places were called "Resting Places". - At church nothing is done but as directed by the Rubric, besides that Evening Service is read with the office of the Buriall. [Llanycil.]
>
> At those words, "we commit this body to the ground", the minister holds the spade and throws in the earth first.
>
> At Dimeirchion there is a Custum of ringing a little bell before the corpse from the house to ye churchyard.
>
> When a corpse is carried to church from any part of the town, the bearers take care to carry it so that the cross may be on their right hand, though the way be hester (nearer) and it be less trouble to go on the other side ; nor will they bring the corpse to the churchyard any other way but through the south gate, singing psalms on the way as the corpse is entered into the church. The minister goes to the altar and there saith the Lord's Prayer, with one of the prayers appointed to be read at the grave, after which the congregation offer upon the altar, or on a little board for that purpose fixed to the rails of the altar, their benevolence to the officiating minister. A friend of the deceased is appointed to stand at the altar, observing who gives and how much. When all have given, he tells the money with the minister, and signifies the sum to the congregation, thanking them all for their goodwill.
>
> The people kneel and say the Lord’s Prayer on the graves of their lately deceased friends for some Sundays after their interment, and this is done generally upon their first coming into y® church, and after that they dress the grave with flowers. [Llanvechan.]
>
> In the church there is a general spitting; they usually spit at the name of the Devil or any of his synonime, and smite their breasts at the name of Judas.
>
> NOTITIA.
>
> We have reprinted the above "Extracts" from the Rhyl Journal for Nov. 22nd, 1884, because they comprise a highly interesting list of old customs, some of which, indeed, still linger among us. From the localities named it is evident that they relate to the diocese of St. Asaph, and they look as if they were taken from the Returns of Rural Deans on some of the ecclesiastical uses of their parishes. The probable date may be the earlier half of the last century. Many of the customs are very curious, for different reasons.
>
> ...
>
> "Smiting the breast", at the mention Judas, falls under the same category, so does "spitting at the names of Satan" ; though we by no means imply that the custom was limited to that one occasion. The funeral customs were, all of them, expressive. The distribution of rolls of bread and of pence and half-pence at the house, was very likely symbolical of the obligation of charity, and the need to make friends of the mammon of unrighteousness.

*I have been unable to find a digital archive copy of the Rhyl Journal for November, 22nd, 1884.*

## Echoes through the early 1890s

As the 1880s turned into the 1890s, references to the sin-eater continued to make an occasional appearance as the following short piece in the *The Pontypridd Chronicle and Workman's News*, [June 3rd, 1892, p3](https://newspapers.library.wales/view/3812076/3812079/14/), the same note also appearing in the [Herald of Wales, Saturday 04 June 1892, p7](https://www.britishnewspaperarchive.co.uk/viewer/bl/0003036/18920604/007/0007), albeit citing the source as the *Newb__e__ry House Magazine*.

> CHURCH FOLK LORE.
>
> Writing in the *Newbury House Magazine* anent "Church Folk Lore," the Rev. J. E. Vaux records a very remarkable custom which prevailed up to, say, a couple of hundred years ago. There was in one of the villages adjoining Wales an old man who was called "The Sin Eater." His office was, for a trifling consideration, to pawn (so to speak) his own soul for the ease and rest of a soul departed. When a person died, notice was given to him, and he at once went to the house of the deceased. A cricket— i.e., a stool— was brought, and he sat down in front of the door. A groat, a crust of bread, and a full bowl of ale were given to him, after the consumption of which he rose and pronounced the "ease and rest of the soul departed, for which he would pawn his own soul." It was believed that this ceremony would free the departed soul from "walking" thenceforth. It is probable that this strange custom was originally connected some way with the ceremony of the Scape Goat under the Law (Lev. xvi. 21). This institution of the "Sin Eater" was in later times mainly confined to the county of Hereford; but there is reason to believe that it once prevailed generally in Wales.

An echo of Vaux's observations also came around again in the *Evening Express* of [July 4th, 1894, p2](https://newspapers.library.wales/view/3245581/3245583/40/):

> Welsh Wit and Wisdom
>
> ...
>
> In his interesting work on Church folk- lore the Rev. J. Edward Vaux says that one of the most striking (ustoms m connection with funerals is a custom which continued till the seventeenth century. "There was in one of the villages adjoining the Welsh border an old man called the 'Sin Eater,' and his office was, for a trifling consideration, to pawn his own soul for the ease and rest of the soul departed. When a person died notice was given to him, and he at once went to the house of the deceased. A cucket —that is, a stool- was brought, and he sat down in front of the door. A groat, a crust of bread, and a full bowl of ale were given to him, after which he rose and pronounced the ease and rest of the soul departed, for which he would pawn his own soul. It was believed that this ceremony would free the departed soul from "walking thenceforth."