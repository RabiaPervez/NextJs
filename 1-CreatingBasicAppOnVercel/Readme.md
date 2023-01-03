### The NextJs basic app was deployed on vercel (https://rabia-app.vercel.app/) with the help of following steps. </br>
Go into the folder where app has to e created </br>
open vscode and then terminal in it. Create project with npx create-next-app@latest --experimental-app</br>
Give app name, e.g., rabia-app</br>
move into the app by cd rabia-app</br>
Now go into app folder and open page.tsx</br>
Delete the previously written react component and write the following code in it</br></br>

export default function Home() {</br>
 return (</br>
<div>Hello World</div></br>
 )</br></br>
 
Start the server by command npm run dev</br>
The app can be viewed at http://localhost:3000/</br>
To deploy this app on remote cloud of vercel, type the command npm i -g vercel to install vercel cli</br>
log into vercel account through github account (or any other account of own choice)</br>
type vercel in cmd </br>
Enter ‘y’ to setup and deploy your project</br>
Then enter ‘n’ if you don’t want to link to an existing project</br>
enter the app name and directory</br>
the app will be deployed on vercel</br>
