# Repository
This repository contains the configuration files used during the demos for the
[OpenSIPS Summit Distributed 2020](https://www.opensips.org/events/Summit-2020Distributed/) conference.

# Demos
Demos performed during the Conference.

## Call management using the new Call API in OpenSIPS 3.1

 * [Presentation](https://docs.google.com/presentation/d/1AkXZJ5uj6TNPDpCd5Y6QxZxOUA1gKAXrDdgZoSWlzIY/edit?usp=sharing)
 * [Video](https://youtu.be/3h7WPW3xhi8?list=PLMMZA6ketvKqwzIR4txlKEqZtcPsrldr-&t=4220)
 * Repository tags
   * `call-api` tag contains the config used to run the [Call API](https://github.com/OpenSIPS/call-api) tool

## DTMF Handling in OpenSIPS 3.1

 * [Presentation](https://docs.google.com/presentation/d/17OGKh6WRd_LNGNVezWKi2iPAGzNenRQdA_991bQQkQE/edit?usp=sharing)
 * [Video](https://www.youtube.com/watch?v=uHFOB-J8GIQ&ab_channel=OpenSIPS)
 * Repository tags
   * `dtmf-conversion` tag contains the config used to convert in-band DTMFs to out-of-band SIP
   * `dtmf-pin` tag contains the config that requires a pin within the first 10 seconds of the call
   * `dtmf-transfer` tag contains the config that transfers the call when a key is pressed

## Media Exchanger in OpenSIPS 3.1

 * [Presentation](https://docs.google.com/presentation/d/1Y7mFXRfHlgFVX7cTZJj0A3Nn3_g-8AhJEOf1pTIwqek/edit?usp=sharing)
 * [Video](https://www.youtube.com/watch?v=NHzwOp2qYzQ&list=PLMMZA6ketvKqwzIR4txlKEqZtcPsrldr-&index=5&ab_channel=OpenSIPS)
 * Repository tags
   * `media-moh` tag contains the config used to play music on hold
