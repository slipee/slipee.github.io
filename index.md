<script>
function simpleTest() {
    window.webkit.messageHandlers.test.postMessage("Hello, world!");
}
</script>


<button onclick="simpleTest()">Simple test message</button>

<a href="https://ya.ru">Yandex test</a>

<a href="companionapp://host">Deeplink test</a>
