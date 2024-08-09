### NOTE: THIS IS A DRAFT AND IS WORK IN PROGRESS

---

## Stop PingTracker Abuse
This is an initiative to standardize how Among Us mods should and should not alter the PingTracker.

`Draft 3, 9th of August 2024`

## Supporters
Well-known individuals that support this initiative include:
- [Alexejhero](https://github.com/Alexejhero), Submerged developer and creator of this initiative
- [probablyadnf](https://github.com/simonkellly), Submerged developer

## Guidelines

### What is the PingTracker for?
You should only add content to the PingTracker for diagnostic or information purposes. For example, displaying the current mod name and version, displaying role information or displaying current game mode is acceptable.

**The PingTracker should not be used as a watermark or for displaying credits, especially during active gameplay.**

Here is an example of a good PingTracker patch, from our [Submerged](https://github.com/SubmergedAmongUs/Submerged) mod:

<details>
<summary>Click to view details</summary>
  
<br>
The PingTracker uses a smaller font to fit and is also displayed only when Submerged is the current map. It's only purpose is so that we can easily identify what version someone is playing if they send me a clip of a bug.
  
![](./Images/PingTracker.png)
  
</details>

### Editing guidelines
- You must ensure that the original functionality of the PingTracker remains, and not remove the ping indicator.
- Individual people or companies such as authors, developers, collaborators, etc should not be named in the PingTracker.
- You should not use a larger font size than the default for your PingTracker text, nor should you increase the overall scale of the PingTracker.
- Moving the PingTracker from the default location (bottom middle) is acceptable, but you must place it adjacent to the top or bottom edges of the screen, with no padding.

Note: While this initiative only explicitly mentions the PingTracker, creating a separate text object to display your watermark is literally the same thing and it obviously included.

### What about credits?
I acknowledge that crediting people for their work is important, however naming them in the PingTracker is a relic of the past and should not be the first solution you think about. (More info in the [Reasoning](#reasoning) section)

Having your name written on the screen at all times doesn't help you in any way, and it is also just an intrusive obstacle to both regular players, and streamers and their viewers.

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

The reason PingTracker watermarks exist in the first place is because people used to add them on mods they sold to content creators during the early days of Among Us modding. Since content creators only showed gameplay, that meant that modders would sometimes not be credited for their work unless they added their name in the PingTracker, and even so some YouTubers chose to put their face cam over them.

Now, while this is true even in the present to some extent, I think it is bad practice to modify the PingTracker for credits. If you want to use a YouTube video or Twitch stream as an example of your previous work, you do not need to have your name on there. Having the mod name is enough, and sometimes you don't even need that.

My name is written in both the credits menu of Submerged and in the repository, so I do not need to add it to the PingTracker. I can use Submerged as a past project on my resume or a reference when pitching to potential clients because I can prove that I worked on it. I don't need my name in the top right of every video and every stream to prove that.

I think that writing the mod name is obviously acceptable so people know what they're playing, but you don't need to make it bigger or increase the scale or make it flashy. It doesn't need to draw attention or take up more screen space, you don't want it to turn into a watermark.

### Final thoughts

If all you're after is credits, look around at other modding communities and you will see how they do it. 

There is no need to watermark your mod, so keep it simple, keep it minimal, and keep it small. People who care about it _will_ know who the developers are, and you will not be forgotten.

![](./Images/PingTracker-Cropped.png)
