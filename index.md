---
uid: index
---

OSIsoft Message Format 
======================



# Overview

The OSIsoft Message Format (OMF) defines a set of message headers and bodies that can be used to generate messages for ingestion into a compliant back-end system.

OMF can be used to develop data acquisition applications on platforms and in languages for which there are no supported OSIsoft libraries.

OMF itself does not define or depend on any particular binary message protocol (HTTP, AMQP, Kafka, etc.) It is instead based on an abstract message type, 
where a message consists of a set of key / value pairs, called the headers, and a binary payload, called the body. OMF messages can thus be constructed 
using any message protocol that defines headers and bodies. For up to date information on the specific binary protocols currently supported by OSIsoft 
systems, consult the OSIsoft Cloud Services and PI Web API documentation.

Please note that anything defined in this document, such as keywords and enumerated
values, is treated as case insensitive. Case sensitivity for all user specified values
is determined by the rules of the backend system.

# OMF Specification (1.1)

- [Whats New](xref:whatsNewv11)
- [Message Headers](xref:headersv11)
- [Message Types](xref:messageTypesv11)
- [Type Messages](xref:typeMessagesv11)     
  - [Link Type](xref:linkTypev11)
  - [Type Properties and Formats](xref:typePropertiesAndFormatsv11)	 
  - [Type Example](xref:typeExamplev11)
- [Container Messages](xref:containerMessagesv11)
  - [Container Example](xref:containerExamplev11)
- [Data Messages](xref:dataMessagesv11)	 
  - [Data Example](xref:dataExamplev11) 

# HTTP Behaviors

While the OMF specification does not define a particular binary message protocol, OSIsoft 
systems accepting OMF over HTTP conform to a set of behaviors described in this section.

- [Message Size](xref:messageSize)
- [HTTP Status Codes](xref:httpStatusCodes)

