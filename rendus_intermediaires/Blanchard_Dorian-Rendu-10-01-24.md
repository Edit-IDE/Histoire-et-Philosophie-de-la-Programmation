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
      - [1.7.8.2. IBM 602 \& 603](#1782-ibm-602--603)
      - [1.7.8.3. Trackball](#1783-trackball)
      - [1.7.8.4. Norbert Wiener](#1784-norbert-wiener)
      - [1.7.8.5. SSEM](#1785-ssem)
      - [1.7.8.6. Manchester Mark I](#1786-manchester-mark-i)
      - [1.7.8.7. Théorie de l'information](#1787-théorie-de-linformation)
      - [1.7.8.8. IBM 604](#1788-ibm-604)
      - [1.7.8.9. IBM 407](#1789-ibm-407)
      - [1.7.8.10. Origines de l'Assembleur](#17810-origines-de-lassembleur)
      - [1.7.8.11. IBM CPC](#17811-ibm-cpc)
      - [1.7.8.12. Ferranti Mark I](#17812-ferranti-mark-i)
      - [1.7.8.13. Compilateurs et premiers languages de haut niveau](#17813-compilateurs-et-premiers-languages-de-haut-niveau)
      - [1.7.8.14. Leo I](#17814-leo-i)
      - [1.7.8.15. Premiers langages de haut niveau opérationnels](#17815-premiers-langages-de-haut-niveau-opérationnels)
        - [1.7.8.15.1. Lisp](#178151-lisp)
      - [1.7.8.16. IBM 1401](#17816-ibm-1401)
      - [1.7.8.17. Théorie algorithmique de l'information](#17817-théorie-algorithmique-de-linformation)
      - [1.7.8.18. Computionnalisme](#17818-computionnalisme)
      - [1.7.8.19. Souris](#17819-souris)
      - [1.7.8.20. Luciano Floridi](#17820-luciano-floridi)
      - [1.7.8.21. IBM System 360](#17821-ibm-system-360)
      - [1.7.8.22. Premières applications de l'IA](#17822-premières-applications-de-lia)
      - [1.7.8.23. Microprocesseur](#17823-microprocesseur)
      - [1.7.8.24. Course à l'espace](#17824-course-à-lespace)
      - [1.7.8.25. John Horton Conway](#17825-john-horton-conway)
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
    - [1.10.9. FOUTOIR](#1109-foutoir)
      - [1.10.9.1. 12 24 36 48 361248 2520=9x8x7x5](#11091-12-24-36-48-361248-25209x8x7x5)
      - [1.10.9.2. Philosophie](#11092-philosophie)
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

Etymologie et définition, Zénon d'Élée, -490**. Thèse, une antithèse, et une synthèse.



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

Etymologie, Réécriture syntaxique abrégée et langage SMS. Diogène Laërce, **405 avant J.-C**. Xénophon.

[^1]: https://gallica.bnf.fr/ark:/12148/btv1b84470700/f95.item.zoom



##### 1.7.2.5.13. Géométrie Euclidienne

Euclide, *Éléments[^1]*. Géométrie, arithmétique, PGCD, division.

[^1]: https://gallica.bnf.fr/ark:/12148/bpt6k68013g/f3.item



##### 1.7.2.5.14. Aristote

**-384** Lycée. Syllogismes. Biologie. Âme, terre ronde et confiance sensation. Vertu ethique, doxographie, métacognition.



##### 1.7.2.5.15. Stoïcisme

Zénon de Kition, **-301**, *mal*/*bien*/*indifférence*. Désirs, craintes et représentations. Apathie et Ataraxie. Tempérance et la prudence. Rationnel : raison et non envie. *Panthéisme*.

https://www.youtube.com/watch?v=iE08wLRGPcQ



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

Compilateur du **1er siècle avant J.-C.** Architecture, Alexandrie, Dinocrate [^1] . Liens avec Archimède et mécanique et fluides. Aqueducs.

Les six principes théoriques de l'architecture.

[^1]: https://www.ancientportsantiques.com/wp-content/uploads/Documents/AUTHORS/Vitruve-Maufras%20-%20Edit%20Panckoucke%201848-Livres%20I%C3%A0V.pdf


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

Isaac Newton, lois de la gravitations universelle. Mécanique classique, décomposition de la lumière [^1][^2]. 

1757 calculateurs français, Alexis Clairaut, Jérôme Lalande, et Nicole Lepaute. Edmond Halley, et sa comète. Révolution de 76 ans

[^1]: https://archive.org/details/newtonspmathema00newtrich/page/n7/mode/2up
[^2]: https://archive.org/details/optickstreatise00newta/page/n9/mode/2up



#### 1.7.4.2. Philosophes modernes

François Rabelais moine apostat, médecin, et écrivain. Gigantisme, Pantagruel, Gargantua, en **1532** et **1534**

Montaigne.

Francis Bacon, droit et politique, empiriste. *Novum organum*[^1] **1620**

Préjugés, illusions, sophismes, biais, 4 idoles.

[^1]: https://archive.org/details/1762novumorganum00baco/page/n3/mode/2up

Thomas Hobbes, *Léviathan* en **1651**,  référence biblique. Matérialiste et rationaliste. Critique des États, de la souveraineté et des religions (scolastique). Humain naturellement mauvais et violent, rapport à l'autorité. "société athée ou a-religieuse constitue la solution au problème social ou politique".

René Descartes 1596, fondateur géométrie analytique et mécanisme, causalité et fonctionnalisme. Dualité entre l'âme est le corps. Scepticisme, et doute cartésien, épochè. Méfiance envers les sensations trompeuses, illusions d'optiques. "cogito ergo sum".

Baruch Spinoza 1632, herem, taille de lentilles optiques. Panthéisme stoïcien. Niveau de connaissances : ouï-dire, connaissance empirique, déduction, et connaissance première.

**1712** Jean-Jacques Rousseau, philosophe autodidacte, *Discours sur l'origine et les fondements de l'inégalité parmi les hommes*[^1] **1755**, l'humain est naturellement bon. Volonté générale, *Du contrat social* **1762**. *Emile* ou *De l'éducation*, pédagogie moderne.

[^1]: http://classiques.uqac.ca/classiques/Rousseau_jj/discours_origine_inegalite/discours_inegalite.pdf

1724, Kant, fondateur du criticisme et de l'idéalisme transcendantal. Descartes dans le "Traité de l'homme" de 1664.



#### 1.7.4.3. Journalisme

Antiquité, pratique orale, par crieurs, messagers ou troubadours, sur la place publique. Empire Romain *Acta Diurna*. **1622**  *Weekly News* de Nathaniel Butter. Théophraste Renaudot, *Gazette* 1631.

Liberté de la presse contre la censure royale. Droits de l'Homme et du citoyen de 1789. *L'Agence des feuilles politiques, correspondance générale* 1835, Charles-Louis Havas.

Vérification des faits, protection des sources. Benjamin Franklin ?



#### 1.7.4.4. Binaire

-750 les hexagrammes chinois. **-200**, Pingala *Chandahsastra*. Juan Lobkowitz, 1606, fondateur de la mathématique binaire.

**1690** Leibniz Wilhelm Gottfried. Cylindre cannelé et *characteristica universalis*. 



#### 1.7.4.5. Encryptions moderne

Giambattista della Porta cryptographe, **1563** *De furtivis literarum notis, vulgo de ziferis*."[^1] système littéral à double clef.

[ ^1]: https://books.google.fr/books?id=DcI9AAAAcAAJ&pg=GBS.PT3&printsec=frontcover&redir_esc=y#v=onepage&q&f=false

**1523** Blaise de Vigenère et son code (Giovan Battista Bellaso). *Traité des chiffres* **1586**, Table de chiffrement et déchiffrement cassé par Friedrich Kasiski en 1863.



#### 1.7.4.6. Premières machines à calculer

"computer" Richard Brathwaite *The Yong Mans Gleanings* **1613**,

**1617** John Napier, Bâtons de Napier. Logarithme népérien.

Wilhelm Schickard, une horloge à calculer.

**1621** William Oughtred, notation de π et "x" pour la multiplication. Règle coulissante.

En **1650**, le clermontois polymathe Blaise Pascal, invente la Pascaline. Traité de géométrie projective. Première machine à calculer.

Cartes perforées, orgue de Barbarie. **1725**, Basile Bouchon. 1728, Jean-Baptiste Falcon. Jacques de Vaucanson, célèbre Grenoblois inventeur d'automates musicaux et à objectif de divertir, réutilise ce concept en remplaçant ruban et cartes perforées par un cylindre métallique à pointes. Joseph Marie Jacquard, métier à tisser éponyme en **1801**.



#### 1.7.4.7. Pédagogie moderne

**1746**, Johann Heinrich Pestalozzi, *Leonard et Gertrude* en **1781**. *Comment Gertrude instruit ses enfants* en **1801**. Éducation bienveillante et mutuelle. Du concret à l'abstrait.

Grégoire Girard, écoles mutuelles 1816.

Andrew Bell l'enseignement mutuel, *Expériences sur l'éducation faire à l'école des garçons de Madras* en **1789**.

Joseph Lancaster, *Improvement in Education* en 1803.

Charles Démia, *Règlements pour les écoles de la ville et diocèse de Lyon* en 1674.



#### 1.7.4.8. Théorie générale des systèmes

De 1751 à 1772, Diderot et Alembert, l'*Encyclopédie* ou le *Dictionnaire raisonné des sciences des arts et des métiers*.  Sébastien Le Prestre, aka marquis de Vauban. Système art militaire, arrangement toutes les parties [^1].

Étienne Bonnot de Condillac, système en science politique *Traité des Systèmes* en **1749**.

Vilfredo Pareto qui l'appliqua à l'économie politique au début du 20ème siècle.

https://gallica.bnf.fr/ark:/12148/bpt6k505471/f682.item







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

Georg Wilhelm Friedrich Hegel, 1770, idéaliste. "*Phénoménologie de L'Esprit*", dialectique du maître et de l'esclave. Travail facteur d'émancipation et de libération.

Jean-Baptiste de Lamarck, biologie. Théorie transformiste et fixisme. *Philosophie zoologique*[^1], théorie de l'évolution, l'homme descends du singe.

Charles Darwin, l'*Origine des espèces* en 1859. Sélection naturelle, preuve scientifique.

Herbert Spencer sciences humaines, darwinisme social.

[^1]: https://gallica.bnf.fr/ark:/12148/bpt6k5675762f

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

John Dewey, **1899** *The School and Society*[^1].

[^1]: https://archive.org/details/schoolsociety00deweiala/page/n8/mode/1up

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

Nikola Tesla, moteur asynchrone, alimentation polyphasée[^1], réseau de distribution d’électricité alternative. Très haute fréquence et technologie sans fil, l'imagerie radio (Wilhelm Röntgen). Automates radio-contrôlés. Lucien Gaulard, transformateur.

[^1]: https://patents.google.com/patent/US359748

Albert Einstein, relativité générale.



##### 1.7.5.6.1. Communications à distances

Feux placés en hauteur sur des montagnes ou des tours, signaux de fumée.

1794, Claude Chappe tours et sémaphores, victime de piratage. 

1837 télégraphe électrique commercial de Cooke et Wheatstone

Samuel Morse en 1840.

Robert Hooke, téléphone à ficelle en 1665.

Antonio Meucci, 1850 *Telettrofono*

Alexander Graham Bell, brevet téléphone[^1]. 

Elisha Gray, télégraphe musical, ancêtre du synthétiseur.

[ ^1]: https://patents.google.com/patent/US174465A/en?inventor=Alexander+Graham+Bell&sort=old - https://patents.google.com/patent/US178399A/en?inventor=Alexander+Graham+Bell&sort=old



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

https://www.victorian-cinema.net/machines

**1893**, André Blondel, oscillographe bifilaire.



#### 1.7.5.7. Logique

Bolzano "*Théorie de la science*", notion d'objet

Charles Sanders Peirce, philosophie pragmatique et scientifique, notation flèche de Peirce, porte NOR.

https://courses.media.mit.edu/2004spring/mas966/Peirce%201878%20Make%20Ideas%20Clear.pdf

Principe de Hume ---> Gottlob Frege, notation logique *Idéographie* (*Begriffsschrift*). Mouvement de la philosophie analytique dans le but de clarifier les pensée.

Russel *Principia Mathematica* 

Alfred North Whitehead, philosophie des processsus. Ernst Schröder

**1847** George Boole, tables de vérité, algèbre booleen et portes logiques.



#### 1.7.5.8. Genèse de la programmation

https://www.youtube.com/watch?v=RQYuyHNLPTQ

1725, Basile Bouchon, métier à tisser semi-automatique, ruban de papiers perforé. 1728, Jean-Baptiste Falcon cartes perforées en carton reliées entre elles pour améliorer la robustesse de cette machine. De 1745 à 1755, le mécanicien Jacques Vaucanson automatise la machine à l'aide de système hydrauliques dont il dote ses automates. A la même période apparaissent les machines à coudre. Enfin, en 1800, Joseph Marie Jacquard invente le métier à tisser Jacquard, complétement automatisé. Cette machine inspirera Charles Babbage, la première personne à avoir automatiser l'édition de tables de calcul. Il a initialement travaillé avec des calculateurs humains, "computers" en anglais, sa langue natale. La conception de telles tables étaient fastidieuses à superviser et encore plus à calculer et réaliser. Il a œuvré à développer une machine basée sur les méthodes de calcul de l'époque, réalisées par des gens qui étaient coiffeurs, ayant perdu leur travail suite à la révolution française, période après laquelle la coiffure étant vue comme symbole de l'aristocratie, a été délaissée. Ils effectuaient essentiellement des additions et des soustraction, sous la supervision de mathématiciens qui leurs prépareraient les formules d'après la méthode des différences finies. D'où le nom de la machine qu'il a inventé en **1834**, "la machine à différences". Ayant l'expérience du milieu, il voulait réaliser un système fiable, résilient a l'erreur. Cette dernière pouvait provenir du calcul, mais arrivant le plus souvent lors de l'impression, il à donc fait en sorte, dès la phase de design, que sa machine prépare directement le texte en résultant pour l'impression. C'est une approche très intéressante réduisant les intermédiaires et automatisant toute la chaine de création, que je reprendrais plus tard. La machine est à ce moment déjà un outil qui peut guider et réduire les erreurs, ce qui à l'époque était crucial, notamment en mer où une erreur de calcul ou d'impression sur l'almanach du navigateur pouvait mener à la perte de tout un navire et de son équipage. De 1820 à 1830 il a visité beaucoup d'usines en Europe dans le but de trouver des idées pour sa machine à différences, il n'en trouva pas beaucoup mais cela lui a permis de devenir un économiste des machines industrielles à son époque. À peine eu t'il conçu la machine à différence, qu'il eu oublié la finalité de base : réaliser des tables de calcul, et il embrassa alors l'idée d'une machine capable de calculer tout ce qu'un humain pourrait lui demander, la Machine Analytique. De son vivant, seul le concept existait, elle ne vu le jour que grâce à son fils, qui après une tentative infructueuse en 1888, revint à la charge et réalisa en 1906 une machine fonctionnelle qu'il eu présenté devant l'académie royale anglaise d'astronomie, après quoi il en fit don au musée des sciences de Londres en 1910.

Pour en revenir à l'industrie du textile, c'est à la même période apparaissent les machines à coudre. Il est avéré que les humains savent coudre depuis la préhistoire, en 2016 des russes ont retrouver une aiguille qui aurait 50000 ans. Quelques années avant le début de la période contemporaine, Charles Fredrick Wiesenthal dépose le premier brevet de machine à coudre en 1755. Au début des années 1800, Josef Madersperger commence à développer une machine à coudre qui présentera pour la première fois en 1814. C'est en 1830 que Barthélemy Thimonnier dépose un brevet pour la première machine à coudre fiable. La même année, il décroche un contrat pour la réalisation d'uniformes de l'armée Française avant que toutes ses machines soit détruites par des ouvriers craignant de perdre leurs emplois. En 1846, c'est Elias Howe qui dépose un brevet pour la première machine à coudre capable de faire des points noués, améliorée par Allen B. Wilson seulement 3 ans après. Cette machine sera améliorée par bien d'autres personnes, et popularisée par Isaac Merritt Singer, créateur de la marque de machine à coudre Singer encore existante, qui a racheter toute sortes de brevet et optimiser la processus de création pour réduire les coûts et rendre le produit accessible aux particuliers.

Le métier Jacquard et les travaux de Charles Babbage sont donc à l'origine de la programmation. Un programme est une prévision écrite, c'est ce qui permet de répondre a la question "Quoi faire quand ?". Le tout premier programme informatique à été imaginé pour cette fameuse Machine Analytique par Ada Lovelace en **1842**, à 27 ans. 10 ans auparavant, elle rencontre Charles Babbage, avec qui elle travailla, notamment sur la machine analytique, pour laquelle elle conçu ce dit programme. Héritant de toutes les technologies et concepts énoncés précédemment dans cette section, Hermann Hollerith invente la mécanographie. Cet ingénieur américain a été recruté en tant que statisticien au Bureau de recensement des États Unis. Dans la fin du 18è siècle, en 1790, le premier recensement estimait la population des États-Unis à 3.9 millions d'individus. En 1840, 28 greffiers ont travaillés à la réalisation d'une estimation de 17.1 millions. Enfin, le recensement de 1880 a nécessité 1495 greffiers qui devait scrupuleusement pointer avec une couleur d'encre particulière pour chaque statistique effectuée. Avec la méthode automatisée par cartes perforées d'Hermann Hollerith dévoilée l'an **1890**, la création d'un tableau statistique à été accélérée de 10 fois par rapport à ses concurrents, remplaçant bon nombre de greffiers. Il a construit une machine à statistiques à cartes perforées qui exploite des cartes 12x6cm regroupant les 210 cases nécessaires pour recevoir toutes les informations nécessaires. Son invention a permis d'effectuer le recensement auparavant manuel en seulement six ans. Par la suite,  sur une idée de l'un de ses collègues, il a amélioré le fonctionnement de cette machine en utilisant un métier à tisser Jacquard pour mécaniser la lecture des fiches de recensement et améliorer son efficacité. Enfin, il finit par quitter l'administration et fonde la Tabulating Machine Company en 1896 qui fusionnera en 1911 avec 3 autres entreprise pour fonder la Computing-Tabulating-Recording Company (CTR), qui deviendra en 1924 l'International Business Machines Corporation, IBM. 





[Retour](#Sommaire)

### 1.7.6. Première guerre mondiale et entre deux guerres

En 9 décembre **1905**, l'abrogation du régime concordataire de 1802 sépare l'État et l'Église, mettant fin à l'affrontement violent qui a opposé deux conceptions de la place des Églises dans la société française pendant environ vingt-cinq ans.

C'est la première guerre à impliquer simultanément tout les pays, les machines de bureau deviennent électromécaniques, l'humain peut désormais rapidement transmettre des messages sur de longues distances à ses congénères à l'aide des télégraphes. L'informatique naissante cherchera à vendre des machine mécanographiques dans le monde entier, elles serviront les gouvernement les plus puissant et également les pires de l'époque, Thomas Watson, après avoir travaillé à la récente et bien portante Nationnal Cash Register company (NCR), est embauché en 1914 pour diriger la regroupement d'entreprise de la CTR, c'est lui qui fonda IBM après la guerre en 1924.



#### 1.7.6.1. Théorie des jeux

La théorie des jeux, comme son nom l'indique, étudie les jeux et plus notamment le comportement des joueurs et leurs décisions. Elle se base sur l'hypothèse qu'ils effectuent toujours un choix rationnel en fonction des connaissances à leur disposition, et ce dans le but de maximiser leurs gains et à minimiser leurs pertes. La plus ancienne démonstration de la sorte que je connaisse est le Pari de Blaise Pascal, déclarant que si Dieu n'existe pas, alors y croire ou pas n'as pas d'importance, mais dans l'hypothèse où il existe, alors il vaut mieux y croire pour ne pas finir en enfer. Le choix rationnel permettant les gains potentiels maximum serait ainsi de croire en Dieu.

Ernst Zermelo, un assistant de Max Planck, a jeté les bases de la formalisation mathématique des jeux à somme nulle avec un article "*Sur une application de la théorie des ensembles à la théorie du jeu d'échecs*" publié en 1913. Emile Borel pionnier de la théorie des mesure, des probabilités, et des jeux, publiera un article sur ce dernier domaine dans les *Comptes rendus hebdomadaires des séances de l'Académie des sciences* du 1er juillet 1921[^1]. Puis en 1940 il publia également un guide de "*Théorie mathématique du bridge à la portée de tous*" coécrit avec l'aide d'André Chéron.

[^1]: https://gallica.bnf.fr/ark:/12148/bpt6k31267.image.r=Comptes+rendus+hebdomadaires+des+s%C3%A9ances+de+l.f1304.pagination.langFR

Ces théories seront également appliqués au jeux économiques, Antoine Augustin Cournot fut pionnier en 1838 dans ses "*Recherches sur les principes mathématiques de la théorie des richesses*" dans lesquelles il analysa un duopole et vint a être l'un des premier à déclarer qu'il existe un équilibre entre l'offre et la demande. Il faudra attendre 1944 pour qu'Oskar Morgenstern et John von Neumann formalisent ce domaine de recherche dans leur ouvrage "*Théorie des jeux et du comportement économique*". Enfin, John Forbes Nash, aboutira les travaux de Cournot et inventera lui aussi un équilibre a son nom, le fameux équilibre de Nash.



#### 1.7.6.2. Améliorations du stockage

Lors de l'Exposition universelle de Paris qui a eu lieu en 1900, Valdemar Poulsen présente son invention d'un système d'enregistrement magnétique sur fil nommé télégraphone. Inspiré par ces travaux Fritz Pfleumer invente la bande magnétique en 1928 dans le but d'enregistrer du son comme ça sera le cas la même année avec le magnétophone de Karl Stille lui même inspiré du télégraphone. Quelques années après sera perfectionné la bande magnétique en acier, et une dizaine années plus tard, vers 1940, naitra la première bande magnétique en [matière plastique](https://fr.wikipedia.org/wiki/Matière_plastique).

En **1932**, l'ingénieur Gustav Tauschek, invente une nouvelle méthode de mémoire vive magnétique possèdent un temps de lecture de seulement quelques millisecondes contre plusieures centaines auparavant. La mémoire tambour sera réutilisé dans le Manchester Mark I, l'ENIAC, l'IBM 650, l'IBM 701, et l'UNIVAC 1103 (version scientifique)



#### 1.7.6.3. Tabulatrices

Dans un atelier de mécanographie, de multiples stations d'outils étaient présentes, parmi ces outils, les perforatrices chargées de créer et vérifier les données en perforant des cartes, les trieuses responsables de créer les différents lots de cartes, les interclasseurs capables de réunir deux lots de cartes avec des informations différentes en une seule grâce à une colonne de donnée commune aux deux, et les reproductrices permettant de copier des cartes perforées en une seule perforation. Jusque là, ces premier outils mécanographique étaient appelés machines à statistiques. Les opérateurs devaient à chaque fois reprogrammer la tabulatrice à l'aide du tableau de connexion représentant le programme à l'aide de câbles permettant d'envoyer les données d'entrés dans les différents modules de calcul, puis de l'exécuter et enfin récupérer le résultat affiché sur des roues totalisatrices gravées pour enfin le recopier à la main et produire de nouveaux programmes en cartes perforés à partir de ces résultats. En 1920, Hollerith présente la première machine avec module d'impression et tableaux de connexion amovibles interchangeable permettant de rapidement changer le programme d'une machine, qui sera désormais appelée tabulatrice. 11 ans plus tard, en 1931, IBM sort le modèle 601, ce calculateur électromécanique est la première machine d'IBM capable de multiplier deux nombre provenant de cartes en entrée et de perforer la valeur en résultant. Elle est d'ailleurs surnommée ma Multiplying Punch.

Les téléscripteurs auparavant utilisés par les opérateurs télégraphiques avant d'être rendus obsolètes par le téléphone seront réutilisés pour encoder des caractères qui seront convertis en binaire dans le bit de travailler et perforer des cartes à distance. En 1935 né le réseau Telegraph Exchange ou TELEX



#### 1.7.6.4. Détections par ondes

Le radar est un outil de détection et estimation de la distance utilisant les ondes radio (RAdio Detection And Ranging). Sa création découle des travaux de James Clerk Maxwell et Heinrich Rudolf Hertz utilisés par Albert Hull, l'inventeur du magnétron, machine capable de convertir l'énergie cinétique des électrons en ondes électromagnétiques à l'aide de tubes à vide. En **1934**, la Compagnie générale de télégraphie Sans Fil française (CSF) étudie le magnétron et développe les premiers radars décimétriques[^1].

[^1]: https://web.archive.org/web/20090116093441/http://www.radar-france.fr/brevet%20radar1934.htm

Dans le début des années 1900 le sonar à déjà été bien étudié et mis en application, et pour cause, il utilise le son audible par l'oreille humaine, comme onde permettant le calcul de distances. Rudolf Kühnhold était spécialiste du domaine mais décida en 1931 de se consacrer aux ondes électromagnétiques, la même année que le dépôt de brevet de la CSF il abouti simultanément à cette dernière, la création d'un système de télémètre radio.

C'est année suivante, en 1935 que Robert Watson-Watt, que l'on retiendra comme l'inventeur officiel du radar, dépose un brevet [^1] avec des indications pour l'améliorer. Prouvant efficacité de son système en détectant des avions a 27km puis l'améliorant jusqu'à 100km, il met fin aux développement concurrents comme le sonar, et commence la mise en place d'un réseau de radar côtier nommé Chain Home. En 1937 les premières stations étaient opérationnelles et elle jouerons un rôle crucial en 1940 lors de la bataille d'Angleterre, durant laquelle ils ont même monter des radars sur des engins volants dans le but de détecter les bombardiers.

[^1]: https://worldwide.espacenet.com/patent/search/family/001739501/publication/GB593017A?q=pn%3DGB593017





#### 1.7.6.5. Alan Turing 

En **1936** il invente une expérience de pensée présentant une machine nommée d'après son nom. Cette machine de Turing est à la base de l'informatique théorique, c'est une métaphore du fonctionnement de tout appareil de calcul, elle à poser les bases de la complexité algorithmique et de la calculabilité. Imaginez un **ruban infini** composé de cases numérotées, toutes ces cases possèdent initialement un zéro. Sur ce ruban est situé un **agent** capable de lire et écrire les symboles sur le ruban, ainsi que de se déplacer sur la case précédente ou suivante. Un **registre** viendra mémoriser la suite d'états allant de celui initial, jusqu'à actuel, le nombre d'état est limité et fini. Enfin, cet état permet grâce à une **table d'action** d'indiquer à la machine quel action réaliser, que ce soit un déplacement, une lecture ou une écriture, ainsi que le nouvel état après réalisation de l'action. Si aucune action ne correspond à l'état actuel et au symbole qui bien d'être lu alors la machine s'arrête.

Avec ses quatre simples composant, on peut comme Alan l'indique dans sa publication, créer une Machine de Turing universelle, capable de simuler le comportement de n'importe quelle autre machine de Turing, on dit alors qu'elle est Turing-complète. C'est ainsi la raison pour laquelle on peut utiliser un ordinateur pour simuler une machine virtuelle, ou utiliser des jeux Turing-complete comme Minecraft[^1] Terraria[^2]  ou Factorio[^3] pour reproduire une processeur, un affichage graphique, et ainsi une version simplifié du jeu à l'intérieur de son propre monde virtuel. Il existe également un ludiciel du même nom qui guide le joueur et l'élève, on peut y apprendre l’électronique pas à pas, dans un logiciel qui simule sa logique, et permet de reproduire des circuits complexes et comprendre le fonctionnement des langages assembleurs, qui naîtrons 13 ans après l'expérience de pensée de Turing.[^4]

[^1]: https://www.youtube.com/watch?v=-BP7DhHTU-I
[^2]: https://www.youtube.com/watch?v=7lVAFcDX4eM
[^3]: https://youtube.com/watch?v=zXPiqk0-zDY 
[^4]: https://store.steampowered.com/app/1444480/Turing_Complete/

Pionnier de l'intelligence artificielle il proposera également le Test de Turing permettant de tester la faculté d'une machine à imiter une conversation humaine. Il la décrivit dans sa publication *Computing Machinery and Intelligence* comme un *jeu d'imitation* qui donnera le titre du film récent abordant une partie de sa vie.

Enfin, alors que la série de machines Allemandes Enigma, dont le brevet à été déposé à la fin de la première guerre mondiale, chiffre des messages de guerre depuis des dizaines d'années en utilisant le chiffrement par substitution poly-alphabétique de Vigenère, et dont une énième version sert en cette période de seconde guerre mondiale 

En se basant sur les travaux du cryptologue polonais Marian Rejewski, qui a étudié un exemplaire d'un manuel d'Enigma montrant le chiffrement d'un texte en clair à l'aide d'une clé et de son résultat chiffré, Alan Turing conçu une Bombe cryptologique électromécanique qui utilise la force brute, de l'anglais brute-force, c'est à dire qu'elle vérifie toutes les combinaisons. Cette machine sera capable de casser les codes d'Enigma utilisé pendant la période de seconde guerre mondiale évoquée dans cette section. Il est estimé que le déchiffrement d'Enigma à réduit d'au moins deux ans la durée de la guerre.

Avant sa mort en 1954, il eu connaissance du projet Manhattan de réalisation de la bombe atomique lors de son voyage aux Etats-Unis en 1942-1943, et il assistera également aux travaux de Von Newman qui, reprenant son architecture, lui inspireront l'Automatic Computing Engine, un design d'ordinateur à programme enregistré.



#### 1.7.6.6. Zuse Konrad

En 1936 l'ingénieur allemand Zuse Konrad commencera à travailler sur une série de quatre calculateurs éponymes nommés Zuse. La première version, le Z1, était un calculateur mécanique qui sera abouti en 1938 bien que peu fiable, certaines pièces ayant étés réalisés manuellement à la scie, dans la chambre de ses parents qui l'ont soutenu financièrement. La deuxième version en sera une version améliorée sortie en 1940, réutilisant la mémoire mécanique qui était elle très fiable, mais remplaçant l'unité arithmétique en utilisant des relais électriques. Le Z3, achevé en 1941, est un calculateur électromécanique qui sera considéré comme le premier ordinateur numérique, il était entièrement automatique et programmable, utilisant le calcul binaire et à virgule flottante. Cette troisième version s'avèrera être théoriquement Turing-complet, mais ne fut pas considéré pleinement comme tel car ne possédant pas de branchement conditionnel permettant de ne pas aller à l'adresse mémoire suivante, mais vers une adresse spécifique en fonction de la satisfaction ou non d'une condition. La quatrième et dernière version en 1953, sera la premier ordinateur commercial au monde, avant même le Ferranti Mark I et l'UNIVAC 1. Konrad sera ailleurs plus considéré comme un scientifique de production et d'affaire qu'un chercheur, contrairement à Alan Turing ou Von Neumann qui conceptualisaient et publiaient avant de passer aux applications. Cela ne l'empêcha pas d'être un pionnier de l'informatique qui conçut également, de 1942 à 1946, le premier langage de haut niveau nommé Plankalkül, bien qu'il fut oublié de son temps et repris qu'en 1975 puis compilé en 2000 cinq ans après sa mort.

Son histoire nous montre qu'avec de la motivation et le soutien de nos proches, on peut devenir un pionnier, voire le premier à développer une technologie donnée, quitte à n'être que peu connu, même perdre des travaux, et que d'autres ne soient redécouverts et exploités que plus tard.



#### 1.7.6.7. Calculs balistique

La Moore School, un établissement de formation d'ingénieur en électronique voit le jour en 1923. À la même période apparaît le Ballistic Research Laboratory, qui comme son nom l'indique, est un établissement de recherche en  balistique. Ces deux établissement auront une importance cruciale dans le développement de l'informatique.

En **1937**, un professeur de mathématiques et de physique nommé John Vincent Atanasoff entreprends, avec l'aide de Clifford Berry un de ses étudiants diplômé, la création d'une machine à calculer électronique. Deux ans plus tard, en 1939 une machine rudimentaire est alors existante mais incomplète, elle sera nommée Atanasoff Berry Computer (ABC). Pendant son développement, ils ont apporté des idées pionnières et innovantes comme l'arithmétique binaire, l'utilisation d'éléments de commutation électronique, ou encore la parallélisation. La construction de cette machine est d'ailleurs la première à intégrer des tubes à vides. En 1940 ils présentent la machine à John Mauchly, qui a voulu apporter une solution à la réalisation de tables de tir, permettant de régler correctement une arme balistique pour atteindre sa cible avec si possible un seul réglage plutôt que de devoir faire un essai approximatif et réajuster en fonction de la trajectoire observée comme c'était le cas jusque là. En 1942 la machine est testé avec succès et sera utilisée pour trouver des solutions à des équations linéaires. 

-> ENIAC



#### 1.7.6.8. Hewlett Packard

Créée en 01/01/**1939**, HP réalisait initialement des instruments de mesure.





[Retour](#Sommaire)

### 1.7.7. Seconde guerre mondiale

#### 1.7.7.1. Colossus Mark 1

Plusieurs calculateurs seront construit pour l'effort de guerre, que se soit pour effectuer différents calculs balistiques ou pour la cryptanalyse. Le Colossus Mark 1 sera par exemple utilisé pour déchiffrer les messages produits par les machines de Lorenz, utilisés par l'Allemagne nazie pour faire communiquer les haut dirigeants de Berlin et ceux des différents corps d'armée en utilisant un chiffrement de flux en continue. La version 2 du Colossus sera quand à elle utilisé pour le débarquement de Normandie.



#### 1.7.7.2. Harvard Mark 1

L'IBM Automatic Sequence Controlled Calculator (ASCC) datant de **1944** est le premier calculateur entièrement automatique. Une fois lancé, il calculait pendant des heures en suivant le programme qui lui était donné à l'aide de cartes perforées. Ces avancés lui ont valu une couverture médiatique dans la presse, voyant cette machine comme un robot intelligent pouvant trouver toutes les réponses mathématiques. Cette machine ne possédait pourtant pas encore de branchement conditionnel alors que la machine analytique de Babbage, bien que jamais construite, stipulait déjà cette fonctionnalité. Les programmes était alors très long et il possédait des Relay Switches qui pouvaient casser. L'ASCC a permis la réalisation de tables et la réalisations de premières expérimentations notamment par Grace Hopper.

https://www.youtube.com/watch?v=MOUg25dJM4c



#### 1.7.7.3. Architecture de von Neumann

Beaucoup d'ordinateurs ont été réalisés en **1945** dont l'EDVAC l'ENIAC, le SSEC succédant au ASCC, et le Z4. Von Neumann lors de ses travaux sur l'EDVAC, à décrit cette architecture qui sera réutilisée par Turing, Mauchly et Eckert pour l'ENIAC, ainsi que sur tout les ordinateurs à partir de cette date.

Cette architecture à permis à permis au stockage de posséder les instructions du programme et la donnée à traiter sur le même support, permettant également aux instructions du programme d'être également traités comme de la donnée, et donc de pouvoir être lu et réécrite.

La mort de leur investisseur principal lors d'un trajet en avion les poussera à revendre leur entreprise à Remington par la suite.

Remington Racheté par Sperry Corporation après fusion avec la Burroughs Corporation en 1986, deviendra Unisys, 100 ans après sa création en 1886

Même si il a été pensé par 2 hommes, l'ENIAC à été programmé par 6 femmes, qui ont du documenter, coder et brancher des millions de cables, il a été réalisé à la Moore School de l'université de Pennsylvanie à partir de juin 1943

Ils formeront la Eckert-Mauchly Computer Corporation en 1946



Elisabeth Findler Jake, nom de domaines, whois nom de domaine (page jaunes) Alors que la silicon vallait est encore loin.



#### 1.7.7.4. As we may think

Vannevar Bush, était un chercheur en électrotechnique au MIT, co-créateur de l'analyseur différentiel résolvant des équations différentielles à l'aide de machines analogiques composées d'engrenages ; puis créateur du Comparator et du Rapid Selector en 1940, destinés au traitement automatique des microfilms de stockage analogique.

Titulaire d’une chaire à l’ancêtre de la NASA alors nommé NACA, il sera également conseiller scientifique de Roosevelt et parmi les chercheurs du projet Manhattan de 1945, pour lesquelles il assistera aux premier essais de la bombe nucléaire. C'est d'ailleurs un mois avant les bombardements atomiques d'Hiroshima et Nagasaki, alors que la seconde guerre mondiale se termine, en **juillet 1945**, qu'il publia *As we may think* dans le mensuel The Atlantic.

Cet article est un appel aux scientifiques, qui ont alors mis leur savoir au service de la guerre, semblant à juste titre arriver à sa fin ; de désormais partager la connaissance, trouver des moyens d'inscrire une information de manière quasi permanente, et de la retrouver plus facilement, déplorant que les travaux de certaines personnes comme le concept des lois de la génétique de Mendel, aient été perdus pendant toute une génération du fait que sa publication n'ai à l'époque pas atteint un public capable de reprendre ses travaux.

Il indique que contrairement à Babbage et Leibniz, la situation technologique et économique nous permet désormais de stocker et gérer l'information scientifique afin qu'elle soit conservée, transmise et surtout consultée, à l'aide de machines de moins en moins chères et de plus en plus fiables, dont ils sont tout deux pionniers.

Il parlera des avancés de la photographie, de la capture vidéo, et de la compression utilisé sur les microfilms qu'il a longuement étudié. Il  introduit alors la possibilité qu'à l'avenir, une machine puisse enregistrer et convertir la parole d'un auteur en texte, comme le faisait alors les sténographes, ajoutant qu'une machine des laboratoires Bell nommée *Voice Operating Demonstrator* (Voder), présentée lors d'une exposition internationale, était actuellement capable de convertir du texte en une voix humaine synthétique, et qu'une autre était capable de l'opposé, c'est à dire de convertir une voix en caractères phonétiques (à la manière d'une sténotype), appelée quand à elle Vocoder.

Il projette alors que les auteurs du futurs pourront utiliser des machines non plus analogique mais électroniques, utilisant des signaux radio pour communiquer à distance 100 fois ou plus rapidement qu'alors, traitant des informations bien plus variées, ayant des usages plus versatiles, conjointement à une possibilité de suppression et de réécriture.

D'un point de vue de l'information, il énoncera plusieurs concept dont la sélection, avec pour exemple les numéros de téléphone permettant de sélectionner un destinataire parmi des millions de stations possibles ; mais aussi l'indexation, indiquant que l'information est stockée à un endroit unique, suivant un chemin de groupes et sous groupe se finissant généralement par une liste triée alphabétiquement. Il introduit alors la notion d'association et de liens entre les informations, formant une toile, dans laquelle l'utilisateur pourrais se balader, gardant un historique du chemin qu'il a emprunté pour passer d'un article ou d'une idée à une autre.

Pour illustrer ses propos, il fini par introduire un outil fictif de son invention, le memex, permettant à tout un chacun de stocker ses livres, enregistrements, communications, lui permettant se suppléer à sa mémoire. Il l'image comme un bureau, composé d'écran translucides, d'un clavier, de leviers et de boutons, potentiellement utilisable à distance; et évoque alors la possibilité d'acheter du contenu sous forme de microfilms à insérer dans la machine, ou les interactions utilisateurs en comme l'utilisation de leviers pour défiler les pages des livres ou d'un stylet pour ajouter des notes de marges.

Ces concepts seront sources d'inspiration pour la construction du world wide web avec l'hypertexte, les sélecteurs HTML, et même Wikipédia dont l'usage du memex décrit en réalité parfaitement le fonctionnement, formant comme il l'indique "une nouvelle forme d'encyclopédie formée de chemins associatifs interconnectés".

https://www.w3.org/History/1945/vbush/vbush.txt



[Retour](#Sommaire)

### 1.7.8. Guerre froide et course à l'espace

La seconde guerre mondiale prends fin et c'est officiellement l'époque contemporaine pour les anglo-saxons. C'est l'avènement du nucléaire, de l'ère de l'informatique, mais aussi de la décolonisation et de la guerre froide. Les besoins de calculs sont plus importants que jamais, aéronefs, nucléaire militaire, civil, et gestion de l'énergie sont au cœur des réflexions et stratégies des pays du monde.

L'arrivé du calcul et de la simulation informatique offrent un meilleur contrôle, ainsi qu'une prise de décision plus efficace, permettant de gérer de grandes structures, qu'elles soient civiles, militaires, ferroviaires, aériennes, ou autre.  

De grands projets à forte complexité en découlent, elle amènent à un besoin de communication multimédia mondiale, pour que les gens puissent s'organiser et faire coopérer des spécialistes de tout les domaines concernés. Internet viendra résoudre ce problème à partir de 1970, amenant à la période de mondialisation intense que l'on vit encore actuellement en 2023.



#### 1.7.8.1. Temps réel

Initialement chiffré à 200'000 dollars pour deux ans de développement, pour finalement atteindre les 8 millions de dollars pour huit ans ; un projet américain top secret nommé *Project Whirlwind* visait à simuler de l'espace aérien des États-Unis. Bien qu'il ai coûté une fortune, cet ordinateur constitué initialement de tubes à vides, puis par la suite l'un des premiers à avoir utilisé de la mémoire à tores de ferrites, mais surtout ayant permis des sorties en temps réel ; a influencé cette technologie et battit les fondations de l'industrie informatique jusqu'à aujourd'hui.

Cet ordinateur devant simuler les sorties d'un avion, et même potentiellement de n'importe quel avion sur le territoire américain, il est évident que pour que le pilote ai une expérience réaliste, les affichages et donc les valeurs sorties de l’ordinateur doivent toujours être à jour, nécessitant du temps réel. C'est pourquoi Jay W. Forrester, la personne en charge du projet, fit la rencontre de Perry O. Crawford Jr. Ce pionnier de l'informatique était alors l'un des premier si ce n'est le premier, à avoir réalisé et par la suite promu, les mérites des ordinateurs numériques au profit des analogues, notamment pour ce genre de problème de temps réel, et ce avant même que de tels ordinateurs ne soit construit, le premier étant l'ENIAC en 1945. Crawford et Forrester l'ont découvert à la fin de la guerre, lorsque les projets secret militaire ont alors été révélé, à l'occasion d'une conférence du MIT sur les Techniques de Calcul Avancés.

Mais alors que les budgets sont revus à la baisse à cause de la fin de la guerre, le projet Whirlwind est mis en danger, et sa faisabilité à court terme remise en cause. Arrive alors la guerre froide, avec la menace de bombe nucléaire, missiles et bombardiers russes, capables d'arriver aux États-Unis en passant par le pôle nord.



George Valley, professeur de physique au MIT, faisant alors parti du conseil scientifique de l'armée de l'air américaine, fit en **1950** un rapport déclarant que le système de défense anti-aérienne américain était catastrophique. Les informations du système de radar était à ce moment traités manuellement avant d'être relayées à un centre de contrôle et de commande. Les problèmes de communication et de couverture radar rendant impossible une alerte rapide en cas de tentative d'attaque par le pôle nord.

Valley sera par conséquent responsable du projet qui sera nommé Semi-Automatic Group Environment (SAGE), ayant pour but de solutionner ces problèmes. Pour la réalisation de ce projet, il chercha alors un moyen informatique pour améliorer la récupération, les communication et le traitement des données radar. Bien qu'il eu écho du Projet Whirlwind en mal, il décida de se se renseigner par lui même. Se rendant compte des progrès impressionnant qui avaient été réalisés, et qui par chance avait enfin permis l’exécution de programmes de tests ; il relança le projet avec les fond nécessaires, rendant le système opérationnel l'année suivante, en 1951. À partir de ce moment, le Whirlwind fusionne avec SAGE.

Un réseau de 23 centres de directions est alors distribué dans tout le pays, et des opérateurs commencent à analyser les engins volants, qu'ils soit civils ou militaire, alliés ou ennemis, sur des écran cathodiques.

Crawford avait prédit que le temps réel ne permettrait pas seulement la simulation d'un avion, mais la visualisation en temps réel de tout le trafic aérien, comme c'est le cas aujourd'hui en source ouverte. Les circuits imprimés, écrans cathodiques et mémoire à tores seront grâce à ce projet, et aux intervenant comme IBM, Burroughs, ou Bell ; rapidement démocratisés et vendus aux particulier dans les années 1960. Le développement des écran causera également la naissance de nouvelles interfaces bien plus pratiques.

Ce système en temps réel donnera lieu, dans les années suivantes, au projet SABRE de réservation aériennes, jusqu'alors manuel et fastidieux, qui sera lui même généralisé à bien d'autres système comme le bancaire avec l'apparition des cartes de crédits, distributeurs automatiques, codes barres, et plus tard paiements en ligne. Plus récemment, les usa ont déclarer que les ovnis sont un problème de sécurité nationale, cela laisse penser que se système est surement encore dans les tuyaux.



#### 1.7.8.2. IBM 602 & 603

IBM 602 & 603 **1946**



#### 1.7.8.3. Trackball

1946



#### 1.7.8.4. Norbert Wiener

En **1947** par le mathématicien Norbert Wiener décrit la **cybernétique**, l'étude des mécanismes d'information des systèmes complexes et leur analogies entre les organismes vivants et les machines. Ils mettent en avant la rétroaction, et la téléologie très présente dans ce domaine. La cybernétique trouve son origine étymologique du grec kubernêtikê qui signifie gouverner dans le sens de diriger un navire. 

L'une des premières machines pourvues de rétroaction est le régulateur à boules de James Watt en 1788 qui permettait de réguler la vitesse de rotation d'une vachine à vapeur.

https://fr.wikipedia.org/wiki/Auto-organisation

Le mouvement cybernétique ralliera de nombreux mathématicien dont John Von Neumann.



#### 1.7.8.5. SSEM

Le tube de Williams-Kilburn, développé en 1946 ou 1947 par Frederic Calland Williams et Tom Kilburn, utilise les tubes cathodiques de Boris Rosing pour enregistrer des données binaires. La Small-Scale Experimental Machine (SSEM), premier ordinateur à architecture de von Neumann les utilisait pour sa mémoire vive. Le test de cette nouvelle technologie sur la SSEM, aussi appelé Manchester Baby étant concluant en **1948**, la production d'un autre ordinateur à été lancé.



#### 1.7.8.6. Manchester Mark I

En 1948 les travaux commencent pour voir le jour en 1949, décrit comme un cerveau électronique par la presse, des neuro-scientifiques s'y intéressent rapidement, à une période ou naît la cybernétique.



#### 1.7.8.7. Théorie de l'information

1948 Claude Shannon

**Warren Weaver**, né le 17 juillet 1894 est principalement connu comme un des pionniers de la traduction automatique, il a également assister Shannon dans le développement de la théorie de l'information



#### 1.7.8.8. IBM 604

1948



#### 1.7.8.9. IBM 407

1949 imprimante 150 lignes par minutes



#### 1.7.8.10. Origines de l'Assembleur

Jusqu'alors, les instruction était écrites en binaire, Maurice Wilkes et David Wheeler, qui en **1949** travaillèrent sur l'Electronic Delay Storage Automatic Calculator (EDSAC), et le Binary Automatic Computer (BINAC), ont récupérer l'idée d'une notation utilisée par Von Neuman et Herman Goldstine.

Pour exemple, un ingénieur pouvait indiquer la notation `A 25 S` sur papier pour décrire l'instruction d'ajouter dans l'emplacement mémoire de numéro 25 l'entier court (**S**hort type : pouvant stocker les entiers de -32 767 à 32 767). Cette instruction serait alors récupérée par un technicien qui le convertira en binaire, obtenant `1110000000110010`. Une fois inscrite en binaire dans le système, il était compliqué de "debugger" et voir où était située l'erreur.

Wilkes, se rendant compte que l'ordinateur, capable de manipuler les nombres et les lettres de l'alphabet grâce au binaire, pouvait théoriquement lui même stocker `A 25 S` et le convertir en `1110000000110010`, décida alors de confier à Wheeler, qui passait alors son doctorat, la rédaction d'un programme capable de convertir les instructions symboliques d'un téléscripteur en un code binaire. Cette avancée formidable permit d'automatiser une tâche mais mettait en exergue un autre problème, les programmes en résultants devait s’exécuter correctement et produire les résultats escomptés. Pour cela des techniciens devait relire attentivement le programme et la provenance des erreurs semblait alors venir de la répétition et ré-implémentation de la même fonctionnalité de manières différentes. La solution, également initialement proposée par Von Neuman et Herman Goldstine a été de mettre en place une bibliothèque de petit programmes spécifiques alors appelées routine. Ainsi, les "développeurs" de l'époque pouvait juste y faire appel plutôt que de les réinventer à chaque fois. L'idée de factorisation et de code réutilisable est alors née, permettant d'améliorer la productivité et la fiabilité. 



#### 1.7.8.11. IBM CPC

Rival de l'EDSAC et du BINAC, il fait son apparition la même année en **1949**, fait à partir du IBM 604 et du IBM 402

Premier compilateur (A-0 System Grace Hopper 1951)



#### 1.7.8.12. Ferranti Mark I

Le Ferranti Mark 1, aussi connu comme le Manchester Electronic Computer, est le premier ordinateur électronique généraliste commercialisé du monde et le second au monde après l’ordinateur électromécanique Z4. Il a été créé en **1951**. Alan Turing l'a utilisé pour modéliser des processus de morphogenèse, devenant pionnier de la bio-informatique. Il a aussi été employé pour jouer de la musique ou aux échecs. Il ne sera vendu qu'a raison de 7 exemplaires avant d'être succédé par le Ferranti Mercury



#### 1.7.8.13. Compilateurs et premiers languages de haut niveau

L'Universal Automatic Computer I (UNIVAC) est sorti en **1951**, c'est alors une filiale de Remington Rand, MAGNETIC TAPE STORAGE start and stop tape rapidement avec des servomoteurs, plastic -> déforme -----> métal résistant, travail pour écrire et lire dessus

Pour la réalisation de cet ordinateur, Grace Hopper, docteur en mathématiques, officier de la marine, et informaticienne américaine ; créé en **1951** le Arithmetic Language ou A-0 system, qui sera le premier compilateur. Il aura plusieurs version jusqu’à arriver au B-0 Flow-matic, développé entre 1955 et 1959. Comme tout les compilateurs, il prends un code et le converti en code machine exécutable, ce que le A-0 réalisait déjà en établissant des liens entre les programmes et sous-programmes ainsi que leurs paramètres.





#### 1.7.8.14. Leo I

Descendant de l'EDSAC créé par Maurice Wilkes, le Lyons Electronic Office est créé en **1951**. Il est le premier ordinateur utilisé pour des opérations commerciales.

J'ai pu lire que le LEO I était le premier ordinateur à avoir un système d'exploitation, mais il n’est avéré que pour le LEO III en 1961 qui pouvait ouvrir plusieurs programmes en même temps à l'aide du multitasking. Il est cependant possible que le LEO I avait un système d'exploitation lui permettant de faciliter l'accès aux ressources, voire faire du traitement par lots. Cet ordinateur pouvait calculer et imprimer 40 fiches de paie en une heure, soit un peu moins d'une par minute.



La première occurrence que j'ai trouvée dans une archive du MIT de Douglas T. Ross, est la suivante, qui a sûrement été utilisée pour l'UNIVAC 1103 réalisé en 1953. 

>  Another innovation triggered by my needs was the
> creation of the Director Tape utility program
> [WWJQ54p7] -- the first real Operating System
> command language system (to use present-day
> terms) to eliminate the computer operator
> function for my elaborate, multi-tape runs.





L'UNIVAC I a fait grandement peur à IBM qui craignant de perdre une partie importante du marché civil, bien que cela ne fut pas le cas. Leur réponse à été de confier la réalisation d'un ordinateur à Nathaniel Rochester, qui a travaillé sur la technologie Radar, m les éléments arithmétiques du projet Whirlwind I, les prémices de l'intelligence lors de travaux d'études sur la reconnaissance de schémas et la théorie de l'information qu'il a dirigé à IBM, en plus d'être l'un des conférenciers de la conférence de Dartmouth qui se tiendra en 1956 avec John McCarthy, Marvin Minsky et Claude Shannon.

IBM dévoila ainsi le modèle IBM 701 en **1952**, premier ordinateur scientifique produit en masse, aussi connu sous le nom de Defense Calculator. Il possédait une mémoire tambour, utilisant le premier langage assembleur, conçu par Rochester.

L'année d'après en **1953**, John Backus, alors ingénieur d'IBM, créé le Speedcoding, un interpréteur qui a été le premier langage de programmation de haut niveau créé pour un ordinateur IBM. Bien qu'il s'appelle Speedcoding, et qu'il ai facilité le développement en fournissant des instructions pour les fonctions mathématiques, le fait que ce soit un interpréteur le rendait particulièrement lent, 10 à 20 fois plus que du code machine, de plus, il prenait 30% de la mémoire à lui seul. Malgré cela, il a permis la prise en charge des nombres à virgule flottante sur les ordinateurs IBM 701.

L'IBM 702 lui succédera la même année, il est le premier ordinateur muni de dérouleur de bandes magnétiques, il était moins puissant que le 701 ou le ERA 1103 mais avait contrairement à eux, les civils pour cible commerciale. Contrairement à l'UNIVAC, sa mémoire n'était pas constituée de ligne à retard analogiques, mais elle était électrostatique en utilisant des tubes de William, deux fois plus rapide et plus fiable. De plus, contrairement au monolithe qu'était l'UNIVAC, son design étant modulaire et composé de boites reliées entre elles, l'ordinateur pouvait être transporté dans la majorité des ascenseurs. Après son annonce, IBM arrive à réaliser 50 commandes en 10 mois.

Toujours en **1953**, est développée la mémoire à tores magnétique qui a révolutionné pendant une vingtaine d'année la mémoire vive. Constitué d'anneaux de ferrite polarisés, correspondant à un bit de 0 ou 1 en fonction du sens du champ magnétique, tous traversés par des fils conducteurs.

Se basant sur l'hystérésis, faire passer un courant dans un fil permettait de lire, ou d'écrire si le courant est assez élevé, la valeur des tores.

Cette technologie à poussé IBM a rééditer ses modèles 701 et 702 avec ce type de mémoire, en plus de la création de nouveau modèles l'utilisant comme le 650, 704 et 705 EDPM.



L'année suivante, en **1954** sortira l'IBM 650, modèle le plus populaire des années 50, et pour cause, il coûtait seulement un quart du prix d'un 701, et a été vendu à de nombreuses universités, créant toute une génération de programmeur. Faisant de lui le premier ordinateur produit en masse dans le monde et la première machine d'IBM à réaliser un profit significatif.

Créé aux États-Unis en **1955**, le TRAnsistor DIgital Computer sera quand à lui premier ordinateur à transistors.





#### 1.7.8.15. Premiers langages de haut niveau opérationnels

En **1957**, Backus invente le Formula Translator ou FORTRAN, un langage de programmation haut niveau qui produira des programmes binaires aussi performants que ceux des programmeurs expérimentés. Il à initialement conçu ce langage comme une solution à un problème, suite à la constatation que plus de la moitié des coûts des centres informatiques était dus aux salaires des développeurs qui passent jusqu’à la moitié de leurs temps à tester et debugger plutôt qu'a produire du code, à cela s'ajoute le fait que le coût des machine devenant de moins en moins cher, ce pourcentage ne ferait alors qu'augmenter si rien n'était fait. C'est en présentant cette logique à son supérieur qu'il eu l'autorisation de travailler sur ce projet qui n'a à son début que peut de reconnaissance, considéré comme un projet de recherche tentant de réaliser l'impossible et n'ayant aucune garantie de résultats.

Lorsque Backus et son équipe ont présenter le projet à des développeurs, ils étaient tous sceptique. Leurs attentes étaient hautes et le FORTRAN encore approximatif et inabouti. Cela faisait en effet plusieurs années que les salariés d'IBM entendaient parler de "programmation automatique" permettant d'automatiser la programmation bas niveau en utilisant un langage de plus haut niveau d'abstraction pour factoriser à la manière de programmes comme les assembleurs, interpréteurs, compilateurs et générateurs de programmes. Ce type de programme s’exécutant sur d'autre programmes voire dans certains cas sur eux même sont du domaine de la méta-programmation.

La réalisation comme la popularité du FORTRAN ont donc pris du temps à se mettre en place. Son developpement et son adoption ont été acceleré par l'edition de manuels simplifies comme le Programmer's Primer de Grace E. Mitch.



Par la suite, Grace Hopper inventera le COBOL, un langage haut niveau qui sera créé en **1959**, dans ce langage, les instructions étaient moins technique et plus lisible, donnant l'illusion aux décisionnaires que n'importe qui pourrait comprendre les programmes qui en découlent, pour preuve, celle pour calculer le salaire net d'un employé à partir de son salaire brut était ainsi :

```cobol
SUBSTR TAX FROM GROSS-PAY GIVING NET-PAY
```



Langage de première génération : Binaire, difficile à lire et interpréter par un humain

Languages de deuxième génération : Instructions simples et lisible par l'humain, spécifiques à une certaine famille de processeur, dont elle permet de manipuler les commandes principales à l'aide de mot clés mnémoniques.

Langages de troisième génération - haut niveau - Structures de contrôle et de données

Ces abstractions sont de plus haut niveau et indépendant du matériel, les langages deviennent plus conviviaux et pratiques d'utilisation

(FORTRAN & COBOL) aggregate data types



##### 1.7.8.15.1. Lisp

**1958** John Mc Carthy



Languages de quatrième génération

Abstraction encore plus haute permettant de facilement interconnecter et manipuler des outils logiciels tiers comme une base de donnée, une interface graphique, ou un serveur web. La plupart des langages de la troisième génération se sont doté de ses fonctionnalités et ont évolué vers cette génération. Ce genre de langage est désormais assez haut niveau pour permettre un développement rapide de programme dans un domaine spécifique. C'est la raison pour laquelle Python étaient initialement spécialisés dans le traitement de la donnée et JavaScript les interactions utilisateurs.



Language de cinquiéme génération

L'ordinateur trouve lui même les solutions pour nous, très lié à l'intelligence artificiel, l'example le plus concret est Prolog.



#### 1.7.8.16. IBM 1401

Fabriqué entre **1959** et 1965, il a été l'ordinateur à transistor le plus vendu, notamment grâce à la politique marketing d'IBM qui a adopté une vision globale, dans l'objectif de prendre en compte le maximum d'utilisateurs et donc clients potentiels. Cette politique avait déjà fait ses preuves avec le modèle 650. IBM à ainsi créer plus qu'un ordinateur, un système complet, avec une imprimante pouvant imprimer 600 lignes par minutes, principale raison d'achat ayant fait son succès. En plus de cela, avec ses transistors flambants neufs et bien plus fiables que les tubes à vide, il a rendu obsolète les ordinateurs en étant munis en même temps que les machines électromécaniques qui était encore utilisées par soucis monétaires.

Par la même occasion, IBM invente le Report Program Generator (RPG), un langage de programmation haut niveau facile à comprendre, permettant aux comptables et techniciens de tabulatrices de se "reconvertir", en utilisant des concepts qu'ils connaissent et utilisaient déjà sur les panneaux de contrôles, où ils branchaient des câbles pour implémenter les entrées, calculs, et sorties. Ils pouvaient ainsi programmer sans apprendre toutes les arcanes de l'assembleur, du COBOL, ou encore du FORTRAN. Malgré cela, beaucoup de client préféraient demander les logiciels directement à IBM, qui avait un monopole si important qu'ils pouvaient se permettre de les livrer "gratuitement" avec les machines qu'ils louaient.





#### 1.7.8.17. Théorie algorithmique de l'information

**1960**



#### 1.7.8.18. Computionnalisme

**1961**



#### 1.7.8.19. Souris

Inventée en **1963** par Douglas Engelbart, elle ne sera présentée au public qu'en 1968. Cet informaticien réalisera également le système d'exploitation NLS, ses travaux serons financés par Joseph Carl Robnett Licklider qui financera également ARPANET



#### 1.7.8.20. Luciano Floridi 

Luciano Floridi est né à Rome le 16 novembre **1964**, ce philosophe est l'un des plus important théoriciens de la Philosophie de l'information et de l'éthique de l'informatique. Il a fondé et dirige plusieurs groupes de recherche dans ces domaines.



#### 1.7.8.21. IBM System 360

Alors que Control Data Corporation (CDC) s'attaque au marché scientifique, fournissant des ordinateurs avec un meilleur rapport performance / prix, les plaçant 3 ème derrière UNIVAC et le leader IBM ; que General Electric annonce 3 ordinateurs bas, moyen et haut de gamme ; que la Radio Corporation of America (RCA) et Honeywell décident de réaliser un ordinateur compatible avec le 1401 et d'autres machines IBM ; cette dernière se rends compte que ses concurrents ont déceler une opportunité et qu'ils doivent réagir à cette menace mettant en danger leur domination sur la marché.

IBM lance alors une gamme d'ordinateurs compatibles entre eux, ayant la même architecture, et capable d’exécuter les mêmes logiciels ; ce qui n'était à ce moment pas le cas, posant problème autant à ses clients qu'à IBM même, ces machines alors très spécialisées n'offrait pas une grande interopérabilité ou possibilité de changements de logiciel comme de matériel et périphériques, voire chaîne de production, nécessitant des experts de la machine en question.

Contrairement aux machine à cartes perforées, les ordinateurs n'avait donc à ce moment pas de normes et standards, nécessitant parfois de recoder un même programme sur X machines différentes, un processus très onéreux.

IBM décide alors de concevoir le System/360 en 1962, il n'a pas été économe pour autant, 5 billion de dollars, c'est plus que le budget du projet Manhattan. Cela a provoqué des différent monumentaux dans leurs équipes, ils ont été obligés d'isoler celle en charge du 360.

Niveau marketing ils aurait pu tout anoncer d'un coup mais ont décider d'anoncer machine par machine permettant une adoption progressive comme cela avait été le cas pour le passage des machines electromécaniques aux ordinateurs dans les années 50.

Alors qu'Honeywell lance en 1963 le modèle 200 compatible IBM 1401, qu'IBM décida de rendre progressivement obsolète, et lance en **1964** la communication du System/360 dans 63 villes des États Unis et 14 pays étrangers, 6 ordinateurs et 44 périphériques.

S'en suit plus de 5 billions de chiffre d'affaire, 30 ans de croissance, "l'ordinateur a été fait par IBM et a fait IBM".

Cet ordinateur avait pourtant bien des défauts, il ne supportait pas le temps partagé, permettant d'être utilisé par plusieurs utilisateurs en même temps.



#### 1.7.8.22. Premières applications de l'IA

Percepton En **1957**, le psychologue Frank Rosenblatt 

Dendral fut créé en **1965** par deux informaticiens, 1 médecin et 1 chimiste. Ce programme permet d'identifier des structures moléculaires en se basant sur les connaissances d'expert et des techniques d'analyses telles que la spectrométrie de masse. C'est le premier programme considéré comme "système expert".

Il a par la suite été utilisé comme outil d'aide à la décision. Pour des molécules complexes, le nombre de possibilité étant plus grand, il permet d'obtenir rapidement les différentes combinaisons réalisable selon les règles de la chimie et la masse moléculaire donnée.

L'année suivante, en 1966 Eliza sera révélée, une intelligence artificielle conversationnelle dans le but de simuler un psychothérapeute, notamment en tournant des affirmations de l'utilisateur en questions.



#### 1.7.8.23. Microprocesseur

Au début du 20 ème siècle, seront développés les circuits imprimés, composés de métal conducteurs appliqués sur une carte faite d'un matériau isolant aussi appelé diélectrique, réalisant ainsi des circuits électroniques complexes.

En 1903 Albert Hanson dépose un premier brevet[^0] pour coller des fils conducteurs sur un papier de paraffine dans le but d'améliorer les branchements téléphoniques, posant les bases de cette technologie.

[^0]: https://worldwide.espacenet.com/patent/search/family/009975642/publication/?q=pn%3DGB269729A

En 1925, Charles Ducas déposa un brevet utilisant la galvanoplastie électrolytique pour graver un circuit électronique en utilisant un pochoir, décrivant par la même occasion la possibilité de réaliser des cartes ayant plusieurs couches de circuits conducteurs [^1]

[^1]: https://patents.google.com/patent/US1563731A/en?inventor=Ducas+Charles | https://worldwide.espacenet.com/patent/search?q=pn%3DUS1563731A

En 1927, César Parolini réalisera également un brevet sur l'impression de motifs adhésifs en poudre de cuivre sur un diélectrique, suivant un procédé de Ducas et une idée de Thomas Edison. [^1.1]

[^1.1]: https://worldwide.espacenet.com/patent/search/family/009975642/publication/GB269729A?q=pn%3DGB269729A

En 1943 Paul Eisler, dépose un autre brevet de gravure de motif conducteur utilisant des feuilles cuivre plaquées sur une base isolante servant de support au circuit électriques [^2] 

[^2]: https://worldwide.espacenet.com/patent/search/family/032233881/publication/GB639178A?q=pn%3DGB639178

L'ensemble de ces travaux seront réutilisés pour la réalisation du transistor en 1947. Par la suite des améliorations comme les trous traversants plaqués initialement brevetés en 1961 par la Hazeltine Corporation ont permis des cartes plus fiables et complexes. Aujourd'hui, les cartes électroniques peuvent avoir une centaines de couches de circuits imprimés.



En 1958, Jack Kilby ingénieur chez Texas Instruments, réalise le premier circuit imprimé, qui sera plus tard connu sous le nom de puce électronique, en reliant manuellement deux transistors en utilisant du germanium, bien qu'il fut longtemps oublié, il fini par obtenir le prix Nobel de physique en 2000. La même année, toujours en 1958 Robert Norton Noyce qui travaille alors à Fairchild Semiconductor qu'il a cofondé un an avant, fait indépendamment la même découverte et popularise les circuits intégrés en silicium à la base de l’électronique encore utilisée aujourd'hui, éclipsant ainsi Kilby. Suite à un désaccord au sein des dirigeants de Fairchild, il décide, avec Gordon Earle Moore, également cofondateur, de quitter cette entreprise pour fonder Intel. De la même manière que Backus avait constaté que le matériel devenait de plus en plus fiable et de moins en moins cher pour de meilleures performances, Moore inventa en 1965 une loi éponyme postulant que les semi-conducteurs aurait une progression linéaire de leur performances, qui doublerai ainsi tout les deux ans.

En **1969**, le microprocesseur est inventé par Federico Faggin, et Marcian Hoff, un ingénieur et physicien d'Intel, 



#### 1.7.8.24. Course à l'espace

Spoutnik 1 **1957**

En **1967**, Apollo 1 est un échec et la lune parait de nouveau inaccessible aux américains, sous Kennedy.

Le programme Apollo Guidance Computer (AGC) réalisé en **1969** par Margaret Hamilton a été numérisé et rendu disponible sur [Github](https://github.com/chrislgarry/Apollo-11). Écrit en Assembly

Apollo 11 sera finalement une réussite, les États-Unis rattrapent alors leur retard dans la course à l'espace jusqu'alors menée par l'URSS.

Katherine_Johnson



#### 1.7.8.25. John Horton Conway

https://www.youtube.com/watch?v=8DBhTXM_Br4

Théorie des noeux, qui trouve des usages dans la créations de matérieux composites et l'analyse de l'ADN1937 il invente le jeu de la vie en **1970**, les règles sont très simple mais comme l'as dit Leonard de Vinci, la simplicité est l'ultime sophistication.





[Retour](#Sommaire)

### 1.7.9. Popularisation et Mondialisation

Jusqu'alors, l'informatique était essentiellement réservé aux domaines privés comme le militaire, le spatial et l'administration des États. À partir des années 70, l'informatique va commencer à arriver dans le quotidien des particulier les plus aisés et finir par être dans une grande majorité des foyers. Internet commence à se développer petit à petit.



#### 1.7.9.1. Genèse d'internet

Arpanet et Cyclades **1969** et 1972 (Louis Pouzin)



#### 1.7.9.2. Interfaces graphiques

Inspiré par le memex décrit par Vannevar Bush, Ivan Edward Sutherland invente Sketchpad en 1963, il obtiendra à cet effet bien des honneurs et récompenses, dont un Turing Award en 1988. Cela inspirera à Douglas Engelbart la réalisation du oN-Line System (NLS), le premier système d'exploitation multi-utilisateur à utiliser la souris qu'il a lui même inventé, mais également les liens hypertextes, écrans à balayage et les interfaces graphiques et leurs fenêtres. Ce projet finira par être abandonné à cause de sa difficulté d'apprentissage, beaucoup de personnes ayant travaillé sur le projet décident alors d'aller travailler pour Xerox, qui en 1970, met en place le Palo Alto Research Center, plus connu sous le nom de Xerox Parc.

Ce laboratoire d'études travailla sur les premières interfaces graphiques et éditeurs permettant de modifier un document directement depuis son rendu visuel, on appelle ceci la technologie "What You See Is What You Get" ou WYSYWYG. Le premier logiciel à implémenter cette technologie et permettre le repositionnement du curseur et la sélection de texte à l'aide d'une souris est l'éditeur de documents Xerox Bravo sorti en 1974, peu après l'ordinateur Xerox Alto, qui a été révélé le 1er Mars 1973. Cet ordinateur est le premier à fournir une interface graphique, et ainsi ne plus être dépendant de la ligne de commande. Il introduira également les métaphores de bureau, documents, classeurs, et corbeille, familiers à tout employé de bureau. L'ensemble interface graphique et pointeur favorisa grandement l'adoption et la démocratisation des ordinateurs, cela deviendra un standard omniprésent dans nos interactions avec machine.

Alan Kay à dirigé le développement de Smalltalk, créé en 1972 au Xerox Parc, c'est un langage de programmation objet et surtout le premier à avoir un environnement de développement complétement graphique indépendant de la ligne de commande ou d'un éditeur de texte. Il fut intégré au Xerox DoRADO, héritié du Xerox Alto, avec pour objectif d'être un système bien plus performant. Plus tard, en 1996, Smalltalk deviendra Squeak encore disponible et utilisé aujourd'hui. Squeak est inspiré de Logo, qui est à la fois une famille de langages de programmation et une philosophie de l'éducation. C'est le résultats de travaux sur le cognitivisme promu par Marvin Minsky et les travaux sur l'éducation de Jean Piaget promus par Seymour Pagert.





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

C'est une expérience de pensée considérant que si chaque membre d'une immense nation comme la Chine, était invité à simuler l'action d'un neurone, constitué d'axones et de dendrites, en utilisant des émetteurs bidirectionnels, et ce afin de reconstituer un cerveau, alors un tel système pourrait-il avoir un esprit ou une conscience ?

L'affirmative repose sur une pensée fonctionnaliste, l'idée est que ce qui réalise la même fonction est capable de réaliser les mêmes résultats, et dans notre cas, l'obtention d'états mentaux et de conscience.

Cette idée de cerveau artificiel géant imaginée en 1961 et reprise en 1974 par Lawrence Davis et **1978** par Ned Block qui quant à lui déclarera qu'un tel cerveau n'aurait pas d'esprit, sera reprises mainte fois, comme par exemple lorsque l'on a affirmé que Google avait plus de connexion que le cerveau humain et que les gens craignent alors qu'internet qui en ai encore plus puisse développer une conscience.

Leibniz avait déjà dans son livre *Monadologie*, imaginé "un homme mécanique dont on pourrait visiter le corps comme on visite un moulin".

Par ailleurs cela pose la question du bateau de Thésée, si l'on était capable de remplacer des neurones par des neurones artificielles, jusqu'à substituer totalement au neurones "naturels", l'individu serait il le même ?



#### 1.7.9.8. La chambre chinoise

Cette expérience de pensée à été imaginée par un philosophe américain nommé John Searle vers **1980**. Alors qu'il lit un livre sur l'intelligence artificielle et la manière dont la machine interprète et créer du texte, il se demanda alors si un programme informatique pouvait recréer un esprit numérique.

Il énonce alors une situation ou un humain n'ayant aucune connaissance du chinois est enfermé dans une pièce, avec une table de questions et réponse à des phrases chinoises. Un examinateur extérieur parlant réellement chinois (sinophone) lui pose alors des questions, le programme humain se repose alors sur la syntaxe des phrases, retrouvant la réponse correspondante et l'appliquant, produisant des réponses. Du point de vue de l'examinateur sinophone les réponses qu'il obtient correspondent bien à celles d'un de ses semblables. Pour autant, elle sont produites par quelqu'un qui ne parle pas un mot de chinois, et ne comprends sûrement pas le sens des phrases qu'il reçoit ou émet. 

Il démontra qu'une intelligence artificielle ne peut actuellement que simuler un esprit ou une pensée, et qu'elle est dans l'incapacité de recréer une réelle conscience ou intentionnalité. Cela démontre aussi que le test de Turing est insuffisant pour déterminer si ses caractéristiques sont présentes chez une IA, en effet, dans son expérience, les réponses du programme humain ne sont pas différentes de celle d'un sinophone, puisqu'elles proviennent de tables de correspondances, et que l'examinateur ne peut malgré tout pas faire la différence avec un natif car cela se base sur de l'écrit. Pour autant, bien qu'il finisse par maîtriser la manipulation des symboles pour reconnaître des schémas et former des réponses cohérentes, il ne connaîtra et comprendra toujours pas un traître mot ou signification derrière les symboles qu'il utilise.

Cela à permis de redéfinir plus précisément l'intentionnalité, à la fois comme la capacité de l'esprit, émanent du cerveau, de rendre l'organisme conscient de son environnement grâce à sa perception subjective, et en dérivé de lui permettre d'être un locuteur qui doit en plus de ce qui est dit avant, formuler dans son esprit, la phrase qu'il va prononcer. Autrement dit, c'est parce l'humain est conscient qu'il peut penser et parler intentionnellement. Un locuteur humain a conscience de ce que signifient ses dires à travers la sémantique qu'il accorde aux mots qu'il utilise, et au fond de son discours.



#### 1.7.9.9. Mémoire flash et stockage optique

Optical Storage Disc **1980**



#### 1.7.9.10. Cerveau dans une cuve

C'est une reformulation moderne du malin génie de Descartes, imaginée par Hilary Putnam en 1981, cette expérience de pensée invite à s'imaginer que notre cerveau pourrait être placé dans une cuve, et qu'il recevrait des stimulis envoyés par une machine, chargée de nous simuler le monde extérieur. La problématique étant alors de savoir si ce cerveau à raison de croire de qu'il perçoit.

La thèse serait ainsi de dire que comme les signaux envoyés aux cerveaux ne correspondent à rien de tangible dans notre monde, alors il est dans l'illusion.

L'antithèse, revient à justifier que le stimuli étant identique, il est tout à fait légitime du point de vue du cerveau, de dire qu'il le reconnaît bien.



#### 1.7.9.11. Logiciel libre

Richard Stallman annonce le projet GNU le 27 Septembre **1983**, en 1985 il fonde le FSF, la Free Software Foundation. Ou Free ne signifie par gratuit dans le sens de prix mais dans le sens de liberté. Le langage C est alors grandement utilisé. Il invente également en 1989 la licence GNU General Public Licence, plus connu sous le nom de GPL.

En 1987 Andrew S. Tanenbaum invente Minix un système d'exploitation UNIX avec une architecture 16 bit. Inspiré par Minix, Linus à donc créer **Linux en 1991**, avec un nouveau Kernel, lineage, sous licence GPL. Leur coopération donnera GNU/Linux qui est une suite embarquée d'éditeurs comme bash, emac, la GNU C Library et le compilateur GCC, et pleins d'autres.

Aujourd'hui la grande majorité des entreprises utilisent du code Open Source dans leur business, certains utilisent même à tord des logiciels GPL sans savoir que cette licence est contaminante et peut faire que leur logiciel devrait légalement être libre de facto. D'autres licences permettent aux entreprises d'utiliser des librairies pour un usage commercial. Certains projets Open Sources comme Symfony ont donné naissances à multitudes de Business à commencer par le leur, SensioLabs, qui fournissent des conférences et formations payantes, et sponsorise certaines entreprises experts dans cette technologie.



#### 1.7.9.12. Cadriciels et Open Source

CSS a permi de diversifier l'apparence des sites webs, les frameworks et themes comme Foundation ou bootstrap ont regénéraliser et harmoniser l'affichage des sites, réduisant la créativité au profit de l'accessibilitée. Tout cadre vient limiter la liberté, généralement pour le bien commun.

Symfony, un outil logiciel facilitant la réalisation d'application webs, ne permet pas de surcharger l'attribut "name" d'un champ de formulaire, le retrait de requêtes expires ne marche pas... L'installation d'un de leurs plugin React m'a récemment causer defaut. J'ai eu, par la force des choses, à contacter la personne chargée de la documentation de Symphony. Un certain [Ryan](https://github.com/weaverryan), qui est "Symfony docs lead, writer at SymfonyCasts". Ce fût une expérience riche ou j'ai découvert un environnement qui m'est familier, bien que je n'ai pas souvent réaliser de l'open source avant. Une pipeline qui sors des erreurs à des lignes qui n'existent pas sur ma version, et qui malgré ça permet d'assurer la qualité de la documentation rédigée en RST ou DOCtor-RST, à l'aide de tests de compilation.





#### 1.7.9.13. World Wide Web

https://fr.wikipedia.org/wiki/ENQUIRE (**1990** Tim Berners Lee) web semantique Rose Dieng Kuntz

Ward Cunningam créa le premier wiki en 1995 il est encore disponible tel quel[^1], il fut un développeur Smalltalk 

[^1]: http://wiki.c2.com/



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

L'informatique est désormais omniprésente, la terre est entourée de satellites en orbites, les continents sont interconnectés avec des câbles sous marins, 7 personnes sur 10 possèdent un smartphone, les demandes d'informations et démarches administratives se numérisent rapidement. La programmation est facilitée par l’apparition de langages haut niveau à la syntaxe simple avec des compilateurs plus explicites. Depuis 1950, bien que les interfaces graphiques aient permis de faciliter l'utilisation des ordinateurs, la programmation n'a plus été révolutionnée depuis les premiers langages haut niveau. Seul l'apparition du langage Rust, dont l'adoption dans les entreprises sera encore longue, à permis d'avoir un nouveau candidat avec des performances équivalentes au C et une expérience de développement plus agréable que les autres, et ce grâce à ses nouveaux concepts de gestion de la mémoire, évitant ainsi 70% des bugs selon Microsoft.[^1]

[^1]: https://www.technologyreview.com/2023/02/14/1067869/rust-worlds-fastest-growing-programming-language/

Pour le reste, la majorité des langages ont leur propres qualités notament grâce à leur communautés et aux outils qu'elles ont développés, le Python est toujours une référence pour le traitement de la donnée, et le JavaScript à standardiser la gestion des 



https://fr.wikipedia.org/wiki/Th%C3%A9orie_g%C3%A9n%C3%A9rale_des_syst%C3%A8mes



Les gens suivent l'autorité, la loi, mais la loi est parfois fausse, la seule loi qui doivent etre suivit est la science, la raidon pure pouvant etre prouvée.

En tant qu'animal humaine on ne s'en porte pourtant que mieux de juste suivre les instructions et juste faire ce que l'on doit ou a envie de faire.



### 1.8.1. Méthodes d'aide à la structuration d'information 

Le management moderne à eu besoin de pouvoir former et guider efficacement ses employés et pour cela il à fallu trouver des outils et moyens mnémotechniques pour facilement analyser les facteurs influent sur l'activité d'une entreprise, une des plus ancienne est la carte heuristique plus connue sous le nom de carte mentale. Née de l'arbre de porphyre, un philosophe néoplatonicien du 3è siècle, elle représente visuellement le cheminement de la pensée et l’interconnections des idées afin d'en extraire les toutes les informations importantes.



#### 1.8.1.1. Décision

Prendre une décision est n'est pas chose aisée, il est parfois difficile de mesurer les tenants et aboutissants de nos choix. C'est pourquoi il est important de prendre du recul pour poser sur la table les différentes possibilités et acteurs de la situation. Beaucoup d'outils comme la carte mentale heuristique analysent d'abord un panel d'informations variés, parmi eux l'analyse Politique, Économique, Socioculturel, Technologique, Écologique, et Légal, nommée PESTEL permet de se poser des question sur les influences externes, et par la suite réaliser une analyse plus fine des parties prenantes. Elle peut également permettre de trouver des éléments à mettre dans une matrice multicritère ou Strenght Weakness Opportunity Threat (SWOT).

Une fois que l'on a analysé l'environnement du projet, ses avantages et inconvénient internes et externes, on peut être amenés à choisir entre plusieurs fournisseurs ou solutions, pour cela on peut appliquer la matrice multicritère. Chaque été, avec des amis, nous l'utilisons pour choisir dans quel AirBnb nous allons partir. Nous y renseignons une note pour le prix, l'emplacement géographique, la qualité du logement, etc... et obtenons un score moyen permettant de déterminer où nous partirons en vacances.

Pour planifier et ordonnancer les tâches, la matrice d'Eisenhower est un outil élémentaire. Très proche des matrices de faisabilité et de priorisation, elle permet de classifier les tâches importantes et/ou urgentes, celles qui ne le sont pas, ainsi qu'à qui les confier.

Si un problème apparaît lors de la réalisation d'une tâche, une méthode simple et efficace nommée "5 Why" indique que se poser 5 fois d'affillée la question "Pourquoi ?" permet généralement de trouver la source d'un problème. Dans le même genre nous avons également le diagramme d'Ishikawa qui permet de schématiser les différentes causes possible d'un événement ou effet. Inspiré des quatre causes d'Aristote, il est généralement construit en analysant les 5 M : Matière première constituante, Matériel utilisé, Méthode employée, Main-d’œuvre intervenant, et Milieu dans lequel l’événement apparaît.

5S Supprimer, S'organiser, Scintiller, Standardiser, Suivre

QQOQCCP est un acronyme résumant une méthode interrogative empirique qui trouve ses origines dans L'Éthique à Nicomaque d'Aristote[^1] Elle corresponds aux 7 questions fondamentales à se poser pour faire de tour d'une situation Quoi Quand Où Quand Comment Combien Pourquoi. Cela est très utilisé en journalisme pour découper l'information en priorité.

Un objectif SMART doit être **s**pécifique, **m**esurable, **a**tteignable, **r**éaliste et **t**emporel.

[^1]: Livre III, Chap. 2, fragment 1111a 2-20 - https://remacle.org/bloodwolf/philosophes/Aristote/nicom2.htm#II



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

Les blocs de codes de ce chapitre sont écrits en Javascript. Vous pouvez les tester vous même le code en faisant des copiés collés dans la console d'un navigateur internet. Pour y accéder il faut être sur ordinateur et généralement taper sur la touche F12 ou faire la combinaison `Ctrl + Shift + I`.

Comme évoqué dans le chapitre [Prémices de l'Algèbre](#Prémices de l'Algèbre), et plus généralement en Mathématiques, les informations sont stockés dans des *variables*, souvent représentées par une lettre, ou dans le cas de l'informatique, sous forme de mots. Parmi les variables, nous avons aussi des *constantes*, variables qui ne changerons plus une fois qu'on leur à affecté une information. Un objet, représente un ensemble de variables. Dans notre monde, n'importe quel objet peut être représenté par un ensemble de variables, prenons une voiture, discrétisons ses informations à une marque, un modèle, une vitesse actuelle et maximum.

```js
var ma_première_voiture = {
    "marque": "Citröen",
    "modele": "C4",
    "vitesse_actuelle": 0,
    "vitesse_max": 140
};
```

Les langages de haut niveaux permettent de déclarer des *fonctions*, qui permettent d'obtenir un résultat en fonction d'une variables fournies ou non en entrées. Les fonctions permettent  généralement de réaliser des actions sur des objets, dans notre cas, nous allons faire accélérer la voiture qui sera passée en paramètre.

```js
function faire_accélérer(voiture) {
    const vitesse_de_la_voiture = voiture.vitesse_actuelle;
    const { vitesse_max } = voiture;
    if(vitesse_de_la_voiture + 1 <= vitesse_max) {
        voiture.vitesse_actuelle = vitesse_de_la_voiture + 1;
    }    	
}

// [En l'utilisant sur la déclaration de la variable ma_première_voiture faite avant]
console.log("Vitesse initiale : %o", ma_première_voiture.vitesse_actuelle); // 0
faire_accélérer(ma_première_voiture);
console.log("Vitesse après accélération : %o", ma_première_voiture.vitesse_actuelle); // 1
```

Dans le cas présent, nous sommes en train de faire avancer la voiture, c'est un peu comme si on devait la pousser. Sachant cela, je peut vérifier que sa vitesse a augmentée, mais je vais surtout créer une *classe* pour qu'elle puisse se déplacer elle même. Vous noterez que dans le code comme dans les langages parlés, il y'a une forme passive et active. La classe est un moule permettant de décrire un l'objet qui y sera forgé et de lui affecter des fonctions. En JavaScript la classe peut faire référence à l'objet qu'elle décrit à l'aide du mot clé `this`. Toute classe à une fonction obligatoire nommée `constructor`, elle d'indique l'algorithme à suivre pour créer l'objet qui résultera d'une nouvelle création avec le mot clé `new`.

L'exemple ci-dessous va donc créer une classe Voiture que l'on peut construire en lui passant un objet représentant une voiture telle qu'on l'a précédemment déclaré implicitement, avec la fonction vue plus haut.

```js
class Voiture {
    constructor(
    	{
            marque,
        	modele,
            vitesse_actuelle,
            vitesse_max,
    	}
    ) {
        this.marque = marque;
        this.modele = modele;
        this.vitesse_actuelle = vitesse_actuelle;
        this.vitesse_max = vitesse_max;
    }
    
    accélére() {
        // On peut renommer une variable de deux manières
        const vitesse_de_la_voiture = this.vitesse_actuelle;
        const { vitesse_max: vitesse_maximum } = this;
        
        if(vitesse_de_la_voiture + 1 <= vitesse_maximum) {
            this.vitesse_actuelle = vitesse_de_la_voiture + 1;
        }
        
        // A l'instar du constructeur qui le fait par défault,
        // ici on retourne explicitement l'objet. 
        return this;
    }
}

const object_premiere_voiture = new Voiture(ma_premiere_voiture).accélére;
console.log("Vitesse maintenant : %o", ma_première_voiture.vitesse_actuelle); // 2
```

La plupart les langages objets ont une notion d'interfaces, en Javascript elle n'existe pas, on pourrais utiliser Typescript, mais dans notre cas on va juste faire une classe abstraite avec un constructeur vide et donc sans attribut. Un objet créé avec cette classe n'aurait que des méthodes, dans le cas de l'interface on ne définit normalement que le nom, les paramètres et le type de retour. Les abstractions permettent de réutiliser des fonctions et de s'assurer que plusieurs entités, dans notre cas des véhicules différant (voiture, bus, train, etc...) d'une liste puissent tous effectuer le même calcul ou traitement donné, par exemple sur la vitesse et la position pour mettre les déplacer avant chaque affichage d'une simulation routière. On peut ainsi redéfinir notre voiture plus simplement. De plus, en utilisant les abstractions, nos objets deviennent super !

```js
class Vehicule {
    constructor(
    	{
            vitesse_actuelle,
            vitesse_max,
    	}
    ) {
        this.vitesse_actuelle = vitesse_actuelle;
        this.vitesse_max = vitesse_max;
    }
    
    accélère() {
        const vitesse_de_la_voiture = this.vitesse_actuelle;
        const { vitesse_max } = this;
        if(vitesse_de_la_voiture + 1 <= vitesse_max) {
            this.vitesse_actuelle = vitesse_de_la_voiture + 1;
        }
        
        return this;
    }
}

class Voiture extends Vehicule {
    constructor(voiture) {
        const {
            marque,
        	modele,
            vitesse_actuelle,
            vitesse_max,
    	} = voiture;
        
        super(voiture);
        
        this.marque = marque;
        this.modele = modele;
    }
}

const object_premiere_voiture_abstract = new Voiture(ma_premiere_voiture).accélére;
console.log("Vitesse maintenant : %o", object_premiere_voiture_abstract.vitesse_actuelle); // 2
```

Assez de code pour le moment. Je suis de l'avis que ces abstractions devraient être représentée et manipulable de manière graphique, de la même manière que le reste. La syntaxe doit être optionnelle comme c'est le cas dans l'éditeur Typora avec lequel j'ai rédigé la première version Markdown de ce mémoire.



#### 1.8.4.5. UML

Les flowchart, qui se traduisent en français par arbres de décisions, diagramme de processus, logigramme ou encore organigramme de programmation (non pas par diagrammes de flux), ont initialement été développés dans l'ingénierie industrielle vers 1920. Ils ont rapidement été repris par l'industrie informatique alors naissante vers 1950. La réalisation de schémas ont depuis les début de l'informatique, permit de formuler la logique la constituant pour modéliser les programmes qui en résulterait et les présenter à toute personne sans avoir à écrire ou lire du code.

C'est ainsi qu'en **1996**, Grady Booch, James Rumbaugh et Ivar Jacobson, trois ingénieurs travaillant sur des langages de modélisation objets différents, décident de s'unir pour co-créer un Langage de Modélisation Unifié qui avec l'inversion anglaise donne l'acronyme UML. Reprenons notre véhicule qu'est la voiture, nous pouvons la modéliser ainsi en UML.

![](./assets/VehiculeVoiture.png)





https://hal.science/hal-02970135/document



#### 1.8.4.6. Performances et Optimisations

##### 1.8.4.6.1. Techniques

1. Parallélisation
2. Pointeurs mémoires
3. Calculs distribués



##### 1.8.4.6.2. Managériales

Dans une grande partie des lignes de production il a une équipe dédiée aux tests et à la vérification. Elle est chargée de s'assurer que le produit est conforme à leurs attentes ou à celles formulées dans un document dédié comme un cahier des charges idéalement technique. Dans le monde de la production logicielle, nous avons la chance de pouvoir l'automatiser à l'aide de pratiques DevOps, intégration et déploiement continus (CI / CD) permettent non seulement de vérifier le bon fonctionnement d'une liste de fonctionnalités mais également de les mettre automatiquement à disposition du public lorsqu'elles sont toutes valides.

1. Commentaires et documentation

   Chaque fonctionnalitée doit être documentée.

   Chaque ligne devrait être commentée en langage naturel, un switch devrait permettre de basculer entre le code réel et commenté. Toute manquement déclancherai une notification sur la ligne en question.
2. Gestionnaires de version 

Git est un logiciel de gestion de versions décentralisé sous licence GNU GPL. C'est un logiciel libre et gratuit, initié en **2005** par Linus Torvalds le créateur de Linux lors de la création de son noyau. Linus ne voulait pas réaliser ce projet seul et a rapidement compris que la qualité d'un logiciel viendrai des débats houleux entre ses collaborateurs et l'implémentation de la meilleure idée à la fin. graphe d'historique de modifications de fichiers visualisable avec gource.

5. Microservices



#### 1.8.4.7. Quelqu'un à généralement la solution

En programmation objet, il existe des Patrons de conceptions qui trouvent leur racines dans l'architecture. L'architecte en bâtiment Christopher Alexander publie l'essai *A Pattern Language : Towns, Buildings, Construction* en **1977**. Cette œuvre à définit de manière casuistique, à la manière du [Code de Hammurabi](#Code-de-Hammurabi), les problèmes rencontrés en architecture et leurs solutions.

Cette notion à permit de catégoriser les patrons algorithmiques selon trois classes, les *créateurs* solutionnent des problèmes d'[instanciation](https://fr.wikipedia.org/wiki/Instanciation) et de configuration des classes et des objets, les *structuraux* indiquent comment organiser les classes d'un programme et leurs l'interfaces ; et les *comportementaux* définissent l'organisation des [objets](https://fr.wikipedia.org/wiki/Objet_(informatique)) pour que ceux-ci s'échangent des informations en fonction de leurs responsabilités.





#### 1.8.4.8. Principes SOLID

Robert Cecil Martin aussi connu en tant que l'Oncle Bob est un ingénieur en informatique et écrivain ayant compléter les patrons de conception, et langages de modélisation en introduisant de multiples concepts de programmation, décrivant et argumentant des bonnes pratiques de cet art comme le fait de bien nommer les variables afin qu'elles explicitent leur utilité et les valeurs qu'elles stockent, de ne pas faire de copier coller que l'on modifie mais de plutôt faire des fonction réutilisables avec des paramètres pour faire varier un comportement. Dans la même logique de cohérence et d'uniformisation, il énonça les cinq principes fondamentaux de la programmation orientée objet.

Simple responsabilité unique : une classe, une fonction ou une méthode doit avoir une et une seule responsabilité

Ouvert / Fermé : tout élément d'une application, que ce soit une classe, une fonction ou autre, doit être fermée à la modification mais ouverte à l'extension. L'utilisateur doit pouvoir grâce à son API,  ses paramètres ou sa configuration, l'utiliser voire l'interconnecter à un autre logiciel.

Liskov et sa substitution : Si une instance de véhicule doit pouvoir être remplacée par une instance de voiture, tel que voiture est un sous-type de véhicule, sans que cela ne modifie la cohérence du programme.

Interfaces séparées : Il vaut mieux créer plusieurs interfaces spécifiques quitte à ce qu'elles n'ai qu'une seule méthode ou fonction, plutôt qu'une seule interface générale possédant plusieurs fonctions. Cela permet d'avoir une granularité plus fine et de pouvoir à l'aide de la composition, obtenir des interfaces composés uniquement des méthodes dont on a besoin.

Dépendances inversés : Bien que les classes dépendent d'abstraction telles que les interfaces, il faut le plus souvent possible ne pas travailler avec mais utiliser les interfaces, cela permet notamment de respecter le principe de Liskov. On part du concept général pour traiter le plus de cas et aller vers le particulier au besoin.



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

La définition de l'information est controversée et difficile à établir clairement à cause de son usage et des abus de langages. La définition philosophique donnée par le Centre National de Ressources Textuelles et Lexicales (CNRTL.fr) est selon moi la plus proche. Elle indique que l'information est la transmission d'une forme, dans le sens de concept et référence au monde des idées propre à l'intellect, comme le décrit Platon dans sa classification des connaissance, découlant de son analogie de la ligne. En effet l'étymologie latine "*informare*" signifie donner forme ou se former une idée de quelque chose.

Contrairement à la définition de Wikipédia, qui déclare qu'elle désigne le message et les symbole utilisés pour l'écrire,  l'information n'est selon moi réelle qu'au moment ou elle se manifeste au moyen du matériel. C'est à dire qu'elle n'est  pas définie par son support, mais bien par la forme ou l'idée à laquelle son support fait référence. La quantification et / ou qualification lié au message étant la réelle information. Pour preuve, une information chiffrée avec des méthodes modernes est totalement illisible et ne témoigne absolument pas de l'idée qu'elle véhicule. Ce n'est que lors du déchiffrement que l'information est être révélée.

Un fait est ainsi la naissance d'une information émanant d'une action matérielle se manifestant à un moment donné t. Pour autant, le fait n'existe plus une fois ce moment t passé, il n'en reste plus que les conséquences physiques et l'idée de cette action qui en est la cause. Plusieurs observateurs peuvent avoir une version différente des faits, propre à leur subjectivité et vérités relatives. Le fait en lui même est une vérité absolue et pure que l'on ne peut qu'approximer. Seul l'acteur des faits peut réellement savoir ce qui c'est passé à condition bien sur qu'il soit conscient. 

### 1.9.2. IO

Entrées et sorties, Inputs et Outputs (IO), sont l'ensemble des paramètres et des valeurs retournant d'une fonction. Avec elles seules on peut définir les fonctionnalités possibles à un certain contexte d'entrées et sorties attendues. C'est une sorte de double entonnoir, comme des portails, théoriquement bidirectionnels. On peut la mettre en relation avec la lecture et l'écriture, en C# .NET [`System.IO`](#https://learn.microsoft.com/en-us/dotnet/api/system.io?view=net-7.0) est ailleurs un espace de noms (namespace) permettant d'accéder à des fonctions algorithmiques standard de lire et écrire des fichiers et par conséquent des dossiers. Puisque oui, les dossiers sont des fichiers, contenant l'adresse mémoire de son contenu. En réalité, tout n'est que variables et fonction mathématiques. Les fichiers sont des variables, et les actions que l'on peut réaliser à l'aide de fichiers de code sont des fonctions, elles mêmes composées de variables. 

### 1.9.3. Habitudes

La mode n'est que passagère, il n'y a que les habitudes de vies et s'en tenir à un plan structuré, cohérent et à forte plus-value qui reste dans l'Histoire. Il n'y a pas de bons ou de mauvais moments pour agir, il y a le moment et l’agissement qu'on y fait ou pas. La volonté est la seule capacité mentale capable de reprogrammer la pensée et ses habitudes. Il faut apprendre à dire non et encore plus savoir se dire non à soi-même.

Une habitude provient d'un signal, suivi d'une envie, puis d'une action récompensée, et enfin, elle est pleinement constituée par la répétition qui la caractérise. Les habitudes sont fondamentales dans l'addiction, on fini par faire ce qu'on a l'habitude de faire, dire ce qu'on a l'habitude de dire. On ne change pas ou peu notre manière de penser car cela nous coûterait trop d'efforts sans garantie de résultat. Mais si on attends toujours d'avoir une preuve de résultat, on n'expérimenterai alors jamais. N'ayez pas peur de changer vos habitudes, qu'elles soient bonnes ou mauvaises, toutes les habitudes occupent une part très importante de notre temps. Et si l'on veut occuper ce dernier d'actions variées, il convient alors de parfois changer même nos bonnes habitudes.

### 1.9.4. Valeurs

La valeur d'une chose ne dépends que du prix qu'un acheteur est prêt à dépenser pour l'acheter. Les valeurs d'une personne ne dépendent quand à elle que du prix qu'elle est prête à accepter pour les renier. En informatique, la valeur est l'information que l'on stocke dans une variable. 

### 1.9.5. Rapport de force, ordres de grandeur et précision

Les bases sont les fondations d'un système numéraire, notre base 10 permet de multiplier et diviser par 2, et 5, la base 12, par 2, 3, 4 et 6. Un base donne lieu à des ordres de grandeurs, le système décimal commun possède les puissances de dix que tout le monde connaît : dizaines, centaines, milliers, etc...

Ces puissances peuvent représenter des paliers symboliques pouvant représenter un rapport de force qui est universel et naturel. Dans les relations humaines, la différence de puissances entre deux personnes dépend selon moi principalement du nombre d'années de vie qu'un individu a expérimenté dans de bonnes conditions. On pourrait également le penser sous le prisme de la taille, nombre facile à se représenter proportionnellement à nos petites mètres de hauteur, que l'on peut rapporter aux grattes ciels faisant jusqu'à 414 humains empilés. Cet exemple absurde me permet d'introduire le fait que le Burj Khalifa ai coûte 1,5 milliard de dollars, ce qui représente environ 1000 vies de travail à 2000€ par mois pendant 40 ans (sans dépense). Si de tels projets d'envergure sont réalisables depuis l'époque des pyramides et autres merveilles du monde, c'est grâce à un travail coopératif et à un rapport de force démentiel entre les maître d'ouvrage et les maîtres d’œuvre, puis entre les maîtres d’œuvres et les salariés, puis tout ceux en dessous. Cette hiérarchie naturelle est nécessaire à l'aboutissement de tout projet ou société d'envergure, c'est pourquoi la bourgeoisie n'as jamais était contre bien qu'elle ai défendu une séparation des pouvoir dans le but d'éviter un despotisme absolu et tyrannique. L'autorité agit fortement sur les comportement et prises de décisions, l'expérience de Milgram nous prouve même qu'elle peut nous faire faire des choses qui vont à l'encontre de nos principes.

En informatique la composition décrit le fait que dans chaque boite, on peut avoir une autre boite, c'est l'idée abstraite de la poupée russe poussée à l'infini. Je pense que ce grand tout, suis une logique de composition. On peut le voir à différentes granularité et plus il est grand plus sa vie est longue. Certains principes sont similaires quelque soit l'ordre de grandeur, d'autres, sont propres à certains. Lorsque l'on fait face à un problème informationnel, il convient de définir son périmètre, pour analyser et gérer précisément la zone voulue. L'informatique nous permet désormais d'avoir une interface pour naviguer précisément dans une simulation réaliste et visualiser ses ordres de grandeur. [c4model](https://c4model.com/)

Loi de Moore, Volume de donnée internet ou chat gpt, probabilités sachant que. le big deal Théorie du chaos et contextes intriqués, un grand tout.



Même de nos jours, une personne décidant de se salarier dans un travail dit alimentaire pour survivre se "vends" en échange de sa subsistance. Pour autant, c'est lui qui par son travail, assure les revenus du patron, et indirectement des autres salariés.



#### 1.9.5.1. Signaux forts et faibles

En communication comme en électronique, un signal fort peut perturber voire totalement stopper un système. C'est le cas dans l’épisode 22 de la série Baki dans lequel un combattant spécialisé en environnement fait taire toute une arène en criant extrêmement fort. Tout étudiant l'a déjà expérimenté, on a tous déjà été dans une situation ou un groupe bruyant se tait après qu'une autorité ai hausser la voix.

### 1.9.6. Viralité

La viralité est un facteur mathématiquement calculable. C'est la moyenne de transmissions faites par les personnes atteintes par une information.



### 1.9.7. Parasitage

informations parasites quand je travaille sur une fonction je n’ai pas besoin de voir autre chose que ses dépendances. le divertissement n'est pas nécessaire non plus. L'informatique et l'algorithmique nous permettent de répliquer a l'infini une information ou un traitement logique de donnée. 

croyances limitantes et mauvaise foi







### 1.9.8. Contexte et vérité

La vérité peut être absolue ou relative, l'absolue ne peut être approché qu'en la définissant dans un contexte partiel dont on aura jamais une pleine compréhension car il nous est impossible de capter et mémoriser toutes les informations y ayant donné lieu.

Par exemple, la proposition "L'eau mouille" n'est vraie que relativement à l'état de l'eau liquide, cet état étant lui même absolu, il est lui même relatif à une certaine densité des molécules H2O le constituant, définie entre autre par la température qui n'est pas le seul facteur. On peut en effet reprendre même raisonnement et dire que "l'eau bout à 100•C", or cette affirmation ne sera vraie que sur la Terre, à une altitude de 0m au niveau de la mer, sous une pression d'environ 1000hPa.

Cette récursion de vérité absolu-relative à une autre est la raison pour laquelle on utilise des axiomes pour admettre des informations comme vraie selon un contexte et des limite données, pour ainsi baser nos réflexions dessus, que ce soit en physique, comme en mathématique ou d'autres sciences. On déduit ainsi des démonstrations dont la syntaxe est composée de définitions, que ce soit de variables en informatique ou de conditions avec des "si et seulement si [...] alors" en mathématique. C'est également la raison pour laquelle l'humain à inventé la méthode des 5 Why, permettant généralement de retrouver la cause d'un problème en remontant jusqu'à 5 récursions de "Pourquoi ?".

De plus, nous l'avons vu au chapitre décrivant Antiquité, l'art du dialogue qu'est la dialectique, nous montre qu'il est futile de vouloir avoir raison et exposer sa vérité relative comme absolue. La mauvaise foi est l’ennemie de l'amélioration personnelle. Seule la vérité absolue compte, lors d'un débat suivant les règles de cet l'art ce n'est pas dans le but de faire briller son savoir ou répandre sa version relative de la vérité que les deux acteurs conversent, mais au contraire de challenger leurs vérités relatives pour les améliorer voire invalider à l'aide des antithèses d'autrui.

En effet la dialectique indique bien qu'il est fondamental de garder sa parole distincte de celle de son interlocuteur, que l'on ne doit pas prendre comme une vérité absolue mais analyser pour en dégager les raisonnements logiques. Il n'y a rien à gagner à avoir raison, l'humanité évolue en échangeant des idées permettant de s'instruire, et d'apprendre.

### 1.9.9. Doute

Il faut douter de tout même de ce que l'on sait, il faut challenger constamment sa vérité relative pour la remettre en question et s'approcher de l'absolu. Toute notre expérience de la vie introduit des biais dans nos apprentissages. Bien qu'il y'est un certain déterminisme dans le monde, il est multifactoriel. On est certain de rien qui ne soit pas vérifié et prouvé ou que l'on expérimente soit même avec une bonne proportion de réussite.



### 1.9.10. Preuves

Hiérarchie des preuves, et niveaux de preuves





### 1.9.11. Apprentissage

L'apprentissage commence généralement avec de la mémorisation, s'ensuit une compréhension qui permet la résolutions de problèmes, enfin s'y ajoute la créativité que l'on débloque lorsque l'on à le savoir et le savoir faire. La mémorisation étant le terreau du savoir, il est important de comprendre que scientifiquement, on sait aujourd'hui que les humains ont, tout comme les machines, une mémoire de travail et une mémoire à long terme. Ses deux mémoires sont comparables à la RAM et aux stockages de masse. Le cerveau possède même un mécanisme d'encodage de l'information vers la mémoire à long terme et de récupération vers la mémoire de travail, les informations les plus importantes possèdent plus d'amorces, permettant de les retrouver et s'en souvenir plus facilement, avec bien sur certaines informations dont le signal se perd, dans l'oubli, nécessaire à trier et jeter ou archiver ce qui l'est moins, dans le cas de la mémoire à long terme, cela se produit en perdant des amorces au fur et a mesure du temps.

A l'aide de schémas mentaux, nous associons un ensemble de concepts ou d'idées liées, permettant de formuler facilement des phrases compréhensibles et retransmissibles. L'humain à la chance d'être multimodal et d'avoir plusieurs "périphériques" biologiques. Une fois qu'il a capté une information grâce à un d'entre eux, il doit la revoir ou se la répéter à intervalles réguliers et assez courts afin de la mémoriser. D'après ce que l'on a vu précédemment cela fait sens, la répétition de la perception de cette information par l'esprit va lui permettre de créer plus d'amorces et constituer des schémas mentaux. La reformulation sous forme de questions que l'on peut se poser pour tester ses connaissance permet un apprentissage plus rapide. Reformuler dans le but de réexpliquer permet également de diversifier son apprentissage [^1]

Apprentissage par l’erreur, sans elle rien ne serais possible le succès ne s’obtient qu’en résolvant des micro problèmes. N'apprennez pas par coeur, comprenez et retenez la logique derriere.

[^1]:  https://www.youtube.com/watch?v=RVB3PBPxMWg

### 1.9.12. Informatique et Éducation

Récemment le développement de l'apprentissage et les écoles adoptant la pédagogie Montessori sont un peu revenu à la mode, certains établissements ne donnent plus de notes mais des appréciations ou validations de niveau. Conformément à la pensée de Céléstin Freinet, les estrades ne sont plus, ou du moins ne servent plus à mettre le professeur en exergue, qui de toute manière se retrouve souvent à passer dans les rangs pour accompagner ou surveiller les élèves lors des examens. Bien que les compétences numérique, sociales et civiques, ainsi qu'apprendre à apprendre, fasse partie du socle commun des connaissances et des compétences, je pense qu'elles sont négligées et que l'on devrais enseigner des choses plus concrètes comme le suggérait John Dewey dans *School and Society*. J'ai du attendre l'enseignement supérieur pour avoir un cours unique de quelques heures sur la mémorisation et l'auto-formation, et je regrette que l'on ne nous indique pas quels sont les droits et aides disponibles, que l'on soit en situation précaire ou chef d'entreprise en devenir. Actuellement, l'éducation n'apprends pas aux gens à bien vivre. Imposer un programme est nécessaire pour avoir une base commune, mais les gens ont une vie à côté qui les impact positivement ou négativement dans le scolaire. Certaines compétences générales qui devraient être universelles, comme la gestion d'un budget, d'un planning, la cuisine, l'entretien d'un foyer, ou les démarches administratives élémentaires comme les déclarations d'impôts ou les demandes d'aides, ne sont transmises que par les parents ou les enseignements supérieurs spécialisés.

Or selon moi le rôle de l'éducation devrait être de faire en sorte que toute personne ayant un objectif soit capable d'elle même trouver les pré-requis nécessaires et les appliquer. De plus nous avons de formidables références nationales comme https://legifrance.gouv.fr/,  https://www.service-public.fr/ ou https://gallica.bnf.fr/ ou internationales comme https://fr.wikipedia.org et elle ne sont que peu connues ou référencées. Nul n'est censé ignoré la loi mais seuls les professionnels la lise et la connaissent. L'éducation ne doit pas fournir tout les outils existants, mais apprendre à l'élève comment trouver les outils et informations dont il aura besoin en plus de lui apprendre à apprendre, et ainsi lui indiquer comment il peut s'autoformer. L'école et l'éducation nationale n'ont pas le monopole du savoir.

Je n'ai pas encore parlé de la didactique, elle s’intéresse plus aux contenus des cours, contrairement à la pédagogie qui est la manière de les amener et de les transmettre d'un mentor à un apprenant, les deux sont complémentaires. La pédagogie possède le biais de l'Effet Dr. Fox, qui dit qu'un cours sera apprécié plus en fonction de la personnalité du professeur que du contenu du cours. Or je pense que son dernier et son architecture sont fondamentales et différents en fonction du mode de pensée et d'apprentissage des élèves, d'où l'intervention de la pédagogie pour diriger l'élève vers des exercices ou conversations adaptés à son raisonnement et lui permettant de comprendre les concepts.

Des études montrent désormais que l'apprentissage se fait mieux par la récompense que la punition.[^1] Il est plus productif d'encourager un bon comportement que d'en réprimander un mauvais, bien que cela soit parfois nécessaire, il vaut toujours mieux orienter sa pédagogie de manière positive. 

[^1]: https://www.inshs.cnrs.fr/fr/cnrsinfo/apprentissage-par-recompense-ou-par-punition-quelles-differences

Je pense que la pédagogie active et mutuelle des pédagogues contemporains est une belle utopie inspirée de Rousseau. En réalité un bon apprentissage est avant tout du ressort de l'apprenant. C'est d'ailleurs pourquoi il est au cœur de ces techniques d'apprentissages. Depuis Montaigne, l'adage "L'enfant n'est pas un vase que l'on remplit, mais un feu que l'on allume" est couramment repris. En effet, la plus forte source de motivation est intrinsèque, c'est celle qui émane de la pensée telle la conscience. Celle qui est infinie comme l'imagination. Celle dont né une volonté et satiété de savoir intarissable.

La pédagogie active et plus généralement l'autodidaxie permettent à l'élève d'être acteur de son apprentissage, il choisit ce qu’il désire apprendre, quand, et comment ; bien que cela se passe souvent par le jeu dirigé puis libre. La motivation de l'étudiant devient intrinsèque au fur et à mesure qu'on lui donne de la liberté, ce qui favorise l'autonomie, la retenue, la prise de décision, et la gestion des conflits. L'adulte ou le mentor doit n'être qu'un médiateur entre l'élève et le savoir, un guide d'apprentissage. Il doit selon moi lui faire part de ce qu'il sait vrai, le justifier, et admettre qu'il peut avoir tord. Le vrai respect ne s'obtient pas par l'autorité mais par le partage, tout en respectant la barrière sensible nécessaire à toute relation professionnelle. Il n'est pas grave de la franchir pour autant, la proximité permet une meilleur compréhension d'autrui, mais il faut savoir repartir de l'autre côté à n'importe quel moment.

Les logiciels éducatifs sont également un médium guidant l'apprentissage. Comme j'ai pu le dire précédemment, j'ai appris à lire à 2 ans et demi et sauté deux classes grâce à "Reader Rabbit, Learn to read with phonics". Je n'en suis pas un génie pour autant, et ce n'est pas pour faire preuve humilité. J'ai juste expérimenté un programme, réalisé par des développeurs qui avait une conscience de l'expérience utilisateurs, et qui pour se mettre dans la tête de leurs joueurs, ont inventé un scénario où un ordinateur, propose un vœux à une petite souris qui ne sait pas lire, retire alors l'intégralité des charactères écrits de sa ville. Le joueur doit alors retrouver les lettres de l'alphabet une part une et écouter le son qu'elles produisent, les mots qu'elles permettent de former. Guidant l'élève pour qu'il construise au fur et à mesure, à travers le jeu vidéo, des associations entre les caractères visuels, les sons et les formes qu'elles représentent dans le sens d'idées. Permettant ainsi la lecture textuelle et la compréhension qui en découle.

https://www.youtube.com/watch?v=Vl_S21D7j9w

De manière générale, le jeu développe les compétences sociales et cognitives de l'apprenti, qui n'est plus passif face à un cours qui lui est dispensé par une autorité qui sanctionne et récompense, mais découvre et s'approprie la connaissance par lui même. Bien que le jeu libre ai bien des avantages, le jeu dirigé permet de structurer l'apprentissage à l'aide d'un mentor favorisant l'acquisition de compétences, que le pédagogue transmet à ses disciples. Ce cadre réside dans l'analyse des difficultés et problèmes de l'étudiant, par la recherche des notions manquantes pour y palier, et l'élaboration d'un plan classique permettant d'y arriver, composé de cours, d'exercices, et enfin d'un examen, nécessaire à la validation individuelle de la théorie. Cette notion d'apprentissage actif "Learning by doing" se retrouve pour les langages de programmation comme avec le logiciel Rustlings ou Rust by example. Il existe d'autres langages et jeux en lignes utilisant le jeu pour faciliter l'apprentissage, parmis eux je pense notamment à Scratch, FlexboxFroggy, CodingGame, Logo.

La tablette pourrait remplacer les manuels scolaires, les cahiers, réduire les couts et le poids des cartables. Malgré le fait que certains pays l'ayant essayé ai fait marche arrière comme la Suède, je pense qu'avec un ludiciel adapté couvrant l'ensemble des matières de tout niveau à l'aide d'un arbre de compétence et gérant les communications entre les familles et les écoles, il serait possible d'harmoniser les enseignements et d'appliquer les programmes tout en réduisant le temps apprentissage. Quand j'ai appris à lire, les périphériques tactiles n'étaient pas encore démocratisés, j'avais alors un gros retard sur cette compétence. Il existe aujourd'hui multitude d'application mobiles pour apprendre à écrire. Sur une tablette possédant un stylet, un enfant peut en toute autonomie jouer pour acquérir cette habilité. Le problème et la crainte réelle des enseignants et des parent sont essentiellement la casse et le prix du renouvellement d'un tel appareil électronique accompagné des dérives liés aux possibilités illimitées d'un ordinateur pouvant distraire l'élève et le détourner de ses objectifs éducatifs. Je leur répondrais que leur rôle est d'enseigner la précaution et la discipline, l'élève pourra ainsi se charger lui même du reste. 

Enfin je terminerai avec une citation de jeu vidéo, Maitre Yi dans League Of Legends dit "*Un vrai maître est un éternel étudiant*".

###   1.9.13. Informatique et Cuisine

La cuisine est selon moi une science combinatoire et une philosophie à part entière regroupant les mathématiques, la biologie, la physique-chimie, et plein d'autres sciences y compris sociales ou neurologique. C'est un grand tout, depuis l'antiquité, les recettes sont des formulations logiques, les ingrédient sont biologiques, leurs modifications par leurs préparations, formes, mélanges, et leurs méthodes de cuissons, sont physiques, les proportions quant à elles sont mathématiques. On sait aujourd'hui scientifiquement que notre alimentation conditionne notre santé, et que notre santé peut conditionner notre alimentation. En effet, le système humain et animal à besoin d'une entrée d'énergie constante pour contrebalancer son activité physique et neuronale. Sans cela ou avec une mauvaise alimentation, il parait logique d'avoir un système défaillant. C'est la source même de la vie. Pour autant, bien que ce soit un facteur pouvant influer sur les comportements, je pense qu'en dehors de scénario très précis, les décision peuvent, si la volonté est suffisante pour cela, transcender un pseudo-déterminisme alimentaire. La cuisine à quelque chose d'universel, tout peuple de la Terre à inventé indépendamment des autres ses propres recettes, cultures, élevages, croisement d'espèces volontaire ou non. La mondialisation est venue optimiser les agriculture et permettre des échanges de nourriture et des pratiques de cultures culinaires à l'échelle de la Terre.

On sait aujourd'hui que les bactéries qui nous aident à digérer les aliments représentent une partie non négligeable de notre poids, nous vivons en symbiose avec eux à travers notre alimentation. En Informatique, et notamment en intelligence artificielle, les résultats dépendent également beaucoup des information avec lesquelles on alimente le système. Le résultat d'un algorithme, dépends des variables passées en entrée.


### 1.9.14. Communication & Compréhension

L'allégorie de la ligne ou celle de la caverne énoncée par Platon sont également la pour nous rappeler que la connaissance peut être hiérarchisée en fonction du contexte et niveau de compréhension.

Il est intéressant d'abaisser son raisonnement en utilisant une métaphore pour expliquer simplement un concept à un initié, tout comme il est important de laisser cet initié le reformuler et corroboré pour vérifier sa compréhension, c'est ainsi que l'on valide la transmission d'une information et un apprentissage, en le testant.

transparence, adéquation clarté crédibilité, réactivité

En tant que président d'une SASU Politesse, Respect et Bienveillance seront les maîtres mots de ma philosophie d'entreprise. Veiller à bien faire et bien communiquer, bien travailler, bien apprendre et retransmettre, et essayer tout les jours, malgré les hauts et les bas, de devenir un peu meilleur que la veille.



### 1.9.15. Professionnalisme

J'aimerai appliquer la dialectique à l'entreprise, avec des visioconférences 1:1

On agit tous différemment dans le contexte professionnel. Effectuer un métier n'est pas compliqué, le réaliser avec des gens l'est plus. Il faut tellement de compétences managériales qu'il nous faut. Quand je suis dans le milieu professionnel, j'exerce une fonction, ou une liste de fonctions définies par le contrat de travail.

On ne comprend l'essence des concepts qu'en généralisant et remontant au niveau du groupe social voulu. En discrétisant les information à la granularité voulue. Tolérance face à la différence entre réalité qu'on imagine et qu'on expérimente. Dans une entreprise nous somme tous concernés par rapport à un même produit. Norbert Ellias nous apprends que l'individu et la société ne sont pas deux choses séparés. On est tous responsable de nos actes quels qu'ils soient. 

De nos jours j'ai souvent entendu parler de philosophie d'entreprise. L'entreprise étant une entité morale, elle se compose d'un groupe de personnes physiques réunies pour accomplir quelque chose en commun. Ce groupe peut aussi réunir des personnes physiques et des personnes morales. Cela corresponds à une secte, qui est un terme connoté négativement mais qui, comme beaucoup de mots, est poly-sémantique, il possède plusieurs définitions, celle que l'on retient généralement n'est pas celle de la secte mais de la dérive sectaire. En effet, d'un point de vue étymologique, le mot secte provient du latin "secta", signifiant "voie que l'on suit, parti, cause, doctrine". Or quand je travaille en groupe avec d'autres personnes, je le fait de pair avec mes collègues, suivant ensemble une même voie, pendant une période définie de travail, comme tout salarié qui vends a son employeur.

En réalité, une secte, comme tout groupe d'humain agissants ensemble pour une même cause, est comme internet, la rue ou tout autre environnement dans lequel nous évoluons, c'est une indifférence, ce n'est ni bien, ni mal, cela ne dépends de ce que l'on en fait et à qu'elles fins. Nous devons tous un jour faire face au fait que nous sommes influencés et conditionnés par notre environnement et notre histoire, nos habitudes, et les groupes d'humains dans lesquels nous avons évolués. Le réel problèmes sont les dérives, notamment le fait de vénérer une autorité austère qu'on ne peut discuter, mais aussi tout les heurts qui nous sont propres. Pour le reste, la vie bats son plein et continue de parcourir le temps en faisant ce qu'elle a à faire, vivre. En réalisant EditIDE, je ne sais pas comment cet outil va être utilisé, mais je sais désormais que je veut créer des indifférences, et aller du global vers le particulier.

### 1.9.16. Prestation vs édition de logiciel

Le modèle économique d'une entreprise influence énormément les comportement de ses salariés. Contraintes de temps et de budget

Les prestataires vendent du temps, et ont donc naturellement tendance à avoir des deadline plus courtes et par conséquent plus de pression. Cela nécessite également une équipe commerciale solide capable de décrocher assez de projet pour faire travailler l'entreprise pendant les prochaines années. En contrepartie, ce n'est pas un logiciel ou site maintenable qui est demandé, mais il faut qu'il soit assez bien réalisé et fonctionnel pour être livré le plus rapidement possible afin d'en dégager une marge. 

Les éditeurs logiciels quant a eux le louent généralement en tant que service ou le vendent en tant que bien, le nerf de la guerre réside alors dans la maintenabilité du logiciel auquel doit être ajouté des fonctionnalités au fil du temps. Plus le logiciel grossit, plus il est compliqué de maitriser les effets de bord et de comprendre l'intégralité du logiciel et de son historique. Ils ont cependant la chance d'avoir conçu une sorte de distributeur automatique qui n'a pas besoin d'action humaine.

### 1.9.17. Division du travail

Charles Babbage a visité des maison d'échanges bancaires, et autres établissement de gestion, comme le bureau du cadastre qui du réaliser des cartes à jour pour établir une taxation. Il était fasciné par la division mentale du travail qui s'y opérait, la personne en charge du cadastre était le Baron Gaspard De Prony qui a également réaliser les *Grandes tables de logarithme* en seulement deux ans grâce à ses lectures des travaux d'Adam Smith, notamment de son œuvre "*Recherches sur la nature et les causes de la richesse des nations*". Ce dernier à été le premier à décrire le principe de division du travail. Ce principe sera par la suite réutilisé pour optimiser les temps de formations du personnel et de réalisation d'un produit. 

https://fr.wikipedia.org/wiki/Division_du_travail

### 1.9.18. Astrologie

Oui le mois de naissance influe sur votre vie, mais cela n'a rien à voir avec des constellations à des années lumières, mais au soleil, qui est à la base même d'une révolution de la terre autour de lui, l'année elle même. En effet les maladies sont plus présentes en hiver et peuvent affecter le bébé lors de la gestation. Croire que la position des astres dans le ciels peuvent avoir une influence sur nous est scientifiquement ridicule, surtout sachant que l'on ne sait qu'il est au centre que relativement récemment et qu'encore aujourd'hui nous ne pouvons qu'approximer les distances entre les astres.

https://www.youtube.com/watch?v=AwCq4PwCnQE

### 1.9.19. Divin

Je suis agnostique, je ne sais des Dieux s'ils sont ou pas. Je pense que l'entité qui à créé l'univers et celle qui pourrait être omnisciente ne sont pas forcement la même entité. Pour autant, je pense que le divin est omniprésent, chaque bonne action, chaque amélioration à du divin en elle. Le bien est universel, on ne doit pas faire à son prochain, ce que l'on aimerai pas qu'il nous fasse. On doit demander pardon et s'excuser pour nos erreurs. Remercier chaque personne qui nous rends biens et services. Ces morales également transmises par les textes sacrés devraient être là pour nous inspirer le bien, par pour être utilisé fanatiquement dans le but d'exposer sa vérité quelle qu'elle soit. Les sages antiques nous ont transmis la raison et la tempérance. Les philosophes modernes quand à eux, l'absence de jugement et le fait qu'il faille parfois limiter son savoir pour laisser une place à la croyance et comprendre la manière de penser des gens. Pour autant à cette période, dans le but de ce rapprocher de la vérité, les sciences prévalent sur la religion, et s'en est ainsi depuis le siècle des lumière. Science et religion ne sont pas incompatibles pour autant, bien au contraire. Le divin réside dans notre attribution de se qui est juste ou mauvais en fonction de notre système de croyance. Malgré mon manque manifeste de rigueur, j'aspire à consciencieusement suivre la science et sa logique qui nous rapproche le plus purement de l'information véritable, factuelle, démontrable par expérimentation. Depuis toujours, dans le but de se rapprocher du divin, l'humanité améliore continuellement les conditions de leurs descendants, et ce avec l'environnement et tout aléas qu'on ne peut encore y contrôler. Pour autant, on doit juger sur le pari pas le résultat, pour accéder à la raison et au savoir, le hasard doit être limité. Selon moi la vraie question à se poser face à une information douteuse serait "Est ce que c'est scientifiquement démontrable ?" Celle a se poser vis à vis d'une croyance serait quant à elle : "What if ?" autrement dit : "Que se passerai t'il si je me mettais à croire ça ?".

> "It was there noticed that the action of thought is excited by the irritation of doubt, and ceases when belief is attained; so that the production of belief is the sole function of thought."
>
> Charles S. Peirce - *How to make Ideas clear*



### 1.9.20. Effets des croyances

Une prophétie autoréalisatrice est une croyance personnelle ou une attente d'autrui qui influence positivement ou négativement nos réactions futures, ces deux effets sont appelés respectivement Pygmalion, et Golem en hommage à la mythologie grecque et juive.

La fameuse Méthode Coué, se base sur une répétition de l'Effet Pygmalion pour persuader quelqu'un ou soit même d'un évènement futur positif. Il existe également un effet Hawthorne disant que lorsqu'un sujet a conscience qu'il est testé sa motivation augmente, en effet lorsque qu'un étudiant sait qu'il à un examen en fin de séance sur le cours qui lui est prodigué, il est naturellement plus attentif.

La loi de Murphy disant que si quelque chose peut mal se passer alors cet évènement finira par arriver, est en parti de l'effet Golem, mais c'est surtout du réalisme statistique, sur un grand nombre d'essai si quelque chose a une probabilité échec, même infime, alors elle finira forcement par se produire. Enfin vient la menace du Menace du stéréotype.



Le dernier effet que je vais vous présenter est l'Effet Mathieu venant de la phrase de l'évangile selon Matthieu disant : "Car on donnera à celui qui a, et il sera dans l'abondance, mais à celui qui n'a pas on ôtera même ce qu'il a". Selon moi c'est un biais animal qui vient accentuer les inégalités, je relierai cela aux deux types de prophétie réalisatrices couplé au darwinisme social.

De manière générale, nos attentes conditionnent nos réactions.

Parmi les gens qui n'ont pas peur de la mort on retrouve ceux qui croient en la réincarnation, ou certains qui aurait consommer de la DMT, cette drogue libérée par le cerveau lors de la mort comme un dernier petit plaisir accordé par la biologie.



### 1.9.21. Intelligence

À l’heure où j’écris ça, le monde est plongé dans la mode des Intelligences Artificielles, technologie qui se base sur quelque chose de général (réseaux de neurones et systèmes pondérés), pour accumuler des informations spécifiques, afin de pouvoir répondre à des questions les concernant.

L'intelligence du latin *intellego* signifie étymologiquement capacité à percevoir et comprendre. Ce mot est intimement lié au discernement et aux choix. Elle est selon moi la capacité d'utiliser ses connaissances et sa compréhension pour s'adapter à une situation et faire un choix ou proposer une solution à un problème. 

https://fr.wiktionary.org/wiki/intelligence#:~:text=(%20XII%20e%20si%C3%A8cle)%20Emprunt%C3%A9%20au,%2C%20choisir%2C%20lire%20%C2%BB).

https://fr.wikipedia.org/wiki/Intelligence

ChatGPT n'est pas capable de raisonnement mais il fourni une solution mathématique probabiliste à un énoncé textuel. Il connais les mots qui le compose, sait qu'il y a tant de probabilité qu'ils y sont liés et les assemble de manière à proposer une réponse elle même textuelle.



Comment aurais-je pu parler d'intelligence sans parler de l'organe biologique dont elle émane, le cerveau. Environ la moitié des cellules constituant ce dernier sont des neurones, la partie restante sont les cellules de soutien dites gliales, électriquement silencieuses, voire isolantes comme la myéline. Les astrocytes font partie de cette deuxième catégorie et forment la frontière entre le système sanguin et le cerveau, assurant à ce dernier l'apport de nutriment provenant du sang et permettant à l'inverse d'évacuer les déchets du cerveaux dans le système sanguin. Des astrocytes humains ont été greffés sur des souris et celles-ci ont trouvé la sortie 2 fois plus vite que les souris "naturelles", elles jouent un rôle clé dans la mémoire et l'apprentissage, et donc dans l'intelligence. Il y'a désormais des preuves scientifiques prouvant que la biologie et la génétique influence cela, pour autant, les facteurs sont bien trop multiples, et je pense qu'il faut se concentrer sur ceux que l'on peut éthiquement contrôler, avec la certitude de bienfaits. L'intelligence est plus globale et dépend d'un environnement donné. Comme l'aurai dit Einstein, dont le cerveau à été analysé et a permit d'avancer sur les recherches portant sur les astrocytes : "on ne doit pas juger un poisson à sa capacité à grimper à un arbre". Le test de QI n'est selon moi pas représentatif de l'intelligence d'une personne, car elle n'évalue pas la capacité d'une personne à vivre au mieux possible dans son environnement. Cette intelligence se fait d'ailleurs de manière collective avec l'aide et l'accompagnement de services publics comme privés. L'intelligence est de faire les meilleures connexions entre les informations mémorisées et celles qui sont perçues à un moment T de la vie de l'individu. Elle n'est donc selon moi pas fixe, parfois on fait des choses stupides, d'autre fois brillantes, de plus un idiot peut faire semblant d'être intelligent, mais il ne le sera pas pour autant, alors que quelqu'un d'intelligent peut faire exprès d'être idiot il ne le sera que le temps de son action. Vouloir être brillant tout le temps est fade et prétentieux, mais faire de son mieux est précieux. L'intelligence humaine réside dans le chaos de la pluralité de visions du monde. L'intelligence en elle même serait selon moi un tout tendant vers un fonctionnement optimal, et dont la limite inatteignable est la perfection. 

https://www.youtube.com/watch?v=NH2sMPERT2g

https://fr.wikipedia.org/wiki/Cellule_gliale

https://fr.wikipedia.org/wiki/My%C3%A9line

https://onlinelibrary.wiley.com/doi/abs/10.1002/cne.21974

https://en.wikipedia.org/wiki/Mental_chronometry

### 1.9.22. Consciences

Je pense que l'intelligence émane du matériel de la même manière que l'information, un comportement est considéré comme intelligent lorsqu'il apporte une solution innovante, qui nous était alors inconnue. Mais pour toute personne connaissant cette dite solution, ce choix paraîtrai alors juste normal, voire idiot si on se rends compte qu'il est imparfait ou ne prends pas en compte des détails importants. 


La conscience est le fait d'analyser et comprendre une information émanant dans notre cerveau, elle ne nécessite pas forcement la perception pour autant, certaines personnes dont la vision est totalement obscurcie et qui ne sont donc pas capable de voir peuvent pour autant avoir conscience de si une lumière est allumée devant leurs yeux, on appelle ça la vision aveugle[^1]. La conscience est donc le fait d'activer une information, de la lire et d'être capable de lire d'information comme quoi on est en train de lire.

Les théories les plus récentes de la conscience disent que c'est le fait d'avoir une information disponible à un moment T pour la partager à l'ensemble des traitements du cortex cérébral. Pour autant avoir conscience d'une information ne signifie pas forcement avoir conscience de soi, ceci relève de la métacognition. 

https://www.youtube.com/watch?v=dGo5Whv-VCU
mémoire onirique

Percevoir la réalité c'est rêver de la réalité, notre conscience est limité par la réalité physique, le rêve pur n'est contraint que par notre conscience

[^1]: https://www.frcneurodon.org/comprendre-le-cerveau/a-la-decouverte-du-cerveau/la-conscience



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

Les deux vont de pair, il ne sert à rien d'être dans la précipitation, on peut être rapide mais il ne faut pas oublier la rigueur ou tenter de faires plusieurs choses à la fois. Il vaut mieux prendre une pose ou faire quelque chose pendant une attente, que d'être happer et l'oublier. Et si on doit changer de tâche, alors il faut la noter et mieux, la planifier. Malgré la planification il faut aussi accepter que tout et n'importe quoi peut arriver à n'importe quel moment dans la vie de chacun et donc savoir être indépendant, c'est également pourquoi le partage de connaissance est important en entreprise. Lors de mon alternance chez SoeMan j'ai pu participer à des réunions d'on-boarding après quoi nous réalisions des comptes rendus. De Bussac Multimedia, nous avions en plus la chance de pouvoir partager initialement des petits posts de blogs, et plus tard de présenter des diaporama et démonstrations de ce que l'on voulait dans des sessions afterwork. Actuellement chez ABGX, nous avons même tout nos vendredis après midi de dédié à un projet interne annexe de notre choix. Pour autant on ne planifie que les tâches à faire, pas exactement quand, on définit un ordre, une pile des tâches à réaliser avec des priorités et urgences. Tout les workflow de travail que j'ai pu voir ont leurs avantages et leurs inconvénients, pour autant c'est chez ABGX que j'ai retrouver ce qui personnellement me convient le plus parmi toutes mes expériences, j'ai immensément apprécié être à plein temps sur la refonte graphique de SoEMan mais je n'avais plus l'impression d'être utile dans l'avancement du logiciel à cette période, chez De Bussac au contraire, j'avais la sensation d'être en symbiose avec mon emploi du temps qui régissait mon activité professionnelle avec malgré tout un certain confort. Ce même confort qui m'a appris à prendre mon temps chez ABGX, m'apportant malgré tout une sensation de décélération qui m'a parfois frustré. Pour autant, c'est celle qui m'a remis en phase avec le travail. Dans le travail comme en voiture, il faut adapter votre vitesse à votre environnement. Même sur une piste de course comme en formule 1, les meilleures temps sont réalisés en ayant la vitesse la plus optimale dans les conditions matérielles à ce moment.

#### 1.9.26.2. Rigueur et retravail

Démarche itérative avec demande de feed-back à chaque changement, besoin de ne pas renvoyer la balle mais de demander conseil sur le moment si possible pour encore plus d'agilité. On m'a reprocher mon manque de rigueur, mais personne ne fait les choses correctement en amont de mon travail de technicien. Les cahiers des charges sont incomplets, le cahier des charges technique inexistant.

Ce qui m'agace le plus dans la rédaction des tickets, au delà du manque d'information, c'est l'information incorrecte qui pousse à suivre le déroulement indiqué pour ne pas avoir la finalité problématique décrite. On se retrouve dans l'incapacité de reproduire le problème qui nous laisse penser qu'il n'y a potentiellement pas de problème.

#### 1.9.26.3. Amélioration continue

Doute constant et remise en question en sont la clé.



#### 1.9.26.4. Standardisation & Universalité

L’uniformisation à permi d'avoir un langage commun au même titre que la logique mathématique. Le système métrique aussi

Actuellement, malgré les bonnes pratiques prônées, peu sont mises en application et beaucoup de fois je me retrouve a effectuer des copier coller avec une légère modification, alors que ma philosophie est que chaque copier coller devrait être une fonction réutilisable avec pour paramètre les variables amenées a changer ou être configurable. Cela me permet de standardiser l'ensemble de mon code et de le factoriser au plus simple.

Interopérabilité instantanée inter-appareils, édition live multiutilisateur 



#### 1.9.26.5. Do it now

J'ai souvent entendu dire "ce n'est pas ce qui est demandé ni prioritaire, on fera ça plus tard", et bien évidement, la plupart du temps cela fini par n'être jamais fait. Dans les projets informatique c'est ainsi que la dette technique s'immisce, des fonctionnalités qui s’accumulent, des développements qui s’enchaînent, et pallie aux problèmes qu'avec des corrections rapides, s’attaquant aux causes plutôt qu'aux conséquences.

Dès que l'on constate un problème, il faut avoir le réflexe de réaliser la tâche dans la foulée, ou de la planifier pour ne pas que l'information se perde. 



#### 1.9.26.6. Aide

Il n'y a jamais de mal à demander de l'aide, nous vivons dans un monde où cela demande pourtant beaucoup d'effort, hors quand on est en difficulté, c'est parfois peut être l'aide qui devrait venir à nous, et pas l'inverse.

Je me suis toujours efforcé de venir en aide ceux qui en avait vraiment besoin, pendant la période Covid j'ai héberger deux amis qui se sont retrouvés à la rue. C'était une période difficile mais je suis content d'avoir pu leur fournir un endroit neutre, avec le stricte nécessaire, du temps pour se reposer, et une oreille pour les écouter.

J'ai même parfois aider des gens qui m'avait fait des crasses à nettoyer les leurs, et je ne regrette pas, peut être que grâce à cela ils se sont rendu compte qu'ils ont agit injustement, et que la bonté transcende les mauvais actes ; et même si ce n'est pas le cas, j'ai agis, et agirais toujours selon ma morale et ce qui me semble bien.

Ce qui fait la force de l'humanité, c'est l'amitié et l'entraide, sans cela cette dernière n'aurais jamais réussi à aller aussi loin dans l'histoire. "Seul on va plus vite, ensemble, on va plus loin."



#### 1.9.26.7. STOP

Dans le monde du travail, comme personnel, il faut savoir imposer son rythme et le justifier, tout comme savoir prendre des pauses et du recul pour analyser, afin de partir dans la bonne direction plutôt que d'avancer continuellement de manière imprécise et inefficace. Il est important de prendre soin de soi avant tout, cependant, quelqu'un qui bloque sur un problème n'avance plus et peut retarder les autre également. 

On entends souvent parler de Lean Startup comme livre de référence, et il y a une notion dedans qui est rarement reprise mais que je trouve très importante, lorsqu'il y a un problème dans une chaîne de production, il est mieux de tout arrêter pour éviter qu'il n'impacte le reste. Cela permet également de trouver une solution ensemble et que tout le monde ai connaissance du problème, et ce dans un but informatif et préventif.

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
- L'expérience candidat est la première priorité dans laquelle les recruteurs prévoient d'investir pour 2022. [^1]

[^1]: https://www.codingame.com/work/fr/codingame-coderpad-tech-hiring-survey-2022/

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

Il suffit pour cela de trois composantes reparties dans trois fichiers, ou centralisé en un seul dans le cas de ce prototype. Cette étape est donc logiquement séparée en trois étapes, qui correspondent aux 3 parties d'un site web, le contenu structuré, l'habillage, et la réaction que doit avoir le site aux entrées utilisateur. Pour l'exemple je vais réaliser un site très simple, un mot, centré au milieu de l'écran, qui change lorsque l'on clique dessus.

```html
<html>
    <head>
        <!-- Script de récuperation d'une police recupérée sur https://fonts.google.com/specimen/Alice -->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Alice&display=swap" rel="stylesheet">
        
        <!-- Script d'habillage CSS -->
        <style>
            body {
                height: 100vh;
                display: flex;
                justify-content: center;
                align-items: center;
            }
            
            .inverted h1{
                transform: rotateZ(180);
            }
            
            h1 {
                font-family: 'Alice', serif;
                font-size: 15vw;
                transition: all 0.5 ease-in-out;
            }
        </style>
        <!-- Notez que j'aurais pu l'importer depuis un fichier avec un link ayant un href="/style.css" -->
    </head>
    <body>
        <h1 id="text" onclick="animate()">Bonjour</h1>
        <script>
            function animate() {
                const { body } = document;
                body.classList.toggle("inverted")
            }
        </script>
    </body>
</html>
```



##### 1.10.5.1.2. Etape 2 : ouvrir les ports

Allez dans le panneau de configuration de votre box et vous ouvrez le port qui permettent d'emmètre un site web et d'écouter les requêtes des clients en https avec le numéro 443 et en http avec le numéro complémentaire 80. 

![](.\assets\freebox.png)

##### 1.10.5.1.3. Etape 3 : mettre un serveur en service

Télécharger NGINX,

👉https://nginx.org/en/download.html



##### 1.10.5.1.4. Étape 4 : Configurer un nom de domaine (Facultative)

Première possibilité, votre box possède une IP fixe ou une option pour qu'elle le soit. Si c'est 



#### 1.10.5.2. Lancement du site au démarrage

Sur Windows il suffit de trouver le dossier Démarrage ou Startup, il est censé être situé au chemin `C://` mais la solution la plus facile pour y accéder est de faire `Windows + R` de taper `%startup%` et de valider. Vous pouvez ensuite épingler le dossier au menu d'accès rapide pour le retrouver plus facilement. Tout raccourci que vous mettez dedans sera exécuté au démarrage. Il ne manque donc plus qu'a réaliser un script avec la commande 



#### 1.10.5.3. Bureau à distance

Je suis l'heureux détenteur d'un ordinateur portable Asus Zenbook, il est très compact mais à l'inconvénient de beaucoup chauffer. À mon arrivée à Hexagone j'ai donc décidé d'acheter un mini PC et l'utiliser à distance. Pour cela, j'ai activer le bureau à distance de Windows, cela se fait très simplement dans les paramètres. Ensuite il suffit d'activer le port 3389 comme indiqué ci-dessus. Si vous le faites il faut cependant avoir un mot de passe avec assez d'entropie, pour cela il doit être assez long et contenir assez de caractères différents, incluant des minuscules, majuscules, chiffres, et caractères spéciaux. Malgré cette disposition, des botnet peuvent tenter de réaliser de multiples tentatives de connexion ou trouver une faille de sécurité dans le protocole et interférer avec votre système. Il convient donc de ne pas ouvrir le port 3389 et d'installer un VPN pour accéder au réseau local de manière sécurisée.



### 1.10.6. Comment architecturer un système d'information ?

Maintenant que l'infrastructure réseau nécessaire est en place, je vais expliquer la structure de fichiers et de dossiers que j'utilise. A la racine d'un projet logiciel, on retrouve toute sortes d'outils, qu'il convient d'organiser et de séparer dans leurs dossiers respectifs. Pour EditIDE, j'ai fait le choix d'utiliser **Cypress** pour automatiser mes tests en ayant une interface WYSIWYG ne permettant malheureusement pas l'édition, bien que fournissant des outils de sélection des éléments du site web à tester. J'ai donc un dossier contenant toutes les informations qu'il lui faut pour simuler le comportement d'un utilisateur final. J'ai également choisit d'intégrer **Docker** pour m'assurer que si le système de la personne voulant installer le projet possède des incompatibilités, alors il peut l'exécuter dans un conteneur. Cela permet également de faciliter l'installation, le seul prérequis devenant alors Docker.

Medias

2SIG Interfaces

1. Structure
2. Style
3. Interaction
4. Gestion de la donnée

La donnée est la matière première d'un système d'information, sa collecte, son stockage à un emplacement géographique. Elle peut être à l'origine de bugs, si on attends une donnée numérique et que l'on a une donnée textuelle à la place, il faut gérer le cas, autrement il y a fort à parier que cela provoquerai un plantage car on ne peut pas additionner un nombre avec une cacahuète. Il convient de tester la robustesse de ses fonctionnalités en passant toute sorte de données de différant types et longueur sans jamais que le programme ne plante. Dans la réalité, on ne teste souvent que les cas qui marchent et le jour ou le format de donnée change, on corrige le plantage avec un patch tel une rustine sur une chambre à air sans prendre en compte les autres usures de cette dernière.





### 1.10.7. Qu'elle est la plus-value d'EditIDE ?

Web builders are bad.

![](./assets/wixux.png)



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

En informatique, beaucoup d'erreurs occurrent par manque d'information ou de clarté dans leur communication, le client exprime parfois mal son besoin, voire à un problème et ne sais pas ce dont il aurait besoin pour y palier. Les équipes faisant l'intermédiaire entre le client et l'équipe de production se retrouvent souvent entre deux eaux et doivent s'adapter et apprendre deux vocabulaires très différents.

Idéalement ce genre de personnes devrait avoir été ou du moins être capable de se mettre à la place des deux partis dont il fait l'intermédiaire afin de mieux les comprendre et pouvoir efficacement communiquer dans le but de trouver la meilleure solution.

Certains problèmes arrivent également lors de l'échange entre l'équipe design et l'équipe technique.

Il arrive que des design soient validés alors qu'ils ne sont tout bonnement pas réalisable en terme de code, généralement due à des limitations CSS, ou des problèmes dues à des cas qui n'ont pas étés pensés, comme le changement de sens de lecture et d'écriture dans certains langages comme l'arabe ou le mandarin.

Tout ses problèmes arrivent car rien n'est centralisé, à une heure ou la collaboration est mise en avant comme jamais. 

Dans EditIDE, tout ce ferait sur le site lui même. Le design et l'intégration ne ferait désormais plus qu'un, les développeurs front ne seraient chargés que de dynamiser les design déjà intégrés avec les appels API du back qui seraient auto-générés. 



##### 1.10.7.0.5. Visualisation

Les sucres syntaxiques devrait être des éléments d'interface graphique. Je pense la même chose de la documentation elle devrait toujours être relié au code, lui même explicite et faisant référence a un site externe si nécessaire. Le code lui même doit être visuellement explicite, on doit pouvoir facilement créer de nouvelles instructions sans devoir choisir dans une liste d'auto-complétions interminable remplie éléments impertinents. L'intelligence artificielle peut améliorer ce problème de pertinence mais le principal désagrément vient de l'agencement et l'affichage trop brut du texte. 

Quand j'arrive dans un fichier de code, je veux savoir directement le nom des variables et fonctions qui le constitue, je me fiche d'avoir le contenu le détail ou d'entre elles, ni même leurs paramètres ou leur type de retour, bien que je doit pouvoir rechercher en fonction de ses derniers. De la même manière, quand je travaille sur une fonction je ne désire voir que ce qui concerne cette fonction.

Doit on avoir moins de fonctionnalité sur mobile ? Non, c'est l'interface qui doit changer et s'adapter à l'utilisateur.



##### 1.10.7.0.6. Documentation

La documentation permet théoriquement de répondre à toute question que l'on pourrait se poser concernant un domaine, ou dans le cas de la programmation informatique, d'un projet logiciel. Elle doit couvrir toutes les actions que doivent accomplir le développeur, de l'installation du logiciel, a son lancement, son usage, ses fonctionnalités, son code, comment contribuer et collaborer. Git permet même théoriquement, si on l'utilisait mieux, de décrire chaque action réalisée. Les instructions doivent être claires, simples, et utiliser des diagrammes au besoin. Le respect de cette documentation autant dans sa rédaction que dans sa lecture permet une amélioration de la qualité et de la sécurité de l'application.

Les API étants une boite noire, il est essentiel de les documenter, pour ce faire, le meilleur outil est actuellement swagger, il permet de regrouper des ressources web (url) dans des groupes et d'indiquer quels sont les paramètres que l'on peut y passer, et la ou les réponse attendue possibles.



Dans EditIDE, je souhaite qu'il n'y ai pas besoin de renseigner ces informations, que l'on a en théorie déjà lors de la conception et que l'on doit répéter dans swagger, généralement en utilisant un format qui plus est légèrement différant. De plus les documentations étant rarement mises à jours, elles seraient ainsi automatiquement toujours représentatives de la réalité car fortement liées. Pour EditIDE, malgré le fait que je travaille seul, je suis souvent reparti de zéro pour réexpérimenter ce que vivrai un nouveau collaborateur arrivant sur le projet, et ainsi indiquer tout les problèmes qui peuvent être recentrés et les solutions associées.  

Le formulaire de création de fonction et son interface dédiées indiqueront les champs obligatoires ou recommandés non renseignés. Recommandations gérées par ESLint.



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

5V de l'information sont volume vitesse variété véracité valeur, pour écrire ce mémoire c’est surtout le volume et la bonne variété ou proportion ainsi que la véracité qui a été au coeur de mes préoccupations



___

### 1.10.9. FOUTOIR



#### 1.10.9.1. 12 24 36 48 361248 2520=9x8x7x5

En toute humilité je sais que je peut paraître orgueilleux ou insolent, désolé si certains se sentent humiliés, j’en suis désolé, je m’en excuse.

Ma motivation est intrinsèque mais toute gratification supplémentaire est la bienvenue.

je ne me défini que par mon système de pensée, non pas par mon apparence corporelle qui me dégoute ni par mon expérience ou mes groupes sociaux


A la manière de Platon, je n'ai rien inventé, les idées sont immuables et universelles, elles n'appartiennent à personne.





https://fr.wikipedia.org/wiki/Utilisabilit%C3%A9

https://en.wikipedia.org/wiki/High_availability



#### 1.10.9.2. Philosophie

https://fr.wikipedia.org/wiki/Philosophie_de_l%27information

Philip Kindred Dick :

>  "La réalité, c'est ce qui continue d'exister lorsque l'on cesse d'y croire"

Openheimer: 

>  "Peut on le faire et doit on le faire ? On peut dire oui on peut dire non, mais pour moi. C'est mauvais de ne pas connaître si on peut connaître, c'est mauvais de ne pas savoir ce que l'on peut savoir, Ce veut dire qu'il faut préparer tout les engins toutes les techniques ou pratiques que la science permette."

C'est très difficile pour le chercheur qui fait la découverte, de savoir et de peser immédiatement, les possibilités ultérieures.

C'est le cas dans le jeu de la vie 





## 1.11. Postface : Rétrospective et métacognition

J'ai longtemps haï l'écriture et je ne l'ai que rarement pratiquée, mais désormais, j'apprécie savoir et pouvoir partager de manière claire et la plus explicite possible, mes idées et ce que je sais comme étant scientifiquement vrai. Quand j'écris ma pensée, je peut la relire comme si je m'entendais la prononcer, et ainsi la reformuler jusqu’à ce que son intention soit claire. J'ai ainsi du mal a comprendre les philosophes antiques qui auraient dit ne pas vouloir transmettre leurs pensées à l'écrit car elle ne peut alors plus se défendre elle même. Bien que rappelons le a cet époque l'imprimerie n'existe pas encore, rendant la tâche plus complexe et rebutante.

J'ai écris ce mémoire en commençant par de la prise de note puis en rédigeant, reliant petit à petit toutes les idées et concepts dont je voulais parler. En soit comme beaucoup de personnalités évoqués dans mon œuvre, je n'ai rien inventé, j'ai découvert plein d'informations et me suis contenté de les compiler à la manière de Vitruve, ou d'un ordinateur. Chaque idée ou sujet que je voulais évoquer m'as fait parcourir des dizaines d'onglets Wikipédia, et demandé des heures de recherches et de lecture pour finir par  rédiger un maigre paragraphe résumant le thème étudié aux informations que je trouvais les plus pertinentes. 

Dès que j'avais une idée ou une information qui pouvait se relier à mon mémoire, je dégainais mon téléphone, activais mon VPN pour me connecter au réseau de mon appartement et ainsi accéder à un Windows a distance. Ce dernier tourne h24 sur un mini-pc à 500 euros que j'ai acheté avant d'intégrer l'école hexagone, avec le premier salaire de mon alternance et la jolie prime obtenue pour avoir rejoint l'entreprise dès que possible un mois avant la rentrée scolaire. 

J'ai parfois rencontré des problèmes pour retrouver des informations, pour Raymond Lulle par exemple, j'ai dû récupérer la page en catalan pour mieux comprendre le lien entre Lulle et la logique combinatoire et computationnelle qui a inspiré Leibniz. En effet, certains concepts comme l'*automatic programming*, ne possède pas de page Wikipédia ni de définition en français. J'ai très souvent croiser les versions anglais et françaises des pages Wikipédia que je consultait pour être sur de la source et de la véracité des informations. J'ai également pu lire des textes historiques fantastiques comme *School and Society* de John Dewey, *How to Make Our Ideas Clear* de Charles S. Peirce ou le texte *As we may think* de Vannevar Bush, prouvant encore une fois que beaucoup d'inventions et informations qui n'était pas encore connues du grand public, était déjà accessible aux plus curieux.

Je n'ai pas pu tout garder, et j'ai du parler de personnes qui ont écris des choses ou fait des choses regrettable, j'ai pourtant parler de Lancaster qui dans lors de son enseignement a brutalisé des enfants. Rousseau disait que "Toute l'éducation des femmes doit être relative aux hommes, leur plaire, leur être utile, se faire aimer, honorer d'eux, les élever jeunes, les soigner grands, les consoler, leur rendre la vie agréable et douce. Voilà les devoir d'une femme dans tous les temps et ce qu'on doit leur apprendre dès leur enfance." car je n'ai pu valider son apparence sexiste par la lecture du texte et de son contexte. Personnellement je pense que ce genre d'injonction ne devrait pas être genré au féminin, au risque même d'en priver les Hommes dans le sens de l'humanité. De la même manière, Nicole-Claude Mathieu à déclarer que la féminité est "imposée aux femmes, et de la masculinité, apprise aux hommes", et je souhaite à tout le monde d'apprendre sans jamais se laisser imposer quoi que ce soit, n'hésitez pas à fuir, ça s'apprends également au même titre que le courage, qui n'est rappelons le, pas l'absence de peur, mais sa capacité à les gérer.



Oui, j'ai utilisé Wikipédia et ChatGPT pour écrire cet ouvrage, mais aucun texte n'en est extrait. Pourquoi ? Je tenais à rédiger moi même, comme je vous l'aurais expliqué à l'oral. Le passage sur Richard Stallman à néanmoins vu le jour grâce au modèle de génération de texte qu'est ChatGPT. J'ai voulu retrouver qui à prononcer une phrase dans le reportage : "Révoltes et révolutions technologiques | La Californie ! | ARTE"

Voici le dialogue qui en est à l'origine :



![](assets\ChatGPTRichardStallman.png)

J'ai donc découvert que OpenAI n'aurais évidement pas été racheté par Microsoft s'il avait été sous licence GNU. Et que le homebrew club à été autant fier que déçu qu'IBM lance un ordinateur commercial utilisant leur code.



J'ai écrit ce mémoire en gardant en tête que ma relation pédagogique avec le Docteur Pachon à commencé par une action provocatrice et insolence de ma part. Avec l'accord de ce dernier, j'ai rédigé ce paragraphe pour rétablir publiquement la vérité quand à ce qui c'est réellement passé et à m'excuser publiquement. En effet, l'information a été déformée. Bien qu'elle ai garder l'idée globale que la prévention est importante et qu'il vaut mieux être averti par quelqu'un de bien intentionné, au moment des faits M. Pachon ne me connait pas, il ne sait pas si l'accès non autorisé à son ordinateur n'a pas permis un grief plus important que la simple saisie du mot croissant dans la recherche Windows, qui représente réellement la seule interaction que j'ai eu avec son poste. C'est pourquoi j'ai pleinement accepté et compris non seulement sa réaction mais également sa volonté justifiée de me sanctionner. Comme je l'ai mentionner à l'oral aux gens avec qui j'ai pu en reparler et dans mon mail d'excuse, mon approche était maladroite et suite à des "dramas X" (initialement Twitter), l'officier de Gendarmerie Matthieu Audibert (https://twitter.com/MattAudibert) a rappelé que dans la loi : tout accès à "un système de traitement automatisé de données est puni de trois ans d'emprisonnement et de 100 000€ d'amende."[^1] Je ne saurais donc ni contester la loi, ni le ressenti du Docteur Pachon lors de cet évènement dont j'ai été l'acteur initial. L'éthique doit être reliée à la morale sinon elle  n'aurait pas lieu d'être.

Encore merci à tous d'être l'individu que vous êtes. Tâchez d'être encore meilleur(e)s jours après jours mais faites le et vivez pour vous-même. Pour le moment, si vous avez lu ce texte, vous faites surement parti de l'humanité.

Tant que j'y pense, voici une liste de projet qui me sont venus en tête lors de la rédaction de ce mémoire :

- Faire un autocompléteur pour une langue parlée pour la rédaction écrite
- Il existe déjà des casque de VR permettant de visualiser les zones couvertes par le wifi, imaginez un casque multisensoriel visuel qui permette a laide d'onduloanalyse de voir les temperatures, les zones radioactiactives,

Si il y'a bien quelque chose que l'on ne peut comprendre qu'en étant seul, c'est bien qu'être adulte concomite avec faire tout les jours un peu plus attention au soi de demain.

Puisque j'ai beaucoup travaillé sur l'écriture mémoire qui m'a tant appris, je finirai sur une citation de Célestin Freinet sur l'imprimerie et plus généralement sur l'écriture en tant qu'exercice pédagogique : 

> Dans la pratique, on ne se lasse jamais d’imprimer et les adultes se laissent prendre eux aussi à la minutie d’une technique qui permet la transcription en une forme magnifiée et définitive des textes auxquels on veut donner vie et harmonie. L’enfant qui compose un texte le sent naître sous sa main ; il lui donne une nouvelle vie, il le fait sien. Il n’y a désormais plus d’intermédiaire dans le processus qui conduit de la pensée ébauchée, puis exprimée, au journal qu’ils postent pour les correspondants : tous les échelons y sont : écriture, mise au point collective, composition, illustration, disposition sur la presse, encrage, tirage, groupage, agrafage. C’est justement cette continuité artisanale qui constitue l’essentiel de la portée pédagogique de l’imprimerie à l’école. Elle corrige ce qu’a d’irrationnel en éducation cette croyance que d’autres peuvent créer pour nous notre propre culture.
> *Célestin Freinet, Le journal scolaire, 1967*



[^1]: https://www.legifrance.gouv.fr/codes/id/LEGISCTA000006149839/



Je me suis retenu de partager des posts LinkedIn tels que celui-ci. https://www.linkedin.com/feed/update/urn:li:activity:7124136845021458432?updateEntityUrn=urn%3Ali%3Afs_feedUpdate%3A%28V2%2Curn%3Ali%3Aactivity%3A7124136845021458432%29



## 1.12. Table des illustrations

### 1.12.1. http://toastytech.com/guis



## 1.13. Annexes

Mon œuvre peut être vendue avec mon accord mais elle est libre et sera toujours accessible comme c'est le cas actuellement sur GitHub ! :) Si vous voulez lire cela sur un libre rien ne vous empêche d'en payer un ou concevoir un vous même.

#### 1.13.0.1. Bibliographie

Transmette - Christophe André



#### 1.13.0.2. Webographie

https://www.physique.usherbrooke.ca/~afaribau/essai/#:~:text=Les%20tables%20de%20calcul%20furent,aux%20cailloux%20selon%20leur%20position

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



https://en.wikipedia.org/wiki/Timeline_of_computing

https://en.wikipedia.org/wiki/History_of_the_graphical_user_interface

https://fr.wikipedia.org/wiki/Histoire_de_la_cryptologie

https://fr.wikipedia.org/wiki/Analogies_et_correspondances

https://fr.wikipedia.org/wiki/Philosophie_de_l%27information

https://fr.wikipedia.org/wiki/%C3%89pist%C3%A9mologie

https://fr.wikipedia.org/wiki/Th%C3%A9orie_de_la_connaissance



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



Lean Startup



https://www.amazon.fr/Building-Blocks-Teaching-Preschoolers-Special/dp/1557669678

#### 1.13.0.3. Lexique

concomitant

#### 1.13.0.4. Table des illustrations



#### 1.13.0.5. Page d’évaluation 
