# Root content extension for Contao Open Source CMS

The extension allows to create root-page aware content in your Contao layouts.


## Installation

Install the bundle via Composer:

```
composer require terminal42/contao-rootcontent
```

## Configuration

There's absolutely nothing to configure :-)


## Usage

There are two options to create root-page aware content.


### Create articles in the root page

The extension allows to create articles in the root page. Here's how it
works:

1. Edit your **theme** and add custom content sections. Each theme
   can have multiple sections with root content.
2. Add an article to a root page. Contrary to regular articles, you
   cannot enter a name but select one of the sections from your theme.
3. Create a root-content module in your theme and select the section
   you want to output.
4. Place the new module anywhere in your page layout.


### Limit front end modules per root page

For each front end module, there is a new setting to limit it for one
or multiple root pages. This way you can create language-aware modules.
Simply place all of them in your page layout and only the respective
ones will be rendered one at a time.
