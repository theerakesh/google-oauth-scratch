## Google Oauth Implementation from scratch

1. `yarn install`
2. Update the `example.config.ts` and rename to `config.ts`
3. Install typescript `npm install -g typescript`

Update relevant `authorized redirect ui` in the google clientId creation wizard accordingly.

### Deploying to AWS using `serverless`

- Install `aws-cli-tools` and autheticate
- Install `serverless` using `npm install -g serverless`
- Edit the `serverless.yml`, accordingly
- Compile typescript to javascript, run `tsc` in root directory
- Finally `sls deploy`
