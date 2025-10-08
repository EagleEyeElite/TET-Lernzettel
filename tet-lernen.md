Zusammenfassung:

- Stetigkeitbedingnen (herleitung: nicht in Klausur erfolerdlich)
- elektrische polarisation, elektirsches feld in der Materie (auch nicht Klausur notwenig, höchstens ganz öberflachlich)
- maxwell gleichung im frequeznbereich (herleiung fouriere (oder unüblich über laplace) vlt. in Klausur? - nur guessing)
- Definiton von Energie (Elektirsche Energie) - (könnte auch Klausur relevatn sein) : w_e = Integral E.dD = 1/2 eplision |E| ^2
-> poyntingscher satz (anschauen für klausur)
- Modellbildung: makrokospoosche: Wann gild die Modullelbildung, und wann nicht?


-> Physikalische Größen kennen (V/m^2 usw.)
-> Zylinderkoo. in Prüfung immer einfache Fälle (keine längliche Ausdruck, nach roh, phi usw. höchstens, dann einfach nur eine Ableitung, einfache Fälle)

Problemkassen:
- E statik, Strömungsfeld, M-statik
- quasistatik
- wellen (2 Wochen)

-> Einfache Überlegeung (Punktladung)
-> Überlagerung von Elementarlösungen (Columnb integral, punktladung, dipol, speigeldunt etc.)
-> Lösungen von Diff/ integral gleichungen (Mawxell vereinfachen, randbedingugnen, anfangswerte)



maxwell im stationären fall: d/dt = 0

Warum gilt rot grad = 0

Coulomb Integral (Superposition -> Integral) (Für Klausur wichtig)

r_p, r_q wird zu r , r' (aufpassen in Übungen)


Poisson, laplace gleichung,




Magnetostatik:

Potentialansatz: B=rot A => div B = div Rot A = 0
rot H = J => rot rot A = µJ

Klemmgrößen: Induktivität ist wie Kapaszivität
-> XI = Integral B da => ist eigentlich ein großes Phi
Xi ist nicht din norm, aber ist für die VL so


Magnetostatik: Warum ist ein Vektorpotieantil richtig, usw. (Kurz ein Satz mit reinschreiben können), warum ist vereinfachung der Maxwell gleichungen möglich?



Quasistationärefelder:
Verschiebungsstrom weglassen? -> Warum, wann ist das möglich?
dD/dt << |k E| und so

Helmholtz gleichung (herleitung dahin könnte gefragt werden, herleitung sollte man kennen)

Lösung der 1D-Helmholtz gleichung

Eindringtiefe

Wellengleichung:
diff gleichung 3d oder auch 1d : Laplace E - epsilin µ d^2/dt^2 E = 0 oder mit f(z,t) auch

frequeznbereich Lösung, Wellenzahl, Wellenvektor (Hinlaufende und Rücklaufende Welle)

Dispersionsbeziehung

Polarisation von Wellen

Ebene Wellen: Verluste: komplexe Permittivität


1 d und 3d Wellengleichung aus Maxwelleshcne Gleichung herleiten können

















-> Tut: Überblick:
Statik:
Elektrostatik:


E Statik d/dt = 0
------------------


stet. bedingung muss nicht hergeleitet werden, aber was ist die begründung: Maxwell Begründung, kommt durch maxwell: unstätigtiektein im Raum, rot E = 0 -> und dann dadurch tanential komponente muss springen



3 Lösungsmethonde (1 auf jeden Fall, vlt. auch 2, und sehr oft auch Randwertproblem):
    1. Integrationsansatz (Übung 5 A1 + Ha 1) -> Oft erstmal nach Phi Potential lösen, und dann per grad rest lösen. Phi (r) = Integral dPhi(r) = 1/4pi Integral Integral Integral rho (r_q) / |r_p - r_q|  dV_Q

    Hilfsvektoren drauf haben: Wenn Das koo. system verschoben ist. Bauen vektore, der vom Koo. system zur Ladung geht, und eine Vetkor der zu unserem Volumen zeigt. und dann gesuchter vector ist r = rp - rq


    2. Spiegelungsmethode (Übung 7 A1, HA3) -> E Feld kann nicht tangential springen -> Feldlienen zeigen immer senkrecht auf die Fläche.

    3. Randwertproblem: (Übung 6 A1, H2) -> Laplace Phi = 0 (diese Laplace Lösung wichtig, und wird versucht gelöst zu werden)
    -> Sperationsansatz: LGS -> Phi(x,y,z) = f(x) * g(x) * h(z)
    -> J''(x) / f(x) + g''(y)/g(y) + h''(z)/h(z) = 0
    -> K_x + K_y  K_z = 0
    allg. Lösung: f(x) = skalare lsg oder sin(..) cos(..) oder e^.. e^-..
    reduzierte Lösung
    Randbedingung: Es muss sin, sein, kann auch einfach über einen Satz begründet werden, (keliner Satz), durch oberen Fläche oder so, muss sin sein
    Hinweis: wenn f(x) = sin, dann muss g(y) = e sein, aber wenn irgenwo gleich potential 0 sein muss (z.b. geschlossene Rand), dann kombieneren wir über hypberbolische Funktion (sinh/ cosh) -> z.B. auch über e fkt aufschreiben können

    -> Hausuafbage mit Hyperbolikus: letztes Jahr gab es eine Übung mit Flächenladung, (ähnlch zur aktuellen HA) -> da ist Musterlösung zu sehen

Magnetostatik: (Tut 8)
rot H = J => rot rot A = µJ => grad div A - laplacian A = µJ (dann selber schreiben: Coulomb Eichung, schreiben sie nicht in der Aufgabe, aber sollen wir dann selber machen. Es gibt ein Freiheitsgrad den wir setzen. Hier: div A = 0)
div B = 0 => nach eichung: laplacinan A = -µJ -> Dann Lösung ist genau so gleich wie bei der elektrostatik
Vektorpotieantial A => B = rot A        (weil div rot A = 0)
Lösungansätze
    1. immer Integrationsansatz
    Flächenströme J, oder über Oberfläche K (wird meistens nicht benuttz)
    Eigentlich in der Klausur: Einfacher Strom: I über z.B. einer Feder (drehneder strom leitung I), oder Strom der in einer Raute fließt (4 eck), und dann über Symmetrie, nur ein teil zu lösen müssen
    Leiterschleifen:
    Bio Servart: H(r_p) = Integral dH(r_p) = I/4pi Integral dr_Q x (r_p - r_Q) / |r_p - r_q|^3
    -> Idee r_Q (vektor zeigt auf Quelle), dann ableiten: d_r_Q bilden -> dann einfacher

    -> Bevor man rechent: überlegen: wie sieht Lösung aus (mit der Handregel, fürht das B feld heraus oder herein, nach  z oben oder nach unten, macht es dann einfacher)

    A(r_p) = Integral dA(R_p) = µ_0I/4pi Integral dr_Q/|r_p - r_Q|

    A aufzustellen ist einfacher als H aufzustellen und dann damit zu rechen
    -> am Ende: rot A = (...), einfacher da nur einmal ableiten

    2. Strömungsfeld (kam nur einmal ran, muss vlt. nicht in der Klausur rankommen, kann auf Lücke gelernt werden)

    rot E = 0
    rot H = J <=> rot H = kappa E
    div (eplison E ) = 0
    -> Kombinert: Potentialgelichugn: div (kappa grad(Phi))  = 0 (Theretisch mit eplsion, ist aber eignelitch immer konstatn, und kann dann herausgezogen werden hur 0 hin)
    Materialeig. J = k* E

    0 = div (kappa grad Phi) => wenn kappa konstant => laplacian Phi = 0



Magnetoquasistik MQS: (Tut 11 A1 + A2) keine HA, kommt aber gerne drauf an
(Tut 12 kommt nicht dran, auf Lücke lernen)


Oder z.b. Eindringtiefe (mit  dem verscheibungsstrom) ist so kleien, da frequehn so groß z.B., dann geht das auch gut


Helmholtzgleichung:
LSG: {e^pz    e^-pz} -> {sinh (pz)      cosh(pz)}

-> Wenn platte unendlich lang ist, eine Strich (der unendlich lange und nach unte ngeht, dann wird das Magnetfeld, nicht kleiner so weiter ich nach außen gehe, eignetlich weird, aber richtig, da Leiter unendlich lang ist.). Wenn zwei leiter, dann überlagerung. Wenn zwischne den zwei Leitern irgendwi was ist (kappa größer 0), dann werden die Lösung wegen diffuddieren Strom, wirds dann zu hypberbolischen Funktionen (skin effect usw.)


Bei Aufgabentyp:
H(z=0) = H_0 cos(wt)
Dann Lösen mit Eindringtiefe:
delta = sqrt(2/wµx)

Lösung ist immer: H(z) ~ H_0 e^(-(Hj) Z/delta) = H_0 e^-z/delta  e^jz/delta

-> wenn Lösung gedämpte cos curve ist: e^-z * cos(wt)

Lösen im Freq. Bereich -> dann Trafo zurück in Zeitbereich

Wichtig (gute mathe identität): e^j Theta = cos(Theta) + j sin(Theta)
H(z,t) = Re{H(Z) * e^jwt } = RE{H_0 e^-z/delta   e^-jz/delta   e^jwt} = H_0 e^-z/delta } = H_0 e^-z/delta  cos (wt - z/ delta)

Oft gefragt: an welcher Stelle z, hab ich nur noch hälfte von H_0 (Amplitdute)

delta=sqrt(2/wµ kappa)
H ~e^-z/delta => 1/2 != e^-z/delta <=> ln(1/2) = -z/delta <=> z=-sin(1/2)











Wellen: es wird nichts schweres rankommen: (Tut 13 A1 + A2, HA 5)


(das könnte in der 1) teilaufgabe rankommen)

laplace E - eplsion µ d^2E/dt^2 = 0             (d/dt -> jw, d^2/dt^2 -> -w^2)
 Laplace/fourire => laplcae E + w^2 eplsion µ E = 0       (wird auch Helmholtz Gelichung genannt)

 Beachte: Wellenzahl k = w^2 eplsion µ

 LSG: E(z) ~e^-jkz

 Dass wieder im Zeitbereich:
 E(z,t) = Re{e^-jkz  e^jwt} = cos(wt - kz)


Oder auch: (so was kann sehr gut rankommen) -> Tut13 A1

Wie sieht H(z) aus? -> rot E = -jwµ H <=> H = 1/-jwµ   rot E     für ebene Wellen
H=1/z n x E     mit z = swrt(µ/ epslion)




Wenn er fies ist dann kommt Tut13 A2 ran:
Verluste:
geg. wenn geringe Verluste: komplexes epsilion (jetzt e) => e = e' - je'' = e'sqrt(1-j tan delta) ~= e'(1-j (tan delta)/ 2)
e' = e_r e_0
e'' = kappa / w e
tan delta = e''/e'

ges: 1/2 = E(z= ?)

E~e^-jkz (jetzt ist k auch komplex)

=> k=q sqrt(µ e) = w sqrt(µe')sqrt(1- j tan delta) ~= w sqrt(µ e) (1- j tan delta / 2) = w sqrt(µ e') - jw sqrt(µ e') tan delta / 2

k = beta - j alpha


Auch Klausur frate: gib mir beta und alpha
-> beta ~= w sqrt(µe')          (Phasenterm)
    alpha ~= w sqer(w e') tan d / 2     (Dämfpungsterm)



(kommt wahrscheinlich nicht ran):
e ~e^-jkz = e^-j(beta - j alpha)z = e^-alpah z  e^-j beta
E(z, t) = Re{epslion e^jwt}



Mit E und H kann man gut noch Pointyng vector! berechnen

