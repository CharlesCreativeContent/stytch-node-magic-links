# LifeGPT using stytch-node-magic-links


<img src="https://github.com/CharlesCreativeContent/stytch-node-magic-links/blob/main/public/images/app.gif?raw=true" width="100%" alt="gif of app login screen"/>

## Tech used: ![OpenAI BADGE](https://img.shields.io/static/v1?label=|&message=OPENAI&color=23555f&style=plastic&logo=openai)![CSS BADGE](https://img.shields.io/static/v1?label=|&message=NODE&color=285f65&style=plastic&logo=javascript)![JAVASCRIPT BADGE](https://img.shields.io/static/v1?label=|&message=STYTCH&color=3c7f5d&style=plastic&logo=css3)


Thank you for taking the time to check out LifeGPT! We used OpenAI to generate health, wealth and spiritual quotes with Node and the [Stytch API](https://stytch.com/docs/api) to send and authenticate magic links.

My learning was centered around analyzing as many Stytch demos as possible in a few hours and choosing one to build a small ChatGPT style application.

## Running the app locally

1. Fill in `STYTCH_PROJECT_ID` and `STYTCH_SECRET` in the `.env` file. Get your credentials from
   your [Stytch dashboard](https://stytch.com/dashboard/api-keys).
2. Update apiKey for OpenAI in server.js
3. Add `http://localhost:3000/authenticate` (the `PORT` set in `.env`) as a valid sign-up and
   login URL on your [Stytch dashboard](https://stytch.com/dashboard/redirect-urls).
4. Run `npm i`
5. Run `npm start`
6. Visit `http://localhost:3000` and login with your email. Then check for the Stytch email and
   click the sign in button. You should be signed in!


## Stytch Developer Experience

[![Watch the video](https://github.com/CharlesCreativeContent/stytch-node-magic-links/blob/main/public/images/0FD9210A-CE0E-4D89-939F-8A197B56C13E.jpeg?raw=true)](https://youtu.be/fxJBj6ExRUg)

<video src=”https://youtube.com/”></video>
I liked that Stytch used the magic links for their signup process, because it is very minimal friction for customer onboarding. The [documentation](https://stytch.com/docs) was straight forward. 

There were enough demos for almost every stack and the dev team has an open [forum](https://forum.stytch.com/) and [slack group](https://stytch.slack.com/ssb/redirect) you can join to talk to the team. The demos were very quick to get you from 0 to locally hosted application. 

I tried the 5 demos below and was able to deploy all of them locally, but had some difficulty hosting them. Decreasing the time to a hosted application can greatly increase conversion rates on developer adoption.

Some of the newer demos already have auto-deploy buttons to [vercel](https://github.com/CharlesCreativeContent/stytch-next/blob/main/README.md#vercel) and [netlify](https://github.com/CharlesCreativeContent/stytch-netlify-example/blob/main/README.md#netlify) for example, which I think were very convenient. I would love if more of the demos were deployment ready, being able to directly upload your demos into vercel, netlify, heroku, etc. and have a live demo in seconds would be a game changer for onboarding and top of funnel outreach.



## Demos deployed
• <a target="_blank" href="https://github.com/CharlesCreativeContent/stytch-node-magic-links">Node Magic Links
</a>
• <a target="_blank" href="https://github.com/CharlesCreativeContent/stytch-react-example">Stytch React App
       </a>
• <a target="_blank" href="https://github.com/CharlesCreativeContent/stytch-next">Stytch Next App
       </a>
• <a target="_blank" href="https://github.com/CharlesCreativeContent/stytch-javascript-links">Stytch Javascript Links
       </a>
• <a target="_blank" href="https://github.com/CharlesCreativeContent/stytch-netlify-example">Stytch Netlify App
       </a>


## Memes


<img style="width:100%;" src="https://github.com/CharlesCreativeContent/stytch-node-magic-links/blob/main/public/images/7ne6rp.jpg?raw=true">


<img style="width:100%;" src="https://github.com/CharlesCreativeContent/stytch-node-magic-links/blob/main/public/images/7ne75d.jpg?raw=true">



<img style="width:100%;" src="https://github.com/CharlesCreativeContent/stytch-node-magic-links/blob/main/public/images/7ne755.jpg?raw=true">
