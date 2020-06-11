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

<a href="https://ya.ru">Yandex test</a>
