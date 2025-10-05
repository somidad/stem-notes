# AMF related identities

```txt
            +------------------------------------------+
            | AMF ID                                   |
+------------------------------------------------------+
| GUAMI                                                |
+-----+-----+---------------+------------+-------------+---------+
| MCC | MNC | AMF Region ID | AMF Set ID | AMF Pointer | 5G-TMSI |
+-----+-----+---------------+------------+-------------+---------+
| 5G-GUTI                                                        |
+----------------------------------------------------------------+
                            | 5G-S-TMSI                          |
                            +------------+-------------+---------+

```

- MCC: 3 digits
- MNC: 2-3 digits
- AMF Region ID: 8 bits
- AMF Set ID: 10 bits
- AMF Pointer: 6 bits
- 5G-TMSI: 32 bits

**References**

1. 3GPP TS 23.003 GSM; UMTS; LTE; 5G; Numbering, addressing and identification
