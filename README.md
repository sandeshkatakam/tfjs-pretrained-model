# tjs-pretrained-model

Follow the steps to reproduce the local server and load the webapp locally in your browser:  
* clone the repo to your pc using git or download the repo and extract the zip to your pc.
* **Note:** The `VGG16` Saved model format is very large to upload to github so dowload the file by clicking on this link: https://drive.google.com/drive/folders/1VXFQWeSbAbdns8dwTpY9DJfpUc3rmuIk?usp=sharing
* Then place the vgg16 downloaded folder in the local repo inside the the `tfjs` directory which is located inside `static` directory.
* Open VS COde or any other development environment and add the repo to the workspace
* open the terminal from the editor in VS Code and run the command: `npm install`
* Then to run the server use this command in the terminal: `node ./server.js`
* The command sets up the server showing the port on which the server is hosted : static serving on 81
* go to your browser and navigate to this link: http://localhost:81/predict-with-tfjs.html

