### The NextJs basic app was deployed on vercel (https://rabia-app.vercel.app/) with the help of following steps. </br>
1- Go into the folder where app has to e created </br>
2- Open vscode and then terminal in it. Create project with npx create-next-app@latest --experimental-app</br>
3- Give app name, e.g., rabia-app</br>
4- Move into the app by cd rabia-app</br>
5- Now go into app folder and open page.tsx</br>
6- Delete the previously written react component and write the following code in it</br></br>

export default function Home() {</br>
 return (</br>
<div>Hello World</div></br>
 )</br></br>
 
7- Start the server by command npm run dev</br>
8- The app can be viewed at http://localhost:3000/</br>
9- To deploy this app on remote cloud of vercel, type the command npm i -g vercel to install vercel cli</br>
10- Log into vercel account through github account (or any other account of own choice)</br>
11- type vercel in cmd </br>
12- Enter ‘y’ to setup and deploy your project</br>
13- Then enter ‘n’ if you don’t want to link to an existing project</br>
14- Enter the app name and directory</br>
15- The app will be deployed on vercel</br>
