# loud-mouth
A Personal Blog Application

## Features

### Admin/Editor App
- **Markdown Editor**
  - Support for dot phrases and slash commands, similar to [Notion](https://www.notion.so/help/guides/using-slash-commands).
  - Categorization functionality.
- **Blog Management**
  - Ability to delete, hide, edit, and publish blogs.

### Reader App
- **User Interface**
  - Header with a home button.
  - Home page featuring full blog content with infinite scroll.
- **Sidebar**
  - Closeable and lists all blogs.
  - Sorting by publish date and category.
  - Search functionality (?).
- **Responsive Design**
  - Minimal responsiveness for various device sizes.

## Tech Stack

### Front-end
- **Admin/Editor App**: Written in [Elm](https://elm-lang.org/).
- **Reader App**: Developed in [Rust](https://www.rust-lang.org/) using [Handlebars.rs](https://github.com/sunng87/handlebars-rust).

### Back-end
- **API Handler**: Implemented in [Rust](https://www.rust-lang.org/) and hosted with [Cloud Run](https://cloud.google.com/run?hl=en).

### Database
- **Main Database**: [Postgres](https://www.postgresql.org/) using [Cloud SQL](https://cloud.google.com/sql?hl=en).
- **Storage**: [Cloud Storage](https://cloud.google.com/storage?hl=en).

## Blog Ideas
- Exploring the dilemma of sticking with what's comfortable vs. diving into something new ([Elm](https://elm-lang.org/) vs. [Rust](https://www.rust-lang.org/) front-end development).
