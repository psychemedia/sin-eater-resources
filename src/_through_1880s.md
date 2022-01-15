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
# Through the 1880s

Throughout the 1880s, occasional references to the sin-eater occurs in various *Notes and Queries* style columns, along with occasional reference works on folklore that make mentions of the tradition although add nothing of real substance to our understanding of it.

Of these full length works, two publications perhaps stand out in particular: Paxton Hood's *Cristmas Evans*, which added nothing new, but got noticed, and the publication of an edited edition of Aubrey's manuscripts, *Remaines of Gentilisme* by James Britten.

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
show_diffs(x1.replace('.',''),x2.replace('.',''),
           "Excerpt from *Shrewsbury Chronicle*",
           "Excerpt from Kennet's *Parochial Antiquities*")
```

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

*Red deletions are deltions from the original text in `In Praise of Ale`. Green additions are changes added in the Eddowes quotation.*

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

## *The Antiquities of Laugharne, Pendine*, Mary Curtis, 1880

In a self-published work on *The antiquities of Laugharne, Pendine, and their neighbourhood, Carmarthenshire, Amroth, Sandersfoot, Cilgetty, Pembrokeshire, South Wales*](https://archive.org/details/antiquitiesoflau00curt/page/206/mode/2up?q=funeral), published in second edition at least in 1880, Mary Curtis describes the following custom All Hallows custom in which parishioners might learn the names of who was to die in the folloming year (p206-7)

> They had this very remarkable custom : — I was informed by a respectable farmer of Eglwyscummin parish, who died in old age in 1875, that his father told him that there was a person appointed to every church, whose office was to go to the church on All Hallows Eve to hear the names of those who would die the next year, called. An old woman of this town, dead now sixty years, is remembered by some old people as going on this eve to Laugharne church to stand by the chancel window, where they say she distinctly heard the names pronounced. She said that, as she had been once to hear the names called, she was bound to go at every future eve. I was told by one of the most respectable and esteemed old inhabitants of this town, that in his presence some one said to her, that a lady then dangerously ill, and given over, would die. She said, "No ; for her name was not called." She did recover and live many years. And another time she foretold that a funeral of a person would take place shortly in Laugharne church, which it did. In Cardiganshire, on All Hallows Eve, it was the custom to sit in the porch of the church to see those pass through who should die that year. I am not quite sure that this was not on St. John's day, 24th June. I give no opinion, though I would not declare them falsehoods, or the results of imagination. Which is the worst to believe — too much or too little ? Some people, deeming themselves very wise and superior to such credulity, with a wonderfully wise look, condemn these as mere superstitions.

Of death tradition themselves, Curtis describes appropriate behaviour for showing respect for the dead  (p213-7):

> When a death occurred, a boy was sent round the town and neighbourhood to give notice, and invite to the sitting up ; he rang a small bell to draw attention. People were expected to come to the funerals in their neighbourhood, even without invitation; families would be offended if they did not.

The way the Welsh treat their dead, with respect and kindness, is noted, as are the "watch" stye traditions:

> There is something very beautiful in the care the Welsh show for the dead, and in their customs at burials. It proves their kindliness and reverential feeling. They think it wanting in feeling to leave the dead body in the room by itself for a single instant. The face was exposed, a number of candles kept burning all night, and those who came to sit up brought presents of tea, sugar, and candles. An old inhabitant of this town, who died 20 years ago, aged 89, was at a wake kept in a room of the old inn, called the Dials, now in ruins.

But even in death, so might traditions of youthful life might also be observed:

> During the night, in presence of the departed, a number of men and women, she said, played different games. One was called "Trounsing;" it was like blind-man's buff. If the young man who was blindfolded caught a young woman, she was his sweetheart for that year.

But eben by the 1880s, these traditions were lapsing:

> No more remains of these customs in Laugharne, except the presents of candles, etc., which friends do bring.

The gtahering for the funeral procession involved an element of hosptiality, and once again t is easy to see how the over-zealous fan of the sin-eating tradition might claim elements of this behaviour as a relic of that ritual:

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

For Curtis, the belief still appeared to be a contemporary one, aorund the 1880s:

> An old woman of Laugharne said to me that she continually saw those lights. It seems from all I hear that they are seen as much as ever. I must give this singular one : A gentleman belonging to a county family of Pembrokeshire, was some years ago returning in his carriage to his home in Tenby from the railway. He was inside. With the coachman sat a tenant of the lady from whom I had this story. Between Narberth and Templeton, they perceived through the darkness of the evening a black mass moving towards them. As it approached they saw it was a funeral. The horses now plunged and reared ; the carriage was overturned ; the coachman and the tenant thrown over the hedge into the field, much bruised ; the gentleman escaped without injury. My friend who related this had it from her tenant himself.

## *Domestic Folk-lore*, T. F. Thiselton Dyer, 1881

In [*Domestic Folk-lore*](https://archive.org/details/b24884558/page/n4/mode/2up?q=sin-eater), 1881, the rather splendidly named Revered Thomas Firminger Thiselton Dyer also describes several traditions relating to death and burial, including the traditional use of salt (p59-63):

> Again, the interval between death and burial has generally been associated with various superstitious fears and practices. Thus, as soon as the corpse is laid out there is still a widespread custom of placing a plate of salt upon the breast, the reason being no doubt to prevent the body swelling ; although there is a belief that it acts as a charm against any attempt on the part of evil spirits to disturb the body.

Several Scottish traditions are also described:

> Pennant tells us that formerly in Scotland, "the corpse being stretched on a board and covered with a coarse linen wrapper, the friends laid on the breast of the deceased a wooden platter, containing a small quantity of salt and earth, separate and un-mixed ; the earth an emblem of the corruptible body, the salt as an emblem of the immortal spirit." Mr. Napier, in his "Folk-Lore of the West of Scotland," points out that we may find another explanation for the plate of salt on the breast in the "sin-eaters," persons who, in days gone by, when a person died, were sent for to come and eat the sins of the deceased. On their arrival their first act was to place a plate of salt and one of bread on the breast of the corpse, repeating a series of incantations, after which they devoured the contents of the plates. By this ceremony the deceased person was supposed to be relieved of such sins as would have kept his spirit hovering about his relations to their discomfort and annoyance.

One intriguing tale suggests that fresh corpses were once believed to have divinatory powers:

> It is customary, especially among the poor, for those who visit a house while the dead body is lying in it to touch the corpse, thereby showing that they owe the departed one no grudge. This practice, in all probability, originated in the belief that a corpse would bleed at the touch of the murderer, constant allusions to which we find in old authors.

Watching over corpses is recognised as a custom still contemporary to the 1880s:

> The practice of watching the dead body until its burial is not yet obsolete, a custom indeed which, among the Irish, is even still occasionally the scene of the most unseemly revelries, those present often-times indulging in excessive drinking and riotous merry-making. In days gone by, however, this practice was attended with every mark of respect to the deceased one, the leading idea being to see that the devil did not carry off the body.

As regards funerals and the funeral proocession, some of which we have not previously heard described:

> Lastly, since the formation of cemeteries, many of the quaint old funeral customs which formerly existed in many of our country villages have passed away. Now-a-days, the "last act," as the committal of the body to the grave has been termed, has been shorn of much of its pomp. Thus, in the North of England it was customary, only a few years ago, to carry "the dead with the sun" to the grave, a practice corresponding with the Highland usage of making "the deazil," or walking three times round a person, according to the course of the sun.

We might also note that sometimes, such traditions may offer something of a surprise to a cleric in charge of the funeral:

> On one occasion, in the village of Stranton, near West Hartlepool, the vicar was standing at the churchyard gate, awaiting the arrival of the funeral procession, when, much to his surprise, the entire group, who had come within a few yards of him, suddenly turned back and marched round the churchyard wall, thus traversing its west, north, and east boundaries. On inquiring the reason of this extraordinary procedure, one of the mourners quickly replied, "Why, ye wad no hae them carry the dead again the sun ; the dead maun ay go wi' the sun."

A similar custom appears to hail from Wales, althoiugh I havenlt yet tracked down the original Pennant reference:

> This is not unlike a Welsh custom mentioned by Pennant, who tells us that when a corpse was conveyed to the churchyard from any part of the town, great care was always taken that it should be carried the whole distance on the right-hand side of the road.

The payment to the cleric, the *parson's penny*, as we heard described in Wirt Sike's *British goblins*, is also mentioned, along with a possible variant, the *spade money*:

> A curious custom, which still survives at Welsh funerals, is termed "the parson's penny." After reading the burial service in the church, the clergyman stands behind a table while a psalm is being sung. In the meantime each of the mourners places a piece of money on the table for his acceptance. This ceremony is regarded as a token of respect to the deceased, although it was no doubt originally intended to compensate the clergyman for praying for the soul of the departed. In some Welsh parishes a similar custom, called "spade-money," is observed. As soon as the corpse has been committed to its resting-place, the grave-digger presents his spade as a receptacle for donations, these offerings, which often amount to a goodly sum, being regarded as his perquisites.

Finally, a traditional belief, the echoes of which may provide us with routes into local stories based on the graves to be found in the north side of church graveyards:

> From time immemorial there has been a popular prejudice among the inhabitants of rural villages against "burial without the sanctuary." This does not imply in unconsecrated ground, but on the north side of the church, or in a remote corner of the church-yard. The origin of this repugnance is said to have been the notion that the northern part was that which was appropriated to the interment of unbaptised infants, excommunicated persons, or such as had laid violent hands upon themselves. Hence it was generally known as "the wrong side of the church." In many parishes, therefore, this spot remained unoccupied while the remaining portion of the churchyard was crowded. White, in his "History of Selborne," alluding to this superstition, says that as most people wished to be buried on the south side of the churchyard, it became such a mass of mortality that no person could be interred "without disturbing or displacing the bones of his ancestors." A clergyman of a rural parish in Norfolk says : — "If I were on any occasion to urge a parishioner to inter a deceased relative on the north side of the church, he would answer me with some expression of surprise, if not of offence, at the proposal, 'No, sir, it is not in the sanctuary.'"

## John Aubrey, *Remaines of Gentilisme*, 1881

A long time in the coming, 1881 also saw the publication by *The Folk-Lore Society* of [*Remaines of Gentilisme and Judaisme*](https://archive.org/details/remainesgentili01aubrgoog/page/n12/mode/2up) by John Aubrey, "Printed from Lansdowne manuscript 231 in the British Museum", and edited by James Britten.

Some of Aubrey's "observations" on occult and supernatual matters had been previously published as [*Miscellanies, Collected by J. Aubrey, Esq.](https://archive.org/details/miscellanies00aubr/page/n1/mode/2up), "printed for Edward Castle, next Scotland Yard Gate, by Whitehall", in 1696, but that collection had made no mention of that lamentable fellow from the Rosse highway. This collection undoubtedly contributed to later opinions of him regarding his credulity.

But now for the first time we have a collection that provides us us a relatively direct form access to Aubrey's text without having to visit the British Library and view the original manuscript.

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

That Aubrey *did* collect write down his observations, no mattter how credulous he was, is, however, to be valued:

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

The mention directly follows a description of offertory customs at funerals:

>Offertories at funeralls.
>
> These are mentioned in the Rubrick of ye ch. of Engl. ComonPrayer-booke : but I never sawe it used, but once at Beaumaris, in Anglesey ; but it is used over all the Counties of North-Wales. But before when the corps is brought out of Doores, there is Cake & Cheese, and a new Bowle of Beere, and another of Milke with ye Anno Dni ingraved on it, & ye parties name deceased, wch one accepts of on the other side of ye Corps ; & this Custome is used to this day, 1686, in North Wales,`[From this to the end of the paragraph is added by Dr. Kennett. — Ed.]` where a small tablet or board is fixt near the Altar, upon which the friends of ye defunct lay their offerings in mony according to their own ability and the quality of the person deceased. This custom proves a very happy augmentation to some of the very poor vicars, and is often the best part of their maintenance.

The more complete reference, with which we are familiar, comes at [pp.35-6](https://archive.org/details/remainesgentili01aubrgoog/page/n50/mode/2up):

```{admonition} Aubrey on *Sinne-Eaters*,  *Remaines of Gentilisme*, ed. J. Britten, 1881
:class: note
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

The Reverend Edwin Paxton Hood was a non-conformist minister and prolific author. Several of his works took the form of biographies of other non-conformists. One such character, Christmas Evans, who presumbaly took his name from his birthdate, 25th December, 1766 – was a noted Welsh minister with a gift for preaching. He was the subject of his 1881 book *Christmas Evans : the preacher of Wild Wales, his country, his times and his contemporaries*](https://archive.org/details/christmasevanspr00hood/page/22/mode/2up?q=sin-eater).

In the chapter on *Characterisitics of Welsh Preaching*, p22-24, Paxton Hood has cause to comment on the tradition of the sin-eater as surviving despite the activities of a wave of great Christian preachers in the first half of the 19th century:

> In a word, it is impossible, knowing Wales as we know it in our own day, to form any very distinct idea of the country as it was when these great preachers arose ; and, when the tides of a new spiritual life rolled over the Principality, the singular relics of even heathenish superstition were loitering still among the secluded valleys and mountains of the land. No doubt, the proclamation of the Gospel, and the elevated faith which its great truths bring in its train, broke the fascination, the charm, and power of many of these ; but they lingered even until within the last forty or fifty years, — indeed, the superstition of the Sin-Eater is said to linger even now in the secluded vale of Cwm-Aman, in Caermarthenshire.

Paxton Hood's description of the tradition appears to owe, originally at least, to John Murray’s 1860 work, *A handbook for travellers in South Wales and its borders*, with its mention of the fee of 2s 6d and the "fact" that was hounded out after performing the ceremony *"with blows and kicks"*.

> The meaning of this most singular institution of superstition was, that when a person died, the friends sent for the Sin-Eater of the district, who, on his arrival, placed a plate of salt and bread on the breast of the deceased person ; he then uttered an incantation over the bread, after which, he proceeded to eat it, — thereby eating the sins of the dead person ; this done, he received a fee of two-and-sixpence, — which, we suppose, was much more than many a preacher received for a long and painful service. Having received this, he vanished as swiftly as possible, all the friends and relatives of the departed aiding his exit with blows and kicks, and other indications of their faith in the service he had rendered. A hundred years since, and through the ages beyond that time, we suppose this curious superstition was everywhere prevalent.

If we display a side-by-side view to inspect the difference between the texts, we can spot the areas of simularity directly:

`````{admonition} Comparing the Texts
:class: dropdown

````{panels}
<p><strong>Excerpt from Paxton Hood, <em>Christmas Evans</em></strong>

</p><p>the superstition of the sin-eater is said to linger even now in the secluded vale of <span style="background: #69E2FB;">cwm-aman,</span> in <span style="background: #69E2FB;">caermarthenshire the meaning of this most singular institution of superstition was, that</span> when a person died, the friends sent for the sin-eater of the district, <span style="background: #69E2FB;">who,</span> on his <span style="background: #69E2FB;">arrival,</span> placed a plate of salt <span style="background: #69E2FB;">and bread</span> on the breast of the <span style="background: #69E2FB;">deceased person ;</span> he then <span style="background: #69E2FB;">uttered</span> an incantation over the bread, <span style="background: #69E2FB;">after which,</span> he <span style="background: #69E2FB;">proceeded to eat it, —</span> thereby eating the sins of the dead person <span style="background: #69E2FB;">;</span> this done, he received <span style="background: #69E2FB;">a</span> fee of <span style="background: #69E2FB;">two-and-sixpence, — which, we suppose, was much more than many a preacher received for a long</span> and <span style="background: #69E2FB;">painful service having received this, he</span> vanished as <span style="background: #69E2FB;">swiftly</span> as <span style="background: #69E2FB;">possible, all</span> the friends <span style="background: #69E2FB;">and relatives</span> of <span style="background: #69E2FB;">the departed aiding his exit with</span> blows and kicks, <span style="background: #69E2FB;">and other indications</span> of <span style="background: #69E2FB;">their faith in</span> the <span style="background: #69E2FB;">service</span> he <span style="background: #69E2FB;">had rendered</span> a <span style="background: #69E2FB;">hundred years since, and through the ages beyond that time, we suppose this curious superstition</span> was <span style="background: #69E2FB;">everywhere prevalent</span> </p>
---
<p><strong>Excerpt from John Murray, <em>Handbook for Travellers in South Wales</em></strong>

</p><p>the superstition of the sin-eater is said to linger even now in the secluded vale of <span style="background: #69E2FB;">cwm amman</span> in <span style="background: #69E2FB;">carmarthenshire</span> when a person died, the friends sent for the sin-eater of the district, <span style="background: #69E2FB;">who</span> on his <span style="background: #69E2FB;">arrival</span> placed a plate of salt on the breast of the <span style="background: #69E2FB;">deceased, and on the salt a piece of bread</span> he then <span style="background: #69E2FB;">muttered</span> an incantation over the bread, <span style="background: #69E2FB;">which</span> he <span style="background: #69E2FB;">finally eat,</span> thereby eating the sins of the dead person this done, he received <span style="background: #69E2FB;">the</span> fee of <span style="background: #69E2FB;">2s 6d,</span> and vanished as <span style="background: #69E2FB;">quickly</span> as <span style="background: #69E2FB;">he could,</span> the friends <span style="background: #69E2FB;">helping his departure by the aid</span> of <span style="background: #69E2FB;">sundry</span> blows and kicks, <span style="background: #69E2FB;">if they could catch him ; for as it was believed that he took upon himself the sins</span> of the <span style="background: #69E2FB;">defunct,</span> he <span style="background: #69E2FB;">was looked upon as</span> a <span style="background: #69E2FB;">social pariah for whom nothing</span> was <span style="background: #69E2FB;">too bad</span> </p>
````

`````

As well as referrring to the sin-eater tradition, Paxton Hood also makes passing reference to a "horse's head" tradition that is used to castigate a "social delinquent":

> Another odd custom was the manner in which public opinion expressed itself on account of any domestic or social delinquency. A large crowd assembled before the house of the delinquent, one of whom was dressed up in what seemed to be a horse's head ; the crowd then burst forth into strong vituperative abuse, accompanying the execrations with the rough music of old kettles, marrow-bones, and cleavers ; finally, the effigy of the sinner was burnt before the house, and the sacred wrath of the multitude appeased. The majesty of outraged opinion being vindicated, they dispersed.

This stands in contrast to the New Year's Eve *Mari Lwyd* tradition, which is a far more light hearted and celebratory affair.

In the [third edition](https://archive.org/details/christmasevansp00hooduoft/page/22/mode/2up?q=sin+eater), published in 1888, there is an additional footnote referring the sin-eater which directs to the reader to *"See Note at end of Chapter, page 39."*, which then proceeds as follows:

> *Note to "Cwm-Aman" page 23.*
> 
> Dr. Thos. Rees, in a letter to the Editor of the *Dysgedydd*, Rev. Herber Evans, says, "That although bred and born within ten miles of Cwm-Aman, he had never heard of this ridiculous superstition."

An eagle-eyed correspondent to *Notes and Queries*, [Vol 7 Iss 159, January 13th, 1883](https://archive.org/details/sim_notes-and-queries_1883-01-13_7_159/page/24/mode/2up?q=sin), p25, picked up on the reference and provided a new note on the matter, perhaps unaware of previous mentions of the tradition in earlier volumes.

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

When the book came to the attention of the editor in *Bye-Gones* of [February 15th, 1882](https://journals.library.wales/view/2092910/2094771/9#?xywh=-1532%2C-191%2C5763%2C3801), p18, it was almost  as if they were keeping a look out for such references. The resulting note can quite easily be read as mocking.

> Mr. Paxton Hood has made a discovery which many more experienced archaeological authorities have sought after, and failed in the search. In a life of the Rev. Christmas Evans, he has recently written, he tells us that there still exists in Caermarthenshire "the Sin Eater," a personage once universal in Wales. We thought that belief was finally scotched in the Academy discussion a few years ago. Such an accommodating official does not and never did exist in Wales, and the only authority (?) for supposing that one ever existed on the borders was old Aubrey, who tells of a "leane, hungry raskel" in Herefordshire.

In the [March, 1883 edition, p282](https://archive.org/details/reddragonnation00wilkgoog/page/282/mode/2up?q=sin), of the Red Dragon, Paxton Hood's sin-eater reference is also discussed:

> A correspondent calls attention to a curious scrap of folk lore occurring in the Rev. Paxton Hood's book on *Christmas Evans, the Preacher of Wild Wales* published a couple of years ago. According to the author "the superstition of the Sin-Eater is said to linger even now in the secluded vale of Cwm-Aman, in Carmarthenshire. The meaning of this most singular superstition was that when a person died the friends sent for the Sin-Eater of the district, who, on his arrival, placed a plate of salt and bread on the breast of the deceased person ; he then uttered an incantation over the bread, after which he proceeded to eat it, thereby *eating the sins of the dead person*. This done he received a fee of two-and-sixpence, which we suppose was much more than many a preacher received for a long and painful service. Having received this he vanished as swiftly as possible, all the friends and relatives of the departed aiding his exit with blows and kicks and other indications of their faith in the service he had rendered. A hundred years since, and through the ages beyond that time, we suppose this curious superstition was everywhere prevalent."

In no uncertain terms, Paxton Hood's assertions are refuted:

> It would be difficult to say upon what ground the Rev. Paxton Hood founded the generalisation contained in the last sentence, unless it be that he is neither a close nor a profound reasoner. But what there ought to be no difficulty about is the proof or disproof of the existence of the custom referred to in the vale of Cwm-Aman or in any other part of the Principality.

The author also wonders about the propensity for folk other than the Welsh to introduce notions about Welsh behaviour to the Welsh:

> It is a singular, and by no means creditable fact, that our acquaintance with things happening at our very doors should be so often the result of the observation of strangers.

A plea, of a sort, is then made, for Welsh correspondents to provide further evidence about this tradition:

> Contributions having for their subject any scrap of curious old Welsh customs or folk lore will be always welcome to the editor of the National Magazine. Perhaps in this matter of the "Sin-Eater," of which we should like to obtain other and more authentic information than the Rev. Paxton Hood can give, some correspondent, like "Tal-a-hên," may come to our rescue.

It would be useful to know what sort of contributor *Tal-a-hên* was to know whether this plea is entirely serious!

## *Popish Ceremonies Existing in Wales*, Bye-Gones, 1882

A series of articles over several issues of Bye-Gones ([May 13th, 1882, p64-5](https://journals.library.wales/view/2092910/2094824/5#?xywh=-1532%2C-117%2C5763%2C3800), [June 7th, 1882](https://journals.library.wales/view/2092910/2094841/#?xywh=-464%2C207%2C4906%2C3235), [July 5th, 1882](https://journals.library.wales/view/2092910/2094856/#?xywh=-1532%2C-369%2C5763%2C3801), [July 12th, 1882](https://journals.library.wales/view/2092910/2094856/2#?xywh=-860%2C-91%2C4002%2C2639)) describes various Catholic rituals.

The first installment opens with claim of the continued practice of Catholic ceremonies, and goes on to offer a consideration of death and burial rites:

> POPISH CEREMONIES STILL EXISTING IN WALES.
>
> The Rev. Canon Richards said, in his lecture at St. Joseph's, Swansea, on the recent Church Congress, that the old faith, or Popery, still lingers in men's hearts and memories, and that even now the people retain in Wales many practices once belonging to the old religion. That this is so amongst the members of the Established Church is an acknowledged fact, but that such practices still exist amongst the Welsh Nonconformists may at the first be questioned. I have long observed these strange but contradictory rites with no small interest, and possibly the pointing of them out may lead others to the same line of observation.
>
> I will first confine myself to death and burial rites. We have much that surrounds these events that must have come down to us from the times when the holy fathers were the masters of the ceremonies.

No mention is made of the sin-eater, but we do see several rituals described that we have mant in related forms prviously. For example, the *wake*:

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

TO DO

p143 Popular antiq, 1849 edition https://archive.org/details/b29328561_0002/page/142/mode/2up?q=bride+ale
```