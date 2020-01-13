6.1 Core — spring-security-core.jar
This module contains core authentication and access-contol classes and interfaces, remoting support, and basic provisioning APIs. It is required by any application that uses Spring Security. It supports standalone applications, remote clients, method (service layer) security, and JDBC user provisioning. It contains the following top-level packages:

org.springframework.security.core
org.springframework.security.access
org.springframework.security.authentication
org.springframework.security.provisioning
6.2 Remoting — spring-security-remoting.jar

This module provides integration with Spring Remoting. You do not need this unless you are writing a remote client that uses Spring Remoting. The main package is org.springframework.security.remoting.

6.3 Web — spring-security-web.jar
This module contains filters and related web-security infrastructure code. It contains anything with a servlet API dependency. You need it if you require Spring Security web authentication services and URL-based access-control. The main package is org.springframework.security.web.

6.4 Config — spring-security-config.jar
This module contains the security namespace parsing code and Java configuration code. You need it if you use the Spring Security XML namespace for configuration or Spring Security’s Java Configuration support. The main package is org.springframework.security.config. None of the classes are intended for direct use in an application.

6.5 LDAP — spring-security-ldap.jar
This module provides LDAP authentication and provisioning code. It is required if you need to use LDAP authentication or manage LDAP user entries. The top-level package is org.springframework.security.ldap.

6.6 OAuth 2.0 Core — spring-security-oauth2-core.jar
spring-security-oauth2-core.jar contains core classes and interfaces that provide support for the OAuth 2.0 Authorization Framework and for OpenID Connect Core 1.0. It is required by applications that use OAuth 2.0 or OpenID Connect Core 1.0, such as client, resource server, and authorization server. The top-level package is org.springframework.security.oauth2.core.

6.7 OAuth 2.0 Client — spring-security-oauth2-client.jar
spring-security-oauth2-client.jar contains Spring Security’s client support for OAuth 2.0 Authorization Framework and OpenID Connect Core 1.0. It is required by applications that use OAuth 2.0 Login or OAuth Client support. The top-level package is org.springframework.security.oauth2.client.

6.8 OAuth 2.0 JOSE — spring-security-oauth2-jose.jar
spring-security-oauth2-jose.jar contains Spring Security’s support for the JOSE (Javascript Object Signing and Encryption) framework. The JOSE framework is intended to provide a method to securely transfer claims between parties. It is built from a collection of specifications:

JSON Web Token (JWT)
JSON Web Signature (JWS)
JSON Web Encryption (JWE)
JSON Web Key (JWK)
It contains the following top-level packages:

org.springframework.security.oauth2.jwt
org.springframework.security.oauth2.jose
6.9 OAuth 2.0 Resource Server — spring-security-oauth2-resource-server.jar
spring-security-oauth2-resource-server.jar contains Spring Security’s support for OAuth 2.0 Resource Servers. It is used to protect APIs via OAuth 2.0 Bearer Tokens. The top-level package is org.springframework.security.oauth2.server.resource.

6.10 ACL — spring-security-acl.jar
This module contains a specialized domain object ACL implementation. It is used to apply security to specific domain object instances within your application. The top-level package is org.springframework.security.acls.

6.11 CAS — spring-security-cas.jar
This module contains Spring Security’s CAS client integration. You should use it if you want to use Spring Security web authentication with a CAS single sign-on server. The top-level package is org.springframework.security.cas.

6.12 OpenID — spring-security-openid.jar
This module contains OpenID web authentication support. It is used to authenticate users against an external OpenID server. The top-level package is org.springframework.security.openid. It requires OpenID4Java.

6.13 Test — spring-security-test.jar
This module contains support for testing with Spring Security.