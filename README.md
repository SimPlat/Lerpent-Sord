### Requirments
* Firefox
  * Extensions 
    * [JS injector](https://addons.mozilla.org/en-US/firefox/addon/javascript/)
    * [VPN](https://addons.mozilla.org/en-US/firefox/addon/hoxx-vpn-proxy/)
* [Auto-clicker](https://autoclicker.pro/download/)

### Steps
1. Run Firefox
2. Install the extensions and the auto-clicker
3. Navigate to the [poll page](https://poll.fm/10539880)
4. Add the following script to the injector(on poll page)
<pre>
function lerpent_sord(){
  $('#PDI_answer48790212').attr('checked', true); 
  document.getElementsByClassName("vote-button css-vote-button pds-vote-button")[0].click();
}

function back_to_poll(){
    window.location = "https://poll.fm/10539880/";
}

setTimeout(back_to_poll(), 4000);
lerpent_sord();
</pre>
5. Initialize the VPN by connecting to a random country
6. Run the autoclicker and set it up like [this](https://prnt.sc/s3hxon)  
_note: cursor potision(VPN's disconnect button potision) may vary depending on your monitor size_
7. Vote for the bois and submit(or simply refresh the page)
8. Open the VPN drop down menu by clicking on it and press F4

### How to stop
1. Stop the auto-clicker by pressing F4 again
2. Press `Esc` on the poll page to spot the refreshing
3. Navigate to the [extension menu](about:addons) and turn off the injector.
_note: you'll have to restart it again if you wanna repeat the process_
