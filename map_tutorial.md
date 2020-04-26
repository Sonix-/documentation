# How to create a map

### Getting Started
To open the map editor press the "Editor" button in the main menu or "Control + Shift + E" in the game.  
This is what you should see.  
http://img816.imageshack.us/img816/1142/screenshot2011041315195.png

### Starting, Saving, and Loading a Map
To create a new map (the editor already comes with one open smile), click "File" at the top left of your screen. You should see a drop-down list. In that list, you can see the essentials: New, Load, Save, and Save as.
http://img858.imageshack.us/img858/2913/screenshot2011041315200.png

To start a new map, click "File", then click "New".

To save a map that you are working on, click "File", and then click Save as. A window should pop up--this is where you can type in the name of your map! After saving it once, you can just hit "Save" instead. NOTE: When saving a map, make sure to add a ".map" file extension!
http://img263.imageshack.us/img263/3333/screenshot2011041317062.png

Loading a map is easy as well. Just open the "File" list again, and select "Load". A window should show up, where you can open a map that you have previously saved.

Before We Start Mapping...
You have to a little, before you actually get to the fun part! First of all, you have to add images. To do this, click "Layers" at the left-hand side of the editor. The two layers should disappear! Also, the "Layers" button has changed to "Images"! To bring them back, you can click the same button, which is now labeled "Images". Everything should revert back to normal. Now, go back to the images tab (where there were no layers), and click "Add". A nice, dark window should pop up--this is where you can select the tiles you want to use for the map. There are several different themes that come pre-packaged with Teeworlds. For example, CTF3 uses the desert theme.
http://img695.imageshack.us/img695/8022/screenshot2011041316533.png

There are 4 main themes in Teeworlds:

Grass

Jungle

Desert

Winter

For this tutorial map, we will be using "grass_main". Click on the file named "grass_main" and finish off by pressing "Add". The picture should now be at the left hand side of your editor. Now, you can go back to the layers by clicking on the "Images" tab again.
http://img688.imageshack.us/img688/856/screenshot2011041315311.png

Alright, now, you can apply the "grass_main" file to your tile layers!

Add a layer to your Game group. On the left-hand side of your screen, you should see a list of rectangles labeled "#0" and "#1" and so on. These are layers. To add a tile layer to your game group, right click the rectangle that says, "#1 Game". In that new box that appears, you can click "Add tile layer...". After that, you should see another rectangle appear: This is a tile layer.

Right click that new layer (#1 Tile), and you should see something like this.
http://img685.imageshack.us/img685/4898/screenshot2011041315461.png

Under the "Image" box, click "None" and change it to "grass_main". The reason why you can see this "grass_main" is because you added it earlier under the "images" tab.

Resizing layers is as easy as a cup of tee. To resize your Game layer, right-click #0 Game and change the width. For this map, try using 65. If the numbers move too fast, you can hold shift to make it more precise! Do the same for the "#1 Tiles" layer. Now, you can say that your map is 65 Tiles by 50 Tiles. NOTE: 1 Tile is approximately 1 tee long/tall.
http://img816.imageshack.us/img816/9429/screenshot2011041315453.png

Congrats! You have finished your pre-phase of mapping!

Where's the Fun Part? Right here.
Alright, now that you have applied images to your layers and such, we can get to the fun part. select the layer that is called "#1 Tile" and make sure it is coated red. If the layer is red, that means it is your active layer.

To pan around the map, hold control and drag around with your mouse. Drag your screen into a center area of the map, and stay there.

Hold space to show your tile selection page. When you let go, those tiles will disappear. While holding space, you can select tile(s) by clicking and dragging. After you let go of space, your cursor should show the tile you selected. Try painting it on your canvas (white box)! You have placed your first tiles!
http://img18.imageshack.us/img18/7876/screenshot2011041315553.png

To clear your brush, right click. When you do this, the tiles you have selected to paint will disappear.

Let's get serious. At the edge of the white border, the tiles you place there will continue to infinity. For example:
http://img864.imageshack.us/img864/7237/infinite.png

So you will want to paint your entire border of the map with a tile that could repeat itself with no problems. This tile is the plain brown tile. Hold space, and you should see the tile I am talking about.
http://img146.imageshack.us/img146/2531/screenshot2011041316041.png

Wait! You have to delete the old tiles first! To do this, select a blank area on your canvas. You can choose any size you want! Just click and drag. You should have a blank rectangle as your brush. Paint over those ugly tiles, and they should disappear.
http://img402.imageshack.us/img402/5416/screenshot2011041316051.png

After you border your map, it should look like this. NOTE: My map looks so small because it is zoomed out. To zoom out, scroll with the mouse wheel.
http://img192.imageshack.us/img192/3683/screenshot2011041316073.png

Go ahead and save your map. Name it, "FirstMap.map".

At the top of your editor, you can see a button labeled "1:1". This button changes your view so you can see the size of your map in game. Go ahead and click it! Things should get bigger...
http://img593.imageshack.us/img593/6130/screenshot2011041316085.png

Pan around the map using Control, and meet with the bottom left corner of your map.
Hold to get to tile select, and select a tile you want to place. This is the tile I placed for a floor:
http://img16.imageshack.us/img16/625/screenshot2011041316094.png

Draw the tile on your map. Select different tiles as needed--you're not in a rush!
You can select existing tiles on the canvas to replicated them.

Take your time to make your map a beauty. This is what you can try out.
http://img684.imageshack.us/img684/5323/screenshot2011041316133.png

Continue mapping, until you fill up your entire map. Remember: Do not place any tiles other than plain ones on the edge! Also, make a quick save!

You can use mine, if you really want to. Or if you have no imagination -_-
http://img819.imageshack.us/img819/9697/screenshot2011041316235.png

After you are done mapping the visible (*hint*) parts, you are ready for the boring part. Save first. You now have to endure making your map playable. Teeworlds uses a special thing called "Entities". They are what allows your tee to come in contact with them, and they are what allows your tee to walk on platforms. They are what kills your tee, they are what spawns your tee. They supply ammunition to you, and more. Entities are a pretty big deal.

Entities and Placing Them
The entities are cleverly hidden in the game layer (#0 Game). Select the game layer, and hold space. You can see your entities!
http://img40.imageshack.us/img40/1089/screenshot2011041316340.png

The transparent white tiles are what allows your tee to hook, walk, and collide with. In other words, they are ground and roof. These are called collisions.

The red skull is death--if you touch that tile, you die! We call these death tiles.

The tile with a hook picture is one of the fanciest--unhookable tiles! Your tee can walk on these, and collide with these. The only thing is: you can't hook them. They are often used on metal and such. These are called unhookables.

The colored tees you see at the bottom--those are spawn points. The blue tee will spawn blue team's players, and the red will spawn red team. The beige tee will be neutral--they are only activated during a DM game.

The guns... any person with an IQ above toast will be able to tell what they are for.
Those white tiles are useless. Really. They don't do anything. Don't believe me? Try it yourself.

Placing Your Entities (Quick)
Right click your #1 Tiles layer, and the menu should appear. Click "Game Tiles" and then click "Collision". Teeworlds will automatically fill your grass tiles in with collision! (If you play without collision tiles, you will fall through the ground and teeworlds will get F__Ked up.)
http://img713.imageshack.us/img713/651/screenshot2011041316570.png

So now that collisions are taken care of, you can now manually place your spawn points and weapons.

Make sure that the game layer is selected, and hold space to bring up selection. Choose a beige spawn point, and place it on the canvas. Make sure that you do not place it over a collision tile, or your tee will spawn inside the ground. Best thing to do is place it 2 tiles above the ground. Place about 5-6 of them.
http://img535.imageshack.us/img535/7169/screenshot2011041316573.png

Now that spawns are taken care of, you will want to add weapons and health. Place armor and health as you like. For spawn, health, and armor tips skip to the end (not recommended). After you finish adding weapons, armor, and health, your map is ready for playing. But do you really want to play a plain map?
http://img856.imageshack.us/img856/305/screenshot2011041316585.png

Doodads!
Time to add more images. If you remember how, add the "grass_doodads" image, and create a new layer. Make sure that new layer is 65x50! Apply the image to the layer, and you are ready.
http://img52.imageshack.us/img52/289/screenshot2011041316593.png
Move the doodads layer to the back (make it #0 Tile). Moving the layer to the back will make it appear behind your tee and the ground in game.
http://img29.imageshack.us/img29/289/screenshot2011041316593.png

Add doodads, and make sure to make your map cute and beautiful.
http://img121.imageshack.us/img121/3231/screenshot2011041317011.png

Save your map--you are almost done. Last thing you need to do is change all of the unnescessary items to high detail. Do that by right clicking on your "Doodads" layer, and chaging "detail" to yes.
http://img857.imageshack.us/img857/4079/screenshot2011041317173.png

I hope you really enjoyed this tutorial, and it helped you guys out! Thanks for reading, and [+] please!

Download for final tutorial map: Here!

Tips for Mapping
Weapon Placement

Weapon placement is a rather hard thing to accomplish unless you have been playing Teeworlds for a while.
For a 1 versus 1 map, I recommend:
0 lasers
2 grenade launchers
2 shotguns
1 katana
9 armor pieces
7 hearts (there should be a group of one somewhere..)

-Take a look at official maps for weapon and heart placement tips.

Hopefully this helped someone, if anyone, and they now know how to map. More will be added to this topic (about tips, what not to do, etc.)

Goodbye!
