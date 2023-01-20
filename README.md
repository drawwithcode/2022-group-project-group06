<p align="center">
  <img src="https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/logo.png" />
</p>

## About
"Parasite" is an interactive website built on [p5.js](https://p5js.org) that reveals the origin of connections between users, placing a limit on these, which are conditioned by factors that don't permit them to be infinite and automatic.
"Parasite" was developed as part of the [Creative Coding](https://drawwithcode.github.io/) course at the Politecnico di Milano.
<br>Faculty: Michele Mauri, Tommaso Elli, Andrea Benedetti

## Table of Contents
1. [Project idea](#Project-idea)<br>
a. [Concept](#concept)<br>
b. [Metaphor](#metaphor)<br>
c. [Context of use](#context-of-use)<br>
2. [Structure](#structure)<br>
a. [Homepage](#homepage)<br>
b. [Mobile Interface](#mobile-interface)<br>
c. [Microverse](#microverse)<br>
3. [The Code](#the-code)<br>
a. [Design challenges](#design-challenges)<br>
b. [Coding challenges](#coding-challenges)<br>
c. [Tools](#tools)<br>
4. [Team](#team)<br>

## Project idea
#### Concept

Technology is often perceived as invisible and untouchable, as something surreal that connects everyone even miles away. It is considered as what brings us the most towards the metaphysical, the mystical and the abnormal. Is it possible today to subtract the magical aura around the infinite connections that occur thanks to technology?
What we wanted to create is a website that, through a simple metaphor, imposes limitations on the usual use of technology. In fact, it sets temporal and spatial barriers that condition the experience within the website: users only perceive the presence of others if they are in the same spatial coordinates. 
This is possible thanks to the collection of certain sensitive user data, in particular the gps position of anyone accessing the site is collected by the system, to trace the footprint of individual users and relate them to their neighbours. The aim is to create an engaging interactive experience to explain the complexity of the topic.

The world of Parasite consists of two subjects: parasites, which visually represent a place; and individual cells, the single user who access the website. A parasite is born only when a user creates the first cell in that specific place and it is enriched as other cells join it. When cells inhabit a parasite, they become colonies.

#### Metaphor

What has been referred to in order to communicate the need for proximity for the creation of new connections are micro-organisms. Millions of microorganisms exist around us even though we cannot see them with the naked eye. Bacterial cells undergo repeated and rapid divisions, giving rise to numerous progeny, even from few initial cells: this is how bacterial colonies are formed, aggregates of millions of billions of individuals close to the mother cell from which they are derived. Only connection with neighbouring bacteria allows the creation of colonies; the greater the association of cells, the more they will be visible to the naked eye in their macroscopic features of shape and color.

The world of Parasite consists of two subjects: parasites, which visually represent a place; and individual cells, single users who access the website. A parasite is born only when a user creates the first cell in that specific place and it is enriched as other cells join it. When cells inhabit a parasite, the two become a colony.

#### Context of use
The project is addressed to a wide audience, with no age limits; it is imagined that it will appeal especially to young people because they might be more interested in the idea of presence related to technology. 
The site can be accessed at any time, groups of people in the same place can decide to create different cells to enrich the same colony. However, a person can access it independently to find out if other users have already left their trace in that place.



## Structure
#### Homepage
![heading](https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/Intro.gif)
<br>
<br>
The homepage is designed to present the whole project in small steps. The landing page appears immediately interactive, as the movement of the background can be managed with the dynamic position of the mouse. In the centre there is the site logo, accompanied by the claim 'leave micro traces, trace macro limits', that appears with a delay of few seconds after the loading of the page. The logo is designed in order to recall the visual appearence of the central parasite. At the bottom right there is a call to action 'Go straight to the experience' that guides the user in the interaction.<br>
<br>
![homepage](https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/PrimaInterfacciaMov.gif)
<br>
<br>Starting with the first scroll, there is an initial description of what Parasite represents and what the user is going to experience.<br>
<br>
![minigame](https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/SecondaInterfaccia.gif)
<br>
<br>
 In the second scroll the QR code is presented,  inviting the users to begin their experience. Below the 'Go to the microverse' button takes the user to the archive section of the site.<br>
<br>
<br>
![minigame](https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/TerzaInterfaccia.gif)
<br>
<br>The page is completed with a navbar emerging from the background with two buttons: Microverse (a further reminder of the archive) and About. Specifically, the About section appears as an overlay on the page in bright and vivid colours and provides detailed information about the project and the team. <br>
<br>
![minigame](https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/About.gif)
<br>
<br>
#### Mobile interface
After scanning the QR code on the landing page, the user arrives at the personalization page, designed for mobile. This interface consists of the logo at the top, a phrase welcoming the new cell to the world. The cell can be customized in its color and size by pressing the screen. In addition, the user can give it a name by filling in the name input. To send the cell to its parasite the person must shake the device.<br>
<br>
<p align=center>
<img width=150 src="https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/Mobile.gif" />
</p>
<br>
<br>

#### Microverse
The 'Microverse' section is the heart of the website. In fact, it provides an overview of all the parasites that have been created so far. It is constructed in a concentric manner: in the centre the user finds the parasite corresponding to his location, around which all the others are arranged. By clicking on each individual parasite, at the bottom left reference coordinates appear informing the user of the type of parasite, where and when it was created and the owner of the first cell.<br>

![waitingroom](https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/Microverse.gif)
<br>
<br>
At the bottom right, accompained by the words 'slide to view neighbouring colonies', a zoom slider permits the user to enlarge the view of his or her own parasite. He/She arrives at his/her colony, where there are all the cells created by the different users orbiting the parasite. In this view, bottom left, the QR code appears again to invite anyone to create cells.<br>


![waitingroom](https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/colony.gif)
<br>
<br>


## The Code


#### Design challenges

#### Coding challenges



#### Tools
* [p5.js](https://p5js.org/)
* [p5 Geolocation](https://github.com/bmoren/p5.geolocation)
* [Firebase Realtime Database](https://firebase.google.com/docs/database)
* [Bootstrap](https://github.com/bmoren/p5.geolocation)

## Team
* [Maria Cecilia Buonocunto](mailto:mariacecilia.bnc@gmail.com)  
* [Deborah Franceschini](mailto:dfranceschini18@gmail.com)
* [Stefano Gubiolo](mailto:stefano.gubiolo@gmail.com)  
* [Matteo Visini](mailto:matteo.visini.99@gmail.com)
* [Giulia Zago](mailto:giulia.zago16@gmail.com)
