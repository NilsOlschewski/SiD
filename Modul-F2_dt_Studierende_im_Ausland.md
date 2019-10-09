\--------------------------------

F2_1
====

tc:

vn: aeinnorm1 ; aeinnorm2; aeinnorm3; aeinnormando

qt: Einfachauswahl

hl:

in:

q: Inwiefern treffen die folgenden Aussagen Ihrer Meinung nach zu?

is:

it:

st:

ao1: (aeinnorm1): : Ein studienbezogener Auslandsaufenthalt darf während des
Studiums auf keinen Fall fehlen.

ao2: (aeinnorm2): : Auslandserfahrungen werden auf dem Arbeitsmarkt oftmals
erwartet.

ao3: (aeinnorm3): : Jede\*r Studierende sollte während des Studiums
studienbezogen im Ausland gewesen sein.

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_2

hi: Items bitte zufällig rotieren (Ausnahme: aeinnormandoba)

\--------------------------------

F2_2
====

tc:

vn: aeinsarbm; aeinssprachk; aeinsfach; aeinspersön; aeinskont; aeinskultur;
aeinsspaß; aeinsfinanz; aeinsorga; aeinsfreun; aeinsanerk; aeinszeit;
aeinsfehlspra; aeinsangstl

qt: Einfachauswahlmatrix

hl:

in:

q: Was spricht Ihrer Meinung nach …

is:

Überschrift: … für einen Auslandsenthalt?

it1 (aeinsarbm): verbesserte Arbeitsmarktaussichten

it2 (aeinssprachk): verbesserte Sprachkenntnisse

it3 (aeinsfach): verbesserte Fachkenntnisse

it4 (aeinspersön): Persönlichkeitsentwicklung

it5 (aeinskont): internationale Kontakte knüpfen

it6 (aeinskultur): andere Länder/Kulturen kennenlernen

it7 (aeinsspaß): Spaß haben

Überschrift: … gegen einen Auslandsaufenthalt?

it8 (aeinsfinanz): finanzielle Belastung

it9 (aeinsorga): Organisationsaufwand

it10 (aeinsfreun): Trennung von Freunden und Familie

it11 (aeinsanerk): Anerkennungsschwierigkeiten

it12 (aeinszeit): Zeitverlust

it13 (aeinsfehlspra): fehlende Sprachkenntnisse

it14 (aeinsangstl): Angst vor fremder Studien- und Lebenssituation

st:

ao1: 1: : überhaupt nicht

ao2: 2

ao3: 3

ao4: 4

ao5: 5: : sehr stark

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_3

hi:

\--------------------------------

F2_3
====

tc:

vn: ainfpfakt

qt: Einfachauswahl

hl:

in:

q: Ist in Ihrem Studiengang ein Auslandsaufenthalt verpflichtend vorgeschrieben?

is:

it:

st:

ao1: 1: : nein

ao2: 2: : ja

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_4

hi:

\--------------------------------

F2_4
====

tc:

vn: avorelt; avorgeschw; avorandver; avorfeund; avorkomm; avorniem

qt: Mehrfachauswahl mit Exklusivkategorie

hl:

in:

q: Kennen Sie jemanden, der bereits vor Ihnen im Rahmen seines Studiums im
Ausland war?

is: Mehrfachauswahl

it:

st:

ao1: (avorelt) : Eltern

ao2: (avorgeschw) : Geschwister

ao3: (avorandver) : andere Verwandte

ao4: (avorfreund) : Freunde

ao5: (avorkomm) : Kommiliton\*innen

ao6: (avorniem) : nein, niemanden (Exklusivkategorie)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_5

hi:

\--------------------------------

F2_5
====

tc:

vn: aauszeitlebnein; aauszeitlebfrkin; aauszeitlebwschul; aauszeitlebnschul;
aauszeitlebbama

qt: Mehrfachauswahl

hl:

in:

q: Haben Sie im Laufe Ihres Lebens eine längere Zeit (durchgängig mehr als 3
Monate) Im Ausland verbracht?

is: Bitte alles Zutreffende ankreuzen.

it:

st:

ao1: (aauszeitlebnein): Nein Exklusivkategorie)

ao2: (aauszeitlebfrkin): ja, in meiner frühen Kindheit

ao3: (aauszeitlebwschul): ja, während meiner Schulzeit

ao4: (aauszeitlebnschul): ja, direkt nach der Schulzeit

ao5: (aauszeitlebbama): ja, zwischen meinem Bachelor- und Masterstudium

mv:

ka:

vc: SHOW aauszeitlebbame IF (nur für MA-Studierende mit vorherigem BA-Schluss )

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_6

hi:

\--------------------------------

F2_6
====

tc: IF (nur für dt. Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: ainfasia; ainfbmsia; ainfbjsia; ainfemsia; ainfejsia

qt: Tableau-Abfrage Drop-Down-Menü, offene Angabe

hl:

in:

q: Bitte beschreiben Sie Ihren aktuellen studienbezogenen Auslandsaufenthalt
näher.

is:

it:

st:

Drop-Down-Menü:

ao1 (ainfasia): 1: : Auslandsstudium mit angestrebtem Abschluss im Ausland

ao2 (ainfasia): 2: : Auslandsstudium/-semester ohne angestrebten Abschluss

ao3 (ainfasia): 3: : Praktikum/Praxisphase

ao4 (ainfasia): 4: : Sprachkurs

ao5 (ainfasia): 5: : Studienreise

ao6 (ainfasia): 6: : Projektarbeit

ao7 (ainfasia): 7: : Summerschool

ao8 (ainfasia): 8: : sonstiger Aufenthalt

Nebeneinander angeordnete Drop-Down-Menüs: Start des Auslandsaufenthalts

ao9 (ainfbmsia): : Monat: (Januar \| … \| Dezember)

ao10 (ainfbjsai): : Jahr: (2020 \| 2019 \| … \| 2000 \| vor 2000)

Nebeneinander angeordnete Drop-Down-Menüs: vrstl. Ende des Auslandsaufenthalts

ao11 (ainfemsia): : Monat: (Januar \| … \| Dezember)

ao12 (ainfejsia): Jahr: (2030 \| 2029 \| … \| 2000 \| vor 2000)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_7 (ainfasia=3-8 OR ainfasia=1-2 AND hsstand=1 \| hsstandbl=1-16

GOTO F2_8 (else)

hi:

\--------------------------------

F2_7
====

tc: IF ainfasia=3-8 OR ainfasia=1-2 AND hsstand=1 \| hsstandbl=1-16

vn: hsstandla; hsstandlao; hsstandst; hsstandsto; hsstandhs; hsstandhso

qt: offene Angabe

hl:

in:

q: Bitte tragen Sie das Land, den Ort sowie ggf. die Hochschule ein, an der Sie
aktuell im Ausland studieren.

is:

it:

st:

ao1: 100 Stellen, Präfix (hsstandla; hsstandlao), Suffix: Land

ao2: 100 Stellen, Präfix (neue Variablen erforderlich), Suffix: Ort

ao1: 300 Stellen, Präfix (hsstandhs; hsstandhso), Suffix: Hochschule:

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_8

hi:

F2_8
====

tc: IF (nur für dt. Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: bdefinsia; bdekensia; bdesprsia; bdefamssia; bdefamlsia; bdetecsia;
bdeoeksia; bdepolsia; bdequasia; bdearbsia, es fehlen noch zwei Variablen
(„anderer Grund, und zwar“ und offene Angabe)

qt: Einfachauswahlmatrix

hl:

in:

q: Warum haben Sie sich für das Land in dem Sie Ihren aktuellen studienbezogenen
Auslandsaufenthalt absolvieren entschieden?

is: Bitte geben Sie den jeweils zutreffenden Skalenwert an.

Überschrift: Ich habe mich für das Studienland entschieden …

it1 (bdefinsia): weil ein Studium in diesem Land meinen finanziellen
Möglichkeiten entspricht.

it2 (bdekensia): um dieses Land kennenzulernen/weil mich die Geschichte und
Kultur des Landes interessiert.

it3 (bdesprsia): um eine Sprachkenntnisse zu vertiefen.

it4 (bdefamssia): weil Freunde/Verwandte in diesem Land studieren/studiert
haben.

it5 (bdefamlsia): weil Freunde/Verwandte in diesem Land leben/gelebt haben.

it6 (bdetecsia): weil dieses Land ein hochtechnisiertes Land ist.

it7 (bdeoeksia): wegen der wirtschaftlichen Lage in diesem Land.

it8 (bdepolsia): wegen der politischen Lage in diesem Land.

it9 (bdequasia): wegen der Lebensqualität in diesem Land.

it10 (bdearbsia): aufgrund der Möglichkeiten, nach Studienabschluss in diesem
Land zu arbeiten.

it11 (Variable fehlt ): anderer Grund

st:

ao1: 1: : trifft gar nicht zu

ao2: 2

ao3: 3

ao4: 4

ao5: 5: : trifft voll und ganz zu

ao6: (Variable für offene Angabe ): 100 Zeichen, Prefix (anderer Grund)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_9

hi: Items bitte zufällig rotieren.

\--------------------------------

F2_9
====

tc: IF (nur für Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: ainfastsia

qt: Einfachauswahl

hl:

in:

q: Planen Sie im Rahmen Ihres aktuellen studienbezogenen Auslandsaufenthalts
eine Abschluss zu erwerben?

is:

it:

st:

ao1: 1: : nein

ao2: 2: : ja, sowohl an der ausländischen Hochschule als auch der deutschen.

ao3: 3: : Ja, nur an der ausländischen Hochschule.

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_10

hi:

\--------------------------------

F2_10
=====

tc: IF (nur für Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: ainfcpsia; ainfcp1osia; ainfcp2osia

qt: Einfachauswahl, offene Angabe

hl:

in:

q: Wissen Sie bereits, ob Ihr aktueller Auslandsaufenthalt auf Ihr Studium in
Deutschland angerechnet wird, z. B. in Form von ECTS-Punkten?

is:

it:

st:

ao1: 1: : nein

ao2: 2: : offene Angabe: 2 Stellen Präfix [ainfcp1osia], Suffix: ja, teilweise:
… ECTS-Punkte

ao3: 3: : offene Angabe: 2 Stellen Präfix [ainfcp2osia], Suffix: ja,
vollständig: … ECTS-Punkte

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_11

hi:

\--------------------------------

11
==

tc: IF (nur für dt. Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: aproselbsia; aproerassia; aproapeusia; aprodaadsia; apropadsia;
apropromossia; aprodthssia; aprogahssia; aproanprsia; aproanprosia

qt: Mehrfachnennung

hl:

in:

q: Findet Ihr Auslandsaufenthalt im Rahmen eines Austauschprogramms statt?

is: Bitte alles Zutreffende auswählen.

it:

st:

ao1 (aproselbsia): : nein, ich habe den Aufenthalt selbst organisiert
(Exklusivkategorie)

ao2 (aproerassia): : ja, ERASMUS+, ERASMUS

ao3 (aproapeusia): : ja, anderes EU-Programm

ao4 (aprodaadsia): : ja, DAAD-Programm

ao5 (apropadsia): : Pädagogischer Austauschdienst (PAD)/COMENIUS

ao6 (apropromossia): : PROMOS-Stipendium

ao7 (aprodthssia): : ja, Programm meiner Hochschule in Deutschland

ao8 (aprogahssia): : ja, Programm meiner Gasthochschule im Ausland

ao9 (aproanprsia): : ja, anderes Programm offene Angabe: 100 Stellen, Präfix
[aproanprosia], Suffix:und zwar:

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_12

hi:

\--------------------------------

F2_12
=====

tc: IF (nur für Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: afinelt; afinpar; afinbaf; afinjobv; afinjobw; afinstip; afinand

qt: Mehrfachnennung

hl:

in:

q: Wie finanzieren Sie Ihren studienbezogenen Auslandsaufenthalt?

is: Bitte alles Zutreffende auswählen.

it:

st:

ao1 (afinelt): : Eltern

ao2 (afinpar): : Parnter\*in

ao3 (afinbaf): : BAföG

ao4 (afinjobv): : eigener Verdienst aus Tätigkeiten vor dem Auslandsaufenthalt

ao5 (afinjobw): : eigener Verdienst aus Tätigkeiten während des
Auslandsaufenthalts

ao6 (afinstip): : Stipendium

ao7 (afinand): : andere Finanzierungsquelle

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_13

hi:

\--------------------------------

F2_13
=====

tc: IF (nur für dt. Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: akontdeustsia; akontgastsia; akonteinheimsia; akontintstsia

qt: Einfachauswahlmatrix

hl:

in:

q: Wie häufig haben Sie während Ihres aktuellen studienbezogenen
Auslandsaufenthalts insgesamt Gespräche/Kontakt …

is:

it1 (akontdeustsia): … mit Studierenden aus Deutschland?

it2 (akontgastsia): … mit Studierenden des Gastlandes?

it3 (akonteinheimsia): … mit anderen Einheimischen?

it4 (akontintstsia): … mit anderen internationalen Studierenden (nicht aus
Deutschland)?

st:

ao1: 1: : nie

ao2: 2: : selten

ao3: 3: : manchma

ao4: 4: : häufig

ao5: 5: : sehr häufig

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_14

hi:

\--------------------------------

F2_14
=====

tc: IF (nur für dt. Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: asprachlandsia; asprachdeutsia; asprachandsia; asprachandosia

qt: Einfachauswahlmatrix

hl:

in:

q: Wie häufig sprechen Sie während Ihres aktuellen Auslandsaufenthalts die
folgenden Sprachen

is:

it1 (asprachlandsia): Landessprache

it2 (asprachdeutsia): Deutsch

it3 (asprachandsia): andere Sprache, und zwar (offene Angabe: 50 Stellen, Präfix
[asprachandosia], Suffix

st:

ao1: 1: : nie

ao2: 2: : selten

ao3: 3: : manchmal

ao4: 4: : häufig

ao5: 5: : sehr häufig

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_15

hi:

\--------------------------------

F2_15
=====

tc: IF (nur für dt. Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: azufskein; azufskstu; azufsklehr; azuflernerf; azufinsg

qt: Einfachauswahlmatrix

hl:

in:

q: Wie zufrieden sind Sie bis zum jetzigen Zeitpunkt in Bezug auf Ihren
aktuellen studienbezogenen Auslandsaufenthalt mit …

is:

it1 (azufskein): … dem sozialen Kontakt zu Einheimischen?

it2 (azufskstu): … dem sozialen Kontakt zu Studierenden?

it3 (azufsklehr): … dem sozialen Kontakt zu Lehrenden?

it4 (azuflernerf): … den gewonnenen fachlichen Kenntnissen?

it5 (azufinsg): … dem Auslandsaufenthalt insgesamt?

st:

ao1: 1: : überhaupt nicht zufrieden

ao2: 2

ao3: 3

ao4: 4

ao5: 5: : sehr zufrieden

ao6: 6: : trifft nicht zu

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_16

hi:

\--------------------------------

F2_16
=====

tc: IF (nur für dt. Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: azufleistanf; azuforgaufw; azuffinanzaufw

qt: Einfachauswahlmatrix (Akkordeon)

hl:

in:

q: Und wie beurteilen Sie …

is:

it1 (azufleistanf): … die aktuellen Leistungsanforderungen?

it2 (azuforgaufw): … den aktuellen organisatorischen Aufwand?

it3 (azuffinanzaufw): … den aktuellen finanziellen Aufwand?

st:

ao1: 1: : sehr niedrig

ao2: 2

ao3: 3

ao4: 4

ao5: 5: : sehr hoch

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_17

hi:

\--------------------------------

F2_17
=====

tc: IF (nur für dt. Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: aeempfsia

qt: Einfachauswahlmatrix

hl:

in:

q: Ausgehend von Ihren bisherigen Erfahrungen:

Würden Sie empfehlen, im Rahmen eines Studiums ins Ausland zu gehen?

is:

it:

st:

ao1: 1: : nein, überhaupt nicht

ao2: 2

ao3: 3

ao4: 4

ao5: 5: : ja, unbedingt

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_18

hi:

\--------------------------------

F2_18
=====

tc: IF (nur für Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: bdedarlsia; bdedarlosia; bdedarhssia; bdedarhsosia

qt: Einfachauswahl, offene Angabe

hl:

in:

q: Hinsichtlich Ihres Auslandsaufenthalts:

Wenn Sie die freie Wahl hätten, in welchem Land, an welchem Ort bzw. an welcher
Hochschule hätten Sie am liebsten studiert?

is:

it:

st:

ao1 (bdedarlsia): : Land: (offene Angabe: 100 Zeichen, Präfix [bdedarlosia],
Suffix:

ao2 (bdedarhssia): :Ort/Hochschule: (offene Angabe: 100 Zeichen, Präfix
[bdedarhsosia], Suffix:

ao3: -12 : : weiß ich nicht

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_19

hi:

\--------------------------------

F2_19 
======

tc: IF (nur für Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: intpsydeu; intpsyzeitl; intpsyandl

qt: Einfachauswahlmatrix

hl:

in:

q: Wenn Sie an Ihre Zukunft denken, wo möchten Sie leben?

is:

it1 (intpsydeu): in Deutschland

it2 (intpsyzeitl): zeitweise im Ausland

it3 (intpsyandl): dauerhaft im Ausland

st:

ao1: 1: : auf keinen Fall

ao2: 2

ao3: 3

ao4: 4

ao5: 5: : auf jeden Fall

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO F2_20

hi:

\--------------------------------

F2_20
=====

tc: IF (nur für Studierende, die sich aktuell studienbezogen im Ausland
befinden)

vn: intling1sia; intling2sia; intling3sia

qt: Einfachauswahlmatrix

hl:

in:

q: Wie sehr treffen die folgenden Aussagen auf Sie zu?

is:

it1 ( intling1sia): Ich kann in der Landessprache über vertraute Themen sprechen
und persönliche Meinungen äußern.

it2 (intling2sia): Ich verstehen die wichtigsten Punkte in Radio- und
Fernsehprogrammen, die in der Landessprache gesendet warden.

it3 (intling3sia): Ich kann einheimische Zeitungsartikel lesen und vollständig
verstehen.

st:

ao1: 1: : trifft gar nicht zu

ao2: 2

ao3: 3

ao4: 4

ao5: 5: : trifft voll und ganz zu

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:

GOTO nächstes Modul

hi: