# ethwaterloo
FireTV application for ETH Waterloo

<img src="matic.png" height="250" width="250">

An Alexa Skill and backend platform that facilitates the recycle of Este Lauder cosmetics. In addition users can donate to breast cancer and post selfies from the Kiosk to social media to raise awareness.

## Installation
`git clone [this repo]`

 Follow instructions for making your first Alexa Skill on the Amazon Developers Console. This will get you env setup to upload the code in this repo.

## VoiceFlow Diagram
<pre>


      +---------------+
      |               |        +------------------------+
      |               |        |                    x   |
      |    ENS  +     |        |                        |
      |         |     |        |                    x   |
      |         +--------+-----------&gt;                  |
      |               +  |     |   +   DApp             |
      |               +--|------------&gt;                 |
      +---------------+  |     |                        |
                         |     |                        |
                         |+    +------------------------+
                         ||
                         ||
                        &lt;+|               +---------------------------+
                      +   |               |  Ethereum                 |
&lt;---------------------+   +--------------&gt;|---------------------------|
                                          |                           |
                                          |                           |
                                          |                           |
                                          |                           |
                                          |                           |
                                          |                           |
                                          |                           |
                                          |                           |
                                          +---------------------------+</pre>

## MySQL setup
`mysql --host=123.45.67.3 --user=root --password=password elc`

'cd' to the project folder

*Wait for build to complete sucessfully*

`Python run ...`

# Try it!

Take a look at our Beta web app [HERE!](http://www..com/)

[![Build Status](https://travis-ci.org/coderrick/drill.svg?branch=master)](https://travis-ci.org/coderrick/drill)
