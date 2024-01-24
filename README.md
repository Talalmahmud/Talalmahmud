- 👋 Hi, I’m @Talalmahmud
- ✨ I'm a MERN developer
- ✨I'm a problem solver.
- 👀 I’m interested in full stack web developer.
<br><b>Skills in</b>
- React JS
- Node JS
- Express JS
- Next JS
- HTML
- CSS
- Tailwind
- SASS
- JavaScript
- MongoDB
- Sql
- Python
- Next Auth

<!--START_SECTION:badges-->
name: Update badges

on:
  schedule:
    # Runs at 2am UTC
    - cron: "0 2 * * *"
jobs:
  update-readme:
    name: Update Readme with badges
    runs-on: ubuntu-latest
    steps:
      - name: Badges - Readme
        uses: pemtajo/badge-readme@main
        with:       
          CREDLY_USER: <username_credly> # optional, but default will use the same from github
<!--END_SECTION:badges-->
