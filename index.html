<div class="album">

    <div class="cover"></div>

    <h1>Il violoncello nella fortezza</h1>
    <h2>Presentimento (Luis Fader)</h2>

    <audio id="audio" src="violoncello.mp3"></audio>

    <div class="controls">
        <button onclick="prev()">⏮</button>
        <button onclick="play()">▶</button>
        <button onclick="pause()">⏸</button>
        <button onclick="stop()">⏹</button>
        <button onclick="next()">⏭</button>
    </div>

    <div class="progress-container" onclick="seek(event)">
        <div class="progress" id="progress"></div>
    </div>

</div>

<style>
.album {
    width: 360px;
    margin: auto;
    text-align: center;
    font-family: sans-serif;
    color: white;
}

body {
    background: radial-gradient(circle, #111, #000);
}

.cover {
    width: 100%;
    height: 360px;
    background: url('cover.jpg') center/cover no-repeat;
    border-radius: 20px;
    box-shadow: 0 0 30px rgba(255,150,0,0.5);
}

h1 {
    font-size: 18px;
    margin: 10px 0 5px;
    color: gold;
}

h2 {
    font-size: 14px;
    color: #aaa;
    margin-bottom: 10px;
}

.controls button {
    background: gold;
    border: none;
    margin: 5px;
    padding: 10px;
    border-radius: 50%;
    cursor: pointer;
    font-size: 18px;
}

.progress-container {
    width: 90%;
    height: 6px;
    background: #333;
    margin: 10px auto;
    cursor: pointer;
}

.progress {
    height: 100%;
    width: 0%;
    background: gold;
}
</style>

<script>
const tracks = ["violoncello.mp3"];
let current = 0;

const audio = document.getElementById("audio");
const progress = document.getElementById("progress");

function loadTrack(i) {
    audio.src = tracks[i];
    audio.load();
}

function play() {
    audio.play().catch(e => alert("Error al reproducir"));
}

function pause() {
    audio.pause();
}

function stop() {
    audio.pause();
    audio.currentTime = 0;
}

function next() {
    current = (current + 1) % tracks.length;
    loadTrack(current);
    play();
}

function prev() {
    current = (current - 1 + tracks.length) % tracks.length;
    loadTrack(current);
    play();
}

audio.addEventListener("timeupdate", () => {
    const percent = (audio.currentTime / audio.duration) * 100;
    progress.style.width = percent + "%";
});

function seek(e) {
    const width = e.currentTarget.clientWidth;
    const clickX = e.offsetX;
    audio.currentTime = (clickX / width) * audio.duration;
}
</script>
