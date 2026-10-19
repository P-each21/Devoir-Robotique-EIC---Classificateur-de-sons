# Devoir-Robotique-EIC---Classificateur-de-sons

Ce que j’ai appris
J’ai appris à utiliser Teachable Machine pour entraîner un modèle d’intelligence artificielle capable de reconnaître trois classes de sons: le bruit de fond (Back Noise), le claquement de doigts et le sifflement. J’ai compris que le modèle apprend à partir des échantillons audio fournis afin d’identifier des caractéristiques sonores (fréquences, amplitudes) et de distinguer les différentes classes. Lors des tests avec le microphone, j’ai observé des scores de confiance très élevés (souvent 100 %) pour les sons présentés dans mes captures d’écran. Cette expérience m’a permis de comprendre que la qualité et la diversité des échantillons sonores (éviter les bruits parasites) sont importantes pour obtenir un modèle plus fiable.
Fonctionnement du programme
Le fonctionnement du projet se déroule en trois étapes. D’abord, je collecte des échantillons sonores des trois classes à l’aide du microphone, avec environ 30 échantillons par classe (8 minutes minimum au total). Ensuite, je lance l’entraînement afin que le modèle apprenne à distinguer les sons à partir des exemples fournis. Enfin, je teste le modèle en produisant différents sons devant le microphone: il analyse les ondes sonores, compare leurs caractéristiques à ce qu’il a appris et affiche un score de confiance pour chaque classe. La classe qui obtient le score le plus élevé correspond à la prédiction du modèle.

Difficultés rencontrées au programme
•	Gestion du bruit: Il a été difficile d'obtenir un échantillon de "silence" parfait, car il y avait toujours un léger bruit de fond ambiant.
•	Durée d’enregistrement: Le temps d'enregistrement par échantillon (environ 1 seconde) est court, il fallait donc être précis au moment de cliquer sur "Enregistrer".
•	Confusion des classes: Au début, le modèle confondait parfois le sifflement avec le bruit de fond, ce qui a nécessité de refaire certains échantillons pour améliorer la précision.
Lien du projet
•	Le lien du devoir : https://teachablemachine.withgoogle.com/models/lcSUt-gZv/
