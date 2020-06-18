<script>
function simpleTest() {
    window.webkit.messageHandlers.test.postMessage("Hello, world!");
}
function openDeeplink() {
    window.open("companionapp://host")    
}
</script>


<button onclick="simpleTest()">Simple test message</button>
<button onclick="openDeeplink()">Open deeplink</button>

<a href="javascript:close_window();">close</a>
<a href="https://ya.ru">Open ya.ru</a>
