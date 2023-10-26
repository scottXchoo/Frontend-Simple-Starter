# Simple Starter & Boilerplate for NextJS 13+, Tailwind CSS 3.3 and TypeScript

> Inspired by "[Next-js-Boilerplate](https://github.com/ixartz/Next-js-Boilerplate)".

I love [Next-js-Boilerplate](https://github.com/ixartz/Next-js-Boilerplate) project, but there are some libraries I don't want to use and it was heavy & difficult to use. If you need more libraries such as testing, please use this project. (Thanks to [Remi Wg](https://github.com/ixartz))

I made a simpler Next.js starter & boilerplate for beginners. It's a project with only Next.js, Tailwind CSS and TypeScript. I hope you can use it well 🙇🏻‍♂️

Clone this project and use it to create your own [Next.js](https://nextjs.org/) project.

## Features
### **"Developer experience first"**

- ⚡ Next.js with App Router and Page Router support
- 🔥 Type checking TypeScript
- 💎 Integrate with Tailwind CSS
- ✅ Strict Mode for TypeScript and React 18
- 🗂️ Folder Structure inspired by [Naver](https://recruit.navercorp.com/), [Toss](https://toss.im/career), [Kakao](https://careers.kakao.com/index) etc
- 📏 Linter with ESLint (default NextJS, NextJS Core Web Vitals, Tailwind CSS and Airbnb configuration)
- 💖 Code Formatter with Prettier

## Requirements

- Node.js 16+ and npm

## Getting Started

Run the following command on your local environment:

```
git clone --depth=1 https://github.com/scottXchoo/Simple_Starter_for_NextJS.git project-name
cd project-name
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
├── README.md                     # README file
├── public                        # Public assets folder
├── src
│   ├── app                       # Next JS App (App Router)
│   ├── components                # React components
│   ├── libs                      # 3rd party libraries
│   ├── pages                     # Next JS Pages (page router)
│   ├── styles                    # Styles folder
│   └── utils                     # Utilities folder
├── tailwind.config.js            # Tailwind CSS configuration
└── tsconfig.json                 # TypeScript configuration
```

## Contributions
Everyone is welcome to contribute to this project. Feel free to open an issue if you have question or found a bug. Totally open to any suggestions and improvements.
