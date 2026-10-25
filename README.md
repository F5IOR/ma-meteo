🌤️ Météo F5IOR - Station Météo & Assistant Drone

Application web météo mobile-first avec analyse des conditions de vol pour drone DJI Mavic Air, incluant le suivi de l'activité solaire (indice Kp) et l'estimation d'autonomie batterie.
✨ Fonctionnalités
🌡️ Météo générale

    Température actuelle & ressentie (formule Wind Chill / Heat Index)

    Humidité, pression atmosphérique et tendances

    Vent (direction, vitesse, rafales)

    Index UV et qualité de l'air (AQI)

    Cycle solaire (lever/coucher du soleil)

    Conseils vestimentaires dynamiques

    Alertes vigilance Météo-France par département

🚁 Analyse vol drone (DJI Mavic Air)

    Données réelles : vent au sol, GPS, activité solaire, indice Kp (NOAA)

    Données estimées : vent à 30/50/120m, densité de l'air, visibilité, givrage, turbulence

    Estimation autonomie batterie selon :

        Mode de vol (Normal / Sport / Cinéma / Trépied)

        Température, vent, altitude

    Impacts solaires : analyse des risques GPS/radio/fly-away selon Kp

    Statut global : ✅ SÛR / ⚠️ PRUDENCE / ⛔ DANGER

    Niveaux de confiance affichés pour chaque donnée (✔ élevé / ≈ moyen / ≈ faible)

🛠️ Technologies

    HTML/CSS/JavaScript pur (aucune dépendance)

    Interface mobile-first avec effet glassmorphism

    Stockage local (localStorage) pour mémoriser la dernière ville

🔌 APIs utilisées
API	Usage
Open-Meteo	Météo, vent, UV, précipitations, nuages, lever/coucher
OpenWeatherMap	Météo actuelle, AQI
NOAA SWPC	Indice Kp, vent solaire
api-adresse.data.gouv.fr	Géocodage inverse (département)
Opendatasoft	Vigilance Météo-France
⚙️ Configuration

    Ouvre index.html dans un navigateur moderne

    (Optionnel) Remplace la clé OpenWeatherMap dans API_KEY :
    js

    const API_KEY = "ta_cle_ici";

📱 Utilisation

    📍 Géolocalisation : bouton en haut à droite

    🔍 Recherche : champ texte ou liste de favoris

    🎮 Mode de vol : sélecteur dans le bloc drone (impacte l'autonomie calculée)

    🔄 Actualisation automatique : toutes les 10 minutes

⚠️ Avertissements

    Les données estimées (vent en altitude, autonomie, givrage…) sont indicatives

    Le pilote reste seul responsable de sa décision de vol

    Vérifiez toujours les conditions réelles sur place avant décollage

    Respectez la réglementation locale (hauteur max 120m en France)

📄 Licence

Usage personnel — libre d'adaptation.
