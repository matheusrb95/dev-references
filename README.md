# My Dev References

> Last update: 08/2026

## Table of Contents

- [Code Structure](#code-structure)
- [Code Patterns](#code-patterns)
- [Database](#database)
- [Observability](#observability)
- [CICD](#cicd)
- [Repos](#repos)
- [Game Dev](#game-dev)
- [Git](#git)
- [Others](#others)

## Code Structure

* [How I write HTTP services in Go after 13 years](https://grafana.com/blog/how-i-write-http-services-in-go-after-13-years/) - *structuring servers and handlers for maximum maintainability*
* [App Structure](https://rednafi.com/go/app-structure/) - *letting the domain guide your application structure*
* [Package as layers](https://web.archive.org/web/20251012015522/https://www.gobeyond.dev/packages-as-layers/) - *foundational architecture pattern behind the wtfdial project*

## Code Patterns

* [Go Naming Conventions](https://www.alexedwards.net/blog/go-naming-conventions) - *conventions that helps maintainability*
* [Unit of Work](https://rednafi.com/go/repo-txn-uow/) - *managing transactional boundaries across services*
* [Dynamic JSON in Go](https://eagain.net/articles/go-dynamic-json/) - *typing tips for nested jsons*
* [NULL SQL in Go](https://medium.com/aubergine-solutions/how-i-handled-null-possible-values-from-database-rows-in-golang-521fb0ee267) - *handling null database values cleanly in application domain types*
* [Intentional Code](https://intentionalcode.com/) - *code pattern catalog in go*
* [A Step-by-Step Guide to Go Internationalization](https://phrase.com/blog/posts/internationalization-i18n-go/) - *practical strategies for implementing i18n/l10n in go apps*
* [URL path parameters in routes](https://www.willem.dev/articles/url-path-parameters-in-routes/) - *patterns and trade-offs for handling path parameters in go routing*
* [Excessive nil pointer checks in Go](https://konradreiche.com/blog/excessive-nil-pointer-checks-in-go/) - *a nil check is suspicious when it silently handles a state the program claims should be impossible*
* [Four ways to pay an order in Go](https://viviersoft.com/blog/ddd-go-2-four-ways-to-pay-an-order/) - *talks about a pattern named Functional Event Sourcing Decider*

## Database

* [Life Altering Postgresql Patterns](https://mccue.dev/pages/3-11-25-life-altering-postgresql-patterns) - *techniques for scaling postgresql usage*

## Observability

* [A Guide to Observability with Go](https://www.lucavallin.com/blog/opentelemetry-a-guide-to-observability-with-go) - *how to integrate open telemetry in a go application*
* [Canonical Log Lines](https://stripe.com/blog/canonical-log-lines) - *log all information needed once*

## CICD

* [How I Tuned My CI/CD Pipeline To Be Done in 60 Seconds](https://mzfit.app/blog/the_one_where_i_tune_my_cdcd_pipeline/)
* [Github Actions and Go](https://olegk.dev/github-actions-and-go) - *efficient CI/CD workflow setup for Go using caching and linters*

## Repos

* [Data Orientied Design](https://github.com/ardanlabs/service) - *production-ready reference architecture for go services based on data-oriented design*
* [Exposure Notifications Verification Server](https://github.com/google/exposure-notifications-verification-server) - *real-world enterprise go server built by google*
* [Go API Server](https://github.com/urlspace/api) - *clean api server template following layered architecture principles*
* [Goapp](https://github.com/naughtygopher/goapp) - *opinionated production template for modular go microservices*
* [Pacman Go](https://github.com/gandarez/pacman-go) - *pacman game using ebiten*
* [Catle](https://github.com/npinochet/castle) - *dark souls like game using ebiten*

## Game Dev

* [Gopher Survival](https://github.com/LuigiVanacore/beginning-game-programming-go-ebitengine) - *book that teaches, step by step, how to program a 2D "bullet-heaven" game using the Go language and the Ebitengine framework.*
* [Client-Server Architecture](https://www.gabrielgambetta.com/client-server-game-architecture.html) - *techniques to handle with latency in mmorpg*
* [Enemy AI](https://www.youtube.com/watch?v=-y3MOsBetow) - *funny video about implementing an enemy ai based in context steering behavior*

## Git

* [Learn Git](https://learngitbranching.js.org/) - *iterative and visual way of learning git*
* [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) - *feat, chore, refactor, fix, ...*

## Others

* [Multi-tenancy](https://blog.logto.io/implement-multi-tenancy/) - *overview of multi-tenant architecture models (isolated vs shared schema)*
* [Lambda coldstart benchmark](https://github.com/maxday/lambda-perf/tree/main) - *benchmarks comparing cold start latency across runtimes on aws lambda*
* [You've just inherited a legacy C++ codebase, now what?](https://gaultier.github.io/blog/you_inherited_a_legacy_cpp_codebase_now_what.html#3970719462-get-buy-in) - *good tips on how to work with a legacy codebase*
