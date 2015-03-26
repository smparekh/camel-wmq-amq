# camel-wmq-amq
A Camel IBM Websphere MQ to Active MQ Bridge Route
==================================================

Prerequisites
-------------

- IBM supplied OSGi jar files for MQ client installed on Fuse
  - IBM_MQ_INSTALL_DIR/java/lib/OSGi
- Running AMQ Broker
- wmq.to.amq.properties file in JBOSS_FUSE_INSTALL_DIR/etc/ with populated properties

Usage
-----
Once route is deployed use the IBM MQ Viewer to send test messages to your IBM MQ Queue. The messages will be picked up by the camel endpoint and delivered to the AMQ endpoint.

