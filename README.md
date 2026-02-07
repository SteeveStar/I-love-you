# Page romantique Britanie

## Demarrage local
1. Installe les dependances:
   npm install
2. Cree un fichier `.env` a partir de `.env.example` et renseigne tes infos SMTP.
3. Lance le serveur:
   npm start
4. Ouvre http://localhost:3000

## Notes
- Le bouton "Je t'aime Steeve" affiche le texte romantique et envoie une confirmation par email.
- Le bouton "Je veux prendre plus de temps" envoie aussi une confirmation si SMTP est configure.
