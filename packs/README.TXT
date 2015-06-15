*---------------------------------------------------------------------*
*                              README.TXT                             *
*                                                                     *
*          packdefinitions in  the startrek-1E Lackey Plugin          *
*                               v. 1.1                                *
*---------------------------------------------------------------------*

The files in the directory /packs provide the startrek1e plugin with 
functionality for Booster Draw and Sealed Decks. The directory contains
three pack definition files: 

+ packdefinitions1.xml for all Booster from Premiere to The Motion 
  Pictures plus the Warp Pack, 

+ packdefinitions2.xml for Starters from Premiere, DS9, StarterDeck II, 
  Enhanced Premiere and TWT (Klingon and Fed) plus OTSD,

+ packdefinitions3.xml for definitions of 8 different Voyager Starters.

Images of all packs are also loacated in the directory /packs and 
should not be renamed. Images were taken form stccg.germes.org.


NEW 

V. 1.1
The definition for DS9 Starters was altered to reflect new informations.
DS9 Starters were printed semifixed on an extra 80 card sheet. 2 sheets
account for five possible setups of fixed cards in the starter. The 
actual position of single cards is not known, so the Lackey version is
a shot in the dark, but afaik ressembling the real starters quite well.


KNOWN LIMITATIONS

The distribution of R/R+, U and C in Boosters from AU and TWT onwards
is only an approximation; URs are slightly overrepresented (1:100) as
the plugin can only deal with integers.

The distribution of U and C in the sets MM, Borg, HA and TMP is not 
well documented a C:U ratio of 2:1 for MM, Borg, HA and a ratio of 3:2
for TMP was assumed for the pool to get a working base. Then different 
probabilites for different ratios of C:U in a pack were calculated and 
these probabilities were used in the pack definition.

The distribution of cards in the Voyager Starters is not known. Some 
players at CC have created a list of order of the cards in the Starters
(esp. OLE_ALE). This ordered list was used as a base to create 8
different Starters which should provide a (albeit limited) Starter pool
which can be expanded in future releases.


FURTHER ISSUES

- The R* in TWT Starters is not represented.
- BOG does not include foils in the Booster distribution.
  

CAVEAT

The packdefinitions is no true XML (e.g. won't take comments) and is
very fragile; changes might render Lackey unable to start. If you do
modify and improve it - let us know!