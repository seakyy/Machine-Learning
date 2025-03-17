# Machine-Learning-Projekt: Stellar Classification Dataset - SDSS17

### Gewählter Datensatz
Name: Stellar Classification Dataset - SDSS17
Quelle: Öffentliche Datenquelle (Kaggle.com)
Lizenz: Public Domain (SDSS)
Anzahl der Einträge: 100.000 Zeilen, 18 Spalten

### Warum dieser Datensatz?
Ich habe diesen Datensatz gewählt, da die Klassifikation von Himmelsobjekten eine spannende Anwendung für Machine Learning ist. Besonders interessant ist es, zu analysieren, welche Faktoren eine Rolle spielen, um Sterne, Galaxien und Quasare voneinander zu unterscheiden. Der Datensatz bietet:
- Reale astronomische Beobachtungen zur Kategorisierung von Objekten im Universum.
- Eine wissenschaftlich relevante Basis für Supervised Learning (Klassifikation).
- Die Möglichkeit, astronomische Muster durch Clustering oder Anomalieerkennung zu entdecken.


## Datensatzbeschreibung

Der Stellar Classification Dataset - SDSS17 enthält 100.000 Beobachtungen aus dem Sloan Digital Sky Survey (SDSS), einer der größten astronomischen Datenbanken. Ziel ist es, Machine-Learning-Modelle zu entwickeln, die basierend auf spektralen Merkmalen automatisch Sterne, Galaxien oder Quasare klassifizieren können.

### Beschreibung

obj_ID: Einzigartige ID für jedes Objekt in der SDSS-Datenbank.

alpha, delta: Himmelskoordinaten (Rektaszension & Deklination).

u, g, r, i, z: Helligkeitswerte in verschiedenen Spektralbändern.

class: Zielvariable (Stern, Galaxie oder Quasar).

redshift: Maß für die Rotverschiebung – gibt Hinweise auf die Entfernung.

plate, MJD, fiber_ID: Technische Identifikatoren für die Beobachtung.


### Datenschutzmassnahmen

Der Datensatz enthält keine persönlichen Daten und wurde ausschließlich für wissenschaftliche Zwecke erhoben.

Alle Informationen sind frei verfügbar und öffentlich zugänglich.

Die Daten stammen von einer astronomischen Himmelsbeobachtung und beeinträchtigen keine Datenschutzrichtlinien.



### Einschränkungen des Datensatzes

Ein Nachteil dieses Datensatzes ist, dass er keine Zeitreiheninformationen enthält – zukünftige oder sich verändernde Objekte können nicht vorhergesagt werden. Zudem sind einige Kategorien möglicherweise nicht gleichmäßig verteilt, was zu Class Imbalance führen könnte. Eine Verbesserung wäre die Ergänzung weiterer astronomischer Merkmale oder neuer Daten aus zukünftigen SDSS-Releases.


## Mögliche Machine-Learning-Anwendungen
- Klassifikation: Vorhersage, ob ein Objekt ein Stern, eine Galaxie oder ein Quasar ist.
- Clustering: Entdeckung unbekannter Gruppen oder Muster in den Daten.
- Anomalieerkennung: Identifikation von seltenen oder aussergewöhnlichen Objekten.

### Randinfos
Ich habe den Stellar Classification Dataset - SDSS17 gewählt, weil mich das Universum und die Astrophysik schon immer fasziniert haben. Schon als Kind habe ich gerne Dokumentationen über den Weltraum geschaut und mir vorgestellt, wie es wäre, ferne Galaxien zu erforschen. Einer meiner Lieblingsfilme ist Interstellar, weil er auf spannende Weise Wissenschaft und Science-Fiction verbindet.

Mit diesem Datensatz kann ich meine Begeisterung für den Weltraum mit Machine Learning verknüpfen. Ich finde es spannend, dass echte astronomische Beobachtungen aus dem Sloan Digital Sky Survey (SDSS) genutzt werden können, um Sterne, Galaxien und Quasare automatisch zu klassifizieren. Das zeigt, wie moderne Technologien uns helfen, das Universum besser zu verstehen.

Besonders interessant finde ich, dass die Rotverschiebung (Redshift) im Datensatz enthalten ist, die eine entscheidende Rolle bei der Erforschung der Expansion des Universums spielt. Mit Machine Learning kann ich untersuchen, welche Merkmale dabei helfen, Himmelsobjekte voneinander zu unterscheiden – genau wie Astronomen es in der realen Forschung tun. Dieses Projekt gibt mir die Möglichkeit, mit echten Weltraumdaten zu arbeiten und mein Wissen über KI und Astrophysik zu erweitern.


### Was kann man vorhersagen?
Falls Ihnen der Datensatz nichts sagt, kann ich kurz erklären was man mithilfe ML vorhersagen kann:
- Klassifikation des Objekttyps (GALAXY, QSO, STAR)
- Vorhersage des Redshifts
- Unterscheidung zwischen Sternen und fernen Objekten
- Bestimmung von ungewöhnlichen Objekten (Outlier Detection)
