npm install dplayer --save
yarn add dplayer
<link rel="stylesheet" href="DPlayer.min.css" />
<div id="dplayer"></div>
<script src="DPlayer.min.js"></script>
const dp = new DPlayer({
    container: document.getElementById('dplayer'),
    video: {
        url: 'demo.mp4',
    },
});
