<script>
function simpleTest() {
    window.webkit.messageHandlers.test.postMessage("Hello, world!");
}
</script>


<button onclick="printHelloWorld()">Simple test message</button>
