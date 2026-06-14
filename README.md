<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Birthday Wonderland | June 13, 2026 Countdown ✨</title>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;600;700&family=Dancing+Script:wght@400;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            background: linear-gradient(145deg, #fbc2eb 0%, #a6c1ee 100%);
            font-family: 'Poppins', 'Quicksand', sans-serif;
            padding: 20px;
            position: relative;
            overflow-x: hidden;
        }

        /* animated floating elements */
        .floating-particle {
            position: fixed;
            pointer-events: none;
            z-index: 10;
            font-size: 1.8rem;
            animation: floatMagic 7s linear forwards;
        }

        @keyframes floatMagic {
            0% { transform: translateY(100vh) rotate(0deg); opacity: 0.9; }
            100% { transform: translateY(-20vh) rotate(360deg); opacity: 0; }
        }

        .container {
            max-width: 1300px;
            margin: 0 auto;
        }

        /* main layout */
        .dashboard {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 28px;
            margin-bottom: 35px;
        }

        .card {
            background: rgba(255, 255, 255, 0.94);
            backdrop-filter: blur(3px);
            border-radius: 56px;
            padding: 28px 24px;
            box-shadow: 0 25px 45px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
            border: 1px solid rgba(255,235,200,0.7);
        }

        .card:hover {
            transform: translateY(-6px);
        }

        /* countdown hero */
        .countdown-hero {
            text-align: center;
            background: linear-gradient(135deg, #fff9f0, #ffefdb);
        }

        .cake-icon {
            font-size: 70px;
            animation: bounceGentle 2s infinite ease;
        }

        @keyframes bounceGentle {
            0%,100%{ transform: translateY(0); }
            50%{ transform: translateY(-10px); }
        }

        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 3rem;
            background: linear-gradient(120deg, #e74c3c, #f39c12, #27ae60);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            margin: 12px 0;
        }

        .target-date {
            font-size: 1.5rem;
            font-weight: bold;
            background: #ffd966;
            display: inline-block;
            padding: 5px 25px;
            border-radius: 50px;
            color: #a04010;
            margin-bottom: 20px;
        }

        .countdown-timer {
            display: flex;
            justify-content: center;
            gap: 22px;
            flex-wrap: wrap;
            margin: 20px 0;
        }

        .time-card {
            background: #fff3e0;
            border-radius: 40px;
            padding: 15px 12px;
            min-width: 95px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .time-num {
            font-size: 2.8rem;
            font-weight: 800;
            color: #e67e22;
            font-family: monospace;
        }

        .time-label {
            font-weight: 600;
            color: #b45f2b;
        }

        .birthday-message {
            margin-top: 20px;
            font-weight: bold;
            background: #ffd0a4;
            display: inline-block;
            padding: 8px 24px;
            border-radius: 40px;
            color: #ad4b1c;
        }

        /* ANIMATED GIFT CARD */
        .gift-card-section {
            background: linear-gradient(145deg, #ffe6f0, #ffe0c0);
            text-align: center;
            cursor: pointer;
            overflow: hidden;
        }

        .gift-wrapper {
            perspective: 800px;
            margin: 15px 0;
        }

        .gift-box {
            width: 150px;
            height: 150px;
            margin: 0 auto;
            position: relative;
            transform-style: preserve-3d;
            transition: transform 0.6s;
            cursor: pointer;
        }

        .gift-box.open {
            transform: rotateY(180deg);
        }

        .gift-front, .gift-back {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            border-radius: 28px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            box-shadow: 0 15px 25px rgba(0,0,0,0.2);
        }

        .gift-front {
            background: linear-gradient(135deg, #ff9a9e, #fecfef);
            transform: rotateY(0deg);
            font-size: 4rem;
        }

        .gift-back {
            background: linear-gradient(135deg, #a1c4fd, #c2e9fb);
            transform: rotateY(180deg);
            font-size: 1.2rem;
            font-weight: bold;
            color: #2c3e66;
            padding: 20px;
            text-align: center;
        }

        .gift-hint {
            margin-top: 12px;
            font-size: 0.8rem;
            color: #c96f32;
        }

        /* letter section */
        .letter-card {
            grid-column: span 2;
            background: #fffaf0;
            padding: 20px 28px;
        }

        .letter-content {
            background: #fffef7;
            border-radius: 48px;
            padding: 25px;
            border: 2px dashed #ffbc6e;
            max-height: 280px;
            overflow-y: auto;
            font-family: 'Dancing Script', cursive;
            font-size: 1.2rem;
            line-height: 1.6;
            color: #4a2a1a;
        }

        /* photo gallery */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(170px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .photo-card {
            background: white;
            border-radius: 32px;
            overflow: hidden;
            transition: 0.2s;
            cursor: pointer;
            box-shadow: 0 8px 18px rgba(0,0,0,0.1);
        }

        .photo-card:hover {
            transform: scale(1.02);
        }

        .photo-img {
            width: 100%;
            height: 160px;
            object-fit: cover;
            background: #f3d9b1;
        }

        .photo-caption {
            padding: 10px;
            font-weight: 500;
            text-align: center;
            background: #fff3e6;
            color: #b4511c;
        }

        .upload-area {
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
            margin-top: 20px;
            justify-content: center;
        }

        .btn-glow {
            background: #ff8c5a;
            border: none;
            padding: 10px 22px;
            border-radius: 60px;
            color: white;
            font-weight: bold;
            cursor: pointer;
            transition: 0.2s;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        }

        .btn-glow:hover {
            background: #e56e3b;
            transform: scale(1.02);
        }

        input, textarea {
            padding: 10px 18px;
            border-radius: 60px;
            border: 1px solid #ffbb77;
            font-family: inherit;
            background: white;
        }

        /* modal for photos */
        .modal-photo {
            display: none;
            position: fixed;
            top:0;left:0;
            width:100%;height:100%;
            background: rgba(0,0,0,0.85);
            z-index: 2000;
            justify-content: center;
            align-items: center;
            cursor: pointer;
        }
        .modal-img-big {
            max-width: 90%;
            max-height: 85%;
            border-radius: 32px;
        }

        @media (max-width: 850px) {
            .dashboard { grid-template-columns: 1fr; }
            .letter-card { grid-column: span 1; }
            .time-num { font-size: 2rem; }
            .time-card { min-width: 70px; }
        }

        footer {
            text-align: center;
            margin-top: 30px;
            color: #fff2d7;
            text-shadow: 1px 1px 0 #ad6b3a;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="dashboard">
        <!-- COUNTDOWN CARD for June 13, 2026 -->
        <div class="card countdown-hero">
            <div class="cake-icon">🎂✨🎈</div>
            <h1>Birthday Countdown</h1>
            <div class="target-date">🎯 June 13, 2026 🎯</div>
            <div class="countdown-timer" id="countdownDisplay">
                <div class="time-card"><div class="time-num" id="days">00</div><div class="time-label">Days</div></div>
                <div class="time-card"><div class="time-num" id="hours">00</div><div class="time-label">Hours</div></div>
                <div class="time-card"><div class="time-num" id="minutes">00</div><div class="time-label">Mins</div></div>
                <div class="time-card"><div class="time-num" id="seconds">00</div><div class="time-label">Secs</div></div>
            </div>
            <div id="specialMessage" class="birthday-message">💖 The magic is approaching! 💖</div>
        </div>

        <!-- ANIMATED GIFT CARD SECTION -->
        <div class="card gift-card-section" id="giftCardArea">
            <h2>🎁 Animated Gift Card 🎁</h2>
            <div class="gift-wrapper">
                <div class="gift-box" id="giftBox">
                    <div class="gift-front">
                        🎀 <br> 🎁
                    </div>
                    <div class="gift-back">
                        ✨ HAPPY BIRTHDAY! ✨<br>
                        🎂 You deserve all the joy! 🎂<br>
                        💝 Special virtual gift for you 💝
                    </div>
                </div>
            </div>
            <div class="gift-hint">✨ Click the gift box to open your surprise! ✨</div>
            <p style="margin-top: 12px; font-size:0.8rem;">💎 An exclusive birthday gift card + warm wishes 💎</p>
        </div>
    </div>

    <!-- LETTER SECTION: Personal birthday letter -->
    <div class="card letter-card">
        <h2>💌 A Special Birthday Letter 💌</h2>
        <div class="letter-content" id="birthdayLetter">
            🌟 My Dearest Birthday Star, 🌟<br><br>
            As the days tick down to <strong>June 13, 2026</strong>, my heart fills with excitement and love. 
            This countdown is a celebration of YOU — your kindness, your laughter, and the beautiful light you bring into the world. 
            May every moment of your special day be wrapped in joy, surrounded by the people you cherish, and filled with sweet surprises. <br><br>
            🎂 This year, I wish you courage to chase dreams, happiness that never fades, and love that echoes in every heartbeat. 
            Remember that you are deeply loved today, tomorrow, and always. <br><br>
            ✨ Let's make memories that shimmer like gold. Happy Birthday in advance, wonderful soul! ✨<br><br>
            With all my heart, <br>
            Your forever well-wisher 💖
        </div>
    </div>

    <!-- PHOTO GALLERY + animated photos -->
    <div class="card" style="margin-bottom: 20px;">
        <h2>📸 Birthday Memories & Animated Photos 📸</h2>
        <div class="gallery-grid" id="photoGallery">
            <!-- sample photos will be injected here plus later added -->
        </div>
        <div class="upload-area">
            <label class="btn-glow" style="background:#bb7e4a; display:inline-block; cursor:pointer;">📷 Upload Photo<input type="file" id="photoUpload" accept="image/*" style="display:none;"></label>
            <input type="text" id="photoCaptionInput" placeholder="Write a caption...">
            <button class="btn-glow" id="uploadPhotoBtn">➕ Add Memory</button>
        </div>
        <p style="font-size:0.75rem; margin-top:12px;">✨ Click any photo to enlarge. Add your own photos to personalize the album! ✨</p>
    </div>
    <footer>🎈 Countdown to June 13, 2026 | Every tick brings you closer to celebration 🎈</footer>
</div>

<!-- Modal for enlarged photo -->
<div id="photoModal" class="modal-photo">
    <img id="modalFullImg" class="modal-img-big" alt="enlarged">
    <div id="modalCaptionText" style="color:white; margin-top:15px; text-align:center; background:rgba(0,0,0,0.6); padding:6px 18px; border-radius:40px;"></div>
</div>

<script>
    // ---------- 1. COUNTDOWN for JUNE 13, 2026 ----------
    const targetDate = new Date(2026, 5, 13, 0, 0, 0); // June 13 2026 (month 5 = June)
    const daysSpan = document.getElementById('days');
    const hoursSpan = document.getElementById('hours');
    const minutesSpan = document.getElementById('minutes');
    const secondsSpan = document.getElementById('seconds');
    const specialMsgDiv = document.getElementById('specialMessage');

    function updateCountdown() {
        const now = new Date();
        const diff = targetDate - now;
        if (diff <= 0) {
            daysSpan.innerText = "00";
            hoursSpan.innerText = "00";
            minutesSpan.innerText = "00";
            secondsSpan.innerText = "00";
            specialMsgDiv.innerHTML = "🎉🎂 TODAY IS THE BIRTHDAY! CELEBRATE BIG! 🎂🎉";
            launchConfettiBurst(35);
            return;
        }
        const totalSec = Math.floor(diff / 1000);
        const days = Math.floor(totalSec / 86400);
        const hours = Math.floor((totalSec % 86400) / 3600);
        const minutes = Math.floor((totalSec % 3600) / 60);
        const seconds = totalSec % 60;
        daysSpan.innerText = String(days).padStart(2, '0');
        hoursSpan.innerText = String(hours).padStart(2, '0');
        minutesSpan.innerText = String(minutes).padStart(2, '0');
        secondsSpan.innerText = String(seconds).padStart(2, '0');
        
        if (days <= 30 && days > 0) {
            specialMsgDiv.innerHTML = `✨ Just ${days} days left! The excitement is real ✨`;
        } else if (days <= 7 && days > 0) {
            specialMsgDiv.innerHTML = `🎈 ONLY ${days} DAYS! GET READY TO PARTY! 🎈`;
        } else {
            specialMsgDiv.innerHTML = `💖 Countdown to June 13, 2026 — Your special day is coming! 💖`;
        }
    }

    // floating confetti / particles
    function launchConfettiBurst(count = 28) {
        const icons = ['🎉','🎈','🎊','✨','🎂','🎁','🌸','🥳','💖','⭐','🎀'];
        for (let i=0; i<count; i++) {
            const particle = document.createElement('div');
            particle.classList.add('floating-particle');
            particle.innerText = icons[Math.floor(Math.random() * icons.length)];
            particle.style.left = Math.random() * 100 + '%';
            particle.style.fontSize = (Math.random() * 28 + 18) + 'px';
            particle.style.animationDuration = (Math.random() * 4 + 3) + 's';
            document.body.appendChild(particle);
            particle.addEventListener('animationend', () => particle.remove());
        }
    }

    setInterval(updateCountdown, 1000);
    updateCountdown();

    // ---------- 2. ANIMATED GIFT CARD (3D flip) ----------
    const giftBox = document.getElementById('giftBox');
    let isOpened = false;
    giftBox.addEventListener('click', () => {
        if (!isOpened) {
            giftBox.classList.add('open');
            isOpened = true;
            launchConfettiBurst(40);
            // Show hidden alert sweet message
            const msg = document.createElement('div');
            msg.innerText = "🎁✨ Gift Unlocked! Happy Birthday! ✨🎁";
            msg.style.position = "fixed";
            msg.style.bottom = "20%";
            msg.style.left = "50%";
            msg.style.transform = "translateX(-50%)";
            msg.style.background = "#ffecb3";
            msg.style.padding = "12px 28px";
            msg.style.borderRadius = "60px";
            msg.style.fontWeight = "bold";
            msg.style.zIndex = "999";
            msg.style.boxShadow = "0 8px 20px black";
            msg.style.color = "#b64926";
            document.body.appendChild(msg);
            setTimeout(() => msg.remove(), 2500);
        } else {
            // optional: show message again but no flip back to keep magic
            const already = document.createElement('div');
            already.innerText = "💝 Your birthday magic is already open! 💝";
            already.style.position = "fixed";
            already.style.bottom = "20%";
            already.style.left = "50%";
            already.style.transform = "translateX(-50%)";
            already.style.background = "#fce4b2";
            already.style.padding = "8px 20px";
            already.style.borderRadius = "40px";
            already.style.zIndex = "999";
            document.body.appendChild(already);
            setTimeout(() => already.remove(), 1500);
        }
    });

    // ---------- 3. PHOTO GALLERY with localStorage + sample photos + animated addition ----------
    let photosArray = [];

    // default photos (beautiful memories)
    const defaultPhotos = [
        { src: "https://picsum.photos/id/20/300/200", caption: "🎂 Classic birthday cake & sparkle" },
        { src: "https://picsum.photos/id/29/300/200", caption: "🎈 Colorful balloons of joy" },
        { src: "https://picsum.photos/id/169/300/200", caption: "🌅 Sunset birthday magic" },
        { src: "https://picsum.photos/id/91/300/200", caption: "📸 Happy memories with loved ones" },
        { src: "https://picsum.photos/id/100/300/200", caption: "🌸 Blooming birthday wishes" }
    ];

    function loadPhotosFromStorage() {
        const stored = localStorage.getItem('birthday_photos_june13');
        if (stored) {
            try {
                photosArray = JSON.parse(stored);
            } catch(e) { photosArray = []; }
        }
        if (!photosArray || photosArray.length === 0) {
            photosArray = [...defaultPhotos];
        }
        renderGallery();
    }

    function renderGallery() {
        const galleryContainer = document.getElementById('photoGallery');
        if (!galleryContainer) return;
        galleryContainer.innerHTML = '';
        photosArray.forEach((photo, idx) => {
            const photoDiv = document.createElement('div');
            photoDiv.className = 'photo-card';
            photoDiv.innerHTML = `
                <img class="photo-img" src="${photo.src}" alt="memory" loading="lazy" onerror="this.src='https://picsum.photos/id/1/300/200'">
                <div class="photo-caption">${escapeHtml(photo.caption)}</div>
            `;
            photoDiv.addEventListener('click', (e) => {
                e.stopPropagation();
                openModal(photo.src, photo.caption);
            });
            galleryContainer.appendChild(photoDiv);
        });
        localStorage.setItem('birthday_photos_june13', JSON.stringify(photosArray));
    }

    function addPhoto(imageDataUrl, captionText) {
        if (!imageDataUrl) return;
        let finalCaption = captionText.trim();
        if (finalCaption === "") finalCaption = "🎀 Birthday memory ✨";
        photosArray.unshift({ src: imageDataUrl, caption: finalCaption.substring(0, 70) });
        renderGallery();
        launchConfettiBurst(18);
    }

    function escapeHtml(str) {
        return str.replace(/[&<>]/g, function(m) {
            if(m === '&') return '&amp;';
            if(m === '<') return '&lt;';
            if(m === '>') return '&gt;';
            return m;
        });
    }

    // Modal logic
    const modal = document.getElementById('photoModal');
    const modalImg = document.getElementById('modalFullImg');
    const modalCaptionSpan = document.getElementById('modalCaptionText');
    function openModal(src, cap) {
        modalImg.src = src;
        modalCaptionSpan.innerText = cap;
        modal.style.display = 'flex';
    }
    modal.addEventListener('click', () => {
        modal.style.display = 'none';
    });

    // Upload image handling
    const fileUpload = document.getElementById('photoUpload');
    const captionInput = document.getElementById('photoCaptionInput');
    const uploadBtn = document.getElementById('uploadPhotoBtn');
    const labelTrigger = document.querySelector('.upload-area .btn-glow');
    
    uploadBtn.addEventListener('click', () => {
        if (fileUpload.files && fileUpload.files[0]) {
            const file = fileUpload.files[0];
            if (!file.type.startsWith('image/')) {
                alert("Please choose an image file 🖼️");
                return;
            }
            const reader = new FileReader();
            reader.onload = function(ev) {
                let caption = captionInput.value;
                addPhoto(ev.target.result, caption);
                captionInput.value = "";
                fileUpload.value = "";
            };
            reader.readAsDataURL(file);
        } else {
            alert("Select a photo from your device first! 📸");
        }
    });
    // manually trigger file input via label
    document.querySelector('.upload-area .btn-glow')?.addEventListener('click', (e) => {
        if(e.target === uploadBtn) return;
        fileUpload.click();
    });
    fileUpload.addEventListener('change', () => {
        if(fileUpload.files.length) {
            // optional preview auto add not necessary
        }
    });

    // ---------- 4. ADDITIONAL EFFECT: click on letter shows spark ----------
    const letterDiv = document.getElementById('birthdayLetter');
    letterDiv.addEventListener('click', () => {
        launchConfettiBurst(12);
        const ripple = document.createElement('div');
        ripple.innerText = "💌✨";
        ripple.style.position = "absolute";
        ripple.style.fontSize = "2rem";
        ripple.style.pointerEvents = "none";
        letterDiv.appendChild(ripple);
        setTimeout(() => ripple.remove(), 500);
    });

    // Helper random floating emoji every 10 seconds
    setInterval(() => {
        if (Math.random() < 0.4) launchConfettiBurst(8);
    }, 12000);

    // also on load launch welcome particles
    window.addEventListener('load', () => {
        loadPhotosFromStorage();
        launchConfettiBurst(20);
        // Extra: if countdown shows 0? no, its far away but we set inline
        // Let's add a sweet message about custom gift.
        const customAlert = setTimeout(() => {
            const note = document.createElement('div');
            note.innerText = "🎁 Don't forget to open the gift card above! 🎁";
            note.style.position = "fixed";
            note.style.bottom = "15px";
            note.style.left = "15px";
            note.style.background = "#fdebb3";
            note.style.padding = "6px 15px";
            note.style.borderRadius = "40px";
            note.style.fontSize = "0.8rem";
            note.style.zIndex = "99";
            document.body.appendChild(note);
            setTimeout(() => note.remove(), 5000);
        }, 1500);
    });
    
    // Also add option to keep gift card flipped permanently if user reopens but not needed
    // Extra: preload some animated style
    const style = document.createElement('style');
    style.textContent = `.photo-card { transition: all 0.2s ease; } .photo-card:hover { transform: scale(1.02) rotate(1deg); }`;
    document.head.appendChild(style);
    
    // Enable saving of birthday letter editable? not needed, but keep cozy.
    // ensure countdown always shows proper leading zero
    function leadingZero(num) { return String(num).padStart(2,'0'); }
</script>
</body>
</html>
