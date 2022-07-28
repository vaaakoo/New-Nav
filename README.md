# New-Nav
Tailwind sample project for responsive nav-bar with dark-mode


## Installation:

First you need install nodejs 
[NodeJs](https://nodejs.org/en/)

and you can try on
[Tailwindcss site](https://tailwindcss.com/docs/installation)

##### or Follow me...


## Run Locally
*open terminal and
make directory  "tailwind"*

```bash
  cd tailwind
  npm init 
```

Write and Enter repeatly

```bash
  package name: (tailwind) tailwind
  description: "tailwind sample"
  author: "Vako"
```

Fill like this...

```bash
package name: (tailwind) tailwind
version: (1.0.0) 
description: tailwind sample
entry point: (index.js) 
test command: 
git repository: 
keywords: 
author: Vako
license: (ISC) 

```

Next Run:

```bash
  * npm install -D tailwindcss
  * npx tailwindcss init

```

#### *open tailwind.config.js* 

and change`content: ["./src/*.{html,js}"],` 
#### *make directori "src" and make input.css*  
add this:
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;

```
*Next write*

```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch

```
#### *Ready for work*
