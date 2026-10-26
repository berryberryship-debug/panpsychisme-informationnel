# Panpsychisme informationnel : vers une formalisation dynamique des relations entre champ, information et expérience subjective

## 1. Introduction

Ce projet explore comment des structures dynamiques, des invariants informationnels et des mécanismes de mémoire peuvent être formalisés et testés par simulation, dans le but d’étudier leurs relations possibles avec l’organisation physique et l’expérience subjective.

Il réunit plusieurs axes de recherche : systèmes classiques, reconnaissance de structures sous transformations, dynamique quantique, mémoire et dépendance à l’histoire. Son objectif est de construire un cadre mathématique explicite dans lequel les hypothèses peuvent être comparées à des résultats numériques et soumises à des critères de réfutation.

L’hypothèse directrice est que les relations entre organisation, information et manifestation pourraient être aussi importantes que les propriétés locales prises isolément. Cette proposition constitue un programme de recherche, et non une conclusion ontologique déjà établie.

## 2. Statut scientifique et niveaux d’interprétation

Le projet distingue quatre niveaux :

1. **Résultat numérique** — valeurs calculées, trajectoires simulées, métriques et figures produites par un programme.
2. **Résultat mathématique ou méthodologique** — propriétés établies sous des hypothèses explicites, contrôles pertinents et comparaisons reproductibles.
3. **Correspondance physique** — justification du lien entre les variables simulées et un système physique ou biologique identifiable.
4. **Interprétation ontologique** — hypothèses concernant le statut fondamental de l’information, de l’organisation ou de l’expérience subjective.

Ces niveaux ne sont pas interchangeables. Une simulation reproductible ne constitue pas, à elle seule, une validation expérimentale. Une régularité numérique ne devient pas automatiquement un théorème. Une propriété mathématique ne suffit pas à établir une correspondance physique, et cette correspondance ne démontre pas à elle seule une thèse sur la conscience.

Les résultats présentés doivent donc être évalués selon les modèles utilisés, les hypothèses, les conditions initiales, les contrôles, les métriques, les incertitudes et les limites de généralisation.

## 3. Les trois piliers de la recherche

### 3.1. Systèmes classiques : conservation, topologie et symétrie

Les expériences numériques de la série V45–V57 explorent des propriétés de systèmes classiques, notamment la conservation, les changements topologiques et la brisure de symétrie.

L’objectif est de caractériser les conditions dans lesquelles certaines propriétés persistent, se transforment ou disparaissent dans les modèles étudiés.

Les conclusions doivent rester liées aux équations, aux conditions aux limites, aux paramètres et aux diagnostics effectivement utilisés. Une annihilation ou une transition observée numériquement ne démontre pas, sans analyse supplémentaire, une loi universelle.

### 3.2. Invariance contextuelle : phase, amplitude et transformations

Les expériences de la série V68–V76 examinent la capacité de différentes signatures à reconnaître des objets lorsque leurs trajectoires ou certains paramètres varient.

Les premières expériences factorielles suggèrent que, dans le générateur utilisé, la signature d’amplitude spectrale peut conserver une information discriminante importante entre différentes trajectoires. La performance dépend toutefois de la famille d’objets, des paramètres variables, de la métrique et du protocole de test.

L’enjeu est de distinguer trois propriétés :

- la **stabilité** d’une signature sous une transformation ;
- son **invariance** au sens défini par le modèle ;
- sa **discrimination**, c’est-à-dire sa capacité à distinguer les objets qui doivent rester différents.

Ces propriétés doivent être évaluées séparément. Une bonne reconnaissance dans un ensemble simulé ne démontre pas une invariance générale, et la comparaison entre amplitude, phase et signature combinée exige des métriques suffisamment comparables.

### 3.3. Dynamique quantique : mémoire, histoire et durée

Les scripts V77–V79 explorent des modèles de dynamique quantique, de mémoire non markovienne et de dépendance à l’histoire.

La question centrale est de déterminer dans quelles conditions l’évolution d’un système réduit peut dépendre de son historique ou de corrélations avec son environnement, au-delà de ce que représente son état instantané dans une description donnée.

La série comprend également une exploration conceptuelle inspirée de la philosophie de la durée de Henri Bergson. Cette articulation est une piste interprétative : une dépendance dynamique à l’histoire ne suffit pas à démontrer l’existence d’une durée vécue ni à établir un lien causal entre mémoire physique et expérience subjective.

Pour renforcer ces résultats, il faut documenter les équations, les paramètres, les contrôles, les répétitions, les métriques et les conditions exactes sous lesquelles les trajectoires divergent.

## 4. Ce que le projet ne prétend pas

À ce stade, le projet ne prétend pas :

- démontrer que la conscience est une propriété fondamentale de l’univers ;
- établir que l’information, la phase ou l’amplitude spectrale est en elle-même consciente ;
- démontrer que la mémoire non markovienne équivaut à une mémoire vécue ;
- établir une équivalence entre un modèle quantique et la phénoménologie bergsonienne ;
- présenter des résultats de simulation comme des observations expérimentales ;
- généraliser une performance numérique au-delà des conditions testées ;
- revendiquer une validation scientifique indépendante sans réplication et examen externes.

Le panpsychisme informationnel constitue ici un cadre d’interprétation et une hypothèse de recherche. Sa valeur scientifique dépendra de la capacité à formuler des prédictions distinctives, à les confronter à des hypothèses concurrentes et à préciser les résultats qui conduiraient à abandonner ou réviser les propositions avancées.

## 5. Structure du dépôt

L’organisation du dépôt vise à séparer les prototypes, les résultats, les visualisations et les axes expérimentaux.

```text
gw/
├── README.md
├── 00_archives_prototypes/
├── 01_resultats_conservation_topologie/
├── 02_resultats_attention_inhibition/
├── 03_resultats_phase_amplitude/
├── 04_resultats_invariance_contextuelle/
├── 05_quantique/
├── images_memoire/
├── v75_factoriel.py
└── v75_factoriel_v2.py
