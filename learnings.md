# learnings

A documentation about my learning during the process of creating this resident like game menu for the web from scratch.

## Illustrator

- Deselect view->Snap to Pixel for making working with paths easier
- When using the path tool holding the left key can created curves. It will continue to push curved lines on you. Pressing `ESC` will discontinue this behaviour. Then clicking `ALT` left click on the last anchor point will allow you to continue with a straight line from there on.
- The direct selection tool `a` can be used to alter specific anchor points manually
- The smoothing tool can be used to hand draw and smooth out specific curves that are not shaped well
- You can switch to the outline/preview/wireframe mode with `CTRL + Y` which can be used to check angles of different parts against each other and make them uniform
- Duplicate elements by dragging them and pressing `ALT`
- When more space around the illustration is needed use view->hide artboard bounds
- Send selected objects into the background/foreground with object -> send to back
- To use textures you can download a texture background image from unplash, open it in photoshop use `CTRL + U` and get rid of all saturation, then use `CTRL+L` and put all three levels right on top of each other within the gaussian bell curve and thus extract the shadows and highlights of the texture image only. Then this can be brought into illutrator by simple select -> all and copy paste. To further use this texture in illustrator it needs to be vectorized.
- Vectorizing images can be achieved by window -> image trace. Turn on the preview. Pull the level to the right to bring in more details. When finished use object -> expand and click okay to vectorize it. Then cut the image. Open a new image 1920x1080 and paste the vectorized image. Here the white-value can be removed. Use the magic wand tool and click in the black to select everything there. Then cut it out. Paste it back into the working file and change the color to your liking. Often you need to enable RGB by clicking on the color settings burger menu. Then go to settings for pathfinder and click unite to bring all individual vectors into one vector texture asset. THen select the united element and go to object->compoung mask -> make `CTRL + 8` only then it will be one single object.
- After that an icon/illustration can be selected or duplicated to apply the texture on it. First it needs to be object -> expand again not kind of render it. Now it cant be edited anymore. Go into outline mode `CTRL + Y` and check for groupings and paths. If your illustation is just one path that is great. Everthing that is not one path needs to be united through settings and then used object -> compound path -> make `CTRL + 8` so all are treated as one path.
- Then leave outline mode and overlay/scale the texture on top of the illustration. Then use the color picker tool to make the texture the same color as the background. If the texture is not on top it needs to be brought in front of the layers through object -> arrange -> bring to front.
- Then the illustration outline can be selected through the selection tool `V` and the settings -> minus front (next to unite) can be used to just keep the texture within the illustration and delete it everywhere else.
- There is also an even easier way to achieve this result when the illustration owns multiple colors. Simply select the whole illustration and make it a compound path `CTRL + 8`. Then overlay the texture. Then select with the selection tool the texture and the illustration path. Then use in the settings minus front. Now the texture is applied to the whole illustration but the color of elements is lost. Simply use the direct selection tool `A` to select all parts which should be colored and use the color of your liking. Even when the whole illustration is one compuond path this tool is able to select subelements of it and bring back in color.
