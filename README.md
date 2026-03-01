<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog nho nhỏ của Hà</title>
    <style>
        :root { --primary-color: #2563eb; --dark-bg: #1e293b; }
        body {font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;margin: 0;line-height: 1.6;color: #213A58;}
        .card img {width: 100%; height: 50px;object-fit: cover; }
        header { background: #36436f; color: white; padding: 1rem; position: sticky; top: 0; z-index: 20; }
        nav { display: flex; justify-content: space-around; align-items: center; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: 500; }
        .hero { height: 60vh; display: flex; flex-direction: column; justify-content: center; align-items: center; background: #a7d0d6; color: #34675c ;text-align: center; }
        .hero h1 { font-size: 3rem; margin-bottom: 0.5rem; }
        .container { max-width: 900px; margin: 40px auto; padding: 0 20px; }
        .section { background: white; padding: 30px; border-radius: 12px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1); margin-bottom: 30px; }
        h2 { border-bottom: 2px solid var(--primary-color); display: inline-block; padding-bottom: 5px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .item { padding: 15px; border: 1px solid #e2e8f0; border-radius: 8px; }
        footer { text-align: center; padding: 20px; background: #334155; color: white; margin-top: 50px; }
    </style>
</head>
<body>
    <header>
        <nav>
            <div style="font-weight: bold; font-size: 1.2rem;">MILKY WAY</div>
            <div>
                <a href="#about">Giới thiệu</a>
                <a href="#skills">Sở thích</a>
                <a href="#contact">Liên hệ</a>
            </div>
        </nav>
    </header>
    <section class="hero">
        <h1>Người mang lý trí trong tim</h1>
        <p>Coi như đây là Blog để tui chat chít nhẹ nhàng thôi nha.</p>
    </section>
    <div class="container">
        <div id="about" class="section">
            <h2>Giới thiệu bản thân</h2>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3D1AMs4u9Cx4xxP18LqASODyP1tjH9INl58Q_NO_ICpKPQC72621IYswC245E-0Mv1Ax7em1ncYvUPAA_9eIhUBpGRk8dqBwdOmzLIdU&s=10" alt="Trần Phạm Ngân Hà">
            <p>Tui hiện tại chỉ là học sinh thôi nhưng ngày này năm sau thì không chắc. Tui không định làm một bông hoa đâu thay vào đó tui thích làm cây liễu hơn. Bên trên là thần tượng gần đây của tui á. Bạn này chăm chỉ lắm và cũng là một người kiên trì nữa nên có thể vì vậy mà tui ngưỡng mộ bạn này lắm.</p>
        </div>
        <div id="skills" class="section">
            <h2>Sở thích</h2>
            <div class="grid">
                <div class="item"><strong>Nhạc POP:</strong> Khoảng thời gian trước tui khá thích BTS, Talor Switch,... nhưng giờ tui nghe nhạc lộn xộn lắm.</div>
                <div class="item"><strong>Game:</strong> Thay vì tự mình chơi thì tui thích xem người khác chơi hơn (do tui gà). Gần đây tui khá thích nhóm T1 Liên Minh Huyền Thoại.</div>
                <div class="item"><strong>Đọc sách:</strong> Tui không có loại sách nào thật sự thích hết nhưng tui đọc khá nhiều tiểu thuyết và báo nên tui nghĩ mình chỉ thích đọc chữ thôi (nhưng tui cũng là một người đọc chọn lọc đó nha).</div>
                <div class="item"><strong>Cắm hoa:</strong> Đây thật sự chỉ là sở thích thời vụ thôi. Tui cũng không giỏi mấy cái cần khéo tay nên chỉ cắm thôi chứ tui không cho xem đâu.</div>
                <div class="item"><strong></strong> Để đây trước đi có gì tui sẽ update cho mọi người xem nha.</div>
            </div>
        </div>
        <div id="contact" class="section">
            <h2>Liên hệ với tôi</h2>
            <p>📧 Email: nganhatranpham2501n@gmail.com</p>
            <p>📞 Số điện thoại: 0123456789</p>
            <p>📍 Địa chỉ: Quảng Ngãi, Việt Nam</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2026 Trần Phạm Ngân Hà. Thiết kế bởi chính tôi.</p>
    </footer>
</body>
</html>
