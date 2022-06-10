# Questions

## What are my requirements to the project?

- [ ] well documented
    - [ ] `docs` folder for my intenstions and several explanations
    - [ ] `readme` files for workspace members
    - [ ] `code-comments` for some details
- [ ] primary language `rust`
    - [ ] `rust` cli
    - [ ] `rust` backend
    - [ ] `rust` frontend
    - [ ] `rust` shareable libs
- [ ] modular structure
- [ ] dynamic configuration solution
- [ ] examples with `javascript` apps
- [ ] testing examples
    - [ ] unit tests
    - [ ] integration tests
    - [ ] e2e tests
- [ ] running ci/cd pipelines
- [ ] convention like release strategy
    - [ ] changelog generation
    - [ ] tags / releases
    - [ ] artifacts
    - [ ] deployment examples

## What are my requirements to the `cli`?

- [ ] cli framework
- [ ] recognize related cli apps from name like `cargo` and `cargo-modules`
- [ ] related cli apps inside the same monorepo like `greeting` or `server`

## What are my requirements to the `backends`?

- [ ] binary to run from cli, maybe as related cli app like `cli-server`
- [ ] configuration from env, file or different config provider (repo, database, services like vault)
- [ ] different database drivers / data sources / multiple databases
- [ ] database migrations
- [ ] different authentication solutions
    - [ ] stateful
    - [ ] stateless
    - [ ] ldap / other idp
    - [ ] oauth2 / oidc
    - [ ] saml
- [ ] distributed session management
- [ ] multi tenancy
    - [ ] url path
    - [ ] query string
    - [ ] header
    - [ ] domain
- [ ] logging
- [ ] error handling
- [ ] instrumentation
- [ ] sentry error and performance
- [ ] different http/rest endpoints
    - [ ] get html
    - [ ] post form-data
    - [ ] port multipart
    - [ ] get json
    - [ ] post json
    - [ ] websockets (should work distributed, maybe with redis?)
    - [ ] other methods
- [ ] multiple graphql endpoints
    - [ ] queries
    - [ ] mutations
    - [ ] subscriptions
    - [ ] custom scalars
    - [ ] 
- [ ] different access levels
    - [ ] public
    - [ ] authenticated
    - [ ] roles / scopes
    - [ ] pre- and post-authorize
- [ ] message queues
- [ ] gRPC
- [ ] template engine (ssr + stateful session)
- [ ] multiple spa endpoints (see my requirements to the frontends)
- [ ] mailing with mail templates
- [ ] security investigations
    - [ ] csrf
    - [ ] cors
    - [ ] xss
- [ ] caching
- [ ] background workers (like sidekiq etc.)
- [ ] scheduler
- [ ] custom scipted functions
    - [ ] triggered from rest
    - [ ] triggered from event
    - [ ] with context
    - [ ] with config
    - [ ] with databases
    - [ ] with http/other clients
    - [ ] with mailer
- [ ] solution for integrations
- [ ] default healthcheck
- [ ] custom healthcheck

## What are my requirements to the `frontends`?

- [ ] custom website (ssr from template engine)
- [ ] custom internal website (sessions) (ssr from template engine)
- [ ] different spa examples with several base paths
    - [ ] `rust` wasm spa examples
        - [ ] example with custom ui framework
        - [ ] example with tailwind
        - [ ] simple wasm example
        - [ ] example with yew
        - [ ] example with dioxus
        - [ ] example with perseus
        - [ ] example with seed
        - [ ] example with percy
    - [ ] `javascript` spa examples
        - [ ] create-react-app example
        - [ ] nextjs example
        - [ ] vue example
        - [ ] svelte example
- [ ] custom themes / override ssr

## What are my requirements to the `shareable libs`?

- [ ] share code between `backends` and `frontends`
- [ ] share code between `backends`
- [ ] share code between `frontends`
- [ ] share code to other projects (api clients, etc.)

## Do i have additional requirements?

- [ ] can i deploy all examples as one big artifact?
- [ ] how should a production deployment looks like?
- [ ] example for PaaS deployment
    - [ ] DigitalOcean
    - [ ] Heroku
    - [ ] other?
- [ ] example for container deployment
- [ ] showcase for testing different parts in the projects
- [ ] solution for code coverage
- [ ] solution for code quality measure
- [ ] benchmarks for different examples
