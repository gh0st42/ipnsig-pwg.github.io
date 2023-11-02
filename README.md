# Bundle Protocol Implementations

This document tries to list the various features of Bundle Protocol (RFC5050, RFC9171) Implementations. It is based on reading documentation or information from the developers. When a cell is empty, it means not verified or unknown, maybe not implemented but not confirmed (to be not implemented).

No guarantee of accuracy. If you have modifications to suggest, please send a PR or write an issue at the [source github repo](https://github.com/ipnsig-pwg/ipnsig-pwg.github.io) or [send email](mailto:marc.blanchet@viagenie.ca).

| Feature/Stack | Subfeature | [ION](https://sourceforge.net/projects/ion-dtn/) | [IONE](https://sourceforge.net/projects/ione/) | [HDTN](https://github.com/nasa/HDTN/wiki/HDTN-Implementation-Features) | [uD3TN](https://gitlab.com/d3tn/ud3tn) | [DTNME](https://github.com/nasa/DTNME) | [BPLib/CFS](https://github.com/nasa/bplib) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [BPv6](https://www.rfc-editor.org/rfc/rfc5050) | | Y | Y | Y | Y | Y | Y |
|  | [TCPCLv3/BPv6](https://www.rfc-editor.org/rfc/rfc7242) | Y | Y | Y | Y | Y | |
|  | [UDPCL/BPv6](https://www.rfc-editor.org/rfc/rfc7122) | Y | Y | Y | N | Y |  |
|  | [LTPv1/BPv6](https://www.rfc-editor.org/rfc/rfc5326) | Y | Y | Y | N | Y |  |
|  | [BPSEC/BPv6](https://www.rfc-editor.org/rfc/rfc6257) | Y | Y | N | N | N |  |
|  | Custody BPv6 | Y | Y | Y | N | Y |  |
| [BPv7](https://www.rfc-editor.org/rfc/rfc9171) | | Y | Y | Y | Y | Y | Y |
|  | [TCPCLv3/BPv7](https://www.rfc-editor.org/rfc/rfc7242) | Y | Y | Y | Y | Y |  |
|  | [TCPCLv4/BPv7](https://www.rfc-editor.org/rfc/rfc9174) | Y | Y | Y | [N](https://gitlab.com/d3tn/ud3tn/-/issues/40) | Y |  |
|  | [UDPCL/BPv7](https://datatracker.ietf.org/doc/draft-sipos-dtn-udpcl/) | Y | Y | Y | N | Y |  |
|  | LTPv1/BPv7 | Y | Y | Y | N | Y |  |
|  | [BPSEC/BPv7](https://www.rfc-editor.org/rfc/rfc9172) | Y | Y | Y | N | N |  |
| | Custody (with [BIBE](https://datatracker.ietf.org/doc/draft-ietf-dtn-bibect/)) BPv7 | Y | Y | N |  | Y |  |
| | [RTP/BPv7](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjrn92gvJaCAxXxFFkFHXY5A1QQFnoECAwQAQ&url=https%3A%2F%2Fcwe.ccsds.org%2Fsis%2Fdocs%2FSIS-MIA%2FDraft%2520Documents%2FRTP%2520over%2520DTN%2520for%2520Video%2F766x3r0_JPM_RID_Answer_TEMP.doc&usg=AOvVaw3YVH8gKoTvgPLxiUC7PgPq&opi=89978449) | N | N | Y | N |  |  |
| [CGR](https://datatracker.ietf.org/doc/html/draft-burleigh-dtnrg-cgr) | | Y | Y | Y | N | N |  |
| [CCSDS SPP](https://public.ccsds.org/Pubs/133x0b2e1.pdf) | | N | N | N | Y |N |  |
| [Bundle Streaming Service Protocol](https://public.ccsds.org/Pubs/730x2g1.pdf) | | Y | Y | N | N | N |  |
| [Asynchronous Message Service](https://public.ccsds.org/Pubs/735x1b1.pdf) | | Y | Y | N | N | N |  |
| IPv6 (for CLAs) | | N | Y | N | Y | N |  |
| [IPND](https://datatracker.ietf.org/doc/draft-johnson-dtn-ipnd/) | | Y | Y | N | N | N |  |
| [CFDP](https://public.ccsds.org/Pubs/727x0b5.pdf) | | Y | Y | N | N | Y |  |

## Acknowledgments
Thanks to Scott Burleigh(ION, IONE), Scott Johnson(IONE), Felix Walter(uD3TN), Joshua Deaton(DTNME) and HDTN team for providing information on their implementations.

## Last Version
[See last commit](https://github.com/ipnsig-pwg/ipnsig-pwg.github.io/commits/main)
