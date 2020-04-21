### Requirments
* Firefox
  * Extensions 
    * [JS injector](https://addons.mozilla.org/en-US/firefox/addon/javascript/)
    * [VPN](https://addons.mozilla.org/en-US/firefox/addon/hoxx-vpn-proxy/)
* (Extra) Auto-clicker

### Steps
1. Run Firefox
2. Install the extensions
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
5. Initialize the VPN
6. Vote for the bois and submit(or simply refresh the page)
