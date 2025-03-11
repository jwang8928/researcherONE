# Getting Started 
[Source](https://github.com/gitname/react-gh-pages)
1) clone repo
2) git pull and cd app
3) install ```npm install gh-pages --save-dev``` - allows hosting on the gh-pages branch

# Making changes 
1) create branch off of develop
2) make changes on that branch
3) to see changes on the actual page run this ```$ npm run deploy```
      - does take a min wait maybe 5-10 mins and reload?
4) once satisfied, commit add changes and pull request off of develop


# Github Branches 
- **master**: our actual product, only pushes/updates made to this branch is when we are sure the final product of what we want
      - only branch pushing changes to this branch is develop
- **develop**: our working product, this is the branch we work off of and can make changes to, it's our working product
      - we make branches off of develop and if anything goes wrong, we know we still have the working product on master and can just rework
- **gh-pages**: our deployment branch, the branch that hosts the [ResearcherOne](https://jwang8928.github.io/researcherONE/)

