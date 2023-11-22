# Play Pacman via the Webcam: Teach an ML model to read gestures

In this project, an ML model will predict direction from an image in webcam using transfer
learning.

We can use a pretrained [MobileNet](https://github.com/tensorflow/tfjs-examples/tree/master/mobilenet) model and train another model
using an internal mobilenet activation to predict 4 different classes (i.e, up, down, left, right) from the webcam defined by the user.

[See this example live!](https://qianwen.info/tfjs-webcam-ML-PACMAN/)


## Run and Develop the Project in Your Laptop

### Preparation
- You need a code IDE such as [vscode](https://code.visualstudio.com/download) installed in your laptop. I highly recommend vscode but you should feel free to use whatever IDE you prefer.
- Have a [github](http://github.com) account, `fork` this project to your github and `clone` the forked project to your laptop. [How to fork and clone](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
- Install [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) to your laptop.


### install npm dependency
Use vscode to open the folder of the cloned project.

Open the integrated terminal using either the `Terminal > New Terminal` or `View > Terminal` in the menu.

In terminal, run the command below to install npm packages.
```npm install```
you only need to run the comand the first time

then run
```npm run watch```
The project will automatically open in your web browser.

every time you change code in the vscode, the webpage will automatically updated after refresh.


## Deploy to Github Page

### 1. Configure GitHub Pages


In your web browser, navigate to the GitHub repository, click on the tab labeled "Settings".
In the sidebar, in the "Code and automation" section, click on "Pages"
Configure the "Build and deployment" settings like this:
- Source: Deploy from a branch
- Branch: gh-pages; Folder: / (root)  

Click on the "Save" button.

### 2. Deploy
```npm run deploy```