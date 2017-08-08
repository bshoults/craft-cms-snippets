# Meta Pattern
The concept behind this snippet is to create a global that covers the meta description & social media card image. Then, you have the ability to change the meta description, social image, and SEO title (long title) on a per-page basis. The conditionals reflect this.

## Setup
You will need to import the `export.json` file. You will need to create a global set called "Global SEO" with the handle `globalSeo` and apply the *SEO Description*, *SEO Image* and *SEO Image Alt Text* fields (SEO Title is not used since we don't want to create a global title).

You need to apply the fields to whatever section you want them displayed in. I typically create a few tabs (*Content* and *SEO & Options*) and apply the fields there.
