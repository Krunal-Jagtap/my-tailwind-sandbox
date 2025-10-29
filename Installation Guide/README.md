# ⚙️ Installation & Setup

### Prerequisites :

- Install Node JS
  [Download Node.js 🔗](https://nodejs.org/en/download)

### Create Folder :

- Learn Tailwind ( Folder )
- Open folder in VS-CODE
- Open Terminal ( ctrl + ` )

### Run this command :

```bash
npm install tailwindcss @tailwindcss/cli
```

- Create Folder ( src )
- Create File ( input.css ) in **src** folder
- Save this code in input.css

```bash
@import "tailwindcss";
```

### Run this command :

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

- Create File ( index.html ) in src folder
- Copy - Pest below code in **index.html**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tailwind Installation</title>
    <link rel="stylesheet" href="./output.css" />
  </head>

  <body>
    <h1 class="text-5xl bg-orange-600 text-white p-8 text-center font-bold">
      Tailwind CSS Installed ✅
    </h1>
  </body>
</html>
```

### 💡 Recommended Tools :

VS-CODE Tailwind CSS IntelliSense Extension Provides class name suggestions and hover previews.
[Download Extension 🔗](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
