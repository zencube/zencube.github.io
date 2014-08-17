# ZenCube
## Your life, your data, your cloud

A cloud ecosystem that gives you control over all that matters to you:

* Data: Documents, Photos, Music
* Communication: Email, Instant Messaging, Social networking
* Sharing & Collaboration

Carefully crafted, platform independent, build to empower you.

<blockquote id="quotd"></blockquote>
<script>
    var quotd = document.getElementById("quotd");
    var oReq = new XMLHttpRequest();
    oReq.onload = function() {
        quotd.textContent = this.responseText;
    };
    oReq.open("get", "http://quotes.zencu.be/", true);
    oReq.send();
</script>