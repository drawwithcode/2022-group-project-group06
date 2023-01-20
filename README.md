<p align="center">
  <img src="https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/pinklogo.png" />
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
In the second scroll the QR code is presented, inviting the users to begin their experience. Below the 'Go to the microverse' button takes the user to the archive section of the site.<br>
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

After scanning the QR code on the landing page, the user arrives at the personalization page, designed for mobile. This interface consists of the logo at the top, a phrase welcoming the new cell to the world. The cell can be customized in its color and size by pressing the screen. Another parameter that defines the appearance of the cell is the time of day: it affects the brightness of the cell's colour. In addition, the user can give it a name by filling in the name input. To send the cell to its parasite the person must shake the device.<br>
<br>

<p align=center>
<img width=150 src="https://github.com/drawwithcode/2022-group-project-group06/blob/main/links/Mobile.gif" />
</p>
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

<br>
Starting from the metaphor of microorganisms, a highly moldable generative form that could abstract that aesthetic was sought.
The chosen shape is created by overlapping distorted circles, filled in the core part and wireframed in the outer part.
A second element created are the cells of each individual user for which an aesthetic consistent with the parasite was pursued while still highlighting the hierarchical difference.
<br>
<br>
The site identity echoes the parasite aesthetic by using an organic wireframe font for the site name and icons.
The palette uses bright colors for accents and graphic elements and a neutral background.
<br>

#### Coding challenges

The main technical challenges of the code are continuous communication with the firebase realtime database and location verification to center all site content in relation to the user's location.

<br>
<br>

```Javascript
  /* send cells  */
    function submitDiametro() {
    let data = {
    name: nameInput.value(),
    startingPos: startingPos,
    creationDate: currentDate,
    incrementoBright: incrementoBright,
    cellColor: cellColor,
    cellDimension:cellDimension,
    diametro: diametro,
    lat: lat,
    lng: lng,
    acc: acc
  };

```

  <br>
  
  On the create page, the submitDiametro() function allows you to send passively taken location and date data to the database and the cell color chosen by the user.

```Javascript
/* get incoming cells */
  function getDiametro(data) {
  diametri = data.val();
  keys = Object.keys(diametri);
  // console.log("la funzione getDiametro è partita");
}
```

the getDiametro(data) function takes the data from the firebase and inserts them into an array of objects that will be called throughout the code via a for.Each loop.

```Javascript
//variables outside

/* geolocation initialization and roundup */
var locationData; //geolocation variable
let RoundUp = 0.015; //geolocation round up

//in the setup
//set laptop geolocation
laptopLat = locationData.latitude;
laptopLng = locationData.longitude;
laptopAcc = locationData.accuracy;
```

Location parameters are derived through the P5.geolocation library and rounded to create a location grid of finite values.

```Javascript
maxNoise = slider.value(); //maxNoise starting value based on a slider

stars.forEach(function (key) {
push();
translate(width / 2, height / 2); //translate everything to put it in the middle of the canvas
rotate(270); //rotate everything to match north (we don't know why we had to do this, maybe we made some formula errors before)

//variables to check every single parasite positions in the database
myLatStella = stelle[key].latStella;
myLngStella = stelle[key].lngStella;

keys.forEach(function (key) {
//variables to check every single cells in the database
let latCell = diametri[key].lat;
let lngCell = diametri[key].lng;

    //increases the size of different parasites based on nearby cells
    if (
      latCell <= myLatStella + RoundUp &&
      latCell >= myLatStella - RoundUp &&
      lngCell <= myLngStella + RoundUp &&
      lngCell >= myLngStella - RoundUp
    ) {
      singoloDiametro = 0.01 * slider.value();
      maxNoise = maxNoise + singoloDiametro;
      maxNoisenucleo = maxNoise / 2;
    }

});
```

This loop allows the parasite data to be increased in relation to the number of users accessing from the same location.

```Javascript
function checkStelle() {
fine = 0; // se cambia, finisce il ciclo

if (stars) {
stars.forEach(function (key) {
myLatStella = stelle[key].latStella;
myLngStella = stelle[key].lngStella;

      if (fine === 0) {
        if (
          laptopLat >= myLatStella - RoundUp &&
          laptopLat <= myLatStella + RoundUp &&
          laptopLng <= laptopLng + RoundUp &&
          laptopLng >= laptopLng - RoundUp
        ) {
          console.log("Your closest star is:", laptopLat, laptopLng, laptopAcc);
          starAdjustmentX = myLatStella - laptopLat;
          starAdjustmentY = myLngStella - laptopLng;
          fine = 1;
        } else {
          console.log("there's nothing here");
          starAdjustmentX = 0;
          starAdjustmentY = 0;
        }
      }
    });

}
}
}}
```

The checkStars function checks whether a parasite already exists in the vicinity and if so, adjusts the canvas display by centering all elements with reference to the position of the laptop being used.

```Javascript
function drawStella(sx, sy, scolore, stipo, sbrightness, sommacerchi) {
  stellax = sx;
  stellay = sy;
  let colore = scolore;
  let tipo = stipo;
  let brightness = sbrightness;
  let xdiff = stellax - laptopLat;
  let ydiff = stellay - laptopLng;
  let diameter = sommacerchi;
  let d = dist(
    stellax - starAdjustmentX,
    stellay - starAdjustmentY,
    laptopLat,
    laptopLng
  );
  push();
  stroke("#4d4d4d");
  strokeWeight(0.1);
  noFill();

  circle(0, 0, d * 2 * scale);
  pop();

  //blob
  push();

  let t = frameCount / starSpeed;
  if (
    (ydiff - starAdjustmentY) * scale + width / 2 > 0 &&
    (ydiff - starAdjustmentY) * scale + width / 2 < windowWidth &&
    -1 * ((xdiff - starAdjustmentX) * scale) + height / 2 > 0 &&
    -1 * ((xdiff - starAdjustmentX) * scale) + height / 2 < windowHeight
  ) {
    for (let i = n; i > 0; i--) {
      //if (ydiff*scale>0 && ydiff*scale<windowHeight){
      strokeWeight(3);
      noFill();
      step = 0.01;
      let alpha = 1 - noiseProg(i / n);
      stroke(colore, 100, brightness, 0.2);
      let size = radius + i * inter;
      let k = tipo * sqrt(i / n);
      let noisiness = diameter * noiseProg(i / n);
      blob(
        size,
        (xdiff - starAdjustmentX) * scale,
        (ydiff - starAdjustmentY) * scale,
        k,
        t - i * step,
        noisiness
      );
    }
  }
  pop();

  // nucleo
  push();
  if (
    (ydiff - starAdjustmentY) * scale + width / 2 > 0 &&
    (ydiff - starAdjustmentY) * scale + width / 2 < windowWidth &&
    -1 * ((xdiff - starAdjustmentX) * scale) + height / 2 > 0 &&
    -1 * ((xdiff - starAdjustmentX) * scale) + height / 2 < windowHeight
  ) {
    for (let i = n2; i > 0; i--) {
      let alpha = 1 - noiseProg(i / n2);
      strokeWeight(1);
      step2 = 1;
      noStroke();
      fill(colore, 100, brightness - 10, alpha);
      let size = radius + i * inter;
      let k = tipo * sqrt(i / n2);
      let noisiness = maxNoisenucleo * noiseProg(i / n2);
      nucleo(
        size,
        (xdiff - starAdjustmentX) * scale,
        (ydiff - starAdjustmentY) * scale - starAdjustmentY,
        k,
        t - i * step2,
        noisiness
      );
    }
  }
  pop();
}
```

The cells and parasites are created by a for loop that creates a series of circles deformed by noise and with color values that increase/decrease in relation to the loop.

```Javascript
function distanceKm() {
// Coordinate dei due punti
let lat1 = laptopLat;
let lon1 = laptopLng;
let lat2 = stellax;
let lon2 = stellay;

// Converte i gradi in radianti
lat1 = radians(lat1);
lon1 = radians(lon1);
lat2 = radians(lat2);
lon2 = radians(lon2);

// Formula del great-circle distance
let dlon = lon2 - lon1;
let dlat = lat2 - lat1;
let a = pow(sin(dlat / 2), 2) + cos(lat1) _ cos(lat2) _ pow(sin(dlon / 2), 2);
let c = 2 \* atan2(sqrt(a), sqrt(1 - a));

// Raggio medio della Terra (in metri)
let R = 6371e3;

// Calcola la distanza in metri
let distance = R \* c;

// Calcola la distanza in km
starDistance = round(distance / 1000);
}
```

The function distanceKm() converts latitude and longitude values to calculate the distance between points in kilometers.
(The mathematical formula was suggested by ChatGPT)

```Javascript
let cellDate = diametri[key].creationDate;

function atTime(cellDate) {
let myCellDate = cellDate;
var currentYear = year();
var currentMonth = month();
var currentDay = day();
var currentDate =
nf(currentMonth, 2) + "-" + nf(currentDay, 2) + "-" + currentYear;

const firstDate = new Date(currentDate);
const secondDate = new Date(myCellDate);

const firstDateInMs = firstDate.getTime();
const secondDateInMs = secondDate.getTime();

const differenceBtwDates = secondDateInMs - firstDateInMs;

const aDayInMs = 24 _ 60 _ 60 \* 1000;

const daysDiff = Math.round(differenceBtwDates / aDayInMs);

if (daysDiff > 8 _ daysGone) {
daysDiff = 8 _ daysGone;
}
cellOpacity = daysDiff / (10 \* daysGone);
}
```

The setTime function calculates the difference between the creation date of each cells and the current date to change the opacity of them.

#### Tools

- [p5.js](https://p5js.org/)
- [p5 Geolocation](https://github.com/bmoren/p5.geolocation)
- [Firebase Realtime Database](https://firebase.google.com/docs/database)
- [Bootstrap](https://github.com/bmoren/p5.geolocation)

## Team

- [Maria Cecilia Buonocunto](mailto:mariacecilia.bnc@gmail.com)
- [Deborah Franceschini](mailto:dfranceschini18@gmail.com)
- [Stefano Gubiolo](mailto:stefano.gubiolo@gmail.com)
- [Matteo Visini](mailto:matteo.visini.99@gmail.com)
- [Giulia Zago](mailto:giulia.zago16@gmail.com)

```

```
