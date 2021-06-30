# NexusModsCustomSearchEngines
Handy [Chromium browser](https://en.wikipedia.org/wiki/Chromium_(web_browser)#:~:text=builds.%5B64%5D%5B11%5D-,Browsers%20based%20on%20Chromium,-%5Bedit%5D) search URLs for games on [NexusMods](https://www.nexusmods.com/)!

This project was borne out of a desire for convenience. I found myself installing some Skyrim SE mods whenever I had a few minutes of free time. I love keyboard shortcuts, so I thought it would be nice if those mods were only a few keyboard strokes away so I wouldn't have to...open up [NexusMods](https://www.nexusmods.com/), navigate to my game, then click the search bar, then type in my search query. I figured it would be simple to throw together a custom search engine in my web browser for Nexus Mods. I was wrong. Nexus Mods and Chromium browsers don't do the best job at displaying the search query to the user, and instead displays something like 'https://www.nexusmods.com/skyrimspecialedition/search/' which isn't super helpful.

I figured since I was already digging through dev tools to get the exact search query for Skyrim SE, why not put *all* of the search URLs together in one place for *anyone* to use? That is the purpose of this project. If you are knee deep in modding a specific game, this repo should help make it trivial to add a custom search engine for all of that game's mods available on [NexusMods](https://www.nexusmods.com/) for a bit of extra convenience.

If you have no idea what any of this means, the following will function as a tutorial to add a custom search engine to your Chromium based web browser.

# How to add a custom search engine to Chromium web browsers
1. Open the browser settings
2. Locate and open **Manage search engines** in the settings menu
3. Next to the **Other search engines** header, click the **Add** button
4. Fill out the **Edit search engine** fields, example below

![Edit search engine window](https://github.com/NerdyGamerB0i/NexusModsCustomSearchEngines/blob/main/Skyrim%20Chromium%20Nexus%20Mod%20Search%20Engine%20Tutorial/1%20-%20Chromium%20Nexus%20Mod%20Search.png?raw=true)

5. Click **Save**

## But wait, what are these fields for?
**Search engine** - what will be displayed in the address bar to indicate the search engine you are using, so name it whatever is most convenient for you!

**Keyword** - whatever you want to type into the address bar to trigger the specific search engine. Since I currently only use Nexus for Skyrim SE, mine is currently set to nexus. 

**URL** - this is the most important field. It's search URL specific for NexusMods, and is what will let you execute the search *directly* from your browser's address bar. Every search URL for every [NexusMods](https://www.nexusmods.com/) game can be found [here](https://github.com/NerdyGamerB0i/NexusModsCustomSearchEngines/blob/main/Entire%20Search%20URL%20Collection.md).


### Now what?
Now that you've added a new search engine to your browser, you can simply press *CTRL-T* (new tab keyboard shortcut), type in your keyword, and you will see that you are currently searching using your new search engine.

![New search engine](https://github.com/NerdyGamerB0i/NexusModsCustomSearchEngines/blob/main/Skyrim%20Chromium%20Nexus%20Mod%20Search%20Engine%20Tutorial/2%20-%20Chromium%20Nexus%20Mod%20Search%20-%20Keyword.png?raw=true)

Next, just type in some search query that would lead you to the mod you're looking for. In my example, I used paper, because I love the [Dear Diary Menu Replacer so much](https://www.nexusmods.com/skyrimspecialedition/mods/23010)

![Searching for paper](https://github.com/NerdyGamerB0i/NexusModsCustomSearchEngines/blob/main/Skyrim%20Chromium%20Nexus%20Mod%20Search%20Engine%20Tutorial/3%20-%20Chromium%20Nexus%20Mod%20Search%20-%20Example%20Search.png?raw=true)

Hit enter, and you'll now have gone straight from your new tab directly to your search results on [NexusMods](https://www.nexusmods.com/).

![Found me some paper](https://github.com/NerdyGamerB0i/NexusModsCustomSearchEngines/blob/main/Skyrim%20Chromium%20Nexus%20Mod%20Search%20Engine%20Tutorial/4%20-%20Chromium%20Nexus%20Mod%20Search%20-%20Example%20Result.png?raw=true)

Enjoy the new ease of access to all of the mods your heart desires. **Happy Modding!**

### Addendum
- If you aren't sure if your browser is based on Chromium, here is a link to a list of [current Chromium based web browsers](https://en.wikipedia.org/wiki/Chromium_(web_browser)#:~:text=builds.%5B64%5D%5B11%5D-,Browsers%20based%20on%20Chromium,-%5Bedit%5D)

- If you come across a search URL that isn't working, just let me know so I can fix the code that pulls/constructs the URLs

- I've been really loosey goosey with the use of the term search engine, and I'm aware that this *isn't* actually a search engine per se, but that's how the browser settings refer to it so whatevs
