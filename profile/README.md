My old projects.

I probably have many archived projects because I was quite particular, rigid, and perfectionist since an adolescent. As a result, I have had to unlearn those bad
habits and traits through writing these apps. Of course, lack of experience and interest are other contributing factors to these archived projects. Besides learning
the concrete skills, these projects helped me improve and tune my personal coding methodology and technique. This document lists notable projects that I have worked
on, and what they were about and what I learned.

Some include (roughly chronologically):

- [word-finder](https://github.com/fox-archives/word-finder)
  - Like scrabble for the terminal
  - My first "large" first project
  - Graded as final project for class [AP Computer Science A](https://apstudents.collegeboard.org/courses/ap-computer-science-a)
  - Contains my first real-world [shell script](https://github.com/fox-archives/word-finder/blob/master/run.sh)
  - skills: Git, Java, Bash
- [portable-workstation](https://github.com/fox-archives/portable-workstation)
  - Dotfile bootstrapper for Windows
  - My first project outside of school
  - skills: Git, PowerShell, Bash
- [appliance-manager](https://github.com/fox-archives/appliance-manager)
  - Supposed to be an IoT tracker
  - My first hackathon project
  - Learned about my perfectionist tendencies the hard way
  - skills: Git, VueJS, Python, Flask
- [sigag](https://github.com/fox-archives/sigag)
  - Desktop app implementing a [pomodoro timer](https://en.wikipedia.org/wiki/Pomodoro_Technique)
  - Likely first real-world project with HTML, CSS
  - Likely first project using npm
  - Described in my blog post [_Frontend Web Development: My First Year_](https://hyperupcall.github.io/blog/posts/front-end-web-dev-a-years-reflection)
  - skills: Git, NodeJS, Electron, HTML, CSS, JavaScript
- [baeuda](https://github.com/fox-archives/baeuda)
  - Desktop app for studying flashcards
  - Described in my blog post [_Frontend Web Development: My First Year_](https://hyperupcall.github.io/blog/posts/front-end-web-dev-a-years-reflection)
  - skills: Git, NodeJS, Electron, HTML, CSS, JavaScript
- [periodic-table](https://github.com/fox-archives/periodic-table), [periodic-table-v2](https://github.com/fox-archives/periodic-table-v2)
  - Fully responsive [periodic table](https://en.wikipedia.org/wiki/Periodic_table) for the web
  - First full-stack project
  - First time I deployed to cloud (DigitalOcean VM) and registered a domain (aperiodictable.com, chemtable.app)
  - Created to rival [ptable.com](https://ptable.com), since at the time it was not implement responsive design
  - Wrote v2 as an improvement, but stalled due to performance issues I could not fix at the time
  - Described in my blog post [_Frontend Web Development: My First Year_](https://hyperupcall.github.io/blog/posts/front-end-web-dev-a-years-reflection)
  - skills: Git, NodeJS, ExpressJS, GraphQL, Gulp, VueJS, HTML, SCSS, JavaScript, [Mathematica](https://www.wolfram.com/mathematica)
- [hacklang-sucrase](https://github.com/fox-archives/hacklang-sucrase)
  - Custom "Version" of JavaScript with keywords replaced with friends' names
  - Implemented first with [Babel](https://github.com/babel/babel), then with [Sucrase](https://github.com/alangpierce/sucrase)
  - skills: Git, JavaScript, Babel, compilers
- [fox-night](https://github.com/fox-archives/fox-night)
  - Wrote so me and my friends from [Hack Club](https://hackclub.com) could watch movies together
  - skills: Git, NodeJS, Ansible, Terraform, CSS, EJS, TypeScript, JavaScript
- [fox-suite](https://github.com/fox-archives/fox-suite)
  - Configuration manager for web development
  - Learned how wrapping well-known tools (on the command line) could be very poor for DX
  - Learned that custom configuration should be in few places as possible
  - Learned that configuration shouldn't need to be migrated to specific directories
  - Learned the imporance of writing code that solves an actual problem
  - skills: Git, NodeJS, TypeScript, monorepos, [Lerna](https://github.com/lerna/lerna), [pnpm](https://github.com/pnpm/pnpm)
- [glue](https://github.com/fox-archives/glue)
  - Configuration Manager
  - Learned how bloated requirements and ambitious goals leads to poor outcomes
  - Learned the hard way of choosing the wrong language
- [dotfox](https://github.com/fox-archives/dotfox)
  - Dotfile manager (symlinker)
  - Worked quite well until I wrote [dotmgr](https://github.com/hyperupcall/dotmgr), which supercedes it
  - skills: Git, [Nim](https://github.com/nim-lang/Nim)
- [tails](https://github.com/fox-archives/tails)
  - All in one solution for managing programming projects
  - Learned (yet again) about being too ambitious, over-engineering solutions
  - Learned what TDD is _not_
  - skills: Git, [gRPC](https://grpc.io), [NATS.io](https://nats.io), Docker, Typescript, JavaScript
- [typescript-runtime-transpiler](https://github.com/fox-archives/typescript-runtime-transpiler)
  - Transpiles TypeScript/JavaScript written for the NodeJS runtime environment to [Deno](https://deno.com)
  - Learned (yet again) of using technology that I did not need to use (because it made things harder) (Babel-like monorepo pattern)
  - Solves the same use case as [Denoify](https://github.com/garronej/denoify)
  - skills: Git, Deno, parsers, ASTs
- [bats-support](https://github.com/fox-archives/bats-support), [bats-file](https://github.com/fox-archives/bats-file), and [bats-assert](https://github.com/fox-archives/bats-assert)
  - These were initially forked from [bats-core](https://github.com/bats-core) so improvements, bug fixes, and merges could be made quicker
  - Initially created for [bats-all](https://github.com/bash-bastion/bats-all)
  - Archived because upstream made the same improvements
  - skills: Git, Git Subtree, Bash

Some not included in this organization include:

- [carnival](https://github.com/replit-discord/carnival)
  - Supposed to be a place for the [replit](https://replit.com) community to deploy games
  - Learned how I wasted so time on tooling (ESLint, Webpack, Babel, PostCSS, etc.)
  - skills: Git, VueJS, [NuxtJS](https://nuxt.com), SCSS, Postgres