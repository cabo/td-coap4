td-coap4
========

This repo contains the Test Descriptions for ETSI plugtest CoAP#4.

For each area of testing, there is a pair of files:

| Area              | source file                                                            | html version                                                           |
| ---               | ---                                                                    | ---                                                                    |
| Base CoAP         | [base.yml](http://github.com/cabo/td-coap4/blob/master/base.yml)       | [base.html](http://rawgithub.com/cabo/td-coap4/master/base.html)       |
| Block and Observe | [block.yml](http://github.com/cabo/td-coap4/blob/master/block.yml)     | [block.html](http://rawgithub.com/cabo/td-coap4/master/block.html)     |
| Link format       | [link.yml](http://github.com/cabo/td-coap4/blob/master/link.yml)       | [link.html](http://rawgithub.com/cabo/td-coap4/master/link.html)       |
| DTLS              | [dtls.yml](http://github.com/cabo/td-coap4/blob/master/dtls.yml)       | [dtls.html](http://rawgithub.com/cabo/td-coap4/master/dtls.html)       |
| 6LoWPAN           | [6lowpan.yml](http://github.com/cabo/td-coap4/blob/master/6lowpan.yml) | [6lowpan.html](http://rawgithub.com/cabo/td-coap4/master/6lowpan.html) |

In the test descriptions, the following shorthands are used for the references:

| shorthand  | document                                                                                |
| ---        | ---                                                                                     |
| \[COAP]    | [draft-ietf-core-coap-18](http://tools.ietf.org/html/draft-ietf-core-coap-18.txt)       |
| \[OBSERVE] | [draft-ietf-core-observe-12](http://tools.ietf.org/html/draft-ietf-core-observe-12.txt) |
| \[BLOCK]   | [draft-ietf-core-block-14](http://tools.ietf.org/html/draft-ietf-core-block-14.txt)     |
| \[LINK]    | [RFC 6690](http://tools.ietf.org/html/rfc6690.txt)  (CoRE link format)                  |
| \[ND]      | [RFC 6775](http://tools.ietf.org/html/rfc6775.txt)  (6LoWPAN ND)                        |
| \[IPHC]    | [RFC 6282](http://tools.ietf.org/html/rfc6282.txt)  (6LoWPAN HC)                        |
| \[FORMAT]  | [RFC 4944](http://tools.ietf.org/html/rfc4944.txt)  (6LoWPAN base format)               |

The following parameters have not yet been assigned by IANA but are
needed for the DTLS tests:

* 0xC0 0xAC as the cipher suite identifier for TLS_ECDHE_ECDSA_WITH_AES_128_CCM_8

Note that, for RPK, we now have the [final assignments](http://www.iana.org/assignments/tls-extensiontype-values/tls-extensiontype-values.xhtml):

  * client_certificate_type: 19
  * server_certificate_type: 20

