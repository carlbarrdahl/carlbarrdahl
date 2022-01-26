# Resume / CV

Javascript developer with a wide array of experience working on projects such as realtime mobile games, e-commerce sites, an analytics dashboard for internet of things data, a food-ordering app, a ticketing platform, bots and more.

+6 year experience in React and Node.js development. Quick and efficient. Knowledgeable in ecosystem and best-practices.

## Contents:

1. [Technical skills](#technical-skills)
2. [Work](#work)
3. [Side-projects](#side-projects)
4. [Web3 Hackathons](#hackathons)
5. [Education](#education)
6. [Volunteering](#volunteering)

## Technical skills

- React (Next.js, Gatsby)
- Node.js (Express, Fastify)
- Typescript
- Data fetching (Apollo, React-Query)
- API (GraphQL, OpenAPI, Swagger)
- Authentication (Oauth2, Auth0, Web3)
- Cloud (Firebase, gcloud, Azure, AWS)
- Styling (chakra-ui, theme-ui, styled-components, tailwind.css)
- ORM (Prisma, Knex, Sequelize, TypeORM)
- Testing (Jest, Cypress)
- API integration (Stripe, Google, Youtube)
- Charts (Nivo, Recharts)
- Content (Markdown, MDX)
- Figma
- Web3 (Ceramic Network, basic Solidity)

## Work

### Zephyr Valley `2020.01 - Current`

_Independent consultant_

- Frontend development with React
- Backend development with Node.js
- Oauth2 authentication

### Evolve Technologies `2018.03 - 2019.06`

_Fullstack developer consultant_

- Developed a brand new frontend for a company in the real estate business. Worked closely with one graphic designer, one UX designer and a backend team of five in a agile environment using Jira for project management. Next.js, Apollo, GraphQL.
- Worked with two developers and one UI / UX designer to build an e-health platform for video calls with mobile app and admin dashboard. Serverless, MongoDB, BankID.
- Built a dashboard for an emergency response centre showing vehicles on a map in realtime.
- Built a progressive web app for IKEA Family to be used to sign in attendees for their internal events. QR scanner to read tickets and offline support.

### Annevo `2017.02 - 2018.2`

_Web developer consultant_

- Created real-time components in React and Redux used to manage orders from the different stations in the restaurant. Integrated push notifications for customer communications in the app.
- IoT platform in which I created realtime data visualization components in React and Redux. Deployed to AWS for high availability and low latency real-time communications. Integrated with Elasticsearch for advanced search queries. Worked in a team of 3 frontend developers and 3 backend developers.

Built several internal prototypes including:

- Online realtime multiplayer mobile game in React Native and GameSparks as backend, push notifications to increase player engagement and payment using Swish (swedish mobile bank app) integration.
- Built a tool to create Facebook and Instagram ads using their real estate property data and photos.
- Built a React Native app for tracking the quality of motocross tracks using Google Cloud and Firebase on backend.

### Telenor Connexion `2016 - 2016`

- Created high quality data visualizing components in React and Redux
- Deployed to AWS for high availability and low latency real-time communications
- Integrated with Elasticsearch for advanced search queries

### Ticketmaster `2014 - 2015`

_Frontend developer_

- Created prototypes of new features in React
- Worked on checkout flow

### Sigma (and Maverick by Sigma) `2013 - 2014`

_Frontend developer_

- Front-end development on a large municipal intranet solution built on .NET and EPiServer

### Spielo G2 `2012 - 2013`

_Game developer_

- Developed mobile games in HTML5 running on a backend game engine emitting events via WebSockets
- Built on a module based game engine where several different games shared the same modules
- Cross device development (desktop, tablets, phones)

## Side-projects

### 🌼 Kaleido `2020 - `

Experiment with Three.js and camera. Transforms the camera feed into a kaleidoscope using WebGL shaders. Simple controls to change the parameters for the shaders.

Technologies: React (Next.js), Three.js (react-three-fiber)  
Link: https://kaleido.on.fleek.co  
Example artwork: https://kaleido.on.fleek.co/gallery

### Music project marketplace `2020`

A marketplace for music creators to sell their project files. Embeds a YouTube video explaining the contents of the project and integrates Stripe for payments.

![](https://raw.githubusercontent.com/carlbarrdahl/web/master/src/assets/music-marketplace/figma.png)
![](https://raw.githubusercontent.com/carlbarrdahl/web/master/src/assets/music-marketplace/landing.png)
![](https://raw.githubusercontent.com/carlbarrdahl/web/master/src/assets/music-marketplace/view_project.png)

Technologies: React, Stripe, Firebase  
Link: https://loopsquare.web.app/zen-world/project-name

### Pakt `2020`

Create, manage and sign digital contracts using the mobile app BankID (used in Sweden to authenticate your identity).

Pakt is a platform where users can create and share contracts. Documents are uniquely identified with a hash of its content to ensure everyone signs the same copy and no tampering is done. Signing and verification of users identity is done with BankID which is the leading electronic identification app in Sweden.

Other services can easily be integrated by specifying webhooks that gets triggered when changes occur in the system.

Future improvements could include adding Swish (similar to BankID but for sms payments) to add costs to creating documents or signatures. Users could also be notified by sms when contracts are assigned or new signatures created to connected contract.

Some documents might be sensitive to store on central servers. In that case something like ipfs could be used to store the documents and then secure them with smart contracts on a blockchain, Ethereum for instance.

![](https://raw.githubusercontent.com/carlbarrdahl/web/master/src/assets/pakt/create.png)
Contracts are easily created by dragging a document to upload (or browsing) and filling out the details. Start and end date for contract validity can be set and participants can be added by entering their email.

![](https://raw.githubusercontent.com/carlbarrdahl/web/master/src/assets/pakt/view.png)
Documents are embedded to easily be read without need of downloading. Future improvements can include templates to dynamically generate documents based on data.

![](https://raw.githubusercontent.com/carlbarrdahl/web/master/src/assets/pakt/sign.png)
Sign contract by entering your SSN and open app on mobile. QR code can be added for a more secure (and convenient) signing experience.

![](https://raw.githubusercontent.com/carlbarrdahl/web/master/src/assets/pakt/list.png)
![](https://raw.githubusercontent.com/carlbarrdahl/web/master/src/assets/pakt/webhooks.png)

### Recipe app `2020`

Experimenting with Progressive Web Apps (PWA), web scrapers and JSON+LD.
I often just search for recipes on Google with my phone but the pages are filled with articles, ads and other non-relevant content with no easy way to save these recipes for future use.
I built a product to simply share the recipe to a PWA (using Web Share Target API). This will trigger a robot to crawl the recipe data and store in a Firebase database.

![](https://user-images.githubusercontent.com/2961337/149950703-dc43b8ac-18a0-453c-8f40-b0303bdc0293.png)

Technologies: React, Theme-UI, Firebase, Puppeteer (scraper)  
Link: https://recipes-e0cee.web.app/recipes

### Swisher `2019`

Playing around with QR codes and crypto.
Simple Progressive Web App built in React to generate QR codes and links for payments in swedish banking app Swish. This makes it easier to share payments between people for splitting bills for example. Using crypto to encrypt phone number and payment data so they can safely be shared in the url.

![](https://raw.githubusercontent.com/carlbarrdahl/swisher/master/static/screen.png)

Technologies: React (gatsby), Tailwind, Netlify  
Link: http://swisher.carlb.dev  
Code: https://github.com/carlbarrdahl/swisher

### Thought flow `2019`

Personal journaling app. Playing around with Gatsby and Tailwindcss.

Technologies: React (gatsby), Tailwind  
Link: https://github.com/carlbarrdahl/thought-flow

### Swish Payments `2018`

Open source library written in Typescript to communicate with Swedish Bank app api Swish.

Technologies: Typescript, Jest  
Link: https://github.com/carlbarrdahl/swish-payments

### Busstrams `2014`

First React project. An app to view bus and tram schedule for local transportation.

Technologies: React (v.0.12), Reflux, Gulp, Stylus  
Code: https://github.com/carlbarrdahl/busstrams

## Hackathons

### Skulptur `2021.10`

_🥇 Winner of Open Prize: Best Hack Using Self.ID Or Glaze in Sovereign Data Hackathon_

Decentralized Google Forms platform with Ceramic Network. Create forms and surveys with json-schemas and share with your friends. Forms and responses are stored on ipfs connected to your web3 wallet.

![](https://raw.githubusercontent.com/carlbarrdahl/skulptur/master/screenshot.png)

Technologies: Next.js, Chakra-UI, Ceramic Network  
Code: https://github.com/carlbarrdahl/skulptur  
Link: https://skulptur.vercel.app

### Atoll IDO `2021.10`

IDO launchpad platform built for DeFi & Cross-Chain Interoperability Hackathon.

![](https://raw.githubusercontent.com/carlbarrdahl/atoll-ido/master/screenshot2.png)

Technologies: Next.js, Polkadot, Chakra-UI, Solidity  
Code: https://github.com/carlbarrdahl/atoll-ido  
Link: https://atoll-ido.web.app

### Reef Payment API Gateway `2021.10`

_🥇 Winner of Reef Payment API in DeFi & Cross-chain Interoperability Hackathon_

Merchants with online store can choose to accept payments with REEF wallet.

![](https://raw.githubusercontent.com/carlbarrdahl/reef-payment-api/master/screenshot_admin.png)
![](https://raw.githubusercontent.com/carlbarrdahl/reef-payment-api/master/screenshot_shop1.png)
![](https://raw.githubusercontent.com/carlbarrdahl/reef-payment-api/master/screenshot_checkout.png)

Technologies: Next.js, Chakra-UI, Firebase, Polkadot  
Code: https://github.com/carlbarrdahl/reef-payment-api  
Link: https://reef-payment-api.web.app/

### Conviction Voting `2021.02`

Off-chaing Conviction Voting using Ceramic, IDX and TheGraph.

![](https://raw.githubusercontent.com/carlbarrdahl/conviction-voting/master/ceramic_voting.png)
Technologies: React, Ceramic Network, Fastify, Typescript  
Code: https://github.com/carlbarrdahl/conviction-voting

## Education

### Linnaeus University `2009.09 - 2012.06`

- Media technology
- Web development
- Game development
- User experience
- Interaction design
- Hardware programming

## Volunteering

### Yoga retreat center `2021.04 - 2021.09`

- Helping out in the kitchen to cook vegan food for retreat guests.
