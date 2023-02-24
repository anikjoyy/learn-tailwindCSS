## Process

### There are three process

- Install from CDN
- Install as PostCSS Plugin
- Install Tailwind CLI (Best Approach)

### Tailwind CLI

- npm init -y
- npm i -D tailwindcss
- npx tailwindcss init
- We'll create two folders: src and output
- We'll create tailwind.css file in the src folder
- Then we'll write this in the tailwind.css file-
  _ @tailwind base;
  _ @tailwind components;
  \_ @tailwind utilities;

* We'll create .vscode/setting.json file in the root of our projects
* { "css.validate": false, "tailwindCSS.emmetCompletions": true}
* In the package.json file, in the scripts, {"build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"}
* After build link the ./output/tailwind.css in index.html file
* npm run build
