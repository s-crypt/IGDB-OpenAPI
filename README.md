### I have validated the responses against the API. However, this is STILL IN BETA. Please report any bugs and if you come across any discrepancies, please let me know!  
  
You may use this spec however you like, but please credit me somehow as I spent a lot of time on this 😉  

---

The [rapidoc page](https://igdb-openapi.s-crypt.co/rapidoc) is intended to be a full replacement for the current documentation, with custom theming and all of the docs from the current documentation site.  
The [swagger page](https://igdb-openapi.s-crypt.co/swagger) is for people who want to dig into the OpenAPI specification.  
  
To test out the API with a built-in CORS proxy, go to the [rapidoc page](https://igdb-openapi.s-crypt.co/rapidoc) and select `https://corsproxy.io/?https://api.igdb.com/v4` as the server. Use at your own risk as I do not run the proxy, the people at corsproxy.io do.  
  
---
  
TODO:
- [x] Finish component schemas
- [x] Finish Paths
- [X] Validate against API responses
  - [X] Enhance interlinking schemas
  - [X] Add Format to data types
  - [X] Reorder based on API response
- [X] Add format to numbers (oops)
- [X] Implement Oauth2  
  
Future:
- [X] CORS proxy for Try It function - rapidoc
- [x] More/better descriptions of schema items
- [ ] Create examples based on response
- [ ] OAI 3.1 for Websocket support? (See [discussion](https://github.com/s-crypt/IGDB-OpenAPI/discussions/4))
- [X] Theming with IGDB colors - On rapidoc
- [ ] Organize with tags?
- [ ] Automate JSON generation (spec is written in YAML)

Anything else? Please open a discussion!  
  
  
# How do I use this?
### You can use [Swagger Editor](https://editor-next.swagger.io/) or [OpenAPI Generators](https://openapi-generator.tech/docs/generators#client-generators) to generate the following native clients for the API.
  
#### [Swagger Editor](https://editor-next.swagger.io/)
* C# - C Sharp
* C# .Net2 - C Sharp DotNet 2
* Dart
* Dynamic HTML
* Go - Golang
* HTML
* HTML2
* Java
* Javascript
* Jaxrs-cxf
* Kotlin
* OpenAPI
* OpenAPI-YAML
* PHP
* Python
* R
* Ruby
* Scala
* Swift 3, 4, and 5
* Typescript Angular
* Typescript Axios
* Typescript Fetch

#### [OpenAPI Generators](https://openapi-generator.tech/docs/generators#client-generators)
* ada
* android
* apex
* bash
* c
* clojure
* cpp-qt-client
* cpp-restsdk
* cpp-tiny (beta)
* cpp-tizen
* cpp-ue4 (beta)
* crystal (beta)
* csharp
* dart
* dart-dio
* eiffel
* elixir
* elm
* erlang-client
* erlang-proper
* go
* groovy
* haskell-http-client
* java
* java-helidon-client (beta)
* java-micronaut-client (beta)
* javascript
* javascript-apollo-deprecated (deprecated)
* javascript-closure-angular
* javascript-flowtyped
* jaxrs-cxf-client
* jetbrains-http-client (experimental)
* jmeter
* julia-client (beta)
* k6 (beta)
* kotlin
* lua (beta)
* n4js (beta)
* nim (beta)
* objc
* ocaml
* perl
* php
* php-dt (beta)
* php-nextgen (beta)
* powershell (beta)
* python
* python-pydantic-v1
* r
* ruby
* rust
* scala-akka
* scala-gatling
* scala-pekko
* scala-sttp
* scala-sttp4 (beta)
* scalaz
* swift-combine
* swift5
* typescript (experimental)
* typescript-angular
* typescript-aurelia
* typescript-axios
* typescript-fetch
* typescript-inversify
* typescript-jquery
* typescript-nestjs (experimental)
* typescript-node
* typescript-redux-query
* typescript-rxjs
* xojo-client
* zapier (beta) 
