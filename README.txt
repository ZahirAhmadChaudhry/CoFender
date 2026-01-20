CoFender MVP Prototype
======================

Installation & Usage
--------------------
1. Simply double-click `index.html` to open it in Chrome, Edge, Safari, or Firefox.
2. No internet is required for the logic, but an internet connection is needed to load the Fonts (Google Fonts) and the PDF.js library (CDN) the first time.

Simulated Workflow
------------------
1. **Accountant View**: The default screen. Shows a simulated history of documents.
2. **Upload**: Click "Upload New Document". You can select any file (it won't actually be uploaded anywhere).
   - Watch the fake AI analysis spinner.
   - Click "Submit to Lawyer Queue".
3. **Lawyer View**: Click "Lawyer View" in the top navigation or wait for the notification.
   - You will see the document you just "uploaded" in the queue.
   - Click "Review This".
   - You will see a SAMPLE PDF on the left (embedded in the app) and the compliance issues on the right.
   - Fill in the verdicts and comments, then click "Complete Review".
4. **Final Report**: Go back to the Accountant Dashboard. The document will now be "Finalized".
   - Click "View Report" to see the final audit summary.
   - Click "Download/Print" to simulate generating the final PDF.

Resetting Data
--------------
The app uses your browser's Local Storage to remember the "fake" documents. To clear the data:
1. Open Developer Tools (F12) -> Application -> Local Storage.
2. Clear the data.
OR
3. Open the console and type `localStorage.clear()` and refresh.

Guide Screen
------------
A new "Guide" screen has been added to the application to help users navigate the pilot features.
- Click "Guide" in the navigation bar to see the user manual and feature explanations.

================================================================================

CoFender MVP Prototype (Français)
=================================

Installation & Utilisation
--------------------------
1. Double-cliquez simplement sur `CoFender_fr.html` pour l'ouvrir dans Chrome, Edge, Safari ou Firefox.
2. Aucune connexion internet n'est requise pour la logique, mais elle est nécessaire pour charger les polices et la librairie PDF.js lors de la première ouverture.

Flux de Travail Simulé
----------------------
1. **Vue Expert-Comptable** : L'écran par défaut. Affiche l'historique des documents.
2. **Import (Upload)** : Cliquez sur "Nouveau Document". Sélectionnez un fichier (simulation).
   - Observez le scan IA simulé.
   - Cliquez sur "Envoyer à l'équipe Juridique".
3. **Espace Avocat** : Cliquez sur "Espace Avocat" dans la navigation.
   - Vous verrez le document en attente.
   - Cliquez sur "Examiner".
   - Remplissez les verdicts et validez.
4. **Rapport Final** : Retournez au tableau de bord Tableau de Bord.
   - Cliquez sur "Voir Rapport" pour voir la piste d'audit.
   - Cliquez sur "Télécharger le Certificat".

Écran Guide
-----------
Un nouvel écran "Guide" a été ajouté à l'application.
- Cliquez sur "Guide" dans la barre de navigation pour consulter le mode d'emploi.

Réinitialisation des Données
----------------------------
L'application utilise le Stockage Local (Local Storage) de votre navigateur. Pour effacer les données :
1. Ouvrez les Outils de Développement (F12) -> Application -> Local Storage.
2. Effacez les données.
OU
3. Tapez `localStorage.clear()` dans la console et actualisez.
