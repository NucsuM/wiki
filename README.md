# wiki [![Join the chat at https://gitter.im/rust-leipzig](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/rust-leipzig?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Possible features
- Statically generated HTML pages written in markdown
- Basic templating
    - Menu generation
    - Background colors
    - Fonts
- General source code support
- Full text search with indexing support (autocompletion)
- Runtime documentation
- Resource management (images, pdfs)
    - Uploading, resizing images
    - Auto linking by keyword or category
- Local HTTP server support
- Plugin API and manager
    - Auto generated index (title, creation date, certain word)
    - Git backend for visioning
- User management with certain access rights

## Minimal implementation
1. You have a collection of markdown files
2. Generate static html partials from them
3. Generate the indexes including their links