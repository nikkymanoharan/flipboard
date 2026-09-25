# FlipBoard sender

A page for sending messages to a home split-flap board from anywhere.

It contains no keys or addresses. A phone is paired from the board's home
control panel with a private link. Messages are then encrypted on the phone
(AES-256-GCM) before they leave it, and the board ignores anything that
isn't encrypted with its key.

Built on [FlipOff](https://github.com/magnum6actual/flipoff) by magnum6actual.
