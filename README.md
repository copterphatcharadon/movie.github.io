<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="คอลเลกชันภาพยนตร์และซีรีส์โปรดของ Harry Copter">
  <title>My Favorite Movies & Shows - Harry Copter</title>
  <style>
    /* 2. เพิ่ม CSS Reset พื้นฐานและ Box Sizing */
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      /* 3. ปรับปรุง Font-family ให้อ่านง่ายขึ้น */
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
      background: #f4f4f9; /* ปรับสีพื้นหลังเล็กน้อย */
      line-height: 1.5;
    }

    /* 4. ใช้ <main> ในการจัดเลย์เอาต์หลัก */
    main {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    h1 {
      text-align: center;
      margin-top: 0;
      margin-bottom: 30px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
    }

    /* 5. ปรับปรุงการ์ดภาพยนตร์ (ใช้ <article>) */
    .movie {
      background: white;
      padding: 10px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      text-align: center;
      /* 6. เพิ่ม Hover Effect (Micro-interaction) */
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      display: flex; /* ช่วยจัดองค์ประกอบภายใน */
      flex-direction: column;
      height: 100%; /* ทำให้การ์ดในแถวเดียวกันสูงเท่ากัน */
    }

    .movie:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0,0,0,0.15);
    }

    .movie img {
      width: 100%;
      /* 7. ใช้ aspect-ratio แทน fixed height */
      height: auto;
      aspect-ratio: 2 / 3; /* อัตราส่วนโปสเตอร์หนังมาตรฐาน */
      object-fit: cover;
      border-radius: 5px;
    }

    /* 8. ใช้ <h3> สำหรับชื่อหนัง (Semantic HTML) */
    .movie-title {
      margin-top: 10px;
      margin-bottom: 5px; /* เพิ่มระยะห่างด้านล่างเล็กน้อย */
      font-weight: bold;
      font-size: 0.95rem; /* ใช้ rem เพื่อการเข้าถึงที่ดีขึ้น */
      line-height: 1.3;
      /* ทำให้ title ขยายเต็มพื้นที่ที่เหลือ */
      flex-grow: 1; 
    }
  </style>
</head>
<body>
  <main>
    <h1>🎬 My Favorite Movies & Shows - Harry Copter</h1>

    <div class="grid">

      <article class="movie">
        <img src="https://wallpapers.com/images/hd/fast-and-furious-1-1wgohxcm5s7etb8r.jpg" alt="Fast and Furious">
        <h3 class="movie-title">Fast and the Furious</h3>
      </article>

      <article class="movie">
        <img src="https://image.tmdb.org/t/p/original/57yov1Boc2I0VJ753DnoAHnaiXG.jpg" alt="Bad Boys">
        <h3 class="movie-title">Bad Boys</h3>
      </article>

      <article class="movie">
        <img src="https://www.bloggang.com/data/p/pitchayut8/picture/1649779583.jpg" alt="แก็งช่า ป่วนเมืองไทย">
        <h3 class="movie-title">แก็งช่า ป่วนเมืองไทย</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/DcniF" alt="Green Book">
        <h3 class="movie-title">Green Book</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/HBF38" alt="John Wick">
        <h3 class="movie-title">John Wick</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/XePAM" alt="Spider Man">
        <h3 class="movie-title">Spider Man</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/P6QFY" alt="Iron Man">
        <h3 class="movie-title">Iron Man</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/m9tsr" alt="Avengers">
        <h3 class="movie-title">Avengers</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/WF0Hb" alt="Black Panther">
        <h3 class="movie-title">Black Panther</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/a7tkW" alt="Hobbit">
        <h3 class="movie-title">The Hobbit</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/cVqoC" alt="Stranger Things">
        <h3 class="movie-title">Stranger Things</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/W8Ie3" alt="The Lord of the Rings">
        <h3 class="movie-title">The Lord of the Rings</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/mwphI" alt="Game of Thrones">
        <h3 class="movie-title">Game of Thrones</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/wHIid" alt="Cars">
        <h3 class="movie-title">Cars</h3>
      </article>

      <article class="movie">
        <img src="https://shorturl.asia/M7zCS" alt="Harry Potter">
        <h3 class="movie-title">Harry Potter</h3>
      </article>

      <article class="movie">
        <img src="https://image.tmdb.org/t/p/w500/gEU2QniE6E77NI6lCU6MxlNBvIx.jpg" alt="Interstellar">
        <h3 class="movie-title">Interstellar</h3>
      </article>

      <article class="movie">
        <img src="https://image.tmdb.org/t/p/w500/oYuLEt3zVCKq57qu2F8dT7NIa6f.jpg" alt="Inception">
        <h3 class="movie-title">Inception</h3>
      </article>

      <article class="movie">
        <img src="https://th.bing.com/th/id/R.3b47964866a99fcfbf7c549f901ddf34?rik=2f98kbQp80tx8g&riu=http%3a%2f%2f3.bp.blogspot.com%2f_YanHjln8DDA%2fTMUtNWUyo9I%2fAAAAAAAAACI%2fzZ1eYVMRXRQ%2fs1600%2f300-dvd1.jpg&ehk=n6IOEbe36OoFT%2fXNQi9teCYdrva%2bVnnOnxj9mxdl1gI%3d&risl=&pid=ImgRaw&r=0" alt="300">
        <h3 class="movie-title">300</h3>
      </article>

      <article class="movie">
        <img src="https://th.bing.com/th/id/OIP.fu1NIUpwaX0R9SkmZmAl4gHaK-?w=203&h=301&c=7&r=0&o=7&pid=1.7&rm=3" alt="The Last of Us">
        <h3 class="movie-title">The Last of Us</h3>
      </article>

      <article class="movie">
        <img src="https://mediacdn.aent-m.com/prod-img/500/09/1181909-2720134.jpg" alt="The Mist">
        <h3 class="movie-title">The Mist</h3>
      </article>

      <article class="movie">
        <img src="https://th.bing.com/th/id/R.da2b1d688fff2e714afd99acd7cf8177?rik=ElKZeoZQB3AwHQ&riu=http%3a%2f%2fprodimage.images-bn.com%2fpimages%2f0196588243714_p0_v3_s1200x630.jpg&ehk=AHa1%2bREU4milxk7N6uJFo7W6muA5%2bMfe2H%2b9v8p6GUM%3d&risl=&pid=ImgRaw&r=0" alt="The Witcher">
        <h3 class="movie-title">The Witcher</h3>
      </article>

      <article class="movie">
        <img src="https://m.media-amazon.com/images/M/MV5BNGYzYjE0NzYtMWRiZC00NTk5LWJiMTctMDRiNDhjMjJmZGNmXkEyXkFqcGc@._V1_.jpg" alt="Snowpiercer">
        <h3 class="movie-title">Snowpiercer</h3>
      </article>
      
      <article class="movie">
        <img src=" https://shorturl.asia/96Hsg" alt="หลักสูตรชีวิตนาวิกน้องใหม่">
        <h3 class="movie-title">หลักสูตรชีวิตนาวิกน้องใหม่</h3>
      </article>
      
      <article class="movie">
        <img src="  https://shorturl.asia/DmZqT" alt="sweet tooth">
        <h3 class="movie-title">sweet tooth</h3>
      </article>

     <article class="movie">
        <img src="  https://m.media-amazon.com/images/M/MV5BYzYzNDYxMTQtMTU4OS00MTdlLThhMTQtZjI4NGJmMTZmNmRiXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" alt="Frankenstein2025">
        <h3 class="movie-title">Frankenstein2025</h3>
      </article>

    </div>
  </main>
</body>
</html>
