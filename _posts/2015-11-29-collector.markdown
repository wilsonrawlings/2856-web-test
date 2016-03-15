---
layout:     post
title:      "Session #33"
subtitle:   "Focus of The Day: Ball Collector Working"
date:       2015-11-28 20:04:12
---

<h2>Ball Collector Working!</h2>

<p>Wilson and Shanti finished building the prototype of the cube collector. They tested it and it worked beautifully! They were able to pick up blocks with speed and agility. Now, Wilson is working on making the final version. He will change the size by making it smaller in every direction. He will also change the material. Before it was made out of Tetrix, and now it will be made out of 20x20 extrusion. We will keep the Tetrix belt and urethane flippers.</p>

<img src="{{ site.baseurl }}/img/post33-1.jpg" alt="collector" width="50%">
<span style="text-align: left;" class="caption text-muted">Ball Collector Working!</span>

<hr>

<h2>Going through 2856 box</h2>

<p>Gabe noticed that a lot of parts were going missing. He tasked each team with cleaning out the box of mechanisms and prototypes, because a lot of the materials in there were not being used and could be put back in their respective places. For the beginning of practice, the team went through their box.</p>

<p>We took apart everything we didn’t need. The more interesting prototypes were put to the side to save for judging or to take photos of. Because we all worked together, this didn’t take nearly as long as we thought it would.</p>

<img src="{{ site.baseurl }}/img/post33-2.jpg" alt="mess" width="50%">
<span style="text-align: left;" class="caption text-muted">Us Cleaning Up The Mess in Our Bin.</span>

<hr>

<h2>Autonomous work</h2>

<p>Isaac and Matt worked on perfecting the autonomous. They are working hard to get past the debris. They modified their center block tunnel and replaced it with two plows that move all the blocks from out under the treads. Right now they are just cardboard, but if they work, we are hoping to use polycarbonate or metal for these plows. Their largest problem right now is just moving debris so that they can line up with the correct color of the beacon and score the climbers. The autonomous is working great right now, we are just having trouble with the debris getting in the way. Once we get rid of the debris blockage, we will use our PID movement libraries to get to the beacon and image processing to determine the position of the beacon. All of these programs work great then debris is not a problem.</p>

<img src="{{ site.baseurl }}/img/post33-3.jpg" alt="auto" width="50%">
<span style="text-align: left;" class="caption text-muted">Robot On Field Working on Autonomous.</span>

<hr>

<h2>Continuing to finish notebook cover </h2>

<p>After the notebook finished printing, Wilson printed blue plastic to fill in the shapes. In order to keep them in, Wilson and Robert put hot glue on the backs of them. They used a heat gun to melt the glue and spread it around, creating a cool see through effect. Arielle and Robert finished doing this today. All the glue is finished, but the back of the front cover of our notebook has glue all over it and doesn’t look good. In the future, this has to be cleaned. Most likely, they will be putting a paper or duct tape behind the front cover to obscure the glue.</p>

<img src="{{ site.baseurl }}/img/post33-4.jpg" alt="notebook" width="50%">
<span style="text-align: left;" class="caption text-muted">Cover for new Notebook.</span>

<hr>

<h2>CADing the chassis</h2>

<p>Samin finished CAD-ing the chassis. He talked to Gerald about welding the chassis. We will send our CAD-ed file to Pack Fab and have them water jet, mill, and weld the chassis. Samin also worked on redoing some of the wiring on the robot.</p>

<hr>

<h2>Custom settings for Opmode use</h2>

<p>AJ added custom settings for us to use in our Opmode. This includes what side of the field we are on, are we starting close to the ramp or far from the ramp, how many seconds do we wait before executing the Opmode, and more.</p>

<p>He did this so the Opmode can deal with different cases on the field. In theory, we would implement this by using more than one Opmode. We’re not going to do that because we would have to scroll through a thousand different Opmodes. 9 Opmodes would do the same thing as this 1, and whenever you changed something, you would have to change everything.</p>

<p>This should show up on the phone, allowing the person using it to click what the conditions are. This program will allow us to do different things on the field without requiring us to write 9 Opmodes or lose one in a sea of others. </p>
