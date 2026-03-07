# Effective Altruism Denmark

Website for [effectivealtruism.dk](https://effectivealtruism.dk), built with [Hugo](https://gohugo.io/).

## Setup

1. Install Hugo: https://gohugo.io/installation/
2. Clone the repo: `git clone git@github.com:simvad/eadk.git`
3. Run locally: `hugo server`
4. View at http://localhost:1313

## Contributing

As long as we are a small team of collaborators, you can push straight to main if you are confident in your change. Alternatively please make your change in a new branch and create a pull request for it: 

```
git checkout main
git pull
git checkout -b task-name
```

Make your changes, then:

```
git add -A
git commit -m "Describe what you changed"
git push -u origin task-name
```

Then open a pull request on GitHub.

## TODO

Priority: 🔴 high, 🟡 medium, 🟢 low. Add your name if you're working on something.

### Translation (branch: `feature/language-toggle`)
- [ ] 🔴 Review and polish Danish translation of Front page
- [ ] 🔴 Review and polish Danish translation of About page
- [ ] 🔴 Review and polish Danish translation of Become a Member page
- [ ] 🔴 Review and polish Danish translation of Career Guidance page
- [ ] 🔴 Review and polish Danish translation of Introduction page
- [ ] 🔴 Review and polish Danish translation of Events page
- [ ] 🔴 Review and polish Danish translation of Contact page
- [ ] 🔴 Merge `feature/language-toggle` into main when translations are done

### Chapter pages
- [ ] 🟡 Figure out if we want calendars per chapter (or is there a smart filter thing?)
- [ ] 🟡 Add description and content Copenhagen chapter
- [ ] 🟡 Add description and content Aarhus chapter
- [ ] 🟡 Add description and content Odense chapter
- [ ] 🟡 Add description and content Aalborg chapter

### Content & design
- [ ] 🔴 Review front page layout and decide on final look (do we want the old header/footer images?)
- [ ] 🟡 Set up a proper newsletter solution (replace temporary Google Forms)
