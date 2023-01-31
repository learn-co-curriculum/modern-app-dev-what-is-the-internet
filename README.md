# What is the Internet?

## Learning Goals

- Give an overview of the internet.
- Internet standards.
- Describe protocols.

## What is a Computer Network and the Internet?

A network is any group of interconnected entities. A computer network is an
interconnected system of computers. This kind of network enables communication
and resource sharing between devices.

The Internet is a system of multiple computer networks connected together.
Devices in a workplace or home are connected to each other via a router which
allows the devices to communicate with all the other computers on the internet.

Here’s a [submarine cable map](https://www.submarinecablemap.com/) of the cables
that transmit signals across continents and a
[mobile internet map](https://labs.mapbox.com/labs/twitter-gnip/brands/#3/26.35/-20.21)
that shows the scale of the network.

## Internet Standards

Standards allow hardware and software from different vendors connected through
the internet to interoperate. This allows vendors to focus on business logic
instead of coming up with new protocols (general pattern for communication).

The [Internet Engineering Task Force](https://www.ietf.org/about/introduction/)
(IETF), a sub-body of the [Internet Society](https://www.internetsociety.org/),
works on formalizing standards. Proposals for new standards are published
through
[Request for Comments](https://en.wikipedia.org/wiki/Request_for_Comments)
(RFC). Anyone can create and submit RFCs for consideration by the IETF. Once a
new RFC is submitted, experts review, discuss, and if everything checks out,
adopts the proposal as a new standard.

## Protocols

A protocol defines rules for devices to exchange data. The devices follow a
general pattern to share data with each other. Different protocols enable unique
forms of communication. Some of the common protocols are:

- Transmission Control Protocol (TCP): This protocol ensures that any data
  exchanged between devices is not corrupted.
- User Datagram Protocol (UDP): This protocol trades off data exchange guarantee
  for faster data exchange. It’s used for services where some data loss is
  acceptable such as video streaming services which can drop a few frames and
  still be perfectly watchable.
- HyperText Transfer Protocol (HTTP): This is a protocol that defines how
  messages should be exchanged between devices connected to the web.

## Packets

Computers break down large amount of information into smaller units called
packets before sending them across networks. Links between networks are shared
by multiple systems. Sending messages in smaller chunks allows them to be
transmitted more evenly across links instead of a large amount of data hogging
up specific links.

## Conclusion

We have learned about the Internet in this lesson, how standards are developed,
and some of the common protocols used for data exchange between devices.
