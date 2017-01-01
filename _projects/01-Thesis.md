---
layout: page
title: Thesis
short_description: 3D compositing
long_description: >
  Using Nuke, Maya, and Memento to create a realistic visual effects shot.
image: /images/projects/thesis.png
featured: True
---

{% include page-title.html title="Thesis" %}

Comprehensive comparison of integrating 3D and live action elements. Using Nuke
and Maya to compare several different methods for creating a visual effect shot
in a motion picture. Chrome ball used on set to capture lighting information. 3D
environment created and composited into real footage. Photo spheres created. 3D
model created in Maya, and from photos into 3D mesh ACES workflow used to
preserve color information for a better composite. Find the limitations of how
far each method can be pushed before the shot starts to look unreal.


There are more ways than one to accomplish a task.

The scope of this project was to create a high-end visual effects shot and
compare these different methods and talk a little bit about the science behind
the shot.

I did learn a lot from this experience so there’s that. Looking back at this
project I think that I just tried to do too much.

Tutorials
1.	How to shoot a Chrome ball.

A chrome ball is typically used in High dynamic range photography. It can also
be used to capture lighting information about a scene from nearly 270 degrees.
If the ball is shot from multiple angles, (90 degree separation) then most of
the scenes radiometric energy can be represented in a 2D plane. This can be
transformed in post.
This unwrapping process can be done with software like Nuke, or
Photomatix pro 5. In Maya the equilateral map can be applied to an environment
ball to project onto geometry the lighting information.

On set the best practices for shooting a chrome ball is to fill as much of the
frame of the camera as possible while at the same time being really far away. A
long lens is best to use because this will reduce your own reflection in the ball.

Filming the ball using the same camera move really helps, because it ensures you
 are getting the lighting information from the cameras perspective. Frames can
 be extracted in post to be manipulated.

The ball is imaged at several stops above, and below normal exposure.
In Photoshop you go to automate, merge to HDR Pro and select your images. Save
it as a radiance file and import into nuke. One there you can use a spherical
transform to convert it to a lat/long map, which can then be used for reflection
maps, and environment maps. Just make sure the image is twice as wide as it is
tall. This is the aspect ration for a lat/long map.

For this project two different ball sizes were tested. The small chrome balls
were too small with my own reflection covering up too much of the ball. If there
 were longer lenses to be used it might have made a difference. The longest lens
  used on set was a 300mm lens.
The larger Chrome ball worked better with the lenses used, but it was not
perfect. The equator of the ball had a slight bulge to it and it could be
distorting the light. For this reason the ball was carefully placed when being
imaged.
The ball also had a certain ‘grain’ to it where it would cause micro distortions
 on the surface. Before using the ball a friend helped to polish it for me, and
 every time on set that it was used. When handling the chrome ball use caution
 because fingerprints will cause smudging which can distort the light.

Chrome balls are expensive; the cheap ones are cheap for a reason. The ball
purchased for this project was polished in a machine shop to be shiny.

One thing I would have like to have done is to measure the balls reflectance,
so that in post I could adjust for that.

2.	How to make a panosphere

A panosphere is a panoramic photo that includes everything around a point, of
the camera.
Two of the largest challenges in making a panosphere are time and equipment.
These panospheres can take anywhere from 3-5 hours. This process could be taken
down to 15-20 minutes with the right equipment.

The camera needs to be placed carefully on the tripod so that the entrance pupil
 of the lens spins around the same point. This means that the camera needs to be
  placed in a certain way on the tripod. Some tripods at the cage will not let
  you place the camera where it needs to be.
 Photos should be taken somewhere between 5 and 15-degree increments. Then this
 should be repeated again with the camera tilted 5-10 degrees up. Repeat again
 another 5-10 degrees upward, and again until the camera is pointing upward.
 Then repeat going below the first axis. This completes the first panosphere.
This process should be repeated for several stops above and below normal
exposure. You may begin to see how this can take a while. There are rigs out
there that will do this really fast.
This process takes a long time, but for those who want to shoot for lighting
information but do not have a chrome ball will need to use this method. In this
 case, where you do not want to choose to shoot a panosphere, you may want to go
  with the cheaper smaller chrome balls.

3.	Maya or Memento?
The original intent on this project was to compare a live action actor with a
3D model created in Maya, and a 3D model stitched from photos using Autodesk
Memento.
There was a point in the year when I was advised to stop working in maya for
the 3D actor. I just did not have enough experience modeling humans, let alone
 a realistic human model.
So the new plan is to compare the live action actor with the 3D memento model.
Memento is a great tool to add to your skill set, but it is a completely
different process. This process does not using your everyday photos. The photo
capture process can be very tedious. So much so, that I have debated whether or
 not to retitle my thesis to “Will. It. Stitch!”
Every time I tried to take photos, something would go wrong. One of the most
difficult things about this process is trying to figure out what it was that you
 did wrong. The stitching is all sent to their servers and sent back to you all
 stitched, but that does not mean it will be a good stitch.
After getting several bad stitches back I would photograph some simple object
and it would be georgeous! Just look at this wall! It was not even that many
photos. Maybe about 40 photos. Which is not much when there is a maximum of 250
photos that you can upload.
Now the frustrating thing about this process is that if you take the same set of
 photos and take one or two photos away from the set, you will get a completely
 different stitch together! If you take the same photos and reverse them you get
  a whole other stitch. So just by changing the sequence you could fix a problem
   or might make it worse.
When shooting these photos I used for the most part a Nikon D810 and shot in
raw. Unfortunately the program will not accept raw files, it is one thing that
Autodesk is working on for future releases. But in shooting raw you can make
adjustments to shadows or highlights that could potentially give you an
excellent stitch.

 The one downside to shooting in raw is you have to batch process the photos
 after making adjustments to the photos.
One thing that I have found is that when you make adjustments to the photos the
 model tends to get better, but the texture seems to get worse.
So the shooting process is a little bit intense but basically when you are on
set, here is what you do:
Step 1. Location- it works best if you shoot your subject outside with lots of
light, but not too much light.
Step 2. camera settings-you need to use a high f-stop number in order to
increase sharpness throughout the image and decrease blurry parts of the image
which will not be good for the stitch. The ISO should be set appropriately to
your lighting conditions. There is NO ZOOMING, it will not stitch, you need a
prime lens and if you want to get closer for the detail you need to physically
move forward.
Step 3. Lighting conditions- I have found that cloudy, overcast days work the
best. If the sun is out it can cause some harsh lighting and some hot spots in
the images. A silk can be used, but what I have found is that it really does not
 help much and it is better to shoot on an overcast day. In Rochester you would
 think it would be easy, but when you need it to be overcast, the sun is out.
Step 4. Shooting order-Basically you go in a circle around the subject in small
5 -10 degree increments. I recommend using a monopod because moving a tripod
takes too long. My first time shooting took about 4 hours-it didn’t stitch well.
The process of moving around, up, and down is tedious. Take a picture, move 5
inches, take a picture, move 5 inches and so on and so on.
Sometimes it helps to go back and forth.
Avoid taking pictures from one point, like you would for creating a panoramic
photo.
Taking pictures of a room, you need to go around the perimeter of the room
looking towards the center, however this really only works for large rooms and
not small hallways. Even stepping through the hallway does not work.
What is interesting to note is that sometimes being far away from the subject
stitches really well, and sometimes being close stitches well with great detail.


4.	How to Green screen

Green screening is a technique that has been around for a while and it is the
process of filming someone with a green background. In listening to several
professionals talking about visual effects, the green screen is used but not
really the way it should be. What I mean by this is that on set many will use
a green screen but not light it properly. I am actually surprised at how much
roto scoping is still heavily used in the industry. Rotoscoping is the process
of tracing an object on screen throughout a clip eliminating the background. So
if you know how to roto, then at least you will be off to a good start!
On set the goal is to light the green screen as uniformly as possible. This is a
 little difficult with the screen that we have due to the curvature in the
 screen and the discoloration of some of the parts on the screen.
The easiest way to determine whether or not the screen is uniformly lit is to
take a photo of it with your phone and increase the contrast to see what areas
need to be adjusted. Once the screen is lit you’re ready for the next step.
 The object or person of interest should be far away from the screen to reduce
 the green spillage on the subject.
Likewise the camera should be far back enough to make the green screen blurry.
This will help in post when trying to key the footage.
Backlighting the object is very helpful with the edges, and especially for hair
because it will separate it from blending into the green screen.

For this thesis project the camera was set at the same distance as it was on
location. In fact all of the settings were kept as close to the same throughout
all of the shooting days. The actor was placed so that the green screen could be
 seen from the camera throughout the move.

The most helpful thing used on set during the green screen filming was the
chrome ball. Because nearly 270 degrees can be seen in 1 2D image it was helpful
 to see where the light was and from what angles it was coming in from. A common
  technique used is to hold up and photograph your fist on location. Then later
  when on a green screen set you can try to figure out the lighting from that
  photograph.  There are cheap mirrored ball solutions out there that can be
  used for this feature. It may not be able to be used for hdr work, but it
  definitely is a great start that will help get you into it.

5.	Nuke

Nuke is a high end visual effects software that allows me to use an ACES
workflow. I am going to step through the process I took to use nuke. The first
thing I do is set up an exportation file. In this file I import all of the dpx
files and export them as a compressed file. This allows me to review the takes,
 and figure out which parts I need from each clip. Before I write each file out,
  I set it up with an aces workflow. This is the same thing I do for the
  compositing file. Going to the setting window, I change the OCIO config option
   to aces under the OCIO tab. The next thing to do is change all of the footage
    to a linear colorspace. Then in the display window, I change the
    viewerProcess to RRT (sRGB). This allows me to view footage the way that it
    should be in a linear encoded space.
It is extremely helpful to use aces in compositing. I can composite with more
accuracy and matching a 3D element to live action and different takes is much
easier.
I like to start by time shifting each clip to line up at the 0 frame. From here
I apply a basic keylight node. Then retiming the footage to make it look like
they were from the same clip. I can start to color correct the green screen
footage then give the overall shot a grade to help to blend the two clips even
further.

6.	Rendering
Rendering can take up a lot of time, and it is important to work with proxies
until the final render. This helps to speed up the workflow. Especially working
 with memento, a proxy should be rendered out to speed up the program. Nuke will
  struggle with the geometry from memento because the average mesh is huge.
  One of my own meshes was almost 3 million faces

7.	What have I learned?
If I could give advice to my younger self or any others wanting to do a
visual effects project similar to mine here are some things I would say.

1.	Use proxies
The best way to start a project like this is to start with a storyboard and
sketch out the shot.
For my project I wanted to recreate a part of the campus. The camera would go
in and out of the sky bridge focusing on my actor.

To do this I knew I needed a fairly realistic model of the campus to scale.
Starting with screenshots from Google maps I could start the 3D modeling.

I quickly discovered that those maps are not to scale and could be anywhere from
 20-50 meters off.
I started to measure parts of the campus.
I looked into LIDAR but long story short it did not work out. But it would have
been good to compare the LIDAR with actual measurements.

I ran into a lot of issues and it started to get late so I decided my best
option was to use proxies.
A Proxy is a simple shape that represents complex geometry. This can be
referenced in another file. This keeps render times short, and the workflow
quick.  
Creating a rough model of the campus did wonders for me! Using proxies allows
you to set it up for the future when you intend to model the buildings or just
give those files to other people to work on them.
I wish I started using this from the beginning. I discovered better shots and
if I had done this from the beginning I think this project could have been much
cooler.
Moral of this story: use proxies.

2.	More Proxies
I imported geometry exported from autodesk memento and this significantly slowed
 down nuke. I couldn’t even move around in the node area. If you do not want
 this to happen to you, then do not import geometry with 3 million faces into
 your comp.
Another good practice is to use low polygon geometry as a proxy. There is not
setting to change; you simply import a low-poly version of your model into nuke.
 When you have the model where you want it in the comp you can switch out the
 model with your high res version right before the final render.
Proxy Mode in nuke lets you watch a lower resolution version of your video.
This is essential when working with high quality footage, which allows you to
watch the composites in real time.
Proxy mode should not be used for techniques that require the pixel location to
 be accurate.

3.	be conscious of any quality that might be lost
Weigh your benefits and disadvantages. It may be cheaper, or it may be faster,
just be conscious of any quality that might be lost.

One of the goals of this project was to pick different workflows and test for
quality, efficiency, and speed.
A great example of this is getting high dynamic range content, lighting
profiles, and photospheres. Two ways to get this data from on set is to either
 create a photosphere at several different stops, or photograph a chrome ball
 at several different stops.
The chrome ball takes very little time on set, and captures nearly 270 degrees
 of lighting information. Photospheres are more accurate however it takes
 nearly 4 hours to capture that data with the tools we have.
There are devices that can capture photospheres faster, but they can be pricey.
This is the same problem with the chrome ball, it takes less time, but it can
get pricey. The ball I purchased has a certain grain to it and can only do so
well. Perfect chrome balls can get really expensive. There are cheaper ones out
 there, but they may not be that good. Also smaller chrome balls will not be
 the best to work with, though they may be more accurate.

4.	Storage storage storage!
Buy a large capacity external drive. I am approaching 2TB currently and this is
only a short scene.
Honestly a network drive might be the best option. This way you can keep
everything together in one place and you can access it from anywhere. However
it may slow your workflow down a bit, but it could be worth it.

Towards the end of the year I started deleting things that I know I would not
need. I would throw things onto an external drive label and date it and delete
off my computer.
Photos take up a lot of space. Especially when you try to stitch things
 together. Take a photosphere for example, the raw files could be anywhere from
  10 to 20 GB. You may think to yourself that is not a lot of space, but when
  you take 5 photospheres, that is 100GB!
The thing that really kills space, other than the raw footage from the ARRI D21
 is taking photos for Autodesk’s Memento. Each model can be a maximum of 250
 photos.  Multiply that by 50 MB and the space fills up pretty quick.

5.	Perseverance
Don’t give up, especially in times of failure. If Memento has taught me one
thing, it is perseverance.
The spring semester basically turned into a game show “will it stitch?!” I
followed the tutorials. I tried different things. I tried playing around with
the photos. Adjusting the photos. And I got failure after failure, after fail,
after fail, after fail,…..and so on.
