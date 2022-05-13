# Firebase-for-Web
This is example repository for Firebase for Web campaign capstone projects for GDSC Leads in India

College Bus Tracking System

Problem Statement:

Over several flight booking websites, different organisations offer differnt pricings. It takes time and efforts for users to check different websites to get best prices for flight bookings each time.

Proposed Solution :

This project proposes a “Website for brining unified results scrapping multiple flight booking websites and provide a list of prices for flights per user journey". Currently the app works for India and domestic travel only. The project's scope is to extend it for other countries and international travel to multiple countries.

<img width="1678" alt="Screenshot 2022-05-13 at 1 58 16 PM" src="https://user-images.githubusercontent.com/18289261/168243889-60f440eb-197c-42de-ae0b-9af55c17d00d.png">
<img width="1680" alt="Screenshot 2022-05-13 at 1 58 47 PM" src="https://user-images.githubusercontent.com/18289261/168243797-17225225-841b-44e3-b0d9-737376f6ed8c.png">

![image](https://user-images.githubusercontent.com/18289261/168243857-fc5085d2-2ba7-4d58-848c-46852fbd5426.png)

Angular application File / Folder Architecture summary:
package.json: consists of Node/NPM library/package/module dependencies for application development
node_modues - folder consists of all installed packages
src/main.ts - entry point to angular application. src/index.html
app/app.module.ts - route module of application
app/app.component.ts - route component of application
ng serve / npm start -> main.ts (index.html) -> app.module.ts -> app.component.ts -> (app.component.html + css)

Functionality & Concepts used :

The Website has a very simple and interactive interface which helps the users select their route flight and find its prices. Following are few Web and Firebase concepts used to achieve the functionalities in website :
<br> 
<ul><li> Components : to add header, footer, search feature in the website. Header and footer components are reused in the website. </li>
<li> Directives : Define how the view components are placed. It also describes the overall structure of the website components. </li>
<li> Databinding : Show the synchronisation between model and view. It populates the websites after mapping the model and view of each website page.
</li>
<li> Firebase Auth : To authenticate users to the website.</li>
<li> Firebase Realtime database : To add most recent prices of the flights for different routes. </li>
<li> Firebase Hosting - To host the website. </li>
</ul>

Application Link & Future Scope :

The app is currently in the Alpha testing phase for Indian users, You can access the app : [YOUR WEBSITE LINK HERE].

Once the website is fully tested and functional in India, we plan to talk to neighboring countries also to propose this app idea and collaborate with them on this flight pricing service. We aim that by next year 100,000 users in India will use FLight Best Prices Website to check out best flight prices and be aware of best prices from different websites. 
