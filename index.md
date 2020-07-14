<script>
function simpleTest() {
    window.webkit.messageHandlers.test.postMessage("Hello, world!");
}
function openDeeplink() {
    window.open("companionapp://host")    
}
function passArray() {
    window.webkit.messageHandlers.test.postMessage([1, 2, 3]);
}
    
function unlinkDevice() {
    window.CompanionApp.unlinkDevice({"device_id": 123})
}
</script>


<button onclick="simpleTest()">Simple test message</button>

<button onclick="openDeeplink()">Open deeplink</button>

<button onclick="passArray()">Pass array</button>

<button onclick="window.CompanionApp.getDeviceConnectionData()">getDeviceConnectionData</button>

<button onclick="unlinkDevice()">Test native js with json</button>

<a href="javascript:close();">close</a>

<a href="https://ya.ru">Open ya.ru</a>
