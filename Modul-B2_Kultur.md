\--------------------------

B2_1
=

tc:

vn: hschabv; hschabm

qt: Einfachauswahl im Spaltenformat/Comparison

hl:

in:

q: Welches ist der höchste allgemeinbildende Schulabschluss Ihres Vaters/Ihrer
Mutter?

is:

it1: (hschabv) Vater

it2: (hschabm) Mutter

st:

ao1: 1: allgemeine/fachgebundene Hochschulreife (Abitur)

ao2: 2: Fachhochschulreife

ao3: 3: mittlere Reife, Realschulabschluss (10. Klasse)

ao4: 4: Haupt-, Volksschulabschluss (mind. 8. Klasse)

ao5: 5: anderer Schulabschluss

ao6: 6: keinen Schulabschluss

mv: -12: weiß ich nicht

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: GOTO A_33

hi: Hilfsvariable muss an vorheriger Stelle generiert werden


\--------------------------

B2_2a
==

tc: 50 Prozent der Befragten

vn: deltposv1

qt: Einfachauswahl mit Überkategorien

hl:

in:

q: Welche berufliche Stellung hat Ihr Vater?

is: Falls Ihr Vater zurzeit nicht erwerbstätig ist (z. B. Rentner, Pensionär, Hausmann oder arbeitssuchend), beziehen Sie sich bitte auf die zuletzt ausgeübte Tätigkeit.

ao1: 1: … ungelernt 

ao2: 2: … angelernt

ao3: 3: … Facharbeiter

ao4: 4: … Vorarbeiter, Kolonnenführer

ao5: 5: … Meister, Polier, Brigadier

ao6: 6: … mit ausführender Tätigkeit
z. B. Verkäufer, Datentypist, Sekretariatsassistent, Pflegehelfer

ao7: 7: … mit qualifizierter Tätigkeit
z. B. Sachbearbeiter, Buchhalter, technischer Zeichner

ao8: 8: … mit Fachverantwortung für Personal 
z. B. wissenschaftlicher Mitarbeiter, Prokurist, Abteilungsleiter bzw. Meister im Angestelltenverhältnis

ao9: 9: … mit umfassenden Führungsaufgaben und Entscheidungsbefugnissen 
z. B. Direktor, Geschäftsführer, Mitglied des Vorstandes

ao10: 10: … im einfachen Dienst 
z. B. Amtsgehilfe, Schaffner, Betriebsassistent, ab (Ober-)Gefreiter

ao11: 11: … im mittleren Dienst 
z. B. Polizei(haupt)meister, Sekretär, Gerichtsvollzieher, ab Unteroffizier

ao12: 12: … im gehobenen Dienst 
z. B. Inspektor, Lehrer, Amtsrat, Kriminalkommissar, ab Leutnant

ao13: 13: … im höheren Dienst 
z. B. Regierungsrat, Studienrat, Hochschullehrer, Rektor, Richter, ab Major

ao14: 14: … keine weiteren Mitarbeiter*innen

ao15: 15: … 1 bis 4 Mitarbeiter*innen

ao16: 16: … 5 und mehr Mitarbeiter*innen

ao17: 17: … keine weiteren Mitarbeiter*innen

ao18: 18: … 1 bis 4 Mitarbeiter*innen

ao19: 19: … 5 und mehr Mitarbeiter*innen

ao20: 20: … PGH-Mitglied

ao21: 21: … mit einer landwirtschaftlich genutzten Fläche bis unter 10 ha

ao22: 22: … mit einer landwirtschaftlich genutzten Fläche von 10 ha und mehr

ao23: 23: … Genossenschaftsbauer (ehemals LPG)

ao24: 24: !!Mithelfender Familienangehöriger!!

ao25: -11: !!nie berufstätig gewesen!!

mv: -12: !!weiß ich nicht!!

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: GOTO B2_2a2

hi: Überkategorien der Antwortoptionen:

>   st1: !!Arbeiter, und zwar …!! (ao1, ao2, ao3, ao4, ao5)

>   st2: !!Angestellter, und zwar …!! (ao6, ao7, ao8, ao9)

>   st3: !!Beamter, Richter, Berufssoldat, und zwar …!! (ao10,
>   ao11, ao12, ao13)

>   st4: !!Akademiker in freiem Beruf (z.B. Rechtsanwalt, niedergelassener Arzt, Steuerberater, Künstler), und zwar…!! (ao14,
>   ao15, ao16)

>   st5: !!Selbstständiger im Handel, im Gastgewerbe, im Handwerk, in der Industrie, der Dienstleistung, auch Ich-AG oder PGH-Mitglied und hat/hatte …!! (ao17, ao18, ao19, ao20)

>   st6: !!Selbständiger Landwirt bzw. Genossenschaftsbauer, und zwar …!!
>   (ao21, ao22, ao23)

\--------------------------

B2_2a2
==

tc:

vn: deltposm1

qt: Einfachauswahl mit Überkategorien

hl:

in:

q: Welche berufliche Stellung hat Ihre Mutter?

is: Falls Ihre Mutter zurzeit nicht erwerbstätig ist (z. B. Rentnerin, Pensionärin, Hausfrau oder arbeitssuchend), beziehen Sie sich bitte auf die zuletzt ausgeübte Tätigkeit.

ao1: 1: … ungelernt 

ao2: 2: … angelernt

ao3: 3: … Facharbeiterin

ao4: 4: … Vorarbeiterin, Kolonnenführerin

ao5: 5: … Meisterin, Polierin, Brigadierin

ao6: 6: … mit ausführender Tätigkeit
z. B. Verkäuferin, Datentypistin, Sekretariatsassistentin, Pflegehelferin

ao7: 7: … mit qualifizierter Tätigkeit
z. B. Sachbearbeiterin, Buchhalterin, technische Zeichnerin

ao8: 8: … mit Fachverantwortung für Personal 
z. B. wissenschaftliche Mitarbeiterin, Prokuristin, Abteilungsleiterin bzw. Meisterin im Angestelltenverhältnis

ao9: 9: … mit umfassenden Führungsaufgaben und Entscheidungsbefugnissen 
z. B. Direktorin, Geschäftsführerin, Mitglied des Vorstandes

ao10: 10: … im einfachen Dienst 
z. B. Amtsgehilfin, Schaffnerin, Betriebsassistentin, ab (Ober-)Gefreite

ao11: 11: … im mittleren Dienst 
z. B. Polizei(haupt)meisterin, Sekretärin, Gerichtsvollzieherin, ab Unteroffizierin

ao12: 12: … im gehobenen Dienst 
z. B. Inspektorin, Lehrerin, Amtsrätin, Kriminalkommissarin, ab Leutnantin

ao13: 13: … im höheren Dienst 
z. B. Regierungsrätin, Studienrätin, Hochschullehrerin, Rektorin, Richterin, ab Majorin

ao14: 14: … keine weiteren Mitarbeiter*innen

ao15: 15: … 1 bis 4 Mitarbeiter*innen

ao16: 16: … 5 und mehr Mitarbeiter*innen

ao17: 17: … keine weiteren Mitarbeiter*innen

ao18: 18: … 1 bis 4 Mitarbeiter*innen

ao19: 19: … 5 und mehr Mitarbeiter*innen

ao20: 20: … PGH-Mitglied

ao21: 21: … mit einer landwirtschaftlich genutzten Fläche bis unter 10 ha

ao22: 22: … mit einer landwirtschaftlich genutzten Fläche von 10 ha und mehr

ao23: 23: … Genossenschaftsbäuerin (ehemals LPG)

ao24: 24: !!Mithelfende Familienangehörige!!

ao25: -11: !!nie berufstätig gewesen!!

mv: -12: !!weiß ich nicht!!

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: GOTO B2_3a IF h_split=1 (50%)
    GOTO B2_3b IF h_split=2 (50%)

hi: Zwischenüberschriften zwischen den ao’s:

>   st1: !!Arbeiterin, und zwar … !! (ao1, ao2, ao3, ao4, ao5)

>   st2: !!Angestellte, und zwar …!! (ao6, ao7, ao8, ao9)

>   st3: !!Beamtin, Richterin, Berufssoldatin, und zwar …!! (ao10,
>   ao11, ao12, ao13)

>   st4: !!Akademikerin in freiem Beruf (z.B. Rechtsanwältin, niedergelassene Ärztin, Steuerberaterin, Künstlerin), und zwar …!! (ao14,
>   ao15, ao16)

>   st5: !!Selbstständige im Handel, im Gastgewerbe, im Handwerk, in der Industrie, der Dienstleistung, auch Ich-AG oder PGH-Mitglied und hat/hatte …!! (ao17, ao18, ao19, ao20)

>   st6: !!Selbständige Landwirtin bzw. Genossenschaftsbäuerin, und zwar…!!
>   (ao21, ao22, ao23)


\--------------------------

B2_2b
==

tc: 50 Prozent der Befragten

vn: deltposv2

qt: Einfachauswahl mit Überkategorien

hl:

in:

q: Welche berufliche Stellung hat Ihr Vater?

is: Falls Ihr Vater zurzeit nicht erwerbstätig ist (z. B. Rentner, Pensionär, Hausmann oder arbeitssuchend), beziehen Sie sich bitte auf die zuletzt ausgeübte Tätigkeit.

ao1: 1: … ungelernt 

ao2: 2: … angelernt

ao3: 3: … Facharbeiter

ao4: 4: … Vorarbeiter, Kolonnenführer

ao5: 5: … Meister, Polier

ao6: 6: … mit ausführender Tätigkeit
z. B. Sekretariatsassistent, Pflegehelfer

ao7: 7: … mit qualifizierter Tätigkeit
z. B. Sachbearbeiter, technischer Zeichner

ao8: 8: … mit Fachverantwortung für Personal 
z. B. Prokurist, Abteilungsleiter

ao9: 9: … mit umfassenden Führungsaufgaben und Entscheidungsbefugnissen 
z. B. Direktor, Geschäftsführer

ao10: 10: … im einfachen Dienst 
z. B. Amtsgehilfe, Schaffner

ao11: 11: … im mittleren Dienst 
z. B. Polizei(haupt)meister, Gerichtsvollzieher

ao12: 12: … im gehobenen Dienst 
z. B. Lehrer, Amtsrat

ao13: 13: … im höheren Dienst 
z. B. Studienrat, Hochschullehrer, Richter

ao14: 14: … keine weiteren Mitarbeiter*innen

ao15: 15: … 1 bis 4 Mitarbeiter*innen

ao16: 16: … 5 und mehr Mitarbeiter*innen

ao17: 17: … keine weiteren Mitarbeiter*innen

ao18: 18: … 1 bis 4 Mitarbeiter*innen

ao19: 19: … 5 und mehr Mitarbeiter*innen

ao20: 20: … PGH-Mitglied

ao21: 21: … mit einer landwirtschaftlich genutzten Fläche bis unter 10 ha

ao22: 22: … mit einer landwirtschaftlich genutzten Fläche von 10 ha und mehr

ao23: 23: … Genossenschaftsbauer (ehemals LPG)

ao24: 24: !!Mithelfender Familienangehöriger!!

ao25: -11: !!nie berufstätig gewesen!!

mv: -12: !!weiß ich nicht!!

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: GOTO B2_2b2

hi: Überkategorien der Antwortoptionen:

>   st1: !!Arbeiter, und zwar …!! (ao1, ao2, ao3, ao4, ao5)

>   st2: !!Angestellter, und zwar …!! (ao6, ao7, ao8, ao9)

>   st3: !!Beamter, Richter, Berufssoldat, und zwar …!! (ao10,
>   ao11, ao12, ao13)

>   st4: !!Akademiker in freiem Beruf (z.B. Rechtsanwalt, niedergelassener Arzt, Steuerberater, Künstler), und zwar…!! (ao14,
>   ao15, ao16)

>   st5: !!Selbstständiger im Handel, im Gastgewerbe, im Handwerk, in der Industrie, der Dienstleistung, auch Ich-AG oder PGH-Mitglied und hat/hatte …!! (ao17, ao18, ao19, ao20)

>   st6: !!Selbständiger Landwirt bzw. Genossenschaftsbauer, und zwar …!!
>   (ao21, ao22, ao23)

\--------------------------

B2_2b2
==

tc:

vn: deltposm2

qt: Einfachauswahl mit Überkategorien

hl:

in:

q: Welche berufliche Stellung hat Ihre Mutter?

is: Falls Ihre Mutter zurzeit nicht erwerbstätig ist (z. B. Rentnerin, Pensionärin, Hausfrau oder arbeitssuchend), beziehen Sie sich bitte auf die zuletzt ausgeübte Tätigkeit.

ao1: 1: … ungelernt 

ao2: 2: … angelernt

ao3: 3: … Facharbeiterin

ao4: 4: … Vorarbeiterin, Kolonnenführerin

ao5: 5: … Meisterin, Polierin

ao6: 6: … mit ausführender Tätigkeit
z. B. Sekretariatsassistentin, Pflegehelferin

ao7: 7: … mit qualifizierter Tätigkeit
z. B. Sachbearbeiterin, technische Zeichnerin

ao8: 8: … mit Fachverantwortung für Personal 
z. B. Prokuristin, Abteilungsleiterin

ao9: 9: … mit umfassenden Führungsaufgaben und Entscheidungsbefugnissen 
z. B. Direktorin, Geschäftsführerin

ao10: 10: … im einfachen Dienst 
z. B. Amtsgehilfin, Schaffnerin

ao11: 11: … im mittleren Dienst 
z. B. Polizei(haupt)meisterin, Gerichtsvollzieherin

ao12: 12: … im gehobenen Dienst 
z. B. Lehrerin, Amtsrätin, Kriminalkommissarin

ao13: 13: … im höheren Dienst 
z. B. Studienrätin, Hochschullehrerin, Richterin

ao14: 14: … keine weiteren Mitarbeiter*innen

ao15: 15: … 1 bis 4 Mitarbeiter*innen

ao16: 16: … 5 und mehr Mitarbeiter*innen

ao17: 17: … keine weiteren Mitarbeiter*innen

ao18: 18: … 1 bis 4 Mitarbeiter*innen

ao19: 19: … 5 und mehr Mitarbeiter*innen

ao20: 20: … PGH-Mitglied

ao21: 21: … mit einer landwirtschaftlich genutzten Fläche bis unter 10 ha

ao22: 22: … mit einer landwirtschaftlich genutzten Fläche von 10 ha und mehr

ao23: 23: … Genossenschaftsbäuerin (ehemals LPG)

ao24: 24: !!Mithelfende Familienangehörige!!

ao25: -11: !!nie berufstätig gewesen!!

mv: -12: !!weiß ich nicht!!

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: GOTO B2_3a IF h_split=1 (50%)
    GOTO B2_3b IF h_split=2 (50%)

hi: Zwischenüberschriften zwischen den ao’s:

>   st1: !!Arbeiterin, und zwar … !! (ao1, ao2, ao3, ao4, ao5)

>   st2: !!Angestellte, und zwar …!! (ao6, ao7, ao8, ao9)

>   st3: !!Beamtin, Richterin, Berufssoldatin, und zwar …!! (ao10,
>   ao11, ao12, ao13)

>   st4: !!Akademikerin in freiem Beruf (z.B. Rechtsanwältin, niedergelassene Ärztin, Steuerberaterin, Künstlerin), und zwar …!! (ao14,
>   ao15, ao16)

>   st5: !!Selbstständige im Handel, im Gastgewerbe, im Handwerk, in der Industrie, der Dienstleistung, auch Ich-AG oder PGH-Mitglied und hat/hatte …!! (ao17, ao18, ao19, ao20)

>   st6: !!Selbständige Landwirtin bzw. Genossenschaftsbäuerin, und zwar…!!
>   (ao21, ao22, ao23)


\--------------------------

B2_3a
==

tc: 50 Prozent der Befragten

vn: buchanzi1, buchanze1

qt: Einfachauswahl im Spaltenformat/Comparison

hl:

in:

q: Was schätzen Sie, wie viele Bücher besitzen Sie selbst aktuell und wie viele Bücher besaßen Ihre Eltern zum Zeitpunkt Ihrer Kindheit?

is: Als Hilfestellung: Auf einen Meter Regalbrett passen ungefähr 40 Bücher.
Zählen Sie bitte keine E-Books, Zeitungen und Zeitschriften mit.

is: Anzahl Bücher

it1: (buchanzi1): ich selbst

it2: (buchanze1): Eltern

ao1: 1: 0 bis 10

ao2: 2: 11 bis 25

ao3: 3: 26 bis 50

ao4: 4: 51 bis 100

ao5: 5: 101 bis 150

ao6: 6: 151 bis 200

ao7: 7: 201 bis 249

ao8: 8: 250 bis 300

ao9: 9: 300 bis 400

ao10: 10: 400 bis 500

ao11: 11: mehr als 500

mv: -12: : weiß ich nicht

ka:

vc:

av:

kh:

fv:

hv:

fo: ao12 absetzen

tr: GOTO B2_6

hi:

\--------------------------

B2_3b
==

tc: 50 Prozent der Befragten

vn: buchanzi2; buchanze2

qt: Einfachauswahl im Spaltenformat/Comparison

hl:

in:

q: Wie viele Bücher besitzen Sie selbst aktuell bzw. Ihre Eltern?

is: Als Hilfestellung: Auf einen Meter Regalbrett passen ungefähr 40 Bücher.
Zählen Sie bitte keine E-Books, Zeitungen und Zeitschriften mit.

is: Anzahl Bücher

it1: (buchanzi2): ich selbst

it2: (buchanze2): Eltern

ao1: 1: 0 bis 10

ao2: 2: 11 bis 25

ao3: 3: 26 bis 50

ao4: 4: 51 bis 100

ao5: 5: 101 bis 150

ao6: 6: 151 bis 200

ao7: 7: 201 bis 249

ao8: 8: 250 bis 300

ao9: 9: 300 bis 400

ao10: 10: 400 bis 500

ao11: 11: mehr als 500

mv: -12: weiß ich nicht

ka:

vc:

av:

kh:

fv:

hv:

fo: ao12 absetzen

tr: GOTO B2_6

hi:

\--------------------------

B2_4
=

tc:

vn: diskpol / disklit / diskkun / diskmus / diskspo / disktv / diskwiss

qt: Einfachauswahlmatrix

hl:

in:

q: Wie oft diskutieren Sie mit anderen in Ihrer Freizeit über folgende Themenbereiche?

is:

it1: (diskpol) politische oder soziale Fragen

it2: (disklit) Literatur

it3: (diskkun) Kunst

it4: (diskmus) Musik

it5: (diskspo) Sport

it6: (disktv) Serien, Filme (Fernsehen/Streaming)

it7: (diskwiss) wissenschaftliche Themen und Fragestellungen

st:

ao1: 1: 1: täglich

ao2: 2: 2: mehrmals in der Woche

ao3: 3: 3: einmal in der Woche

ao4: 4: 4: mehrmals im Monat

ao5: 5: 5: nie oder selten

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: GOTO B2_7

hi:

\--------------------------

B2_5
=

tc:

vn: freimus / freikunst / freikult / freiaba / freifreu / freikonz / freinet /
freispor / freiehr / freipc

qt: Einfachauswahlmatrix

hl:

in:

q: Wie häufig gehen Sie in Ihrer Freizeit folgenden Tätigkeiten nach?

is:

it1: (freimus) musizieren

it2: (freikunst) künstlerisch betätigen

it3: (freikult) kulturelle Veranstaltungen besuchen

it4: (freiaba) abends Ausgehen

it5: (freifreu) mit Freunden treffen

it6: (freikonz) auf Konzerte gehen

it7: (freinet) soziale Netzwerke nutzen

it8: (freispor) sportlich betätigen

it9: (freiehr) ehrenamtlich engagieren

it10: (freipc) Computer spielen

st:

ao1: 1: 1: nie

ao2: 2: 2: selten

ao3: 3: 3: manchmal

ao4: 4: 4: häufig

ao5: 5: 5: sehr häufig

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo: Items bitte zufällig rotieren.

tr: GOTO B2_4

hi:

\--------------------------

B2_6
=

tc:

vn: bezgew / bezmein / bezprob / bezsit / beztip / bezunth / bezfrag / bezfunt /
bezmis / bezwohl / bezuntp / bezint / bezplan

qt: Einfachauswahlmatrix

hl:

in:

q: Wenn Sie an die Beziehung zu Ihren Eltern denken, inwiefern treffen die
folgenden Aussagen zu?

is:

it1: (bezgew) Ich habe meinen Eltern gegenüber manchmal ein schlechtes Gewissen,
weil ich studiere.

it2: (bezmein) Die Meinung meiner Eltern ist mir sehr wichtig.  
it3: (bezprob) Wenn ich Probleme im Studium habe, dann spreche ich mit meinen
Eltern darüber.

it4: (bezsit) Meine Eltern können meine Lebenssituation gut nachvollziehen

it5: (beztip) Meine Eltern geben mir Tipps, wenn es um mein Studium geht.

it6: (bezunth) Ich fahre oft nach Hause, um meine Eltern zu unterstützen.

it7: (bezfrag) Meine Eltern fragen regelmäßig nach, wie es im Studium läuft.

it8: (bezfunt) Nach meinem Studium möchte ich meine Eltern finanziell
unterstützen.

it9: (bezmis) Ich fühle mich von meinen Eltern oft unverstanden.

it10: (bezwohl) Bei meinen Eltern fühle ich mich richtig wohl.

it11: (bezuntp) In Prüfungsphasen kann ich mich auf die Unterstützung meiner
Eltern verlassen.

it12: (bezint) Meine Eltern interessieren sich für das, was ich studiere.

it13: (bezplan) Meine Eltern fänden es besser, wenn ich arbeite anstatt zu
studieren.

st:

ao1: 1: 1: trifft gar nicht zu

ao2: 2: 2

ao3: 3: 3

ao4: 4: 4

ao5: 5: 5: trifft voll und ganz zu

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo: Items bitte zufällig rotieren.

tr: GOTO B2_8a IF sabsan = 1 OR sabsan = 2
    GOTO B2_8b IF sabsan >=3
    GOTO B2_8b IF sabsan=MISSING
hi:

\--------------------------

B2_7
=

tc:

vn: skkarr / skeuro / skwiss / skjobs / skantr / skausl

qt: Einfachauswahlmatrix

hl:

in:

q: Wie wahrscheinlich ist es, dass jemand aus Ihrem persönlichen Umfeld…

is:

it1: (skkarr) … Ihnen hilfreiche Ratschläge für den weiteren Berufs- und
Karriereweg gibt?

it2: (skeuro) … Ihnen spontan 1000 € leiht?

it3: (skwiss) … Ihre wissenschaftlichen Arbeiten gegenliest?

it4: (skjobs) … Ihnen einen Job oder ein Praktikum vermittelt?

it5: (skantr) … Ihnen beim Ausfüllen von amtlichen Anträgen (z.B. Bafög,
Steuererklärung) helfen würde?

it6: (skausl) … Ihnen nahelegt, im Ausland zu studieren?

st:

ao1: 1: 1: sehr unwahrscheinlich

ao2: 2: 2

ao3: 3: 3

ao4: 4: 4

ao5: 5: 5: sehr wahrscheinlich

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo: Items bitte zufällig rotieren.

tr: GOTO B2_9a if h_split=1 (50%)
    GOTO B2_9b if h_split=2 (50%)
    
hi:

\--------------------------

B2_8a
==

tc: sabsan = 1 OR sabsan = 2

vn: bilaspab / bilaspma / bilaspdr / bilaspber

qt: Einfachauswahlmatrix

hl:

in:

q: Was denken Sie: Wie wichtig ist es Ihren Eltern, dass Sie…

is:

it1: (bilaspab) … einen Hochschulabschluss erreichen?

it2: (bilaspma) … einen Masterabschluss erreichen?

it3: (bilaspdr) … einen Doktortitel erreichen?

it4: (bilaspber) … beruflich ganz weit nach vorne kommen?

st:

ao1: 1: 1: sehr unwichtig

ao2: 2: 2

ao3: 3: 3

ao4: 4: 4

ao5: 5: 5: sehr wichtig

mv: -12: weiß ich nicht

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:   GOTO B2_10

hi:

\--------------------------

B2_8b
==

tc: IF sabsan \<\> 1 OR sabsan \<\> 2

vn: bilaspab1 / bilaspdr1 / bilaspber1

qt: Einfachauswahlmatrix

hl:

in:

q: Was denken Sie: Wie wichtig ist es Ihren Eltern, dass Sie…

is:

it1: (bilaspab1) … einen Hochschulabschluss erreichen?

It2: (bilaspdr1) … einen Doktortitel erreichen?

It3: (bilaspber1) … beruflich ganz weit nach vorne kommen?

st:

ao1: 1: 1: sehr unwichtig

ao2: 2: 2

ao3: 3: 3

ao4: 4: 4

ao5: 5: 5: sehr wichtig

mv: -12: weiß ich nicht

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:   GOTO B2_10


hi:

\--------------------------

B2_9a
==

tc: 50 Prozent der Befragten

vn: einkberuf1; einkba1; einkma1; einkstex11; einkstex21; einkdr1

qt: Einfachauswahl im Spaltenformat/Comparison

hl:

in:

q: Was denken Sie: Wie hoch ist das durchschnittliche monatliche Nettoeinkommen in Ihrem Berufsfeld...

is: Beziehen Sie Ihre Angaben auf das Netto-Gehalt, d.h. Einkommen abzüglich
Steuer.

it1: (einkberuf1):  … mit einer Berufsausbildung?

it2: (einkba1): … mit einem Bachelorabschluss? 

it3: (einkma1):  … mit einem Masterabschluss?

it4: (einkstex1): … mit dem ersten Staatsexamen?

it5: (einkstex21):  … mit dem zweiten Staatsexamen?

it6: (einkdr1): … mit einer Promotion?

st:

ao1: 1: unter 1.000 €

ao2: 2: 1.000 € bis unter 1.500 €

ao3: 3: 1.500 € bis unter 2.000 €

ao4: 4: 2.000 € bis unter 2.500 €

ao5: 5: 2.500 € bis unter 3.000 €

ao6: 6: 3.000 € bis unter 4.000 €

ao7: 7: 4.000 € bis unter 5.000 €

ao8: 8: 5.000 € bis unter 10.000 €

ao9: 9: 10.000 € und mehr

mv: -12: : weiß ich nicht

ka:

vc:
SHOW it4 and it5 if sabsan=3 [SDK-stu#05] Grundprogramm

SHOW it2 and it3 if sabsan!=3 [SDK-stu#05] Grundprogramm

av:

kh:

fv:

hv:

fo: ao10 absetzen

tr: GOTO D3_13 IF masterplan=9, 10, 11, 12
    GOTO A_54 IF masterplan=7, 8, 14

hi:

\--------------------------

B2_9b
==

tc: 50 Prozent der Befragten

vn: einkberuf2; einkba2; einkma2; einkstex12; einkstex22; einkdr2; einkka2

qt: Offene Angabe

hl:

in:

q: Was denken Sie: Wie hoch ist das durchschnittliche monatliche Nettoeinkommen in Ihrem Berufsfeld...

is: Beziehen Sie Ihre Angaben auf das Netto-Gehalt, d.h. Einkommen abzüglich
Steuer.

it:

st:

ao1 (einkberuf2): 5, Präfix: … mit einer Berufsausbildung: , Suffix: €/Monat

ao2 (einkba2): 5, Präfix: … mit einem Bachelorabschluss: , Suffix: €/Monat

ao3 (einkma2): 5, Präfix: … mit einem Masterabschluss: , Suffix: €/Monat

ao4 (einkstex12): 5, Präfix: … mit dem ersten Staatsexamen: , Suffix: €/Monat

ao5 (einkstex22): 5, Präfix: … mit dem zweiten Staatsexamen: , Suffix: €/Monat

ao6 (einkdr2): 5, Präfix: … mit einer Promotion: , Suffix: €/Monat

mv: (einkka2): -12, weiß ich nicht

ka:

vc: 
SHOW ao4 and ao5 if sabsan=3 [SDK-stu#05] Grundprogramm

SHOW ao2 and ao3 if sabsan!=3 [SDK-stu#05] Grundprogramm

av:

kh:

fv:

hv:

fo: ao7 absetzen

tr: GOTO D3_13 IF masterplan=9, 10, 11, 12
    GOTO A_54 IF masterplan=7, 8, 14


hi:

\--------------------------

B2_10
==

tc:

vn: promno / promges / promelt / promgroß / promver

qt: Mehrfachauswahl mit vertikalen ao

hl:

in:

q: Hat in Ihrer Familie bereits jemand eine Promotion begonnen oder erfolgreich
abgeschlossen?

is:

it:

st:

ao1 (promno): nein

ao2 (promges): ja, Geschwister

ao3 (promelt): ja, Eltern

ao4 (promgroß): ja, Großeltern

ao5 (promver): ja, andere Verwandte

mv: -12: weiß ich nicht

ka:

vc:

av:

kh:

fv:

hv:

fo: ao6 absetzen

tr: GOTO A_34

hi: [ao1 (promno): nein] soll exklusiv sein
