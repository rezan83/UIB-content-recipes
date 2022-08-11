# Recipe Book
[![Status overview badge](../../blob/badges/.github/badges/autograding/badge.svg)](#results)


## Exercise I

- [x] In the `recipes` folder, create a new file with the basic html structure, with the following naming convention `index.html`.
- [x] Create a meta tag with the name author and your name as the value.
- [x] Change the title of the page to the name of the recipe.

---

## Exercise II

- [x] Find and/or download an image for your recipe, and put it in the `img` folder.
- [x] Add the image of your recipe to the html page, the fallback text for the image should be the name of the recipe, the image must be 500 px wide

---

## Exercise III

- [x] Under the image, add the main heading of your page. The heading should be the name of your recipe.
- [x] Add two secondary headings to your page. The first should say "Ingredients" and the second should say "Preparation".

---

## Exercise IV

- [x] Under the "Ingredients" heading, add an unordered list for the ingredients of your recipe
- [x] Under the "Preparation" heading, add an ordered list for the preparation of your recipe

![mockup-image](/img/reference-image.png)

---

[//]: # (autograding info start)
## Results


### Recipe Book

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/autograding/status0.svg) | Index file should contain specified meta tags |
| ![Status](../../blob/badges/.github/badges/autograding/status1.svg) | Index.html Should contain a 'title' Tag  |
| ![Status](../../blob/badges/.github/badges/autograding/status2.svg) | An image should be present in index.html, with specified width of 500px |
| ![Status](../../blob/badges/.github/badges/autograding/status3.svg) | H2 tag with the text 'ingredients' exists |
| ![Status](../../blob/badges/.github/badges/autograding/status4.svg) | Ingredients Should have an Unordered List with a list of ingredients |
| ![Status](../../blob/badges/.github/badges/autograding/status5.svg) | H2 tag with the text 'Preparation' exists |
| ![Status](../../blob/badges/.github/badges/autograding/status6.svg) | Preparation Should have an Unordered List with a list of Instructions |



[🔬 Results Details](https://github.com/DigitalCareerInstitute/UIB-content-recipes/actions)

[📢 Give Feedback or Report Problem](https://docs.google.com/forms/d/e/1FAIpQLSfS8wPh6bCMTLF2wmjiE5_UhPiOEnubEwwPLN_M8zTCjx5qbg/viewform?usp=pp_url&entry.652569746=UIB-content-recipes&entry.2115011968=https%3A%2F%2Fgithub.com%2FDigitalCareerInstitute%2FUIB-content-recipes)

### Debugging your code
> [reading the test outputs](https://github.com/DCI-EdTech/autograding-setup/wiki/Reading-test-outputs)

There are two ways to see why tasks might not be completed:
#### 1. Running tests locally
- Run `npm install`
- Run `npm test` in the terminal. You will see where your solution differs from the expected result.

#### 2. Inspecting the test output on GitHub
- Go to the [Actions tab of your exercise repo](https://github.com/DigitalCareerInstitute/UIB-content-recipes/actions)
- You will see a list of the test runs. Click on the topmost one.
- Click on 'Autograding'
- Expand the item 'Run DCI-EdTech/autograding-action@main'
- Here you see all outputs from the test run

[//]: # (autograding info end)