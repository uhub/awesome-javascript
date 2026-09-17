# awesome-javascript

A curated list of awesome JavaScript frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Frontend and UI Components](#frontend-and-ui-components)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Search and Indexing](#search-and-indexing)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Computer Vision](#computer-vision)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
* User Interface
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
* Concurrency and Performance
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Science and Math
	* [Mathematics](#mathematics)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [airbnb/javascript](https://github.com/airbnb/javascript) - JavaScript Style Guide
* [Chalarangelo/30-seconds-of-code](https://github.com/Chalarangelo/30-seconds-of-code) - Coding articles to level up your development skills
* [goldbergyoni/nodebestpractices](https://github.com/goldbergyoni/nodebestpractices) - ✅ The Node.js best practices list (July 2026)
* [microsoft/Web-Dev-For-Beginners](https://github.com/microsoft/Web-Dev-For-Beginners) - 24 Lessons, 12 Weeks, Get Started as a Web Developer
* [ryanmcdermott/clean-code-javascript](https://github.com/ryanmcdermott/clean-code-javascript) - Clean Code concepts adapted for JavaScript
* [leonardomso/33-js-concepts](https://github.com/leonardomso/33-js-concepts) - 📜 33 JavaScript concepts every developer should know.
* [Asabeneh/30-Days-Of-JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript) - 30 days of JavaScript programming challenge is a step-by-step guide to learn JavaScript programming language in 30 days. This challenge may take more than 100 days, please just follow your own pace. These videos may help too: https://www.youtube.com/channel/UC7PNRuno1rzYPb1xLa4yktw
* [LeCoupa/awesome-cheatsheets](https://github.com/LeCoupa/awesome-cheatsheets) - 👩‍💻👨‍💻 Awesome cheatsheets for popular programming languages, frameworks and development tools. They include everything you should know in one single file.
* [denysdovhan/wtfjs](https://github.com/denysdovhan/wtfjs) - 🤪 A list of funny and tricky JavaScript examples
* [elsewhencode/project-guidelines](https://github.com/elsewhencode/project-guidelines) - A set of best practices for JavaScript projects
* [Asabeneh/30-Days-Of-React](https://github.com/Asabeneh/30-Days-Of-React) - 30 Days of React challenge is a step by step guide to learn React in 30 days. These videos may help too: https://www.youtube.com/channel/UC7PNRuno1rzYPb1xLa4yktw
* [goldbergyoni/javascript-testing-best-practices](https://github.com/goldbergyoni/javascript-testing-best-practices) - 📗🌐 🚢 Comprehensive and exhaustive JavaScript & Node.js testing best practices (August 2025)
* [MostlyAdequate/mostly-adequate-guide](https://github.com/MostlyAdequate/mostly-adequate-guide) - Mostly adequate guide to FP (in javascript)
* [ruanyf/es6tutorial](https://github.com/ruanyf/es6tutorial) - 《ECMAScript 6入门》是一本开源的 JavaScript 语言教程，全面介绍 ECMAScript 6 新增的语法特性。
* [verekia/js-stack-from-scratch](https://github.com/verekia/js-stack-from-scratch) - 🛠️⚡ Step-by-step tutorial to build a modern JavaScript stack.
* [camsong/You-Dont-Need-jQuery](https://github.com/camsong/You-Dont-Need-jQuery) - Examples of how to do query, style, dom, ajax, event etc like jQuery with plain javascript.
* [you-dont-need/You-Dont-Need-Lodash-Underscore](https://github.com/you-dont-need/You-Dont-Need-Lodash-Underscore) - List of JavaScript methods which you can use natively + ESLint Plugin
* [jonasschmedtmann/complete-javascript-course](https://github.com/jonasschmedtmann/complete-javascript-course) - Starter files, final projects, and FAQ for my Complete JavaScript course
* [getify/Functional-Light-JS](https://github.com/getify/Functional-Light-JS) - Pragmatic, balanced FP in JavaScript. @FLJSBook on twitter.
* [alsotang/node-lessons](https://github.com/alsotang/node-lessons) - :closed_book:《Node.js 包教不包会》 by alsotang
* [nswbmw/N-blog](https://github.com/nswbmw/N-blog) - 《一起学 Node.js》
* [stephentian/33-js-concepts](https://github.com/stephentian/33-js-concepts) - :scroll: 每个 JavaScript 工程师都应懂的33个概念 @leonardomso
* [grab/front-end-guide](https://github.com/grab/front-end-guide) - 📚 Study guide and introduction to the modern front end stack.
* [google/WebFundamentals](https://github.com/google/WebFundamentals) - Former git repo for WebFundamentals on developers.google.com *(archived)*
* [DrkSephy/es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) - ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets
* [TheOdinProject/curriculum](https://github.com/TheOdinProject/curriculum) - The open curriculum for learning web development
* [reactjs/react.dev](https://github.com/reactjs/react.dev) - The React documentation website
* [jhu-ep-coursera/fullstack-course4](https://github.com/jhu-ep-coursera/fullstack-course4) - Example code for HTML, CSS, and Javascript for Web Developers Coursera Course
* [hakanyalcinkaya/kodluyoruz-frontend-101-egitimi](https://github.com/hakanyalcinkaya/kodluyoruz-frontend-101-egitimi) - Kodluyoruz için Hazırladığım Video Eğitim Seti Repo'sudur. Tüm Eğitimlerime: https://linktr.ee/hakanyalcinkaya adresinden ulaşabilirsiniz.
* [gibbok/typescript-book](https://github.com/gibbok/typescript-book) - The Concise TypeScript Book: A Concise Guide to Effective Development in TypeScript. Free and Open Source.
* [liyupi/codefather](https://github.com/liyupi/codefather) - 程序员鱼皮的编程宝典 ⭐️ 2026年最全编程学习路线图！包含Java学习路线、前端学习路线、Python学习路线、C++学习路线、算法学习路线、计算机基础学习路线、AI应用开发学习路线、AI Agent开发学习路线等。提供编程入门教程、AI大模型应用开发教程、RAG开发实战、MCP开发教程、Prompt工程指南、LLM应用开发、技术知识分享、学习资源推荐、项目实战教程、热门面试题、求职经验、简历优化、编程自学指南等内容，适用于所有零基础学编程、学习AI开发、转行程序员、计算机专业学生、求职找工作的同学 💎 编程学习，就来编程导航！
* [mouredev/hello-javascript](https://github.com/mouredev/hello-javascript) - Curso para aprender el lenguaje de programación JavaScript desde cero y para principiantes. +120 lecciones, 14 horas en vídeo y 220 ejercicios.
* [ljianshu/Blog](https://github.com/ljianshu/Blog) - 关注基础知识，打造优质前端博客，公众号[前端工匠]的作者
* [jawil/blog](https://github.com/jawil/blog) - Too young, too simple. Sometimes, naive & stupid 🐌
* [amejiarosario/dsa.js-data-structures-algorithms-javascript](https://github.com/amejiarosario/dsa.js-data-structures-algorithms-javascript) - 🥞Data Structures and Algorithms explained and implemented in JavaScript + eBook
* [andreasbm/web-skills](https://github.com/andreasbm/web-skills) - A visual overview of useful skills to learn as a web developer
* [Bogdan-Lyashenko/Under-the-hood-ReactJS](https://github.com/Bogdan-Lyashenko/Under-the-hood-ReactJS) - Entire React code base explanation by visual block schemes (Stack version)
* [pomber/didact](https://github.com/pomber/didact) - A DIY guide to build your own React
* [nao-sabemos-js/You-Dont-Know-JS](https://github.com/nao-sabemos-js/You-Dont-Know-JS) - 📗📒 (PT-Br translation) JS Book Series.
* [braziljs/eloquente-javascript](https://github.com/braziljs/eloquente-javascript) - Tradução do livro "Eloquent JavaScript" 4ª edição, por Marijn Haverbeke
* [KieSun/all-of-frontend](https://github.com/KieSun/all-of-frontend) - 你想知道的前端内容都在这
* [hiteshchoudhary/js-hindi-youtube](https://github.com/hiteshchoudhary/js-hindi-youtube) - A code repo for javascript series at Chai aur code youtube channel
* [felixge/node-style-guide](https://github.com/felixge/node-style-guide) - A guide for styling your node.js / JavaScript code. Fork & adjust to your taste.
* [felipe-augusto/clean-code-javascript](https://github.com/felipe-augusto/clean-code-javascript) - Conceitos de Código Limpo adaptados em JavaScript (Tradução PT-BR)
* [loiane/javascript-datastructures-algorithms](https://github.com/loiane/javascript-datastructures-algorithms) - :books: collection of JavaScript and TypeScript data structures and algorithms for education purposes. Source code bundle of JavaScript algorithms and data structures book
* [goldbergyoni/nodejs-testing-best-practices](https://github.com/goldbergyoni/nodejs-testing-best-practices) - Beyond the basics of Node.js testing. Including a super-comprehensive best practices list and an example app (April 2025)
* [kdchang/reactjs101](https://github.com/kdchang/reactjs101) - 從零開始學 ReactJS（ReactJS 101）是一本希望讓初學者一看就懂的 React 中文入門教學書，由淺入深學習 React.js 生態系 (Flux, Redux, React Router, ImmutableJS, React Native, Relay/GraphQL etc.)。
* [berwin/Blog](https://github.com/berwin/Blog) - 记录成长的过程
* [lessfish/underscore-analysis](https://github.com/lessfish/underscore-analysis) - underscore-1.8.3.js 源码解读 & 系列文章（完）
* [tyroprogrammer/learn-react-app](https://github.com/tyroprogrammer/learn-react-app) - Application that will help you learn React fundamentals. Install this application locally - there's tutorial, code snippets and exercises. The main objective of this project is to help you get off the ground with React!
* [azat-co/practicalnode](https://github.com/azat-co/practicalnode) - Practical Node.js, 1st and 2nd Editions [Apress] 📓
* [FrontendMasters/front-end-handbook-2017](https://github.com/FrontendMasters/front-end-handbook-2017) - 2017 edition of our front-end development guide
* [wesbos/Advanced-React](https://github.com/wesbos/Advanced-React) - Starter Files and Solutions for Full Stack Advanced React and GraphQL
* [andersontr15/clean-code-javascript-es](https://github.com/andersontr15/clean-code-javascript-es) - Clean Code traducido al Español
* [WTFAcademy/WTF-Ethers](https://github.com/WTFAcademy/WTF-Ethers) - 我最近在重新学ethers.js，巩固一下细节，也写一个“WTF Ethers.js极简入门”，供小白们使用，每周更新1-3讲。Now supports English! 官网: https://wtf.academy
* [latentflip/loupe](https://github.com/latentflip/loupe) - Visualizing the javascript runtime at runtime
* [sl1673495/blogs](https://github.com/sl1673495/blogs) - :book: 全网 100w+ 阅读量的进阶前端技术博客仓库，Vue 源码解析，React 深度实践，TypeScript 进阶艺术，工程化，性能优化实践……
* [marijnh/Eloquent-JavaScript](https://github.com/marijnh/Eloquent-JavaScript) - The sources for the Eloquent JavaScript book
* [workshopper/javascripting](https://github.com/workshopper/javascripting) - Learn JavaScript by adventuring around in the terminal.
* [CleverProgrammers/JavaScript-Course-by-Clever-Programmer-](https://github.com/CleverProgrammers/JavaScript-Course-by-Clever-Programmer-) - This is a full JavaScript course by Clever Programmer
* [YvetteLau/Blog](https://github.com/YvetteLau/Blog) - 【前端进阶】优质博文
* [vasanthk/js-bits](https://github.com/vasanthk/js-bits) - ✨ JavaScript concepts with code ✨
* [cheatsheet1999/CloudCollection](https://github.com/cheatsheet1999/CloudCollection) - Notes for Software Engineers on infrastructure and distributed systems. Covers common data structure and algorithms, web concepts, and more!
* [dwyl/learn-tdd](https://github.com/dwyl/learn-tdd) - :white_check_mark: A brief introduction to Test Driven Development (TDD) in JavaScript (Complete Beginner's Step-by-Step Tutorial)
* [chetannada/Namaste-React](https://github.com/chetannada/Namaste-React) - ❤ Namaste React Live Course from Zero to Hero 🚀 by Akshay Saini(Founder of NamasteDev). This repository for Assignment & Class Notes taken during Namaste React Live Course #namaste #javascript #react
* [mike-works/pwa-fundamentals](https://github.com/mike-works/pwa-fundamentals) - 👨‍🏫 Mike & Steve's Progressive Web Fundamentals Course
* [tooto1985/js-array-operations](https://github.com/tooto1985/js-array-operations) - 20 kinds of methods to get to know a JavaScript array operations.

### Examples and Exercises

* [trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) - 📝 Algorithms and data structures implemented in JavaScript with explanations and links to further readings
* [azl397985856/leetcode](https://github.com/azl397985856/leetcode) - LeetCode Solutions: A Record of My Problem Solving Journey.( leetcode题解，记录自己的leetcode解题之路。)
* [sudheerj/reactjs-interview-questions](https://github.com/sudheerj/reactjs-interview-questions) - List of top 500 ReactJS Interview Questions & Answers....Coding exercise questions are coming soon!!
* [yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook) - Front End interview preparation materials for busy engineers (updated for 2026)
* [TheAlgorithms/JavaScript](https://github.com/TheAlgorithms/JavaScript) - Algorithms and Data Structures implemented in JavaScript for beginners, following best practices.
* [tastejs/todomvc](https://github.com/tastejs/todomvc) - Helping you select a JavaScript framework - Todo apps for React.js, Angular, Vue and many more
* [sudheerj/javascript-interview-questions](https://github.com/sudheerj/javascript-interview-questions) - List of 1000 JavaScript Interview Questions
* [Advanced-Frontend/Daily-Interview-Question](https://github.com/Advanced-Frontend/Daily-Interview-Question) - 我是依扬（木易杨），公众号「高级前端进阶」作者，每天搞定一道前端大厂面试题，祝大家天天进步，一年后会看到不一样的自己。
* [haizlin/fe-interview](https://github.com/haizlin/fe-interview) - 前端面试每日 3+1，以面试题来驱动学习，提倡每日学习与思考，每天进步一点！每天早上5点纯手工发布面试题（死磕自己，愉悦大家），6000+道前端面试题全面覆盖，HTML/CSS/JavaScript/Vue/React/Nodejs/TypeScript/ECMAScritpt/Webpack/Jquery/小程序/软技能……
* [bradtraversy/vanillawebprojects](https://github.com/bradtraversy/vanillawebprojects) - Mini projects built with HTML5, CSS & JavaScript. No frameworks or libraries
* [webrtc/samples](https://github.com/webrtc/samples) - WebRTC Web demos and samples
* [Chalarangelo/30-seconds-of-interviews](https://github.com/Chalarangelo/30-seconds-of-interviews) - A curated collection of common interview questions to help you prepare for your next interview. *(archived)*
* [olistic/warriorjs](https://github.com/olistic/warriorjs) - 🏰 An exciting game of programming and Artificial Intelligence
* [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) - Collection of classic computer science paradigms, algorithms, and approaches written in JavaScript.
* [midudev/preguntas-entrevista-react](https://github.com/midudev/preguntas-entrevista-react) - Preguntas típicas sobre React para entrevistas de trabajo ⚛️
* [mgechev/javascript-algorithms](https://github.com/mgechev/javascript-algorithms) - 💻 JavaScript implementations of computer science algorithms
* [bencodezen/vue-enterprise-boilerplate](https://github.com/bencodezen/vue-enterprise-boilerplate) - An ever-evolving, very opinionated architecture and dev environment for new Vue SPA projects using Vue CLI.
* [lgwebdream/FE-Interview](https://github.com/lgwebdream/FE-Interview) - 🔥🔥🔥 前端面试，独有前端面试题详解，前端面试刷题必备，1000+前端面试真题，Html、Css、JavaScript、Vue、React、Node、TypeScript、Webpack、算法、网络与安全、浏览器
* [learning-zone/website-templates](https://github.com/learning-zone/website-templates) - 150+ HTML5 Website Templates
* [Data-Camp/WeApp_Demos](https://github.com/Data-Camp/WeApp_Demos) - 持续更新中的微信小程序和小游戏的源码案例库。目前涵盖了120多个微信小程序或小游戏。
* [Chalarangelo/30-seconds-of-react](https://github.com/Chalarangelo/30-seconds-of-react) - Short React code snippets for all your development needs *(archived)*
* [kriasoft/react-firebase-starter](https://github.com/kriasoft/react-firebase-starter) - Boilerplate (seed) project for creating web apps with React.js, GraphQL.js and Relay
* [kolodny/exercises](https://github.com/kolodny/exercises) - Some basic javascript coding challenges and interview questions
* [mdn/dom-examples](https://github.com/mdn/dom-examples) - Code examples that accompany various MDN DOM and Web API documentation pages
* [lxieyang/chrome-extension-boilerplate-react](https://github.com/lxieyang/chrome-extension-boilerplate-react) - A Chrome Extensions boilerplate using React 18 and Webpack 5. *(archived)*
* [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - Sample apps for Electron
* [async-labs/builderbook](https://github.com/async-labs/builderbook) - Open source web application to learn JS stack: React, Material-UI, Next.js, Node.js, Express.js, Mongoose, MongoDB database.
* [rohan-paul/Awesome-JavaScript-Interviews](https://github.com/rohan-paul/Awesome-JavaScript-Interviews) - Popular JavaScript / React / Node / Mongo stack Interview questions and their answers. Many of them, I faced in actual interviews and ultimately got my first full-stack Dev job :)
* [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) - All the 23 (GoF) design patterns implemented in Javascript *(archived)*
* [coffe1891/frontend-hard-mode-interview](https://github.com/coffe1891/frontend-hard-mode-interview) - 《前端内参》，有关于JavaScript、编程范式、设计模式、软件开发的艺术等大前端范畴内的知识分享，旨在帮助前端工程师们夯实技术基础以通过一线互联网企业技术面试。
* [adrianhajdin/portfolio_website](https://github.com/adrianhajdin/portfolio_website) - Tutorial created by Enyel Sequeira, taught by JavaScript Mastery
* [ronami/minipack](https://github.com/ronami/minipack) - 📦 A simplified example of a modern module bundler written in JavaScript
* [xdevplatform/samples](https://github.com/xdevplatform/samples) - Sample code for the X API v2 endpoints
* [careercup/CtCI-6th-Edition-JavaScript](https://github.com/careercup/CtCI-6th-Edition-JavaScript) - Cracking the Coding Interview 6th Ed. JavaScript Solutions
* [GoogleCloudPlatform/nodejs-docs-samples](https://github.com/GoogleCloudPlatform/nodejs-docs-samples) - Node.js samples for Google Cloud Platform products.
* [dragonir/3d](https://github.com/dragonir/3d) - Three.js 3D项目，包含冰墩墩🐼、数字城市🏙、3D人像👤、车模展示🚗、塞尔达传说🗡等一些3D趣味演示页面，持续优化中...访问链接如下👇
* [azl397985856/fe-interview](https://github.com/azl397985856/fe-interview) - 宇宙最强的前端面试指南 (https://lucifer.ren/fe-interview)
* [ivarprudnikov/webpack-static-html-pages](https://github.com/ivarprudnikov/webpack-static-html-pages) - Webpack template/example with multiple static html pages *(archived)*
* [dnshi/Leetcode](https://github.com/dnshi/Leetcode) - Leetcode problems & solutions
* [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) - Atwood's Law applied to CS101 - Classic algorithms and data structures implemented in JavaScript

## Language and Tooling

### Compilers and Interpreters

* [nodejs/node](https://github.com/nodejs/node) - Node.js JavaScript runtime ✨🐢🚀✨
* [acornjs/acorn](https://github.com/acornjs/acorn) - A small, fast, JavaScript-based JavaScript parser
* [facebook/hermes](https://github.com/facebook/hermes) - A JavaScript engine optimized for running React Native.
* [WebKit/WebKit](https://github.com/WebKit/WebKit) - Home of the WebKit project, the browser engine used by Safari, Mail, App Store and many other applications on macOS, iOS and Linux.
* [facebook/jscodeshift](https://github.com/facebook/jscodeshift) - A JavaScript codemod toolkit.
* [chakra-core/ChakraCore](https://github.com/chakra-core/ChakraCore) - ChakraCore is an open source Javascript engine with a C API.
* [awslabs/llrt](https://github.com/awslabs/llrt) - LLRT (Low Latency Runtime) is an experimental, lightweight JavaScript runtime designed to address the growing demand for fast and efficient Serverless applications.
* [google/traceur-compiler](https://github.com/google/traceur-compiler) - Traceur is a JavaScript.next-to-JavaScript-of-today compiler *(archived)*
* [google/closure-compiler](https://github.com/google/closure-compiler) - A JavaScript checker and optimizer.
* [fkling/astexplorer](https://github.com/fkling/astexplorer) - A web tool to explore the ASTs generated by various parsers.
* [imba/imba](https://github.com/imba/imba) - 🐤 The friendly full-stack language
* [svaarala/duktape](https://github.com/svaarala/duktape) - Duktape - embeddable Javascript engine with a focus on portability and compact footprint
* [thx/gogocode](https://github.com/thx/gogocode) - GoGoCode is a transformer for JavaScript/Typescript/HTML based on AST but providing a more intuitive API.
* [lebab/lebab](https://github.com/lebab/lebab) - Turn your ES5 code into readable ES6. Lebab does the opposite of what Babel does.
* [ohmjs/ohm](https://github.com/ohmjs/ohm) - A library and language for building parsers, interpreters, compilers, etc.
* [CanadaHonk/porffor](https://github.com/CanadaHonk/porffor) - An ahead-of-time JavaScript compiler
* [pegjs/pegjs](https://github.com/pegjs/pegjs) - PEG.js: Parser generator for JavaScript
* [ballercat/walt](https://github.com/ballercat/walt) - :zap: Walt is a JavaScript-like syntax for WebAssembly text format :zap:
* [mozilla/rhino](https://github.com/mozilla/rhino) - Rhino is an open-source implementation of JavaScript written entirely in Java
* [sweet-js/sweet-core](https://github.com/sweet-js/sweet-core) - Sweeten your JavaScript. *(archived)*
* [zaach/jison](https://github.com/zaach/jison) - Bison in JavaScript.
* [facebook/regenerator](https://github.com/facebook/regenerator) - Source transformer enabling ECMAScript 6 generator functions in JavaScript-of-today. *(archived)*
* [just-js/just](https://github.com/just-js/just) - the only javascript runtime to hit no.1 on techempower :fire:
* [kach/nearley](https://github.com/kach/nearley) - 📜🔜🌲 Simple, fast, powerful parser toolkit for JavaScript.
* [noflo/noflo](https://github.com/noflo/noflo) - Flow-based programming for JavaScript
* [babel/babel-preset-env](https://github.com/babel/babel-preset-env) - PSA: this repo has been moved into babel/babel --> *(archived)*
* [codemix/babel-plugin-contracts](https://github.com/codemix/babel-plugin-contracts) - Design by Contract for JavaScript via a Babel plugin.
* [codemix/babel-plugin-macros](https://github.com/codemix/babel-plugin-macros) - Hygienic, non-syntactic macros for JavaScript via a Babel plugin.

### Build Systems

* [webpack/webpack](https://github.com/webpack/webpack) - A bundler for javascript and friends. Packs many modules into a few bundled assets. Code Splitting allows for loading parts of the application on demand. Through "loaders", modules can be CommonJs, AMD, ES6 modules, CSS, Images, JSON, Coffeescript, LESS, ... and your custom stuff.
* [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) - The zero configuration build tool for the web. 📦🚀
* [11ty/buildawesome](https://github.com/11ty/buildawesome) - A simpler site generator. Transforms a directory of templates (of varying types) into HTML.
* [browserify/browserify](https://github.com/browserify/browserify) - browser-side require() the node.js way
* [mishoo/UglifyJS](https://github.com/mishoo/UglifyJS) - JavaScript parser / mangler / compressor / beautifier toolkit
* [requirejs/requirejs](https://github.com/requirejs/requirejs) - A file and module loader for JavaScript
* [gruntjs/grunt](https://github.com/gruntjs/grunt) - Grunt: The JavaScript Task Runner
* [uncss/uncss](https://github.com/uncss/uncss) - Remove unused styles from CSS
* [terser/terser](https://github.com/terser/terser) - 🗜 JavaScript parser, mangler and compressor toolkit for ES6+
* [mishoo/UglifyJS-old](https://github.com/mishoo/UglifyJS-old) - JavaScript parser / mangler / compressor / beautifier library for NodeJS
* [umdjs/umd](https://github.com/umdjs/umd) - UMD (Universal Module Definition) patterns for JavaScript modules that work everywhere.
* [brunch/brunch](https://github.com/brunch/brunch) - 🍴 Web applications made easy. Since 2011.
* [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) - A CLI tool to run multiple npm-scripts in parallel or sequential.
* [react/metro](https://github.com/react/metro) - 🚇 The JavaScript bundler for React Native
* [insin/nwb](https://github.com/insin/nwb) - A toolkit for React, Preact, Inferno & vanilla JS apps, React libraries and other npm modules for the web, with no configuration (until you need it) *(archived)*
* [egoist/poi](https://github.com/egoist/poi) - ⚡A zero-config bundler for JavaScript applications. *(archived)*
* [kangax/html-minifier](https://github.com/kangax/html-minifier) - Javascript-based HTML compressor/minifier (with Node.js support)
* [jaredpalmer/backpack](https://github.com/jaredpalmer/backpack) - 🎒 Backpack is a minimalistic build system for Node.js projects.
* [fuse-box/fuse-box](https://github.com/fuse-box/fuse-box) - A blazing fast js bundler/loader with a comprehensive API :fire: *(archived)*
* [yeoman/yo](https://github.com/yeoman/yo) - CLI tool for running Yeoman generators
* [neutrinojs/neutrino](https://github.com/neutrinojs/neutrino) - Create and build modern JavaScript projects with zero initial configuration. *(archived)*
* [ember-cli/ember-cli](https://github.com/ember-cli/ember-cli) - The Ember.js command line utility.
* [mozilla/web-ext](https://github.com/mozilla/web-ext) - A command line tool to help build, run, and test web extensions
* [jakejs/jake](https://github.com/jakejs/jake) - JavaScript build tool, similar to Make or Rake. Built to work with Node.js.
* [electron/packager](https://github.com/electron/packager) - Customize and package your Electron app with OS-specific bundles (.app, .exe, etc.) via JS or CLI
* [tbranyen/use-amd](https://github.com/tbranyen/use-amd) - An AMD plugin for consuming globally defined JavaScript.

### Package Management

* [yarnpkg/yarn](https://github.com/yarnpkg/yarn) - The 1.x line is frozen - features and bugfixes now happen on https://github.com/yarnpkg/berry
* [lerna/lerna](https://github.com/lerna/lerna) - Lerna is a fast, modern build system for managing and publishing multiple JavaScript/TypeScript packages from the same repository.
* [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) - A lightweight Node.js private proxy registry
* [bower/bower](https://github.com/bower/bower) - A package manager for the web
* [npm/cli](https://github.com/npm/cli) - the package manager for JavaScript
* [sindresorhus/np](https://github.com/sindresorhus/np) - A better `npm publish`
* [entropic-dev/entropic](https://github.com/entropic-dev/entropic) - 🦝 :package: a package registry for anything, but mostly javascript 🦝 🦝 🦝

### Linters and Formatters

* [prettier/prettier](https://github.com/prettier/prettier) - Prettier is an opinionated code formatter.
* [standard/standard](https://github.com/standard/standard) - 🌟 JavaScript Style Guide, with linter & automatic code fixer
* [eslint/eslint](https://github.com/eslint/eslint) - Find and fix problems in your JavaScript code.
* [jsx-eslint/eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) - React-specific linting rules for ESLint
* [jshint/jshint](https://github.com/jshint/jshint) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code
* [beautifier/js-beautify](https://github.com/beautifier/js-beautify) - Beautifier for javascript
* [xojs/xo](https://github.com/xojs/xo) - ❤️ JavaScript/TypeScript linter (ESLint wrapper) with great defaults
* [sverweij/dependency-cruiser](https://github.com/sverweij/dependency-cruiser) - Validate and visualize dependencies. Your rules. JavaScript, TypeScript, CoffeeScript. ES6, CommonJS, AMD.
* [Bogdan-Lyashenko/js-code-to-svg-flowchart](https://github.com/Bogdan-Lyashenko/js-code-to-svg-flowchart) - js2flowchart - a visualization library to convert any JavaScript code into beautiful SVG flowchart. Learn other’s code. Design your code. Refactor code. Document code. Explain code.
* [import-js/eslint-plugin-import](https://github.com/import-js/eslint-plugin-import) - ESLint plugin with rules that help validate proper imports.
* [sindresorhus/eslint-plugin-unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn) - More than 300 powerful ESLint rules
* [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) - :arrow_heading_up: JavaScript Code Style checker (unmaintained) *(archived)*
* [vuejs/eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue) - Official ESLint plugin for Vue.js
* [es-analysis/plato](https://github.com/es-analysis/plato) - JavaScript source code visualization, static analysis, and complexity tool
* [prettier/prettier-eslint](https://github.com/prettier/prettier-eslint) - Code :arrow_right: `prettier` :arrow_right: `eslint --fix` :arrow_right: Formatted Code :sparkles:
* [jslint-org/jslint](https://github.com/jslint-org/jslint) - JSLint, The JavaScript Code Quality and Coverage Tool
* [geuis/helium-css](https://github.com/geuis/helium-css) - Helium - javascript tool to scan your site and show unused CSS
* [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code
* [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) - ⚙️ The static code analysis tool you need for your HTML
* [babel/babel-eslint](https://github.com/babel/babel-eslint) - :tokyo_tower: A wrapper for Babel's parser used for ESLint (renamed to @babel/eslint-parser) *(archived)*
* [JSMonk/hegel](https://github.com/JSMonk/hegel) - An advanced static type checker *(archived)*
* [gcanti/tcomb](https://github.com/gcanti/tcomb) - Type checking and DDD for JavaScript *(archived)*
* [kangax/kratko.js](https://github.com/kangax/kratko.js) - Simple tool to help refactor Javascript

## Web

### Web Frameworks

* [expressjs/express](https://github.com/expressjs/express) - Fast, unopinionated, minimalist web framework for node.
* [meteor/meteor](https://github.com/meteor/meteor) - Meteor, the JavaScript App Platform
* [hexojs/hexo](https://github.com/hexojs/hexo) - A fast, simple & powerful blog framework, powered by Node.js.
* [emberjs/ember.js](https://github.com/emberjs/ember.js) - Ember.js - A JavaScript framework for creating ambitious web applications
* [keystonejs/keystone-classic](https://github.com/keystonejs/keystone-classic) - Node.js CMS and web app framework *(archived)*
* [jaredpalmer/razzle](https://github.com/jaredpalmer/razzle) - ✨ Create server-rendered universal JavaScript applications with no configuration
* [senchalabs/connect](https://github.com/senchalabs/connect) - Connect is an extensible HTTP server framework for node using "plugins" known as middleware.
* [nuejs/nue](https://github.com/nuejs/nue) - Fastest way to build modern websites
* [metalsmith/metalsmith](https://github.com/metalsmith/metalsmith) - An extremely simple, pluggable static site generator for Node.js
* [rethinkdb/horizon](https://github.com/rethinkdb/horizon) - Horizon is a realtime, open-source backend for JavaScript apps.
* [expressjs/session](https://github.com/expressjs/session) - Simple session middleware for Express
* [expressjs/cors](https://github.com/expressjs/cors) - Node.js CORS middleware
* [remoteinterview/zero](https://github.com/remoteinterview/zero) - Zero is a web server to simplify web development.
* [livebud/bud](https://github.com/livebud/bud) - The Full-Stack Web Framework for Go
* [flatiron/director](https://github.com/flatiron/director) - a tiny and isomorphic URL router for JavaScript
* [expressjs/body-parser](https://github.com/expressjs/body-parser) - Node.js body parsing middleware
* [krakenjs/kraken-js](https://github.com/krakenjs/kraken-js) - An express-based Node.js web application bootstrapping module.
* [meanjs/mean](https://github.com/meanjs/mean) - MEAN.JS - Full-Stack JavaScript Using MongoDB, Express, AngularJS, and Node.js - *(archived)*
* [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) - A full-featured, open-source content management framework built with Node.js that empowers organizations by combining in-context editing and headless architecture in a full-stack JS environment.
* [hoodiehq/hoodie](https://github.com/hoodiehq/hoodie) - :dog: The Offline First JavaScript Backend
* [totaljs/framework](https://github.com/totaljs/framework) - Node.js framework
* [tighten/ziggy](https://github.com/tighten/ziggy) - Use your Laravel routes in JavaScript.
* [spine/spine](https://github.com/spine/spine) - Lightweight MVC library for building JavaScript applications
* [quirkey/sammy](https://github.com/quirkey/sammy) - Sammy is a tiny javascript framework built on top of jQuery, It's RESTful Evented Javascript.
* [aurajs/aura](https://github.com/aurajs/aura) - A scalable, event-driven JavaScript architecture for developing component-based applications.
* [expressjs/compression](https://github.com/expressjs/compression) - Node.js compression middleware
* [astoilkov/jsblocks](https://github.com/astoilkov/jsblocks) - 2012 UI framework (I was 20 years old, React didn't exist, inspired by Knockout)
* [enyojs/enyo](https://github.com/enyojs/enyo) - A JavaScript application framework emphasizing modularity and encapsulation

### HTTP and Networking Clients

* [axios/axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js
* [ccxt/ccxt](https://github.com/ccxt/ccxt) - A unified trading API with more than 100 crypto exchanges and prediction markets in JavaScript / TypeScript / Python / C# / PHP / Go / Java / Rust
* [discordjs/discord.js](https://github.com/discordjs/discord.js) - A powerful JavaScript library for interacting with the Discord API
* [JakeChampion/fetch](https://github.com/JakeChampion/fetch) - A window.fetch JavaScript polyfill.
* [pagekit/vue-resource](https://github.com/pagekit/vue-resource) - The HTTP client for Vue.js *(archived)*
* [wendux/fly](https://github.com/wendux/fly) - :rocket: Supporting request forwarding and Promise based HTTP client for all JavaScript runtimes.
* [jpillora/xdomain](https://github.com/jpillora/xdomain) - A pure JavaScript CORS alternative
* [sendgrid/sendgrid-nodejs](https://github.com/sendgrid/sendgrid-nodejs) - The Official Twilio SendGrid Led, Community Driven Node.js API Library
* [BrasilAPI/cep-promise](https://github.com/BrasilAPI/cep-promise) - Busca por CEP integrado diretamente aos serviços dos Correios, ViaCEP e outros (Node.js e Browser)
* [ded/reqwest](https://github.com/ded/reqwest) - browser asynchronous http requests

### API and GraphQL

* [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) - 网易云音乐 Node.js API service *(archived)*
* [swagger-api/swagger-ui](https://github.com/swagger-api/swagger-ui) - Swagger UI is a collection of HTML, JavaScript, and CSS assets that dynamically generate beautiful documentation from a Swagger-compliant API.
* [Netflix/falcor](https://github.com/Netflix/falcor) - A JavaScript library for efficient data fetching
* [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) - Swagger module for node.js *(archived)*
* [hasura/graphqurl](https://github.com/hasura/graphqurl) - curl for GraphQL with autocomplete, subscriptions and GraphiQL. Also a dead-simple universal javascript GraphQL client.
* [glennreyes/graphpack](https://github.com/glennreyes/graphpack) - ☄️ A minimalistic zero-config GraphQL server.

### Frontend and UI Components

* [react/react](https://github.com/react/react) - The library for web and native user interfaces.
* [twbs/bootstrap](https://github.com/twbs/bootstrap) - The most popular HTML, CSS, and JavaScript framework for developing responsive, mobile first projects on the web.
* [mui/material-ui](https://github.com/mui/material-ui) - Material UI: Comprehensive React component library that implements Google's Material Design. Free forever.
* [juliangarnier/anime](https://github.com/juliangarnier/anime) - JavaScript animation engine
* [jquery/jquery](https://github.com/jquery/jquery) - jQuery JavaScript Library
* [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) - A professional front-end template for building fast, robust, and adaptable web apps or sites.
* [bigskysoftware/htmx](https://github.com/bigskysoftware/htmx) - </> htmx - high power tools for HTML
* [DavidHDev/react-bits](https://github.com/DavidHDev/react-bits) - An open source collection of animated, interactive & fully customizable React components for building memorable websites.
* [Dogfalo/materialize](https://github.com/Dogfalo/materialize) - Materialize, a CSS Framework based on Material Design
* [alvarotrigo/fullPage.js](https://github.com/alvarotrigo/fullPage.js) - fullPage plugin by Alvaro Trigo. Create full screen pages fast and simple
* [zenorocha/clipboard.js](https://github.com/zenorocha/clipboard.js) - :scissors: Modern copy to clipboard. No Flash. Just 3kb gzipped :clipboard:
* [transloadit/uppy](https://github.com/transloadit/uppy) - The next open source file uploader for web browsers :dog:
* [layui/layui](https://github.com/layui/layui) - 一套遵循浏览器原生态开发模式的 Web UI 组件库。
* [VincentGarreau/particles.js](https://github.com/VincentGarreau/particles.js) - A lightweight JavaScript library for creating particles
* [greensock/GSAP](https://github.com/greensock/GSAP) - GSAP (GreenSock Animation Platform), a JavaScript animation library for the modern web
* [vuejs/vuex](https://github.com/vuejs/vuex) - 🗃️ Centralized State Management for Vue.js.
* [quasarframework/quasar](https://github.com/quasarframework/quasar) - Quasar Framework - Build high-performance VueJS user interfaces in record time
* [nilbuild/driver.js](https://github.com/nilbuild/driver.js) - A lightweight, dependency-free JavaScript library for guiding user focus across the page.
* [feathericons/feather](https://github.com/feathericons/feather) - Simply beautiful open-source icons
* [select2/select2](https://github.com/select2/select2) - Select2 is a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.
* [Modernizr/Modernizr](https://github.com/Modernizr/Modernizr) - Modernizr is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser.
* [dimsemenov/PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) - JavaScript image gallery for mobile and desktop, modular, framework independent
* [hammerjs/hammer.js](https://github.com/hammerjs/hammer.js) - A javascript library for multi-touch gestures :// You can touch this
* [usablica/intro.js](https://github.com/usablica/intro.js) - Lightweight, user-friendly onboarding tour library
* [js-cookie/js-cookie](https://github.com/js-cookie/js-cookie) - A simple, lightweight JavaScript API for handling cookies, client-side.
* [jlmakes/scrollreveal](https://github.com/jlmakes/scrollreveal) - Animate elements as they scroll into view.
* [react-grid-layout/react-grid-layout](https://github.com/react-grid-layout/react-grid-layout) - A draggable and resizable grid layout with responsive breakpoints, for React.
* [bevacqua/dragula](https://github.com/bevacqua/dragula) - :ok_hand: Drag and drop so simple it hurts
* [handsontable/handsontable](https://github.com/handsontable/handsontable) - JavaScript Data Grid / Data Table with a Spreadsheet Look & Feel. Works with React, Angular, and Vue. Supported by the Handsontable team ⚡
* [KaTeX/KaTeX](https://github.com/KaTeX/KaTeX) - Fast math typesetting for the web.
* [PanJiaChen/vue-admin-template](https://github.com/PanJiaChen/vue-admin-template) - a vue2.0 minimal admin template
* [basecamp/trix](https://github.com/basecamp/trix) - A rich text editor for everyday writing
* [hyperapp/hyperapp](https://github.com/hyperapp/hyperapp) - 1kB-ish JavaScript framework for building hypertext applications
* [vuejs/vue-router](https://github.com/vuejs/vue-router) - 🚦 The official router for Vue 2
* [Shopify/draggable](https://github.com/Shopify/draggable) - The JavaScript Drag & Drop library your grandparents warned you about.
* [sweetalert2/sweetalert2](https://github.com/sweetalert2/sweetalert2) - ✨ A beautiful, responsive, highly customizable and accessible (WAI-ARIA) replacement for JavaScript's popup boxes. Zero dependencies. 🇺🇦🇪🇺
* [JedWatson/classnames](https://github.com/JedWatson/classnames) - A simple javascript utility for conditionally joining classNames together
* [aFarkas/lazysizes](https://github.com/aFarkas/lazysizes) - High performance and SEO friendly lazy loader for images (responsive and normal), iframes and more, that detects any visibility changes triggered through user interaction, CSS or JavaScript without configuration.
* [julianshapiro/velocity](https://github.com/julianshapiro/velocity) - Accelerated JavaScript animation.
* [dream-num/Luckysheet](https://github.com/dream-num/Luckysheet) - Luckysheet upgraded to Univer *(archived)*
* [infernojs/inferno](https://github.com/infernojs/inferno) - :fire: An extremely fast, React-like JavaScript library for building modern user interfaces
* [angular/material](https://github.com/angular/material) - Material design for AngularJS *(archived)*
* [pqina/filepond](https://github.com/pqina/filepond) - 🌊 A flexible and fun JavaScript file upload library
* [mattboldt/typed.js](https://github.com/mattboldt/typed.js) - A JavaScript Typing Animation Library
* [yabwe/medium-editor](https://github.com/yabwe/medium-editor) - Medium.com WYSIWYG editor clone. Uses contenteditable API to implement a rich text solution.
* [maxwellito/vivus](https://github.com/maxwellito/vivus) - JavaScript library to make drawing animation on SVG
* [janpaepke/ScrollMagic](https://github.com/janpaepke/ScrollMagic) - The javascript library for magical scroll interactions.
* [riot/riot](https://github.com/riot/riot) - Simple and elegant component-based UI library
* [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) - The project has been migrated to @wolf-table/table https://github.com/wolf-table/table
* [MithrilJS/mithril.js](https://github.com/MithrilJS/mithril.js) - A JavaScript Framework for Building Brilliant Applications
* [marko-js/marko](https://github.com/marko-js/marko) - A declarative, HTML-based language that makes building web apps fun
* [pandao/editor.md](https://github.com/pandao/editor.md) - The open source embeddable online markdown editor (component).
* [single-spa/single-spa](https://github.com/single-spa/single-spa) - The router for easy microfrontends
* [Tencent/omi](https://github.com/Tencent/omi) - Web Components Framework - Web组件框架
* [mdbootstrap/TW-Elements](https://github.com/mdbootstrap/TW-Elements) - 𝙃𝙪𝙜𝙚 collection of Tailwind MIT licensed (free) components, sections and templates 😎
* [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) - 📦 Workbox: JavaScript libraries for Progressive Web Apps
* [uxsolutions/bootstrap-datepicker](https://github.com/uxsolutions/bootstrap-datepicker) - A datepicker for twitter bootstrap (@twbs)
* [alyssaxuu/flowy](https://github.com/alyssaxuu/flowy) - The minimal javascript library to create flowcharts ✨
* [CodeSeven/toastr](https://github.com/CodeSeven/toastr) - Simple javascript toast notifications
* [jaredreich/pell](https://github.com/jaredreich/pell) - 📝 the simplest and smallest WYSIWYG text editor for web, with no dependencies
* [summernote/summernote](https://github.com/summernote/summernote) - Super Simple WYSIWYG Editor
* [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in Javascript
* [jquery/jquery-ui](https://github.com/jquery/jquery-ui) - The official jQuery user interface library.
* [javve/list.js](https://github.com/javve/list.js) - The perfect library for adding search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML.
* [dangrossman/daterangepicker](https://github.com/dangrossman/daterangepicker) - JavaScript Date Range, Date and Time Picker Component
* [mathjax/MathJax](https://github.com/mathjax/MathJax) - Beautiful and accessible math in all browsers
* [clauderic/react-sortable-hoc](https://github.com/clauderic/react-sortable-hoc) - A set of higher-order components to turn any list into an animated, accessible and touch-friendly sortable list✌️
* [browserstate/history.js](https://github.com/browserstate/history.js) - History.js gracefully supports the HTML5 History/State APIs (pushState, replaceState, onPopState) in all browsers. Including continued support for data, titles, replaceState. Supports jQuery, MooTools and Prototype. For HTML5 browsers this means that you can modify the URL directly, without needing to use hashes anymore. For HTML4 browsers it will revert back to using the old onhashchange functionality.
* [knockout/knockout](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript
* [reactstrap/reactstrap](https://github.com/reactstrap/reactstrap) - Simple React Bootstrap 5 components
* [ckeditor/ckeditor5](https://github.com/ckeditor/ckeditor5) - Powerful rich text editor framework with a modular architecture, modern integrations, and features like collaborative editing.
* [alexfoxy/lax.js](https://github.com/alexfoxy/lax.js) - Simple & lightweight (<4kb gzipped) vanilla JavaScript library to create smooth & beautiful animations when you scroll. *(archived)*
* [jquery-validation/jquery-validation](https://github.com/jquery-validation/jquery-validation) - jQuery Validation Plugin library sources
* [sparksuite/simplemde-markdown-editor](https://github.com/sparksuite/simplemde-markdown-editor) - A simple, beautiful, and embeddable JavaScript Markdown editor. Delightful editing for beginners and experts alike. Features built-in autosaving and spell checking.
* [snapappointments/bootstrap-select](https://github.com/snapappointments/bootstrap-select) - :rocket: The jQuery plugin that brings select elements into the 21st century with intuitive multiselection, searching, and much more.
* [bpmn-io/bpmn-js](https://github.com/bpmn-io/bpmn-js) - A BPMN 2.0 rendering toolkit and web modeler.
* [carbon-design-system/carbon](https://github.com/carbon-design-system/carbon) - A design system built by IBM
* [mdbootstrap/material-design-for-bootstrap](https://github.com/mdbootstrap/material-design-for-bootstrap) - Important! A new UI Kit version for Bootstrap 5 is available. Access the latest free version via the link below.
* [guillaumepotier/Parsley.js](https://github.com/guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of javascript
* [NUKnightLab/TimelineJS](https://github.com/NUKnightLab/TimelineJS) - TimelineJS: A Storytelling Timeline built in JavaScript. *(archived)*
* [locomotivemtl/locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll) - 🛤 Detection of elements in viewport & smooth scrolling with parallax.
* [desandro/imagesloaded](https://github.com/desandro/imagesloaded) - :camera: JavaScript is all like "You images done yet or what?"
* [tuupola/lazyload](https://github.com/tuupola/lazyload) - Vanilla JavaScript plugin for lazyloading images
* [givanz/VvvebJs](https://github.com/givanz/VvvebJs) - Drag and drop page builder library written in vanilla javascript without dependencies or build tools.
* [Nickersoft/push.js](https://github.com/Nickersoft/push.js) - The world's most versatile desktop notifications framework :earth_americas: *(archived)*
* [shipshapecode/tether](https://github.com/shipshapecode/tether) - A positioning engine to make overlays, tooltips and dropdowns better
* [Hacker0x01/react-datepicker](https://github.com/Hacker0x01/react-datepicker) - A simple and reusable datepicker component for React
* [grommet/grommet](https://github.com/grommet/grommet) - a react-based framework that provides accessibility, modularity, responsiveness, and theming in a tidy package
* [remix-run/history](https://github.com/remix-run/history) - Manage session history with JavaScript
* [jackocnr/intl-tel-input](https://github.com/jackocnr/intl-tel-input) - For entering, formatting, and validating international telephone numbers. Available in vanilla JavaScript, or as React, Vue, Angular, and Svelte components.
* [fengyuanchen/viewerjs](https://github.com/fengyuanchen/viewerjs) - JavaScript image viewer.
* [text-mask/text-mask](https://github.com/text-mask/text-mask) - Input mask for React, Angular, Ember, Vue, & plain JavaScript
* [jagenjo/litegraph.js](https://github.com/jagenjo/litegraph.js) - A graph node engine and editor written in Javascript similar to PD or UDK Blueprints, comes with its own editor in HTML5 Canvas2D. The engine can run client side or server side using Node. It allows to export graphs as JSONs to be included in applications independently.
* [FineUploader/fine-uploader](https://github.com/FineUploader/fine-uploader) - Multiple file upload plugin with image previews, drag and drop, progress bars. S3 and Azure support, image scaling, form support, chunking, resume, pause, and tons of other features. *(archived)*
* [Pikaday/Pikaday](https://github.com/Pikaday/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS *(archived)*
* [alibaba/rax](https://github.com/alibaba/rax) - 🐰 Rax is a progressive framework for building universal application. https://rax.js.org
* [rebassjs/rebass](https://github.com/rebassjs/rebass) - :atom_symbol: React primitive UI components built with styled-system.
* [alibaba/x-render](https://github.com/alibaba/x-render) - 🚴‍♀️ Very easy to use process form table chart solution.
* [verlok/vanilla-lazyload](https://github.com/verlok/vanilla-lazyload) - LazyLoad is a lightweight, flexible script that speeds up your website by deferring the loading of your below-the-fold images, backgrounds, videos, iframes and scripts to when they will enter the viewport. Written in plain "vanilla" JavaScript, it leverages IntersectionObserver, supports responsive images and enables native lazy loading.
* [kimmobrunfeldt/progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) - Responsive and slick progress bars
* [tabulator-tables/tabulator](https://github.com/tabulator-tables/tabulator) - Interactive Tables and Data Grids for JavaScript
* [dataarts/dat.gui](https://github.com/dataarts/dat.gui) - Lightweight controller library for JavaScript.
* [glidejs/glide](https://github.com/glidejs/glide) - A dependency-free JavaScript ES6 slider and carousel. It’s lightweight, flexible and fast. Designed to slide. No less, no more
* [styled-components/polished](https://github.com/styled-components/polished) - A lightweight toolset for writing styles in JavaScript ✨
* [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) - 🔥 Highly performant, light ~1kb and configurable lazy loader in pure JS with no dependencies for responsive images, iframes and more
* [reactjs/react-modal](https://github.com/reactjs/react-modal) - Accessible modal dialog component for React
* [hotwired/turbo](https://github.com/hotwired/turbo) - The speed of a single-page web application without having to write any JavaScript
* [jspreadsheet/ce](https://github.com/jspreadsheet/ce) - Jspreadsheet is a lightweight JavaScript data grid component for creating interactive data grids with advanced spreadsheet controls.
* [jaywcjlove/hotkeys-js](https://github.com/jaywcjlove/hotkeys-js) - ➷ A robust Javascript library for capturing keyboard input. It has no dependencies.
* [olton/metroui](https://github.com/olton/metroui) - A progressive front-end framework for creating high-performance responsive reactive web applications!
* [cssinjs/jss](https://github.com/cssinjs/jss) - JSS is an authoring tool for CSS which uses JavaScript as a host language.
* [fabiospampinato/cash](https://github.com/fabiospampinato/cash) - An absurdly small jQuery alternative for modern browsers.
* [marionettejs/backbone.marionette](https://github.com/marionettejs/backbone.marionette) - The Backbone Framework
* [mleibman/SlickGrid](https://github.com/mleibman/SlickGrid) - A lightning fast JavaScript grid/spreadsheet
* [vuelidate/vuelidate](https://github.com/vuelidate/vuelidate) - Simple, lightweight model-based validation for Vue.js
* [Choices-js/Choices](https://github.com/Choices-js/Choices) - A vanilla JS customisable select box/text input plugin ⚡️
* [shentao/vue-multiselect](https://github.com/shentao/vue-multiselect) - Universal select/multiselect/tagging component for Vue.js
* [golden-layout/golden-layout](https://github.com/golden-layout/golden-layout) - A multi window layout manager for webapps
* [needim/noty](https://github.com/needim/noty) - ⛔️ DEPRECATED - Dependency-free notification library that makes it easy to create alert - success - error - warning - information - confirmation messages as an alternative the standard alert dialog.
* [zeroclipboard/zeroclipboard](https://github.com/zeroclipboard/zeroclipboard) - The ZeroClipboard library provides an easy way to copy text to the clipboard using an invisible Adobe Flash movie and a JavaScript interface. *(archived)*
* [flightjs/flight](https://github.com/flightjs/flight) - A component-based, event-driven JavaScript framework from Twitter
* [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) - A Wysiwyg editor build on top of ReactJS and DraftJS. https://jpuri.github.io/react-draft-wysiwyg
* [Grsmto/simplebar](https://github.com/Grsmto/simplebar) - Custom scrollbars vanilla javascript library with native scroll, done simple, lightweight, easy to use and cross-browser.
* [boringdesigners/boring-avatars](https://github.com/boringdesigners/boring-avatars) - Boring avatars is an open source React library that generates custom, SVG-based avatars from any username and color palette.
* [webslides/WebSlides](https://github.com/webslides/WebSlides) - Create HTML presentations in seconds —
* [jaredreich/notie](https://github.com/jaredreich/notie) - 🔔 a clean and simple notification, input, and selection suite for javascript, with no dependencies *(archived)*
* [jerosoler/Drawflow](https://github.com/jerosoler/Drawflow) - Simple flow library 🖥️🖱️
* [jakiestfu/Snap.js](https://github.com/jakiestfu/Snap.js) - A Library for creating beautiful mobile shelfs in Javascript (Facebook and Path style side menus)
* [bendc/animateplus](https://github.com/bendc/animateplus) - A+ animation module for the modern web
* [kbrsh/moon](https://github.com/kbrsh/moon) - 🌙 The minimal & fast library for functional user interfaces
* [moxiecode/plupload](https://github.com/moxiecode/plupload) - Plupload is JavaScript API for building file uploaders. It supports multiple file selection, file filtering, chunked upload, client side image downsizing and when necessary can fallback to alternative runtimes, like Flash and Silverlight.
* [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) - Excel-like data grid (table) component for React
* [cferdinandi/smooth-scroll](https://github.com/cferdinandi/smooth-scroll) - A lightweight script to animate scrolling to anchor links. *(archived)*
* [NervJS/nerv](https://github.com/NervJS/nerv) - A blazing fast React alternative, compatible with IE8 and React 16.
* [orneryd/ui-grid](https://github.com/orneryd/ui-grid) - UI Grid: a Data Grid
* [kartik-v/bootstrap-fileinput](https://github.com/kartik-v/bootstrap-fileinput) - An enhanced HTML 5 file input for Bootstrap 5.x/4.x./3.x with file preview, multiple selection, and more features.
* [Khan/aphrodite](https://github.com/Khan/aphrodite) - Framework-agnostic CSS-in-JS with support for server-side rendering, browser prefixing, and minimum CSS generation
* [davatron5000/Lettering.js](https://github.com/davatron5000/Lettering.js) - A lightweight, easy to use Javascript <span> injector for radical Web Typography
* [sachinchoolur/lightgallery.js](https://github.com/sachinchoolur/lightgallery.js) - Full featured JavaScript image & video gallery. No dependencies
* [sarcadass/granim.js](https://github.com/sarcadass/granim.js) - Create fluid and interactive gradient animations with this small javascript library.
* [MoOx/postcss-cssnext](https://github.com/MoOx/postcss-cssnext) - `postcss-cssnext` has been deprecated in favor of `postcss-preset-env`. *(archived)*
* [uNmAnNeR/imaskjs](https://github.com/uNmAnNeR/imaskjs) - vanilla javascript input mask
* [GoogleChromeLabs/sw-precache](https://github.com/GoogleChromeLabs/sw-precache) - [Deprecated] A node module to generate service worker code that will precache specific resources so they work offline. *(archived)*
* [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) - Fast animations with javascript and CSS transforms
* [jquery-form/form](https://github.com/jquery-form/form) - jQuery Form Plugin
* [tommoor/tinycon](https://github.com/tommoor/tinycon) - A small library for manipulating the favicon, in particular adding alert bubbles and changing images.
* [react-ga/react-ga](https://github.com/react-ga/react-ga) - React Google Analytics Module *(archived)*
* [bootboxjs/bootbox](https://github.com/bootboxjs/bootbox) - Wrappers for JavaScript alert(), confirm() and other flexible dialogs using Twitter's bootstrap framework
* [evil-icons/evil-icons](https://github.com/evil-icons/evil-icons) - Simple and clean SVG icon pack with the code to support Rails, Sprockets, Node.js, Gulp, Grunt and CDN
* [mycolorway/simditor](https://github.com/mycolorway/simditor) - An Easy and Fast WYSIWYG Editor
* [json-editor/json-editor](https://github.com/json-editor/json-editor) - JSON Schema Based Editor
* [firebase/firebaseui-web](https://github.com/firebase/firebaseui-web) - FirebaseUI is an open-source JavaScript library for Web that provides simple, customizable UI bindings on top of Firebase SDKs to eliminate boilerplate code and promote best practices.
* [Tencent/cherry-markdown](https://github.com/Tencent/cherry-markdown) - ✨ A Markdown Editor
* [igorescobar/jQuery-Mask-Plugin](https://github.com/igorescobar/jQuery-Mask-Plugin) - A jQuery Plugin to make masks on form fields and HTML elements.
* [baidu/san](https://github.com/baidu/san) - A fast, portable, flexible JavaScript component framework
* [23/resumable.js](https://github.com/23/resumable.js) - A JavaScript library for providing multiple simultaneous, stable, fault-tolerant and resumable/restartable uploads via the HTML5 File API.
* [visionmedia/move.js](https://github.com/visionmedia/move.js) - CSS3 backed JavaScript animation framework
* [ant-design/ant-motion](https://github.com/ant-design/ant-motion) - :bicyclist: Animate specification and components of Ant Design
* [camwiegert/in-view](https://github.com/camwiegert/in-view) - Get notified when a DOM element enters or exits the viewport. :eyes: *(archived)*
* [crabbly/Print.js](https://github.com/crabbly/Print.js) - A tiny javascript library to help printing from the web.
* [NekR/offline-plugin](https://github.com/NekR/offline-plugin) - Offline plugin (ServiceWorker, AppCache) for webpack (https://webpack.js.org/)
* [muicss/mui](https://github.com/muicss/mui) - Lightweight CSS framework
* [peterramsing/lost](https://github.com/peterramsing/lost) - LostGrid is a powerful grid system built in PostCSS that works with any preprocessor and even vanilla CSS.
* [jakiestfu/Medium.js](https://github.com/jakiestfu/Medium.js) - A tiny JavaScript library for making contenteditable beautiful (Like Medium's editor)
* [strues/retinajs](https://github.com/strues/retinajs) - JavaScript, SCSS, Sass, Less, and Stylus helpers for rendering high-resolution image variants *(archived)*
* [pinterest/gestalt](https://github.com/pinterest/gestalt) - A set of React UI components that supports Pinterest’s design language
* [hunvreus/basecoat](https://github.com/hunvreus/basecoat) - A components library built with Tailwind CSS that works with any web stack.
* [jonathantneal/flexibility](https://github.com/jonathantneal/flexibility) - A JavaScript polyfill for Flexbox
* [fabien-d/alertify.js](https://github.com/fabien-d/alertify.js) - JavaScript Alert/Notification System
* [OscarGodson/EpicEditor](https://github.com/OscarGodson/EpicEditor) - EpicEditor is an embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more. For developers, it offers a robust API, can be easily themed, and allows you to swap out the bundled Markdown parser with anything you throw at it.
* [securingsincity/react-ace](https://github.com/securingsincity/react-ace) - React Ace Component
* [Alex-D/Trumbowyg](https://github.com/Alex-D/Trumbowyg) - A lightweight and amazing WYSIWYG JavaScript editor under 10kB
* [alvarotrigo/pagePiling.js](https://github.com/alvarotrigo/pagePiling.js) - pagePiling plugin by Alvaro Trigo. Create a scrolling pile of sections. http://alvarotrigo.com/pagePiling/
* [tholman/cursor-effects](https://github.com/tholman/cursor-effects) - Old-school cursor effects for your browser built with modern JavaScript
* [JosephusPaye/Keen-UI](https://github.com/JosephusPaye/Keen-UI) - A lightweight Vue.js UI library with a simple API, inspired by Google's Material Design.
* [TarekRaafat/autoComplete.js](https://github.com/TarekRaafat/autoComplete.js) - Simple autocomplete pure vanilla Javascript library.
* [micku7zu/vanilla-tilt.js](https://github.com/micku7zu/vanilla-tilt.js) - A smooth 3D tilt javascript library.
* [BoxFactura/pulltorefresh.js](https://github.com/BoxFactura/pulltorefresh.js) - A quick and powerful plugin for your pull-to-refresh needs in your webapp.
* [terwanerik/ScrollTrigger](https://github.com/terwanerik/ScrollTrigger) - Let your page react to scroll changes.
* [francoischalifour/medium-zoom](https://github.com/francoischalifour/medium-zoom) - 🔎🖼 A JavaScript library for zooming images like Medium
* [matthewhudson/current-device](https://github.com/matthewhudson/current-device) - 📱 The easiest way to write conditional CSS and/or JavaScript based on device operating system (iOS, Android, Blackberry, Windows, Firefox OS, MeeGo), orientation (Portrait vs. Landscape), and type (Tablet vs. Mobile).
* [Okazari/Rythm.js](https://github.com/Okazari/Rythm.js) - A javascript library that makes your page dance.
* [KyleAMathews/typography.js](https://github.com/KyleAMathews/typography.js) - A powerful toolkit for building websites with beautiful design
* [rikschennink/fitty](https://github.com/rikschennink/fitty) - ✨ Makes text fit perfectly
* [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) - Gmail JavaScript API
* [ReactTooltip/react-tooltip](https://github.com/ReactTooltip/react-tooltip) - React Tooltip Component
* [hizzgdev/jsmind](https://github.com/hizzgdev/jsmind) - a mind mapping library built by javascript
* [web-animations/web-animations-js](https://github.com/web-animations/web-animations-js) - JavaScript implementation of the Web Animations API
* [fomantic/Fomantic-UI](https://github.com/fomantic/Fomantic-UI) - Fomantic-UI is the official community fork of Semantic-UI
* [benhowdle89/grade](https://github.com/benhowdle89/grade) - This JavaScript library produces complementary gradients generated from the top 2 dominant colours in supplied images.
* [FortAwesome/react-fontawesome](https://github.com/FortAwesome/react-fontawesome) - Official React Component for Font Awesome Icons
* [micromodal/Micromodal](https://github.com/micromodal/Micromodal) - ⭕ Tiny javascript library for creating accessible modal dialogs
* [jschr/textillate](https://github.com/jschr/textillate) - A jquery plugin for CSS3 text animations.
* [Aerolab/midnight.js](https://github.com/Aerolab/midnight.js) - Switch your nav's design on the fly
* [nolimits4web/atropos](https://github.com/nolimits4web/atropos) - Stunning touch-friendly 3D parallax hover effects
* [WickyNilliams/enquire.js](https://github.com/WickyNilliams/enquire.js) - Awesome Media Queries in JavaScript
* [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) - [Deprecated] A collection of service worker tools for offlining runtime requests *(archived)*
* [osano/cookieconsent](https://github.com/osano/cookieconsent) - A free solution to the EU, GDPR, and California Cookie Laws
* [mailru/FileAPI](https://github.com/mailru/FileAPI) - FileAPI — a set of javascript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF.
* [CreateJS/TweenJS](https://github.com/CreateJS/TweenJS) - A simple but powerful tweening / animation library for Javascript. Part of the CreateJS suite of libraries.
* [prototypejs/prototype](https://github.com/prototypejs/prototype) - Prototype JavaScript framework
* [webkul/coolhue](https://github.com/webkul/coolhue) - Coolest Gradient Hues and Swatches
* [openseadragon/openseadragon](https://github.com/openseadragon/openseadragon) - An open-source, web-based viewer for zoomable images, implemented in pure JavaScript.
* [stevenschobert/instafeed.js](https://github.com/stevenschobert/instafeed.js) - A simple Instagram JavaScript plugin for your website
* [xdan/datetimepicker](https://github.com/xdan/datetimepicker) - jQuery Plugin Date and Time Picker
* [pawelgrzybek/siema](https://github.com/pawelgrzybek/siema) - Siema - Lightweight and simple carousel in pure JavaScript
* [redom/redom](https://github.com/redom/redom) - Tiny (2 KB) turboboosted JavaScript library for creating user interfaces.
* [ElemeFE/vue-amap](https://github.com/ElemeFE/vue-amap) - 🌍 基于 Vue 2.x 和高德地图的地图组件
* [UI5/openui5](https://github.com/UI5/openui5) - OpenUI5 lets you build enterprise-ready web applications, responsive to all devices, running on almost any browser of your choice.
* [neomjs/neo](https://github.com/neomjs/neo) - Neo.mjs is a self-evolving software organism: a professional end-to-end AI engineering team whose cross-model swarm inhabits live apps via Neural Link, Active Hybrid GraphRAG, DreamService, and self-healing loops.
* [cristianbote/goober](https://github.com/cristianbote/goober) - 🥜 goober, a less than 1KB 🎉 css-in-js alternative with a familiar API
* [skatejs/skatejs](https://github.com/skatejs/skatejs) - Effortless custom elements powered by modern view libraries.
* [mikeric/rivets](https://github.com/mikeric/rivets) - A lightweight data binding library.
* [NUKnightLab/TimelineJS3](https://github.com/NUKnightLab/TimelineJS3) - TimelineJS v3: A Storytelling Timeline built in JavaScript. http://timeline.knightlab.com
* [Tencent/weui.js](https://github.com/Tencent/weui.js) - A lightweight javascript library for WeUI.
* [alexmacarthur/typeit](https://github.com/alexmacarthur/typeit) - The most versatile JavaScript typewriter effect library on the planet.
* [hybridsjs/hybrids](https://github.com/hybridsjs/hybrids) - Extraordinary JavaScript UI framework with unique declarative and functional architecture
* [warp-drive-data/warp-drive](https://github.com/warp-drive-data/warp-drive) - WarpDrive is the lightweight data library for ambitious web apps — universal, typed, reactive, and ready to scale.
* [e-oj/Magic-Grid](https://github.com/e-oj/Magic-Grid) - A simple, lightweight Javascript library for dynamic grid layouts.
* [Ionaru/easy-markdown-editor](https://github.com/Ionaru/easy-markdown-editor) - EasyMDE: A simple, beautiful, and embeddable JavaScript Markdown editor. Delightful editing for beginners and experts alike. Features built-in autosaving and spell checking.
* [flowjs/flow.js](https://github.com/flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API.
* [mar10/fancytree](https://github.com/mar10/fancytree) - JavaScript tree view / tree grid plugin with support for keyboard, inline editing, filtering, checkboxes, drag'n'drop, and lazy loading
* [seiyria/bootstrap-slider](https://github.com/seiyria/bootstrap-slider) - A slider control for Bootstrap 3 & 4.
* [riophae/vue-treeselect](https://github.com/riophae/vue-treeselect) - A multi-select component with nested options support for Vue.js
* [stuyam/pressure](https://github.com/stuyam/pressure) - :point_down::boom: JavaScript library for handling Force Touch, 3D Touch, and Pointer Pressure.
* [redux-orm/redux-orm](https://github.com/redux-orm/redux-orm) - NOT MAINTAINED – A small, simple and immutable ORM to manage relational data in your Redux store.
* [ded/script.js](https://github.com/ded/script.js) - Asyncronous JavaScript loader and dependency manager
* [duskload/react-device-detect](https://github.com/duskload/react-device-detect) - Detect device, and render view according to detected device type.
* [bevacqua/rome](https://github.com/bevacqua/rome) - :calendar: Customizable date (and time) picker. Opt-in UI, no jQuery!
* [horizon-ui/horizon-ui-chakra](https://github.com/horizon-ui/horizon-ui-chakra) - Horizon UI JavaScript ⭐️ The trendiest & innovative Open Source Admin Template for Chakra UI & React!
* [caroso1222/notyf](https://github.com/caroso1222/notyf) - 👻 A minimalistic, responsive, vanilla JavaScript library to show toast notifications.
* [t1m0n/air-datepicker](https://github.com/t1m0n/air-datepicker) - Lightweight, dependency-free JavaScript datepicker.
* [CreateJS/PreloadJS](https://github.com/CreateJS/PreloadJS) - PreloadJS makes preloading assets & getting aggregate progress events easier in JavaScript. It uses XHR2 when available, and falls back to tag-based loading when not.
* [artberri/sidr](https://github.com/artberri/sidr) - Sidr is a jQuery plugin for creating side menus and the easiest way for doing your menu responsive.
* [hsnaydd/moveTo](https://github.com/hsnaydd/moveTo) - A lightweight scroll animation javascript library without any dependency
* [darsain/sly](https://github.com/darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support.
* [tonytomov/jqGrid](https://github.com/tonytomov/jqGrid) - jQuery grid plugin
* [ElemeFE/element-react](https://github.com/ElemeFE/element-react) - Element UI
* [jsonform/jsonform](https://github.com/jsonform/jsonform) - Build forms from JSON Schema. Easily template-able. Compatible with Bootstrap 3 out of the box.
* [yued-fe/lulu](https://github.com/yued-fe/lulu) - 跨端跨框架的原生 UI 组件库，即插即用
* [grevory/angular-local-storage](https://github.com/grevory/angular-local-storage) - An AngularJS module that gives you access to the browsers local storage with cookie fallback
* [rikschennink/shiny](https://github.com/rikschennink/shiny) - 🌟 Shiny reflections for mobile websites
* [substance/substance](https://github.com/substance/substance) - A JavaScript library for web-based content editing.
* [open-wc/open-wc](https://github.com/open-wc/open-wc) - Open Web Components: guides, tools and libraries for developing web components.
* [nitin42/terminal-in-react](https://github.com/nitin42/terminal-in-react) - 👨‍💻 A component that renders a terminal
* [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts.
* [refactory-id/bootstrap-markdown](https://github.com/refactory-id/bootstrap-markdown) - Bootstrap plugin for markdown editing
* [shuhei/material-colors](https://github.com/shuhei/material-colors) - Colors of Google's Material Design made available to coders
* [nicolasbize/faviconx](https://github.com/nicolasbize/faviconx) - A tiny javascript library that makes progress bars out of the favicon placeholders.
* [ryejs/rye](https://github.com/ryejs/rye) - A modern, lightweight browser library using ES5 natives
* [hd996/color-generate](https://github.com/hd996/color-generate) - 🔥 An awesome theme color generation scheme.
* [amazeui/amazeui](https://github.com/amazeui/amazeui) - Amaze UI, a mobile-first and modular front-end framework.

### Scraping and Crawling

* [jsdom/jsdom](https://github.com/jsdom/jsdom) - A JavaScript implementation of various web standards, for use with Node.js
* [jo-inc/camofox-browser](https://github.com/jo-inc/camofox-browser) - Stealth headless browser for AI agents — bypass Cloudflare, bot detection, and anti-scraping. Drop-in Puppeteer/Playwright replacement.
* [casperjs/casperjs](https://github.com/casperjs/casperjs) - CasperJS is no longer actively maintained. Navigation scripting and testing utility for PhantomJS and SlimerJS *(archived)*
* [bda-research/node-crawler](https://github.com/bda-research/node-crawler) - Web Crawler/Spider for NodeJS + server-side jQuery ;-)
* [l0o0/translators_CN](https://github.com/l0o0/translators_CN) - Zotero translator中文网页抓取翻译器🎉This is Zotero translators for Chinese Sites(beta), not the official Zotero repo
* [cyrus-and/chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface) - Chrome Debugging Protocol interface for Node.js
* [amir20/phantomjs-node](https://github.com/amir20/phantomjs-node) - PhantomJS integration module for NodeJS *(archived)*
* [laurentj/slimerjs](https://github.com/laurentj/slimerjs) - A scriptable browser like PhantomJS, based on Firefox

## Data and Storage

### Databases

* [localForage/localForage](https://github.com/localForage/localForage) - 💾 Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.
* [typicode/lowdb](https://github.com/typicode/lowdb) - Simple and fast JSON database
* [apache/pouchdb](https://github.com/apache/pouchdb) - :kangaroo: - PouchDB is a pocket-sized database.
* [marcuswestin/store.js](https://github.com/marcuswestin/store.js) - Cross-browser storage for all use cases, used across the web.
* [sql-js/sql.js](https://github.com/sql-js/sql.js) - A javascript library to run SQLite on the web.
* [louischatriot/nedb](https://github.com/louischatriot/nedb) - The JavaScript Database, for Node.js, nw.js, electron and the browser
* [AlaSQL/alasql](https://github.com/AlaSQL/alasql) - AlaSQL.js - JavaScript SQL database for browser and Node.js. Handles both traditional relational tables and nested JSON data (NoSQL). Export, store, and import data from localStorage, IndexedDB, or Excel.
* [techfort/LokiJS](https://github.com/techfort/LokiJS) - javascript embeddable / in-memory database
* [google/lovefield](https://github.com/google/lovefield) - Lovefield is a relational database for web apps. Written in JavaScript, works cross-browser. Provides SQL-like APIs that are fast, safe, and easy to use. *(archived)*
* [gruns/ImmortalDB](https://github.com/gruns/ImmortalDB) - :nut_and_bolt: A relentless key-value store for the browser.

### Database Clients and ORMs

* [sequelize/sequelize](https://github.com/sequelize/sequelize) - Feature-rich ORM for modern Node.js and TypeScript, it supports PostgreSQL (with JSON and JSONB support), MySQL, MariaDB, SQLite, MS SQL Server, Snowflake, Oracle DB, DB2 and DB2 for IBM i.
* [knex/knex](https://github.com/knex/knex) - A query builder for PostgreSQL, MySQL, CockroachDB, SQL Server, SQLite3 and Oracle, designed to be flexible, portable, and fun to use.
* [mysqljs/mysql](https://github.com/mysqljs/mysql) - A pure node.js JavaScript Client implementing the MySQL protocol.
* [dexie/Dexie.js](https://github.com/dexie/Dexie.js) - A Minimalistic Wrapper for IndexedDB
* [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) - A simple Node.js ORM for PostgreSQL, MySQL and SQLite3 built on top of Knex.js
* [Level/levelup](https://github.com/Level/levelup) - Superseded by abstract-level. A wrapper for abstract-leveldown compliant stores, for Node.js and browsers. *(archived)*
* [vitaly-t/pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL interface for Node.js
* [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) - Microsoft SQL Server client for Node.js
* [xavierlacot/joli.js](https://github.com/xavierlacot/joli.js) - joli.js is an Activerecord-like javascript ORM, particularly suited for being used in the Appcelerator Titanium Mobile framework.

### Serialization and Formats

* [mozilla/pdf.js](https://github.com/mozilla/pdf.js) - PDF Reader in JavaScript
* [SheetJS/sheetjs](https://github.com/SheetJS/sheetjs) - 📗 SheetJS Spreadsheet Data Toolkit -- New home https://git.sheetjs.com/SheetJS/sheetjs
* [parallax/jsPDF](https://github.com/parallax/jsPDF) - Client-side JavaScript PDF generation for everyone.
* [paularmstrong/normalizr](https://github.com/paularmstrong/normalizr) - Normalizes nested JSON according to a schema *(archived)*
* [mholt/PapaParse](https://github.com/mholt/PapaParse) - Fast and powerful CSV (delimited text) parser that gracefully handles large files and malformed input
* [bpampuch/pdfmake](https://github.com/bpampuch/pdfmake) - Client/server side PDF printing in pure JavaScript
* [foliojs/pdfkit](https://github.com/foliojs/pdfkit) - A JavaScript PDF generation library for Node and the browser
* [protobufjs/protobuf.js](https://github.com/protobufjs/protobuf.js) - High-performance Protocol Buffers for JavaScript and TypeScript. Conformant through Edition 2026, and unusually versatile. No protoc required.
* [Stuk/jszip](https://github.com/Stuk/jszip) - Create, read and edit .zip files with Javascript
* [douglascrockford/JSON-js](https://github.com/douglascrockford/JSON-js) - JSON in JavaScript
* [nodeca/js-yaml](https://github.com/nodeca/js-yaml) - JavaScript YAML parser and dumper. Very fast.
* [jonschlinkert/gray-matter](https://github.com/jonschlinkert/gray-matter) - Smarter YAML front matter parser, used by metalsmith, Gatsby, Netlify, Assemble, mapbox-gl, phenomic, vuejs vitepress, TinaCMS, Shopify Polaris, Ant Design, Astro, hashicorp, garden, slidev, saber, sourcegraph, and many others. Simple to use, and battle tested. Parses YAML by default but can also parse JSON Front Matter, Coffee Front Matter, TOML Front Matter, and has support for custom parsers. Please follow gray-matter's author: https://github.com/jonschlinkert
* [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) - Serialize JavaScript to a superset of JSON that includes regular expressions and functions.
* [dylang/node-xml](https://github.com/dylang/node-xml) - Fast and simple Javascript-based XML generator/builder for Node projects.
* [blowsie/Pure-JavaScript-HTML5-Parser](https://github.com/blowsie/Pure-JavaScript-HTML5-Parser) - A Pure JavaScript HTML5 Parser

### Search and Indexing

* [krisk/Fuse](https://github.com/krisk/Fuse) - Lightweight fuzzy-search, in JavaScript
* [nextapps-de/flexsearch](https://github.com/nextapps-de/flexsearch) - Next-generation full-text search library for Browser and Node.js
* [olivernn/lunr.js](https://github.com/olivernn/lunr.js) - A bit like Solr, but much smaller and not as bright
* [elasticsearch-dump/elasticsearch-dump](https://github.com/elasticsearch-dump/elasticsearch-dump) - Import and export tools for elasticsearch & opensearch
* [lucaong/minisearch](https://github.com/lucaong/minisearch) - Tiny and powerful JavaScript full-text search engine for browser and Node
* [farzher/fuzzysort](https://github.com/farzher/fuzzysort) - Fast SublimeText-like fuzzy search for JavaScript.

## Machine Learning and AI

### LLM and Inference

* [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI) - Unrestricted Open-source alternative to AI video platforms — Free AI image & video generation studio with 600+ models (Flux, Midjourney, Kling, Sora, Veo). No content filters. Self-hosted, MIT licensed.
* [ConardLi/easy-dataset](https://github.com/ConardLi/easy-dataset) - A powerful tool for creating datasets for LLM fine-tuning 、RAG and Eval
* [pollinations/pollinations](https://github.com/pollinations/pollinations) - Your Friendly Open-Source Gen-AI Platform
* [waylaidwanderer/node-chatgpt-api](https://github.com/waylaidwanderer/node-chatgpt-api) - A client implementation for ChatGPT and Bing AI. Available as a Node.js module, REST API server, and CLI app.
* [0hq/WebGPT](https://github.com/0hq/WebGPT) - Run GPT model on the browser with WebGPU. An implementation of GPT inference in less than ~1500 lines of vanilla Javascript.
* [openai/openai-realtime-console](https://github.com/openai/openai-realtime-console) - React app for inspecting, building and debugging with the Realtime API

### Machine Learning Frameworks

* [huggingface/transformers.js](https://github.com/huggingface/transformers.js) - State-of-the-art Machine Learning for the web. Run 🤗 Transformers directly in your browser, with no need for a server!
* [karpathy/convnetjs](https://github.com/karpathy/convnetjs) - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* [harthur/brain](https://github.com/harthur/brain) - Simple feed-forward neural network in JavaScript *(archived)*
* [ml5js/ml5-library](https://github.com/ml5js/ml5-library) - Friendly machine learning for the web! 🤖
* [transcranial/keras-js](https://github.com/transcranial/keras-js) - Run Keras models in the browser, with GPU support using WebGL
* [janhuenermann/neurojs](https://github.com/janhuenermann/neurojs) - A JavaScript deep learning and reinforcement learning library.

### Computer Vision

* [naptha/tesseract.js](https://github.com/naptha/tesseract.js) - Pure Javascript OCR for more than 100 Languages 📖🎉🖥
* [infinitered/nsfwjs](https://github.com/infinitered/nsfwjs) - NSFW detection on the client-side via TensorFlow.js
* [auduno/clmtrackr](https://github.com/auduno/clmtrackr) - Javascript library for precise tracking of facial features via Constrained Local Models
* [nenadmarkus/picojs](https://github.com/nenadmarkus/picojs) - A face detection library in 200 lines of JavaScript
* [serratus/quaggaJS](https://github.com/serratus/quaggaJS) - An advanced barcode-scanner written in JavaScript
* [auduno/headtrackr](https://github.com/auduno/headtrackr) - Javascript library for headtracking via webcam and WebRTC/getUserMedia
* [antimatter15/ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in Javascript via Emscripten
* [jeeliz/jeelizFaceFilter](https://github.com/jeeliz/jeelizFaceFilter) - 🎭 Lightweight WebGL & JavaScript library for real-time multi-face detection, tracking and augmented-reality face filters. Supports rotation, mouth-opening and integrates with Three.js, Babylon.js, Canvas2D and CSS3D
* [victordibia/handtrack.js](https://github.com/victordibia/handtrack.js) - A library for prototyping realtime hand detection (bounding box), directly in the browser.
* [inspirit/jsfeat](https://github.com/inspirit/jsfeat) - JavaScript Computer Vision library.

### Data Science and Analytics

* [chartjs/Chart.js](https://github.com/chartjs/Chart.js) - Simple HTML5 Charts using the <canvas> tag
* [plotly/plotly.js](https://github.com/plotly/plotly.js) - Open-source JavaScript charting library behind Plotly and Dash
* [apexcharts/apexcharts.js](https://github.com/apexcharts/apexcharts.js) - 📊 Interactive JavaScript Charts built on SVG
* [frappe/charts](https://github.com/frappe/charts) - Simple, responsive, modern SVG Charts with zero dependencies
* [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) - Graph theory (network) library for visualisation and analysis
* [jwilber/roughViz](https://github.com/jwilber/roughViz) - Reusable JavaScript library for creating sketchy/hand-drawn styled charts in the browser.
* [sbstjn/timesheet.js](https://github.com/sbstjn/timesheet.js) - JavaScript library for HTML5 & CSS3 time sheets
* [shutterstock/rickshaw](https://github.com/shutterstock/rickshaw) - JavaScript toolkit for creating interactive real-time graphs
* [pa7/heatmap.js](https://github.com/pa7/heatmap.js) - 🔥 JavaScript Library for HTML5 canvas based heatmaps
* [frappe/gantt](https://github.com/frappe/gantt) - Open Source Javascript Gantt
* [flot/flot](https://github.com/flot/flot) - Attractive JavaScript charts for jQuery
* [square/cubism](https://github.com/square/cubism) - Cubism.js: A JavaScript library for time series visualization.
* [jasondavies/d3-cloud](https://github.com/jasondavies/d3-cloud) - Create word clouds in JavaScript.
* [markmarkoh/datamaps](https://github.com/markmarkoh/datamaps) - Customizable SVG map visualizations for the web in a single Javascript file using D3.js
* [britecharts/britecharts](https://github.com/britecharts/britecharts) - Composable Charting Library based on reusable D3.js components.
* [jones2000/HQChart](https://github.com/jones2000/HQChart) - HQChart - H5, 微信小程序 沪深/港股/数字货币/期货/美股 K线图(kline),走势图,缩放,拖拽,十字光标,画图工具,截图,筹码图. 分析家语法,通达信语法,(麦语法),第3方数据替换接口
* [danvk/dygraphs](https://github.com/danvk/dygraphs) - Interactive visualizations of time series using JavaScript and the HTML canvas tag
* [ignoreintuition/jSchema](https://github.com/ignoreintuition/jSchema) - A simple, easy to use data modeling framework for JavaScript
* [oreillymedia/thebe](https://github.com/oreillymedia/thebe) - Jupyter javascript plugin for static sites

## Networking and Distributed

### Networking

* [webtorrent/webtorrent](https://github.com/webtorrent/webtorrent) - ⚡️ Streaming torrent client for the web
* [websockets/ws](https://github.com/websockets/ws) - Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js
* [WhiskeySockets/Baileys](https://github.com/WhiskeySockets/Baileys) - Socket-based TS/JavaScript API for WhatsApp Web
* [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) - WebSocket emulation - Javascript client
* [fonoster/fonoster](https://github.com/fonoster/fonoster) - 🚀 The open-source alternative to Twilio.
* [feross/simple-peer](https://github.com/feross/simple-peer) - 📡 Simple WebRTC video, voice, and data channels
* [mscdex/ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server modules written in pure JavaScript for node.js
* [haraka/Haraka](https://github.com/haraka/Haraka) - A fast, highly extensible, and event driven SMTP server
* [socketio/engine.io](https://github.com/socketio/engine.io) - The engine used in the Socket.IO JavaScript server, which manages the low-level transports such as HTTP long-polling and WebSocket.
* [primus/primus](https://github.com/primus/primus) - :zap: Primus, the creator god of the transformers & an abstraction layer for real-time to prevent module lock-in.
* [joewalnes/reconnecting-websocket](https://github.com/joewalnes/reconnecting-websocket) - A small decorator for the JavaScript WebSocket API that automatically reconnects
* [sockjs/sockjs-node](https://github.com/sockjs/sockjs-node) - WebSocket emulation - Node.js server

### RPC and Messaging

* [grpc/grpc-web](https://github.com/grpc/grpc-web) - gRPC for Web Clients
* [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) - The MQTT client for Node.js and the browser
* [SocketCluster/socketcluster](https://github.com/SocketCluster/socketcluster) - Highly scalable realtime pub/sub and RPC framework
* [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) - Dependency free publish/subscribe for JavaScript
* [senecajs/seneca](https://github.com/senecajs/seneca) - A microservices toolkit for Node.js.
* [vpulim/node-soap](https://github.com/vpulim/node-soap) - A SOAP client and server for node.js.
* [postaljs/postal.js](https://github.com/postaljs/postal.js) - JavaScript pub/sub library supporting advanced subscription features, and several helpful add-ons.
* [Flotype/now](https://github.com/Flotype/now) - NowJS makes it easy to build real-time web apps using JavaScript

### Distributed Systems

* [web3/web3.js](https://github.com/web3/web3.js) - Collection of comprehensive TypeScript libraries for Interaction with the Ethereum JSON RPC API and utility functions. *(archived)*
* [automerge/automerge-classic](https://github.com/automerge/automerge-classic) - A JSON-like data structure (a CRDT) that can be modified concurrently by different users, and merged again automatically.
* [ipfs/js-ipfs](https://github.com/ipfs/js-ipfs) - IPFS implementation in JavaScript *(archived)*
* [automerge/automerge](https://github.com/automerge/automerge) - A JSON-like data structure (a CRDT) that can be modified concurrently by different users, and merged again automatically.
* [bitcoinjs/bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) - A javascript Bitcoin library for node.js and browsers.
* [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) - Javascript bitcoin library for node.js and browsers

### Cloud and Infrastructure

* [anomalyco/sst](https://github.com/anomalyco/sst) - Build full-stack apps on your own infrastructure.
* [aws/aws-sdk-js](https://github.com/aws/aws-sdk-js) - AWS SDK for JavaScript v2 (End-of-Life as of 09/08/2025). The AWS SDK for JavaScript v3 in the browser and Node.js is available here: https://github.com/aws/aws-sdk-js-v3 *(archived)*
* [shipitjs/shipit](https://github.com/shipitjs/shipit) - Universal automation and deployment tool ⛵️ *(archived)*
* [apocas/dockerode](https://github.com/apocas/dockerode) - Docker + Node = Dockerode (Node.js module for Docker's Remote API)
* [middyjs/middy](https://github.com/middyjs/middy) - 🛵 The stylish Node.js middleware engine for AWS Lambda 🛵
* [claudiajs/claudia](https://github.com/claudiajs/claudia) - Deploy Node.js projects to AWS Lambda and API Gateway easily

## User Interface

### Mobile

* [dcloudio/uni-app](https://github.com/dcloudio/uni-app) - A cross-platform framework using Vue.js
* [dcloudio/mui](https://github.com/dcloudio/mui) - 最接近原生APP体验的高性能框架
* [expo/create-react-native-app](https://github.com/expo/create-react-native-app) - Create React Native apps that run on iOS, Android, and web
* [invertase/react-native-firebase](https://github.com/invertase/react-native-firebase) - 🔥 A well-tested feature-rich modular Firebase implementation for React Native. Supports both iOS & Android platforms for all Firebase services.
* [didi/cube-ui](https://github.com/didi/cube-ui) - :large_orange_diamond: A fantastic mobile ui lib implement by Vue
* [OnsenUI/OnsenUI](https://github.com/OnsenUI/OnsenUI) - Mobile app development framework and SDK using HTML5 and JavaScript. Create beautiful and performant cross-platform mobile apps. Based on Web Components, and provides bindings for Angular 1, 2, React and Vue.js.
* [GeekyAnts/vue-native-core](https://github.com/GeekyAnts/vue-native-core) - Vue Native is a framework to build cross platform native mobile apps using JavaScript
* [apache/cordova-android](https://github.com/apache/cordova-android) - Apache Cordova Android
* [iSimar/HackerNews-React-Native](https://github.com/iSimar/HackerNews-React-Native) - Hacker News iOS and Android App - Made with React Native.
* [jemise111/react-native-swipe-list-view](https://github.com/jemise111/react-native-swipe-list-view) - A React Native ListView component with rows that swipe open and closed

### Applications and End User Tools

* [strapi/strapi](https://github.com/strapi/strapi) - 🚀 Strapi is the leading open-source headless CMS. It’s 100% JavaScript/TypeScript, fully customizable, and developer-first.
* [gorhill/uBlock](https://github.com/gorhill/uBlock) - uBlock Origin - An efficient blocker for Chromium and Firefox. Fast and lean.
* [atom/atom](https://github.com/atom/atom) - :atom: The hackable text editor *(archived)*
* [twentyhq/twenty](https://github.com/twentyhq/twenty) - The open alternative to Salesforce, designed for AI.
* [TryGhost/Ghost](https://github.com/TryGhost/Ghost) - Independent technology for modern publishing, memberships, subscriptions and newsletters.
* [lyswhut/lx-music-desktop](https://github.com/lyswhut/lx-music-desktop) - 一个基于 Electron 的音乐软件
* [usebruno/bruno](https://github.com/usebruno/bruno) - Opensource IDE For Exploring and Testing API's (lightweight alternative to Postman/Insomnia)
* [HeyPuter/puter](https://github.com/HeyPuter/puter) - 🌐 The Internet Computer! Free, Open-Source, and Self-Hostable.
* [ToolJet/ToolJet](https://github.com/ToolJet/ToolJet) - Open-source foundation of ToolJet AI - the enterprise app generation platform for internal tools, dashboards, business applications, workflows and AI agents. Build visually, from a prompt, or from Claude Code, Codex and Cursor over MCP 🚀
* [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb) - Free, simple, and intuitive online database diagram editor and SQL generator.
* [carbon-app/carbon](https://github.com/carbon-app/carbon) - :black_heart: Create and share beautiful images of your source code
* [adobe/brackets](https://github.com/adobe/brackets) - An open source code editor for the web, written in JavaScript, HTML and CSS. *(archived)*
* [responsively-org/responsively-app](https://github.com/responsively-org/responsively-app) - A modified web browser that helps in responsive web development. A web developer's must have dev-tool.
* [nylas/nylas-mail](https://github.com/nylas/nylas-mail) - :love_letter: An extensible desktop mail app built on the modern web. Forks welcome! *(archived)*
* [MagicMirrorOrg/MagicMirror](https://github.com/MagicMirrorOrg/MagicMirror) - MagicMirror² is an open source modular smart mirror platform. With a growing list of installable modules, the MagicMirror² allows you to convert your hallway or bathroom mirror into your personal assistant.
* [benweet/stackedit](https://github.com/benweet/stackedit) - In-browser Markdown editor
* [gildas-lormeau/SingleFile](https://github.com/gildas-lormeau/SingleFile) - Web Extension for saving a faithful copy of a complete web page in a single HTML file
* [xifangczy/cat-catch](https://github.com/xifangczy/cat-catch) - 猫抓 浏览器资源嗅探扩展 / cat-catch Browser Resource Sniffing Extension
* [wekan/wekan](https://github.com/wekan/wekan) - The Open Source kanban, built with Meteor. GitHub issues/PRs are only for FLOSS Developers, not for support, support is at https://wekan.fi/commercial-support/ . PR source translation to imports/i18n/data/en.i18n.json, other translations at https://app.transifex.com/wekan/wekan . No telemetry.
* [hmjz100/LinkSwift](https://github.com/hmjz100/LinkSwift) - 一个基于 JavaScript 的网盘文件下载地址获取工具。基于【网盘直链下载助手】修改 ，支持 百度网盘 / 阿里云盘 / 中国移动云盘 / 天翼云盘 / 迅雷云盘 / 夸克网盘 / UC网盘 / 123云盘 八大网盘
* [decaporg/decap-cms](https://github.com/decaporg/decap-cms) - A Git-based CMS for Static Site Generators
* [alyssaxuu/screenity](https://github.com/alyssaxuu/screenity) - The free and privacy-friendly screen recorder with no limits 🎥
* [alam00000/bentopdf](https://github.com/alam00000/bentopdf) - The Privacy First PDF Toolkit
* [NodeBB/NodeBB](https://github.com/NodeBB/NodeBB) - Node.js based forum software built for the modern web
* [cockpit-project/cockpit](https://github.com/cockpit-project/cockpit) - Cockpit is a web-based graphical interface for servers.
* [HabitRPG/habitica](https://github.com/HabitRPG/habitica) - A habit tracker app which treats your goals like a Role Playing Game.
* [novnc/noVNC](https://github.com/novnc/noVNC) - VNC client web application
* [codesandbox/codesandbox-client](https://github.com/codesandbox/codesandbox-client) - An online IDE for rapid web development
* [mayswind/AriaNg](https://github.com/mayswind/AriaNg) - AriaNg, a modern web frontend making aria2 easier to use.
* [DustinBrett/daedalOS](https://github.com/DustinBrett/daedalOS) - Desktop environment in the browser
* [gnab/remark](https://github.com/gnab/remark) - A simple, in-browser, markdown-driven slideshow tool.
* [keeweb/keeweb](https://github.com/keeweb/keeweb) - Free cross-platform password manager compatible with KeePass
* [piskelapp/piskel](https://github.com/piskelapp/piskel) - A simple web-based tool for Spriting and Pixel art.
* [Automattic/wp-calypso](https://github.com/Automattic/wp-calypso) - The JavaScript and API powered WordPress.com
* [plankanban/planka](https://github.com/plankanban/planka) - Elegant open source project tracking. Self-hosted Kanban for teams — free Community edition, with PLANKA Pro for organisations.
* [reactioncommerce/reaction](https://github.com/reactioncommerce/reaction) - Project has been discontinued ////// Mailchimp Open Commerce is an API-first, headless commerce platform built using Node.js, React, GraphQL. Deployed via Docker and Kubernetes.
* [ShareDropio/sharedrop](https://github.com/ShareDropio/sharedrop) - Easy P2P file transfer powered by WebRTC - inspired by Apple AirDrop
* [FredrikNoren/ungit](https://github.com/FredrikNoren/ungit) - The easiest way to use git. On any platform. Anywhere.
* [reactide/reactide](https://github.com/reactide/reactide) - Reactide is the first dedicated IDE for React web application development.
* [aandrew-me/ytDownloader](https://github.com/aandrew-me/ytDownloader) - Desktop app to download audio/video from hundreds of sites
* [ksky521/nodeppt](https://github.com/ksky521/nodeppt) - This is probably the best web presentation tool so far! *(archived)*
* [kern/filepizza](https://github.com/kern/filepizza) - :pizza: Peer-to-peer file transfers in your browser
* [webtorrent/webtorrent-desktop](https://github.com/webtorrent/webtorrent-desktop) - ❤️ Streaming torrent app for Mac, Windows, and Linux
* [MrXujiang/h5-Dooring](https://github.com/MrXujiang/h5-Dooring) - H5 Page Maker, H5 Editor, LowCode. Make H5 as easy as building blocks. | 让H5制作像搭积木一样简单, 轻松搭建H5页面, H5网站, PC端网站,LowCode平台.
* [evolus/pencil](https://github.com/evolus/pencil) - The Pencil Project's unique mission is to build a free and opensource tool for making diagrams and GUI prototyping that everyone can use.
* [blueedgetechno/win11React](https://github.com/blueedgetechno/win11React) - Windows 11 in React 💻🌈⚡ *(archived)*
* [Laverna/laverna](https://github.com/Laverna/laverna) - Laverna is a JavaScript note taking application with Markdown editor and encryption support. Consider it like open source alternative to Evernote.
* [TiddlyWiki/TiddlyWiki5](https://github.com/TiddlyWiki/TiddlyWiki5) - A self-contained JavaScript wiki for the browser, Node.js, AWS Lambda etc.
* [felixrieseberg/macintosh.js](https://github.com/felixrieseberg/macintosh.js) - 🖥 A virtual Apple Macintosh with System 8, running in Electron. I'm sorry.
* [joemccann/dillinger](https://github.com/joemccann/dillinger) - The last Markdown editor, ever.
* [uBlock-LLC/uBlock](https://github.com/uBlock-LLC/uBlock) - uBlock: a fast, lightweight, and lean blocker for Chrome, Firefox, and Safari. *(archived)*
* [jgraph/drawio](https://github.com/jgraph/drawio) - draw.io is a JavaScript, client-side editor for general diagramming.
* [zhukov/webogram](https://github.com/zhukov/webogram) - Telegram web application, GPL v3 *(archived)*
* [cryptpad/cryptpad](https://github.com/cryptpad/cryptpad) - Collaborative office suite, end-to-end encrypted and open-source.
* [brave/browser-laptop](https://github.com/brave/browser-laptop) - [DEPRECATED] Please see https://github.com/brave/brave-browser for the current version of Brave *(archived)*
* [1j01/jspaint](https://github.com/1j01/jspaint) - 🎨 Classic MS Paint, ＲＥＶＩＶＥＤ + ✨Extras
* [alyssaxuu/omni](https://github.com/alyssaxuu/omni) - The all-in-one tool to supercharge your productivity ⌨️
* [SVG-Edit/svgedit](https://github.com/SVG-Edit/svgedit) - Powerful SVG-Editor for your browser
* [LiteLoaderQQNT/LiteLoaderQQNT](https://github.com/LiteLoaderQQNT/LiteLoaderQQNT) - QQNT 插件加载器：LiteLoaderQQNT —— 轻量 · 简洁 · 开源 · 福瑞 *(archived)*
* [os-js/OS.js](https://github.com/os-js/OS.js) - OS.js - JavaScript Web Desktop Platform
* [OpenSignLabs/OpenSign](https://github.com/OpenSignLabs/OpenSign) - 🔥 The free & Open Source DocuSign alternative
* [nikolaeu/numi](https://github.com/nikolaeu/numi) - Beautiful calculator app for macOS, Linux & Windows
* [itorr/nbnhhsh](https://github.com/itorr/nbnhhsh) - 😩「能不能好好说话？」 拼音首字母缩写翻译工具
* [brookhong/Surfingkeys](https://github.com/brookhong/Surfingkeys) - Map your keys for web surfing, expand your browser with javascript and keyboard.
* [jvalen/pixel-art-react](https://github.com/jvalen/pixel-art-react) - Pixel art animation and drawing web app powered by React
* [Azgaar/Fantasy-Map-Generator](https://github.com/Azgaar/Fantasy-Map-Generator) - Web application generating interactive and highly customizable maps
* [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) - Web-based MongoDB admin interface, written with Node.js and Express
* [ShizukuIchi/winXP](https://github.com/ShizukuIchi/winXP) - 🏁 Web based Windows XP desktop recreation.
* [EddieHubCommunity/BioDrop](https://github.com/EddieHubCommunity/BioDrop) - Connect to your audience with a single link. Showcase the content you create and your projects in one place. Make it easier for people to find, follow and subscribe. *(archived)*
* [GargantuaX/gemini-watermark-remover](https://github.com/GargantuaX/gemini-watermark-remover) - A high-performance, 100% client-side tool for removing Gemini AI image & video watermarks. Built with pure JavaScript using mathematically precise Reverse Alpha Blending. / 基于 JavaScript 的纯浏览器端 Gemini AI 图像和视频无损去水印工具，使用数学精确的反向 Alpha 混合算法
* [Neet-Nestor/Telegram-Media-Downloader](https://github.com/Neet-Nestor/Telegram-Media-Downloader) - A script allowing you to download images and videos from Telegram web even if the group restricts downloading.
* [manojVivek/medium-unlimited](https://github.com/manojVivek/medium-unlimited) - A browser extension to read medium.com articles for free without membership. *(archived)*
* [agentejo/cockpit](https://github.com/agentejo/cockpit) - Add content management functionality to any site - plug & play / headless / api-first CMS
* [Soundnode/soundnode-app](https://github.com/Soundnode/soundnode-app) - Soundnode App is the Soundcloud for desktop. Built with Electron, Angular.js and Soundcloud API.
* [Studio-42/elFinder](https://github.com/Studio-42/elFinder) - 📁 Open-source file manager for web, written in JavaScript using jQuery and jQuery UI
* [miroslavpejic85/mirotalk](https://github.com/miroslavpejic85/mirotalk) - 🚀 Open-source, self-hosted P2P WebRTC video conferencing for fast, private real-time communication. Create browser-based meeting rooms with no downloads or time limits, plus screen sharing, chat, whiteboard, recording, and collaboration.
* [limbopro/Adblock4limbo](https://github.com/limbopro/Adblock4limbo) - 毒奶去网页广告计划用户脚本 For Quantumult X & Surge & Shadowrocket & Loon & Stash & 油猴 ；1.导航 2.通过 JS/CSS 移除特定网站网页广告 —— 搜索引擎（Bing/Google）广告及内容农场结果清除/低端影视/欧乐影院/iyf爱壹帆/哔滴影视/Pornhub/Javbus/Supjav/Jable(M3U8)/MissAv/91porn/hitomi/紳士漫畫/禁漫天堂/等视频&ACG&小说&漫画网站上的弹窗广告&视频广告&Gif广告，沉浸式翻译/提取M3U8等，保持网页清爽干净无打扰！ P.S. 欢迎提交issue
* [jsbin/jsbin](https://github.com/jsbin/jsbin) - Collaborative JavaScript Debugging App
* [QasimWani/LeetHub](https://github.com/QasimWani/LeetHub) - Automatically sync your leetcode solutions to your github account - top 5 trending GitHub repository
* [timuric/Content-generator-sketch-plugin](https://github.com/timuric/Content-generator-sketch-plugin) - Sketch app plugin for generating dummy data such as avatars, names, photos, geo data etc
* [vanila-io/wireflow](https://github.com/vanila-io/wireflow) - Wireflow - user flow chart real-time collaborative tool
* [pulsar-edit/pulsar](https://github.com/pulsar-edit/pulsar) - A Community-led Hyper-Hackable Text Editor
* [alyssaxuu/motionity](https://github.com/alyssaxuu/motionity) - The web-based motion graphics editor for everyone 📽
* [Atri-Labs/atrilabs-engine](https://github.com/Atri-Labs/atrilabs-engine) - 🧘‍♂️ Open-source no-code & code web app builder
* [openstreetmap/iD](https://github.com/openstreetmap/iD) - 🆔 The easy-to-use OpenStreetMap editor in JavaScript.
* [bilibili-helper/bilibili-helper-o](https://github.com/bilibili-helper/bilibili-helper-o) - 哔哩哔哩 (bilibili.com) 辅助工具，可以替换播放器、推送通知并进行一些快捷操作
* [EFForg/privacybadger](https://github.com/EFForg/privacybadger) - Privacy Badger is a browser extension that automatically learns to block hidden trackers
* [piroor/treestyletab](https://github.com/piroor/treestyletab) - Tree Style Tab, Show tabs like a tree.
* [LimeSurvey/LimeSurvey](https://github.com/LimeSurvey/LimeSurvey) - 🔥 LimeSurvey – A powerful, open-source survey platform. A free alternative to SurveyMonkey, Typeform, Qualtrics, and Google Forms, making it simple to create online surveys and forms with unmatched flexibility.
* [justjavac/ReplaceGoogleCDN](https://github.com/justjavac/ReplaceGoogleCDN) - ⚡️ 一个 Chrome 插件：将 Google CDN 替换为国内的。
* [webtorrent/instant.io](https://github.com/webtorrent/instant.io) - 🚀 Streaming file transfer over WebTorrent (torrents on the web)
* [ssbc/patchwork](https://github.com/ssbc/patchwork) - A decentralized messaging and sharing app built on top of Secure Scuttlebutt (SSB). *(archived)*
* [alyssaxuu/mapus](https://github.com/alyssaxuu/mapus) - A map tool with real-time collaboration 🗺️
* [Haehnchen/crypto-trading-bot](https://github.com/Haehnchen/crypto-trading-bot) - Cryptocurrency trading bot in javascript for Bitfinex, Bitmex, Binance, Bybit ... (public edition)
* [lbryio/lbry-desktop](https://github.com/lbryio/lbry-desktop) - A browser and wallet for LBRY, the decentralized, user-controlled content marketplace.
* [React-Proto/react-proto](https://github.com/React-Proto/react-proto) - :art: React application prototyping tool for developers and designers :building_construction:
* [deepsyx/home-automation](https://github.com/deepsyx/home-automation) - Raspberry Pi 3 based home automation with NodeJS and React Native.
* [EFForg/https-everywhere](https://github.com/EFForg/https-everywhere) - A browser extension that encrypts your communications with many websites that offer HTTPS but still allow unencrypted connections. *(archived)*
* [tmcw/big](https://github.com/tmcw/big) - presentations for busy messy hackers
* [conversejs/converse.js](https://github.com/conversejs/converse.js) - Web-based XMPP/Jabber chat written in JavaScript
* [hainproject/hain](https://github.com/hainproject/hain) - An 'alt+space' launcher for Windows, built with Electron *(archived)*
* [Dynalon/mdwiki](https://github.com/Dynalon/mdwiki) - CMS/Wiki system using Javascript for 100% client side single page application using Markdown.
* [automeris-io/WebPlotDigitizer](https://github.com/automeris-io/WebPlotDigitizer) - Computer vision assisted tool to extract numerical data from plot images.
* [chrisdiana/cms.js](https://github.com/chrisdiana/cms.js) - Client-Side JavaScript Site Generator
* [tobychui/arozos](https://github.com/tobychui/arozos) - Web Desktop Operating System for low power platforms, Now written in Go!
* [phcode-dev/phoenix](https://github.com/phcode-dev/phoenix) - The text editor designed to make coding as simple and fun as playing a video game
* [jekyll/jekyll-admin](https://github.com/jekyll/jekyll-admin) - A Jekyll plugin that provides users with a traditional CMS-style graphical interface to author content and administer Jekyll sites.
* [padloc/padloc](https://github.com/padloc/padloc) - A modern, open source password manager for individuals and teams.
* [shen100/mili](https://github.com/shen100/mili) - mili 是一个开源的社区系统，界面优雅，功能丰富😛
* [mrwill84/DOClever](https://github.com/mrwill84/DOClever) - 做最好的接口管理平台
* [streamlink/streamlink-twitch-gui](https://github.com/streamlink/streamlink-twitch-gui) - A multi platform Twitch.tv browser for Streamlink
* [drichard/mindmaps](https://github.com/drichard/mindmaps) - An open source, offline capable, mind mapping application leveraging HTML5 technologies
* [ehzhang/HELPq](https://github.com/ehzhang/HELPq) - 💁 an extensible real-time queue application, for mentorship @ hackathons and classrooms
* [zero-archive/node-url-shortener](https://github.com/zero-archive/node-url-shortener) - A modern, minimalist, and lightweight URL shortener using Node.js and Redis *(archived)*
* [scripting/river4](https://github.com/scripting/river4) - A JavaScript river-of-news aggregator running in Node.js

## Graphics and Media

### Graphics and Rendering

* [mrdoob/three.js](https://github.com/mrdoob/three.js) - JavaScript 3D Library.
* [mermaid-js/mermaid](https://github.com/mermaid-js/mermaid) - Generation of diagrams like flowcharts or sequence diagrams from text in a similar manner as markdown
* [Leaflet/Leaflet](https://github.com/Leaflet/Leaflet) - 🍃 JavaScript library for mobile-friendly interactive maps 🇺🇦
* [fabricjs/fabric.js](https://github.com/fabricjs/fabric.js) - Javascript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser
* [processing/p5.js](https://github.com/processing/p5.js) - p5.js is a client-side JS platform that empowers artists, designers, students, and anyone to learn to code and express themselves creatively on the web. It is based on the core principles of Processing. Looking for p5.js 2.0? http://beta.p5js.org
* [CesiumGS/cesium](https://github.com/CesiumGS/cesium) - An open-source JavaScript library for world-class 3D globes and maps :earth_americas:
* [paperjs/paper.js](https://github.com/paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas. Created by @lehni & @puckey
* [visgl/deck.gl](https://github.com/visgl/deck.gl) - WebGL2 powered visualization framework
* [adobe-webplatform/Snap.svg](https://github.com/adobe-webplatform/Snap.svg) - The JavaScript library for modern SVG graphics.
* [openlayers/openlayers](https://github.com/openlayers/openlayers) - OpenLayers
* [mapbox/mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js) - Interactive, thoroughly customizable maps in the browser, powered by vector tiles and WebGL
* [svgdotjs/svg.js](https://github.com/svgdotjs/svg.js) - The lightweight library for manipulating and animating SVG
* [DmitryBaranovskiy/raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript Vector Library
* [adrai/flowchart.js](https://github.com/adrai/flowchart.js) - Draws simple SVG flow chart diagrams from textual representation of the diagram
* [jonobr1/two.js](https://github.com/jonobr1/two.js) - A renderer agnostic two-dimensional drawing api for the web
* [CreateJS/EaselJS](https://github.com/CreateJS/EaselJS) - The Easel Javascript library provides a full, hierarchical display list, a core interaction model, and helper classes to make working with the HTML5 Canvas element much easier.
* [bramp/js-sequence-diagrams](https://github.com/bramp/js-sequence-diagrams) - Draws simple SVG sequence diagrams from textual representation of the diagram
* [riccardoscalco/textures](https://github.com/riccardoscalco/textures) - Textures.js is a JavaScript library for creating SVG patterns
* [dagrejs/dagre](https://github.com/dagrejs/dagre) - Directed graph layout for JavaScript
* [regl-project/regl](https://github.com/regl-project/regl) - 👑 Functional WebGL
* [clientIO/joint](https://github.com/clientIO/joint) - A proven SVG-based JavaScript diagramming library powering exceptional UIs
* [mattdesl/canvas-sketch](https://github.com/mattdesl/canvas-sketch) - [beta] A framework for making generative artwork in JavaScript and the browser.
* [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) - Read and write OpenType fonts using JavaScript.
* [mpetroff/pannellum](https://github.com/mpetroff/pannellum) - Pannellum is a lightweight, free, and open source panorama viewer for the web.
* [alibaba/butterfly](https://github.com/alibaba/butterfly) - 🦋Butterfly，A JavaScript/React/Vue2 Diagramming library which concentrate on flow layout field. (基于JavaScript/React/Vue2的流程图组件)
* [maptalks/maptalks.js](https://github.com/maptalks/maptalks.js) - A light and plugable JavaScript library for integrated 2D/3D maps.
* [mdaines/viz-js](https://github.com/mdaines/viz-js) - Graphviz in your browser
* [hustcc/canvas-nest.js](https://github.com/hustcc/canvas-nest.js) - :cancer: Interactive Particle / Nest System With JavaScript and Canvas, no jQuery.
* [soulwire/sketch.js](https://github.com/soulwire/sketch.js) - Cross-Platform JavaScript Creative Coding Framework
* [ericdrowell/KineticJS](https://github.com/ericdrowell/KineticJS) - KineticJS is an HTML5 Canvas JavaScript framework that extends the 2d context by enabling canvas interactivity for desktop and mobile applications.
* [anvaka/VivaGraphJS](https://github.com/anvaka/VivaGraphJS) - Graph drawing library for JavaScript
* [Rezmason/matrix](https://github.com/Rezmason/matrix) - matrix (web-based green code rain, made with love)
* [bradley/Blotter](https://github.com/bradley/Blotter) - A JavaScript API for drawing unconventional text effects on the web.
* [pchen66/panolens.js](https://github.com/pchen66/panolens.js) - Javascript panorama viewer based on Three.js *(archived)*

### Game Development

* [phaserjs/phaser](https://github.com/phaserjs/phaser) - Phaser is a fun, free and fast 2D game framework for making HTML5 games for desktop and mobile web browsers, supporting Canvas and WebGL rendering.
* [4ian/GDevelop](https://github.com/4ian/GDevelop) - 🎮 Open-source, cross-platform 2D/3D/multiplayer game engine designed for everyone.
* [liabru/matter-js](https://github.com/liabru/matter-js) - a 2D rigid body physics engine for the web ▲● ■
* [playcanvas/engine](https://github.com/playcanvas/engine) - Powerful web graphics runtime built on WebGL, WebGPU, WebXR and glTF
* [gabrielecirulli/2048](https://github.com/gabrielecirulli/2048) - The source code for 2048
* [mozilla/BrowserQuest](https://github.com/mozilla/BrowserQuest) - DEPRECATED - A HTML5/JavaScript multiplayer game experiment *(archived)*
* [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) - Create Minecraft bots with a powerful, stable, and high level JavaScript API.
* [pshenok/server-survival](https://github.com/pshenok/server-survival) - Tower defense game that teaches cloud architecture. Build infrastructure, survive traffic, learn scaling.
* [bfirsh/jsnes](https://github.com/bfirsh/jsnes) - A JavaScript NES emulator.
* [melonjs/melonJS](https://github.com/melonjs/melonJS) - a modern & lightweight HTML5 game engine
* [flybywiresim/aircraft](https://github.com/flybywiresim/aircraft) - The A32NX & A380X Project are community driven open source projects to create free Airbus aircraft in Microsoft Flight Simulator that are as close to reality as possible.
* [nicholas-ochoa/OpenSC2K](https://github.com/nicholas-ochoa/OpenSC2K) - OpenSC2K - An Open Source remake of Sim City 2000 by Maxis
* [schteppe/cannon.js](https://github.com/schteppe/cannon.js) - A lightweight 3D physics engine written in JavaScript.
* [AlexNisnevich/untrusted](https://github.com/AlexNisnevich/untrusted) - A meta-JavaScript adventure game by Alex Nisnevich and Greg Shuflin.
* [KilledByAPixel/LittleJS](https://github.com/KilledByAPixel/LittleJS) - Tiny fast HTML5 game engine with many features and no dependencies.
* [egret-labs/egret-core](https://github.com/egret-labs/egret-core) - Egret is a brand new open mobile game and application engine which allows you to quickly build mobile games and apps on Android,iOS and Windows.
* [subprotocol/verlet-js](https://github.com/subprotocol/verlet-js) - A simple Verlet physics engine written in javascript
* [wellcaffeinated/PhysicsJS](https://github.com/wellcaffeinated/PhysicsJS) - A modular, extendable, and easy-to-use physics engine for javascript *(archived)*
* [craftyjs/Crafty](https://github.com/craftyjs/Crafty) - JavaScript Game Engine
* [victorqribeiro/isocity](https://github.com/victorqribeiro/isocity) - A isometric city builder in JavaScript
* [lo-th/Oimo.js](https://github.com/lo-th/Oimo.js) - Lightweight 3d physics engine for javascript
* [cocos2d/cocos2d-html5](https://github.com/cocos2d/cocos2d-html5) - Cocos2d for Web Browsers. Built using JavaScript.
* [deck-of-cards/deck-of-cards](https://github.com/deck-of-cards/deck-of-cards) - Deck of Cards (old version)
* [johakr/html5-slot-machine](https://github.com/johakr/html5-slot-machine) - Modern casino slot machine game using only plain JavaScript (Web Animations API)

### Audio

* [goldfire/howler.js](https://github.com/goldfire/howler.js) - Javascript audio library for the modern web.
* [xiangyuecn/Recorder](https://github.com/xiangyuecn/Recorder) - html5 js 录音 mp3 wav ogg webm amr g711a g711u 格式，支持pc和Android、iOS部分Web浏览器、Hybrid App（提供Android iOS App源码）、微信，提供ASR语音识别转文字 H5版语音通话聊天示例 DTMF编码解码
* [scottschiller/SoundManager2](https://github.com/scottschiller/SoundManager2) - A JavaScript Sound API supporting MP3, MPEG4 and HTML5 audio + RTMP, providing reliable cross-browser/platform audio control in as little as 12 KB. BSD licensed.
* [CreateJS/SoundJS](https://github.com/CreateJS/SoundJS) - A Javascript library for working with Audio. It provides a consistent API for loading and playing audio on different browsers and devices. Currently supports WebAudio, HTML5 Audio, Cordova / PhoneGap, and a Flash fallback.
* [0xfe/vexflow](https://github.com/0xfe/vexflow) - A JavaScript library for rendering music notation and guitar tablature.
* [serversideup/amplitudejs](https://github.com/serversideup/amplitudejs) - AmplitudeJS: Open Source HTML5 Web Audio Library. Design your web audio player, the way you want. No dependencies required.
* [bbc/peaks.js](https://github.com/bbc/peaks.js) - JavaScript UI component for interacting with audio waveforms

### Image and Video

* [videojs/video.js](https://github.com/videojs/video.js) - Video.js - open source HTML5 video player
* [lovell/sharp](https://github.com/lovell/sharp) - High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP, AVIF and TIFF images. Uses the libvips library.
* [sampotts/plyr](https://github.com/sampotts/plyr) - A simple HTML5, YouTube and Vimeo player
* [svg/svgo](https://github.com/svg/svgo) - SVG Optimizer for Node.js and CLI. ⚙️
* [jimp-dev/jimp](https://github.com/jimp-dev/jimp) - An image processing library written entirely in JavaScript for Node, with zero external or native dependencies.
* [fengyuanchen/cropperjs](https://github.com/fengyuanchen/cropperjs) - JavaScript image cropper.
* [lokesh/color-thief](https://github.com/lokesh/color-thief) - Grab the color palette from an image using just Javascript. Works in the browser and in Node.
* [jwagner/smartcrop.js](https://github.com/jwagner/smartcrop.js) - Content aware image cropping
* [tsayen/dom-to-image](https://github.com/tsayen/dom-to-image) - Generates an image from a DOM node using HTML5 canvas
* [shaka-project/shaka-player](https://github.com/shaka-project/shaka-player) - JavaScript player library / DASH & HLS client / MSE-EME player
* [zumerlab/snapdom](https://github.com/zumerlab/snapdom) - High-performance engine for capturing, modifying, and converting DOM elements into any format.
* [clappr/clappr](https://github.com/clappr/clappr) - An extensible, plugin-oriented, HTML5-first media player for the web
* [mapbox/pixelmatch](https://github.com/mapbox/pixelmatch) - The smallest, simplest and fastest JavaScript pixel-level image comparison library
* [muaz-khan/RecordRTC](https://github.com/muaz-khan/RecordRTC) - RecordRTC is WebRTC JavaScript library for audio/video as well as screen activity recording. It supports Chrome, Firefox, Opera, Android, and Microsoft Edge. Platforms: Linux, Mac and Windows.
* [phoboslab/jsmpeg](https://github.com/phoboslab/jsmpeg) - MPEG1 Video Decoder in JavaScript
* [lindell/JsBarcode](https://github.com/lindell/JsBarcode) - Barcode generation library written in JavaScript that works in both the browser and on Node.js
* [fengyuanchen/compressorjs](https://github.com/fengyuanchen/compressorjs) - JavaScript image compressor.
* [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) - A reference client implementation for the playback of MPEG DASH via Javascript and compliant browsers.
* [jnordberg/gif.js](https://github.com/jnordberg/gif.js) - JavaScript GIF encoding library
* [exif-js/exif-js](https://github.com/exif-js/exif-js) - JavaScript library for reading EXIF image metadata
* [eKoopmans/html2pdf.js](https://github.com/eKoopmans/html2pdf.js) - Client-side HTML-to-PDF rendering using pure JS.
* [fent/node-ytdl-core](https://github.com/fent/node-ytdl-core) - YouTube video downloader in javascript.
* [blueimp/JavaScript-Load-Image](https://github.com/blueimp/JavaScript-Load-Image) - Load images provided as File or Blob objects or via URL. Retrieve an optionally scaled, cropped or rotated HTML img or canvas element. Use methods to parse image metadata to extract IPTC and Exif tags as well as embedded thumbnail images, to overwrite the Exif Orientation value and to restore the complete image header after resizing.
* [tapmodo/Jcrop](https://github.com/tapmodo/Jcrop) - Jcrop - The Javascript Image Cropping Engine
* [LazarSoft/jsqrcode](https://github.com/LazarSoft/jsqrcode) - Javascript QRCode scanner
* [brianchirls/Seriously.js](https://github.com/brianchirls/Seriously.js) - A real-time, node-based video effects compositor for the web built with HTML5, Javascript and WebGL
* [spite/ccapture.js](https://github.com/spite/ccapture.js) - A library to capture canvas-based animations at a fixed framerate
* [evanw/glfx.js](https://github.com/evanw/glfx.js) - An image effects library for JavaScript using WebGL
* [kciter/qart.js](https://github.com/kciter/qart.js) - Generate artistic QR code. 🎨
* [schmich/instascan](https://github.com/schmich/instascan) - HTML5 QR code scanner using your webcam
* [videojs/videojs-contrib-hls](https://github.com/videojs/videojs-contrib-hls) - HLS library for video.js *(archived)*
* [imgly/rembrandt](https://github.com/imgly/rembrandt) - Image comparison using node-canvas *(archived)*

## Security

### Cryptography

* [brix/crypto-js](https://github.com/brix/crypto-js) - JavaScript library of crypto standards.
* [bitwiseshiftleft/sjcl](https://github.com/bitwiseshiftleft/sjcl) - [DEPRECATED] Stanford Javascript Crypto Library
* [travist/jsencrypt](https://github.com/travist/jsencrypt) - A tiny (18.5 kB gzip), zero-dependency, Javascript library to perform OpenSSL RSA Encryption, Decryption, and Key Generation.
* [openpgpjs/openpgpjs](https://github.com/openpgpjs/openpgpjs) - OpenPGP implementation for JavaScript
* [digitalbazaar/forge](https://github.com/digitalbazaar/forge) - A native implementation of TLS in Javascript and tools to write crypto-based and network-heavy webapps
* [blueimp/JavaScript-MD5](https://github.com/blueimp/JavaScript-MD5) - JavaScript MD5 implementation. Compatible with server-side environments like node.js, module loaders like RequireJS and all web browsers. *(archived)*
* [google/end-to-end](https://github.com/google/end-to-end) - End-To-End is a crypto library to encrypt, decrypt, digital sign, and verify signed messages (implementing OpenPGP) *(archived)*
* [KuroLabs/stegcloak](https://github.com/KuroLabs/stegcloak) - Hide secrets with invisible characters in plain text securely using passwords 🧙🏻‍♂️⭐
* [dcodeIO/bcrypt.js](https://github.com/dcodeIO/bcrypt.js) - Optimized bcrypt in JavaScript with zero dependencies, with TypeScript support.
* [bitchan/eccrypto](https://github.com/bitchan/eccrypto) - JavaScript Elliptic curve cryptography library

### Security Tools

* [qeeqbox/social-analyzer](https://github.com/qeeqbox/social-analyzer) - API, CLI, and Web App for analyzing and finding a person's profile in 1000 social media \ websites
* [cure53/DOMPurify](https://github.com/cure53/DOMPurify) - DOMPurify - a DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG. DOMPurify works with a secure default, but offers a lot of configurability and hooks. Demo:
* [OpenNHP/opennhp](https://github.com/OpenNHP/opennhp) - A lightweight, cryptography-powered, open-source toolkit built to enforce Zero Trust security for infrastructure, applications, and data in the AI-driven world.
* [tiagozip/cap](https://github.com/tiagozip/cap) - Free, open-source and self-hosted CAPTCHA alternative to reCAPTCHA. Privacy-first and powered by proof-of-work and instrumentation challenges.
* [arkime/arkime](https://github.com/arkime/arkime) - Arkime is an open source, large scale, full packet capturing, indexing, and database system.
* [RetireJS/retire.js](https://github.com/RetireJS/retire.js) - scanner detecting the use of JavaScript libraries with known vulnerabilities. Can also generate an SBOM of the libraries it finds.
* [patriksimek/vm2](https://github.com/patriksimek/vm2) - Advanced vm/sandbox for Node.js

## Concurrency and Performance

### Performance and Optimization

* [gpujs/gpu.js](https://github.com/gpujs/gpu.js) - GPU Accelerated JavaScript
* [facebookarchive/prepack](https://github.com/facebookarchive/prepack) - A JavaScript bundle optimizer. *(archived)*
* [krausest/js-framework-benchmark](https://github.com/krausest/js-framework-benchmark) - A comparison of the performance of a few popular javascript frameworks
* [nodeca/pako](https://github.com/nodeca/pako) - high speed zlib port to javascript, works in browser & node.js
* [gildas-lormeau/zip.js](https://github.com/gildas-lormeau/zip.js) - JavaScript library to zip and unzip files supporting parallel compression, web streams, pluggable compression engines, zip64, split files, data encryption, and deflate64 decompression.
* [codemix/fast.js](https://github.com/codemix/fast.js) - Faster user-land reimplementations for several common builtin native JavaScript functions.
* [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) - a streaming interface for archive generation
* [jsbench/jsbench.github.io](https://github.com/jsbench/jsbench.github.io) - JavaScript benchmark playground

## Testing and Quality

### Testing

* [mochajs/mocha](https://github.com/mochajs/mocha) - ☕️ Classic, reliable, trusted test framework for Node.js and the browser
* [avajs/ava](https://github.com/avajs/ava) - Node.js test runner that lets you develop with confidence 🚀
* [enzymejs/enzyme](https://github.com/enzymejs/enzyme) - JavaScript Testing utilities for React
* [testing-library/react-testing-library](https://github.com/testing-library/react-testing-library) - 🐐 Simple and complete React DOM testing utilities that encourage good testing practices.
* [jasmine/jasmine](https://github.com/jasmine/jasmine) - Simple JavaScript testing framework for browsers and node.js
* [nock/nock](https://github.com/nock/nock) - HTTP server mocking and expectations library for Node.js
* [wix/Detox](https://github.com/wix/Detox) - Gray box end-to-end testing and automation framework for mobile apps
* [karma-runner/karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript
* [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) - Integrated end-to-end testing framework written in Node.js and using W3C Webdriver API. Developed at @browserstack
* [Netflix/pollyjs](https://github.com/Netflix/pollyjs) - Record, Replay, and Stub HTTP Interactions.
* [sinonjs/sinon](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks for JavaScript.
* [artilleryio/artillery](https://github.com/artilleryio/artillery) - The complete load testing platform. Everything you need for production-grade load tests. Serverless & distributed. Load test with Playwright. Load test HTTP APIs, GraphQL, WebSocket, and more. Use any Node.js module.
* [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) - A persistent service that generates mock data quickly and provids visualization view.
* [angular/protractor](https://github.com/angular/protractor) - E2E test framework for Angular apps *(archived)*
* [chaijs/chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [garris/BackstopJS](https://github.com/garris/BackstopJS) - Catch CSS curve balls.
* [istanbuljs/nyc](https://github.com/istanbuljs/nyc) - the Istanbul command line interface
* [miragejs/miragejs](https://github.com/miragejs/miragejs) - A client-side server to build, test and share your JavaScript app
* [testing-library/jest-dom](https://github.com/testing-library/jest-dom) - :owl: Custom jest matchers to test the state of the DOM
* [pa11y/pa11y](https://github.com/pa11y/pa11y) - Pa11y is your automated accessibility testing pal
* [codeceptjs/CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - Supercharged End 2 End Testing Framework for NodeJS
* [qunitjs/qunit](https://github.com/qunitjs/qunit) - 🔮 An easy-to-use JavaScript unit testing framework.
* [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) - Axios adapter that allows to easily mock requests
* [testing-library/dom-testing-library](https://github.com/testing-library/dom-testing-library) - 🐙 Simple and complete DOM testing utilities that encourage good testing practices.
* [boo1ean/casual](https://github.com/boo1ean/casual) - Fake data generator for javascript
* [testem/testem](https://github.com/testem/testem) - Test'em 'Scripts! A test runner that makes Javascript unit testing fun.
* [power-assert-js/power-assert](https://github.com/power-assert-js/power-assert) - Power Assert in JavaScript. Provides descriptive assertion messages through standard assert interface. No API is the best API.

## Utilities

### Command Line Tools

* [commitizen/cz-cli](https://github.com/commitizen/cz-cli) - The commitizen command line utility. #BlackLivesMatter
* [shelljs/shelljs](https://github.com/shelljs/shelljs) - :shell: Portable Unix shell commands for Node.js
* [sindresorhus/fkill-cli](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform.
* [sindresorhus/create-dmg](https://github.com/sindresorhus/create-dmg) - Create a good-looking DMG for your macOS app in seconds
* [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) - MOVED to jsonresume/jsonresume.org (packages/cli) — npm 'resume-cli' unchanged, revived for Node 18+ *(archived)*
* [homerchen19/nba-go](https://github.com/homerchen19/nba-go) - 🏀 💻 The finest NBA CLI.
* [sindresorhus/meow](https://github.com/sindresorhus/meow) - 🐈 CLI app helper
* [feross/thanks](https://github.com/feross/thanks) - 🙌 Give thanks to the open source maintainers you depend on! ✨

### Text Processing

* [validatorjs/validator.js](https://github.com/validatorjs/validator.js) - String validation
* [markdown-it/markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser, done right. 100% CommonMark support, extensions, syntax plugins & high speed
* [janl/mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript
* [showdownjs/showdown](https://github.com/showdownjs/showdown) - A bidirectional Markdown to HTML to Markdown converter written in Javascript
* [VerbalExpressions/JSVerbalExpressions](https://github.com/VerbalExpressions/JSVerbalExpressions) - JavaScript Regular expressions made easy
* [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) - UAParser.js - The Essential Web Development Tool for User-Agent Detection. Detect Browsers, OS, Devices, Bots, Apps, AI Crawlers, and more. Run in Browser (client-side) or Node.js (server-side).
* [goofychris/art-template](https://github.com/goofychris/art-template) - High performance JavaScript templating engine
* [adamwdraper/Numeral-js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers.
* [kpdecker/jsdiff](https://github.com/kpdecker/jsdiff) - A javascript text differencing implementation.
* [remarkjs/remark](https://github.com/remarkjs/remark) - markdown processor powered by plugins part of the @unifiedjs collective
* [ljharb/qs](https://github.com/ljharb/qs) - A querystring parser and serializer with nesting support
* [i18next/i18next](https://github.com/i18next/i18next) - i18next: learn once - translate everywhere
* [mde/ejs](https://github.com/mde/ejs) - Embedded JavaScript templates -- http://ejs.co
* [evilstreak/markdown-js](https://github.com/evilstreak/markdown-js) - A Markdown parser for javascript
* [kazupon/vue-i18n](https://github.com/kazupon/vue-i18n) - :globe_with_meridians: Internationalization plugin for Vue.js *(archived)*
* [medialize/URI.js](https://github.com/medialize/URI.js) - Javascript URL mutation library
* [jonschlinkert/remarkable](https://github.com/jonschlinkert/remarkable) - Markdown parser, done right. Commonmark support, extensions, syntax plugins, high speed - all in one. Gulp and metalsmith plugins available. Used by Facebook, Docusaurus and many others! Use https://github.com/breakdance/breakdance for HTML-to-markdown conversion. Use https://github.com/jonschlinkert/markdown-toc to generate a table of contents.
* [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - Diff & patch JavaScript objects
* [toolgood/ToolGood.Words](https://github.com/toolgood/ToolGood.Words) - 一款高性能敏感词(非法词/脏字)检测过滤组件，附带繁体简体互换，支持全角半角互换，汉字转拼音，模糊搜索等功能。
* [olado/doT](https://github.com/olado/doT) - The fastest + concise javascript template engine for nodejs and browsers. Partials, custom delimiters and more.
* [unifiedjs/unified](https://github.com/unifiedjs/unified) - Parse, inspect, transform, and serialize content with syntax trees
* [openexchangerates/accounting.js](https://github.com/openexchangerates/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies.
* [globalizejs/globalize](https://github.com/globalizejs/globalize) - A JavaScript library for internationalization and localization that leverages the official Unicode CLDR JSON data
* [vinta/pangu.js](https://github.com/vinta/pangu.js) - Opinionated paranoid text spacing in JavaScript, with on-device AI semantic judgment
* [francisrstokes/super-expressive](https://github.com/francisrstokes/super-expressive) - 🦜 Super Expressive is a zero-dependency JavaScript library for building regular expressions in (almost) natural language
* [tj/ejs](https://github.com/tj/ejs) - Embedded JavaScript templates for node
* [dankogai/js-base64](https://github.com/dankogai/js-base64) - Base64 implementation for JavaScript
* [angular-translate/angular-translate](https://github.com/angular-translate/angular-translate) - DEPRECATED Translating your AngularJS 1.x apps *(archived)*
* [facebook/fbt](https://github.com/facebook/fbt) - A JavaScript Internationalization Framework *(archived)*
* [airbnb/polyglot.js](https://github.com/airbnb/polyglot.js) - Give your JavaScript the ability to speak many languages.
* [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) - Generate docx, pptx, and xlsx from templates (Word, Powerpoint and Excel documents), from Node.js or the browser. Demo: https://www.docxtemplater.com/demo. #docx #office #generator #templating #report #json #generate #generation #template #create #pptx #docx #xlsx #react #vuejs #angularjs #browser #typescript #image #html #table #chart
* [mathiasbynens/he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript.
* [panzerdp/voca](https://github.com/panzerdp/voca) - The ultimate JavaScript string library
* [esamattis/underscore.string](https://github.com/esamattis/underscore.string) - String manipulation helpers for javascript
* [slevithan/xregexp](https://github.com/slevithan/xregexp) - Extended JavaScript regular expressions
* [pillarjs/iconv-lite](https://github.com/pillarjs/iconv-lite) - Convert character encodings in pure javascript.
* [paularmstrong/swig](https://github.com/paularmstrong/swig) - Take a swig of the best template engine for JavaScript. *(archived)*
* [patorjk/figlet.js](https://github.com/patorjk/figlet.js) - A FIG Driver written in JavaScript which aims to fully implement the FIGfont spec.
* [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) - A simpler (and smaller) rewrite of Google Android's libphonenumber library in javascript
* [linkedin/dustjs](https://github.com/linkedin/dustjs) - Asynchronous Javascript templating for the browser and server
* [galaxykate/tracery](https://github.com/galaxykate/tracery) - Tracery: a story-grammar generation library for javascript
* [dleitee/strman](https://github.com/dleitee/strman) - 🏗A Javascript string manipulation library.
* [toptensoftware/markdowndeep](https://github.com/toptensoftware/markdowndeep) - Open-source implementation of Markdown for C# and Javascript
* [formatjs/handlebars-intl](https://github.com/formatjs/handlebars-intl) - Handlebars helpers for internationalization.

### Files and Operating System

* [jprichardson/node-fs-extra](https://github.com/jprichardson/node-fs-extra) - Node.js: extra methods for the fs object like copy(), remove(), mkdirs()
* [sindresorhus/execa](https://github.com/sindresorhus/execa) - Process execution for humans
* [mikaelbr/node-notifier](https://github.com/mikaelbr/node-notifier) - A Node.js module for sending notifications on native Mac, Windows and Linux (or Growl as fallback)
* [sindresorhus/file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a file, stream, or data
* [isaacs/minimatch](https://github.com/isaacs/minimatch) - a glob matcher in javascript
* [micromatch/micromatch](https://github.com/micromatch/micromatch) - Highly optimized wildcard and glob matching library. Faster, drop-in replacement to minimatch and multimatch. Used by square, webpack, babel core, yarn, jest, ract-native, taro, bulma, browser-sync, stylelint, nyc, ava, and many others! Follow micromatch's author: https://github.com/jonschlinkert

### Automation and Scripting

* [google/zx](https://github.com/google/zx) - A tool for writing better scripts
* [node-red/node-red](https://github.com/node-red/node-red) - Low-code programming for event-driven applications
* [lowlighter/metrics](https://github.com/lowlighter/metrics) - 📊 An infographics generator with 30+ plugins and 300+ options to display stats about your GitHub account and render them as SVG, Markdown, PDF or JSON!
* [microsoft/botframework-sdk](https://github.com/microsoft/botframework-sdk) - Bot Framework provides the most comprehensive experience for building conversation applications. *(archived)*
* [plopjs/plop](https://github.com/plopjs/plop) - Consistency Made Simple
* [vynect/venom](https://github.com/vynect/venom) - Venom is a high-performance system developed with JavaScript to create a bot for WhatsApp, support for creating any interaction, such as customer service, media sending, sentence recognition based on artificial intelligence and all types of design architecture for WhatsApp.
* [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) - Yeoman generator for an Angular app with an Express server *(archived)*
* [jamiewilson/form-to-google-sheets](https://github.com/jamiewilson/form-to-google-sheets) - Store HTML form submissions in Google Sheets.
* [SuperMonster003/Ant-Forest](https://github.com/SuperMonster003/Ant-Forest) - AutoJs6-based ant forest energy auto-collect script (基于 AutoJs6 的蚂蚁森林能量自动收取脚本)

### General Purpose Libraries

* [lodash/lodash](https://github.com/lodash/lodash) - A modern JavaScript utility library delivering modularity, performance, & extras.
* [jashkenas/underscore](https://github.com/jashkenas/underscore) - JavaScript's utility _ belt
* [ai/nanoid](https://github.com/ai/nanoid) - A tiny (118 bytes), secure, URL-friendly, unique string ID generator for JavaScript
* [zloirock/core-js](https://github.com/zloirock/core-js) - Standard Library
* [ramda/ramda](https://github.com/ramda/ramda) - :ram: Practical functional Javascript
* [hapijs/joi](https://github.com/hapijs/joi) - The most powerful data validation library for JS
* [uuidjs/uuid](https://github.com/uuidjs/uuid) - Generate RFC-compliant UUIDs in JavaScript
* [davidshimjs/qrcodejs](https://github.com/davidshimjs/qrcodejs) - Cross-browser QRCode generator for javascript
* [gka/chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations
* [jakesgordon/javascript-state-machine](https://github.com/jakesgordon/javascript-state-machine) - A javascript finite state machine library
* [es-shims/es5-shim](https://github.com/es-shims/es5-shim) - ECMAScript 5 compatibility shims for legacy (and modern) JavaScript engines
* [chancejs/chancejs](https://github.com/chancejs/chancejs) - Chance - Random generator helper for JavaScript
* [angus-c/just](https://github.com/angus-c/just) - A library of dependency-free JavaScript utilities that do just one thing.
* [bowser-js/bowser](https://github.com/bowser-js/bowser) - a browser detector
* [rtfeldman/seamless-immutable](https://github.com/rtfeldman/seamless-immutable) - Immutable data structures for JavaScript which are backwards-compatible with normal JS Arrays and Objects. *(archived)*
* [bgrins/TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript
* [Qix-/color](https://github.com/Qix-/color) - :rainbow: Javascript color conversion and manipulation library
* [google/closure-library](https://github.com/google/closure-library) - Google's common JavaScript library *(archived)*
* [andrewplummer/Sugar](https://github.com/andrewplummer/Sugar) - A Javascript library for working with native objects.
* [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) - Library of stage-0 JavaScript decorators (aka ES2016/ES7 decorators but not accurate) inspired by languages that come with built-ins like @​override, @​deprecate, @​autobind, @​mixin and more. Popular with React/Angular, but is framework agnostic. *(archived)*
* [imbrn/v8n](https://github.com/imbrn/v8n) - ☑️ JavaScript fluent validation library
* [AsyncBanana/microdiff](https://github.com/AsyncBanana/microdiff) - A fast, zero dependency object and array comparison library. Significantly faster than most other deep comparison libraries and has full TypeScript support.
* [webpack/tapable](https://github.com/webpack/tapable) - Just a little module for plugins.
* [locutusjs/locutus](https://github.com/locutusjs/locutus) - Bringing stdlibs of other programming languages to TypeScript for fun
* [ulid/javascript](https://github.com/ulid/javascript) - Universally Unique Lexicographically Sortable Identifier
* [scurker/currency.js](https://github.com/scurker/currency.js) - A javascript library for handling currencies
* [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) - JavaScript & TypeScript persistent and optionally immutable data tree with cursors.
* [Olical/EventEmitter](https://github.com/Olical/EventEmitter) - Evented JavaScript for the browser *(archived)*
* [sanctuary-js/sanctuary](https://github.com/sanctuary-js/sanctuary) - :see_no_evil: Refuge from unsafe JavaScript
* [stampit-org/stampit](https://github.com/stampit-org/stampit) - OOP is better with stamps: Composable object factories.
* [toss/slash](https://github.com/toss/slash) - A collection of TypeScript/JavaScript packages to build high-quality web services. *(archived)*
* [TehShrike/deepmerge](https://github.com/TehShrike/deepmerge) - A library for deep (recursive) merging of Javascript objects
* [proYang/outils](https://github.com/proYang/outils) - :rocket: 前端业务代码工具库
* [ifandelse/machina.js](https://github.com/ifandelse/machina.js) - ts ex machina - finite state machines in TypeScript
* [jumpkick-studios/Is](https://github.com/jumpkick-studios/Is) - A better way to write JavaScript conditional statements and still have pretty code.

## Science and Math

### Mathematics

* [josdejong/mathjs](https://github.com/josdejong/mathjs) - An extensive math library for JavaScript and Node.js
* [Turfjs/turf](https://github.com/Turfjs/turf) - A modular geospatial engine written in JavaScript and TypeScript
* [MikeMcl/decimal.js](https://github.com/MikeMcl/decimal.js) - An arbitrary-precision Decimal type for JavaScript
* [MikeMcl/bignumber.js](https://github.com/MikeMcl/bignumber.js) - A JavaScript library for arbitrary-precision decimal and non-decimal arithmetic
* [stdlib-js/stdlib](https://github.com/stdlib-js/stdlib) - ✨ The fundamental numerical library for JavaScript and TypeScript. ✨ ⭐️ Star to support our work!
* [toji/gl-matrix](https://github.com/toji/gl-matrix) - Javascript Matrix and Vector library for High Performance WebGL apps
* [MikeMcl/big.js](https://github.com/MikeMcl/big.js) - A small, fast JavaScript library for arbitrary-precision decimal arithmetic.
* [simple-statistics/simple-statistics](https://github.com/simple-statistics/simple-statistics) - simple statistics for node & browser javascript

## Other

* [affaan-m/ECC](https://github.com/affaan-m/ECC) - The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.
* [Snailclimb/JavaGuide](https://github.com/Snailclimb/JavaGuide) - Java 面试 & 后端通用面试指南，覆盖计算机基础、数据库、分布式、高并发、系统设计与 AI 应用开发
* [vercel/next.js](https://github.com/vercel/next.js) - The React Framework
* [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) - Makes your AI agent think like the laziest senior dev in the room. The best code is the code you never wrote.
* [react/create-react-app](https://github.com/react/create-react-app) - Set up a modern web app by running one command.
* [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) - Production-grade engineering skills for AI coding agents.
* [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) - Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More
* [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) - A fancy self-hosted monitoring tool
* [sveltejs/svelte](https://github.com/sveltejs/svelte) - web development for the rest of us
* [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) - Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop
* [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) - :zap: Dynamically generated stats for your github readmes
* [FortAwesome/Font-Awesome](https://github.com/FortAwesome/Font-Awesome) - The iconic SVG, font, and CSS toolkit
* [typicode/json-server](https://github.com/typicode/json-server) - Get a full fake REST API with zero coding in less than 30 seconds (seriously)
* [hakimel/reveal.js](https://github.com/hakimel/reveal.js) - The HTML Presentation Framework
* [career-ops-hq/career-ops](https://github.com/career-ops-hq/career-ops) - Open-source AI job search: scan job portals, evaluate listings into a structured A-H report with a global 1-5 score, tailor your CV, track applications — runs locally in your AI coding CLI (Claude Code, Codex, OpenCode, Antigravity…)
* [pbakaus/impeccable](https://github.com/pbakaus/impeccable) - The design language that makes your AI harness better at design.
* [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) - Extracted system prompts from Anthropic - Claude Fable 5.1, Opus 5, Claude Design, Claude Code. OpenAI - ChatGPT GPT-6-Astra, Codex. Google - Gemini 3.8 Flash, 3.1 Pro, Antigravity. xAI - Grok, Grok Bot, Cursor, Kimi and more! Updated regularly.
* [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) - Stop renting your intelligence. Own it with AnythingLLM. Everything you need for a powerful local-first agent experience
* [tt-a1i/archify](https://github.com/tt-a1i/archify) - Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams—self-contained HTML with motion and crisp export.
* [gsd-build/get-shit-done](https://github.com/gsd-build/get-shit-done) - A light-weight and powerful meta-prompting, context engineering and spec-driven development system for Claude Code by TÂCHES. *(archived)*
* [jgraph/drawio-desktop](https://github.com/jgraph/drawio-desktop) - Official electron build of draw.io
* [resume/resume.github.com](https://github.com/resume/resume.github.com) - Resumes generated using the GitHub informations
* [byoungd/up](https://github.com/byoungd/up) - An advanced guide which might benefit you a lot 🎉 . 韩先凯的人生进阶指南 人生进阶指南 离谱的人生 人生进阶 AI学习 AI指南 韩先凯的AI学习指南 英语学习指南/英语学习教程/英语学习/学英语
* [adam-p/markdown-here](https://github.com/adam-p/markdown-here) - Google Chrome, Firefox, and Thunderbird extension that lets you write email in Markdown and render it before sending.
* [angular/angular.js](https://github.com/angular/angular.js) - AngularJS - HTML enhanced for web apps! *(archived)*
* [scutan90/DeepLearning-500-questions](https://github.com/scutan90/DeepLearning-500-questions) - 深度学习500问，以问答形式对常用的概率知识、线性代数、机器学习、深度学习、计算机视觉等热点问题进行阐述，以帮助自己及有需要的读者。 全书分为18个章节，50余万字。由于水平有限，书中不妥之处恳请广大读者批评指正。 未完待续............ 如有意合作，联系scutjy2015@163.com 版权所有，违权必究 Tan 2018.06
* [gatsbyjs/gatsby](https://github.com/gatsbyjs/gatsby) - React-based framework with performance, scalability, and security built in.
* [chinese-poetry/chinese-poetry](https://github.com/chinese-poetry/chinese-poetry) - The most comprehensive database of Chinese poetry 🧶最全中华古诗词数据库, 唐宋两朝近一万四千古诗人, 接近5.5万首唐诗加26万宋诗. 两宋时期1564位词人，21050首词。
* [bmad-code-org/BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD) - Breakthrough Method for Agile Ai Driven Development
* [poteto/hiring-without-whiteboards](https://github.com/poteto/hiring-without-whiteboards) - ⭐️ Companies that don't have a broken hiring process
* [Semantic-Org/Semantic-UI](https://github.com/Semantic-Org/Semantic-UI) - Semantic is a UI component framework based around useful principles from natural language.
* [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) - Marketing skills for Claude Code and AI agents. CRO, copywriting, SEO, analytics, and growth engineering.
* [NARKOZ/hacker-scripts](https://github.com/NARKOZ/hacker-scripts) - Based on a true story
* [algorithm-visualizer/algorithm-visualizer](https://github.com/algorithm-visualizer/algorithm-visualizer) - :fireworks:Interactive Online Platform that Visualizes Algorithms from Code
* [iamkun/dayjs](https://github.com/iamkun/dayjs) - ⏰ Day.js 2kB immutable date-time library alternative to Moment.js with the same modern API
* [moment/moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript.
* [serverless/serverless](https://github.com/serverless/serverless) - ⚡ Serverless Framework – Effortlessly build apps that auto-scale, incur zero costs when idle, and require minimal maintenance using AWS Lambda and other managed cloud services.
* [microsoft/monaco-editor](https://github.com/microsoft/monaco-editor) - A browser based code editor
* [GitSquared/edex-ui](https://github.com/GitSquared/edex-ui) - A cross-platform, customizable science fiction terminal emulator with advanced monitoring & touchscreen support. *(archived)*
* [NaiboWang/EasySpider](https://github.com/NaiboWang/EasySpider) - A visual no-code/code-free web crawler/spider易采集：一个可视化浏览器自动化测试/数据采集/网页爬虫软件，可以无代码图形化的设计和执行爬虫任务。别名：ServiceWrapper面向Web应用的智能化服务封装系统。
* [Unitech/pm2](https://github.com/Unitech/pm2) - Node.js/Typescript/Bun Production Process Manager with a built-in Load Balancer.
* [saadeghi/daisyui](https://github.com/saadeghi/daisyui) - 🌼 🌼 🌼 🌼 🌼 The most popular, free and open-source Tailwind CSS component library
* [goabstract/Awesome-Design-Tools](https://github.com/goabstract/Awesome-Design-Tools) - The best design tools and plugins for everything 👉
* [nwjs/nw.js](https://github.com/nwjs/nw.js) - Call all Node.js modules directly from DOM/WebWorker and enable a new way of writing applications with all Web technologies.
* [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) - Source for remoteintech.company — a community-maintained directory of remote-friendly tech companies
* [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) - 📄 Configuration files that enhance Cursor AI editor experience with custom rules and behaviors
* [github/awesome-copilot](https://github.com/github/awesome-copilot) - Community-contributed instructions, agents, skills, and configurations to help you make the most of GitHub Copilot.
* [preactjs/preact](https://github.com/preactjs/preact) - ⚛️ Fast 3kB React alternative with the same modern API. Components & Virtual DOM.
* [impress/impress.js](https://github.com/impress/impress.js) - It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com.
* [markedjs/marked](https://github.com/markedjs/marked) - A markdown parser and compiler. Built for speed.
* [fastify/fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework, for Node.js
* [songquanpeng/one-api](https://github.com/songquanpeng/one-api) - LLM API 管理 & 分发系统，支持 OpenAI、Azure、Anthropic Claude、Google Gemini、DeepSeek、字节豆包、ChatGLM、文心一言、讯飞星火、通义千问、360 智脑、腾讯混元等主流模型，统一 API 适配，可用于 key 管理与二次分发。单可执行文件，提供 Docker 镜像，一键部署，开箱即用。LLM API management & key redistribution system, unifying multiple providers under a single API. Single binary, Docker-ready, with an English UI.
* [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) - A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.
* [gchq/CyberChef](https://github.com/gchq/CyberChef) - The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis
* [ryanhanwu/How-To-Ask-Questions-The-Smart-Way](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way) - 本文原文由知名 Hacker Eric S. Raymond 所撰寫，教你如何正確的提出技術問題並獲得你滿意的答案。
* [koajs/koa](https://github.com/koajs/koa) - Expressive middleware for node.js using ES2017 async functions
* [typicode/husky](https://github.com/typicode/husky) - Git hooks made easy 🐶 woof!
* [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) - A boilerplate for Node.js web applications
* [qishibo/AnotherRedisDesktopManager](https://github.com/qishibo/AnotherRedisDesktopManager) - 🚀🚀🚀A faster, better and more stable Redis desktop manager [GUI client], compatible with Linux, Windows, Mac.
* [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) - Clone any website with one command using AI coding agents
* [pcottle/learnGitBranching](https://github.com/pcottle/learnGitBranching) - An interactive git visualization and tutorial. Aspiring students of git can use this app to educate and challenge themselves towards mastery of git!
* [atlassian/react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd) - Beautiful and accessible drag and drop for lists with React *(archived)*
* [lutzroeder/netron](https://github.com/lutzroeder/netron) - Visualizer for neural network, deep learning and machine learning models
* [SillyTavern/SillyTavern](https://github.com/SillyTavern/SillyTavern) - LLM Frontend for Power Users.
* [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) - Use Codex from Claude Code to review code or delegate tasks.
* [maboloshi/github-chinese](https://github.com/maboloshi/github-chinese) - GitHub 汉化插件，GitHub 中文化界面。 (GitHub Translation To Chinese)
* [gulpjs/gulp](https://github.com/gulpjs/gulp) - A toolkit to automate & enhance your workflow
* [gethomepage/homepage](https://github.com/gethomepage/homepage) - A highly customizable homepage (or startpage / application dashboard) with Docker and service API integrations.
* [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) - Prompt as Code | GPT Image 2 / 2.5 提示词与案例库，530+ 个案例、20+ 套工业级模板与可复用 Skills，新增 2.5 同提示词对比专区，附完整提示词与生成记录，持续更新。
* [airbnb/lottie-web](https://github.com/airbnb/lottie-web) - Render After Effects animations natively on Web, Android and iOS, and React Native. http://airbnb.io/lottie/
* [docsifyjs/docsify](https://github.com/docsifyjs/docsify) - 🃏 A magical documentation site generator.
* [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) - Vercel's official collection of agent skills
* [AMAI-GmbH/AI-Expert-Roadmap](https://github.com/AMAI-GmbH/AI-Expert-Roadmap) - Roadmap to becoming an Artificial Intelligence Expert in 2022
* [ascoders/weekly](https://github.com/ascoders/weekly) - 前端精读周刊。帮你理解最前沿、实用的技术。
* [SortableJS/Sortable](https://github.com/SortableJS/Sortable) - Reorderable drag-and-drop lists for modern browsers and touch devices. No jQuery or framework required.
* [GoogleChrome/lighthouse](https://github.com/GoogleChrome/lighthouse) - Automated auditing, performance metrics, and best practices for the web.
* [foundation/yeti](https://github.com/foundation/yeti) - A CSS-first, native, zero-build layout and styling framework for web designers.
* [aosabook/500lines](https://github.com/aosabook/500lines) - 500 Lines or Less
* [vuejs/vue-cli](https://github.com/vuejs/vue-cli) - 🛠️ webpack-based tooling for Vue.js Development
* [react-boilerplate/react-boilerplate](https://github.com/react-boilerplate/react-boilerplate) - 🔥 A highly scalable, offline-first foundation with the best developer experience and a focus on performance and best practices.
* [zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides) - Create beautiful slides on the web using a coding agent's frontend skills
* [jackwener/OpenCLI](https://github.com/jackwener/OpenCLI) - Make Any Website into CLI & Use your logged-in browser by AI agent.
* [decolua/9router](https://github.com/decolua/9router) - Unlimited FREE AI coding. Connect Claude Code, Codex, Cursor, Cline, Copilot, Antigravity to FREE Claude/GPT/Gemini via 40+ providers. Auto-fallback, RTK -40% tokens, never hit limits.
* [viatsko/awesome-vscode](https://github.com/viatsko/awesome-vscode) - 🎨 A curated list of delightful VS Code packages and resources.
* [immerjs/immer](https://github.com/immerjs/immer) - Create the next immutable state by mutating the current one
* [jamiebuilds/the-super-tiny-compiler](https://github.com/jamiebuilds/the-super-tiny-compiler) - :snowman: Possibly the smallest compiler ever
* [Z-Siqi/Clash-for-Windows_Chinese](https://github.com/Z-Siqi/Clash-for-Windows_Chinese) - clash for windows汉化版. 提供clash for windows的汉化版, 汉化补丁及汉化版安装程序
* [kenwheeler/slick](https://github.com/kenwheeler/slick) - the last carousel you'll ever need
* [fanmingming/live](https://github.com/fanmingming/live) - ✯ 可直连访问的电视/广播图标库与相关工具项目 ✯ 🔕 永久免费 直连访问 完整开源 不断完善的台标 支持IPv4/IPv6双栈访问 🔕
* [tj/commander.js](https://github.com/tj/commander.js) - node.js command-line interfaces made easy
* [digitalocean/nginxconfig.io](https://github.com/digitalocean/nginxconfig.io) - ⚙️ NGINX config generator on steroids 💉
* [koodo-reader/koodo-reader](https://github.com/koodo-reader/koodo-reader) - A modern ebook manager and reader with sync and backup capacities for Windows, macOS, Linux, Android, iOS and Web
* [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud) - A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress
* [caolan/async](https://github.com/caolan/async) - Async utilities for node and the browser
* [jashkenas/backbone](https://github.com/jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events
* [eyaltoledano/claude-task-master](https://github.com/eyaltoledano/claude-task-master) - An AI-powered task-management system you can drop into Cursor, Lovable, Windsurf, Roo, and others.
* [michalsnik/aos](https://github.com/michalsnik/aos) - Animate on scroll library
* [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script) - 分流规则、重写写规则及脚本。
* [YMFE/yapi](https://github.com/YMFE/yapi) - YApi 是一个可本地部署的、打通前后端及QA的、可视化的接口管理平台
* [Automattic/mongoose](https://github.com/Automattic/mongoose) - MongoDB object modeling designed to work in an asynchronous environment.
* [codemirror/codemirror5](https://github.com/codemirror/codemirror5) - In-browser code editor (version 5, legacy) *(archived)*
* [badges/shields](https://github.com/badges/shields) - Concise, consistent, and legible badges in SVG and raster format
* [ajaxorg/ace](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor)
* [bvaughn/react-virtualized](https://github.com/bvaughn/react-virtualized) - React components for efficiently rendering large lists and tabular data
* [philc/vimium](https://github.com/philc/vimium) - The hacker's browser.
* [remy/nodemon](https://github.com/remy/nodemon) - Monitor for any changes in your node.js application and automatically restart the server - perfect for development
* [rstacruz/nprogress](https://github.com/rstacruz/nprogress) - For slim progress bars like on YouTube, Medium, etc
* [rollup/rollup](https://github.com/rollup/rollup) - Next-generation ES module bundler
* [simple-icons/simple-icons](https://github.com/simple-icons/simple-icons) - SVG icons for popular brands
* [zhaoolee/ChromeAppHeroes](https://github.com/zhaoolee/ChromeAppHeroes) - 🌈谷粒-Chrome插件英雄榜, 为优秀的Chrome插件写一本中文说明书, 让Chrome插件英雄们造福人类~ ChromePluginHeroes, Write a Chinese manual for the excellent Chrome plugin, let the Chrome plugin heroes benefit the human~ 公众号「0加1」同步更新
* [request/request](https://github.com/request/request) - 🏊🏾 Simplified HTTP request client.
* [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) - JavaScript syntax highlighter with language auto-detection and zero dependencies.
* [spicetify/cli](https://github.com/spicetify/cli) - Command-line tool to customize Spotify client. Supports Windows, macOS, and Linux.
* [winstonjs/winston](https://github.com/winstonjs/winston) - A logger for just about everything.
* [Max-Eee/NeoPass](https://github.com/Max-Eee/NeoPass) - Your Essential Exam Companion for the Iamneo Portal & NPTEL Exams Disguised as NeoExamShield bypass
* [vercel/pkg](https://github.com/vercel/pkg) - Package your Node.js project into an executable *(archived)*
* [docmirror/dev-sidecar](https://github.com/docmirror/dev-sidecar) - 开发者边车，github打不开，github加速，git clone加速，git release下载加速，stackoverflow加速
* [semantic-release/semantic-release](https://github.com/semantic-release/semantic-release) - 📦🚀 Fully automated version management and package publishing
* [tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons) - A set of free MIT-licensed high-quality SVG icons for UI development.
* [pure-css/pure](https://github.com/pure-css/pure) - A set of small, responsive CSS modules that you can use in every web project.
* [jaredhanson/passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication for Node.js.
* [copy/v86](https://github.com/copy/v86) - x86 PC emulator and x86-to-wasm JIT, running in the browser
* [chalk/chalk](https://github.com/chalk/chalk) - 🖍 Terminal string styling done right
* [shimohq/chinese-programmer-wrong-pronunciation](https://github.com/shimohq/chinese-programmer-wrong-pronunciation) - 中国程序员容易发音错误的单词
* [ovity/octotree](https://github.com/ovity/octotree) - GitHub on steroids
* [youhunwl/TVAPP](https://github.com/youhunwl/TVAPP) - 收集全网 Android TV电视盒子应用，涵盖影视、直播、K歌、工具、游戏等类型，整理优质APK资源，支持便捷下载与自动更新。提供安全验证、分类索引与兼容性标注，助力用户打造家庭影音娱乐中心！ ✅ TVBox/影视仓等影音壳接口配置源。
* [bilibili/flv.js](https://github.com/bilibili/flv.js) - HTML5 FLV Player
* [yjs/yjs](https://github.com/yjs/yjs) - Shared data types for building collaborative software
* [balderdashy/sails](https://github.com/balderdashy/sails) - Realtime MVC Framework for Node.js
* [be5invis/Iosevka](https://github.com/be5invis/Iosevka) - Versatile typeface for code, from code.
* [vuejs/vuepress](https://github.com/vuejs/vuepress) - 📝 Minimalistic Vue-powered static site generator
* [facebookarchive/draft-js](https://github.com/facebookarchive/draft-js) - A React framework for building text editors. *(archived)*
* [wwebjs/whatsapp-web.js](https://github.com/wwebjs/whatsapp-web.js) - A WhatsApp client library for NodeJS that connects through the WhatsApp Web browser app
* [Tencent/wepy](https://github.com/Tencent/wepy) - 小程序组件化开发框架 - 已归档 *(archived)*
* [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) - expose yourself
* [redux-saga/redux-saga](https://github.com/redux-saga/redux-saga) - An alternative side effect model for Redux apps
* [postcss/autoprefixer](https://github.com/postcss/autoprefixer) - Parse CSS and add vendor prefixes to rules by Can I Use
* [necolas/react-native-web](https://github.com/necolas/react-native-web) - Cross-platform React UI packages
* [eligrey/FileSaver.js](https://github.com/eligrey/FileSaver.js) - An HTML5 saveAs() FileSaver implementation
* [chenglou/react-motion](https://github.com/chenglou/react-motion) - A spring that solves your animation problems.
* [pugjs/pug](https://github.com/pugjs/pug) - Pug – robust, elegant, feature rich template engine for Node.js
* [EastWorld/wechat-app-mall](https://github.com/EastWorld/wechat-app-mall) - 微信小程序商城，微信小程序微店
* [MobSF/Mobile-Security-Framework-MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis.
* [git-tips/tips](https://github.com/git-tips/tips) - Most commonly used git tips and tricks.
* [tabler/tabler-icons](https://github.com/tabler/tabler-icons) - A set of over 6100 free MIT-licensed high-quality SVG icons for you to use in your web projects.
* [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - A collection of common interactive command line user interfaces.
* [parse-community/parse-server](https://github.com/parse-community/parse-server) - Parse Server for Node.js / Express
* [liriliri/eruda](https://github.com/liriliri/eruda) - Console for mobile browsers
* [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) - 中华人民共和国行政区划：省级（省份）、 地级（城市）、 县级（区县）、 乡级（乡镇街道）、 村级（村委会居委会） ，中国省市区镇村二级三级四级五级联动地址数据。
* [sveltejs/kit](https://github.com/sveltejs/kit) - web development, streamlined
* [chokcoco/iCSS](https://github.com/chokcoco/iCSS) - 不止于 CSS
* [SortableJS/Vue.Draggable](https://github.com/SortableJS/Vue.Draggable) - Vue drag-and-drop component based on Sortable.js
* [motdotla/dotenv](https://github.com/motdotla/dotenv) - Loads environment variables from .env for nodejs projects.
* [petkaantonov/bluebird](https://github.com/petkaantonov/bluebird) - :bird: :zap: Bluebird is a full featured promise library with unmatched performance.
* [Meituan-Dianping/mpvue](https://github.com/Meituan-Dianping/mpvue) - 基于 Vue.js 的小程序开发框架，从底层支持 Vue.js 语法和构建工具体系。
* [Popmotion/popmotion](https://github.com/Popmotion/popmotion) - Simple animation libraries for delightful user interfaces
* [liyupi/ai-guide](https://github.com/liyupi/ai-guide) - 程序员鱼皮的 AI 资源大全 + Vibe Coding 零基础教程，分享 OpenClaw 保姆级教程、大模型玩法（DeepSeek / GPT / Gemini / Claude / GLM）、最新 AI 资讯、Prompt 提示词大全、AI 知识百科（Agent Skills / RAG / MCP / A2A）、AI 编程教程（Harness Engineering）、AI 工具用法（Cursor / Claude Code / TRAE / Codex / Copilot）、AI 开发框架教程（Spring AI / LangChain）、AI 产品变现指南，帮你快速掌握 AI 技术，走在时代前沿。本项目为开源文档 aiguide，已升级为鱼皮 AI 导航网站
* [dailydotdev/daily](https://github.com/dailydotdev/daily) - daily.dev is the personalized developer news feed and community. Get the best tech content from all over the web in your browser new tab or on mobile. Free and open source.
* [mdx-js/mdx](https://github.com/mdx-js/mdx) - Markdown for the component era
* [segment-boneyard/nightmare](https://github.com/segment-boneyard/nightmare) - A high-level browser automation library.
* [SnapDrop/snapdrop](https://github.com/SnapDrop/snapdrop) - A Progressive Web App for local file sharing
* [nuysoft/Mock](https://github.com/nuysoft/Mock) - A simulation data generator
* [datawhalechina/easy-vibe](https://github.com/datawhalechina/easy-vibe) - 💻 vibe coding 101｜The first course for AI-native product builders.
* [pot-app/pot-desktop](https://github.com/pot-app/pot-desktop) - 🌈一个跨平台的划词翻译和OCR软件 | A cross-platform software for text translation and recognition. *(archived)*
* [facebookexperimental/Recoil](https://github.com/facebookexperimental/Recoil) - Recoil is an experimental state management library for React apps. It provides several capabilities that are difficult to achieve with React alone, while being compatible with the newest features of React. *(archived)*
* [Reactive-Extensions/RxJS](https://github.com/Reactive-Extensions/RxJS) - The Reactive Extensions for JavaScript *(archived)*
* [FredKSchott/snowpack](https://github.com/FredKSchott/snowpack) - ESM-powered frontend build tool. Instant, lightweight, unbundled development. ✌️
* [amark/gun](https://github.com/amark/gun) - An open source cybersecurity protocol for syncing decentralized graph data.
* [vaxilu/x-ui](https://github.com/vaxilu/x-ui) - 支持多协议多用户的 xray 面板
* [browsh-org/browsh](https://github.com/browsh-org/browsh) - A fully-modern text-based browser, rendering to TTY and browsers
* [chaozh/awesome-blockchain-cn](https://github.com/chaozh/awesome-blockchain-cn) - 收集所有区块链(BlockChain)技术开发相关资料，包括Fabric和Ethereum开发资料
* [adam-golab/react-developer-roadmap](https://github.com/adam-golab/react-developer-roadmap) - Roadmap to becoming a React developer
* [bgstaal/multipleWindow3dScene](https://github.com/bgstaal/multipleWindow3dScene) - A quick example of how one can "synchronize" a 3d scene across multiple windows using three.js and localStorage
* [HelloZeroNet/ZeroNet](https://github.com/HelloZeroNet/ZeroNet) - ZeroNet - Decentralized websites using Bitcoin crypto and BitTorrent network
* [framework7io/framework7](https://github.com/framework7io/framework7) - Full featured HTML framework for building iOS & Android apps
* [hemanth/functional-programming-jargon](https://github.com/hemanth/functional-programming-jargon) - Jargon from the functional programming world in simple terms!
* [handlebars-lang/handlebars.js](https://github.com/handlebars-lang/handlebars.js) - Minimal templating on steroids.
* [youzan/vant-weapp](https://github.com/youzan/vant-weapp) - 轻量、可靠的小程序 UI 组件库
* [enyo/dropzone](https://github.com/enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
* [mjmlio/mjml](https://github.com/mjmlio/mjml) - MJML: the only framework that makes responsive email easy
* [pinojs/pino](https://github.com/pinojs/pino) - 🌲 super fast, all natural json logger
* [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - JsonWebToken implementation for node.js http://self-issued.info/docs/draft-ietf-oauth-json-web-token.html
* [lllyasviel/style2paints](https://github.com/lllyasviel/style2paints) - sketch + style = paints :art: (TOG2018/SIGGRAPH2018ASIA)
* [overleaf/overleaf](https://github.com/overleaf/overleaf) - A web-based collaborative LaTeX editor
* [statsd/statsd](https://github.com/statsd/statsd) - Daemon for easy but powerful stats aggregation
* [emotion-js/emotion](https://github.com/emotion-js/emotion) - 👩‍🎤 CSS-in-JS library designed for high performance style composition
* [JacksonTian/fks](https://github.com/JacksonTian/fks) - 前端技能汇总 Frontend Knowledge Structure
* [Foundry376/Mailspring](https://github.com/Foundry376/Mailspring) - :love_letter: A beautiful, fast and fully open source mail client for Mac, Windows and Linux.
* [nosir/cleave.js](https://github.com/nosir/cleave.js) - Format input text content when you are typing...
* [GoogleChrome/chrome-extensions-samples](https://github.com/GoogleChrome/chrome-extensions-samples) - Chrome Extensions Samples
* [nodemailer/nodemailer](https://github.com/nodemailer/nodemailer) - ✉️ Send e-mails with Node.JS – easy as cake!
* [aframevr/aframe](https://github.com/aframevr/aframe) - :a: Web framework for building virtual reality experiences.
* [nfl/react-helmet](https://github.com/nfl/react-helmet) - A document head manager for React
* [facebookarchive/flux](https://github.com/facebookarchive/flux) - Application Architecture for Building User Interfaces *(archived)*
* [leaningtech/webvm](https://github.com/leaningtech/webvm) - Virtual Machine for the Web
* [nondanee/UnblockNeteaseMusic](https://github.com/nondanee/UnblockNeteaseMusic) - Revive unavailable songs for Netease Cloud Music
* [vitejs/awesome-vite](https://github.com/vitejs/awesome-vite) - ⚡️ A curated list of awesome things related to Vite.js
* [less/less.js](https://github.com/less/less.js) - Less. The dynamic stylesheet language.
* [architecture-decision-record/architecture-decision-record](https://github.com/architecture-decision-record/architecture-decision-record) - Architecture decision record (ADR) examples for software planning, IT leadership, and template documentation
* [BoostIO/BoostNote-Legacy](https://github.com/BoostIO/BoostNote-Legacy) - This repository is outdated and new Boost Note app is available! We've launched a new Boost Note app which supports real-time collaborative writing. https://github.com/BoostIO/BoostNote-App *(archived)*
* [hubotio/hubot](https://github.com/hubotio/hubot) - A customizable life embetterment robot.
* [PavelDoGreat/WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) - Play with fluids in your browser (works even on mobile)
* [forwardemail/superagent](https://github.com/forwardemail/superagent) - Ajax for Node.js and browsers (JS HTTP client). Maintained for @forwardemail, @ladjs, @spamscanner, @breejs, @cabinjs, and @lassjs.
* [defunkt/jquery-pjax](https://github.com/defunkt/jquery-pjax) - pushState + ajax = pjax
* [wagerfield/parallax](https://github.com/wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device
* [DIYgod/DPlayer](https://github.com/DIYgod/DPlayer) - :lollipop: Wow, such a lovely HTML5 danmaku video player
* [jamiebuilds/react-loadable](https://github.com/jamiebuilds/react-loadable) - :hourglass_flowing_sand: A higher order component for loading components with promises.
* [ai-shifu/ChatALL](https://github.com/ai-shifu/ChatALL) - Concurrently chat with ChatGPT, Bing Chat, Bard, Alpaca, Vicuna, Claude, ChatGLM, MOSS, 讯飞星火, 文心一言 and more, discover the best answers
* [moment/luxon](https://github.com/moment/luxon) - ⏱ A library for working with dates and times in JS
* [ruanyf/react-demos](https://github.com/ruanyf/react-demos) - a collection of simple demos of React.js
* [twitter/typeahead.js](https://github.com/twitter/typeahead.js) - typeahead.js is a fast and fully-featured autocomplete library
* [OptimalBits/bull](https://github.com/OptimalBits/bull) - Premium Queue package for handling distributed jobs and messages in NodeJS.
* [omnivore-app/omnivore](https://github.com/omnivore-app/omnivore) - Omnivore is a complete, open source read-it-later solution for people who like reading.
* [faressoft/terminalizer](https://github.com/faressoft/terminalizer) - 🦄 Record your terminal and generate animated gif images or share a web player
* [dvajs/dva](https://github.com/dvajs/dva) - 🌱 React and redux based, lightweight and elm-style framework. (Inspired by elm and choo)
* [zhaoolee/ChineseBQB](https://github.com/zhaoolee/ChineseBQB) - 🇨🇳 Chinese sticker pack,More joy / 表情包的博物馆, Github最有毒的仓库, 中国表情包大集合, 聚欢乐~
* [JoeanAmier/TikTokDownloader](https://github.com/JoeanAmier/TikTokDownloader) - 抖音 / TikTok 平台作品下载/数据采集工具
* [yonggekkk/Cloudflare-vless-trojan](https://github.com/yonggekkk/Cloudflare-vless-trojan) - CF-workers/pages代理脚本：支持Vless-ws(tls)、Trojan-ws(tls)；Socks5/http本地代理脚本：可选ECH-TLS、普通TLS、无TLS三种代理模式
* [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) - The fastest browser for AI agents to run browser automation, built for sharing your logged-in browser state with your AI agents, like Codex or Claude Code, without disturbing you. Zero cost, zero config.
* [remarkjs/react-markdown](https://github.com/remarkjs/react-markdown) - Markdown component for React
* [yaronn/blessed-contrib](https://github.com/yaronn/blessed-contrib) - Build terminal dashboards using ascii/ansi art and javascript
* [iissnan/hexo-theme-next](https://github.com/iissnan/hexo-theme-next) - Elegant theme for Hexo.
* [kleampa/not-paid](https://github.com/kleampa/not-paid) - Client did not pay? Add opacity to the body tag and decrease it every day until their site completely fades away
* [avwo/whistle](https://github.com/avwo/whistle) - HTTP, HTTP2, HTTPS, Websocket debugging proxy
* [menzi11/BullshitGenerator](https://github.com/menzi11/BullshitGenerator) - Needs to generate some texts to test if my GUI rendering codes good or not. so I made this.
* [exceljs/exceljs](https://github.com/exceljs/exceljs) - Excel Workbook Manager
* [auchenberg/volkswagen](https://github.com/auchenberg/volkswagen) - :see_no_evil: Volkswagen detects when your tests are being run in a CI server, and makes them pass.
* [jsdoc/jsdoc](https://github.com/jsdoc/jsdoc) - An API documentation generator for JavaScript.
* [SimulatedGREG/electron-vue](https://github.com/SimulatedGREG/electron-vue) - An Electron & Vue.js quick start boilerplate with vue-cli scaffolding, common Vue plugins, electron-packager/electron-builder, unit/e2e testing, vue-devtools, and webpack. *(archived)*
* [checkly/headless-recorder](https://github.com/checkly/headless-recorder) - Chrome extension that records your browser interactions and generates a Playwright or Puppeteer script. *(archived)*
* [zotero/zotero](https://github.com/zotero/zotero) - Zotero is a free, easy-to-use tool to help you collect, organize, annotate, cite, and share your research sources.
* [designmodo/Flat-UI](https://github.com/designmodo/Flat-UI) - Flat UI Free - Design Framework (html/css3/less/js). Flat UI is based on Bootstrap, a comfortable, responsive, and functional framework that simplifies the development of websites.
* [librespeed/speedtest](https://github.com/librespeed/speedtest) - Self-hosted Speed Test for HTML5 and more. Easy setup, examples, configurable, mobile friendly. Supports PHP, Node, Multiple servers, and more
* [electerm/electerm](https://github.com/electerm/electerm) - 📻Free and open-sourced terminal/ssh/sftp/ftp/telnet/serialport/RDP/VNC/Spice client(Linux, Mac, Windows, Android, HarmonyOS, iOS)
* [kriskowal/q](https://github.com/kriskowal/q) - A promise library for JavaScript *(archived)*
* [ampproject/amphtml](https://github.com/ampproject/amphtml) - The AMP web component framework.
* [xcanwin/KeepChatGPT](https://github.com/xcanwin/KeepChatGPT) - 这是一款提高ChatGPT的数据安全能力和效率的插件。并且免费共享大量创新功能，如：自动刷新、保持活跃、数据安全、取消审计、克隆对话、言无不尽、净化页面、展示大屏、拦截跟踪、日新月异、明察秋毫等。让我们的AI体验无比安全、顺畅、丝滑、高效、简洁。
* [hapijs/hapi](https://github.com/hapijs/hapi) - The Simple, Secure Framework Developers Trust
* [acdlite/recompose](https://github.com/acdlite/recompose) - A React utility belt for function components and higher-order components. *(archived)*
* [thomaspark/bootswatch](https://github.com/thomaspark/bootswatch) - Themes for Bootstrap
* [lint-staged/lint-staged](https://github.com/lint-staged/lint-staged) - 🚫💩 — Run tasks like formatters and linters against staged git files
* [Fei-Away/Codex-Dream-Skin](https://github.com/Fei-Away/Codex-Dream-Skin) - Codex Dream Skin
* [graphql/graphql-spec](https://github.com/graphql/graphql-spec) - GraphQL is a query language and execution engine tied to any backend service.
* [bootstrap-vue/bootstrap-vue](https://github.com/bootstrap-vue/bootstrap-vue) - MOVED to https://github.com/bootstrap-vue-next/bootstrap-vue-next
* [forwardemail/supertest](https://github.com/forwardemail/supertest) - 🕷 Super-agent driven library for testing node.js HTTP servers using a fluent API. Maintained for @forwardemail, @ladjs, @spamscanner, @breejs, @cabinjs, and @lassjs.
* [advplyr/audiobookshelf](https://github.com/advplyr/audiobookshelf) - Self-hosted audiobook and podcast server
* [hackerkid/Mind-Expanding-Books](https://github.com/hackerkid/Mind-Expanding-Books) - :books: Find your next book to read!
* [http-party/http-server](https://github.com/http-party/http-server) - A simple, zero-configuration, command-line http server
* [maillab/cloud-mail](https://github.com/maillab/cloud-mail) - A Cloudflare-based email service | 基于 Cloudflare 的邮箱服务 | Cloudflare Email 邮箱 Mail
* [angular-ui/bootstrap](https://github.com/angular-ui/bootstrap) - PLEASE READ THE PROJECT STATUS BELOW. Native AngularJS (Angular) directives for Bootstrap. Smaller footprint (20kB gzipped), no 3rd party JS dependencies (jQuery, bootstrap JS) required. Please read the README.md file before submitting an issue! *(archived)*
* [unbug/codelf](https://github.com/unbug/codelf) - A search tool helps dev to solve the naming things problem.
* [http-party/node-http-proxy](https://github.com/http-party/node-http-proxy) - A full-featured http proxy for node.js
* [andrewyng/context-hub](https://github.com/andrewyng/context-hub)
* [automatisch/automatisch](https://github.com/automatisch/automatisch) - The open source Zapier alternative. Build workflow automation without spending time and money.
* [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) - A CLI dashboard for webpack dev server
* [openstf/stf](https://github.com/openstf/stf) - Control and manage Android devices from your browser.
* [Stremio/stremio-web](https://github.com/Stremio/stremio-web) - Stremio - Freedom to Stream
* [LibreSpark/LibreTV](https://github.com/LibreSpark/LibreTV) - 一分钟搭建影视站，支持Docker等部署方式
* [fbsamples/f8app](https://github.com/fbsamples/f8app) - Source code of the official F8 app of 2017, powered by React Native and other Facebook open source projects. *(archived)*
* [rabbitmq/rabbitmq-server](https://github.com/rabbitmq/rabbitmq-server) - Open source RabbitMQ: core server and tier 1 (built-in) plugins
* [zhongyi-tong/electronic-wechat](https://github.com/zhongyi-tong/electronic-wechat) - :speech_balloon: A better WeChat on macOS and Linux. Built with Electron by Zhongyi Tong. *(archived)*
* [foreversd/forever](https://github.com/foreversd/forever) - A simple CLI tool for ensuring that a given script runs continuously (i.e. forever)
* [shipshapecode/shepherd](https://github.com/shipshapecode/shepherd) - Guide your users through a tour of your app
* [Anarios/return-youtube-dislike](https://github.com/Anarios/return-youtube-dislike) - Chrome extension to return youtube dislikes
* [egonSchiele/grokking_algorithms](https://github.com/egonSchiele/grokking_algorithms) - Code for the book Grokking Algorithms (https://www.amazon.com/dp/1633438538)
* [pomber/git-history](https://github.com/pomber/git-history) - Quickly browse the history of a file from any git repository
* [divamgupta/diffusionbee-stable-diffusion-ui](https://github.com/divamgupta/diffusionbee-stable-diffusion-ui) - Diffusion Bee is the easiest way to run Stable Diffusion locally on your M1 Mac. Comes with a one-click installer. No dependencies or technical knowledge needed.
* [krasimir/react-in-patterns](https://github.com/krasimir/react-in-patterns) - A free book that talks about design patterns/techniques used while developing with React.
* [browserslist/browserslist](https://github.com/browserslist/browserslist) - 🦔 Share target browsers between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env
* [RaspberryPiFoundation/blockly](https://github.com/RaspberryPiFoundation/blockly) - The web-based visual programming editor.
* [zalmoxisus/redux-devtools-extension](https://github.com/zalmoxisus/redux-devtools-extension) - Redux DevTools extension.
* [mailcow/mailcow-dockerized](https://github.com/mailcow/mailcow-dockerized) - mailcow: dockerized - 🐮 + 🐋 = 💕
* [rwaldron/johnny-five](https://github.com/rwaldron/johnny-five) - JavaScript Robotics and IoT programming framework, developed at Bocoup.
* [graphql/dataloader](https://github.com/graphql/dataloader) - DataLoader is a generic utility to be used as part of your application's data fetching layer to provide a consistent API over various backends and reduce requests to those backends via batching and caching.
* [microsoft/playwright-cli](https://github.com/microsoft/playwright-cli) - CLI for common Playwright actions. Record and generate Playwright code, inspect selectors and take screenshots.
* [you-dont-need/You-Dont-Need-Momentjs](https://github.com/you-dont-need/You-Dont-Need-Momentjs) - List of functions which you can use to replace moment.js + ESLint Plugin
* [brianc/node-postgres](https://github.com/brianc/node-postgres) - PostgreSQL client for node.js.
* [Semantic-Org/Semantic-UI-React](https://github.com/Semantic-Org/Semantic-UI-React) - The official Semantic-UI-React integration
* [Flipboard/react-canvas](https://github.com/Flipboard/react-canvas) - High performance <canvas> rendering for React components
* [mozilla-firefox/firefox](https://github.com/mozilla-firefox/firefox) - The official repository of Mozilla's Firefox web browser.
* [strongloop/loopback](https://github.com/strongloop/loopback) - LoopBack makes it easy to build modern applications that require complex integrations.
* [nasa/openmct](https://github.com/nasa/openmct) - A web based mission control framework.
* [systemjs/systemjs](https://github.com/systemjs/systemjs) - Dynamic ES module loader
* [angular/angular-seed](https://github.com/angular/angular-seed) - Seed project for angular apps. *(archived)*
* [hiteshchoudhary/chai-aur-react](https://github.com/hiteshchoudhary/chai-aur-react) - chai aur react series on youtube
* [PrismJS/prism](https://github.com/PrismJS/prism) - Lightweight, robust, elegant syntax highlighting.
* [projectdiscovery/nuclei-templates](https://github.com/projectdiscovery/nuclei-templates) - Community curated list of templates for the nuclei engine to find security vulnerabilities.
* [arkenfox/user.js](https://github.com/arkenfox/user.js) - Firefox privacy, security and anti-tracking: a comprehensive user.js template for configuration and hardening
* [cubiq/iscroll](https://github.com/cubiq/iscroll) - Smooth scrolling for the web *(archived)*
* [be5invis/Sarasa-Gothic](https://github.com/be5invis/Sarasa-Gothic) - Sarasa Gothic / 更纱黑体 / 更紗黑體 / 更紗ゴシック / 사라사 고딕
* [surmon-china/vue-awesome-swiper](https://github.com/surmon-china/vue-awesome-swiper) - 🏆 Swiper component for @vuejs *(archived)*
* [catdad/canvas-confetti](https://github.com/catdad/canvas-confetti) - 🎉 performant confetti animation in the browser
* [JoeanAmier/XHS-Downloader](https://github.com/JoeanAmier/XHS-Downloader) - 小红书（XiaoHongShu、RedNote）链接提取/作品采集工具
* [wanglin2/mind-map](https://github.com/wanglin2/mind-map) - SimpleMindMap（思绪思维导图）：一个强大的思维导图。A powerful mind map.
* [Piebald-AI/claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) - All parts of Claude Code's system prompt, 27 builtin tool descriptions, sub agent prompts (Plan/Explore/Task), utility prompts (CLAUDE.md, compact, statusline, magic docs, WebFetch, Bash cmd, security review, agent creation). Updated for each Claude Code version.
* [answershuto/learnVue](https://github.com/answershuto/learnVue) - :octocat:Vue.js 源码解析
* [webpack/webpack-bundle-analyzer](https://github.com/webpack/webpack-bundle-analyzer) - Webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap
* [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) - Node.js debugger based on Blink Developer Tools
* [d2-projects/d2-admin](https://github.com/d2-projects/d2-admin) - An elegant dashboard
* [Wei-Shaw/claude-relay-service](https://github.com/Wei-Shaw/claude-relay-service) - CRS-自建Claude Code镜像，一站式开源中转服务，让 Claude、OpenAI、Gemini、Droid 订阅统一接入，支持拼车共享，更高效分摊成本，原生工具无缝使用。
* [fishjar/kiss-translator](https://github.com/fishjar/kiss-translator) - A simple, open source bilingual translation extension & Greasemonkey script (一个简约、开源的 双语对照翻译扩展 & 油猴脚本)
* [welldone-software/why-did-you-render](https://github.com/welldone-software/why-did-you-render) - why-did-you-render by Welldone Software monkey patches React to notify you about potentially avoidable re-renders. (Works with React Native as well.)
* [amfe/lib-flexible](https://github.com/amfe/lib-flexible) - 可伸缩布局方案
* [redux-form/redux-form](https://github.com/redux-form/redux-form) - A Higher Order Component using react-redux to keep form state in a Redux store
* [segmentio/evergreen](https://github.com/segmentio/evergreen) - 🌲 Evergreen React UI Framework by Segment
* [bailicangdu/node-elm](https://github.com/bailicangdu/node-elm) - Backend system based on node.js + Mongodb. 基于 node.js + Mongodb 构建的后台系统
* [casesandberg/react-color](https://github.com/casesandberg/react-color) - :art: Color Pickers from Sketch, Photoshop, Chrome, Github, Twitter & more
* [downshift-js/downshift](https://github.com/downshift-js/downshift) - 🏎 A set of primitives to build simple, flexible, WAI-ARIA compliant React autocomplete, combobox or select dropdown components.
* [BrowserSync/browser-sync](https://github.com/BrowserSync/browser-sync) - Keep multiple browsers & devices in sync when building websites. https://browsersync.io
* [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) - A web-based tool to view, edit, format, and validate JSON
* [atomiks/tippyjs](https://github.com/atomiks/tippyjs) - Tooltip, popover, dropdown, and menu library *(archived)*
* [firebase/functions-samples](https://github.com/firebase/functions-samples) - Collection of sample apps showcasing popular use cases using Cloud Functions for Firebase
* [react-dates/react-dates](https://github.com/react-dates/react-dates) - An easily internationalizable, mobile-friendly datepicker library for the web
* [marcotcr/lime](https://github.com/marcotcr/lime) - Lime: Explaining the predictions of any machine learning classifier
* [gaearon/react-hot-loader](https://github.com/gaearon/react-hot-loader) - Tweak React components in real time. (Deprecated: use Fast Refresh instead.)
* [spencermountain/compromise](https://github.com/spencermountain/compromise) - modest natural-language processing
* [lockfale/OSINT-Framework](https://github.com/lockfale/OSINT-Framework) - OSINT Framework
* [docker-archive-public/docker.kitematic](https://github.com/docker-archive-public/docker.kitematic) - Visual Docker Container Management on Mac & Windows *(archived)*
* [listen1/listen1_chrome_extension](https://github.com/listen1/listen1_chrome_extension) - one for all free music in china (chrome extension, also works for firefox)
* [expressjs/multer](https://github.com/expressjs/multer) - Node.js middleware for handling `multipart/form-data`.
* [erikras/react-redux-universal-hot-example](https://github.com/erikras/react-redux-universal-hot-example) - A starter boilerplate for a universal webapp using express, react, redux, webpack, and react-transform
* [muaz-khan/WebRTC-Experiment](https://github.com/muaz-khan/WebRTC-Experiment) - WebRTC, WebRTC and WebRTC. Everything here is all about WebRTC!!
* [Semporia/TikTok-Unlock](https://github.com/Semporia/TikTok-Unlock) - TikTok 無需拔卡解鎖最新支援 iPhone &iPad 、TikTok&TikTok TestFlight，地區切換 、視頻發佈 、 live 直播 、點贊 評論、私信聊天等！
* [vega/vega](https://github.com/vega/vega) - A visualization grammar.
* [akiran/react-slick](https://github.com/akiran/react-slick) - React carousel component
* [CodeWithHarry/Sigma-Web-Dev-Course](https://github.com/CodeWithHarry/Sigma-Web-Dev-Course) - Source Code for Sigma Web Development Course
* [jason5ng32/MyIP](https://github.com/jason5ng32/MyIP) - The best IP Toolbox. Check your IP address & geolocation, test IP for WebRTC and DNS IP leaks, run an IP quality check, browser fingerprint check, website availability check, network speed test, global latency test, MTR test, Whois search, and more.
* [chjj/blessed](https://github.com/chjj/blessed) - A high-level terminal interface library for node.js.
* [NetEase/pomelo](https://github.com/NetEase/pomelo) - A fast,scalable,distributed game server framework for Node.js. *(archived)*
* [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) - A curated list of CTF frameworks, libraries, resources and softwares
* [viarotel-org/escrcpy](https://github.com/viarotel-org/escrcpy) - 📱 Display and control your Android device graphically with scrcpy.
* [notionnext-org/NotionNext](https://github.com/notionnext-org/NotionNext) - Turn your Notion workspace into a fast, customizable website. Built with Next.js + Notion API, with multi-platform deployment and no self-hosted server required.
* [Matt-Esch/virtual-dom](https://github.com/Matt-Esch/virtual-dom) - A Virtual DOM and diffing algorithm
* [tj/co](https://github.com/tj/co) - The ultimate generator based flow-control goodness for nodejs (supports thunks, promises, etc)
* [fmhy/edit](https://github.com/fmhy/edit) - Make changes to FMHY
* [phobal/ivideo](https://github.com/phobal/ivideo) - 一个可以观看国内主流视频平台所有视频的客户端（Mac、Windows、Linux） A client that can watch video of domestic(China) mainstream video platform *(archived)*
* [wenzhixin/bootstrap-table](https://github.com/wenzhixin/bootstrap-table) - An extended table for integration with some of the most widely used CSS frameworks. (Supports Bootstrap, Semantic UI, Bulma, Material Design, Foundation, Vue.js)
* [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) - Create PDF documents using web technologies
* [Nozbe/WatermelonDB](https://github.com/Nozbe/WatermelonDB) - 🍉 Reactive & asynchronous database for powerful React and React Native apps ⚡️
* [WordPress/gutenberg](https://github.com/WordPress/gutenberg) - The Block Editor project for WordPress and beyond. Plugin is available from the official repository.
* [1995parham/github-do-not-ban-us](https://github.com/1995parham/github-do-not-ban-us) - GitHub do not ban us from open source world :iran: *(archived)*
* [luin/medis](https://github.com/luin/medis) - 💻 Medis is a beautiful, easy-to-use Mac database management application for Redis.
* [calesthio/Crucix](https://github.com/calesthio/Crucix) - Your personal intelligence agent. Watches the world from multiple data sources and pings you when something changes.
* [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream) - Connect APIs, remarkably fast. Free for developers.
* [stackryze/FreeDomains](https://github.com/stackryze/FreeDomains) - Stackryze Domains: Free Domain for Everyone, Claim yours today.
* [leanote/leanote](https://github.com/leanote/leanote) - Not Just A Notepad! (golang + mongodb) http://leanote.org
* [horsicq/Detect-It-Easy](https://github.com/horsicq/Detect-It-Easy) - Program for determining types of files for Windows, Linux and MacOS.
* [stylelint/stylelint](https://github.com/stylelint/stylelint) - A mighty CSS linter that helps you avoid errors and enforce conventions.
* [serverless/examples](https://github.com/serverless/examples) - Serverless Examples – A collection of boilerplates and examples of serverless architectures built with the Serverless Framework on AWS Lambda, Microsoft Azure, Google Cloud Functions, and more.
* [yargs/yargs](https://github.com/yargs/yargs) - yargs the modern, pirate-themed successor to optimist.
* [jxnblk/mdx-deck](https://github.com/jxnblk/mdx-deck) - ♠️ React MDX-based presentation decks
* [debug-js/debug](https://github.com/debug-js/debug) - A tiny JavaScript debugging utility modelled after Node.js core's debugging technique. Works in Node.js and web browsers
* [electron/minimal-repro](https://github.com/electron/minimal-repro) - Clone to try a simple Electron app
* [mozilla/readability](https://github.com/mozilla/readability) - A standalone version of the readability lib
* [schlagmichdoch/PairDrop](https://github.com/schlagmichdoch/PairDrop) - PairDrop: Transfer Files Cross-Platform. No Setup, No Signup.
* [listen1/listen1_desktop](https://github.com/listen1/listen1_desktop) - one for all free music in china (Windows, Mac, Linux desktop)
* [wangrongding/wechat-bot](https://github.com/wangrongding/wechat-bot) - 🤖 Multi-platform IM AI Agent for Telegram, WhatsApp, Lark, and WeChat. Connects ChatGPT / Claude / Kimi / DeepSeek / Ollama / Pi for auto-replies, community analysis, contact management, and inactive-friend detection.
* [pixeltris/TwitchAdSolutions](https://github.com/pixeltris/TwitchAdSolutions) - *(archived)*
* [qist/tvbox](https://github.com/qist/tvbox) - OK影视、tvbox配置文件，如果喜欢，请Fork自用。使用前请仔细阅读仓库说明，一旦使用将被视为你已了解。
* [stylus/stylus](https://github.com/stylus/stylus) - Expressive, robust, feature-rich CSS language built for nodejs
* [is-a-dev/register](https://github.com/is-a-dev/register) - Grab your own sweet-looking '.is-a.dev' subdomain.
* [dimsemenov/Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance.
* [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) - ⚡️Faster subsequent page-loads by prefetching in-viewport links during idle time
* [akveo/blur-admin](https://github.com/akveo/blur-admin) - AngularJS Bootstrap Admin Panel Framework
* [jojoldu/junior-recruit-scheduler](https://github.com/jojoldu/junior-recruit-scheduler) - 주니어 개발자 채용 정보
* [xiandanin/magnetW](https://github.com/xiandanin/magnetW) - [已失效，不再维护] *(archived)*
* [Hackl0us/SS-Rule-Snippet](https://github.com/Hackl0us/SS-Rule-Snippet) - 搜集、整理、维护 Surge / Quantumult (X) / Shadowrocket / Surfboard / clash (Premium) 实用规则。
* [scottjehl/Respond](https://github.com/scottjehl/Respond) - A fast & lightweight polyfill for min/max-width CSS3 Media Queries (for IE 6-8, and more) *(archived)*
* [kautukkundan/Awesome-Profile-README-templates](https://github.com/kautukkundan/Awesome-Profile-README-templates) - A collection of awesome readme templates to display on your profile
* [ptmt/react-native-macos](https://github.com/ptmt/react-native-macos) - [deprecated in favor of https://microsoft.github.io/react-native-windows/] React Native for macOS is an experimental fork for writing desktop apps using Cocoa
* [BrasilAPI/BrasilAPI](https://github.com/BrasilAPI/BrasilAPI) - Vamos transformar o Brasil em uma API?
* [apachecn/apachecn-algo-zh](https://github.com/apachecn/apachecn-algo-zh) - ApacheCN 数据结构与算法译文集
* [kefranabg/readme-md-generator](https://github.com/kefranabg/readme-md-generator) - 📄 CLI that generates beautiful README.md files
* [Kristories/awesome-guidelines](https://github.com/Kristories/awesome-guidelines) - Programming style, best practices, and coding conventions.
* [thedevs-network/kutt](https://github.com/thedevs-network/kutt) - Free Modern URL Shortener.
* [openspug/spug](https://github.com/openspug/spug) - Spug is a lightweight agent-free automatic operation and maintenance platform designed for small and medium-sized enterprises. It integrates host management, host batch execution, host online terminal, file management, application release and deployment, pipelines, online task planning, configuration center, monitoring, alarm and so on.
* [oldboyxx/jira_clone](https://github.com/oldboyxx/jira_clone) - A simplified Jira clone built with React/Babel (Client), and Node/TypeScript (API). Auto formatted with Prettier, tested with Cypress.
* [beefproject/beef](https://github.com/beefproject/beef) - The Browser Exploitation Framework Project
* [haltu/muuri](https://github.com/haltu/muuri) - Infinite responsive, sortable, filterable and draggable layouts
* [r-spacex/SpaceX-API](https://github.com/r-spacex/SpaceX-API) - :rocket: Open Source REST API for SpaceX launch, rocket, core, capsule, starlink, launchpad, and landing pad data. *(archived)*
* [1c7/Crash-Course-Computer-Science-Chinese](https://github.com/1c7/Crash-Course-Computer-Science-Chinese) - 计算机速成课（播放量 509 万） （共40集，每一集 10 分钟）2018 年完成翻译。评论区有大量好评
* [Shopify/dashing](https://github.com/Shopify/dashing) - The exceptionally handsome dashboard framework in Ruby and Coffeescript. *(archived)*
* [NaturalNode/natural](https://github.com/NaturalNode/natural) - general natural language facilities for node
* [GoogleChromeLabs/ndb](https://github.com/GoogleChromeLabs/ndb) - ndb is an improved debugging experience for Node.js, enabled by Chrome DevTools *(archived)*
* [yokoffing/Betterfox](https://github.com/yokoffing/Betterfox) - Firefox user.js for optimal privacy and security. Your favorite browser, but better.
* [vuejs/vue-hackernews-2.0](https://github.com/vuejs/vue-hackernews-2.0) - HackerNews clone built with Vue 2.0, vue-router & vuex, with server-side rendering
* [WickyNilliams/headroom.js](https://github.com/WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it
* [OffcierCia/DeFi-Developer-Road-Map](https://github.com/OffcierCia/DeFi-Developer-Road-Map) - DeFi Developer roadmap is a curated Developer handbook which includes a list of the best tools for DApps development, resources and references!
* [withspectrum/spectrum](https://github.com/withspectrum/spectrum) - Simple, powerful online communities. *(archived)*
* [ChatGPTBox-dev/chatGPTBox](https://github.com/ChatGPTBox-dev/chatGPTBox) - Integrating ChatGPT into your browser deeply, everything you need is here
* [ryanburgess/engineer-manager](https://github.com/ryanburgess/engineer-manager) - A list of engineering manager resource links.
* [XxHuberrr/Mineradio](https://github.com/XxHuberrr/Mineradio) - 一款以电影镜头、粒子视觉和歌词舞台为核心的沉浸式音乐播放器。
* [jantimon/html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) - Simplifies creation of HTML files to serve your webpack bundles
* [Automattic/node-canvas](https://github.com/Automattic/node-canvas) - Node canvas is a Cairo backed Canvas implementation for NodeJS.
* [restify/node-restify](https://github.com/restify/node-restify) - The future of Node.js REST development
* [metafizzy/zdog](https://github.com/metafizzy/zdog) - Flat, round, designer-friendly pseudo-3D engine for canvas & SVG
* [xinnan-tech/xiaozhi-esp32-server](https://github.com/xinnan-tech/xiaozhi-esp32-server) - 本项目为xiaozhi-esp32提供后端服务，帮助您快速搭建ESP32设备控制服务器。Backend service for xiaozhi-esp32, helps you quickly build an ESP32 device control server.
* [kesenhoo/android-training-course-in-chinese](https://github.com/kesenhoo/android-training-course-in-chinese) - Android官方培训课程中文版
* [tariqbuilds/linux-dash](https://github.com/tariqbuilds/linux-dash) - A beautiful web dashboard for Linux
* [bailicangdu/vue2-happyfri](https://github.com/bailicangdu/vue2-happyfri) - vue2 + vue-router + vuex 入门项目
* [meliorence/react-native-snap-carousel](https://github.com/meliorence/react-native-snap-carousel) - Swiper/carousel component for React Native featuring previews, multiple layouts, parallax images, performant handling of huge numbers of items, and more. Compatible with Android & iOS.
* [leeoniya/uPlot](https://github.com/leeoniya/uPlot) - 📈 A small, fast chart for time series, lines, areas, ohlc & bars
* [sub-store-org/Sub-Store](https://github.com/sub-store-org/Sub-Store) - Advanced Subscription Manager for QX, Loon, Surge, Stash, Egern and Shadowrocket!
* [leecade/react-native-swiper](https://github.com/leecade/react-native-swiper) - The best Swiper component for React Native.
* [easydiffusion/easydiffusion](https://github.com/easydiffusion/easydiffusion) - An easy 1-click way to create beautiful artwork on your PC using AI, with no tech knowledge. Provides a browser UI for generating images from text prompts and images. Just enter your text prompt, and see the generated image.
* [jhen0409/react-native-debugger](https://github.com/jhen0409/react-native-debugger) - The standalone app based on official debugger of React Native, and includes React Inspector / Redux DevTools
* [gskinner/regexr](https://github.com/gskinner/regexr) - RegExr is a HTML/JS based tool for creating, testing, and learning about Regular Expressions.
* [ziahamza/webui-aria2](https://github.com/ziahamza/webui-aria2) - The aim for this project is to create the worlds best and hottest interface to interact with aria2. Very simple to use, just download and open index.html in any web browser.
* [react-static/react-static](https://github.com/react-static/react-static) - ⚛️ 🚀 A progressive static site generator for React.
* [hackjutsu/Lepton](https://github.com/hackjutsu/Lepton) - 💻 Democratizing Snippet Management (macOS/Win/Linux)
* [facebook/stylex](https://github.com/facebook/stylex) - StyleX is the styling system for ambitious user interfaces.
* [imakewebthings/waypoints](https://github.com/imakewebthings/waypoints) - Waypoints is a library that makes it easy to execute a function whenever you scroll to an element.
* [addyosmani/critical](https://github.com/addyosmani/critical) - Extract & Inline Critical-path CSS in HTML pages
* [awesome-opencode/awesome-opencode](https://github.com/awesome-opencode/awesome-opencode) - A curated list of awesome plugins, themes, agents, projects, and resources for https://opencode.ai
* [fantasyland/fantasy-land](https://github.com/fantasyland/fantasy-land) - Specification for interoperability of common algebraic structures in JavaScript
* [dvdzkwsk/react-redux-starter-kit](https://github.com/dvdzkwsk/react-redux-starter-kit) - Get started with React, Redux, and React-Router. *(archived)*
* [reactjs/react-transition-group](https://github.com/reactjs/react-transition-group) - An easy way to perform animations when a React component enters or leaves the DOM
* [PatrickJS/angular-webpack-starter](https://github.com/PatrickJS/angular-webpack-starter) - Angular Webpack Starter
* [askmike/gekko](https://github.com/askmike/gekko) - A bitcoin trading bot written in node - https://gekko.wizb.it/ *(archived)*
* [cmiscm/leonsans](https://github.com/cmiscm/leonsans) - Leon Sans is a geometric sans-serif typeface made with code in 2019 by Jongmin Kim.
* [pahen/madge](https://github.com/pahen/madge) - Create graphs from your CommonJS, AMD or ES6 module dependencies
* [dontbesilent2025/dbskill](https://github.com/dontbesilent2025/dbskill) - dontbesilent 的商业诊断 Skills
* [hackmdio/codimd](https://github.com/hackmdio/codimd) - CodiMD - Realtime collaborative markdown notes on all platforms.
* [qrohlf/trianglify](https://github.com/qrohlf/trianglify) - Algorithmically generated triangle art
* [astrit/css.gg](https://github.com/astrit/css.gg) - 700+ Pure CSS, SVG & Figma UI Icons, 6000+ glyphs, patterns, colors and layouts.
* [i18next/react-i18next](https://github.com/i18next/react-i18next) - Internationalization for react done right. Using the i18next i18n ecosystem.
* [XIU2/UserScript](https://github.com/XIU2/UserScript) - 🐵 自用的一些乱七八糟 油猴脚本~
* [petehunt/webpack-howto](https://github.com/petehunt/webpack-howto)
* [typicode/hotel](https://github.com/typicode/hotel) - 🏩 A simple process manager for developers. Start apps from your browser and access them using local domains
* [oblador/react-native-animatable](https://github.com/oblador/react-native-animatable) - Standard set of easy to use animations and declarative transitions for React Native
* [aksakalli/gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for terminal
* [DevExpress/testcafe](https://github.com/DevExpress/testcafe) - A Node.js tool to automate end-to-end web testing.
* [mattdelacdev/WOW](https://github.com/mattdelacdev/WOW) - Reveal CSS animation as you scroll down a page
* [max-mapper/art-of-node](https://github.com/max-mapper/art-of-node) - :snowflake: a short introduction to node.js
* [pmndrs/drei](https://github.com/pmndrs/drei) - 🥉 useful helpers for react-three-fiber
* [aFarkas/html5shiv](https://github.com/aFarkas/html5shiv) - This script is the defacto way to enable use of HTML5 sectioning elements in legacy Internet Explorer.
* [purifycss/purifycss](https://github.com/purifycss/purifycss) - Remove unused CSS. Also works with single-page apps.
* [lukeed/clsx](https://github.com/lukeed/clsx) - A tiny (239B) utility for constructing `className` strings conditionally.
* [timarney/react-app-rewired](https://github.com/timarney/react-app-rewired) - Override create-react-app webpack configs without ejecting
* [vercel/ncc](https://github.com/vercel/ncc) - Compile a Node.js project into a single file. Supports TypeScript, binary addons, dynamic requires.
* [streamaserver/streama](https://github.com/streamaserver/streama) - Self hosted streaming media server. https://docs.streama-project.com/
* [upgundecha/howtheysre](https://github.com/upgundecha/howtheysre) - A curated collection of publicly available resources on how technology and tech-savvy organizations around the world practice Site Reliability Engineering (SRE)
* [sdelements/lets-chat](https://github.com/sdelements/lets-chat) - Self-hosted chat app for small teams *(archived)*
* [scottjehl/picturefill](https://github.com/scottjehl/picturefill) - A responsive image polyfill for <picture>, srcset, sizes, and more *(archived)*
* [hiteshchoudhary/apihub](https://github.com/hiteshchoudhary/apihub) - Your own API Hub to learn and master API interaction. Ideal for frontend, mobile dev and backend developers.
* [sindresorhus/ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner
* [microsoft/Windows-universal-samples](https://github.com/microsoft/Windows-universal-samples) - API samples for the Universal Windows Platform.
* [Hypfer/Valetudo](https://github.com/Hypfer/Valetudo) - Cloud replacement for vacuum robots enabling local-only operation
* [anvaka/city-roads](https://github.com/anvaka/city-roads) - Visualization of all roads within any city
* [apidoc/apidoc](https://github.com/apidoc/apidoc) - RESTful web API Documentation Generator. *(archived)*
* [coryhouse/react-slingshot](https://github.com/coryhouse/react-slingshot) - React + Redux starter kit / boilerplate with Babel, hot reloading, testing, linting and a working example app built in
* [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) - A full-featured Webpack + vue-loader setup with hot reload, linting, testing & css extraction.
* [VGraupera/1on1-questions](https://github.com/VGraupera/1on1-questions) - Mega list of 1 on 1 meeting questions compiled from a variety to sources
* [jquery-archive/jquery-mobile](https://github.com/jquery-archive/jquery-mobile) - jQuery Mobile Framework *(archived)*
* [ruanyf/webpack-demos](https://github.com/ruanyf/webpack-demos) - a collection of simple demos of Webpack
* [erikras/ducks-modular-redux](https://github.com/erikras/ducks-modular-redux) - A proposal for bundling reducers, action types and actions when using Redux
* [open-gsd/gsd-core](https://github.com/open-gsd/gsd-core) - Git. Ship. Done - Core
* [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) - React UI Components for macOS High Sierra and Windows 10
* [marcelscruz/public-apis](https://github.com/marcelscruz/public-apis) - A collaborative list of public APIs for developers
* [mobz/elasticsearch-head](https://github.com/mobz/elasticsearch-head) - A web front end for an elastic search cluster
* [peachananr/onepage-scroll](https://github.com/peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin
* [eduardolundgren/tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web
* [swagger-api/swagger-editor](https://github.com/swagger-api/swagger-editor) - Swagger Editor
* [Automattic/kue](https://github.com/Automattic/kue) - Kue is a priority job queue backed by redis, built for node.js.
* [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) - CORS Anywhere is a NodeJS reverse proxy which adds CORS headers to the proxied request.
* [c3js/c3](https://github.com/c3js/c3) - :bar_chart: A D3-based reusable chart library
* [klaudiosinani/taskbook](https://github.com/klaudiosinani/taskbook) - Tasks, boards & notes for the command-line habitat
* [WebGoat/WebGoat](https://github.com/WebGoat/WebGoat) - WebGoat is a deliberately insecure application
* [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) - Generate polished résumés and CVs in HTML, Markdown, LaTeX, MS Word, PDF, plain text, JSON, XML, YAML, smoke signal, and carrier pigeon.
* [terkelg/prompts](https://github.com/terkelg/prompts) - ❯ Lightweight, beautiful and user-friendly interactive prompts
* [oso95/scroll-world](https://github.com/oso95/scroll-world) - A skill that turn any brand into a scrollable 3D world landing page
* [dessant/buster](https://github.com/dessant/buster) - Captcha solver extension for humans, available for Chrome, Edge and Firefox
* [bytedance/xgplayer](https://github.com/bytedance/xgplayer) - A HTML5 video player with a parser that saves traffic
* [evil-huawei/evil-huawei](https://github.com/evil-huawei/evil-huawei) - Evil Huawei - 华为作过的恶
* [cnodejs/nodeclub](https://github.com/cnodejs/nodeclub) - :baby_chick:Nodeclub 是使用 Node.js 和 MongoDB 开发的社区系统
* [react-grid-layout/react-draggable](https://github.com/react-grid-layout/react-draggable) - React draggable component
* [typekit/webfontloader](https://github.com/typekit/webfontloader) - Web Font Loader gives you added control when using linked fonts via @font-face.
* [GoogleChromeLabs/carlo](https://github.com/GoogleChromeLabs/carlo) - Web rendering surface for Node applications *(archived)*
* [rastapasta/mapscii](https://github.com/rastapasta/mapscii) - 🗺 MapSCII is a Braille & ASCII world map renderer for your console - enter => telnet mapscii.me <= on Mac (brew install telnet) and Linux, connect with PuTTY on Windows
* [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) - A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings
* [cmliu/CF-Workers-docker.io](https://github.com/cmliu/CF-Workers-docker.io) - 这个项目是一个基于 Cloudflare Workers 的 Docker 镜像代理工具。它能够中转对 Docker 官方镜像仓库的请求，解决一些访问限制和加速访问的问题。 *(archived)*
* [bigbluebutton/bigbluebutton](https://github.com/bigbluebutton/bigbluebutton) - A complete web conferencing system for virtual classes and more!
* [node-schedule/node-schedule](https://github.com/node-schedule/node-schedule) - A cron-like and not-cron-like job scheduler for Node.
* [minbrowser/min](https://github.com/minbrowser/min) - A fast, minimal browser that protects your privacy
* [klaudiosinani/signale](https://github.com/klaudiosinani/signale) - Highly configurable logging library
* [mrdoob/stats.js](https://github.com/mrdoob/stats.js) - JavaScript Performance Monitor
* [zizifn/edgetunnel](https://github.com/zizifn/edgetunnel) - Running V2ray inside edge/serverless runtime
* [EvoMap/evolver](https://github.com/EvoMap/evolver) - The GEP-powered self-evolving engine for AI agents. Auditable evolution with Genes, Capsules, and Events. | evomap.ai
* [GetStream/Winds](https://github.com/GetStream/Winds) - A Beautiful Open Source RSS & Podcast App Powered by Getstream.io *(archived)*
* [marmelab/gremlins.js](https://github.com/marmelab/gremlins.js) - Monkey testing library for web apps and Node.js
* [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) - Micro check library
* [release-it/release-it](https://github.com/release-it/release-it) - 🚀 Automate versioning and package publishing
* [xanderfrangos/twinkle-tray](https://github.com/xanderfrangos/twinkle-tray) - Easily manage the brightness of your monitors in Windows from the system tray
* [poloclub/cnn-explainer](https://github.com/poloclub/cnn-explainer) - Learning Convolutional Neural Networks with Interactive Visualization.
* [developit/htm](https://github.com/developit/htm) - Hyperscript Tagged Markup: JSX alternative using standard tagged templates, with compiler support.
* [rawgraphs/rawgraphs-app](https://github.com/rawgraphs/rawgraphs-app) - A web interface to create custom vector-based visualizations on top of RAWGraphs core
* [mozilla/nunjucks](https://github.com/mozilla/nunjucks) - A powerful templating engine with inheritance, asynchronous control, and more (jinja2 inspired)
* [eze-is/web-access](https://github.com/eze-is/web-access) - 给 Claude Code 装上完整联网能力的 skill：三层通道调度 + 浏览器 CDP + 并行分治
* [didi/chameleon](https://github.com/didi/chameleon) - 🦎 一套代码运行多端，一端所见即多端所见 *(archived)*
* [aksonov/react-native-router-flux](https://github.com/aksonov/react-native-router-flux) - The first declarative React Native router
* [dice2o/BingGPT](https://github.com/dice2o/BingGPT) - Desktop application of new Bing's AI-powered chat (Windows, macOS and Linux)
* [violentmonkey/violentmonkey](https://github.com/violentmonkey/violentmonkey) - Violentmonkey provides userscripts support for browsers. It works on browsers with WebExtensions support.
* [mertJF/tailblocks](https://github.com/mertJF/tailblocks) - Ready-to-use Tailwind CSS blocks.
* [laoma2053/awesome-zhuiju-free](https://github.com/laoma2053/awesome-zhuiju-free) - 免费无广告的追剧资源指南，人工精选资源、每天检测资源有效性。收录在线影视、影视APP、网盘搜索、磁力BT、字幕、TVBox / 影视仓空壳软件/配置地址、IPTV直播源、会员拼团、影视相关开源项目。开源，社区共同维护。
* [pdone/lx-music-source](https://github.com/pdone/lx-music-source) - 洛雪音乐源
* [hexgrad/kokoro](https://github.com/hexgrad/kokoro) - https://hf.co/hexgrad/Kokoro-82M
* [node-fetch/node-fetch](https://github.com/node-fetch/node-fetch) - A light-weight module that brings the Fetch API to Node.js
* [yemount/pose-animator](https://github.com/yemount/pose-animator)
* [ricklamers/gridstudio](https://github.com/ricklamers/gridstudio) - Grid studio is a web-based application for data science with full integration of open source data science frameworks and languages. *(archived)*
* [idurar/idurar-erp-crm](https://github.com/idurar/idurar-erp-crm) - Free Open Source ERP CRM Software Accounting Invoicing | Node.Js React
* [orbitdb/orbitdb](https://github.com/orbitdb/orbitdb) - Peer-to-Peer Databases for the Decentralized Web
* [justlovemaki/AIClient2API](https://github.com/justlovemaki/AIClient2API) - Self-hosted multi-protocol AI API proxy for Antigravity, Codex, Grok, Kiro, OpenAI, Claude, and custom providers. Supports OpenAI-compatible API, Claude API, Gemini protocol conversion, GPT, Grok Build, Claude Opus, Gemini Pro, Kimi, MiniMax, provider pools, smart routing, and automatic failover.
* [uber/react-vis](https://github.com/uber/react-vis) - Data Visualization Components
* [bigcalendar/react-big-calendar](https://github.com/bigcalendar/react-big-calendar) - gcal/outlook like calendar component
* [trazyn/ieaseMusic](https://github.com/trazyn/ieaseMusic) - 网易云音乐第三方 *(archived)*
* [johnfactotum/foliate](https://github.com/johnfactotum/foliate) - Read e-books in style
* [chvin/react-tetris](https://github.com/chvin/react-tetris) - Use React, Redux, Immutable to code Tetris. 🎮
* [porsager/postgres](https://github.com/porsager/postgres) - Postgres.js - The Fastest full featured PostgreSQL client for Node.js, Deno, Bun and CloudFlare
* [qiao/PathFinding.js](https://github.com/qiao/PathFinding.js) - A comprehensive path-finding library for grid based games
* [Kenshin/simpread](https://github.com/Kenshin/simpread) - 简悦 ( SimpRead ) - 让你瞬间进入沉浸式阅读的扩展
* [ProseMirror/prosemirror](https://github.com/ProseMirror/prosemirror) - The ProseMirror WYSIWYM editor *(archived)*
* [facebookarchive/react-360](https://github.com/facebookarchive/react-360) - Create amazing 360 and VR content using React *(archived)*
* [ejci/favico.js](https://github.com/ejci/favico.js) - Make use of your favicon with badges, images or videos
* [sxei/chrome-plugin-demo](https://github.com/sxei/chrome-plugin-demo) - 《Chrome插件开发全攻略》配套完整Demo，欢迎clone体验
* [gotwarlost/istanbul](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool that computes statement, line, function and branch coverage with module loader hooks to transparently add coverage when running tests. Supports all JS coverage use cases including unit tests, server side functional tests and browser tests. Built for scale. *(archived)*
* [GoogleChrome/web-vitals](https://github.com/GoogleChrome/web-vitals) - Essential metrics for a healthy site.
* [react-toolbox/react-toolbox](https://github.com/react-toolbox/react-toolbox) - A set of React components implementing Google's Material Design specification with the power of CSS Modules
* [flutterchina/flutter-in-action](https://github.com/flutterchina/flutter-in-action) - 《Flutter实战》书稿。第二版书稿已上传，请移步新Repo。
* [aemkei/jsfuck](https://github.com/aemkei/jsfuck) - Write any JavaScript with 6 Characters: []()!+
* [poloclub/transformer-explainer](https://github.com/poloclub/transformer-explainer) - Transformer Explained Visually: Learn How LLM Transformer Models Work with Interactive Visualization
* [codecombat/codecombat](https://github.com/codecombat/codecombat) - Game for learning how to code.
* [jamiebuilds/itsy-bitsy-data-structures](https://github.com/jamiebuilds/itsy-bitsy-data-structures) - :european_castle: All the things you didn't know you wanted to know about data structures
* [cerebroapp/cerebro](https://github.com/cerebroapp/cerebro) - 🔵 Cerebro is an open-source launcher to improve your productivity and efficiency
* [reorproject/reor](https://github.com/reorproject/reor) - Private & local AI personal knowledge management app for high entropy people. *(archived)*
* [isno/theByteBook](https://github.com/isno/theByteBook) - ⭐ 【出版书籍】京东购买链接 https://item.jd.com/14531549.html 深入讲解内核网络、Kubernetes、ServiceMesh、容器等云原生相关技术。经历实践检验的“大规模分布式系统”开发指南。
* [mcollina/autocannon](https://github.com/mcollina/autocannon) - fast HTTP/1.1 benchmarking tool written in Node.js
* [carhartl/jquery-cookie](https://github.com/carhartl/jquery-cookie) - No longer maintained, superseded by JS Cookie: *(archived)*
* [NorthwoodsSoftware/GoJS](https://github.com/NorthwoodsSoftware/GoJS) - JavaScript diagramming library for interactive flowcharts, org charts, design tools, planning tools, visual languages.
* [appbaseio/dejavu](https://github.com/appbaseio/dejavu) - A Web UI for Elasticsearch and OpenSearch: Import, browse and edit data with rich filters and query views, create reference search UIs.
* [gridsome/gridsome](https://github.com/gridsome/gridsome) - ⚡️ The Jamstack framework for Vue.js
* [floccusaddon/floccus](https://github.com/floccusaddon/floccus) - :cloud: Sync your bookmarks privately across browsers and devices
* [NobyDa/Script](https://github.com/NobyDa/Script) - This project is based on the scripting capabilities of several excellent iOS proxy tools (e.g. Surge, Quantumult X)
* [hiteshchoudhary/chai-backend](https://github.com/hiteshchoudhary/chai-backend) - A video series on chai aur code youtube channel
* [jerryc127/hexo-theme-butterfly](https://github.com/jerryc127/hexo-theme-butterfly) - 🦋 A Hexo Theme: Butterfly
* [tumobi/nideshop-mini-program](https://github.com/tumobi/nideshop-mini-program) - NideShop：基于Node.js+MySQL开发的开源微信小程序商城（微信小程序）
* [eooce/nodejs-argo](https://github.com/eooce/nodejs-argo) - nodejs-argo是一个强大的Argo隧道部署工具，专为PaaS平台和游戏玩具平台设计。它支持多种代理协议(VLESS、VMess、Trojan)等，有直连协议(Socks5、Hysteria2、Reality)可选开启，并集成了哪吒探针功能
* [chuspeeism/dashi-ppt-skill](https://github.com/chuspeeism/dashi-ppt-skill) - An AI-agent skill that generates browser-editable presentations from multiple visual themes, exportable to HTML, PDF, and PPTX.
* [isomorphic-git/isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - A pure JavaScript implementation of git for node and browsers!
* [antonioru/beautiful-react-hooks](https://github.com/antonioru/beautiful-react-hooks) - 🔥 A collection of beautiful and (hopefully) useful React hooks to speed-up your components and hooks development 🔥
* [litten/hexo-theme-yilia](https://github.com/litten/hexo-theme-yilia) - 一个简洁优雅的hexo主题 A simple and elegant theme for hexo.
* [OpenWhispr/openwhispr](https://github.com/OpenWhispr/openwhispr) - Voice-to-text dictation app with local (Nvidia Parakeet/Whisper) and cloud models (BYOK). Privacy-first and available cross-platform.
* [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) - HTML5 <audio> or <video> player with support for MP4, WebM, and MP3 as well as HLS, Dash, YouTube, Facebook, SoundCloud and others with a common HTML5 MediaElement API, enabling a consistent UI in all browsers.
* [doublespeakgames/adarkroom](https://github.com/doublespeakgames/adarkroom) - A Dark Room - A Minimalist Text Adventure
* [bchiang7/v4](https://github.com/bchiang7/v4) - Fourth iteration of my personal website built with Gatsby
* [seajs/seajs](https://github.com/seajs/seajs) - A Module Loader for the Web
* [fluent-ffmpeg/node-fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) - A fluent API to FFMPEG (http://www.ffmpeg.org) *(archived)*
* [dat-ecosystem/dat](https://github.com/dat-ecosystem/dat) - :floppy_disk: peer-to-peer sharing & live syncronization of files via command line
* [expressjs/morgan](https://github.com/expressjs/morgan) - HTTP request logger middleware for node.js
* [MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-](https://github.com/MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-) - A beautiful cross platform Desktop Player for Google Play Music
* [layui/layer](https://github.com/layui/layer) - 丰富多样的 Web 弹出层组件，可轻松实现 Alert/Confirm/Prompt/ 普通提示/页面区块/iframe/tips等等几乎所有的弹出交互。目前已成为最多人使用的弹层解决方案 *(archived)*
* [soldair/node-qrcode](https://github.com/soldair/node-qrcode) - qr code generator
* [fluid-dev/hexo-theme-fluid](https://github.com/fluid-dev/hexo-theme-fluid) - :ocean: 一款 Material Design 风格的 Hexo 主题 / An elegant Material-Design theme for Hexo
* [lorien/awesome-web-scraping](https://github.com/lorien/awesome-web-scraping) - List of libraries, tools and APIs for web scraping and data processing.
* [jamez-bondos/awesome-gpt4o-images](https://github.com/jamez-bondos/awesome-gpt4o-images) - Awesome curated collection of images and prompts generated by GPT-4o and gpt-image-1. Explore AI generated visuals created with ChatGPT and Sora, showcasing OpenAI’s advanced image generation capabilities.
* [jnMetaCode/superpowers-zh](https://github.com/jnMetaCode/superpowers-zh) - 🦸 AI 编程超能力 · 中文增强版 — superpowers（250k+ ⭐）完整汉化 + 4 个中国原创 skills，让 Claude Code / Copilot CLI / Hermes Agent / Cursor / Windsurf / Kiro / Gemini CLI / Qoder 等 26 款 AI 编程工具真正会干活
* [developit/microbundle](https://github.com/developit/microbundle) - 📦 Zero-configuration bundler for tiny modules.
* [pinokiocomputer/pinokio](https://github.com/pinokiocomputer/pinokio) - AI Browser
* [markodenic/web-development-resources](https://github.com/markodenic/web-development-resources) - Awesome Web Development Resources.
* [nativewind/nativewind](https://github.com/nativewind/nativewind) - The utility-first workflow you love from Tailwind CSS in your React Native applications.
* [relax/relax](https://github.com/relax/relax) - New generation CMS on top of React, Redux and GraphQL
* [collabnix/dockerlabs](https://github.com/collabnix/dockerlabs) - Docker - Beginners | Intermediate | Advanced
* [mruniquehacker/Knightbot-MD](https://github.com/mruniquehacker/Knightbot-MD) - A simple WhatsApp bot to manage groups
* [codebymitch/TitanBot](https://github.com/codebymitch/TitanBot) - A powerful, all-in-one Discord assistant built for every server.
* [JackyAndroid/AndroidInterview-Q-A](https://github.com/JackyAndroid/AndroidInterview-Q-A) - The top Internet companies android interview questions and answers.
* [antvis/F2](https://github.com/antvis/F2) - 📱📈An elegant, interactive and flexible charting library for mobile.
* [iamcco/markdown-preview.nvim](https://github.com/iamcco/markdown-preview.nvim) - markdown preview plugin for (neo)vim
* [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) - A Vue.js plugin for lazyload your Image or Component in your application.
* [hotheadhacker/no-as-a-service](https://github.com/hotheadhacker/no-as-a-service) - No-as-a-Service (NaaS) is a simple API that returns a random rejection reason. Use it when you need a realistic excuse, a fun “no,” or want to simulate being turned down in style.
* [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) - :trophy: Automate versioning and CHANGELOG generation, with semver.org and conventionalcommits.org
* [enquirer/enquirer](https://github.com/enquirer/enquirer) - Stylish, intuitive and user-friendly prompts. Used by eslint, webpack, yarn, pm2, pnpm, RedwoodJS, FactorJS, salesforce, Cypress, Google Lighthouse, Generate, tencent cloudbase, lint-staged, gluegun, hygen, hardhat, AWS Amplify, GitHub Actions Toolkit, @airbnb/nimbus, and more! Please follow Enquirer's author: https://github.com/jonschlinkert
* [bestony/logoly](https://github.com/bestony/logoly) - A Pornhub Flavour Logo Generator
* [mailcheck/mailcheck](https://github.com/mailcheck/mailcheck) - Reduce misspelled email addresses in your web apps.
* [alibaba/anyproxy](https://github.com/alibaba/anyproxy) - A fully configurable http/https proxy in NodeJS
* [OwlCarousel2/OwlCarousel2](https://github.com/OwlCarousel2/OwlCarousel2) - DEPRECATED jQuery Responsive Carousel.
* [VulcanJS/Vulcan](https://github.com/VulcanJS/Vulcan) - 🌋 A toolkit to quickly build apps with React, GraphQL & Meteor *(archived)*
* [Mango/slideout](https://github.com/Mango/slideout) - A touch slideout navigation menu for your mobile web apps.
* [styled-system/styled-system](https://github.com/styled-system/styled-system) - ⬢ Style props for rapid UI development
* [timqian/chart.xkcd](https://github.com/timqian/chart.xkcd) - xkcd styled chart lib
* [openwrt/luci](https://github.com/openwrt/luci) - LuCI - OpenWrt Configuration Interface
* [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) - Serves a webpack app. Updates the browser on changes. Documentation https://webpack.js.org/configuration/dev-server/.
* [vladikoff/chromeos-apk](https://github.com/vladikoff/chromeos-apk) - ☢️ Run Android Apps in Chrome OS OR Chrome in OS X, Linux and Windows.
* [UnblockNeteaseMusic/server](https://github.com/UnblockNeteaseMusic/server) - Revive unavailable songs for Netease Cloud Music (Refactored & Enhanced version)
* [hotoo/pinyin](https://github.com/hotoo/pinyin) - :cn: 汉字拼音 ➜ hàn zì pīn yīn
* [codemirror/dev](https://github.com/codemirror/dev) - Development repository for the CodeMirror editor project *(archived)*
* [visjs/vis](https://github.com/visjs/vis) - ⚠️ This project is not maintained anymore! Please go to https://github.com/visjs *(archived)*
* [pt-plugins/PT-Plugin-Plus](https://github.com/pt-plugins/PT-Plugin-Plus) - PT 助手 Plus，为 Microsoft Edge、Google Chrome、Firefox 浏览器插件（Web Extensions），主要用于辅助下载 PT 站的种子。 *(archived)*
* [gregberge/loadable-components](https://github.com/gregberge/loadable-components) - The recommended Code Splitting library for React ✂️✨
* [hakimel/Ladda](https://github.com/hakimel/Ladda) - Buttons with built-in loading indicators.
* [danialfarid/ng-file-upload](https://github.com/danialfarid/ng-file-upload) - Lightweight Angular directive to upload files with optional FileAPI shim for cross browser support
* [mgonto/restangular](https://github.com/mgonto/restangular) - AngularJS service to handle Rest API Restful Resources properly and easily
* [gaotianliuyun/gao](https://github.com/gaotianliuyun/gao) - FongMi影视和tvbox配置文件，如果喜欢，请Fork自用。使用前请仔细阅读仓库说明，一旦使用将被视为你已了解。
* [stitchesjs/stitches](https://github.com/stitchesjs/stitches) - [Not Actively Maintained] CSS-in-JS with near-zero runtime, SSR, multi-variant support, and a best-in-class developer experience. *(archived)*
* [vercel/styled-jsx](https://github.com/vercel/styled-jsx) - Full CSS support for JSX without compromises
* [memochou1993/gpt-ai-assistant](https://github.com/memochou1993/gpt-ai-assistant) - OpenAI + LINE + Vercel = GPT AI Assistant
* [reactjs/react-router-redux](https://github.com/reactjs/react-router-redux) - Ruthlessly simple bindings to keep react-router and redux in sync *(archived)*
* [dthree/cash](https://github.com/dthree/cash) - Cross-platform Linux commands in ES6
* [icindy/wxParse](https://github.com/icindy/wxParse) - wxParse-微信小程序富文本解析自定义组件，支持HTML及markdown解析
* [jamiebuilds/unstated](https://github.com/jamiebuilds/unstated) - State so simple, it goes without saying
* [facebookarchive/nuclide](https://github.com/facebookarchive/nuclide) - An open IDE for web and native mobile development, built on top of Atom *(archived)*
* [DIYgod/APlayer](https://github.com/DIYgod/APlayer) - :lollipop: Wow, such a beautiful HTML5 music player
* [mnfst/awesome-free-llm-apis](https://github.com/mnfst/awesome-free-llm-apis) - List of Permanent Free LLM API (API Keys)
* [Axorax/awesome-free-apps](https://github.com/Axorax/awesome-free-apps) - Curated list of the best free apps for PC and mobile
* [nodejs/undici](https://github.com/nodejs/undici) - An HTTP/1.1 client, written from scratch for Node.js
* [nhn/tui.image-editor](https://github.com/nhn/tui.image-editor) - 🍞🎨 Full-featured photo image editor using canvas. It is really easy, and it comes with great filters. *(archived)*
* [fengyuanchen/cropper](https://github.com/fengyuanchen/cropper) - ⚠️ [Deprecated] No longer maintained, please use https://github.com/fengyuanchen/jquery-cropper *(archived)*
* [visionmedia/page.js](https://github.com/visionmedia/page.js) - Micro client-side router inspired by the Express router
* [hagopj13/node-express-boilerplate](https://github.com/hagopj13/node-express-boilerplate) - A boilerplate for building production-ready RESTful APIs using Node.js, Express, and Mongoose
* [ustbhuangyi/vue-analysis](https://github.com/ustbhuangyi/vue-analysis) - :thumbsup: Vue.js 源码分析
* [amsul/pickadate.js](https://github.com/amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker.
* [fex-team/webuploader](https://github.com/fex-team/webuploader) - It's a new file uploader solution! *(archived)*
* [cporter202/API-mega-list](https://github.com/cporter202/API-mega-list) - This GitHub repo is a powerhouse collection of APIs you can start using immediately to build everything from simple automations to full-scale applications. One of the most valuable API lists on GitHub—period. 💪
* [kamens/jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's.
* [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) - 微信调试，各种WebView样式调试、手机浏览器的页面真机调试。便捷的远程调试手机页面、抓包工具，支持：HTTP/HTTPS，无需USB连接设备。
* [pickle-com/glass](https://github.com/pickle-com/glass) - Digital Mind Extension
* [NomaDamas/k-skill](https://github.com/NomaDamas/k-skill) - 한국인을 위한 스킬 모음집 - 에이전트를 한국인으로
* [metafizzy/flickity](https://github.com/metafizzy/flickity) - :leaves: Touch, responsive, flickable carousels
* [di-sukharev/opencommit](https://github.com/di-sukharev/opencommit) - top #1 and most feature rich GPT wrapper for git — generate commit messages with an LLM in 1 sec — works with Claude, GPT and every other provider, supports local Ollama models too
* [cmliu/CF-Workers-SUB](https://github.com/cmliu/CF-Workers-SUB) - 这个是一个通过 Cloudflare Workers 搭建，将你任意节点与多个订阅汇聚成专属于你的订阅链接 *(archived)*
* [dequelabs/axe-core](https://github.com/dequelabs/axe-core) - Accessibility engine for automated Web UI testing
* [ecomfe/echarts-for-weixin](https://github.com/ecomfe/echarts-for-weixin) - 基于 Apache ECharts 的微信小程序图表库
* [bailicangdu/react-pxq](https://github.com/bailicangdu/react-pxq) - 一个 react + redux 的完整项目 和 个人总结
* [blasten/turn.js](https://github.com/blasten/turn.js) - The page flip effect for HTML5
* [WiseLibs/better-sqlite3](https://github.com/WiseLibs/better-sqlite3) - The fastest and simplest library for SQLite3 in Node.js.
* [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) - 🔥 Official Firecrawl MCP Server - Adds powerful web scraping and search to Cursor, Claude and any other LLM clients.
* [final-form/react-final-form](https://github.com/final-form/react-final-form) - 🏁 High performance subscription-based form state management for React
* [dc-js/dc.js](https://github.com/dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js
* [ethereum/mist](https://github.com/ethereum/mist) - [DEPRECATED] Mist. Browse and use Ðapps on the Ethereum network. *(archived)*
* [Huibq/keep-alive](https://github.com/Huibq/keep-alive) - 洛雪音乐音源、MusicFree音源、落雪音乐音源
* [kska32/ebooks](https://github.com/kska32/ebooks) - 收藏的一些经典的历史、政治、心理、哲学、数学、计算机方面电子书(约10万本）
* [jbaysolutions/vue-grid-layout](https://github.com/jbaysolutions/vue-grid-layout) - A draggable and resizable grid layout, for Vue.js.
* [berstend/puppeteer-extra](https://github.com/berstend/puppeteer-extra) - 💯 Teach puppeteer new tricks through plugins.
* [surmon-china/vue-quill-editor](https://github.com/surmon-china/vue-quill-editor) - @quilljs editor component for @vuejs(2)
* [Ripple-TS/ripple](https://github.com/Ripple-TS/ripple) - the elegant TypeScript UI framework
* [thomaspark/flexboxfroggy](https://github.com/thomaspark/flexboxfroggy) - A game for learning CSS flexbox 🐸
* [ganeshrvel/openmtp](https://github.com/ganeshrvel/openmtp) - OpenMTP - Advanced Android File Transfer Application for macOS
* [Vincit/objection.js](https://github.com/Vincit/objection.js) - An SQL-friendly ORM for Node.js
* [FormidableLabs/radium](https://github.com/FormidableLabs/radium) - A toolchain for React component styling. *(archived)*
* [stalniy/casl](https://github.com/stalniy/casl) - CASL is an isomorphic authorization JavaScript library which restricts what resources a given user is allowed to access
* [axa-group/nlp.js](https://github.com/axa-group/nlp.js) - An NLP library for building bots, with entity extraction, sentiment analysis, automatic language identify, and so more
* [googlecreativelab/anypixel](https://github.com/googlecreativelab/anypixel) - A web-friendly way for anyone to build unusual displays *(archived)*
* [jsdelivr/jsdelivr](https://github.com/jsdelivr/jsdelivr) - A free, fast, and reliable Open Source CDN for npm, GitHub, Javascript, and ESM
* [up-for-grabs/up-for-grabs.net](https://github.com/up-for-grabs/up-for-grabs.net) - This is a list of projects which have curated tasks specifically for new contributors. These issues are a great way to get started with a project, or to help share the load of working on open source projects. Jump in!
* [js-org/js.org](https://github.com/js-org/js.org) - Dedicated to JavaScript and its awesome community since 2015
* [log4js-node/log4js-node](https://github.com/log4js-node/log4js-node) - A port of log4js to node.js
* [documentationjs/documentation](https://github.com/documentationjs/documentation) - :book: documentation for modern JavaScript
* [airbnb/hypernova](https://github.com/airbnb/hypernova) - A service for server-side rendering your JavaScript views *(archived)*
* [nodegit/nodegit](https://github.com/nodegit/nodegit) - Native Node bindings to Git.
* [syntaxhighlighter/syntaxhighlighter](https://github.com/syntaxhighlighter/syntaxhighlighter) - SyntaxHighlighter is a fully functional self-contained code syntax highlighter developed in JavaScript.
* [facebook/memlab](https://github.com/facebook/memlab) - A framework for finding JavaScript memory leaks and analyzing heap snapshots
* [MrSwitch/hello.js](https://github.com/MrSwitch/hello.js) - A Javascript RESTFUL API library for connecting with OAuth2 services, such as Google+ API, Facebook Graph and Windows Live Connect
* [wooorm/franc](https://github.com/wooorm/franc) - Natural language detection
* [ternjs/tern](https://github.com/ternjs/tern) - A JavaScript code analyzer for deep, cross-editor language support
* [hybridgroup/cylon](https://github.com/hybridgroup/cylon) - JavaScript framework for robotics, drones, and the Internet of Things (IoT)
* [mattdiamond/fuckitjs](https://github.com/mattdiamond/fuckitjs) - The Original Javascript Error Steamroller
* [simov/grant](https://github.com/simov/grant) - OAuth Proxy
* [spencermountain/spacetime](https://github.com/spencermountain/spacetime) - A lightweight javascript timezone library
* [stacktracejs/stacktrace.js](https://github.com/stacktracejs/stacktrace.js) - Generate, parse, and enhance JavaScript stack traces in all web browsers
* [bebraw/jswiki](https://github.com/bebraw/jswiki) - JavaScript wiki. Focuses mainly on JS/HTML5/WebGL related tech.
* [creationix/js-git](https://github.com/creationix/js-git) - A JavaScript implementation of Git.
* [rmm5t/jquery-timeago](https://github.com/rmm5t/jquery-timeago) - :clock8: The original jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago").
* [openspeedtest/Speed-Test](https://github.com/openspeedtest/Speed-Test) - SpeedTest by OpenSpeedTest™ is a Free and Open-Source HTML5 Network Performance Estimation Tool Written in Vanilla Javascript and only uses built-in Web APIs like XMLHttpRequest (XHR), HTML, CSS, JS, & SVG. No Third-Party frameworks or libraries are Required. Started in 2011 and moved to OpenSpeedTest.com dedicated Project/Domain Name in 2013.
* [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) - 🚀 Realtime Monitoring solution for Node.js/Express.js apps, inspired by status.github.com, sponsored by https://dynobase.dev
* [awesome-scripts/awesome-userscripts](https://github.com/awesome-scripts/awesome-userscripts) - 📖 A curated list of Awesome Userscripts.
* [mourner/suncalc](https://github.com/mourner/suncalc) - A tiny JavaScript library for calculating sun/moon positions and phases.
* [google/earthengine-api](https://github.com/google/earthengine-api) - Python and JavaScript bindings for calling the Earth Engine API.
* [ccampbell/rainbow](https://github.com/ccampbell/rainbow) - Simple syntax highlighting library written in javascript
* [breejs/bree](https://github.com/breejs/bree) - Bree is a Node.js and JavaScript job task scheduler with worker threads, cron, Date, and human syntax. Built for @ladjs, @forwardemail, @spamscanner, @cabinjs.
* [parallel-js/parallel.js](https://github.com/parallel-js/parallel.js) - Easy multi-core processing utilities for Node.
* [jscad/OpenJSCAD.org](https://github.com/jscad/OpenJSCAD.org) - JSCAD is an open source set of modular, browser and command line tools for creating parametric 2D and 3D designs with JavaScript code. It provides a quick, precise and reproducible method for generating 3D models, and is especially useful for creating ready-to-print 3D designs.
* [babel/babel-sublime](https://github.com/babel/babel-sublime) - Syntax definitions for ES6 JavaScript with React JSX extensions.
* [jcubic/jquery.terminal](https://github.com/jcubic/jquery.terminal) - jQuery Terminal Emulator - JavaScript library for creating web-based terminals with custom commands
* [matheuss/google-translate-api](https://github.com/matheuss/google-translate-api) - A free and unlimited API for Google Translate :dollar::no_entry_sign:
* [gluon-framework/gluon](https://github.com/gluon-framework/gluon) - A new framework for creating desktop apps from websites, using system installed browsers and NodeJS *(archived)*
* [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) - A microservices API Gateway built on top of Express.js
* [ChanceYu/front-end-rss](https://github.com/ChanceYu/front-end-rss) - :orange_book: 根据 RSS 订阅最新前端技术文章并自动分类
* [React-Sight/React-Sight](https://github.com/React-Sight/React-Sight) - Visualization tool for React, with support for Fiber, Router (v4), and Redux
* [reactjs/react-future](https://github.com/reactjs/react-future) - Specs & docs for potential future and experimental React APIs and JavaScript syntax. *(archived)*
* [esdoc/esdoc](https://github.com/esdoc/esdoc) - ESDoc - Good Documentation for JavaScript
* [jofpin/turbit](https://github.com/jofpin/turbit) - Build applications, scripts, and automations powered by high-performance multicore computing using Node.js
* [taylorhakes/fecha](https://github.com/taylorhakes/fecha) - Lightweight and simple JS date formatting and parsing
* [microjs/microjs.com](https://github.com/microjs/microjs.com) - Fantastic Micro-Frameworks and Micro-Libraries for Fun and Profit!
* [leapmotion/leapjs](https://github.com/leapmotion/leapjs) - JavaScript client for the Leap Motion Controller
* [pacocoursey/paco](https://github.com/pacocoursey/paco) - personal website and blog *(archived)*
* [pillarjs/csrf](https://github.com/pillarjs/csrf) - Logic behind CSRF token creation and verification.
* [Yu9191/wloc](https://github.com/Yu9191/wloc) - 修改 Apple 网络定位（gs-loc）返回坐标 · 支持 Surge / Quantumult X / Loon / Stash · 快捷指令一键设置/恢复定位
