# TodoList

Tu te souviens de la [Todolist](https://github.com/O-clock-Newton/Spe-React-E06-todolist-SoleneOclock) ?
On va refaire la même mais ce coup ci : 
- on utilise les hooks (`useState` et `useEffect`) au lieu de passer nos composants sous forme de classe
- et surtout on va faire persister nos taches en base de données !

## API back

Notre collègue de l'équipe back nous a développé une petite API en Node, pour la lancer il suffit de se placer dans le dossier `api` et de lancer la commande `yarn` puis `yarn start`.

L'API sera dispo sur l'adresse `http://localhost:3000/`

Il y a 4 endpoints qui correspondent au CRUD des taches :
- GET `/tasks`
- POST `/tasks`
- PUT `/tasks/:task_id`
- DELETE `/tasks/:task_id`

## Interface front

Ton objectif : créer une interface en React pour faire le CRUD de ces tâches 💪
- Create : créer une nouvelle tache 
- Read : voir la liste des taches
- Update : mettre à jour la valeur `done` d'une tache
- Delete : supprimer une tache

Tu peux t'inspirer de ce qu'on a fait en épisode 6 mais tu dois ajouter les échanges avec le back à chaque action.