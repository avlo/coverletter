# Nick Avlonitis
## IOTA interest and work
Current goal is developing IOTA SC (smart-contract) POC (proof-of-concept) for MQTT-event (sensor data) triggered micro-payments.

Using SC DonateWithFeedback reference implementation written in Go(lang) directly in WASP as my latest understanding is that the WASM (Rust) SC platform does not currently exist.

First successful MQTT-pub/sub POC's were written in Go atop Gohornet as a starting point.  These were of course, non-SC's as per Gohornet limitation.  Success there then lead me to first development milestone of integrating MQTT broker into Goshimmer.  With the help of IF member Angelo Capossele [Goshimmer MQTT plugin is now functional](https://discord.com/channels/397872799483428865/603609366452502538/805195580686204978) and tested in my [Goshimmer feat/mqtt branch](https://github.com/iotaledger/goshimmer/compare/feat/mqtt...avlo:feat/mqtt-add_topic_utils?expand=1).  It may be of interest to you that after working with Angelo on this for ~2 weeks, he [recommended me to the GoShimmer X-Team](https://discord.com/channels/397872799483428865/603609366452502538/805550391852531732), of which [I am now a member](https://discord.com/channels/397872799483428865/702466814256611359/805557689974259742).

My Current development status is testing DonateWithFeedback smart contract deployment to ensure I'm correctly understanding the role of all components (goshimmer w/ waspconn plugin, wasp, wasp-cli & wasp-cluster) my making small changes to the exsiting SC and once that's confirmed working, the first test of MQTT pub-sub into SC logic will begin.

Per my resume you'll see that I've been in enterprise application development for ~20 years with all skillsets and roles listed.  My strongest and most familiar language is Java, however the software engineering process and design principles are language agnostic.  I'm relatively new to GoLang (~4 months experience so far) but it's strengths, consiseness and ease-of-use are clear and incredibly attractive from a developers perspective and I've found that the greatest learning curve is "unlearning" the way related things are done in Java.

Somewhat unrelated, I've got an [iotaledger/iota.go bug PR merged into master branch](https://github.com/iotaledger/iota.go/pull/221/) in the recent past as well as upcoming documenation PR's for WASP setup and tools use once my MQTT-triggered micro-payments POC is completed.
