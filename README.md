# todoapp-backend

This is the backend of TODO app.

To deploy it manually, we need to use Serverless framework and execute the following command
`serverless deploy --verbose`

This backend component is integrated with travis.ci and travis.ci will pull updates from this repository, build it and use Serverless framework to deploy to AWS automatically.
