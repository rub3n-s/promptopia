# Starting Tips
## Create app
    > npx create-next-app@latest ./
    > ./ will create it in the current folder of the terminal
## Dependencies
In this project MongoDB and Next-Auth are being used\
bscrypt: encript passwords\
mongodb: database\
mongoose: manage the database
    > npm install bcrypt mongodb mongoose next-auth 

## TailwindCSS
In this project I will be using tailwind. If any doubt occurs, consult
    > tailwindcss.com/docs

# TODO
    > [] Implement Search
        - Search by prompt
        - Search by tag
        - Search by username
    > [] Implement Click on Tag
    > [] Implement View other Profiles

## Tips:
    > Search and Click on Tag
        - Code will be needed to be implemented in the Feed component
    > New Folder inside profile dir
        - profile > [id] > page.jsx

# Notes
    > .env (Environment Variables)
        > Never send this file to production
        > Add to .gitignore
