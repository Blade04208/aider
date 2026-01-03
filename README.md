# Aider

the 700th skeuo theme

## build

this theme uses a dev script to check for changes in the source css files and combine them into a build file. to run locally:

1. clone the repository.
2. run `npm i`.
3. create a `.env` file in the project root with the paths of any local theme files you want to update (comma separated)

```
DEV_OUTPUT_PATH=C:\Users\USERNAME\AppData\Roaming\Vencord\themes\aider-dev.theme.css
```

4. run `npm run dev`.
5. make changes to any file in `/src` or the main theme file. the local theme files you listed will automatically be updated, along with the build file in `/build`.


## thanks

**Aidak** - design inspo, orginal person who wanted me to make a theme in this style
**refact0r** - gave base for compartmentalization of the theme, thank you for making mine life easier