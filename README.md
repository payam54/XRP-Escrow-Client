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
  <li>According to the same instruction, it is required to include <a href='https://www.npmjs.com/package/lodash' target='_blank'>lodash.js</a> library. That's why you find lodash.js included there.</li>
  <li>If you are too cautious and are afraid to lose the js libraries in future (which is kinda impossible), just go ahead and download them into the same folder along with this html pages, then replace the urls in header to only file names.</li>
  <li>I didn't add graphics into the pages because wanted them to be only one file and independent. Yes, looks a bit ugly because I'm not a CSS designer, but works nice. I hope collaborators help to make it cooler and responsive (in one html file)</li>
</ul>

## Create Escrow Instruction:

<ol>
  <li>Download all three html files from html directory:XRP_Account_Check.html, Create_Escrow.html, Finish_Escrow.html</li>
  <li>Open 'XRP_Account_Check' page and put your XRP wallet address into it, then click on 'Get Summary' button. This will show you if your browser is able to communicate with Ripple servers</li>
  <li>You can see list of last 50 transactions using the second button. This is useful when transaction info is lost, or some transactions were failed and you need to know why</li>
  <li>Make sure your computer date and time is accurate</li>
  <li>Open 'Create_Escrow' page and fill all fields. Start with very small amount and very short period</li>
  <li>There is a 'Create Escrow' button below the page, but before click, double check calculated escrow finish time</li>
  <li>You will see a confirmation page after clicking on 'Create Escrow' button. Read it and confirm it.</li>
  <li>The Escrow Creation result will show up on the screen with green background. Keep that info till time of finishing the escrow</li>
</ol>


## Finish Escrow Instruction:

<ol>
   <li>Wait for the time that escrow can be released</li>
   <li>Open 'Finish_Escrow' page and put the XRP address that use used to open the escrow. Then click on 'Show Created Escrows'</li>
   <li>This list contains all successful created escrows regardless of their execution status.</li>
   <li>Find the escrow creation transaction ID as you saved when created the escrow; click on 'info' button</li>
   <li>If everything ready, you will see an 'Execute' button. But you need to put your secret key in the second filed first</li>
   <li>Click on Execute. You will see the results almost immediately</li>
</ol>
   
HDR7 4/26/18
