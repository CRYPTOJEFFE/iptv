# EL JEFFE integration

Run `node eljeffe/build-catalog.cjs US` with Node.js 20+ to build channel JSON and a US playlist, or replace US with another ISO country code. The builder reads the official IPTV-org API. Exact channel IDs are required; unmatched streams are reported rather than guessed. Browser playlist exports omit HTTP URLs and custom-header streams. Playback availability still depends on the source, region, and CORS.

The complete EL JEFFE resource collection is maintained in [our Awesome IPTV fork](https://github.com/CRYPTOJEFFE/awesome-iptv/blob/master/ELJEFFE.md). This companion code adds browser interoperability without modifying upstream channel schemas or stream files. Upstream data is CC0; the original EL JEFFE adapter is also dedicated under CC0-1.0.
