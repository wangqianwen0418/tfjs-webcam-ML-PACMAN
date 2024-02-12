# Play Pac-Man using Gestures: Teach an ML model to read your gestures in your web browser

In this project, an ML model will predict directions from an image in web camera.
We can fine-tune a pretrained [MobileNet](https://github.com/tensorflow/tfjs-examples/tree/master/mobilenet) model  to predict 4 different classes (i.e, up, down, left, right) as defined by the user.

## How Does the Project Work
Check out the [Live Demo](https://qianwen.info/tfjs-webcam-ML-PACMAN/)

<img width="1197" alt="image" src="https://github.com/wangqianwen0418/tfjs-webcam-ML-PACMAN/assets/19774198/aab17b7a-82b7-445f-a921-d7b3337e9147">



1. **Add Example**: Use your web camera to provide example images for the four different classes (up, down, left, right).
2. **Train**: Fine-tune the ML model with these images.
3. **Play**: Start playing Pac-Man by making gestures in front of your web camera.


## Run and Develop the Project in Your Laptop

#### Preparation
- Ensure you have a code IDE like [VSCode](https://code.visualstudio.com/download) installed. VSCode is recommended, but feel free to use any IDE of your choice.
- [Install npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) on your machine.
- (If you are familar with Github) `fork` this repository, and `clone` the forked repository to your local machine. [Learn how to fork and clone](https://docs.github.com/en/get-started/quickstart/fork-a-repo).
- (If you are not familar with Github) directly download the code from this repo

#### Install npm Dependencies
1. Open the cloned project folder with VSCode.
2. Launch the VSCode integrated terminal from menu: `Terminal > New Terminal` or `View > Terminal`.
3. In the terminal, run `npm install` to install necessary npm packages (first-time setup only).

#### Run the Project
  Execute `npm run watch` in the terminal.
 
  The project will open in your default web browser.
  Any code changes will automatically update the webpage.
  Google Chrome is recommended for the development.


## Deploy to Github Page

#### 1. Build and Push
  Run `npm run deploy` in your terminal

#### 2. Configure GitHub Page

1. In your web browser, go to the forked project in your github, and select the "Settings" tab.
2. In the sidebar, under "Code and automation," choose "Pages."
3. Set up "Build and deployment" as follows:
   - Source: `Deploy from a branch`
   - Branch: `gh-pages`; Folder: `/ (root)`
4. Click "Save."

![image](https://github.com/wangqianwen0418/tfjs-webcam-ML-PACMAN/assets/19774198/8f1a2975-7fa0-4f33-83cf-5ad706d70af6)

 You can now share this demo via `https://{your_github_userid}.github.io/tfjs-webcam-ML-PACMAN/`


## Acknowledgement

This project is a modified version based on the official TensorFlow.js demos. 
For more information and additional context, visit [TensorFlow.js Demos](https://www.tensorflow.org/js/demos).
