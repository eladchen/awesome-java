# awesome-java
A curated list of awesome Java topics.

### Specifications (https://jcp.org/en/jsr/all)

##### [JSR-196](https://jcp.org/aboutJava/communityprocess/mrel/jsr196/index2.html) Java Authentication Service Provider Interface for Containers or "JASPIC"
- [JASPIC by Arjan Tijms](https://jaspic.zeef.com/arjan.tijms)

##### [JSR-374](https://jcp.org/en/jsr/detail?id=374) Java API for JSON Processing 1.1
- [Overview of JSON Pointer](https://www.baeldung.com/json-pointer)

##### [JSR-375](https://javaee.github.io/security-spec) Java Authentication and Authorization Service or "JAAS" (Java EE Security API)
- [JAAS in Java EE is not the universal standard you may think it is](https://arjan-tijms.omnifaces.org/2014/02/jaas-in-java-ee-is-not-universal.html)
- [JAAS Tutorials by Oracle](https://docs.oracle.com/en/java/javase/13/security/jaas-tutorials.html)

##### [JSR-380](https://jcp.org/en/jsr/detail?id=380) Java Bean Validation v2.0
- [Bean Validation Specification](https://beanvalidation.org/2.0/spec/)
- [Reference Implementation](https://docs.jboss.org/hibernate/stable/validator/reference/en-US/html_single/)

##### JSR 374 & 375 examples:
 - [omnisecurity-jaspic-undertow](https://github.com/omnifaces/omnisecurity-jaspic-undertow/blob/master/src/main/java/org/omnifaces/security/JASPICAuthenticationMechanismX.java)
 - [javaee6-auth-example (JASPIC with ServerAuthModule or "SAM")](https://github.com/arjantijms/javaee6-auth-example)
 - [elytron-examples](https://github.com/wildfly-security-incubator/elytron-examples)
 - [wildfly](https://github.com/wildfly/wildfly/blob/master/undertow/src/main/java/org/wildfly/extension/undertow/security/JAASIdentityManagerImpl.java)
 - [jaspic-jaas-bridge](https://github.com/dstraub/jaspic-jaas-bridge)

### REST APIs
- [DTOs or not?](https://stackoverflow.com/questions/36174516/rest-api-dtos-or-not)
- [Is it bad to create different DTOs for REST request and response?](https://stackoverflow.com/q/37386758/1614199)
- [Representation - Domain Entity or DTOs](https://stackoverflow.com/q/38874746)
- [Reusing DTOs for request/response](https://stackoverflow.com/q/44349199)
- [Input model is too general](https://stackoverflow.com/q/49451725)
- [Introducing the PATCH method](https://craftsmen.nl/patching-jax-rs-3/)
- [PUT vs PATCH with real life examples](https://stackoverflow.com/a/34400076)
- [Please. Don't Patch Like That](https://williamdurand.fr/2014/02/14/please-do-not-patch-like-an-idiot/)
- [Resource Modeling](https://medium.com/@garrihovhannisyan/rest-api-guideline-resource-modeling-48e63807a1b3)
- [The Many Amazing Uses of JSON Schema: Client-side Validation](https://apisyouwonthate.com/blog/the-many-amazing-uses-of-json-schema-client-side-validation)
- [JSON API, OpenAPI and JSON Schema Working in Harmony](https://apisyouwonthate.com/blog/json-api-openapi-and-json-schema-working-in-harmony)
- [Creating Good API Errors in REST, GraphQL and gRPC](https://apisyouwonthate.com/blog/creating-good-api-errors-in-rest-graphql-and-grpc)
- [Patching JAX-RS](https://github.com/dscheerens/patching-jax-rs)
- [Zalando RESTful API and Event Scheme Guidelines](https://opensource.zalando.com/restful-api-guidelines/)

### Persistence
- [Separate domain model and the persistence layer](https://enterprisecraftsmanship.com/posts/having-the-domain-model-separate-from-the-persistence-model)
- [Encapsulating Data Access Layer](https://ayende.com/blog/4567/the-false-myth-of-encapsulating-data-access-in-the-dal)

##### Miscellaneous
- [How servlet containers all implement identity stores differently](https://arjan-tijms.omnifaces.org/2015/10/how-servlet-containers-all-implement.html)
- [Java EE (Jakarta) examples](https://github.com/eclipse-ee4j/jakartaee-tutorial-examples)
- [Java EE Security in Relation to JASPIC, JACC, and LoginModules/Realms](https://dzone.com/articles/ee-security-in-relation-to-jaspic-jacc-and-loginmo)
- [Implementing container authentication in Java EE with JASPIC](https://arjan-tijms.omnifaces.org/2012/11/implementing-container-authentication.html)
- [Transitioning Jakarta EE to the jakarta namespace](https://www.eclipse.org/lists/jakartaee-platform-dev/msg00250.html)
