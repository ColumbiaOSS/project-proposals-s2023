# WildFly

Description of the project:

WildFly Elytron is a security framework used to unify security across the entire application server. The elytron subsystem enables a single point of configuration for securing both applications and the management interfaces. WildFly Elytron also provides a set of APIs and SPIs for providing custom implementations of functionality and integrating with the elytron subsystem.

In addition, there are several other important features of the WildFly Elytron:

Stronger authentication mechanisms for HTTP and SASL authentication.

Improved architecture that allows for SecurityIdentities to be propagated across security domains and transparently transformed ready to be used for authorization. This transformation takes place using configurable role decoders, role mappers, and permission mappers.

Centralized point for SSL/TLS configuration including cipher suites and protocols.

SSL/TLS optimizations such as eager SecureIdentity construction and closely tying authorization to establishing an SSL/TLS connection. Eager SecureIdentity construction eliminates the need for a SecureIdentity to be constructed on a per-request basis. Closely tying authentication to establishing an SSL/TLS connection enables permission checks to happen BEFORE the first request is received.

A secure credential store that replaces the previous vault implementation to store clear text credentials.

The new elytron subsystem exists in parallel to the legacy security subsystem and legacy core management authentication. Both the legacy and Elytron methods may be used for securing the management interfaces as well as providing security for applications.

Good First Bug: [link](https://issues.redhat.com/browse/ELY-2310?filter=12383825)
