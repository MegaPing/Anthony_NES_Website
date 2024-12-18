# Changelog

All notable changes to this project will be documented in this file.

```
## [X.Y.Z] - YYYY-MM-DD

[Short Title Description]

### Added
- [Implemented new feature]

### Changed
- [Edited pre-existing feature]

### Fixed
- [Resolved a problem]
```


```
SEMANTIC VERSIONING FRAMEWORK

MAJOR version (X.Y.Z):
Increment the MAJOR version when you make code changes that are not backward-compatible.
Examples:
  - Redesigning the entire UI that requires users to adapt significantly.
  - Removing or renaming public APIs.
  - Changing the underlying database structure that affects the current way content is served.

MINOR Changes (0.Y.0)
Increment the MINOR version when you add new features or substantial improvements that do not break existing functionality.
Examples:
  - Adding a new feature like a blog or forum section.
  - Implementing new styling or layout options that enhance user experience without disrupting current content.
  - Adding additional languages or localization options.

Increment the PATCH version when you implement backward-compatible bug fixes.
Examples:
  - Fixing a layout issue on specific devices or browsers.
  - Correcting a typo on your site.
  - Addressing minor bugs that don’t change how features work.


```





## [1.0.0] - 2024-10-12
MAJOR RELASE

### Added
- Initial release of the anthonyavelar.com website! Currently deployed as a single page website.
- Implemented NES CSS Framework in the overall design for the website!


## [1.1.0] - 2024-10-17
MINOR RELEASE

### Added
- Implemented a navigation menu within the header of the website!
- Implemented an `About Me` webpage
- Implemented a `Code Projects` webpage
- Implemented an `Art Projects` webpage
- Implemented a `Quests` webpage
- Implemented an `Accomplishments` webpage
- Implemented a `Contact Me` webpage
- Added a `NEWFEATURES.md` file to the `documentation` directory to record ideas I'd like to make into features

### Fixed
- Resolved issue preventing "Press Start 2P" font to render on mobile devices

### Changed
- Edited the footer design used on my homepage. It uses small nes-icons to point to my LinkedIn, GitHub and Instagram accounts.
- Edited the font used on the `About Me` page to be consistent with the NES CSS Framework
- Wrote content for the following sections:
    - "My Story" section
    - "My Life Philosophy" section
    - "Interests" section
    - "Roles I Like to Play" section
- Copied the footer design used in my `index.html` page



## [1.2.0] - 2024-10-18
MINOR RELEASE: Introduced new images and content across multiple pages

### Added
- Added in several art-related image files to `images` directory
  - art_charcoal.jpg
  - art_color_heads.jpg
  - art_david_head.jpg
  - art_inkpen.jpg
  - art_inversion.jpg
  - art_selfportrait.jpg
  - art_skull.jpg
  - art_watercolor.jpg

#### Added to `Art Projects` Page:
- Implemented a gallery feature in the `Art Projects` page
- Added a `script.js` file. Currently contains code exclusively used to enhance the gallery within the `Art Projects` page.

#### Added to `Code Projects` Page:
- Created 4 mock project cards within my `Code Projects` page. Each project card includes:
   - a placeholder image
   - a project name
   - a description
   - technology stack
   - a GitHub repo link

- Added content to `My Code Projects` page:
   - `My Story As A Developer` section
   - `Favorite Technologies` section

### Added to `Questbook` Page:
- Added HTML sections to `questbook.html` page:
   - `What is a Quest?` section
   - `What is a Questbook?` section
   - `Elements of a Good Quest` section
   - `My Currently Active` Quests section
   - `My Master Quest` section
   - `Major Life Quests` section
   - `Full Quest List` section

### Changed
- Added comments within `styles.css` file to clarify the purpose of each CSS class I created.
- Added a section within `styles.css` file dedicated to styling `Questbook` page


## [1.3.0] - 2024-10-19
MINOR RELEASE

### Added
- The `Player Stats` page is now ready to be deployed to cPanel!
- The `Contact` page is now ready to be deployed to cPanel!

- Created HTML structure for `Player Stats` page to include:
   - `Player Skills` section
   - `Education` section
   - `Hackathons & CTF Competitions` section
   - `Work Experience` section
   - `Noteworthy Deeds` section
   - `Download Resume` section

- Created HTML structure for `Contact Me` page to include:
   - `Welcome` section
   - `Start a Conversation` section
   - `Contact Form` section
   - `Download My Resume` section

- Created dedicated code block for `Player Stats` page within `styles.css` file
- Created dedicated code block for `Contact Me` page within `styles.css` file

- Created a `favicon` directory to store favicon files
- Implemented unique favicons for the following pages:
  - `About Me` page
  - `Art Projects` page
  - `Code Projects` page
  - `Contact` page
  - `Index.html` page
  - `Player Stats` page
  - `Questbook` page

- Added a background image to all pages on the website

- Created a `splash` page for my website
  - Added typing animation to welcome message
  - Implemented toggle functionality for background music button
  - Updated "Enter" button with hover effect (wiggle and glow)
  

### Changed
- Redesigned footer section across all pages to include only LinkedIn, GitHub, and Instagram icons; centered elements on a black background

- Updated `main` CSS class in `styles.css` file to add whitespace margins for enhanced readability

- Reorganized HTML structure in `My Code Projects` and `My Art Projects` pages to include:
   - `What I'm Doing Now` section
   - `My Dream` section
   - `What's Next?` section

- Improved design of several webpages by replacing custom section headings with `<section>` tags for better clarity:
   - `My Code Projects` page 
   - `My Art Projects` page
   - `Questbook` page

- Renamed `Accomplishments` page to `Player Stats` and updated header sections throughout the site

- Removed redudant sections from the homepage



## [1.3.1] - 2024-10-20
PATCH RELEASE:

### Added
- Added images to `Code Projects`, `Art Projects`, and `Player Stats` pages.
- Implemented a music button feature across all pages on my website
- Implemented a "praiseMessage" feature which generates praise for when a web visitor clicks on the music button

### Changed
- Rewrote the content in project cards within the `Code Projects` page for clarity
- Removed `script.js` file and replaced it with three scripts for better code maintainability:
   - `art-project.js`
   - `splash.js`
   - `musicbutton.js`
- Updated the styling of the border of the "hero image" used on my homepage

### Fixed
- Centered the project cards by editing `styles.css` file. This fixed issue #2. See `Issues.md` file for context.
- Removed hypothetical project cards from `Code Projects` page. Only the projects I am actively working on remain.



## [1.3.2] - 2024-10-22
PATCH RELEASE: Edited the website's pages in preparation for deployment. The enhanced version will be deployed tomorrow!

### Changed

- Edited content on `index.html` page:
   - Applied capitalized case to all of the section titles
   - Rephrased all the section titles as questions instead of statements
   - Applied the "lists" css class to all the bullet point lists used in the page
   - Added hyperlinks to the bullet points in the `What Am I Currently Working On?` section
   - Added emojis onto the bullet points in the `What Am I Learning About Right Now?` section

- Edited content on `About Me` page:
   - Replaced the "Detective" role with the "Writer" role within the `Roles I Like to Play` section
   - Applied the "lists" css class to all the bullet point lists used in the page
   - Merged the `Roles I Like to Play` section into the `Life Philosophy` section
   - Added a button that points to my `Contact Me` page at the bottom of the page

- Edited content on `Code Projects` page:
   - Changed the title of the `What I'm Doing Now` section to say `What I'm Learning About Now`
   - Applied the `lists` and `nes-list is-disc` css classes to all the bullet point lists used in the page
   - Edited the content of the `What I'm Learning About Now` section
   - Rearranged the order of the sections on the page
   - Added a button that points to my `Contact Me` page at the bottom of the page


- Edited `Art Projects` page content:
  - Changed title of `What I'm Doing Now` section to `What I'm Learning About Now`
  - Applied `lists` and `nes-list is-disc` CSS classes to all bullet point lists
  - Edited content in the `What I'm Learning About Now` section
  - Rearranged the order of sections on the page
  - Added button linking to Contact Me page at the bottom
  - Included hypothetical prices for the art pieces


- Edited `Questbook` page content:
  - Streamlined content in the `What is a Quest?` section
  - Merged `Elements of a Good Quest` section into `What is a Quest?` section
  - Streamlined content in the `What is a Questbook?` section
  - Rearranged the order of sections on the page
  - Created new directory named `quests` with three HTML pages for describing quests:
    - `main-quests.html`
    - `master-quest.html`
    - `side-quests.html`

## WEBSITE VERSION [1.3.2] WAS DEPLOYED TO GODADDY CPANEL VIA FTP ON 2024-10-23
The new enhanced website is live!

## [1.4.0] - 2024-10-23
MINOR RELEASE: Added unique music files for each page on the website.

### Added

- Added 7 new musicbox files to the `music` directory.

- Implemented specific music tracks for the following pages:
  - Home page: `Bloody_Tears_Castlevania.mp3`
  - About Me page: `PokemonThemeAnime.mp3`
  - CodeProjects page: `DireDireDocks_Mario.mp3`
  - ArtProjects page: `MoonlightDensetsu_SailorMoon.mp3`
  - Questbook page: `TrainerBattle_PokemonGen1.mp3`
  - PlayerStats page: `FinalBattleVsRival_PokemonGen1.mp3`
  - Contact page: `NationalPark_Pokemon.mp3`


## [1.5.0] - 2024-10-23
MINOR RELEASE: Implemented toggle feature for improved readability. Feature will be used across the website.

### Added
- Developed a toggle feature for enhanced content accessibility across different sections of the website.
- Integrated the toggle feature on the homepage to improve content readability.


## [1.5.1] - 2024-10-24
PATCH RELEASE: Enhanced the `About Me` page with new toggle feature and wrote new content for the sections

### Added
- Created new sections: `What Makes Me Special?` and `What's My Dream?`.
- Added a profile picture to the `About Me` page to enhance visual appeal.
- Included Font Awesome stylesheet in the head section for icon support:
  `<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">`

### Changed
- Applied toggle feature to the `About Me` page for better content accessibility.
- Streamlined the content within the page sections.
- Incorporated quotes into several sections:
  - `What's My Life Philosophy?`
  - `What Are My Interests?`
  - `What's My Dream?`
  - `If You're Going My Way, Walk With Me`


## [1.5.2] - 2024-10-24
PATCH RELEASE: Enhanced the `Code Projects` page with new toggle features and wrote new content in various sections.

### Added
- Applied toggle feature to the `Code Projects` page for better content management.
- Created a new section: `Inspiration Sources`.
- Added Font Awesome stylesheet link in the head section for icon support:
  `<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">`
- Included script for toggle functionality at the bottom of the page:
  `<script src="scripts/toggle.js"></script>`
  Furthermore, I added this code snippet to the following pages:
  - `art-projects` page
  - `player-stats` page
  - `questbook` page

### Changed
- Streamlined the content within existing sections for improved readability.
- Renamed sections for clarity:
  - `What I'm Learning About Now` to `Current Activities`
  - `What's Next?` to `What I Want To Learn & Build Next`
  - `Like What You Saw Here? Let's Talk!` to `I'm Available For Hire`
- Merged `Favorite Technologies` section into `About Me As A Developer` section for better organization.


## [1.5.3] - 2024-10-24
PATCH RELEASE: Enhanced the `Art Projects` page with new toggle features and wrote new content in various sections.
Added a project card to `Code Projects` page

### Added
- Applied toggle feature to the `art-projects` page for better content management.
- Created a new section: `Inspiration Sources`.

- Related to `code-projects` page:
  - Added a project card to describe capsule wardrobe app
  - Added an image file named `code_wardrobe_app.png` to `images` directory

### Changed
- Streamlined the content within existing sections for improved readability.
- Renamed sections for clarity:
  - `What I'm Learning About Now` to `Current Activities`
  - `What's Next?` to `What I Want To Learn & Create Next`
  - `Like What You Saw Here? Let's Talk!` to `I'm Available For Hire`
- Merged `Favorite Technologies` section into `About Me As An Artist` section for better organization.



## [1.5.4] - 2024-10-24
PATCH RELEASE: Enhanced `Questbook` page and add new quest HTML files.
Made minor content changes within the `Art Projects` and `Code Projects` pages

## Added
- Applied toggle feature to the `questbook` page for improved content management.
- Created 3 new HTML files in the `quests` directory:
  - main-quests.html
  - side-quests.html
  - ultimate-quest.html
- Added basic content within the 3 newly created HTML files

## Changed
- Streamlined the content within existing sections of the `questbook` page for better readability.
- Made minor adjustments to the `My Vision` section within the `Art Projects` and `Code Projects` pages.
- Enhanced the readability of the CHANGELOG.md file by introducing a new rule that requires me to explicitly identify the type of release for every new version of the website
  - Edited the previous entries to be consistent with this new convention



## [1.5.5] - 2024-10-24
PATCH RELEASE: Enhanced `Player Stats` page with updates

## Added
- Applied toggle feature to the `Player Stats` page for better content management.

## Changed
- Eliminated the `Hackathons & CTF Competitions` section to simplify the content.
- Renamed the `Player Skills` section to `Skills` for conciseness.
- Eliminated skills I can't believably justify from `Skills` section




## [1.5.6] - 2024-11-07
PATCH RELEASE: Fixed caption-related bug with images displayed in `Art Projects` page

## Fixed
- Corrected issue #4 described in ISSUES.md file. The captions associated with the art gallery images are now displaying correctly.

## Added
- Added a `.art-title` class to the `Art Projects` page to center the text alignment of the titles on the art cards on the webpage

## Changed
- Modified the properties of these CSS classes:
  - `.lightbox-content`
  - `.lightbox-caption`
  - `.lightbox img`

