# Welcome to your personal event feed repository!
### How is this repository generated?
This repository is *automatically generated* when you use the [event manager online app]. **Never edit this repository directly, always use the online app!** This repository is very *specifically formatted* to be readable from both the online app and the [downloadable AZA mobile app][gplay aza app]&mdash;editing it directly could cause annoying and bothersome problems problems so just don't.
### How can I edit this repository?
As previously stated, **never edit this repository directly.** Use the [online app][event manager online app] to manage your events, and it will automatically update this repository for you correctly. Please note that updates to events can take up to several minutes to show in the [online website], and several more minutes to appear in your mobile apps. *Don't freak out if you can't see your newest updates in the mobile app five seconds after you updated it online.*

You can add new events in the [add new events page] in the website, and edit, delete, and archive events in the [manage events page]. Archiving works by moving all events that are more than one day old from your rss feed and into your [archive file]. The archive file is a csv file, openable by Microsoft Excel and by Google Sheets (and most other spreadsheet editors), and stores all your events that you ever archived. **By archiving old events instead of deleting them, you create a timeline of all your events instead of deleting them forever.** Avoid deleting events when possible.
### How can I create a chapter pack?
Creating a chapter pack is very simple, and can be done with a few basic steps:

1. **Create a contact list csv file**
    
    This may seem complicated, but it really isn't. Simply use your favorite spreadsheet-editing software (such as Microsoft Excel and Google Sheets) to create your contact list, and then export your files as .csv files.
    The format for these spreadsheets should be as follows:  
    
    Name | School | Graduation Year | Address (surrounded by quotes) | Latitude | Longitude | Email | Phone number
    :----: | :------: | :---------------: | :------------------------------: | :--------: | :---------: | :-----: | :------------:
    <br />
    You ***don't*** need to add the **Longitude and Latitude**, they will automatically be added when generating the Chapter Pack using the [online website][chapter pack generation page]. **Put the google maps address to make sure it finds the contact's house.** An example csv file that you input could be:
    
     |  |   |  |  |  |  | | 
    :----: | :------: | :---------------: | :------------------------------: | :--------: | :---------: | :-----: | :------------:
    Ofek Gila | Monta Vista High School | 2017 | "4387 Bubb Rd, Cupertino, California" | | | ofekgila@outlook.com | 555555555
    James Smith | Coke Monster High | 2018 | "James Smith Way Hawaii town" | | | james.smith404@gmail.com | 555555555
    <br />
    View a more complete documentation for csv files [here][csv documentation].
2. **Generate your chapter pack from the mobile app**
    
    This step is easy&mdash;simply head over to the [chapter pack generation page], upload your csv file that you created from step 1, and hit the `Generate and download` button to download the app. **Be sure to include the words "Chapter Pack" in the name of the generated zip file for it to be recognized by the mobile app.** The generation may take a while depending on how many longitudes and latitudes it needs to fill in. For this reason, saving previously generated contact lists (generated contact lists can be found inside of the Chapter Pack zip file), and simply appending to them could save you time when generating chapter packs in the future.
    <br /><br />
3. **You're ready to go!**
    
    You're ready to start distributing your Chapter Pack to your chapter, and they will be able to load if from their [AZA app][gplay aza app]! Note they may need to go to "Settings" -> "Load Chapter Pack".

### How can I include the RSS feed in my chapter's website?
Great question! Simply go over to your [gh pages branch] and read the instructions!

<br />For more information about this repository or the web app, contact ofekgila@outlook.com

[event manager online app]:https://the-ofek-foundation.github.io/UnofficialAZAEventManager/ "event manager web app"
[gplay aza app]:https://play.google.com/store/apps/details?id=org.ramonaza.unofficialazaapp&hl=en "aza mobile app on google play"
[online website]:https://ramonaza.github.io/RamonFeed/ "the online website"
[add new events page]:https://the-ofek-foundation.github.io/UnofficialAZAEventManager/#add-events "add new events page"
[manage events page]:https://the-ofek-foundation.github.io/UnofficialAZAEventManager/#manage-events "manage events page"
[archive file]:https://github.com/ramonaza/RamonFeed/blob/master/archive.csv "archive"
[csv documentation]:https://github.com/ischeinkman/UnofficialAZAApp/wiki/Chapter-Packs#contactlistcsv "csv file documentation"
[chapter pack generation page]:https://the-ofek-foundation.github.io/UnofficialAZAEventManager/#chapter-pack "chapter pack generation page"
[gh pages branch]:https://github.com/ramonaza/RamonFeed/tree/gh-pages "gh-pages branch"
