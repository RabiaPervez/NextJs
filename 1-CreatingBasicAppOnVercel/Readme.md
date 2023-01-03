### The NextJs basic app was deployed on vercel (https://rabia-app.vercel.app/) with the help of following steps. </br>
Go into the folder where app has to e created
open vscode and then terminal in it. Create project with npx create-next-app@latest --experimental-app
Give app name, e.g., rabia-app
move into the app by cd rabia-app
Now go into app folder and open page.tsx
Delete the previously written react component and write the following code in it

export default function Home() {
 return (
<div>Hello World</div>
 )
 
Start the server by command npm run dev
The app can be viewed at http://localhost:3000/
To deploy this app on remote cloud of vercel, type the command npm i -g vercel to install vercel cli
log into vercel account through github account (or any other account of own choice)
type vercel in cmd 
Enter ‘y’ to setup and deploy your project
Then enter ‘n’ if you don’t want to link to an existing projec
enter the app name and directory
the app will be deployed on vercel
