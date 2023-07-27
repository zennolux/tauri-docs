---
title: Contribute
i18nReady: true
---

So, you want to write a doc? You've come to the right place!

![Join us gif](https://media.giphy.com/media/3ohhwznAY9PN08m0H6/giphy.mp4)

## Open Items

- [ ] In copy refer to Tauri 2.0 in the present tense so that it is still accurate upon release
- [ ] Use code that works with Tauri 2.0 now so that readers can still test out features (this will be especially useful during the beta and RC phases)
- [ ] Do we want to do a branding update?
- [ ] Favicon
- [ ] Do some testing around the dev & CI workflows with the JS API submodules

## Types of Documentation

We have the following types of documents that roughly follow the types defined by [Diátaxis](https://diataxis.fr/index.html):

- **[Guide](#guide)**: Learning-oriented
- **[Recipe](#recipe)**: Task-oriented
- **[Reference](#recipe)**: Information-oriented
- **[Blog Post](#blog-post)**: Understanding-oriented

:::tip[What is Diátaxis?]

[Diátaxis](https://diataxis.fr/index.html#) is a technical documentation system that helps with documentation quality and information hierarchy. Since Tauri is such a large project we do our best to organize information as best as possible.

You can dive into the Diátaxis system if you'd like or feel free to start writing and we can guide you along the way.

:::

### Guide

Located in [`/src/content/docs/2/guide/`](https://github.com/tauri-apps/tauri-docs/tree/starlight/src/content/docs/2/guide)

Guides are learning-oriented and take the reader through a specific journey such as starting a new project, and overview of a specific feature, or how to follow a specific flow such as building and bundling their app. They follow a similar philosophy to [tutorials in Diátaxis](https://diataxis.fr/tutorials.html).

The reader should be familiar with the concepts covered by the end of the guide and should set them up with the knowledge required to being experimenting with that topic themselves.

### Recipe

Located in [`/src/content/docs/2/recipe/`](https://github.com/tauri-apps/tauri-docs/tree/starlight/src/content/docs/2/recipe)

Recipes are designed to guide the reader through a specific task similar and have a clear outcome and objective. This could be something like setting up authentication using Firebase, adding a Python binary using sidecar, or requesting admin access on a user's machine. They are similar to [how-to guides in Diátaxis](https://diataxis.fr/how-to-guides.html) (not to be confused with our own guides mentioned above).

The prerequisites for a recipe should be clearly stated. If there are a lot of steps required before getting into the relevant information about the recipe then you may want to link out to another guide, recipe, or external resource and state those as a prerequisite at the top of the recipe.

### Reference

Located in [`/src/content/docs/2/reference/`](https://github.com/tauri-apps/tauri-docs/tree/starlight/src/content/docs/2/reference), although they should be auto-generated when possible

References are where all the nuts and bolts of Tauri's API are documented. These should be generated from upstream repos when possible and written following the best practices described by [references in Diátaxix](https://diataxis.fr/reference.html).

These should be as succinct and to the point as possible so that the reader can quickly find the relevant information.

### Blog Post

Not yet created, will be added in the future.

Topics that are around understanding something can be written as a blog post (we welcome submissions to the Tauri blog from anyone). Blog posts are a good option because they help the reader understand that information is accurate at the time of writing (and of course can always be updated later if it becomes stale). Blog posts follow the goals of [explanation in Diátaxis](https://diataxis.fr/explanation.html), but not all blog posts necessarily fit this specific format.

## Writing Style

TODO:

## Sidebar Structure

We'd like to keep the sidebar flexible as we gather feedback from the community. Right now we prefer a minimal approach so that it isn't overwhelming to new readers but we understand there's also a balance to making information discoverable.

## Translations (i18n)

While we plan to support translations in the future, we are not currently accepting them until Tauri 2.0 is a bit more stable.

Once translations are enabled you can check the [translation status page](/translation-status).