# Installation and Developement Guide

1. Install tailwindcss
`npm install tailwindcss @tailwindcss/cli`

2. Run the tailwindcss instance watcher to generate output.css during developement
`npx @tailwindcss/cli -i ./input.css -o ./output.css --watch`

3. Add output.css as header to every html

4. Run the website
`npx serve .`
or 
`use live server extension in VS Code`