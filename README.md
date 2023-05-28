# LifeGPT using stytch-node-magic-links


<img src="https://github.com/CharlesCreativeContent/stytch-node-magic-links/blob/main/public/images/app.gif?raw=true" width="100%" alt="gif of app login screen"/>

## Tech used: ![OpenAI BADGE](https://img.shields.io/static/v1?label=|&message=OPENAI&color=23555f&style=plastic&logo=openai)![CSS BADGE](https://img.shields.io/static/v1?label=|&message=NODE&color=285f65&style=plastic&logo=nodejs)![JAVASCRIPT BADGE](https://img.shields.io/static/v1?label=|&message=STYTCH&color=3c7f5d&style=plastic&logo=css3)


Thank you for taking the time to check out Life GPT! We used OpenAI to generate health, wealth and spiritual qutoes and Node and the [Stytch API](https://stytch.com/docs/api) to send and authenticate magic links.

My learning was focused on trying out as many Stytch Demos as possible in a few hours and picking the one to build a small ChapGPT style application

## Running the app locally

1. Fill in `STYTCH_PROJECT_ID` and `STYTCH_SECRET` in the `.env` file. Get your credentials from
   your [Stytch dashboard](https://stytch.com/dashboard/api-keys).
2. Add `http://localhost:3000/authenticate` (the `PORT` set in `.env`) as a valid sign-up and
   login URL on your [Stytch dashboard](https://stytch.com/dashboard/redirect-urls).
3. Run `npm i`
4. Run `npm start`
5. Visit `http://localhost:3000` and login with your email. Then check for the Stytch email and
   click the sign in button. You should be signed in!


## Stytch Developer Experience

I liked that Stytch used the magic links for their signup process, because it is very minimal friction for customer onboarding. The [documentation](https://stytch.com/docs) was straight forward. There were enough demos for almost every stack and the dev team has an open [forum](https://forum.stytch.com/) and [slack group](https://stytch.slack.com/ssb/redirect) you can join to talk to the team. The demos were very quick to get you from 0 to locally hosted application.  Some of the newer demos even have auto-deploy buttons to vercel and netlify for example, which I think were very convenient. I would love if more of the demos were deployment ready, being able to directly upload your demos into vercel, netlify, heroku, etc. and have a live demo in seconds would be a game changer for onboarding and top of funnel outreach. I tried the 5 demos below and was able to deploy all of them locally, but had some difficulty hosting them. Decreasing the time to a hosted application can greatly increase conversion rates on developer adoption.



## Demos deployed

<table bordercolor="#66b2b2">
  
  <tr>
    <td width="33.3%"  style="align:center;" valign="top">
<a target="_blank" href="https://github.com/CharlesCreativeContent/Demo-Day">Travelara.org</a>
        <br />
      <a target="_blank" href="https://github.com/CharlesCreativeContent/Demo-Day">
            <img src="https://github.com/CharlesCreativeContent/CharlesCreativeContent/raw/main/images/gif1.gif" width="100%"  alt="Travelara.org"/>
        </a>
    </td>
    <td width="33.3%" valign="top">
<a target="_blank" href="https://github.com/CharlesCreativeContent/Rigley2-FlappyBug">Rigley2-"FlappyBug"</a>
      <br />
        <a target="_blank" href="https://github.com/CharlesCreativeContent/Rigley2-FlappyBug">
          <img src="https://github.com/CharlesCreativeContent/stytch-next/raw/main/public/example-app-image.png" width="100%" alt="Rigley2-'FlappyBug'"/>
        </a>
    </td>
    <td width="33.3%" valign="top">
<a target="_blank" href="https://github.com/CharlesCreativeContent/matching-card-game">Matching Card Game</a>
        <br />
        <a target="_blank" href="https://github.com/CharlesCreativeContent/matching-card-game">
          <img src="https://user-images.githubusercontent.com/100632220/217049841-b9eeb72a-3e50-4074-839a-e64ee5d4a88c.png" width="100%" alt="Matching Card Game"/>
        </a>
    </td>
  </tr>
</table>
