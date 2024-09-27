~1 command~ ``npm init -y``` **download node Modules**,
~2 command~ `npm install -D tailwindcss `,
~3 command~ `npm tailwind init`,
~4 command~ `  content: ["./src/**/*.{html,js}"],` change name.
`  content: ["./*.html"],`,
~5 command~ create new file tw.css
@tailwind base;
@tailwind components;
@tailwind utilities;,
~6 command ~ `npx tailwindcss -i ./src/input.css -o ./src/output.css --watch`
change command!
"scripts": {
"dev": "npx tailwindcss -i tw.css -o style.css --watch"
},
last command! `npm run dev`
!congratulation your run your tailwind in VS Code.


<!---
DesignerJawad0347/DesignerJawad0347 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
