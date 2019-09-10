# Take Home "Quiz Project"

## Table of Contents

[Getting Started](#getting-started)

[Project Info](#project)

[Boilerplate Info](#boilerplate-info)


## Getting Started

[Project repo](https://github.com/lsst-epo/quiz_project)

[The bolierplate that is the basis for this project](https://github.com/lsst-epo/webpack_babel_sass_boilerplate)

Refer to this readme for project requirements, and information regarding the development environment (installing dependencies, starting the development server, creating builds, etc).

### Things to keep in mind

* Commit early and often.  We’re interested in how you like to use git, and how you break down even a small app like this into more manageable parts.  

* After you finish the project please push it to a repo on your personal github and email us the link.

* We do not expect you to spend more than 4 hours on this project.  You may not fully complete all aspects of this project, that’s totally ok, but be prepared to discuss all aspects of this project, including talking through potential solutions and possible extensions.


## Project

Create a short quiz that presents an **information block**, and evaluates the user’s understanding of the **information block** using several **question types**.  Feel free to  (you will need to) add, alter, or replace any or all of the provided copy, markup, or styles.

**Note**: The content of the quiz is nonconsequential; Ipsum Lorem is entirely sufficient for the **information block** and the **questions** text.

### Components

**Information Block**: Several paragraphs of text

**Question**: Form element with accompanying text

**Active Question**: The question whose form field currently has, or last had, focus

**Answer**: Form element value

**Question Types**:
* Short Answer (`Block Level` `Text Input`)
* Long Answer (`Block Level` `Text Area`)
* Fill in the blank (`Inline` `Text Input`)
* Compound Fill in the Blank (2 or more `Inline` `Text Input`)
* Multiple Choice (`Inline` or `Block Level` `Select`)
* Compound Multiple Choice (2 or more `Inline` `Select`)

### Users

**Desktop User**: Uses a keyboard, mouse, and screen, and a `Chrome` browser window width >= 1024px

**Mobile User**: Uses a touchscreen, and a `Chrome` or `Safari` browser window width <= 768px

**Screen Reader User**: Uses a Screen Reader (like `VoiceOver`, `Narrator`, `JAWS`, etc.) and a keyboard, and Chrome browser.

### User Stories

* As a **Desktop or Mobile User**, I can easily distinguish the **active question** from all other questions so that my attention is on the **active question**.

* As a **Desktop or Mobile User**, I can easily distinguish between **answered** and **unanswered** **questions** so that I can identify my general progress at a glance, and easily identify **questions** I skipped.

* As a **Desktop User**, I can view the **information block** and the **active question** at the same time so that I can easily refer back to details in the **information block** while answering the **active question**.

* As a **Mobile User**, I can easily navigate between the **information block** and the **active question** using a single tap (or gesture) so that I have the ability to look back to details in the **information block** without a lot of scrolling.

* As a **Screen Reader or Desktop User**, I can navigate the quiz using only the keyboard so that my experience is fundamentally consistent regardless of accessibility needs.


## Boilerplate info

 1. Webpack configuration for development and production
 2. Transpile ES6+ to ES5
 3. Transpile and Autoprefix SCSS to CSS
 4. Manage static resources
 5. Support for extending webpack functionality with different plugins

#### To clone the repository

> `git clone https://github.com/lsst-epo/webpack_babel_sass_boilerplate.git`

#### Change directory

> `cd webpack_babel_sass_boilerplate`

#### Install dependencies

> `npm install` (or `yarn`)

#### Run development server

> `npm run start` (or `yarn start`) for a dev server. Navigate to `http://localhost:8080/`. 

The app will automatically reload if you change any of the source files.

#### Build

> `npm run build` (or `yarn build`) to build the project in development mode. 

The build artifacts will be stored in the `dist/` directory.
