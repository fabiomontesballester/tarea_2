# codiShoppingCard.md: Pull Request

Una Pull Request (PR) és una sol·licitud en plataformes com GitHub o GitLab per proposar canvis en un repositori, permetent que altres desenvolupadors els revisin abans d'integrar-los a la branca principal com "main" o "master" [web:1].

## Què és una Pull Request?
- Una Pull Request crea una proposta de fusió des d'una branca secundària cap a la principal, on el propietari del repositori decideix si acceptar-la [web:1][web:9].
- Serveix per col·laborar en equips, especialment en projectes oberts, on un contribuidor fa un "fork" del repositori, implementa canvis i sol·licita la seva inclusió [web:3].
- El procés inclou crear una branca (`git checkout -b nova-rama`), fer commits (`git commit -am 'missatge'`), pujar-la (`git push origin nova-rama`) i obrir la PR des de la interfície web [web:1].

## Avantatges
- Millora la qualitat del codi mitjançant revisions per pares (peer review), detectant errors abans de la fusió [web:1][web:8].
- Fomenta la col·laboració i el feedback, generant diferents punts de vista i augmentant la cohesió de l'equip [web:8].
- Permet un procés ordenat d'integració i proves automàtiques abans del merge [web:6][web:10].

## Desavantatges
- Pot causar retards en entorns àgils, ja que les branques llargues augmenten conflictes de fusió (merge conflicts) [web:12].
- Les PR grans són difícils de revisar, allunyant-se de pràctiques àgils com revisions ràpides i petites [web:6][web:10].
- Requereix temps addicional per revisions i possibles canvis iteratius [web:14].

## Bones Pràctiques
- Mantingues les PR petites i enfocades en una sola tasca per facilitar revisions ràpides [web:6][web:10].
- Inclou descripcions clares, proves que passen i sense warnings del compilador [web:10].
- Executa tests locals i assegura't que el codi funcioni abans d'obrir la PR [web:10].

