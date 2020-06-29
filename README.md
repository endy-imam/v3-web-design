# Personal Portfolio + Blog Site V3 Design

## Synopsis

This is a respository of isolated pages and components for the third redesign of my personal site as both a porfolio and a blog site.

This time, I want to make another take on designing a site by scratch to make it a responsive mobile-first ([literally this time](https://dev.to/kevinpowell/stop-making-responsive-websites-the-hard-way-kgb)), all running on [Hugo](https://gohugo.io/) and maybe deploy it on [Netlify](https://www.netlify.com/) — basically a [Jamstack](https://jamstack.org/).

This is also the first time I am properly utilizing [Node.js](https://nodejs.org/en/) for my development toolchain.


## To-Do List

- [ ] _Base Case_
  - [ ] Navbar
    - Listing of pages & section at home or sections w/ link to resume file(s)
    - _Optional:_ Search and Tags section
  - [ ] Footer
    - Social listing, externals, copyright, and top
- [ ] Homepage
  - [ ] Hero
    - Name, headline, socials, direct Llnk to resume file(s) and contact section
  - [ ] Recent Blog Posts
    - Show preview of 3 recent post w/ link to post and main section
  - [ ] About
    - Description and Listing
    - [ ] Skills
      - Listing of Skills for Sections w/ Proficiency Grade
  - [ ] Work Experience
    - Link to resume file(s) + recent experience w/ link to show more in page
  - [ ] Recent Projects (Personal + Volunteering)
    - Show preview of 3 recent projects w/ link to project and main section
  - [ ] Contact
    - Show social listing and email
    - _Optional:_ Contact Form
- [ ] Blog
  - [ ] Main Section
  - [ ] Individual Page
    - Include metadata of title, description, tags, and optional background
- [ ] Projects
  - [ ] Main Section
  - [ ] Subsection
    - [ ] Personal
    - [ ] Volunteer
  - [ ] Individual Page
    - Include metadata of title, description, external page links, affiliates, tags, and optional background


## Installation

```sh
npm install
npm
```


## Development Setup

### Install `pug-cli`

```sh
npm install -g pug-cli
```

### Install `sass`

```sh
npm install -g sass
```

*Note:* `npm` is a straightfoward installation, but it's not as performant as it's [Dart source](https://github.com/sass/dart-sass).


## Development Toolset

Via [npm](https://www.npmjs.com/), these are the templating tools to quickly layout the template for the HTML and CSS:

- [**Pug**](https://pugjs.org/) _(formerly Jade)_ - An HTML templating package for outputting raw `.html` from `.pug` template files.
- [**Sass**](https://sass-lang.com/) - The mature CSS extension and preprocessing language that is the gold standard for web design, converting `.scss` to raw `.css`.


## Directory Hierarchy

```
v3-web-design/
├── components/
├── layouts/
├── output/
│   └── css/
├── pages/
├── sass/
├── .gitignore
├── LICENSE
├── package.json
├── package-lock.json
└── README.md
```

### Output Directory

- `outputs/`: The main directory for output HTML and CSS

### Source Directories

- `pages/`: The main directory of `.pug` files to output `pug` from.
- `layouts/`: The helper directory of `.pug` files to extend from.
- `components/`: The supporting directory of `.pug` files to include from.
- `sass/`: The source directory of `.scss` files to output `sass` from.


## Design Notes

_[TODO: Create Visual Representation of Design Implementaion]_

### External CSS

- [normalize.css](https://necolas.github.io/normalize.css/) to reset for HTML5.

### Fonts

Fonts provided from [Google Fonts](https://fonts.google.com/):

- **Heading Font:** [Fira Code](https://fonts.google.com/specimen/Fira+Code?query=Fira+Code) _(Light 300)_
- **Primary Font:** [Karla](https://fonts.google.com/specimen/Karla?query=Karla) _(Regular 400, Regular 400 Italic, Bold 700)_

### Icons

- **Icons:** [Font Awesome 5 (Free)](https://fontawesome.com/)
  - Final project will use the pro version.

### Color Pallete

_[TODO: Create Final Color Pallete]_
