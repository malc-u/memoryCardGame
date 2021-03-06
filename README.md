# Awesome 80s memory game

![Awesome 80s memory game](https://github.com/malc-u/memoryCardGame/blob/master/assets/images/header.png?raw=true)

Memory game for 80s kids & card matching game for their kids.

Entertaining card matching game that will remind you characters you loved as a child and that will introduce your children to them.

- [Awesome 80s memory game](#awesome-80s-memory-game)
  - [UX](#ux)
    - [Project purpose](#project-purpose)
      - [Site user goals - children](#site-user-goals---children)
      - [Site user goals - adults(parents and guardians)](#site-user-goals---adultsparents-and-guardians)
      - [User stories](#user-stories)
    - [Wireframes](#wireframes)
    - [Design decisions](#design-decisions)
      - [Color scheme](#color-scheme)
      - [Fonts](#fonts)
      - [Background](#background)
      - [Card images](#card-images)
  - [Features](#features)
    - [Existing features](#existing-features)
    - [Features left to implement in the future](#features-left-to-implement-in-the-future)
  - [Technologies](#technologies)
    - [Languages](#languages)
    - [Libraries](#libraries)
    - [Tools](#tools)
  - [Testing](#testing)
  - [Deployment](#deployment)
    - [How to run this project locally](#how-to-run-this-project-locally)
  - [Credits](#credits)

## UX

### Project purpose

Main purpose of this project is to provide easy game that entertains. It is designed to be easy enough for children to operate but the theme may also encourage adults to have a go.

#### Site user goals - children

- Easy game to operate
- Easy enough game to win
- Game that is fun
- Nice pictures to be matched
- Nice colors

Awesome 80s memory card game meets all the needs above because it provides intuitive navigation. Easy and medium levels are great for even very young children to solve. They may not do this in smallest number of turns possible but they still can get sense of achievement by solving the puzzle. Game that provides this is always fun to play. This game is also colorful and presents children with characters they may have not necessarily known yet.

#### Site user goals - adults(parents and guardians)

- Game that will help my children develop
- Easy to use for children
- Game that will challenge my child but not discourage them at the same time
- Game that may spark conversation/child-parent interaction
- Game that my entice me to play myself

Awesome 80s memory card game is not only entertaining but it is also having educational qualities. Game is training player's memory and exercising player's brain. Game is easy to use and challenging for users at any level. Some young children can get discouraged very easily and throw tantrums thus creating problem for parents. Luckily this game is easy enough for children to finish (match all cards) but the number of turns adds another layer to the challenge. The game presents users with characters that may bring smile and trip down memory lane. It can be a good conversation starter that can add irreplaceable intergenerational connection and extra value to using this game. This may also encourage some parents to play this game themselves.

#### User stories

- As a user I want to play easy but not too involving game to kill spare time (eg. during travel etc.)
- As a user and a parent I want the game that is easy enough for my children to operate
- As a user I want to play the game that is visually appealing
- As a user and a parent I want to be presented with cards that present known to me characters
- As a user I want to be presented with the characters that can spark conversation between parents and children

![Screenshot of page](https://github.com/malc-u/memoryCardGame/blob/master/assets/images/screenshot.png?raw=true)

### Wireframes

Initial wireframes for this project can be seen in the [Wireframes folder](https://github.com/malc-u/memoryCardGame/tree/master/wireframes).

### Design decisions

#### Color scheme

![Color palette](https://github.com/malc-u/memoryCardGame/blob/master/assets/images/palette.png?raw=true)

Colors that were picked had to match the theme of this game. 1980s were well known for colorful clothing that could be seen on popular then TV series - [Miami Vice](https://www.imdb.com/title/tt0086759/) - where main characters were wearing bright colors.
1980s colors are known as colors of highlighter pens - bright yellow, orange, pink, blue, green etc, so called neon colors.
Another association with 1980s color scheme and known to younger generation is released in early 2000s game [Grand Theft Auto (GTA) Vice City](https://www.rockstargames.com/vicecity/) that placed it's story in 1986.
There is no color scheme more 80s than neon.

#### Fonts

Font [Neon](https://www.dafont.com/neon.font), font [Crackman](https://www.dafont.com/crackman.font) that created main header as well as font [Audiowide](https://fonts.google.com/specimen/Audiowide) on this page are very reminiscent of 1980s.

#### Background

Background picture was picked to compliment Neon font and neon color scheme. At the same time this picture was intended not to be overwhelming main game areas - difficulty buttons and board area.

#### Card images

These were specifically chosen to present characters from 80s games such as Nintendo's-  Mario and Luigi - 2 plumbers from [Mario Bros](https://en.wikipedia.org/wiki/Mario_Bros.), [Donkey Kong](https://en.wikipedia.org/wiki/Donkey_Kong) from very popular game of the same name, Arcade's [Frogger](https://en.wikipedia.org/wiki/Frogger), [Bomb Jack](https://en.wikipedia.org/wiki/Bomb_Jack) as well as ghost from [Pac-Man](https://en.wikipedia.org/wiki/Pac-Man).
These were complimented with 2 from the list of the most popular comic book characters that debuted in 1980s - [Robin](https://en.wikipedia.org/wiki/Tim_Drake) & Leonardo - one of 4 [Ninja Turtles](https://en.wikipedia.org/wiki/Teenage_Mutant_Ninja_Turtles).

## Features

### Existing features

1. Welcome modal - explaining how to play the game.
2. Difficulty buttons allowing player to change how many cards they want to play - 8, 12 or 16.
3. Turns counter - lets player know how many turns it has taken so far in this game.
4. Board that displays cards in 4 columns and number of rows on computers, tablets and most phone devices.
5. Timer - that allows user only 60 seconds to finish level hard.
6. Game over modal - stopping and resetting the game after time has run out on level hard.
7. Win modal that congratulates user winning of the game - matching all cards.

### Features left to implement in the future

1. Best results /scoreboard.
2. Adding possibility of logging username  and then using it in the scoreboard
3. Different set of cards to be chosen ie. comic characters, game characters etc.

## Technologies

### Languages

- [HTML](https://www.w3schools.com/html/)
- [CSS](https://www.w3schools.com/css/)
- [JavaScript](https://www.w3schools.com/js/)

### Libraries

- [Bootstrap](https://getbootstrap.com/) - structuring the layout of the website and mobile first design
- [Font Awesome](https://fontawesome.com/) - used in win modal
- [jQuery](https://jquery.com/) - used in places to simplify DOM manipulation
- [Google Fonts](https://fonts.google.com/) - used to style website font

### Tools

- [Git](https://git-scm.com/) - for version control
- [GitHub](https://github.com/) - code stored and shared remotely
- [Visual Studio Code](https://code.visualstudio.com/) - IDE
- [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools) - testing the page through the development process
- [Autoprefixer](https://autoprefixer.github.io/) - checking and bringing code up to date
- [Balsamiq](https://balsamiq.com/) - creating wireframes

## Testing

Testing details can be found in separate testing.md [file](https://github.com/malc-u/memoryCardGame/blob/master/testing.md)

## Deployment

Deploying this page from GitHub repository to GitHub Pages was achieved by following these steps:

1. Logging into **GitHub**
2. Picking **malc-u/memoryCardGame** repository for the list of repositories
3. Selecting **Settings** - from menu items on the top of the page (top, right hand corner)
4. Scrolling down to the **GitHub Pages** section
5. Picking **Master Branch** from the "**Source**" drop-down menu in Github Pages (changing from the default "none" to master branch)
6. Awaiting for the page to be refreshed and website to be deployed - this happens automatically when step 5 is actioned
7. Scrolling back down to the **GitHub Pages** section to check/retrieve the link of newly deployed website

### How to run this project locally

To clone this project from this repository following steps need to be taken:

1. **Scroll up** to the repository section on this page
2. **Click "Clone or download"**(green button on the right hand side, just above the file list) - this will open "Clone with HTTPS" section
3. **Copy** the clone **URL** for the repository from "Clone with HTTPS" section
4. **Open** your local **IDE**
5. **Open** your favourite **terminal** (e.g. in your local IDE)
6. **Change** the current **working directory** to the location where you want the cloned directory to be
7. Type **git clone**, paste **the URL** you copied in Step 3 then press **Enter** to create your local clone. In this project the command should be:

```console
git clone <https://github.com/malc-u/memoryCardGame.git>
```

Further reading or help with cloning can be found on this GitHub Help [page](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

## Credits

The content of this page was written by me however following people & their work have influenced me and this project:

- [Bartek Borowczyk](https://www.udemy.com/user/samuraj-programowania/) - mechanics of assigning, swapping classes and card matching and JavaScript in general
- [Mike Bostock](https://bost.ocks.org/mike/) - mechanics of shuffling an array and Fisher–Yates Shuffle
- [Eric Schwartz](https://medium.com/@ericschwartz7) - mechanics of adding sounds to the page
- [Simen Daehlin](https://github.com/Eventyret) Code Institute mentor - overall aspect of the project

I have also used following for reacherching:

- Reddit - for sourcing [background picture](https://www.reddit.com/r/wallpaper/comments/acqekd/neon_gas_1920x1080/) and [colors](https://www.reddit.com/user/-Space-Cadet-/)
- [Freesound](https://freesound.org/) - for sourcing click sound
- [Nintendo](http://mario.nintendo.com/)- sourcing pictures of Mario and Luigi
- [Pin Clipart](https://www.pinclipart.com/) - sourcing Bomb Jack picture
- [Jing](https://www.jing.fm/) - sourcing card cover - palm picture
- [DLPNG](https://dlpng.com/) - sourcing remaining pictures
- [dafont.com](https://www.dafont.com/) - sourcing fonts that are used in the header
- [Font squirrel](https://www.fontsquirrel.com/) - webfont generator
- [Multi Device Website Mockup Generator](https://techsini.com/)
- [Code Pen](https://codepen.io/)
- [Stack overflow](https://stackoverflow.com/)
- [W3Schools](https://www.w3schools.com/)
- [Bootstrap documentation](https://getbootstrap.com/docs/4.1/getting-started/introduction/)
