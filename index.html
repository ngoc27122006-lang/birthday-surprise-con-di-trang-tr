<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>😈 CHAOS MODE</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        overflow: hidden;
        background: radial-gradient(circle at center, #ff00ff, #000020);
        animation: bg 6s infinite alternate;
        cursor: pointer;
    }

    @keyframes bg {
        0% { background: radial-gradient(circle, #ff00ff, #000020); }
        50% { background: radial-gradient(circle, #00ffff, #200020); }
        100% { background: radial-gradient(circle, #ffff00, #001020); }
    }

    .photo {
        position: absolute;
        border-radius: 20px;
        box-shadow:
            0 0 20px rgba(255,255,255,0.7),
            0 0 40px rgba(255,0,255,0.8);
        animation:
            fall linear,
            spin linear infinite,
            pulse 1.5s infinite alternate;
    }

    @keyframes fall {
        from { transform: translateY(-200px); }
        to { transform: translateY(120vh); }
    }

    @keyframes spin {
        from { rotate: 0deg; }
        to { rotate: 360deg; }
    }

    @keyframes pulse {
        from { filter: hue-rotate(0deg) saturate(150%); }
        to { filter: hue-rotate(360deg) saturate(300%); }
    }

    .shake {
        animation: shake 0.15s infinite;
    }

    @keyframes shake {
        0% { transform: translate(0,0); }
        25% { transform: translate(8px,-8px); }
        50% { transform: translate(-8px,8px); }
        75% { transform: translate(8px,8px); }
        100% { transform: translate(0,0); }
    }

    .flash {
        position: fixed;
        inset: 0;
        background: white;
        opacity: 0;
        pointer-events: none;
    }

    .sparkle {
        position: absolute;
        width: 8px;
        height: 8px;
        border-radius: 50%;
        animation: sparkle 1s linear forwards;
    }

    @keyframes sparkle {
        from { transform: scale(1); opacity: 1; }
        to { transform: scale(3); opacity: 0; }
    }
</style>
</head>
<body>

<div id="flash" class="flash"></div>

<script>
const images = ["dim1.jpg", "dim2.jpg", "dim3.jpg"];

function rand(min, max) {
    return Math.random() * (max - min) + min;
}

function spawnImage(x = rand(0, innerWidth)) {
    const img = document.createElement("img");
    img.src = images[Math.floor(Math.random() * images.length)];
    img.className = "photo";

    const size = rand(120, 260);
    img.style.width = size + "px";
    img.style.left = x + "px";
    img.style.top = "-250px";

    img.style.animationDuration =
        rand(3, 8) + "s, " +
        rand(4, 10) + "s, 1.5s";

    document.body.appendChild(img);
    setTimeout(() => img.remove(), 12000);
}

// mưa ảnh liên tục
setInterval(() => spawnImage(), 350);

// click = bùng nổ
document.addEventListener("click", (e) => {
    // flash
    const flash = document.getElementById("flash");
    flash.style.opacity = 0.9;
    setTimeout(() => flash.style.opacity = 0, 100);

    // rung
    document.body.classList.add("shake");
    setTimeout(() => document.body.classList.remove("shake"), 400);

    // spam ảnh
    for (let i = 0; i < 8; i++) {
        spawnImage(e.clientX + rand(-200, 200));
    }

    // sparkles
    for (let i = 0; i < 20; i++) {
        const s = document.createElement("div");
        s.className = "sparkle";
        s.style.left = e.clientX + rand(-80,80) + "px";
        s.style.top = e.clientY + rand(-80,80) + "px";
        s.style.background =
            `hsl(${rand(0,360)},100%,60%)`;
        document.body.appendChild(s);
        setTimeout(() => s.remove(), 1000);
    }
});

// mobile: chạm là nổ
document.addEventListener("touchstart", (e) => {
    const t = e.touches[0];
    for (let i = 0; i < 10; i++) {
        spawnImage(t.clientX + rand(-150,150));
    }
});
</script>

</body>
</html>
