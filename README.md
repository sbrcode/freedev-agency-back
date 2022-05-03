## Install & Launch API

1. `git clone` from repo
2. Install `node_modules` with `yarn install`
3. Run it with `yarn start`


## Consume the REST API

Once launched, this API makes several routes available to you:

- The route to recover the profiles of freelancers:
`GET /freelances`

- The route to get the details of a freelance profile:
`GET /profile/?id={id}`

- The route to get the questionnaire:
`GET /survey/`

- The route to obtain the result of the questionnaire:
`GET /results/?a1={answer1}&a2={answer2}&a3={answer3}...`
