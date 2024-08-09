### NOTE: THIS IS A DRAFT AND IS WORK IN PROGRESS

---

## Stop PingTracker Abuse
This is an initiative to standardize how Among Us mods should and should not alter the PingTracker.

`Draft 2, 9th of August 2024`

## Supporters
Well-known individuals that support this initiative include:
- [Alexejhero](https://github.com/Alexejhero), Submerged developer and creator of this initiative
- [probablyadnf](https://github.com/simonkellly), Submerged developer

## Guidelines

### What is the PingTracker for?
You should only add content to the PingTracker for diagnostic or information purposes. For example, displaying the current mod version, displaying role information or displaying current game mode is acceptable.

**The PingTracker should not be used as a watermark or for displaying credits, especially during active gameplay.**

Here is an example of a good PingTracker patch, from our [Submerged](https://github.com/SubmergedAmongUs/Submerged) mod:

<details>
<summary>Click to view details</summary>
  
<br>
The PingTracker uses a smaller font to fit and is also displayed only when Submerged is the current map. It's only purpose is so that I can easily identify what version someone is playing if they send me a clip of a bug.
  
![](./Images/PingTracker.png)
  
</details>

### Editing guidelines
- You must ensure that the original functionality of the PingTracker remains, and not remove the ping indicator.
- Each mod should add at most _one line_ to the ping tracker, usually with the mod name and version, unless there are very special circumstances which require multiple lines.
- Individual people such as authors, developers, collaborators, etc should not be named in the PingTracker.
- You should not use a larger font size than the default for your PingTracker text, nor should you increase the overall scale of the PingTracker.
- Moving the PingTracker from the default location (bottom middle) is acceptable, but you must place it adjacent to the top or bottom edges of the screen, with no padding.

### What about credits?
The PingTracker should not be how you implement credits. Having your name plastered on the screen at all times doesn't help you in any way, and it is also just an intrusive obstacle to both regular players, and streamers and their viewers.

If you want to implement credits, you should find a different way of doing so. You can add a button to the main menu, have them displayed in the VersionShower instead, or you can come up with your own idea.

Here is an example of how we implemented credits in [Submerged](https://github.com/SubmergedAmongUs/Submerged):

<details>
<summary>Click to view details</summary>
  
<br>
We added a button in the main menu, which when clicked opens a pop-up displaying the credits.
  
![](./Images/Credits-1.png)
![](./Images/Credits-2.png)
  
</details>

### Exceptions
If you do not want to invest time in creating an alternative for displaying credits, which is understandable, you may use the PingTracker to display your credits, but _**only in the pre-game lobby**_. However, keep in mind that this is NOT preferred. 

### Reasoning
Have you ever seen a main-stream, popular mod for any other game to do this?

The reason PingTrackers exist in the first place is because people used to add them on mods they sold to content creators during the early days of Among Us modding.

After that, it just became normal to add a watermark to every mod you make.

However, watermarking in general is a bad practice, especially for open-source software, and it makes no sense in the context of a mod.

People already know they've downloaded your mod, so you don't need to display your mod's name in bold large letters. Also, frankly, most players do not really cares who the developers are. To them, it is just more meaningless text taking up screen space.

If you want your name on there for credits, find a different way of adding it. Or _at the very least_, make it not intrusive by hiding it during regular gameplay.
