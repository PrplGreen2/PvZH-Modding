### Explaining ALL files you'll most likely be working with on your journey through PvZ Heroes Modding
____
## __UABE__
This **UABE** *(Unity Asset Bundle Extractor)* .exe allows you to open and in some way modify any file you put into it.

Specifically for PvZ Heroes modding, I mainly use it to modify the **card_data, inline_text_tag and localization files**.
____
## __UABEA__
This **UABE Avalonia** .exe functions the same as UABE (some may say it's better). However, for PvZ Heroes modding in particular, I use it for **Texture and MonoBehavior editing only**.
____
## __Asset Studio__
This **Asset Studio GUI** .exe allows you to open and preview files.

Specifically for PvZ Heroes modding, I use it to **view and preview Texture files**.
____
## __card_data_187__
A file used by the PvZ Heroes .apk. Contains data of each Card in the game, including **stats, abilities, tribes, etc**.
____
## __en_305__
A localization file used by the PvZ Heroes .apk. Please note that each language has their own prefix and suffix, such as **Spanish localization being es_272**, **Italian localization being it_274**, etc.

A **localization file** is a file that contains text attached to each text string in the game. If the game was running without it (or if it was empty*), the game would display no text at all.

**It's impossible to run the game with the file COMPLETELY empty. Clearing out each and every of the text strings is what would make the game actually display no text.*
____
## __inline_text_tag_40__
A file used by the PvZ Heroes .apk. that contains all of the **Links**.

Links are the light blue underlined text nodes you can see in game in some of the Cards' ability descriptions, such as Witch's Familiar, Banana Split, Lima-Pleurodon, etc.

![image](https://github.com/user-attachments/assets/dd815519-493b-4ae2-897e-fea63e423a38)

**IMAGE:** *Example of an in-game Link*

**NOTE:** While **inline_text_tag_40** does contain the Links, it doesn't actually contain the text that shows up when you tap one. That text string is stored in the aforementioned **localization files**.

If the file was, again, empty*, the links wouldn't show and the game would instead display them as raw text.
____
## __data_assets_362__
A file used by the PvZ Heroes .apk. that contains all other parts of the game that can't be found in the aforementioned files.

Its contents include Daily Battles, Random Battles, Campaign Battles, Heroes - their Classes and what Superpowers they use, Decks used by AI or the Player alike in PvE battles, and more.
____
## __recipe_decks_32__
A file used by the PvZ Heroes .apk. that contains the data of all Strategy Decks.

![image](https://github.com/user-attachments/assets/95da48f7-7769-4e78-88d6-e3c7df24be90)

**IMAGE:** *Examples of Strategy Decks*
____
## __cards_minimalizer & cards_formatter__
These files have a very unique use which I will explain in detail in my upcoming video.

Check regularly at [my YouTube Channel](https://www.youtube.com/@SussyGren) and watch it when it's live.
