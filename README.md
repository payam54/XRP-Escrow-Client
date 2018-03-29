# XRP-Escrow-Client
Complete client-side, browser-based, independent Ripple XRP escrow creator and executor

This repository contains few web pages designed to help XRP holders to check their account transactions, escrow XRP to future dates, and release the escrows when the release date has come.

<h2 style='color:red;'>READ THIS BEFORE USING THE TOOL</h2>
<ul>
  <li>Only use this tool in a trusted computer, and <strong>private browsing mode</strong></li>
  <li>Chrome is recommended, but it works prefectly on FireFox, Brave, Edge and Safari</li>
  <li>Your Secret Key is not transmitted over the network. It gets signed (encrypted) by JS library and then transmitted through Web Socket Secure (WSS). However, <strong>never expose your secret key</strong></li>
  <li>Always start testing with little amounts and short periods, like 0.01 XRP for 5 minutes. Learn how to release it, then go for higher amounts and longer periods. I would not take responsibility of your Gizillion XRP, escrowed to year 2099.</li>
  <li>Take and use this tool as is. This is MIT license tool so please use it on your own responsibility</li>
</ul>

## Notes:

<ul>
  <li>There is no need to install any additional software such as NodeJS</li>
  <li>This is based on <a href='https://ripple.com/build/rippleapi-beginners-guide/#rippleapi-in-web-browsers' target='_blank'>RippleAPI Beginners Guide</a> and uses <a href='https://github.com/ripple/ripple-lib/releases' target='_blank'>riple-api.js</a> library from Ripple itself. Therefore it's considered safe.</li>
  <li>According to the same instruction, it is required to include lodash.js library. That's why you find lodash.js included there.</li>
  <li>If you are too cautious and are afraid to lose the js libraries in future (which is kinda impossible), just go ahead and download them into the same folder along with this html pages, then replace the urls in header to only file names.</li>
  <li>I didn't add graphics into the pages because wanted them to be only one file and independent. Yes, looks a bit ugly because I'm not a CSS designer, but works nice. I hope collaborators help to make it cooler and responsive (in one html file)</li>
</ul>



