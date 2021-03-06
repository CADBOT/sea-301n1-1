# Assignment for Class 5 - Article Writer

Now that you have a blog where your articles can be read, let's create a nice interface for writing new articles.

We'll use a special html page, not linked from the main page, that will allow you to write a new article, and export it into the JSON format that the blogging system supports.

## This is a paired assignment
1. Work in pairs. Pick a driver and a navigator to start.
- Add a new feature to the navigator's repo.
- Switch off as each major feature is completed.
- The new driver now implements the same feature on new navigator's repo.
- Teach each other about what unique approaches you took in your own code base.

## User Stories: MVP
 - As an author, I want a secret URL where I can go write articles, so that blog visitors don't think they can create posts.
 - As an author, I want a form fields for all the article properties, so that I can customize each aspect of my article.
 - As an author, I want to write in Markdown, so that I can easily control formatting.
 - As an author, I want an export of the final article, so that I can paste it into blogArticles.js to publish it.

## User Stories: Stretch Goals
 - As an author, I want a live preview of how my post looks, so that I know if I screw up the markdown.
 - As an author, I want code samples to have syntax highlighting, so that my readers see code as it should appear.

## Technical Requirements and Grading Rubric
 - Keep your CSS code organized according to SMACSS.
 - Ensure your code passes ESLint.
 - Continue to use mobile-first development practices.
 - Verify that your exported data can be copy/pasted into `blogArticles.js` to be published.
 - Integrate libraries to help with markdown and syntax highlighting, as appropriate.
 - Use the same template code to preview the draft article, as appropriate.
 - Bonus points if the new article page is responsive!

## Helpful Resources
 - HTML -> Markdown conversion: https://github.com/chjj/marked
 - Syntax highlighting: https://github.com/isagalaev/highlight.js
