# DSH Customer Documentation - ToC
## Tenant --
###  1. Platform overview [Thomas]
  1. [Tenant/multi tenant](Multi-Tenant)
  2. [Docker container](Docker-Container)
  3. [Datastreams](Datastreams) own stream parts
###  2. Authentication & Authorisation [Dominique]
  1. [Flow requesting a default token](Requesting-a-Token) Howto request a token - OK snowball/docs/aut....
  2. [Specific ACL's](ACLs) types of ACLS? - OK snowball/docs/aut.... 
  3. [User management / keycloak](User-Management) (not in scope for today)

###  3. Topics/streams [Hans]
  1. [public, platform/internal, private](Stream-Types) [Dominique] - OK KPN-Cust-Docs repo
  2. [Contract and configuration](Contract-and-configuration) [Dominique] Stream conf & stream contract - NOK
  3. [Message structure (protobuf)](Message-structure) -  OK 80% -- [Envelopes (Protobuf)](Envelopes) [Dominique] 
  4. [MQTT adapter (overview)](MQTT-adapter)  [Bart] how are datastreams mapped on MQTT
     1. [Topics (mqtt specific)](Topics-MQTT) Mapping Kafka - MQTT
     2. [retained messages](retained-messages) - retained messages in MQTT, constrain yourself, how to delete - OK 80%
     3. How Key envelope ID are filled in for incomming messages

###  4. Deploying a container/nicodemus (overview) [Hans]
  1. [Tenant environment (netwerk setup etc)](Tenant-environment) [Bram] Tenant networking constraints - 20%
  2. [Containerization](Containerization)  [Bram] requirements for a container to run on DSH - 40%
  3. [Container registry](Container-registry) [Bram] how make container available for dsh - 40% (oefening)
  4. [PKI](PKI) [Dominique] How to connect to Kafka? certificates & configuration - 90%
  5. [VPN](VPN) [Bram]- NOK
  6. [Tenant limits & allocations(overview)](Tenant-limits-&-allocations) [Yennick] - NOK
     1. [Services](Services) app-def language description [Dominique]
     2. [Volumes](Volumes)
     3. [Vhosts](Vhosts)
     4. [Private stream](Private-Stream)
     5. [Users](Users) (not is scope for today)

### 5. UMP [Yennick] - LATER

###  6. Platform services [Hans] 
  1. [Tracing](Tracing) [Dominique] - OK 
  2. [Monitoring](Monitoring) [Roel R] - NOK
  3. [Logs](Logs) [Theun] - LATER
  4. [Objectstore](Objectstore) [Radek] - NOK

###  7. 3th party services [Roel V] 
  1. [Cloud provider explanation](Cloud-provider)
  2. [Database as a service](Database-aaS)


###  9. Libaries/SDK [Hans]
  1. [Example Java](Java) [?] - NOK
  2. [Example Python](Python) [Michiel] - NOK
  3. [Example Go](Go) [Dominique] - LATER

###  10. Service process (SRE proces) [Martin]
  1. [Getting up and running](Getting-up-and-running)
  2. [What if I have a problem?](Have-a-problem?)
  3. [What if I want to request a thing?](Request-a-thing)

## Device API
  1. [Flow requesting a default token](Requesting-a-Token) Howto request a token - OK snowball/docs/aut....
  2. [Specific ACL's](ACLs) types of ACLS? - OK snowball/docs/aut....  
  3. [Connect (token)](Connect) [Bart] connect authentication & conditions - NOK
  4. [Pub/sub topic](PubSub-topic) [Bart] - ZIE BOVEN 80%
  5. [Retain messages](Retain-messages) [Bart] - Supported, special wildcard publish - NOK
  6. [Scale](Scale) [Bart] throttling - NOK
  7. [Error handling](Error-handling) [Bart & Dominique] regular errors (ping-pong expired) eplained - NOK 

