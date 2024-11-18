# vue-tailwind-apply

## Introduction
It allows Vue components to 'use @apply just to make things look “cleaner”', without losing tailwind's advantages

According to the [official TailwindCSS docs page](https://tailwindcss.com/docs/reusing-styles#avoiding-premature-abstraction), using `@apply` directive extensively just to 'make things look "cleaner"' will make the final chunk file to loose the advantages of TailwindCSS, for example, making the CSS bundle bigger, once css styles will be written everytime the class with `@apply` is used.

Although making the code clearner is still important to keep components easy to understand and to maintain.

This is what `vue-tailwind-apply` plugin does! By replacing the local usage of a given class defined inside a component by its applied TailwindCSS utility classes before bundling, it places the classes in the DOM as if we've never used `@apply` in the code, for the TailwindCSS compiler.

## How to use
- ToDo!

## How to contribute
- ToDo!
