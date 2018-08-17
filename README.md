# AngularWebApp-PhysioClinic-3350-Swerve2018
Angular web app built using MongoDB database, Mongoose Express and Node. It is styled using Material design and Bootstrap
This project was done as part of Western University's SWE class 3350

## Video Demo Series 

https://www.youtube.com/playlist?list=PLOLGcB_bJ07gToRURf_pRdEq3psjNWqzg

## Group Members:

- Baggio, Austin 
- Chait, Noah 
- Domagala-Tang, 
- Kara, Husayn
- Madruga, Quentin
- McCauley, Connor 
- Price, Matthew

## Frameworks & enivornments

### Backend:
- Mongo w Express 
- Node.js

### Frontend:
- Angular 5

### Design Standards:
- material.angular.io

## TORUN 

### in backend

```
./rundb
mongo
npm run dev
```

### in frontend:

```
npm start
```

### Create new component
```
$ ng g component [<path>]/<name> --module app
$ ng g component <name> --module app
```


### admin login 
```
email: jimbusSupreme@gmail.com  
pass: ohboi

```

### checking and rerouting
```
// add this to the top as an import, may need to be ../../../
import { AuthManageService } from '../../services/auth-manage.service';
//add this as a variable in the ts class
token;
// add this to teh top of ngoninit()
this.token = localStorage.getItem('token');
//if only an admin should see this page, add this after the above line


```

### Sandbox accounts
| ID   | User                   | Pass             | First     | Last     |
| ---- | ---------------------- | ---------------- | --------- | ---------|
| Buy1 | davgren@selfstart.com  | sandBoxBuyAlpha  | David     | Greene   |
| Buy2 | kjaneway@selfstart.com | sandBoxBuyBeta   | Kathryn   | Janeway  |
| Buy3 | matcross@selfstart.com | sandBoxBuyGamma  | Matthew   | Cross    |
| Buy4 | gmolyn@selfstart.com   | sandBoxBuyDelta  | Gwenivere | Molyneux |

