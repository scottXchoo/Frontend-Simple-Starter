# Simple Template and Easy Starter for Next JS 13+, Tailwind CSS 3.3 and TypeScript

🔥 Simple Template and Easy Starter for Next.js 13+, Tailwind CSS 3.3 and TypeScript 🎉 Inspired by "[Next-js-Boilerplate](https://github.com/ixartz/Next-js-Boilerplate)".

 I love [Next-js-Boilerplate](https://github.com/ixartz/Next-js-Boilerplate) project, but there are some libraries I don't want to use, so I decided it was heavy and difficult to use. (Thanks to [Remi Wg](https://github.com/ixartz))

So I made a simpler and easier Next.js template for beginners. It's a project with only Next.js, Tailwind CSS and TypeScript. I hope you can use it well🙇🏻‍♂️

Clone this project and use it to create your own [Next.js](https://nextjs.org/) project.

## Features
**"Developer experience first"**
- ⚡ Next.js with App Router and Page Router support
- 🔥 Type checking TypeScript
- 💎 Integrate with Tailwind CSS
- ✅ Strict Mode for TypeScript and React 18

## Requirements
- Node.js 16+ and npm

## Getting Started
Run the following command on your local environment:
```
git clone --depth=1 https://github.com/ixartz/Next-js-Boilerplate.git my-project-name
cd my-project-name
npm install
```
Then, you can run locally in development mode with live reload:
```
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your favorite browser to see your project.

## Project Structure

```
.
├── README.md                       # README file
├── __mocks__                       # Mocks for testing
├── .github                         # GitHub folder
├── .husky                          # Husky configuration
├── .storybook                      # Storybook folder
├── .vscode                         # VSCode configuration
├── cypress                         # Cypress folder
├── migrations                      # Database migrations
├── public                          # Public assets folder
├── scripts                         # Scripts folder
├── src
│   ├── app                         # Next JS App (App Router)
│   ├── components                  # React components
│   ├── layouts                     # Layouts components
│   ├── libs                        # 3rd party libraries
│   ├── models                      # Database models
│   ├── pages                       # Next JS Pages (page router)
│   ├── pages.test                  # Next JS Pages tests (this avoids tests to be treated as a Next.js pages)
│   ├── styles                      # Styles folder
│   ├── templates                   # Templates folder
│   ├── utils                       # Utilities folder
│   └── validations                 # Validation schemas
├── tailwind.config.js              # Tailwind CSS configuration
└── tsconfig.json                   # TypeScript configuration
```
