# 1. Histoire et Philosophie de l'Information

Dorian Blanchard - Mémoire de fin d'études : Rendu du 7 novembre 2023



## 1.1. Résumé

Cet ouvrage, conformément à son titre et aux recherches qu'il a nécessité, énonce le passé, le présent, et ma pensée concernant le futur de la gestion de l'information. L'étude des connaissances existantes sur ce sujet vous replongera sûrement dans vos cours d'Histoire, elle mettra en situation le présent avec un abrégé allant de la préhistoire jusqu’à l'état actuel du monde scientifique, et plus particulièrement de l'informatique. Cette discipline récente permet désormais de solutionner et automatiser beaucoup de tâches pénibles, mais sa pratique en elle même reste fastidieuse. C'est pourquoi j'en ai fait le cœur de ma problématique, que je l'analyse pour la repenser dans un essai philosophique, et que la dernière partie se nomme "Comment repenser la gestion de l'information pour moderniser l'expérience développeur ?". À l'aide des parties précédentes analysant son origine, la conclusion proposera ainsi une solution informatique innovante, combinant des technologies et pratiques existantes pour se simplifier elle même en utilisant de la rétro-action, et de la méta-programmation à travers une interface graphique simple et agréable.

<div style="page-break-after: always;"></div>

## 1.2. Sommaire

- [1. Histoire et Philosophie de l'Information](#1-histoire-et-philosophie-de-linformation)
  - [1.1. Résumé](#11-résumé)
  - [1.2. Sommaire](#12-sommaire)
  - [1.3. Préface](#13-préface)
  - [1.4. Remerciements](#14-remerciements)
  - [1.5. Introduction](#15-introduction)
  - [1.6. Comprendre la problématique](#16-comprendre-la-problématique)
  - [1.7. Histoire](#17-histoire)
    - [1.7.1. Préhistoire](#171-préhistoire)
      - [1.7.1.1. Abaques](#1711-abaques)
      - [1.7.1.2. Premières villes et sociétés](#1712-premières-villes-et-sociétés)
      - [1.7.1.3. Bulle enveloppe](#1713-bulle-enveloppe)
    - [1.7.2. Antiquité](#172-antiquité)
      - [1.7.2.1. Prémices de l'Algèbre](#1721-prémices-de-lalgèbre)
      - [1.7.2.2. Quipu](#1722-quipu)
      - [1.7.2.3. Boulier](#1723-boulier)
      - [1.7.2.4. Code de Hammurabi](#1724-code-de-hammurabi)
      - [1.7.2.5. Grèce antique](#1725-grèce-antique)
        - [1.7.2.5.1. Thalès](#17251-thalès)
        - [1.7.2.5.2. Genèse de l'encryption](#17252-genèse-de-lencryption)
        - [1.7.2.5.3. Pythagore](#17253-pythagore)
        - [1.7.2.5.4. Dialectique](#17254-dialectique)
        - [1.7.2.5.5. Rhétorique](#17255-rhétorique)
        - [1.7.2.5.6. Sophistes et Sophismes](#17256-sophistes-et-sophismes)
        - [1.7.2.5.7. Socrate](#17257-socrate)
        - [1.7.2.5.8. Atomisme](#17258-atomisme)
        - [1.7.2.5.9. Cynisme](#17259-cynisme)
        - [1.7.2.5.10. Platon](#172510-platon)
        - [1.7.2.5.11. Mathématiques](#172511-mathématiques)
        - [1.7.2.5.12. Sténographie](#172512-sténographie)
        - [1.7.2.5.13. Géométrie Euclidienne](#172513-géométrie-euclidienne)
        - [1.7.2.5.14. Aristote](#172514-aristote)
        - [1.7.2.5.15. Stoïcisme](#172515-stoïcisme)
      - [1.7.2.6. Égypte antique](#1726-égypte-antique)
        - [1.7.2.6.1. Bibliothèque d'Alexandrie](#17261-bibliothèque-dalexandrie)
        - [1.7.2.6.2. Origines de la logique mécanique](#17262-origines-de-la-logique-mécanique)
        - [1.7.2.6.3. Calculateurs analogiques](#17263-calculateurs-analogiques)
        - [1.7.2.6.4. Vitruve](#17264-vitruve)
        - [1.7.2.6.5. Compilateurs d'Alexandrie](#17265-compilateurs-dalexandrie)
    - [1.7.3. Moyen-Âge](#173-moyen-âge)
      - [1.7.3.1. Aryabhata](#1731-aryabhata)
      - [1.7.3.2. Algèbre et Algorithme](#1732-algèbre-et-algorithme)
      - [1.7.3.3. Système de numération indo-arabe](#1733-système-de-numération-indo-arabe)
      - [1.7.3.4. Compilateurs Arabes](#1734-compilateurs-arabes)
      - [1.7.3.5. Occidentalisation des savoirs de l'Âge d'or arabe](#1735-occidentalisation-des-savoirs-de-lâge-dor-arabe)
      - [1.7.3.6. Typographie](#1736-typographie)
      - [1.7.3.7. Inventions italiennes](#1737-inventions-italiennes)
    - [1.7.4. Époque moderne](#174-époque-moderne)
      - [1.7.4.1. Héliocentrisme](#1741-héliocentrisme)
      - [1.7.4.2. Philosophes modernes](#1742-philosophes-modernes)
      - [1.7.4.3. Journalisme](#1743-journalisme)
      - [1.7.4.4. Binaire](#1744-binaire)
      - [1.7.4.5. Encryptions moderne](#1745-encryptions-moderne)
      - [1.7.4.6. Premières machines à calculer](#1746-premières-machines-à-calculer)
      - [1.7.4.7. Pédagogie moderne](#1747-pédagogie-moderne)
      - [1.7.4.8. Théorie générale des systèmes](#1748-théorie-générale-des-systèmes)
    - [1.7.5. Époque contemporaine](#175-époque-contemporaine)
      - [1.7.5.1. Genèse du libéralisme](#1751-genèse-du-libéralisme)
      - [1.7.5.2. Philosophes contemporains](#1752-philosophes-contemporains)
      - [1.7.5.3. Pédagogie contemporaine](#1753-pédagogie-contemporaine)
      - [1.7.5.4. Premières machines de saisie](#1754-premières-machines-de-saisie)
      - [1.7.5.5. Améliorations des calculateurs](#1755-améliorations-des-calculateurs)
      - [1.7.5.6. Inventions électroniques](#1756-inventions-électroniques)
        - [1.7.5.6.1. Communications à distances](#17561-communications-à-distances)
        - [1.7.5.6.2. Semis-conducteurs](#17562-semis-conducteurs)
        - [1.7.5.6.3. Prémices de l'affichage numérique](#17563-prémices-de-laffichage-numérique)
      - [1.7.5.7. Logique](#1757-logique)
      - [1.7.5.8. Genèse de la programmation](#1758-genèse-de-la-programmation)
    - [1.7.6. Première guerre mondiale et entre deux guerres](#176-première-guerre-mondiale-et-entre-deux-guerres)
      - [1.7.6.1. Théorie des jeux](#1761-théorie-des-jeux)
      - [1.7.6.2. Améliorations du stockage](#1762-améliorations-du-stockage)
      - [1.7.6.3. Tabulatrices](#1763-tabulatrices)
      - [1.7.6.4. Détections par ondes](#1764-détections-par-ondes)
      - [1.7.6.5. Alan Turing](#1765-alan-turing)
      - [1.7.6.6. Zuse Konrad](#1766-zuse-konrad)
      - [1.7.6.7. Calculs balistique](#1767-calculs-balistique)
      - [1.7.6.8. Hewlett Packard](#1768-hewlett-packard)
    - [1.7.7. Seconde guerre mondiale](#177-seconde-guerre-mondiale)
      - [1.7.7.1. Colossus Mark 1](#1771-colossus-mark-1)
      - [1.7.7.2. Harvard Mark 1](#1772-harvard-mark-1)
      - [1.7.7.3. Architecture de von Neumann](#1773-architecture-de-von-neumann)
      - [1.7.7.4. As we may think](#1774-as-we-may-think)
    - [1.7.8. Guerre froide et course à l'espace](#178-guerre-froide-et-course-à-lespace)
      - [1.7.8.1. Temps réel](#1781-temps-réel)
      - [1.7.8.2. Trackball](#1782-trackball)
      - [1.7.8.3. Norbert Wiener](#1783-norbert-wiener)
      - [1.7.8.4. SSEM](#1784-ssem)
      - [1.7.8.5. Manchester Mark I](#1785-manchester-mark-i)
      - [1.7.8.6. Théorie de l'information](#1786-théorie-de-linformation)
      - [1.7.8.7. Origines de l'Assembleur](#1787-origines-de-lassembleur)
      - [1.7.8.8. Ferranti Mark I](#1788-ferranti-mark-i)
      - [1.7.8.9. Compilateurs et premiers languages de haut niveau](#1789-compilateurs-et-premiers-languages-de-haut-niveau)
      - [1.7.8.10. Leo I](#17810-leo-i)
      - [1.7.8.11. IBM](#17811-ibm)
      - [1.7.8.12. Premiers langages de haut niveau opérationnels](#17812-premiers-langages-de-haut-niveau-opérationnels)
        - [1.7.8.12.1. Lisp](#178121-lisp)
      - [1.7.8.13. Théorie algorithmique de l'information](#17813-théorie-algorithmique-de-linformation)
      - [1.7.8.14. Computionnalisme](#17814-computionnalisme)
      - [1.7.8.15. Souris](#17815-souris)
      - [1.7.8.16. Luciano Floridi](#17816-luciano-floridi)
      - [1.7.8.17. Premières applications de l'IA](#17817-premières-applications-de-lia)
      - [1.7.8.18. Microprocesseur](#17818-microprocesseur)
      - [1.7.8.19. Course à l'espace](#17819-course-à-lespace)
      - [1.7.8.20. John Horton Conway](#17820-john-horton-conway)
    - [1.7.9. Popularisation et Mondialisation](#179-popularisation-et-mondialisation)
      - [1.7.9.1. Genèse d'internet](#1791-genèse-dinternet)
      - [1.7.9.2. Interfaces graphiques](#1792-interfaces-graphiques)
      - [1.7.9.3. Ordinateurs personnels](#1793-ordinateurs-personnels)
      - [1.7.9.4. Jeux vidéos](#1794-jeux-vidéos)
      - [1.7.9.5. GPS](#1795-gps)
      - [1.7.9.6. Homebrew computer club](#1796-homebrew-computer-club)
      - [1.7.9.7. Cerveau Chinois](#1797-cerveau-chinois)
      - [1.7.9.8. La chambre chinoise](#1798-la-chambre-chinoise)
      - [1.7.9.9. Mémoire flash et stockage optique](#1799-mémoire-flash-et-stockage-optique)
      - [1.7.9.10. Cerveau dans une cuve](#17910-cerveau-dans-une-cuve)
      - [1.7.9.11. Logiciel libre](#17911-logiciel-libre)
      - [1.7.9.12. Cadriciels et Open Source](#17912-cadriciels-et-open-source)
      - [1.7.9.13. World Wide Web](#17913-world-wide-web)
      - [1.7.9.14. Ordinateur quantique](#17914-ordinateur-quantique)
    - [1.7.10. Bilan passé](#1710-bilan-passé)
  - [1.8. Pratiques actuelles](#18-pratiques-actuelles)
    - [1.8.1. Méthodes d'aide à la structuration d'information](#181-méthodes-daide-à-la-structuration-dinformation)
      - [1.8.1.1. Décision](#1811-décision)
      - [1.8.1.2. Gestion de projets](#1812-gestion-de-projets)
        - [1.8.1.2.1. Roadmap](#18121-roadmap)
          - [1.8.1.2.1.1. Project charter](#181211-project-charter)
          - [1.8.1.2.1.2. GANTT](#181212-gantt)
          - [1.8.1.2.1.3. Business Model](#181213-business-model)
          - [1.8.1.2.1.4. Scrum](#181214-scrum)
      - [1.8.1.3. Conception](#1813-conception)
        - [1.8.1.3.1. Design thinking](#18131-design-thinking)
        - [1.8.1.3.2. Lean Startup](#18132-lean-startup)
        - [1.8.1.3.3. MVP](#18133-mvp)
    - [1.8.2. Appareils](#182-appareils)
    - [1.8.3. Usages et industrie du logiciel](#183-usages-et-industrie-du-logiciel)
      - [1.8.3.1. Navigation web](#1831-navigation-web)
      - [1.8.3.2. Automatisation](#1832-automatisation)
      - [1.8.3.3. Robotique](#1833-robotique)
      - [1.8.3.4. Aide à la décision](#1834-aide-à-la-décision)
      - [1.8.3.5. Progiciel](#1835-progiciel)
      - [1.8.3.6. Ludiciel](#1836-ludiciel)
      - [1.8.3.7. Jeux en ligne et MMO](#1837-jeux-en-ligne-et-mmo)
      - [1.8.3.8. Chiffrement actuels](#1838-chiffrement-actuels)
    - [1.8.4. Concepts et outils de programmation](#184-concepts-et-outils-de-programmation)
      - [1.8.4.1. Langages](#1841-langages)
      - [1.8.4.2. Ligne de commande](#1842-ligne-de-commande)
      - [1.8.4.3. Types et structure de donnée](#1843-types-et-structure-de-donnée)
      - [1.8.4.4. Bases de la programmation objet](#1844-bases-de-la-programmation-objet)
      - [1.8.4.5. UML](#1845-uml)
      - [1.8.4.6. Performances et Optimisations](#1846-performances-et-optimisations)
        - [1.8.4.6.1. Techniques](#18461-techniques)
        - [1.8.4.6.2. Managériales](#18462-managériales)
      - [1.8.4.7. Quelqu'un à généralement la solution](#1847-quelquun-à-généralement-la-solution)
      - [1.8.4.8. Principes SOLID](#1848-principes-solid)
      - [1.8.4.9. VSCode](#1849-vscode)
      - [1.8.4.10. Intelligence artificielle](#18410-intelligence-artificielle)
  - [1.9. Essai](#19-essai)
    - [1.9.1. Information](#191-information)
    - [1.9.2. IO](#192-io)
    - [1.9.3. Habitudes](#193-habitudes)
    - [1.9.4. Valeurs](#194-valeurs)
    - [1.9.5. Rapport de force, ordres de grandeur et précision](#195-rapport-de-force-ordres-de-grandeur-et-précision)
      - [1.9.5.1. Signaux forts et faibles](#1951-signaux-forts-et-faibles)
    - [1.9.6. Viralité](#196-viralité)
    - [1.9.7. Parasitage](#197-parasitage)
    - [1.9.8. Contexte et vérité](#198-contexte-et-vérité)
    - [1.9.9. Doute](#199-doute)
    - [1.9.10. Preuves](#1910-preuves)
    - [1.9.11. Apprentissage](#1911-apprentissage)
    - [1.9.12. Informatique et Éducation](#1912-informatique-et-éducation)
    - [1.9.13. Informatique et Cuisine](#1913-informatique-et-cuisine)
    - [1.9.14. Communication \& Compréhension](#1914-communication--compréhension)
    - [1.9.15. Professionnalisme](#1915-professionnalisme)
    - [1.9.16. Prestation vs édition de logiciel](#1916-prestation-vs-édition-de-logiciel)
    - [1.9.17. Division du travail](#1917-division-du-travail)
    - [1.9.18. Astrologie](#1918-astrologie)
    - [1.9.19. Divin](#1919-divin)
    - [1.9.20. Effets des croyances](#1920-effets-des-croyances)
    - [1.9.21. Intelligence](#1921-intelligence)
    - [1.9.22. Consciences](#1922-consciences)
    - [1.9.23. Anticipation](#1923-anticipation)
    - [1.9.24. Temps](#1924-temps)
    - [1.9.25. A posteriori](#1925-a-posteriori)
    - [1.9.26. Développement personnel](#1926-développement-personnel)
      - [1.9.26.1. Planifier et prendre son temps](#19261-planifier-et-prendre-son-temps)
      - [1.9.26.2. Rigueur et retravail](#19262-rigueur-et-retravail)
      - [1.9.26.3. Amélioration continue](#19263-amélioration-continue)
      - [1.9.26.4. Standardisation \& Universalité](#19264-standardisation--universalité)
      - [1.9.26.5. Do it now](#19265-do-it-now)
      - [1.9.26.6. Aide](#19266-aide)
      - [1.9.26.7. STOP](#19267-stop)
      - [1.9.26.8. Justification](#19268-justification)
      - [1.9.26.9. Critique](#19269-critique)
      - [1.9.26.10. Développement informatique](#192610-développement-informatique)
    - [1.9.27. Metagame](#1927-metagame)
  - [1.10. EditIDE ou "Comment repenser la gestion de l'information pour moderniser l'expérience développeur ?"](#110-editide-ou-comment-repenser-la-gestion-de-linformation-pour-moderniser-lexpérience-développeur-)
    - [1.10.1. Pourquoi la programmation est-elle aussi peu démocratisée ?](#1101-pourquoi-la-programmation-est-elle-aussi-peu-démocratisée-)
    - [1.10.2. Pourquoi un outil censé résoudre un problème en cause parfois des bloquants ?](#1102-pourquoi-un-outil-censé-résoudre-un-problème-en-cause-parfois-des-bloquants-)
    - [1.10.3. Qu'elle est l'origine des bugs ?](#1103-quelle-est-lorigine-des-bugs-)
    - [1.10.4. Comment l'interface permet et conditionne l'accès aux fonctionnalités ?](#1104-comment-linterface-permet-et-conditionne-laccès-aux-fonctionnalités-)
        - [1.10.4.0.1. Etude de cas UX/UI FL Studio VS Ableton](#110401-etude-de-cas-uxui-fl-studio-vs-ableton)
    - [1.10.5. Comment faire un logiciel en tant que service ?](#1105-comment-faire-un-logiciel-en-tant-que-service-)
      - [1.10.5.1. Site web](#11051-site-web)
        - [1.10.5.1.1. Etape 1 : Réaliser un site web](#110511-etape-1--réaliser-un-site-web)
        - [1.10.5.1.2. Etape 2 : ouvrir les ports](#110512-etape-2--ouvrir-les-ports)
        - [1.10.5.1.3. Etape 3 : mettre un serveur en service](#110513-etape-3--mettre-un-serveur-en-service)
        - [1.10.5.1.4. Étape 4 : Configurer un nom de domaine (Facultative)](#110514-étape-4--configurer-un-nom-de-domaine-facultative)
      - [1.10.5.2. Lancement du site au démarrage](#11052-lancement-du-site-au-démarrage)
      - [1.10.5.3. Bureau à distance](#11053-bureau-à-distance)
    - [1.10.6. Comment architecturer un système d'information ?](#1106-comment-architecturer-un-système-dinformation-)
    - [1.10.7. Qu'elle est la plus-value d'EditIDE ?](#1107-quelle-est-la-plus-value-deditide-)
        - [1.10.7.0.1. One thing at a time](#110701-one-thing-at-a-time)
        - [1.10.7.0.2. WYSIWYG](#110702-wysiwyg)
        - [1.10.7.0.3. Accessibilité](#110703-accessibilité)
        - [1.10.7.0.4. All in one](#110704-all-in-one)
        - [1.10.7.0.5. Visualisation](#110705-visualisation)
        - [1.10.7.0.6. Documentation](#110706-documentation)
        - [1.10.7.0.7. Gestion](#110707-gestion)
        - [1.10.7.0.8. Précision](#110708-précision)
    - [1.10.8. Qu'elle sont les conditions de succès d'un logiciel ?](#1108-quelle-sont-les-conditions-de-succès-dun-logiciel-)
  - [1.11. Postface : Rétrospective et métacognition](#111-postface--rétrospective-et-métacognition)
  - [1.12. Table des illustrations](#112-table-des-illustrations)
    - [1.12.1. http://toastytech.com/guis](#1121-httptoastytechcomguis)
  - [1.13. Annexes](#113-annexes)
      - [1.13.0.1. Bibliographie](#11301-bibliographie)
      - [1.13.0.2. Webographie](#11302-webographie)
      - [1.13.0.3. Lexique](#11303-lexique)
      - [1.13.0.4. Table des illustrations](#11304-table-des-illustrations)
      - [1.13.0.5. Page d’évaluation](#11305-page-dévaluation)


## 1.3. Préface

Présentation de mon parcours et des gros projets sur lequels j'ai travaillé en tant qu'étudiant, ou professionnel.

## 1.4. Remerciements

Je ne remercierai jamais assez mes parents et grand parents, qui ont eu la chance d'être propriétaires d'ordinateurs, et d'une connexion d'internet, avant ma naissance en 1999. Grâce à cela il ont eu la démarche raisonnée de m'introduire à cette technologie, sur des logiciels éducatifs qui m'ont permis de savoir lire à l'âge de 2 ans.

Merci à toutes les personnes et enseignants des entreprises et écoles qui m'ont accueillis, lors de ma scolarité, et de mon début de carrière, me transmettant une majeure partie ce que je sais aujourd'hui, et ce dans la bienveillance, grâce à des processus itératifs d'amélioration continue.

Merci aux logiciels libres, à l'open source, à Wikipédia et tout leurs contributeurs.

Merci à toutes et tous, car nos métiers et découvertes ne sont que rarement le fruit d'un génie isolé, mais bien d'une collaboration et de l'amélioration d'idées antérieures.

Enfin, merci à toute personne qui lit actuellement ce texte.



## 1.5. Introduction

La transmission d'information s'est fiabilisée au fil des époques, avec l'usage d'outils physique ; notamment des tablettes, plaques permettant de dessiner, d'écrire, lire, compter ; et ce jusqu'à pouvoir automatiser son traitement et son stockage, à l'aide de l'informatique, dont l'histoire ne commence concrètement qu'à la fin du 19 ème siècle.

De nos jours, nous interagissons quotidiennement avec des ordinateurs, que ce soit à l'aide de la programmation, ou des interfaces hommes-machines qui en sont issues. Pourtant, la grande majorité des utilisateurs, et même des personnes travaillant dans le domaine des Technologies de l'Information et de la Communication, ne connaissent pas la plupart des événements majeurs de son histoire.

Moi même n'ayant pas cette connaissance lorsque j'ai entrepris la rédaction de ce mémoire, j'ai décidé de me documenter et de rédiger un format accessible, avec ce qui m'a semblé être nécessaire pour comprendre le sujet, et ainsi le partager à vous, lecteurs de cet ouvrage.

Pour la rédaction de ce dernier, j'ai acquis 4 livres : 

- la 4e édition de "Computer, A History of the Information Machine" de Martin Campbell-Kelly, professeur émérite britannique, spécialisé dans l'histoire de l'informatique. Coécrite avec William F.Aspray, Jeffrey R. Yost, Honghong Tinn, et Gerardo Con Diaz.
- "The history of the computer : people, inventions, and technology that changed our world" de Rachel Ignotofsky
- "Histoire illustrée de l'informatique" d'Emmanuel Lazard et Pierre Mounier-Kuhn.
- "Transmettre" de Christophe André, Céline Alvarez, Catherine Gueguen, Matthieu Ricard, Frédéric Lenoir, Ilios Kotsou, Caroline Lesire

Les trois premiers livres ont chacun leurs avantages grâce à une approche différente d'un même sujet, sur lequel je m'attendais à trouver plus de bibliographie. Contrairement à ceux-ci, j'ai essayé d'avoir une démarche plus globale que l'informatique et l'ordinateur, qui sont des concepts très récent. Et ce en abordant le thème général qu'est l'information, tout en y ajoutant de la philosophie, ainsi que mon humble analyse subjective car j'aime penser, et que l'apprentissage des mathématiques et de l'informatique ont changé ma manière de concevoir le monde dans lequel nous vivons. Ce sont selon moi des philosophies à part entière, apportant des syntaxes et un vocabulaire, nécessitant un apprentissage constant de schémas de pensés dignes d'un logicien.

Dans ce mémoire, je vais donc revenir aux racines les plus ancestrales de la gestion de l'information, au vocabulaire et champ lexical qui y sont liés ou en découlent, ainsi qu'à leurs étymologies à travers leur [Histoire](#Histoire), qui représente toute la première partie de ce livre. J'y présenterai beaucoup de philosophes, scientifiques et de penseurs variés. De l'Antiquité aux époques plus modernes, les idées qu'ils ont amenées ont permis des inventions et progrès technologiques avec un développement de plus en plus rapide. Pourtant, les inventions qui ont le plus impacté l'humanité, resteront toujours les plus anciennes, avec au sommet d'entre elles, l'écriture.

J'aborderai aussi un sujet qui m'est cher, la programmation. Elle n'est pas forcement liée à l'informatique, c'est l'art de planifier et mettre en œuvre des étapes à suivre pour obtenir un résultat. Cela dit, elle passe inévitablement par de la gestion de l'information, à l'aide d'écriture, lecture, chiffrement, déchiffrement, émission, et réception.

Je m’intéresserai également à l'apprentissage qui représente l’acquisition et l'assimilation d'une information ou d'un système, très présent dans les technologies comme l'intelligence artificielle ; ainsi qu'à la pédagogie, propre à "l'animal social émotionnel" qu'est l'humain ; et à la compréhension du rapport maître / élève permettant la transmission de compétences.

L'ensemble de ses sujets, et l'information en général, prennent une place de plus en plus importante dans nos quotidien, cela s'accompagne d'un volume exponentiel d'informations mondialement échangées. Nous avons développés une relation symbiotique avec la technologie, qui nous permet aujourd'hui de communiquer et de jouer presque instantanément au niveau mondial, améliorant même parfois les conditions de vie et la santé, on parle d'ailleurs désormais de télé-santé. Pour autant, comme toutes les technologies récentes ayant un impact majeur, vient un rejet et une techno-phobie d'une certaine partie de la population pas encore convertie à son usage.

Avec mon point de vue de développeur web, je dresserai ensuite un [bilan de l’état actuel de l'informatique](#Pratiques-actuelles), de son marché, ses opportunités, ainsi qu'une étude de sa pratique moderne ; et ce afin d'en [identifier les problèmes](#Comprendre-la-problématique) que l'on y rencontre pour en dégager de possibles solutions, dressant ainsi un [essai](#Essai) philosophique expliquant ma projection en tant qu'acteur et éditeur de logiciels, pour [le futur de cette discipline](#EditIDE-ou-"Comment-repenser-la-gestion-de-l'information-pour-moderniser-l'expérience-développeur-?"), plus particulièrement la pratique que je souhaite en avoir en tant que créateur de services et contenu web.



Notes :

- L’Histoire ne se souvient que rarement de la première occurrence d’une invention, ce qu'il en reste est généralement sa démocratisation.
- Il est évident que tout les concepts scientifiques ne sont que des formulations écrites de théories issues de la raison, qui étaient déjà connues par certaines personnes de manière empirique.
- La majorité des mots sont poly-sémantiques, ils n'ont pas de signification unique. Ils ont même parfois des usages dont le sens dévie de son usage originel.
- Le savoir est magie pour les idiots, et secret de polichinelle pour les érudits.



## 1.6. Comprendre la problématique

L'informatique, étymologiquement "automatisation de la gestion de l'information", est un domaine récent et complexe, qui soulève beaucoup d'avancés technologiques mais également de craintes et de questionnements. En 2022, la programmation à l'origine des logiciels qui nous permettent d'utiliser le matériel informatique, n'était pratiquée que par 0.35% de la population. Elle requiert une rigueur suffisante pour dans un premier temps passer la compilation si elle a lieu, puis l'exécution du programme en résultant, et enfin les tests du comportement voulu dont le but est de vérifier que l'on a correctement implémenté la solution à notre problème informationnel. Une fois que tout cela est satisfait, il faut rendre le programme robuste afin d'assurer sa pérennité tout au long du développement des nouvelles fonctionnalités qui s'accumuleront inexorablement, et ce afin que toutes les existantes restent fonctionnelles, ce que l'intégration et le développement continu solutionne, permettant d'assurer la qualité d'un logiciel au fil de son développement.

Dans la deuxième partie de ce mémoire, je montrerai ainsi les avantages et inconvénients des outils de développeurs actuels et les biais introduits dans leurs pratiques, constituée des étapes décrites précédemment, avec des pistes de solutions. Actuellement, l'apprentissage de ces étapes et les coût de formation d'un nouvel employé en informatique sont importants. Simplifier la prise en main d'un projet informatique me semble être une opportunité technologique intéressante, qui permettrait à l'industrie informatique de se concentrer sur les réelles problématiques. Dans cette dernière, la matière première est la pensée du développeur, c'est l'acteur principal à l'origine des algorithmes qui régissent la gestion de l'information. Les développeurs réalisent des logiciels pour de multiples industries et sont pourtant, selon moi, les cordonniers les plus mal chaussés. On parle souvent d'expérience utilisateur, mais l'expérience développeur reste à désirer, voire archaïque. D'après moi, nous sommes au moyen âge du logiciel. La question fondamentale à laquelle je répondrait dans le troisième chapitre sera donc "*Comment repenser la gestion de l'information pour moderniser l'expérience développeur ?*".

Mais avant de parler des méthodes modernes et répondre à cette question, il me semble important de comprendre l'évolution de la pensée, des outils, des machines et de la technologie, ainsi comment l'humanité en est arrivée là, et surtout, comment faisait-on pour calculer, automatiser des actions, et gérer l'information avant l'invention des ordinateurs ?





[Retour](#Introduction)

## 1.7. Histoire

La première manière pour un être vivant de marquer l'histoire est universelle, c’est celle des fossiles et des dinosaures, celle d’avoir existé et laissé une trace, une information, stockée sur un support physique, sur notre Terre. La deuxième est l’art de sculpter des outils, actuellement estimé 3 millions d’années avant notre ère. La troisième est le dessin, au travers de la peinture ou de la gravure, dont les plus anciennes preuves sont rupestres, et âgées de 65 millénaires.

Relativement aux dates précédentes, l’écriture ne vient que récemment, elle a été attestée en Mésopotamie il y a 5 millénaires. Pourtant, c'est elle qui nous permettra à nous, humains, d'écrire notre Histoire, de transmettre des volumes d'informations variées, véridiques comme les faits ou de qualité comme des idées. Écrire permet de faire naître une information et potentiellement de la rendre éternelle. Les paroles s’envolent les écrits restent, c'est pourquoi la littérature est importante.

D'un point de vue Historique, notre génération laissera toujours une trace. Que ce soit sur un disque dur quelque part dans un grenier, dans un datacenter ou une web archive. Et même si tout disparaissait, il y aurait une preuve immuable et indestructible à échelle de la Terre. Les isotopes lourds que nous avons créés avec l'apparition des industries nucléaire seraient, même dans le cas d'un retour à l'âge de pierre causant un rude hiver civilisationnel, la preuve de l'existence de la nôtre.



### 1.7.1. Préhistoire

Avant même la naissance de l'écriture qui marque la fin de la préhistoire, les humains avait déjà besoin d'informations quantitatives, c'est à dire de compter et d'effectuer des calculs. Le premier réflexe à sûrement été de compter sur ses doigts, raison pour laquelle la base 10 est si présente dans l'histoire. Pour des nombres plus importants, il a fallu inventer d'autres stratagèmes et outils.




#### 1.7.1.1. Abaques

Définition et etymologie de l'abaque.

Présentation bâton de comptage, système unaire. Os de Lebombo. Os d'Ishango. Os coché.



#### 1.7.1.2. Premières villes et sociétés

Sédentarisation, agriculture, besoin de stockage. Urkesh, Ninive, Assur, Guzana, Uruk, Lagash, Ur. Premières civilisation, Sumer **-3500**. Vallée de l'Indus. Premiers conflits d'envergure.



#### 1.7.1.3. Bulle enveloppe

Mésopotamie, sphères d'argile, bulle comptable. Sceau-cylindre. Garantir la véracité d'une information pour le transport et l'échange de marchandise par un transporteur.



### 1.7.2. Antiquité

**-3250** Mésopotamie, naissance de l'écriture.



#### 1.7.2.1. Prémices de l'Algèbre

Papyrus Rhind. Algèbre babylonienne, système sexagésimal. Tables d'inverse. Tables de carrés et approximation par interpolation linéaire.



#### 1.7.2.2. Quipu

-2500 : Recenser la population et gérer l'économie avec des noeuds. Un tiers d'informations qualitatives. Topologie.



#### 1.7.2.3. Boulier

**-2000**, Base décimale (10), ou base alternée (5, 2)



#### 1.7.2.4. Code de Hammurabi

**-1750**, texte de loi Babylonien Mésopotamie Antique. Casuistique.



#### 1.7.2.5. Grèce antique

Périclès, Acropole, Parthénon, sculpture Phidias. Athènes, guerre du Péloponnèse.



##### 1.7.2.5.1. Thalès

**-620**, géométrie, astronomie, calcul révolution (année), physique electricité et aimantation.



##### 1.7.2.5.2. Genèse de l'encryption

Sscytale spartiate **-600**. Code césar.



##### 1.7.2.5.3. Pythagore

**-580**, école Pythagoricienne, l'arithmétique, la musique, la géométrie, et l'astronomie. Terre ronde, lois harmoniques, végétarisme.

Le théorème de Pythagore. Monde mathématiques, toute chose est nombre.



##### 1.7.2.5.4. Dialectique

Etymologie et définition, Zénon d'Élée, **-490**. Thèse, une antithèse, et une synthèse.



##### 1.7.2.5.5. Rhétorique

 définition



##### 1.7.2.5.6. Sophistes et Sophismes 

**-490** Protagoras, sophiste. Pathos, ethos, logos. Agnostisme



##### 1.7.2.5.7. Socrate

Athénien **-470**, maïeutique. *elenchos*, bien et mal, injustice, condamné à la ciguë pour impiété.



##### 1.7.2.5.8. Atomisme

Concept philosophique d'élément insécable composant la matière. Leucippe **-440**, Démocrite, Épicure, Lavoisier.



##### 1.7.2.5.9. Cynisme

**-440** Antisthène, école cynique -390. Désinvolture et l'humilité, étymologie : chien.

Diogène de Sinope, désintérêt pour sépulture, funérailles. cosmopolite. Matérialistes anticonformistes. Contestation et ironie.



##### 1.7.2.5.10. Platon

Monde intelligible et sensible, idéaliste. Ontologie : modèle et archétypes. Epistémologie, science de la connaissance. Hiérarchie des pensées. Allegorie de la ligne et théorie de la caverne.

Démocratie, Académie.



##### 1.7.2.5.11. Mathématiques

Etymologie et définitions. Mathématiques appliquées, et mathématiques pures. Factorisation.



##### 1.7.2.5.12. Sténographie

Etymologie, Réécriture syntaxique abrégée et langage SMS. Diogène Laërce, **405 avant J.-C**. Xénophon.[^b1]



##### 1.7.2.5.13. Géométrie Euclidienne

Euclide, *Éléments[^b2]*. Géométrie, arithmétique, PGCD, division.



##### 1.7.2.5.14. Aristote

**-384** Lycée. Syllogismes. Biologie. Âme, terre ronde et confiance sensation. Vertu ethique, doxographie, métacognition.



##### 1.7.2.5.15. Stoïcisme

Zénon de Kition, **-301**, *mal*/*bien*/*indifférence*. Désirs, craintes et représentations. Apathie et Ataraxie. Tempérance et la prudence. Rationnel : raison et non envie. *Panthéisme*.



#### 1.7.2.6. Égypte antique

**-336**, Alexandre le Grand, conquérant. Alexandrie d’Égypte **-331 **. Transmission des informations de la culture Grecque en Égypte.



##### 1.7.2.6.1. Bibliothèque d'Alexandrie

Mouseîon, 400 000 ouvrages, rouleaux de papyrus. Dépôt légal.



##### 1.7.2.6.2. Origines de la logique mécanique

Archimède de Syracuse **-287**, élève d'Euclide. Théorème de la poussée, levier, vis d'Archimède, palan. Eureka

Ctésibios **-284** Alexandrie. École des mécanicien. Machines hydrauliques, monte-charge, miroir ajustable, clepsydre. Premier orgue de l'histoire, pistons, soupapes et claviers. Canon à eau.

**-280** Philon de Byzance. Traités, sur les leviers, pneumatiques, automates, clepsydres, constructions, roues et machines de guerres. Automates sonores et systèmes d'approvisionnement automatiques de liquide, servante.



##### 1.7.2.6.3. Calculateurs analogiques

Anticythère **-150** Routes de la soie



##### 1.7.2.6.4. Vitruve

Compilateur du **1er siècle avant J.-C.** Architecture, Alexandrie, Dinocrate [^b3] . Liens avec Archimède et mécanique et fluides. Aqueducs.

Les six principes théoriques de l'architecture.



##### 1.7.2.6.5. Compilateurs d'Alexandrie

Héron, **premier siècle après J.-C**. Éolipyle. Machines hydrauliques et pneumatiques. Automates de théatre.

Ménélaos **70**, géodésique.

Claude Ptolémée, **100**. *Almageste* et "les tables faciles".





[Retour](#Sommaire)

### 1.7.3. Moyen-Âge

Les civilisations antiques ont alors introduit le calcul et la gestion de l'information à travers l'écrit de multiples textes, certains se perdant au fil du temps, d'autres étant conservés grâce à des personnalités qui les ont repris et fait vivre en les appliquant voire les améliorant. Les différents penseurs de l'Antiquité ont donc défini, catégorisé et classifié les information de la connaissance humaine en modules. Ce concept omniprésent a permis une standardisation des idées et une base permettant d'avoir un langage commun. À l'aube du Moyen âge, les savant ont alors découvert et transmis les règles fondamentales de la physiques, de l'eau et la vapeur, permettant l'amélioration de l'approvisionnement en eau, de l'agriculture, ou encore la création d'automates et des machines de guerre.

En -47, Jules César ordonne d'incendier la flotte d'Alexandrie. Détruisant une grande quantité de richesses et hypothétiquement de savoir contenu dans la bibliothèque ou dans ses alentours. Sous la Rome Antique, les maîtres artisans n'enseignaient qu'à leurs apprentis pour minimiser la surface d'impact sur leur systèmes de connaissances, et ainsi avoir de la renommée. C'est également pour cela que les textes de Vitruve ont été si précieux pour les historiens de cette période. 

Bien que le début du Moyen-Âge soit marquée par un déclin avec la chute de l'Empire romain en 450, il se passera bien des choses dans le domaine des mathématiques, de la cryptographie et de l'imprimerie. Ce sera par ailleurs l'âge d'or de l'islam du 8ème au 13ème siècle, j'introduirait plusieurs savant arabes de cette époque qui ont eu accès aux textes antiques grâce à la conquête d'Alexandrie, ou d'Antioche vers 650. Ils transmettrons et développeront les sciences à la manière de leurs prédécesseurs, jusqu’à ce que les espagnols reprennent peu à peu leurs territoires lors de la reconquista.

D'un point de vue social et économique, l'humanité a connu une forte croissance démographique à cette période, avec un doublement de la population passant de 35 à 80 millions d'individus entre l'an 1000 et  1350, malgré la grande famine de 1316 et la peste noire de 1347. Ce développement a été en grande partie du à un climat plus favorable et à l'agrandissement des surfaces cultivés, qui a été accompagné par le développement des techniques agricoles comme la rotation des cultures ou l'apparition de la charrue.

L'élevage des moutons à laine longue se développera, avec l'introduction en Europe du rouet inventé en Chine lors du premier siècle. Des boutons existants depuis l'apparition des premières villes permettront la réalisation de textiles de meilleure qualité. Les moulins à vents et à eau vont également proliférer, permettant une automatisation et la réduction de l'utilisation de force manuelle au profit des forces hydrauliques, thermiques, éoliennes et animales.

Les techniques navales vont également se développer avec les coques bordées en clin à la manière des tuiles d'un toit, puis à franc bord ou les planches sont jointes, formant une courbe plus droite ; mais aussi avec la popularisation des voiles latines triangulaires et des gouvernails d'étambot articulés. La réalisation de cathédrales et de châteaux va accélérer le développement des techniques de construction, des armures, et des armes, notamment de siège. Les hauts fourneaux permettant une meilleure production et qualité de fer apparaîtra en Suède, un peu avant la poudre à canon et les armes à feu qui arriveront vers la fin du 13 ème siècle.

Le passage à l'époque moderne se fera en 1492, année de la découverte occidentale des Amériques par Christophe Colomb.



#### 1.7.3.1. Aryabhata

Algorithmes racine carrée et cubique. Demi-corde, Angles et table de calcul trigonométriques.



#### 1.7.3.2. Algèbre et Algorithme

Définition. Recettes babylonniennes. **800**, Al-Khwarizmi. Equation



#### 1.7.3.3. Système de numération indo-arabe

Aryabhata et Al-Khwarizmi chiffres base 10



#### 1.7.3.4. Compilateurs Arabes

Banou Moussa, *Maison de la sagesse* **832** Bagdad. 

Al-Kindi, cryptanalyse.

Al-Battan, Tables de calculs Astronomiques et trigonométrie.

Al Zarqali, Tables Tolédanes.

Averroès médecin philosophe, pensée logique et Galien. Pharmacologie, compilateur commentateur. 

Avicenne, philosophe médecin, encyclopédies de philosophie, sciences, et médecine.

Al-Jazari vers **1206**, "Livre de la connaissance des procédés mécaniques".



#### 1.7.3.5. Occidentalisation des savoirs de l'Âge d'or arabe

Sylvestre II **950** aka Gerbert d'Aurillac, astrolabes.

Hermann Contract, **1013**.

**1070**, Abraham bar Hiyya Hanassi pionnier des sciences mathématiques en Europe.

**1170**, Leonardo Fibonacci, suite et  nombre d'or.

Ramon Llull, **1234**, « alphabet de la pensée logique », théorie des graphes, logiques combinatoires, paradoxe de Condorcet.



#### 1.7.3.6. Typographie

Etymologie, **1440** Gutenberg.

Caractères mobiles 1040, Bi Sheng. Xylographie.



#### 1.7.3.7. Inventions italiennes

Leon Battista Alberti, cryptographie

Luca Pacioli, fondateur de la comptabilité par partie double



[Retour](#Sommaire)

### 1.7.4. Époque moderne

Le début en étant marqué par la découverte occidentale d'un nouveau continent en **1492**, cette période sera notamment celle du développement des empires coloniaux et des grandes découvertes maritimes, permis par les développement technologiques du moyen âge, notamment concernant la navigation, la cartographie, l'imprimerie et les techniques agricoles. L'import de la pomme de terre américaine permettra d’atténuer le problème des famines. 

Dans cette période s'amorce un changement social, avec le très lent déclin des monarchies, du clergé et de la noblesse, au profit de la bourgeoisie qui développa le commerce, notamment dans les villes et leurs abords, causant une urbanisation progressive. L'Église perd de son pouvoir et ses biens entrent progressivement dans le domaine public grâce à la sécularisation. Les États-Unis finiront par déclarer leur indépendance en 1776. L'époque contemporaine lui succédera à partir de la révolution française de 1792.



#### 1.7.4.1. Héliocentrisme

Aristarque de Samos **-280**. Terre tourne autour du soleil.

Nicolas Copernic **1513** modèle héliocentrique,  mouvement philosophique des Lumières.

Johannes Kepler trajectoires elliptiques. Loi orbites, aires, et trajectoires.

Galilée 

Isaac Newton, lois de la gravitations universelle. Mécanique classique, décomposition de la lumière [^b5][^b6]. 

1757 calculateurs français, Alexis Clairaut, Jérôme Lalande, et Nicole Lepaute. Edmond Halley, et sa comète. Révolution de 76 ans



#### 1.7.4.2. Philosophes modernes

François Rabelais moine apostat, médecin, et écrivain. Gigantisme, Pantagruel, Gargantua, en **1532** et **1534**

Montaigne.

Francis Bacon, droit et politique, empiriste. *Novum organum*[^b7] **1620**

Préjugés, illusions, sophismes, biais, 4 idoles.

Thomas Hobbes, *Léviathan* en **1651**,  référence biblique. Matérialiste et rationaliste. Critique des États, de la souveraineté et des religions (scolastique). Humain naturellement mauvais et violent, rapport à l'autorité. "société athée ou a-religieuse constitue la solution au problème social ou politique".

René Descartes 1596, fondateur géométrie analytique et mécanisme, causalité et fonctionnalisme. Dualité entre l'âme est le corps. Scepticisme, et doute cartésien, épochè. Méfiance envers les sensations trompeuses, illusions d'optiques. "cogito ergo sum".

Baruch Spinoza 1632, herem, taille de lentilles optiques. Panthéisme stoïcien. Niveau de connaissances : ouï-dire, connaissance empirique, déduction, et connaissance première.

**1712** Jean-Jacques Rousseau, philosophe autodidacte, *Discours sur l'origine et les fondements de l'inégalité parmi les hommes*[^b8] **1755**, l'humain est naturellement bon. Volonté générale, *Du contrat social* **1762**. *Emile* ou *De l'éducation*, pédagogie moderne.

1724, Kant, fondateur du criticisme et de l'idéalisme transcendantal. Descartes dans le "Traité de l'homme" de 1664.



#### 1.7.4.3. Journalisme

Antiquité, pratique orale, par crieurs, messagers ou troubadours, sur la place publique. Empire Romain *Acta Diurna*. **1622**  *Weekly News* de Nathaniel Butter. Théophraste Renaudot, *Gazette* 1631.

Liberté de la presse contre la censure royale. Droits de l'Homme et du citoyen de 1789. *L'Agence des feuilles politiques, correspondance générale* 1835, Charles-Louis Havas.

Vérification des faits, protection des sources. Benjamin Franklin ?



#### 1.7.4.4. Binaire

-750 les hexagrammes chinois. **-200**, Pingala *Chandahsastra*. Juan Lobkowitz, 1606, fondateur de la mathématique binaire.

**1690** Leibniz Wilhelm Gottfried. Cylindre cannelé et *characteristica universalis*. 



#### 1.7.4.5. Encryptions moderne

Giambattista della Porta cryptographe, **1563** *De furtivis literarum notis, vulgo de ziferis*."[^b9] système littéral à double clef.

**1523** Blaise de Vigenère et son code (Giovan Battista Bellaso). *Traité des chiffres* **1586**[^b10], Table de chiffrement et déchiffrement cassé par Friedrich Kasiski en 1863.



#### 1.7.4.6. Premières machines à calculer

"computer" Richard Brathwaite *The Yong Mans Gleanings* **1613** [^b11],

**1617** John Napier, Bâtons de Napier. Logarithme népérien.

Wilhelm Schickard, une horloge à calculer.

**1621** William Oughtred, notation de π et "x" pour la multiplication. Règle coulissante.

En **1650**, le clermontois polymathe Blaise Pascal, invente la Pascaline. Traité de géométrie projective. Première machine à calculer.

Cartes perforées, orgue de Barbarie. **1725**, Basile Bouchon. 1728, Jean-Baptiste Falcon. Jacques de Vaucanson, célèbre Grenoblois inventeur d'automates musicaux et à objectif de divertir, réutilise ce concept en remplaçant ruban et cartes perforées par un cylindre métallique à pointes. Joseph Marie Jacquard, métier à tisser éponyme en **1801**.



#### 1.7.4.7. Pédagogie moderne

**1746**, Johann Heinrich Pestalozzi, *Leonard et Gertrude*[^b12][^b13]en **1781**. *Comment Gertrude instruit ses enfants*[^b14][^b15] en **1801**. Éducation bienveillante et mutuelle. Du concret à l'abstrait.

Grégoire Girard, écoles mutuelles 1816.

Andrew Bell l'enseignement mutuel, *Expériences sur l'éducation faite à l'école des garçons de Madras* [^b16] en **1789**.

Joseph Lancaster, *Improvement in Education*[^b17] en 1803.

Charles Démia, *Règlements pour les écoles de la ville et diocèse de Lyon*[^b18] en 1674.



#### 1.7.4.8. Théorie générale des systèmes

De 1751 à 1772, Diderot et Alembert, l'*Encyclopédie* ou le *Dictionnaire raisonné des sciences des arts et des métiers*.  Sébastien Le Prestre, aka marquis de Vauban. Système art militaire, arrangement toutes les parties [^b19].

Étienne Bonnot de Condillac, système en science politique *Traité des Systèmes* [^b20]en **1749**. Logique [^b21]

Vilfredo Pareto qui l'appliqua à l'économie politique au début du 20ème siècle.



### 1.7.5. Époque contemporaine

C'est la période actuelle, le début en est défini par la révolution industrielle qui a commencée en **1760** au Royaume-Unis, le besoin de calcul, de gestion et d'automatisation est alors grandissant. La France aboli la monarchie en 1792, les États deviennent pour la plupart des républiques, l'ancien régime et les empires coloniaux prennent fin, l'esclavage est aboli, et les deux guerres mondiales prendront lieu par la suite. Dans le monde anglo-saxon, cette période ne commence qu'en 1945 à la fin de la seconde guerre mondiale.



#### 1.7.5.1. Genèse du libéralisme

François Véron Duverger de Forbonnais, théorie des cycles

Vincent de Gournay,  "Laisser-faire, laisser passer", bureaucratie.

Physiocrates, François Quesnay et le marquis Victor de Mirabeau, Versailles, juillet 1757.

1759,  *Tableau économique* de Quesnay.

Despotisme légal, lois naturelle. Impôt unique et État minimal. Vérification constitutionnelle les lois.

Duc de Choiseul, Anne Robert Jacques Turgot, John Locke, David Hume, Étienne Bonnot de Condillac et Adam Smith.



#### 1.7.5.2. Philosophes contemporains

Georg Wilhelm Friedrich Hegel, 1770, idéaliste. "*Phénoménologie de L'Esprit*"[^b22][^b23], dialectique du maître et de l'esclave. Travail facteur d'émancipation et de libération.

Jean-Baptiste de Lamarck, biologie. Théorie transformiste et fixisme. *Philosophie zoologique*[^b24], théorie de l'évolution, l'homme descends du singe.

Charles Darwin, l'*Origine des espèces*[^b25] en 1859. Sélection naturelle, preuve scientifique.

Herbert Spencer sciences humaines, darwinisme social.

Ernst Mach **1838** dynamique des fluides. Notation vitesse Mach. Philosophie de la science.

Nietzsche 1844

Bergson 1859

Albert Einstein 1879

Le mathématicien Carl Friedrich Gauss, Né en **1777**



#### 1.7.5.3. Pédagogie contemporaine

Friedrich Fröbel **1782**, jardins d'enfants. "Bref exposé des principes d'éducation et de formation de Pestalozzi, d'après Pestalozzi lui même".

1792 Nicolas de Condorcet, réforme du système éducatif à l'Assemblée nationale législative.

1793, Louis-Joseph Charlier enseignement primaire obligatoire gratuit et laïc en France. 

État de New York, 1832 école élémentaire gratuite et obligatoire.

Entre 1879 et 1882, Jules Ferry, lois scolaires, instruction obligatoire et laïque.

John Dewey, **1899** *The School and Society*[^b26].



Francisco Ferrer, l'école moderne 1901, semaine tragique du 26 juillet au 2 août 1909.

Maria Montessori, Italie **1870**.

Édouard Séguin, Jean Itard, Victor, "Enfant sauvage de l'Aveyron".

Adolphe Ferrière, **1879**, complètement sourd, **1909** "*Projet d'école nouvelle*". Ligue internationale pour l'éducation nouvelle en 1921

Célestin Freinet, **1896**, Technique Freinet, Journal scolaire.



#### 1.7.5.4. Premières machines de saisie

Dactylographie et etymologie.

**1714**, Henry Mill, première machine à écrire

1829 William Austin Burt, The Typographer 

1837, Guiseppe Rivezza, clavesin scribe. 

Jean Claude Pingeron et François Pierre Foucaut, ami de Louis Braille. 1780 et 1839, machines raphigraphique.

Les aventures de Tom Sawyer de Mark Twain, première œuvre littéraire écrite intégralement sur machine à écrire en 1872.

**1874**, "type-writter" Remington, claviers QWERTYUIOP, FGHJKL. 

Georges Buisson, sténographe à l'Assemblée Nationale, concours de vitesse dactylographique.



#### 1.7.5.5. Améliorations des calculateurs

**1766**, Almanach nautique

Arithmomètre, Thomas de Colmar **1820**.

Arithmaurel, **1842**, Timoleon Maurel

Planétaires, machine à prévoir la marée de Lord Kelvin, en **1872**.

Dorr E. Felt, comptomètre en **1887**.

**1889**, calculatrices à crosse de Louis Troncet (Arithmographe).



#### 1.7.5.6. Inventions électroniques

Antiquité, *êlektron* ambre jaune en grec ancien. Magnétisme et magnésie.

Pieter van Musschenbroek, Bouteille de Leyde, ancestre condendsateur. Electroscope, électromètre.

Charles Coulomb, 1785, formule de l'intensité de la force électrique entre deux particules chargés

Pile électronique de Volta en 1800, renommée internationale.

1820 Hans Chistian Orsted

1831, Michael Faraday, André-Marie Ampère relier le courant électrique aux champs magnétiques

1873 Maxwell, théorie de l'électromagnétisme.

Roue de Barlow, premier moteur électrique, 1822. Premier électroaimant en 1825, induction en 1831,  premier alternateur => machine de Pixii en 1832.

Edison **1879** brevet lampe à filament, bureaux de recherches industriels, films vidéos.

Nikola Tesla, moteur asynchrone, alimentation polyphasée[^p1], réseau de distribution d’électricité alternative. Très haute fréquence et technologie sans fil, l'imagerie radio (Wilhelm Röntgen). Automates radio-contrôlés. Lucien Gaulard, transformateur.



Albert Einstein, relativité générale.



##### 1.7.5.6.1. Communications à distances

Feux placés en hauteur sur des montagnes ou des tours, signaux de fumée.

1794, Claude Chappe tours et sémaphores, victime de piratage. 

1837 télégraphe électrique commercial de Cooke et Wheatstone

Samuel Morse en 1840.

Robert Hooke, téléphone à ficelle en 1665.

Antonio Meucci, 1850 *Telettrofono*

Alexander Graham Bell, brevet téléphone[^p2]. 

Elisha Gray, télégraphe musical, ancêtre du synthétiseur.



##### 1.7.5.6.2. Semis-conducteurs

Frederick Guthrie 1873.

1874 Karl Ferdinand Braun,  diode et principe du semi-conducteur.

**1904** John Ambrose Fleming, *kénotron*, premier tube à vide, ancêtre des diodes et semi-conducteurs.

Lee De Forest, Audion **1906**.

William Eccles, triode 1919.



##### 1.7.5.6.3. Prémices de l'affichage numérique

1857, *Tube de Geissler*.

Entre 1869 et 1875, William Crooke, rayons cathodique et tube éponyme.

Ferdinand Braun, 1897, tube cathodique éponymes.

Boris Rosing, **1907**, fondations d'un système de télévision mécanique. Hystérésis magnétique.

Vladimir Zvorykine, iconoscope, pionnier de la télévision

Philo Farnsworth, chaîne de télévision avec émission-réception.

Louis Lumière *Étiquettes bleues* 1881.

Georges Eastman Kodak, premier appareil photo, 1884.

Georges Demenÿ, 1895,  biographe. 

Kinétographe d'Edison en 1890.

1895, le Cinématographe des frères lumières avec l'aide de Jules Carpentier.

**1893**, André Blondel, oscillographe bifilaire.



#### 1.7.5.7. Logique

Bolzano "*Théorie de la science*", notion d'objet

Charles Sanders Peirce, philosophie pragmatique et scientifique, notation flèche de Peirce, porte NOR.[^b27]



Principe de Hume ---> Gottlob Frege, notation logique *Idéographie*[^b28] (*Begriffsschrift*). Mouvement de la philosophie analytique dans le but de clarifier les pensée.

Russel *Principia Mathematica* [^b29][^b30] [^b31]

Alfred North Whitehead, philosophie des processsus. Ernst Schröder

**1847** George Boole, tables de vérité, algèbre booleen et portes logiques.



#### 1.7.5.8. Genèse de la programmation

https://www.youtube.com/watch?v=RQYuyHNLPTQ

1800, Joseph Marie Jacquard invente le métier à tisser Jacquard, complétement automatisé. 

Charles Babbage, automatisation de l'édition de tables de calcul. 1834, machine à différences. Machine Analytique.

Machines à coudre. aiguille a coudre de 50000 ans.

Charles Fredrick Wiesenthal premier brevet de machine à coudre en 1755. 1800, Josef Madersperger. 1830 Barthélemy Thimonnier première machine à coudre fiable. 1846 Elias Howe première machine à coudre capable de faire des points noués. Popularisation par Isaac Merritt Singer.

Définition d'un programme et explication premier programme informatique pour Machine Analytique imaginée par Ada Lovelace en **1842**, 

Hermann Hollerith invente la mécanographie en 1890, Tabulating Machine Company, Computing-Tabulating-Recording Company, IBM. 





[Retour](#Sommaire)

### 1.7.6. Première guerre mondiale et entre deux guerres

En 9 décembre **1905**, l'abrogation du régime concordataire de 1802 sépare l'État et l'Église, mettant fin à l'affrontement violent qui a opposé deux conceptions de la place des Églises dans la société française pendant environ vingt-cinq ans.

C'est la première guerre à impliquer simultanément tout les pays, les machines de bureau deviennent électromécaniques, l'humain peut désormais rapidement transmettre des messages sur de longues distances à ses congénères à l'aide des télégraphes. L'informatique naissante cherchera à vendre des machine mécanographiques dans le monde entier, elles serviront les gouvernement les plus puissant et également les pires de l'époque, Thomas Watson, après avoir travaillé à la récente et bien portante Nationnal Cash Register company (NCR), est embauché en 1914 pour diriger la regroupement d'entreprise de la CTR, c'est lui qui fonda IBM après la guerre en 1924.



#### 1.7.6.1. Théorie des jeux

Définition de la théorie des jeux. Ernst Zermelo, assistant de Max Planck, "*Sur une application de la théorie des ensembles à la théorie du jeu d'échecs*" publié en 1913.

Emile Borel, *Comptes rendus hebdomadaires des séances de l'Académie des sciences* 1921[^b32]. 

1940 "*Théorie mathématique du bridge à la portée de tous*" avec André Chéron.

Jeux économiques, Antoine Augustin Cournot 1838 "*Recherches sur les principes mathématiques de la théorie des richesses*"[^b33], équilibre entre l'offre et la demande. 1944 Oskar Morgenstern et John von Neumann "*Théorie des jeux et du comportement économique*".

John Forbes Nash, équilibre de Nash.



#### 1.7.6.2. Améliorations du stockage

1900, Valdemar Poulsen enregistrement magnétique sur fil, télégraphone.

1928, Fritz Pfleumer, bande magnétique & magnétophone de Karl Stille.

bande magnétique en acier

1940, bande magnétique en [matière plastique](https://fr.wikipedia.org/wiki/Matière_plastique).

**1932**, Gustav Tauschek, mémoire tambour (Manchester Mark I, l'ENIAC, l'IBM 650, l'IBM 701, et l'UNIVAC 1103)



#### 1.7.6.3. Tabulatrices

Explication outils d'un atelier mécanographie.

1920, Hollerith, module d'impression et tableaux de connexion amovibles => tabulatrice. 

1931, IBM 601 Multiplying Punch.

1935 TELEX



#### 1.7.6.4. Détections par ondes

Définition du radar, James Clerk Maxwell, Heinrich Rudolf Hertz, Albert Hull, magnétron.

**1934**, Compagnie générale de télégraphie Sans Fil française (CSF) [^p3].

1900 sonar 

Rudolf Kühnhold 1931 système de télémètre radio.

1935 Robert Watson-Watt, inventeur officiel du radar, dépose un brevet [^p4] Chain Home. 

1940 bataille d'Angleterre





#### 1.7.6.5. Alan Turing 

**1936** machine de Turing. Informatique théorique, description et explication.

Jeux-vidéos Turing-complete : Minecraft[^v1] Terraria[^v2]  ou Factorio[^v3] , Turing-Complete.[^g1]

IA et Test de Turing *Computing Machinery and Intelligence* -> *jeu d'imitation*

Enigma, Marian Rejewski, Bombe cryptologique électromécanique => durée de la guerre moins deux ans.

Etats-Unis en 1942-1943, découverte Projet Manhattan, et travaux de Von Newman => Automatic Computing Engine, un design d'ordinateur à programme enregistré.



#### 1.7.6.6. Zuse Konrad

1936 Zuse Konrad calculateurs Zuse.

Z1, 1938. Z2 1940. Z3, 1941. Z4 1953. De 1942 à 1946, premier langage de haut niveau : Plankalkül



#### 1.7.6.7. Calculs balistique

Moore School, 1923. Ballistic Research Laboratory.

**1937**, John Vincent Atanasoff et Clifford Berry => machine à calculer électronique 1939 Atanasoff Berry Computer (ABC).

1940 présentation à John Mauchly. 1942 machine testé avec succès sur équations linéaires. 

=> ENIAC



#### 1.7.6.8. Hewlett Packard

Créée en 01/01/**1939**, HP réalisait initialement des instruments de mesure.





[Retour](#Sommaire)

### 1.7.7. Seconde guerre mondiale

#### 1.7.7.1. Colossus Mark 1

Dechiffrer machines de Lorenz

Colossus 2 débarquement de Normandie.



#### 1.7.7.2. Harvard Mark 1

L'IBM Automatic Sequence Controlled Calculator (ASCC) [^v4] **1944** => premier calculateur entièrement automatique.

Relay Switches fragiles. Réalisation de tables. Expérimentations par Grace Hopper.





#### 1.7.7.3. Architecture de von Neumann

**1945** EDVAC, ENIAC, SSEC, Z4.

Von Neumann & EDVAC

Explications sur cette architecture.

ENIAC programmé par 6 femmes

Eckert-Mauchly Computer Corporation en 1946

Elisabeth Findler Jake, nom de domaines, whois nom de domaine (page jaunes) Alors que la silicon vallait est encore loin.



#### 1.7.7.4. As we may think

Vannevar Bush, électrotechnique au MIT.

Analyseur différentiel, Comparator et Rapid Selector en 1940.

NACA (NASA), projet Manhattan de 1945.

Juillet 1945**, qu'il publia *As we may think* dans le mensuel The Atlantic. [^b34]



[Retour](#Sommaire)

### 1.7.8. Guerre froide et course à l'espace

La seconde guerre mondiale prends fin et c'est officiellement l'époque contemporaine pour les anglo-saxons. C'est l'avènement du nucléaire, de l'ère de l'informatique, mais aussi de la décolonisation et de la guerre froide. Les besoins de calculs sont plus importants que jamais, aéronefs, nucléaire militaire, civil, et gestion de l'énergie sont au cœur des réflexions et stratégies des pays du monde.

L'arrivé du calcul et de la simulation informatique offrent un meilleur contrôle, ainsi qu'une prise de décision plus efficace, permettant de gérer de grandes structures, qu'elles soient civiles, militaires, ferroviaires, aériennes, ou autre.  

De grands projets à forte complexité en découlent, elle amènent à un besoin de communication multimédia mondiale, pour que les gens puissent s'organiser et faire coopérer des spécialistes de tout les domaines concernés. Internet viendra résoudre ce problème à partir de 1970, amenant à la période de mondialisation intense que l'on vit encore actuellement en 2023.



#### 1.7.8.1. Temps réel

*Project Whirlwind* Jay W. Forrester, & Perry O. Crawford Jr.

ENIAC en 1945.

George Valley, **1950** rapport système de défense anti-aérienne américain. Semi-Automatic Group Environment (SAGE).

SABRE



#### 1.7.8.2. Trackball

1946



#### 1.7.8.3. Norbert Wiener

**1947** **cybernétique**.

Rétroaction : régulateur à boules de James Watt en 1788

Le mouvement cybernétique ralliera de nombreux mathématicien dont John Von Neumann.



#### 1.7.8.4. SSEM

Le tube de Williams-Kilburn, 1946 Frederic Calland Williams et Tom Kilburn.

Tubes cathodiques de Boris Rosing. Small-Scale Experimental Machine (SSEM). Manchester Baby **1948**



#### 1.7.8.5. Manchester Mark I

1949



#### 1.7.8.6. Théorie de l'information

1948 Claude Shannon

**Warren Weaver**, né le 17 juillet 1894 est principalement connu comme un des pionniers de la traduction automatique, il a également assister Shannon dans le développement de la théorie de l'information



#### 1.7.8.7. Origines de l'Assembleur

Maurice Wilkes et David Wheeler, **1949** Electronic Delay Storage Automatic Calculator (EDSAC), et le Binary Automatic Computer (BINAC)

notation utilisée par Von Neuman et Herman Goldstine.

Explciations assembleur





#### 1.7.8.8. Ferranti Mark I

Le Ferranti Mark 1, aka Manchester Electronic Computer, premier ordinateur électronique généraliste commercialisé **1951**.

Alan Turing morphogenèse.

=> Ferranti Mercury



#### 1.7.8.9. Compilateurs et premiers languages de haut niveau

L'Universal Automatic Computer I (UNIVAC) **1951** Remington Rand

MAGNETIC TAPE STORAGE start and stop tape rapidement avec des servomoteurs, plastic -> déforme -----> métal résistant, travail pour écrire et lire dessus

Grace Hopper créé en **1951** le Arithmetic Language ou A-0 system. Premier compilateur.

B-0 Flow-matic, entre 1955 et 1959.



#### 1.7.8.10. Leo I

EDSAC créé par Maurice Wilkes, le Lyons Electronic Office créé en **1951**. Premier ordinateur utilisé pour des opérations commerciales.





#### 1.7.8.11. IBM

IBM 602 & 603 **1946**

IBM CPC : Rival de l'EDSAC et du BINAC, il fait son apparition la même année en **1949**, fait à partir du IBM 604 et du IBM 402. Premier compilateur (A-0 System Grace Hopper 1951)

IBM 604 (1948)

IBM 407 : 1949 imprimante 150 lignes par minutes

IBM 701 en **1952**, premier ordinateur scientifique produit en masse, Defense Calculator. Memoire tambour

**1953**, John Backus, créé le Speedcoding, interpréteur, premier langage de programmation de haut niveau créé pour un ordinateur IBM.

IBM 702 1953

**1953**, mémoire à tores magnétique.

**1954** l'IBM 650

Créé aux États-Unis en **1955**, le TRAnsistor DIgital Computer sera quand à lui premier ordinateur à transistors.

IBM 1401 : Entre **1959** et 1965, ordinateur à transistor le plus vendu. Report Program Generator (RPG)

IBM System 360 : 1962, 5 billion de dollars



#### 1.7.8.12. Premiers langages de haut niveau opérationnels

**1957**, Backus invente le Formula Translator ou FORTRAN, langage de programmation haut niveau.

Grace Hopper, COBOL, un langage haut niveau, **1959**, 

Langage de première génération : Binaire, difficile à lire et interpréter par un humain

Languages de deuxième génération : Instructions simples et lisible par l'humain, spécifiques à une certaine famille de processeur, dont elle permet de manipuler les commandes principales à l'aide de mot clés mnémoniques.

Langages de troisième génération - haut niveau - Structures de contrôle et de données

Ces abstractions sont de plus haut niveau et indépendant du matériel, les langages deviennent plus conviviaux et pratiques d'utilisation

(FORTRAN & COBOL) aggregate data types



##### 1.7.8.12.1. Lisp

**1958** John Mc Carthy



Languages de quatrième génération

Abstraction encore plus haute permettant de facilement interconnecter et manipuler des outils logiciels tiers comme une base de donnée, une interface graphique, ou un serveur web. La plupart des langages de la troisième génération se sont doté de ses fonctionnalités et ont évolué vers cette génération. Ce genre de langage est désormais assez haut niveau pour permettre un développement rapide de programme dans un domaine spécifique. C'est la raison pour laquelle Python étaient initialement spécialisés dans le traitement de la donnée et JavaScript les interactions utilisateurs.



Language de cinquiéme génération

L'ordinateur trouve lui même les solutions pour nous, très lié à l'intelligence artificiel, l'example le plus concret est Prolog.



#### 1.7.8.13. Théorie algorithmique de l'information

**1960**



#### 1.7.8.14. Computionnalisme

**1961**



#### 1.7.8.15. Souris

Inventée en **1963** par Douglas Engelbart, elle ne sera présentée au public qu'en 1968. Cet informaticien réalisera également le système d'exploitation NLS, ses travaux serons financés par Joseph Carl Robnett Licklider qui financera également ARPANET



#### 1.7.8.16. Luciano Floridi 

Luciano Floridi est né à Rome le 16 novembre **1964**, ce philosophe est l'un des plus important théoriciens de la Philosophie de l'information et de l'éthique de l'informatique. Il a fondé et dirige plusieurs groupes de recherche dans ces domaines.



#### 1.7.8.17. Premières applications de l'IA

Percepton En **1957**, le psychologue Frank Rosenblatt 

Dendral **1965** 

1966 Eliza 



#### 1.7.8.18. Microprocesseur

1903 Albert Hanson dépose un premier brevet[^p5] 

1925, Charles Ducas [^p6]

1927, César Parolini  [^p7]

1943 Paul Eisler [^p8] 

Transistor en 1947.



1958, Jack Kilby premier circuit imprimé

1958 Robert Norton Noyce circuits intégrés en silicium

avec Gordon Earle Moore, Intel.

En **1969**, le microprocesseur est inventé par Federico Faggin, et Marcian Hoff, un ingénieur et physicien d'Intel, 



#### 1.7.8.19. Course à l'espace

Spoutnik 1 **1957**

En **1967**, Apollo 1 est un échec et la lune parait de nouveau inaccessible aux américains, sous Kennedy.

Le programme Apollo Guidance Computer (AGC) réalisé en **1969** par Margaret Hamilton a été numérisé et rendu disponible sur [Github](https://github.com/chrislgarry/Apollo-11). Écrit en Assembly

Apollo 11 sera finalement une réussite, les États-Unis rattrapent alors leur retard dans la course à l'espace jusqu'alors menée par l'URSS.

Katherine_Johnson



#### 1.7.8.20. John Horton Conway

https://www.youtube.com/watch?v=8DBhTXM_Br4

Théorie des noeux, qui trouve des usages dans la créations de matérieux composites et l'analyse de l'ADN1937 il invente le jeu de la vie en **1970**, les règles sont très simple mais comme l'as dit Leonard de Vinci, la simplicité est l'ultime sophistication.





[Retour](#Sommaire)

### 1.7.9. Popularisation et Mondialisation

Jusqu'alors, l'informatique était essentiellement réservé aux domaines privés comme le militaire, le spatial et l'administration des États. À partir des années 70, l'informatique va commencer à arriver dans le quotidien des particulier les plus aisés et finir par être dans une grande majorité des foyers. Internet commence à se développer petit à petit.



#### 1.7.9.1. Genèse d'internet

Arpanet et Cyclades **1969** et 1972 (Louis Pouzin)



#### 1.7.9.2. Interfaces graphiques

Ivan Edward Sutherland invente Sketchpad en 1963

Douglas Engelbart oN-Line System (NLS), le premier système d'exploitation multi-utilisateur

Xerox Parc

"What You See Is What You Get" ou WYSYWYG. 

Xerox Bravo sorti en 1974

Xerox Alto, 1973. 

Alan Kay Smalltalk, créé en 1972

Xerox DoRADO, 

1996, Squeak





#### 1.7.9.3. Ordinateurs personnels

- Programma 101 1965

- #### *Amstrad* **1968**

- HP

- *Altair 8800* 1975

- Commodore PET 1977

- Apple II 1977

Présenté en 1978 mais sorti en **1980**, le Minitel est un ordinateur connecté à un réseau et donc appelé Terminal. Il utilisait le réseau Transpac pour faire tourner le sien, "Télétel" auquel il se connectait à l'aide d'un modem. Il possédait une mémoire de 8,25 ko, et un processeur Intel 8052

- *Osborne 1* **1981**
- Xerox Star **1981** premier ordinateur commercial avec une interface utilisateur graphique [^1]
- *IBM PC 5150* **1981**
- *Macintoch 128K* Sorti en **1984**, avec des icônes en skeuomorphisme 

[^1]: http://toastytech.com/guis/star.html



#### 1.7.9.4. Jeux vidéos

- *Spacewar!* **1962**
- Atari pong 1972
- *Pac Man*  **1980**



#### 1.7.9.5. GPS

**1973**



#### 1.7.9.6. Homebrew computer club

1976 homebrew exhibits



#### 1.7.9.7. Cerveau Chinois

1961 et reprise en 1974 par Lawrence Davis et **1978** par Ned Block

Leibniz avait déjà dans son livre *Monadologie*[^b35], imaginé "un homme mécanique dont on pourrait visiter le corps comme on visite un moulin".

Bateau de Thésée



#### 1.7.9.8. La chambre chinoise

John Searle vers **1980** & explication

#### 1.7.9.9. Mémoire flash et stockage optique

Optical Storage Disc **1980**



#### 1.7.9.10. Cerveau dans une cuve

Hilary Putnam en 1981,



#### 1.7.9.11. Logiciel libre

Richard Stallman annonce le projet GNU le 27 Septembre **1983**, 

1985 il fonde le FSF, la Free Software Foundation.

En 1987 Andrew S. Tanenbaum Minix 

**Linux en 1991**



#### 1.7.9.12. Cadriciels et Open Source

Foundation ou bootstrap

Symfony.





#### 1.7.9.13. World Wide Web

https://fr.wikipedia.org/wiki/ENQUIRE (**1990** Tim Berners Lee) web semantique Rose Dieng Kuntz

Ward Cunningam créa le premier wiki en 1995 il est encore disponible tel quel[^w6], il fut un développeur Smalltalk 



#### 1.7.9.14. Ordinateur quantique

En **1998** IBM créé le premier ordinateur quantique sur les travaux de Rolf Landauer

### 1.7.10. Bilan passé

J'ai pu remarquer à travers l'Histoire que les inventions de savants et créateurs ne sortent que rarement de nulle part. Leurs origines proviennent souvent de (re)découvertes des principes existants, qu'ils compilent et les réutilisent à leur manières, améliorant les idées de leurs prédécesseur et réalisant de meilleurs outils à force d'itérations innovantes. Des inventions comme le Radar ou la pile de Volta trouvent leur inspiration dans des observations de la nature, notamment des animaux avec les chauves souris qui se guident à l'aide de l'écholocalisation, ou les anguilles électriques capable de produire des courants allant jusqu'à 860V et 2A. Les personnes pionnières dans leur domaine sont généralement suivies par foule de passionnés car les idées naissent d'une combinaison d'autres déjà existantes dans le contexte mondial à un moment donné. Il est en effet impossible de savoir qui à eu l'idée d'une chose pour la première fois, on ne retiendra naturellement que la première personne à avoir populariser le terme ou l'idée, parfois à travers la commercialisation d'un produit, d'autre fois grâce à une publication scientifique ou dépôt d'un brevet. Certaines informations plus ésotériques ne se transmettrons que par la parole, conservant ainsi un secret relatif.

Les découvertes ne sont pas toujours l'œuvre de savants ou de personnes renommés. En 2023, de simples utilisateurs d'application mobile découvriront ce que les mathématiciens recherchent depuis des siècles. Ça a été le cas du problème einstein essayant de trouver une forme dite d'*ein stein* (une tuile en allemand), que les chercheurs ne pensaient pas possible jusque là. En réalité elle est très simple et peut se construire en découpant trois hexagone liés en suivant les médiatrice de leurs côtés. Cette dernière ressemble à un t-shirt ou un chapeau et permet de réaliser un pavage apériodique à tuile unique c'est à dire de recouvrir une surface plane par un emboîtement de copies de cette forme, sans qu'elle ne se répète à l'identique comme les carreaux d'une grille. Pour ce faire il faut parfois avoir recours à une tuile inversé, problème qui a été réglé avec la découverte d'une autre forme, le spectre.



Bien que les prémices de la gestion de l'information automatisée viennent de l'Époque moderne, au 17 ème siècle, période avec un besoin grandissant de calcul ; l'informatique naquit après la révolution industrielle, au 19&nbsp;ème siècle lors de l'Époque contemporaine, et ne commence à réellement émerger qu'après la seconde guerre mondiale qui marque le début d'une nouvelle ère de progrès technologiques, accompagnée d'une forte augmentation de la démographie mondiale causée par le baby boom. Les machines à calculer ne datent pas d'aujourd'hui, le premier programme quand à lui à été imaginé en 1842, pour autant, il faudra attendre 1950 pour voir apparaître l'assembleur et les premiers langages de haut niveau. 

L'informatique moderne comme toutes les technologies, a d'abord exploré les possibilités en créant de multiples outils et techniques, puis sa démocratisation a nécessiter une standardisation. Des consensus se sont alors formés, ils ont établit des normes, simplifier et harmoniser les outils et techniques en les rendant universels. C'est le cas du web avec le W3C et HTML, CSS et JS, ou des protocoles réseaux comme TCP/IP, HTTP, et j'en passe. Tous établissent des bases communes à suivre pour établir des systèmes de communications sécurisés.

Les recherches et compréhension récentes dans le domaine de la bio-informatique ou de la physique quantique ont permis d'imaginer une nouvelles manière de stocker de l'information dans de l'ADN ou dans des bits quantiques appelés qubits. La théorie des nœuds dont j'aurais aimé plus parler a trouvé des applications dans l'étude des protéines et plus généralement des molécules. Grâce à ces études, les scientifiques ont été capable d'inventer de nouvelles structures moléculaires plus solide que le kevlar. Ces nouvelles technologies ouvrent de nouveaux horizons, repoussant les limites du possible en solutionnant de multiples problèmes, nous permettant par la suite d'en trouver de nouveaux. Les systèmes de communication sont rapidement passés du télégraphe à l'appel téléphonique, jusqu'à l’avènement d'internet à la fin du siècle dernier. Cette mondialisation de l'information et son instantanéité nous permettent aujourd'hui de collaborer n'importe quand avec n'importe qui, où que l'on soit, d'avoir accès à des connaissances et de trouver réponse à nos questions.

[Retour](#Introduction)

## 1.8. Pratiques actuelles

L'informatique est désormais omniprésente, la terre est entourée de satellites en orbites, les continents sont interconnectés avec des câbles sous marins, 7 personnes sur 10 possèdent un smartphone, les demandes d'informations et démarches administratives se numérisent rapidement. La programmation est facilitée par l’apparition de langages haut niveau à la syntaxe simple avec des compilateurs plus explicites. Depuis 1950, bien que les interfaces graphiques aient permis de faciliter l'utilisation des ordinateurs, la programmation n'a plus été révolutionnée depuis les premiers langages haut niveau. Seul l'apparition du langage Rust, dont l'adoption dans les entreprises sera encore longue, à permis d'avoir un nouveau candidat avec des performances équivalentes au C et une expérience de développement plus agréable que les autres, et ce grâce à ses nouveaux concepts de gestion de la mémoire, évitant ainsi 70% des bugs selon Microsoft.[^w4]

Pour le reste, la majorité des langages ont leur propres qualités notament grâce à leur communautés et aux outils qu'elles ont développés, le Python est toujours une référence pour le traitement de la donnée, et le JavaScript à standardiser la gestion des 



### 1.8.1. Méthodes d'aide à la structuration d'information 

Le management moderne à eu besoin de pouvoir former et guider efficacement ses employés et pour cela il à fallu trouver des outils et moyens mnémotechniques pour facilement analyser les facteurs influent sur l'activité d'une entreprise, une des plus ancienne est la carte heuristique plus connue sous le nom de carte mentale. Née de l'arbre de porphyre, un philosophe néoplatonicien du 3è siècle, elle représente visuellement le cheminement de la pensée et l’interconnections des idées afin d'en extraire les toutes les informations importantes.



#### 1.8.1.1. Décision

PESTEL

Strenght Weakness Opportunity Threat (SWOT).

matrice multicritère

la matrice d'Eisenhower

"5 Why"

5S Supprimer, S'organiser, Scintiller, Standardiser, Suivre

QQOQCCP : L'Éthique à Nicomaque d'Aristote[^b36] 

Un objectif SMART doit être **s**pécifique, **m**esurable, **a**tteignable, **r**éaliste et **t**emporel.



#### 1.8.1.2. Gestion de projets 

##### 1.8.1.2.1. Roadmap

###### 1.8.1.2.1.1. Project charter

###### 1.8.1.2.1.2. GANTT

###### 1.8.1.2.1.3. Business Model

###### 1.8.1.2.1.4. Scrum





#### 1.8.1.3. Conception

##### 1.8.1.3.1. Design thinking

##### 1.8.1.3.2. Lean Startup

##### 1.8.1.3.3. MVP

itération, stop de toute la chaine de production si problème pour éviter de contaminer le reste





### 1.8.2. Appareils

Ordinateurs portables Mobiles Tablettes Casques de réalité virtuelles





### 1.8.3. Usages et industrie du logiciel

#### 1.8.3.1. Navigation web



#### 1.8.3.2. Automatisation

#### 1.8.3.3. Robotique

- Honda asimo 2000
- Roomba **2002**
- Darpa Grand Challenge **2005**
- DJI **2013** Premier drone commercial autonome
- Boston Dynamics 

#### 1.8.3.4. Aide à la décision

#### 1.8.3.5. Progiciel

#### 1.8.3.6. Ludiciel

Les fois où j'ai appris le plus rapidement des concept était encore une fois à l'aide de jeux, la redstone de minecraft m'as transmis la logique créative et utile, flexboxfroggy.com m'as permis d'apprendre le 

#### 1.8.3.7. Jeux en ligne et MMO

#### 1.8.3.8. Chiffrement actuels

- RSA  1977
- Chiffrement sur courbes elliptiques 1985



### 1.8.4. Concepts et outils de programmation

#### 1.8.4.1. Langages

Nous parlons communément un langage naturel, spontané, qui bien qu'il possède des règles de syntaxe, un vocabulaire et une grammaire définis, ne nécessite pas systématiquement de les suivre à la lettre pour communiquer. Le langage formel ou construit comme le code informatique ou le Lojban nécessite quand a lui une rigueur stricte sans quoi il ne peut être interprété par la 

formel, informatique, et construites

Syntaxe, vocabulaire et Grammaire

Pseudo Code parlé & Lojban



#### 1.8.4.2. Ligne de commande

L'interface la plus simple informatiquement parlant est la ligne de commande, elle a un avantage. Celui d'être totalement textuelle.



#### 1.8.4.3. Types et structure de donnée

Types primitifs, Vecteurs, Matrices



#### 1.8.4.4. Bases de la programmation objet

Variables

Function

Classes

Héritage



#### 1.8.4.5. UML

Flowcharts 1920

**1996**, Grady Booch, James Rumbaugh et Ivar Jacobson, trois ingénieurs travaillant sur des langages de modélisation objets différents, décident de s'unir pour co-créer un Langage de Modélisation Unifié qui avec l'inversion anglaise donne l'acronyme UML. Reprenons notre véhicule qu'est la voiture, nous pouvons la modéliser ainsi en UML.





https://hal.science/hal-02970135/document



#### 1.8.4.6. Performances et Optimisations

##### 1.8.4.6.1. Techniques

1. Parallélisation
2. Pointeurs mémoires
3. Calculs distribués



##### 1.8.4.6.2. Managériales

DevOps, intégration et déploiement continus (CI / CD) 

1. Commentaires et documentation

   Chaque fonctionnalitée doit être documentée.

   Chaque ligne devrait être commentée en langage naturel, un switch devrait permettre de basculer entre le code réel et commenté. Toute manquement déclancherai une notification sur la ligne en question.
2. Gestionnaires de version 

Git est un logiciel de gestion de versions décentralisé sous licence GNU GPL. C'est un logiciel libre et gratuit, initié en **2005** par Linus Torvalds le créateur de Linux lors de la création de son noyau. Linus ne voulait pas réaliser ce projet seul et a rapidement compris que la qualité d'un logiciel viendrai des débats houleux entre ses collaborateurs et l'implémentation de la meilleure idée à la fin. graphe d'historique de modifications de fichiers visualisable avec gource.

5. Microservices



#### 1.8.4.7. Quelqu'un à généralement la solution

Patrons de conceptions  *A Pattern Language : Towns, Buildings, Construction* en **1977**. 



#### 1.8.4.8. Principes SOLID

Robert Cecil Martin = Oncle Bob & explications

#### 1.8.4.9. VSCode

Suite à Atom publié par GitHub le 26 février 2014, bien avant son rachat en 2018 par Microsoft, qui l'a refait en mieux, en sortant le 29 avril **2015** l'IDE le plus utilisé à ce jour Visual Studio Code.



#### 1.8.4.10. Intelligence artificielle

- Deep Blue beats Gary Kasparov  in **1997**
- Imagenet **2009**
- Watson gagne Joepardy **2011**
- Alphago **2015**







[Retour](#Introduction)

## 1.9. Essai

Avant d'arriver à l'ultime partie qui répond pleinement à la problématique, je vais à travers cet essai décrire ma philosophie personnelle découlant de l'ensemble de mon vécu et de mes connaissances. Mais avant tout, j'en suis venu à plusieurs notes sur l'information, semblables à celles écrites en préambule à la fin de l'introduction.



**Notes :**

- Tout est relatif à l'information.
- L'information émane du matériel et le transcende.
- L'information se reproduit réellement que lorsqu'elle se manifeste et émerge du matériel grâce à de l'énergie.
- L'information peut être une illusion ou déformation de la réalité.



### 1.9.1. Information

l'étymologie latine "*informare*" signifie donner forme ou se former une idée de quelque chose.

### 1.9.2. IO

Entrées et sorties, Inputs et Outputs (IO), lecture et l'écriture, en C# .NET [`System.IO`](#https://learn.microsoft.com/en-us/dotnet/api/system.io?view=net-7.0)

### 1.9.3. Habitudes

Mode, volonté.

signal, envie, action récompense => répétition qui la caractérise. 

### 1.9.4. Valeurs

La valeur d'une chose ne dépends que du prix qu'un acheteur est prêt à dépenser pour l'acheter. Les valeurs d'une personne ne dépendent quand à elle que du prix qu'elle est prête à accepter pour les renier. En informatique, la valeur est l'information que l'on stocke dans une variable. 

### 1.9.5. Rapport de force, ordres de grandeur et précision

Base 10

Puissances

composition 

[c4model](https://c4model.com/)

Loi de Moore, Volume de donnée internet ou chat gpt

probabilités sachant que.

le big deal

Théorie du chaos et contextes intriqués, un grand tout.



#### 1.9.5.1. Signaux forts et faibles

épisode 22 de la série Baki dans lequel un combattant spécialisé en environnement fait taire toute une arène en criant extrêmement fort. Tout étudiant l'a déjà expérimenté, on a tous déjà été dans une situation ou un groupe bruyant se tait après qu'une autorité ai hausser la voix.

### 1.9.6. Viralité

La viralité est un facteur mathématiquement calculable. C'est la moyenne de transmissions faites par les personnes atteintes par une information. Une information est virale dès que son facteur dépasse 1, autrement dis dès que la moyenne des personnes en sa possession la retransmettent à plus d'une autre personne.



### 1.9.7. Parasitage

informations parasites quand je travaille sur une fonction je n’ai pas besoin de voir autre chose que ses dépendances. le divertissement n'est pas nécessaire non plus. L'informatique et l'algorithmique nous permettent de répliquer a l'infini une information ou un traitement logique de donnée. 

croyances limitantes et mauvaise foi



### 1.9.8. Contexte et vérité

La vérité peut être absolue ou relative.

"L'eau mouille" n'est vraie que relativement à l'état de l'eau liquide...

Cette récursion de vérité absolu-relative => axiomes

Démonstrations, "si et seulement si [...] alors" en mathématique.

dialectique, futile de vouloir avoir raison. mauvaise foi est l’ennemie de l'amélioration personnelle. Seule la vérité absolue compte.

Dialectique : garder sa parole distincte de celle de son interlocuteur.

### 1.9.9. Doute

Il faut douter de tout même de ce que l'on sait, il faut challenger constamment sa vérité relative pour la remettre en question et s'approcher de l'absolu. Toute notre expérience de la vie introduit des biais dans nos apprentissages. Bien qu'il y'est un certain déterminisme dans le monde, il est multifactoriel. On est certain de rien qui ne soit pas vérifié et prouvé ou que l'on expérimente soit même avec une bonne proportion de réussite.



### 1.9.10. Preuves

Hiérarchie des preuves, et niveaux de preuves





### 1.9.11. Apprentissage

Mémorisation => compréhension => résolutions de problèmes ==> créativité = savoir + savoir faire.

Mémoire de travail et mémoire à long terme.

Amorces, schémas mentaux. Reformuler et réexpliquer [^v5]

Apprentissage par l’erreur, sans elle rien ne serais possible le succès ne s’obtient qu’en résolvant des micro problèmes. N'apprenez pas par cœur, comprenez et retenez la logique derrière.



### 1.9.12. Informatique et Éducation

Compétences numérique, sociales et civiques, ainsi qu'apprendre à apprendre, fasse partie du socle commun des connaissances et des compétences, je pense qu'elles sont négligées et que l'on devrais enseigner des choses plus concrètes comme le suggérait John Dewey dans *School and Society*.

L'éducation ne doit pas fournir tout les outils existants, mais apprendre à l'élève comment trouver les outils et informations dont il aura besoin en plus de lui apprendre à apprendre, et ainsi lui indiquer comment il peut s'autoformer. L'école et l'éducation nationale n'ont pas le monopole du savoir.

Didactique : contenus des cours

Des études montrent désormais que l'apprentissage se fait mieux par la récompense que la punition.[^w1] Il est plus productif d'encourager un bon comportement que d'en réprimander un mauvais, bien que cela soit parfois nécessaire, il vaut toujours mieux orienter sa pédagogie de manière positive. 



Pédagogie active et mutuelle. Un bon apprentissage est avant tout du ressort de l'apprenant.

L'autodidaxie permettent à l'élève d'être acteur de son apprentissage.

https://www.youtube.com/watch?v=Vl_S21D7j9w

"Learning by doing", Rustlings, Scratch, FlexboxFroggy, CodingGame, Logo.

La tablette pourrait remplacer les manuels scolaires.

Enfin je terminerai avec une citation de jeu vidéo, Maitre Yi dans League Of Legends dit "*Un vrai maître est un éternel étudiant*".

###   1.9.13. Informatique et Cuisine

La cuisine est selon moi une science combinatoire et une philosophie à part entière regroupant les mathématiques, la biologie, la physique-chimie, et plein d'autres sciences y compris sociales ou neurologique. C'est un grand tout, depuis l'antiquité, les recettes sont des formulations logiques, les ingrédient sont biologiques, leurs modifications par leurs préparations, formes, mélanges, et leurs méthodes de cuissons, sont physiques, les proportions quant à elles sont mathématiques.


### 1.9.14. Communication & Compréhension

L'allégorie de la ligne ou celle de la caverne énoncée par Platon sont également la pour nous rappeler que la connaissance peut être hiérarchisée en fonction du contexte et niveau de compréhension.

Il est intéressant d'abaisser son raisonnement en utilisant une métaphore pour expliquer simplement un concept à un initié, tout comme il est important de laisser cet initié le reformuler et corroboré pour vérifier sa compréhension, c'est ainsi que l'on valide la transmission d'une information et un apprentissage, en le testant.

transparence, adéquation clarté crédibilité, réactivité



### 1.9.15. Professionnalisme

J'aimerai appliquer la dialectique à l'entreprise, avec des visioconférences 1:1

On agit tous différemment dans le contexte professionnel. Effectuer un métier n'est pas compliqué, le réaliser avec des gens l'est plus. Il faut tellement de compétences managériales qu'il nous faut. Quand je suis dans le milieu professionnel, j'exerce une fonction, ou une liste de fonctions définies par le contrat de travail.

Philosophie d'entreprise. groupe de personnes physiques réunies pour accomplir quelque chose en commun. => secte, connoté négativement mais d'un point de vue étymologique, le mot provient du latin "secta", signifiant "voie que l'on suit, parti, cause, doctrine". Or quand je travaille en groupe avec d'autres personnes, je le fait de pair avec mes collègues, suivant ensemble une même voie, pendant une période définie de travail, comme tout salarié qui se vends a son employeur.

### 1.9.16. Prestation vs édition de logiciel

Le modèle économique d'une entreprise influence énormément les comportement de ses salariés. Contraintes de temps et de budget.

Les prestataires vendent du temps, et ont donc naturellement tendance à avoir des deadline plus courtes et par conséquent plus de pression. Cela nécessite également une équipe commerciale solide capable de décrocher assez de projet pour faire travailler l'entreprise pendant les prochaines années. En contrepartie, ce n'est pas un logiciel ou site maintenable qui est demandé, mais il faut qu'il soit assez bien réalisé et fonctionnel pour être livré le plus rapidement possible afin d'en dégager une marge. 

Les éditeurs logiciels quant a eux le louent généralement en tant que service ou le vendent en tant que bien, le nerf de la guerre réside alors dans la maintenabilité du logiciel auquel doit être ajouté des fonctionnalités au fil du temps. Plus le logiciel grossit, plus il est compliqué de maitriser les effets de bord et de comprendre l'intégralité du logiciel et de son historique. Ils ont cependant la chance d'avoir conçu une sorte de distributeur automatique qui n'a pas besoin d'action humaine.

### 1.9.17. Division du travail

Charles Babbage a visité des maison d'échanges bancaires, et autres établissement de gestion, comme le bureau du cadastre qui du réaliser des cartes à jour pour établir une taxation. Il était fasciné par la division mentale du travail qui s'y opérait, la personne en charge du cadastre était le Baron Gaspard De Prony qui a également réaliser les *Grandes tables de logarithme* en seulement deux ans grâce à ses lectures des travaux d'Adam Smith, notamment de son œuvre "*Recherches sur la nature et les causes de la richesse des nations*"[^b37]. Ce dernier à été le premier à décrire le principe de division du travail. Ce principe sera par la suite réutilisé pour optimiser les temps de formations du personnel et de réalisation d'un produit. 

### 1.9.18. Astrologie

Oui le mois de naissance influe sur votre vie, mais cela n'a rien à voir avec des constellations à des années lumières, mais au soleil, qui est à la base même d'une révolution de la terre autour de lui, l'année elle même. En effet les maladies sont plus présentes en hiver et peuvent affecter le bébé lors de la gestation. Croire que la position des astres dans le ciels peuvent avoir une influence sur nous est scientifiquement ridicule, surtout sachant que l'on ne sait qu'il est au centre que relativement récemment et qu'encore aujourd'hui nous ne pouvons qu'approximer les distances entre les astres.

### 1.9.19. Divin

Je suis agnostique, je ne sais des Dieux s'ils sont ou pas. Je pense que l'entité qui à créé l'univers et celle qui pourrait être omnisciente ne sont pas forcement la même entité. Pour autant, je pense que le divin est omniprésent, chaque bonne action, chaque amélioration à du divin en elle. Le bien est universel, on ne doit pas faire à son prochain, ce que l'on aimerai pas qu'il nous fasse. Morales transmises par les textes sacrés. Raison et la tempérance. Absence de jugement et le fait qu'il faille parfois limiter son savoir pour laisser une place à la croyance et comprendre la manière de penser des gens. 

Selon moi la vraie question à se poser face à une information douteuse serait "Est ce que c'est scientifiquement démontrable ?" Celle a se poser vis à vis d'une croyance serait quant à elle : "What if ?" autrement dit : "Que se passerai t'il si je me mettais à croire ça ?".

> "It was there noticed that the action of thought is excited by the irritation of doubt, and ceases when belief is attained; so that the production of belief is the sole function of thought."
>
> Charles S. Peirce - *How to make Ideas clear*



### 1.9.20. Effets des croyances

Une prophétie autoréalisatrice, Effet Pygmalion, et Golem.

Méthode Coué = répétition de l'Effet Pygmalion. Effet Hawthorne sujet a conscience qu'il est testé sa motivation augmente

La loi de Murphy

Menace du stéréotype.

Effet Mathieu

De manière générale, nos attentes conditionnent nos réactions.

Peur de la mort, réincarnation, DMT.



### 1.9.21. Intelligence

Etymologie

ChatGPT n'est pas capable de raisonnement mais il fourni une solution mathématique probabiliste à un énoncé textuel. Il connais les mots qui le compose, sait qu'il y a tant de probabilité qu'ils y sont liés et les assemble de manière à proposer une réponse elle même textuelle.



Cervear, neurones, cellules gliales, isolantes => myéline. Astrocytes 

L'intelligence est plus globale et dépend d'un environnement donné. Comme l'aurai dit Einstein, dont le cerveau à été analysé et a permit d'avancer sur les recherches portant sur les astrocytes : "on ne doit pas juger un poisson à sa capacité à grimper à un arbre". Le test de QI n'est selon moi pas représentatif de l'intelligence d'une personne, car elle n'évalue pas la capacité d'une personne à vivre au mieux possible dans son environnement. 



### 1.9.22. Consciences

L'intelligence émane du matériel de la même manière que l'information

La conscience est le fait d'analyser et comprendre une information émanant dans notre cerveau.

La perception n'est pas nécessaire : vision aveugle[^w2].

Les théories les plus récentes de la conscience disent que c'est le fait d'avoir une information disponible à un moment T pour la partager à l'ensemble des traitements du cortex cérébral. Conscience information != conscience de soi => métacognition. 

https://www.youtube.com/watch?v=dGo5Whv-VCU
mémoire onirique

Percevoir la réalité c'est rêver de la réalité, notre conscience est limité par la réalité physique, le rêve pur n'est contraint que par notre conscience





### 1.9.23. Anticipation

L'imagination nous permet de se projeter dans les différents scénarios possibles, si on commence a croire qu'une chose va se passer, on se demande alors : 'Qu'est ce qui arriverai probablement si cela se produit ?"

example avec la compiltion rust qui empeche les top 10 des erreurs

extrm prog

Planning poker, reu tech, mais pas d'analyse commune -> rework et pair programming.

### 1.9.24. Temps 

Tout est temps, c'est l’écoulement des choses, l'itération des actions qui s'écrivent et se succèdent.

### 1.9.25. A posteriori

Restaurer l'information perdue, vesuvius challenge https://scrollprize.org/

On a récemment avéré que les techniques de peinture des grand maîtres ont étés transmises par Léonard de Vinci qui expérimentait de nouvelles techniques de peintures comme une première couche à base de plomb nommée Plombonacrite

https://www.journaldugeek.com/2023/10/16/un-accelerateur-de-particules-revele-un-nouveau-secret-de-la-joconde/?utm_source=pocket-newtab-fr-fr

https://pubs.acs.org/doi/10.1021/jacs.3c07000







### 1.9.26. Développement personnel

On invente rien en réalité, on découvre le monde, on essaye de comprendre ses règles et les utiliser chacun a notre manière avec notre perception, sensibilite et connaissances.

#### 1.9.26.1. Planifier et prendre son temps

Les deux vont de pair, il ne sert à rien d'être dans la précipitation, on peut être rapide mais il ne faut pas oublier la rigueur ou tenter de faires plusieurs choses à la fois. Il vaut mieux prendre une pose ou faire quelque chose pendant une attente, que d'être happer et l'oublier. Et si on doit changer de tâche, alors il faut la noter et mieux, la planifier.

#### 1.9.26.2. Rigueur et retravail

Démarche itérative avec demande de feed-back à chaque changement, besoin de ne pas renvoyer la balle mais de demander conseil sur le moment si possible pour encore plus d'agilité. On m'a reprocher mon manque de rigueur, mais personne ne fait les choses correctement en amont de mon travail de technicien. Les cahiers des charges sont incomplets, le cahier des charges technique inexistant.

Ce qui m'agace le plus dans la rédaction des tickets, au delà du manque d'information, c'est l'information incorrecte qui pousse à suivre le déroulement indiqué pour ne pas avoir la finalité problématique décrite. On se retrouve dans l'incapacité de reproduire le problème qui nous laisse penser qu'il n'y a potentiellement pas de problème.

#### 1.9.26.3. Amélioration continue

Doute constant et remise en question en sont la clé.



#### 1.9.26.4. Standardisation & Universalité

L’uniformisation => langage commun. Système métrique

Interopérabilité instantanée inter-appareils, édition live multiutilisateur 



#### 1.9.26.5. Do it now

J'ai souvent entendu dire "ce n'est pas ce qui est demandé ni prioritaire, on fera ça plus tard", et bien évidement, la plupart du temps cela fini par n'être jamais fait. Dans les projets informatique c'est ainsi que la dette technique s'immisce, des fonctionnalités qui s’accumulent, des développements qui s’enchaînent, et pallie aux problèmes qu'avec des corrections rapides, s’attaquant aux causes plutôt qu'aux conséquences.

Dès que l'on constate un problème, il faut avoir le réflexe de réaliser la tâche dans la foulée, ou de la planifier pour ne pas que l'information se perde. 



#### 1.9.26.6. Aide

Demander de l'aide => beaucoup d'effort

en difficulté, => l'aide qui devrait venir à nous, et pas l'inverse.

Ce qui fait la force de l'humanité, c'est l'amitié et l'entraide, sans cela cette dernière n'aurais jamais réussi à aller aussi loin dans l'histoire. "Seul on va plus vite, ensemble, on va plus loin."



#### 1.9.26.7. STOP

Dans le monde du travail, comme personnel, il faut savoir imposer son rythme et le justifier, tout comme savoir prendre des pauses et du recul pour analyser, afin de partir dans la bonne direction plutôt que d'avancer continuellement de manière imprécise et inefficace. Il est important de prendre soin de soi avant tout, cependant, quelqu'un qui bloque sur un problème n'avance plus et peut retarder les autre également. 

Problème dans une chaîne de production => tout arrêter pour éviter qu'il n'impacte le reste.

Les confinements comme celui que l'on a eu lors de la période du Covid nous le confirme également. Il vaut parfois mieux tout mettre en pause pour éviter de foncer dans le mur et mieux repartir par la suite.



#### 1.9.26.8. Justification

Lorsque je commet une erreur, j'en assume la responsabilité, mais je me justifie souvent. Cela me permet d'identifier les causes du problème, et ainsi de clarifier la situation pour éviter de le reproduire. Dans le livre Lean Startup il est mentionné une phrase qui m'a marquée. L'idée est que lorsqu'une erreur survient, il est de notre responsabilité d'avoir rendue la faute si facile à commettre. Autrement dit, lorsqu'une personne faillit à sa tâche, il ne faut pas remettre en question sa responsabilité ou sa compétence, mais se demander pourquoi l'environnement n'a pas permis la réussite de l'action et rendu la situation d'échec si probable qu'elle c'est produite.



#### 1.9.26.9. Critique

Selon moi la critique constructive est positive pour le maître et l'apprenant des lors quelle s'effectue avec une communication positive tout en analysant les défauts et planifiant un programme pour les corriger. 



#### 1.9.26.10. Développement informatique

Collaboration et travail d'équipe : Dans de nombreux projets, plusieurs développeurs doivent collaborer et travailler ensemble sur le même code, ce qui peut entraîner des conflits de version, des problèmes d'intégration et de coordination.

En tant que chef d'entreprise, je me fiche du langage que tu utilise, fait le en patate ou en carotte si tu veux, mais réalise les fonctionnalités demandés, interconnecte les et fait en sorte que ça marche de manière pérenne, je me fiche du temps que ça prends, quand tu aura fini ta tâche, documentée elle sera, par n'importe qui elle pourra être reprise, et optimisée tu l'aura.

Tout devrait être automatique, je suis ravi que le prélèvement à la source ai permis d'automatiser les impôts, mais ça devrait également être le cas pour les aides, les assurances, mutuelles, et tout recours aux droits qui nous sont conférés, les loi devrait être des algorithmes, le système devrait être juste et positif, pour tous, réguler les ordres de grandeurs, réduire les inégalités, être réalisé pour le bien commun et non l'avarice, l'excentricité et la démesure.



### 1.9.27. Metagame

Toute forme de vie réponds à un algorithme très simple. Comment maximiser mes récompenses en minimisant mes efforts ?

Intelligence économique, politique, choix et théorie des jeux.

Jouez au jeu, suivez le pacte d’Ulysse.

https://ayowel.github.io/trust/



1. La magie c'est de défaire et savoir refaire
2. Biais humain, machine, et réalité de la donnée (illusions de captation, interprétation, context)





[Retour](#Introduction)

## 1.10. EditIDE ou "Comment repenser la gestion de l'information pour moderniser l'expérience développeur ?"



### 1.10.1. Pourquoi la programmation est-elle aussi peu démocratisée ?

Soyons franc, pas tout le monde n'a besoin de savoir coder. La meilleur qualité d'un codeur n'est d'ailleurs pas savoir coder, c'est sa capacité à proposer une solution logique à un problème de donnée.

Je vais donc répondre à cette question avec quelques informations statistiques.

En 2013, 1 personne sur 623 était développeur professionnel, soit 0,16 % de la population mondiale. Et 1 personne sur 387 savait alors coder, soit 0.26%. En novembre 2022, la population a dépassé les 8 milliards d'habitants, celle des développeurs représente alors 27.7 millions, soit 0.35%.

La même année, 40 % des recruteurs prévoyaient d’embaucher 50 développeurs ou plus. L’étude liée à cette information note également que le pourcentage de ceux qui recrutent de 201 à 500 personnes a doublé par rapport à 2021. Le problème le plus notable est dans le web où il y'a 60 postes disponible pour 38 développeur en demande d'emploi.

- 70 % des développeurs plébiscitent le travail à distance - complet ou partiel.
- 57 % des recruteurs se déclarent prêts à se passer du CV du processus de recrutement. 
- Le pourcentage de recruteurs qui recrutent des développeurs sans bagage académique a presque doublé (de 23% en 2021 à 39% en 2022). 
- 42 % des recruteurs souhaitent utiliser des solutions d'évaluation basées sur les compétences pour améliorer la diversité. 
- L'expérience candidat est la première priorité dans laquelle les recruteurs prévoient d'investir pour 2022. [^w3]



Il y'a donc des opportunités immenses pour les autodidactes et les écoles en informatique. Mais la discipline requiert des études avancés, et qui ne sont pas ou trop peu enseigné lors de l'instruction obligatoire au lycée.

C'est également une discipline en constant changement, qui requiert beaucoup de connaissances et de pratique. Les développeurs expérimentés sont logiquement très recherché. Pour les mêmes raison, c'est dur d'être dévoué à se domaine, nombre de personnes le quitteront pour quelque chose qui leur convient mieux. Cependant c'est une science et technologie qui est désormais omniprésente dans nos vies et apprentissages. Je suis donc d'avis qu'une généralisation de l'introduction à la programmation en cours de technologie au collège, permettrait aux élèves de savoir si ce domaine les intéresse, d'avoir la possibilité de choisir de prendre cette discipline au lycée, ou juste de pouvoir apprendre par lui même tout en continuant dans une autre voie.

Il y’a un manque d’experts, de personnes compétentes et qualifiées, les années que nous vivons sont saturées d'informations, et l'accumulation de mauvaises nouvelles déprime les uns, là où les tsunamis de désinformation et canulars font rire et haïr les autres. La vérité finissant presque par ironiquement nous consoler.

Et un réel décalage entre offre et demande, nous observons des signaux forts comme ceux autour de la blockchain, technologie ayant un réel intérêt et pouvant jouer un rôle important, notamment dans les systèmes administrant nos sociétés mondialement interconnectées, mais qui présentent cependant un effet Duning Kruger assez important ces derniers temps.



### 1.10.2. Pourquoi un outil censé résoudre un problème en cause parfois des bloquants ?

Les outils no-code fleurissent ses dernières années, ils permettent certes la réalisation de produits plus rapidement qu'un partant d'un cadriciel et en le codant soi même. Cependant dès que l'on désire un rendu différant de ce qui est proposé par le service, cela provoque un blocage, nécessitant l'intervention d'un développeur et de code, les services le proposant sera alors considéré comme low-code et non no-code.

### 1.10.3. Qu'elle est l'origine des bugs ?

A l'exception d'une erreur matérielle venant corrompre la mémoire ou interférer avec un signal, une ne machine fait que ce que son programme lui indique, les bugs sont donc presque toujours dus à une erreur humaine. Elle vient soit du besoin initial mal compris, transmis, ou implémenté, soit d'un enchaînement d'implémentation causant des effets de bords et venant modifier des fonctionnalités existantes pouvant devenir incompatibles avec les nouvelles demandes et besoins.

Les erreurs fatales viennent généralement de problème mémoire ou de langages non compilés, qui n'ont donc pas de programme obligeant l’absence d'erreur avant usage. Et en tant que développeur, je peut vous dire que si on le processus ne force pas les utilisateur d'un outil à faire les chose bien et corriger tout les potentiels problème, ils vont juste s'accumuler et former de la dette technique.

### 1.10.4. Comment l'interface permet et conditionne l'accès aux fonctionnalités ?

L'interface relie un élément graphique à une fonctionnalité, toute interaction de l'utilisateur doit lui indiquer ce qu'il peut faire par la suite.

Un utilisateur averti sais qu'il a sur son clavier des touches de modification comme CTRL, SHIFT, ou ALT permettant appliquer des effets, qu'il peut réaliser des sélection multiple, passer à l'élément suivant avec la touche tabulation, cocher ou découcher une case avec espace, valider avec entrée, supprimer avec la touche du même nom ou la touche retour. Je pense 

##### 1.10.4.0.1. Etude de cas UX/UI FL Studio VS Ableton



### 1.10.5. Comment faire un logiciel en tant que service ?

Imaginons que vous vouliez réaliser un logiciel et qu'il soit accessible en ligne, en réalité il vous suffit d'une connexion internet de trois fichier, d'un logiciel de serveur, et enfin d'un nom de domaine pour y accéder sans avoir à mémoriser une adresse IP.

Ce que j'ai fait, tout le monde peut le faire, et comme l'humain ne comprends quelque chose que lorsque qu'il arrive le réexpliquer plus simplement, à le factoriser, rendre une information usinée, et bien je vais présenter plusieurs cas d'études et vous présenter ce qu'est EditIDE



#### 1.10.5.1. Site web

Pour un utilisateur avertit, la démarche peut ne prendre que quelques minutes, allez, petite démonstration :



##### 1.10.5.1.1. Etape 1 : Réaliser un site web

##### 1.10.5.1.2. Etape 2 : ouvrir les ports

##### 1.10.5.1.3. Etape 3 : mettre un serveur en service

Télécharger NGINX,

👉https://nginx.org/en/download.html

##### 1.10.5.1.4. Étape 4 : Configurer un nom de domaine (Facultative)

Première possibilité, votre box possède une IP fixe ou une option pour qu'elle le soit.



#### 1.10.5.2. Lancement du site au démarrage

Sur Windows il suffit de trouver le dossier Démarrage ou Startup, il est censé être situé au chemin `C://` mais la solution la plus facile pour y accéder est de faire `Windows + R` de taper `%startup%` et de valider. Vous pouvez ensuite épingler le dossier au menu d'accès rapide pour le retrouver plus facilement. Tout raccourci que vous mettez dedans sera exécuté au démarrage. Il ne manque donc plus qu'a réaliser un script avec la commande 



#### 1.10.5.3. Bureau à distance

Parametres windows => port 3389 /!\ ne pas ouvrir le port 3389 et d'installer un VPN pour accéder au réseau local de manière sécurisée.



### 1.10.6. Comment architecturer un système d'information ?

Medias

2SIG Interfaces

1. Structure
2. Style
3. Interaction
4. Gestion de la donnée





### 1.10.7. Qu'elle est la plus-value d'EditIDE ?

Web builders are bad.



Un ludiciel doit être vivant, animé, utilisé, collaboratif.

Réalisation de projets WMD (WYSIWYG meta dogfood) à commencer par les articles markdown

Flux de travail d'EditIDE

1. Gestion projet
2. API
3. Interface
4. Sécurité et permissions.
5. Mise en ligne
6. Comment reproduire le problème ? => Cypress test



##### 1.10.7.0.1. One thing at a time

Where AM I ? (Path)



##### 1.10.7.0.2. WYSIWYG

Elementor / Typora / Python Notebook

plus besoin d'alt tab entre votre ide et le navigateur 

NO MORE CLI NO MORE BLOCNOTE



##### 1.10.7.0.3. Accessibilité



##### 1.10.7.0.4. All in one

Plus un projet a d'intermédiaires, plus il y'a de risques d'erreurs. Dès le fondement de l'informatique, Charles Babbage l'avait déjà compris et sa machine faisait à la fois le calcul et l'impression car beaucoup d'erreur arrivait lors de l'impression.

Certains problèmes arrivent également lors de l'échange entre l'équipe design et l'équipe technique.

Tout ses problèmes arrivent car rien n'est centralisé, à une heure ou la collaboration est mise en avant comme jamais. 

Dans EditIDE, tout ce ferait sur le site lui même. Le design et l'intégration ne ferait désormais plus qu'un, les développeurs front ne seraient chargés que de dynamiser les design déjà intégrés avec les appels API du back qui seraient auto-générés. 



##### 1.10.7.0.5. Visualisation

Sucres syntaxiques => d'interface graphique. Idem pour documentation => relié au code. 

Quand j'arrive dans un fichier de code, je veux savoir directement le nom des variables et fonctions qui le constitue, je me fiche d'avoir le contenu le détail ou d'entre elles, ni même leurs paramètres ou leur type de retour, bien que je doit pouvoir rechercher en fonction de ses derniers. De la même manière, quand je travaille sur une fonction je ne désire voir que ce qui concerne cette fonction.

Doit on avoir moins de fonctionnalité sur mobile ? Non, c'est l'interface qui doit changer et s'adapter à l'utilisateur.



##### 1.10.7.0.6. Documentation

Déscription documentation.

Doc API & Swagger

Solution EditIDE



##### 1.10.7.0.7. Gestion

Gestion de projet informatique, des bugs et des incidents. Que ce soit une nouvelle fonctionnalité ou un problème rencontré dans le logiciel, il convient d'énoncer clairement le problème afin que toute personne profane puisse le comprendre et le réexpliquer. 

>  For an individual, however, there can be no question that a few clear ideas are worth more than many confused ones.
>
> Charles S. Peirce - *How to make Ideas clear*

Dans le cas d'un problème dans l'application, je pense que l'idéal serait de demander à l'utilisateur qui rencontre le problème d'enregistrer la suite d'action et de la convertir en test d'interface automatisé (E2E). Je souhaite automatiser ce processus dans EditIDE pour pouvoir facilement recueillir et traiter les bugs en s'assurant que le comportement reste bon après résolution.



##### 1.10.7.0.8. Précision

Vue macro, vu micro, questions individuelles précises, groupe permet d'avoir le consensus.



### 1.10.8. Qu'elle sont les conditions de succès d'un logiciel ?

facilité d'utilisation, utilité, satisfaction, l'utilisation de l'application doit dépasser les attentes et promesses faites en amont







## 1.11. Postface : Rétrospective et métacognition

Commentaires et métacognition sur la rédaction du mémoire.

5V de l'information sont volume vitesse variété véracité valeur, pour écrire ce mémoire c’est surtout le volume et la bonne variété ou proportion ainsi que la véracité qui a été au coeur de mes préoccupations

Si il y'a bien quelque chose que l'on ne peut comprendre qu'en étant seul, c'est bien qu'être adulte concomite avec faire tout les jours un peu plus attention au soi de demain.

Puisque j'ai beaucoup travaillé sur l'écriture mémoire qui m'a tant appris, je finirai sur une citation de Célestin Freinet sur l'imprimerie et plus généralement sur l'écriture en tant qu'exercice pédagogique : 

> Dans la pratique, on ne se lasse jamais d’imprimer et les adultes se laissent prendre eux aussi à la minutie d’une technique qui permet la transcription en une forme magnifiée et définitive des textes auxquels on veut donner vie et harmonie. L’enfant qui compose un texte le sent naître sous sa main ; il lui donne une nouvelle vie, il le fait sien. Il n’y a désormais plus d’intermédiaire dans le processus qui conduit de la pensée ébauchée, puis exprimée, au journal qu’ils postent pour les correspondants : tous les échelons y sont : écriture, mise au point collective, composition, illustration, disposition sur la presse, encrage, tirage, groupage, agrafage. C’est justement cette continuité artisanale qui constitue l’essentiel de la portée pédagogique de l’imprimerie à l’école. Elle corrige ce qu’a d’irrationnel en éducation cette croyance que d’autres peuvent créer pour nous notre propre culture.
> Célestin Freinet, *Le journal scolaire*, 1967



## 1.13. Annexes



#### 1.13.0.1. Bibliographie

[^b1]: [BFN Gallica : Diogenes Laertius, *Vitae philosophorum, Ambrosius Traversarius Camaldulensis Ordinis interpres.*](https://gallica.bnf.fr/ark:/12148/btv1b84470700/f95.item.zoom)

[^b2]: [BNF Gallica : Euclide - *Élements*](https://gallica.bnf.fr/ark:/12148/bpt6k68013g/f3.item)
[^b3]: [BNF Gallica : Vitruve - *De Architectura* Tome 1](https://gallica.bnf.fr/ark:/12148/bpt6k236629.r=L%27architecture%20de%20Vitruve?rk=21459;2)

[^b4]: [BFN Gallica : Vitruve - *De Architectura* Tome 2](https://gallica.bnf.fr/ark:/12148/bpt6k23663n.r=L%27architecture%20de%20Vitruve?rk=42918;4)
[^b5]: [BFN Gallica : Sir Isaac Newton - *Newton's Principia : the mathematical principles of natural philosophy*](https://archive.org/details/newtonspmathema00newtrich/page/n7/mode/2up)
[^b6]: [BFN Gallica : Sir Isaac Newton - *Opticks Treatise*](https://archive.org/details/optickstreatise00newta/page/n9/mode/2up)
[^b7]: [BFN Gallica : Francis Bacon - *Novum Organum*](https://archive.org/details/1762novumorganum00baco/page/n3/mode/2up)
[^b8]: [BFN Gallica : Jean-Jacques Rousseau - *Discours sur l’origine et les fondements de l’inégalité parmi les hommes*](http://classiques.uqac.ca/classiques/Rousseau_jj/discours_origine_inegalite/discours_inegalite.pdf)
[^b9]: [Google Books - Giambattista della Porta : *De furtivis literarum notis, vulgo de ziferis* Livre IV](https://books.google.fr/books?id=DcI9AAAAcAAJ&pg=GBS.PT3&printsec=frontcover&redir_esc=y#v=onepage&q&f=false)
[^b10]: [BNF Gallica - Blaise de Vigenère : *Traicté des chiffres, ou Secrètes manières d'escrire*](https://gallica.bnf.fr/ark:/12148/bpt6k73371g)
[^b11]: [Internet Archive - Richard Brathwait : *The young mans gleanings gathered out of divers Fathers* 1614](https://archive.org/details/bim_early-english-books-1475-1640_the-young-mans-gleanings_b-r-gent_1614)
[^b12]: [BRN - Johann Heinrich Pestallozi : *Leonard et Gertrude* (FR)](https://ebooks-bnr.com/ebooks/pdf4/pestalozzi_leonard_et_gertrude.pdf)
[^b13]: [Internet Archive - Johann Heinrich Pestallozi : *Leonard et Gertude* (EN)](https://ia800702.us.archive.org/34/items/leonardgertrude00pestiala/leonardgertrude00pestiala.pdf)
[^b14]: [BNF Gallica - Johann Heinrich Pestallozi : *Comment Gertrude instruit ses enfants* (FR)](https://gallica.bnf.fr/ark:/12148/bpt6k5516141m.texteImage)
[^b15]: [Internet Archive - Johann Heinrich Pestallozi : *Comment Gertrude instruit ses enfants* (EN)](https://archive.org/details/howgertrudeteach00pestuoft/page/n5/mode/2up)
[^b16]: [Internet Archive - Andrew Bell : *An Analysis of the Experiment in Education, Made at Egmore, Near Madras*](https://archive.org/details/ananalysisexper00bellgoog/page/n4/mode/2up)
[^b17]: [Google Books - Joseph Lancaster : *Improvement in education*](https://books.google.fr/books?id=_jkIAAAAQAAJ&printsec=frontcover&hl=fr&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false)
[^b18]: [Wikimédia - Charles Démia : *Reglemens pour les écoles de la ville & Diocèse de Lyon*](https://upload.wikimedia.org/wikipedia/commons/0/07/D%C3%A9mia_-_Reglemens_pour_les_ecoles_De_la_Ville_%26_Diocese_de_Lyon._-_Suivi_des_Remonstrances_%C3%A0_MM._du_clerg%C3%A9_-_Avis_important_touchant_l%27%C3%A9tablissement_d%27une_esp%C3%A8ce_de_s%C3%A9minaire.pdf)
[^b19]: [BNF Gallica - Diderot & Alembert : *Encyclopédie ou Dictionnaire raisonné des sciences* (définition de système)](https://gallica.bnf.fr/ark:/12148/bpt6k505471/f682.item)
[^b20]: [BNF Gallica - Etienne Bonnot de Condillac : *Traité des Systèmes*](https://gallica.bnf.fr/ark:/12148/bpt6k1517703g)
[^b21]: [BNF Gallica - Etienne Bonnot de Condillac : *La Logique*](https://gallica.bnf.fr/ark:/12148/bd6t5381259j/f5.item)
[^b22]: [Funambule - Friedrich Hegel : *Phénoménologie de l'esprit* Tome 1](https://funambule.org/lectures/philo/HEGEL%20-%20La%20phenomenologie%20de%20l'esprit%20(T1).pdf)
[^b23]: [Funambule - Friedrich Hegel : *Phénoménologie de l'esprit* Tome 2](https://funambule.org/lectures/philo/HEGEL%20-%20La%20phenomenologie%20de%20l'esprit%20(T2).pdf)
[^b24]: [BNF Gallica : Jean Baptiste Lamarck - *Philosophie Zoologique*](https://gallica.bnf.fr/ark:/12148/bpt6k5675762f)
[^b25]:[BNF Gallica : Charles Darwin - *L'origine des espèces*](https://gallica.bnf.fr/ark:/12148/bpt6k77233m/f25.item)
[^b26]:[Internet Archive : John Dewey - *School and Society*](https://archive.org/details/schoolsociety00deweiala/page/n8/mode/1up)
[^b27]:[MIT : Charles S. Peirce - *How To Make Ideas Clear*](https://courses.media.mit.edu/2004spring/mas966/Peirce%201878%20Make%20Ideas%20Clear.pdf)
[^b28]:[Google Books : Gottlob Frege - *Idéographie*](https://books.google.fr/books?id=krHw5MsbL6sC&printsec=frontcover&hl=fr&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false)
[^b29]:[Internet Archive : Alfred North Whitehead - *Principa Mathematica* Vol 1](https://archive.org/details/dli.ernet.247278/page/n3/mode/2up)
[^b30]:[Internet Archive : Alfred North Whitehead - *Principa Mathematica* Vol 2](https://ia800307.us.archive.org/18/items/PrincipiaMathematicaVol2/AlfredNorthWhiteheadBertrandRussell-PrincipiaMathematicaVol2.pdf)
[^b31]: [Internet Archive : Alfred North Whitehead - *Principa Mathematica* Vol 3](https://archive.org/details/cu31924001575244/page/n7/mode/2up)
[^b32]: [BNF Gallica : Académie des sciences / Emile Borel - *La théorie du jeu et les équations intégrales à noyau symétrique*](https://gallica.bnf.fr/ark:/12148/bpt6k31267.image.r=Comptes+rendus+hebdomadaires+des+s%C3%A9ances+de+l.f1304.pagination.langFR)
[^b33]: [BNF Gallica : Augustin Cournot - *Recherches sur les principes mathématiques de la théorie des richesses*](https://gallica.bnf.fr/ark:/12148/bpt6k6117257c.r=Recherches%20sur%20les%20principes%20math%C3%A9matiques%20de%20la%20th%C3%A9orie%20des%20richesses?rk=21459;2)
[^b34]: [W3C : Vannevar Bush - *As we may think*](https://www.w3.org/History/1945/vbush/vbush.txt)
[^b35]: [BNF Gallica : Leibniz - *Monadologie*](https://gallica.bnf.fr/ark:/12148/bpt6k5551698p)
[^b36]: [BNF Gallica : Aristote - *L'Éthique à Nicomaque* Livre III, Chap. 2, fragment 1111a 2-20](https://remacle.org/bloodwolf/philosophes/Aristote/nicom2.htm#II)
[^b37]: [BNF Gallica : Adam Smith - *Recherches sur la nature et les causes de la richesse des nations*](https://gallica.bnf.fr/services/engine/search/sru?operation=searchRetrieve&version=1.2&collapsing=disabled&query=%28dc.creator%20adj%20%22Smith%20%20Adam%22%20or%20dc.contributor%20adj%20%22Smith%20%20Adam%22%29%20and%20dc.relation%20all%20%22cb31377297x%22%20sortby%20dc.title%2Fsort.ascending&rk=64378;0)





##### Brevets

[^p1]: https://patents.google.com/patent/US359748
[^p2]: https://patents.google.com/patent/US174465A/en?inventor=Alexander+Graham+Bell&sort=old - https://patents.google.com/patent/US178399A/en?inventor=Alexander+Graham+Bell&sort=old
[^p3]: https://web.archive.org/web/20090116093441/http://www.radar-france.fr/brevet%20radar1934.htm
[^p4]: https://worldwide.espacenet.com/patent/search/family/001739501/publication/GB593017A?q=pn%3DGB593017
[^p5]: https://worldwide.espacenet.com/patent/search/family/009975642/publication/?q=pn%3DGB269729A
[^p6]: https://patents.google.com/patent/US1563731A/en?inventor=Ducas+Charles | https://worldwide.espacenet.com/patent/search?q=pn%3DUS1563731A
[^p7]:  https://worldwide.espacenet.com/patent/search/family/009975642/publication/GB269729A?q=pn%3DGB269729A
[^p8]: https://worldwide.espacenet.com/patent/search/family/032233881/publication/GB639178A?q=pn%3DGB639178





##### Vidéos

[^v1]: https://www.youtube.com/watch?v=-BP7DhHTU-I
[^v2]: https://www.youtube.com/watch?v=7lVAFcDX4eM
[^v3]: https://youtube.com/watch?v=zXPiqk0-zDY 
[^v4]: https://www.youtube.com/watch?v=MOUg25dJM4c
[^v5]:  https://www.youtube.com/watch?v=RVB3PBPxMWg



##### Jeu

[^g1]: https://store.steampowered.com/app/1444480/Turing_Complete/



##### Web

[^w1]: [CNRS : Apprentissage par récompense ou par punition : quelles différences ?](https://www.inshs.cnrs.fr/fr/cnrsinfo/apprentissage-par-recompense-ou-par-punition-quelles-differences)
[^w2]: https://www.frcneurodon.org/comprendre-le-cerveau/a-la-decouverte-du-cerveau/la-conscience
[^w3]: https://www.codingame.com/work/fr/codingame-coderpad-tech-hiring-survey-2022/
[^w4]: https://www.technologyreview.com/2023/02/14/1067869/rust-worlds-fastest-growing-programming-language/
[^w5]: https://www.legifrance.gouv.fr/codes/id/LEGISCTA000006149839/
[^w6]: http://wiki.c2.com/



##### Livres

- Lean Startup - Eric Ries
- la 4e édition de "Computer, A History of the Information Machine" de Martin Campbell-Kelly, professeur émérite britannique, spécialisé dans l'histoire de l'informatique. Coécrite avec William F.Aspray, Jeffrey R. Yost, Honghong Tinn, et Gerardo Con Diaz.
- "The history of the computer : people, inventions, and technology that changed our world" de Rachel Ignotofsky
- "Histoire illustrée de l'informatique" d'Emmanuel Lazard et Pierre Mounier-Kuhn.
- "Transmettre" de Christophe André, Céline Alvarez, Catherine Gueguen, Matthieu Ricard, Frédéric Lenoir, Ilios Kotsou, Caroline Lesire
- Clean Code & Clean Architecture - Robert Cecil Martin



#### 1.13.0.2. Webographie

https://www.victorian-cinema.net/machines

http://promenadesmaths.free.fr/histoire_arithmetique.htm

https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/25874/Parent_Simon_2021_these.pdf?sequence=2&isAllowed=y

https://theses.hal.science/tel-00125472/document

http://serge.mehl.free.fr/

https://monoskop.org/images/b/b0/Floridi_Luciano_Philosophy_and_Computing_An_Introduction_1999.pdf

https://www.amazon.fr/Computer-History-Information-Machine-Technology-ebook/dp/B07CNDC344/ref=sr_1_1?__mk_fr_FR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2MCJSC0Q0UNWO&keywords=Computer%3A+A+History+of+the+Information+Machine&qid=1683623797&sprefix=computer+a+history+of+the+information+machine%2Caps%2C74&sr=8-1&asin=0813345901&revisionId=&format=4&depth=2

https://www.physique.usherbrooke.ca/~afaribau/essai/#:~:text=Les%20tables%20de%20calcul%20furent,aux%20cailloux%20selon%20leur%20position

https://www.enfant-encyclopedie.com/pdf/synthese/apprentissage-par-le-jeu

http://remacle.org/bloodwolf/erudits/Vitruve/livre1.htm

**https://dl.acm.org/doi/10.1145/12178.12180**



https://aosabook.org

http://waterbearlang.com



https://fr.mathigon.org/timeline

https://passerelles.essentiels.bnf.fr/fr/chronologie/antiquite



##### Wikipédia

https://fr.wikipedia.org/wiki/Th%C3%A9orie_g%C3%A9n%C3%A9rale_des_syst%C3%A8me

https://en.wikipedia.org/wiki/Timeline_of_computing

https://en.wikipedia.org/wiki/History_of_the_graphical_user_interface

https://fr.wikipedia.org/wiki/Histoire_de_la_cryptologie

https://fr.wikipedia.org/wiki/Analogies_et_correspondances

https://fr.wikipedia.org/wiki/Philosophie_de_l%27information

https://fr.wikipedia.org/wiki/%C3%89pist%C3%A9mologie

https://fr.wikipedia.org/wiki/Th%C3%A9orie_de_la_connaissance

https://fr.wiktionary.org/wiki/intelligence#:~:text=(%20XII%20e%20si%C3%A8cle)%20Emprunt%C3%A9%20au,%2C%20choisir%2C%20lire%20%C2%BB).

https://fr.wikipedia.org/wiki/Intelligence

https://fr.wikipedia.org/wiki/Cellule_gliale

https://fr.wikipedia.org/wiki/My%C3%A9line

https://en.wikipedia.org/wiki/Mental_chronometry

https://fr.wikipedia.org/wiki/Utilisabilit%C3%A9

https://en.wikipedia.org/wiki/High_availability

https://fr.wikipedia.org/wiki/Auto-organisation

https://fr.wikipedia.org/wiki/Division_du_travail

https://fr.wiktionary.org/wiki/intelligence#:~:text=(%20XII%20e%20si%C3%A8cle)%20Emprunt%C3%A9%20au,%2C%20choisir%2C%20lire%20%C2%BB).

https://fr.wikipedia.org/wiki/Intelligence

https://fr.wikipedia.org/wiki/Cellule_gliale

https://fr.wikipedia.org/wiki/My%C3%A9line

https://en.wikipedia.org/wiki/Mental_chronometry



https://onlinelibrary.wiley.com/doi/abs/10.1002/cne.21974





##### Vidéos Youtube

https://www.youtube.com/watch?v=NH2sMPERT2g

https://www.youtube.com/watch?v=AwCq4PwCnQE

https://www.youtube.com/watch?v=NH2sMPERT2g

https://www.youtube.com/watch?v=8KHuSw0W6OA

https://www.youtube.com/watch?v=FlfChYGv3Z4

https://www.youtube.com/watch?v=eMy4vSZ-J_I

https://www.youtube.com/watch?v=MQzpLLhN0fY

https://www.youtube.com/watch?v=YBnBAzrWeF0

https://www.youtube.com/watch?v=2dKG21u2aSo

https://www.youtube.com/watch?v=Yc945sNB0uA

https://www.youtube.com/watch?v=YyxGIbtMS9E

https://www.youtube.com/watch?v=9EjZVEGlk_I

https://www.youtube.com/watch?v=6TRfy70DqD8

https://www.youtube.com/watch?v=h9H6WkUeuUY

https://www.youtube.com/watch?v=eIpoA7Ir9p8

https://www.youtube.com/watch?v=7XTHdcmjenI

https://www.youtube.com/watch?v=Ag1AKIl_2GM

https://www.youtube.com/watch?v=avTMg2THEvM

https://www.youtube.com/watch?v=yp_UUPR6gfg

https://www.youtube.com/watch?v=xqqzMjfFa10

https://www.youtube.com/watch?v=iE08wLRGPcQ





https://www.amazon.fr/Building-Blocks-Teaching-Preschoolers-Special/dp/1557669678



#### 1.13.0.3. Lexique

Je définit les mots que j'utilise dans le développement même du mémoire.



#### 1.13.0.4. Table des illustrations

http://toastytech.com/guis



#### 1.13.0.5. Page d’évaluation 
