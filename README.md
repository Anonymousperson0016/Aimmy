<div align="center">
  <p>
    <a href="https://google.com/" target="_blank">
      <img width="100%" src="https://raw.githubusercontent.com/MarsQQ/Aimmy/master/readme_assets/AimmyBanner.png"></a>
  </p>

Aimmy is a multi-functional AI-based Aim Aligner that was developed by BabyHamsta & Nori for the purposes of making gaming more accessible for a wider audience.

Aimmy differentiates itself from similar tools by being incredibly performant, especially on both NVIDIA and AMD GPUs, extremely customizable, and source-available.

## Table of Contents
[What is the purpose of Aimmy?](#what-is-the-purpose-of-aimmy) | [How does Aimmy Work?](#how-does-aimmy-work) | [Setup](#how-does-aimmy-work) | [Features](#features) | [Setup](#setup) | [How is Aimmy better than similar AI-Based tools?](#how-is-aimmy-better-than-similar-ai-based-tools) | [What is the Web Model?](#what-is-the-web-model) 



## What is the purpose of Aimmy?
### Aimmy was designed for Gamers who are at a severe disadvantage over normal gamers.
### This includes but is not limited to:
- Gamers who are physically challenged
- Gamers who are mentally challenged
- Gamers who suffer from untreated/untreatable visual impairments
- Gamers who do not have access to a seperate Human-Interface Device (HID) for controlling the pointer
- Gamers trying to improve their reaction time
- Gamers with poor Hand/Eye coordination
- Gamers who perform low in FPS games

## How does Aimmy Work?
Aimmy works by using AI Image Recognition to detect opponents, pointing the player towards the direction of an opponent accordingly. 

The gamer is now left to perform any actions they believe is necessary.

Additionally, a Gamer that uses Aimmy is also given the option to turn on Auto-Trigger. Auto-Trigger relieves the need to repeatedly tap the HID to shoot at a player. This is especially useful for physically challenged users who may have trouble with this action.

## Features
- AI Aim Aligning
- Aim Keybind Switching
- Adjustable FOV, Mouse Sensitivity, X Axis, Y Axis, and Model Confidence
- Auto Trigger and Trigger Delay
- Hot Model Swapping (No need to reload application)
- Image capture while playing (For labeling to further AI training)

## Setup
- Download and Install the x64 version of [.NET Runtime 7.0.X.X](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
- Download Aimmy from [Releases](https://github.com/MarsQQ/Aimmy/releases) (Make sure it's the Aimmy zip and not Source zip)
- Extract the Aimmy.zip file
- Run Aimmy.exe
- Choose your Model and Enjoy :)

## How is Aimmy better than similar AI-Based tools?
Our program comes default with 2 AI models, 1 game specific (Phantom Forces) and 1 universal model. We also let users make their own models, share them, and switch between them painlessly. This makes Aimmy very versatile and universal for thousands of games.
![Example of Model switching](https://external-content.duckduckgo.com/iu/?u=https://i.imgur.com/4GYUhyp.gif)

We also provide better performance across the board compared to other AI Aim Aligners. Detecting opponents in milliseconds across the board on most CPUs & GPUs.

Aimmy comes pre-bundled with a well-designed user interface that is beautiful, and accessible. With many features to customize your personal user experience.

## What is the Web Model
The web model is a TFJS (TensorFlow Javascript) export of the model. This allow you to use the model for image labeling, which then images can be sent to us to help further train the PF/Universal model or you can use those images to train your own YOLOv8 model.
You may wonder, "Why is it in YOLOv5 and not YOLOv8?". This is due to us using the tool called MakeSense, it to me is one of the easiest tools and is all web based. I am sure there are other tools that may accept the YOLOv8 web model.

You can visit MakeSense here: https://www.makesense.ai
You then can simply load all of your images in and select Object Detection.

![image](https://github.com/MarsQQ/Aimmy/assets/22938086/35046774-b70b-4264-8c26-eba5fe0b6b9e)


Then run the AI locally, select YOLOv5, and upload all the web model files.

![image](https://github.com/MarsQQ/Aimmy/assets/22938086/78e6329d-0b55-453e-baf1-47186020b2b8)
![image](https://github.com/MarsQQ/Aimmy/assets/22938086/0f13a664-0d0e-41aa-84b2-9d7f96daea1c)
![image](https://github.com/MarsQQ/Aimmy/assets/22938086/f0896522-954d-4120-926f-b691673c802a)


You can now go through your images and click and drag to highlight any Enemies on screen and approve the auto detected enemies from the web model:

![image](https://github.com/MarsQQ/Aimmy/assets/22938086/f1288009-5e7a-4360-a1c5-bee9faf7f387)

Once you are finished labeling you'll want to export the labels for AI training:

![image](https://github.com/MarsQQ/Aimmy/assets/22938086/1af932c3-adde-4138-86f5-1c59934afae7)
![image](https://github.com/MarsQQ/Aimmy/assets/22938086/05cc8837-8131-4035-897c-722301a0233b)

</div>
