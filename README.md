# PlayniteRevisitedSkin
It's just a [Playnite](https://playnite.link) default Fullscreen skin with some modifications inspired by [PlayOS](https://github.com/Deytron/PlayOS) and [DH_Blur](https://github.com/felixkmh/DH_Themes/tree/main/source/Blur).

This skin supports these extensions :
- [BackgroundChanger](https://github.com/Lacro59/playnite-backgroundchanger-plugin)
- [Extra Metadata Loader](https://github.com/darklinkpower/PlayniteExtensionsCollection)
- [Back to Game](https://github.com/ashpynov/BackToGame)

## Main :

![Main](https://raw.githubusercontent.com/ld892012/PlayniteRevisitedSkin/main/Media/Main.png)

## Details View :

You can use a simple background image with a logo included :
![Detail](https://raw.githubusercontent.com/ld892012/PlayniteRevisitedSkin/main/Media/Detail_BB-CB.png)

Or use a Clear background and add a logo :
![Detail](https://raw.githubusercontent.com/ld892012/PlayniteRevisitedSkin/main/Media/Detail_CB-LL.png)
For adding a logo, you can use :
- Extra Metadata Loader's Logo (requires Extra Metadata Loader)
- Place manually your Logo in `<Playnite configuration path>\ExtraMetadata\<Game database Id>\Logo.png` (requires manual folders creation)
- Use Playnite Icon media field

To show logo, you have to do a tiny workaround explained in [Appearance section](#appearance)
Canvas size for a 1080p display is 650x630

### Appearance
You can change appearance of Details view by changing Item spacing value\
(the real item spacing parameter is defined internally and cannot be modified)

![Settings](https://raw.githubusercontent.com/ld892012/PlayniteRevisitedSkin/main/Media/Options.png)

**0** : Show icon/logo only (if not found, show title instead)

**1** : Show icon/logo and title

**Everything else** : Show title only

### Shortcuts
**Down** : Show game description and some extra infos
![Description](https://raw.githubusercontent.com/ld892012/PlayniteRevisitedSkin/main/Media/Animated/Detail_CB-LL_Down.avif)

**Up** : Hide UI and icon/logo (to admire your beautiful background !)
![Description](https://raw.githubusercontent.com/ld892012/PlayniteRevisitedSkin/main/Media/Animated/Detail_CB-LL_Up.avif)

## Status View :

![Status](https://raw.githubusercontent.com/ld892012/PlayniteRevisitedSkin/main/Media/Status_BB-CB_CB-LL.png)

By default, only the background is shown, to show buttons just go down and buttons shows up!

## Extras

This theme support extra file called `ClearBackground`, it's a game background without logo

For example, istead use a Clear background as background and *Extra Metadata* (or icon) for logo, you can :
- Create an background with logo (from a Clear Background and a Logo)
- Use it as Background into Playnite
- Copy your Clear Background in `<Playnite configuration path>\ExtraMetadata\<Game database Id>\ClearBackground.jpg`

This theme automatically detects it and show it in status view and in Details view when *Up* shortcut is pressed

Example :

![Example](https://raw.githubusercontent.com/ld892012/PlayniteRevisitedSkin/main/Media/Animated/Detail_BB-CB_Up.avif)

## Some ideas to implement one day :
- [x] Change appearance of Main view
- [x] Modify Detail View to make it minimalistic
- [x] Transform Status view to add it game background
- [x] Add advanced infos to detail view by pressing a key
- [x] Add possibility to show icon in Detail view
- [x] Add BackgroundChanger support
- [x] Add Extra Metadata Loader support (Logos)
- [x] Add [Back to Game](https://github.com/ashpynov/BackToGame) button in status view
- [x] Add ClearBackground support (replace background image in Status view)
- [ ] Add some modifiable skin settings (icon show, title show, Play item position, theme color, ...) (with [Theme Options](https://github.com/ashpynov/ThemeOptions) or a future version of Playnite)
- [ ] Add custom buttons color in Detail View (inspired by [ReskinPS5](https://github.com/TheKersalMassive/ReskinPS5#how-do-i-get-a-custom-colour-border))
- [ ] Add SuccessStory entry to Advanced details
- [ ] Add HowLongToBeat entry to Advanced details
- [x] ~~Add tools to Playnite menu~~ (not by myself, added in Playnite  10.36)
- [ ] ~~Add a music player to Detail View which plays a game-specific music~~ (possible but unusable at theme-side, I let prototype in `Main.xaml` for archive, you better use [PlayniteSound](https://github.com/ashpynov/PlayniteSound))
