# IMPORTANT: NOT COMPLETE
I am hand crafting the OpenAPI spec from IGDB's docs, so there is a good chance there are mistakes.

The response types have yet to be validated.

The Excel spreadsheets have been created to speed up the copy process, by auto-crafting the YAML properties of a component based on the copied table from IGDB's docs.

TODO:
1. Finish component schemas
2. Finish Paths
3. Create JSON when in a "filled-out" state
4. Enhance interlinking before GameVersionFeature (Ex: Reference ID for Game will $ref: /components/schemas/Game/properties/name)
5. Add Format to data types above Genre
5. Validate against API responses

Below are data types that have been converted to match the OpenAPI specs Above Genre, because I am learning the OAI spec as I go

| IGDB Type           	| OpenAPI Compatable Type 	|
|---------------------	|-------------------------	|
| uuid                	| string                  	|
| array [of anything] 	| array of undefined type 	|
| unix time stamp     	| number                  	|
| date					| string					|
| integer				| number					|

Bug reports/Pull Requests are encouraged and very helpful!

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