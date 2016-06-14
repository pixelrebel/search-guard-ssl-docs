<!---
Copryight 2016 floragunn UG (haftungsbeschränkt)
-->

# Enabled SSL ciphers and protocols

By default the following SSL cipher suites and protocols are enabled:

<pre>
//https://wiki.mozilla.org/Security/Server_Side_TLS
"TLS_ECDHE_RSA_WITH_AES_128_GCM_SHA256",
"TLS_ECDHE_ECDSA_WITH_AES_128_GCM_SHA256",
"TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384",
"TLS_ECDHE_ECDSA_WITH_AES_256_GCM_SHA384",
"TLS_DHE_RSA_WITH_AES_128_GCM_SHA256",
"TLS_DHE_DSS_WITH_AES_128_GCM_SHA256",
"TLS_DHE_DSS_WITH_AES_256_GCM_SHA384",
"TLS_DHE_RSA_WITH_AES_256_GCM_SHA384",
"TLS_ECDHE_RSA_WITH_AES_128_CBC_SHA256",
"TLS_ECDHE_ECDSA_WITH_AES_128_CBC_SHA256",
"TLS_ECDHE_RSA_WITH_AES_128_CBC_SHA",
"TLS_ECDHE_ECDSA_WITH_AES_128_CBC_SHA",
"TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384",
"TLS_ECDHE_ECDSA_WITH_AES_256_CBC_SHA384",
"TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA",
"TLS_ECDHE_ECDSA_WITH_AES_256_CBC_SHA",
"TLS_DHE_RSA_WITH_AES_128_CBC_SHA256",
"TLS_DHE_RSA_WITH_AES_128_CBC_SHA",
"TLS_DHE_DSS_WITH_AES_128_CBC_SHA256",
"TLS_DHE_RSA_WITH_AES_256_CBC_SHA256",
"TLS_DHE_DSS_WITH_AES_256_CBC_SHA",
"TLS_DHE_RSA_WITH_AES_256_CBC_SHA"
"TLSv1.1"
"TLSv1.2"
</pre>

When OpenSSL is used then `SSLv2Hello` is also enabled