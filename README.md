# IMPORTANT: NOT COMPLETE
### The schemas have yet to be validated.

The Excel spreadsheet have been created to speed up the copy process, by auto-crafting the YAML properties of enums based on the copied table from IGDB's docs.

TODO:
- [x] Finish component schemas
- [ ] Finish Paths
- [ ] Validate against API responses
  - [ ] Enhance interlinking before GameVersionFeature (Ex: Reference ID for Game will $ref: /components/schemas/Game/properties/name)
  - [ ] Add Format to data types above Genre
  - [ ] Reorder based on API response
- [ ] Create JSON when validated
- [ ] Add websockets

### Bug reports/Pull Requests are encouraged and very helpful!

Once this is complete, you can use [Swagger Editor](https://editor-next.swagger.io/) or [OpenAPI Generators](https://openapi-generator.tech/docs/generators#client-generators) to generate the following native clients for the API. I may add some of these to releases, IDK yet.

[Swagger Editor](https://editor-next.swagger.io/)
* C# - C Sharp
* C# .Net2 - C Shart DotNet 2
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

[OpenAPI Generators](https://openapi-generator.tech/docs/generators#client-generators)
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
