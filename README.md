<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Clout TECH | Gokah Israel Web Developer</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
<style>
:root{
    --primary:#3b82f6;
    --accent:#10b981;
    --dark:#0a0f1e;
    --card:#1f2937;
    --text:#e2e8f0;
}
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',Arial,sans-serif}
body{background:var(--dark);color:var(--text);padding-bottom:80px}
html{scroll-behavior:smooth}

/* HEADER WITH LOGO */
.app-header{background:linear-gradient(135deg,#1e3a8a,#3b82f6);padding:30px 20px 40px;text-align:center;border-radius:0 0 30px 30px}
.logo{width:200px;max-width:80%;margin-bottom:15px;filter:drop-shadow(0 0 20px rgba(59,130,246,0.5))}
.profile-pic{width:90px;height:90px;border-radius:50%;border:3px solid white;object-fit:cover;margin-bottom:12px}
.app-header h2{font-size:1.2rem;font-weight:600;opacity:0.9}

/* BADGES */
.badge-row{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;margin:12px 0}
.badge{background:rgba(255,255,255,0.2);padding:5px 12px;border-radius:20px;font-size:11px;font-weight:600}

/* BUTTONS */
.btn{display:block;width:90%;margin:12px auto;padding:16px;border-radius:15px;text-decoration:none;text-align:center;font-weight:700;font-size:1rem;transition:0.2s}
.btn-primary{background:var(--primary);color:white;box-shadow:0 4px 15px rgba(59,130,246,0.4)}
.btn-whatsapp{background:#25D366;color:white;box-shadow:0 4px 15px rgba(37,211,102,0.4)}
.btn:active{transform:scale(0.97)}

/* CONTAINER */
.container{padding:20px}
.section{margin-bottom:30px}
h2{font-size:1.3rem;color:#60a5fa;margin-bottom:15px;text-align:left}
.card{background:var(--card);padding:20px;border-radius:20px;margin-bottom:15px;border:1px solid #374151}

/* SKILLS */
.skills-wrap{display:flex;gap:8px;flex-wrap:wrap}
.skill{background:#111827;padding:8px 14px;border-radius:20px;font-size:12px;border:1px solid #374151}

/* PROJECTS */
.project-card{background:var(--card);border-radius:20px;overflow:hidden;margin-bottom:18px;border:1px solid #374151}
.project-img{width:100%;height:200px;object-fit:cover;display:block}
.project-content{padding:15px}
.project-content h3{color:var(--primary);font-size:1.1rem;margin-bottom:8px}
.btn-small{display:inline-block;background:var(--primary);color:white;padding:10px 18px;border-radius:12px;text-decoration:none;font-size:0.85rem;font-weight:600}

/* PRICING */
.pricing-card{background:linear-gradient(135deg,#1f2937,#111827);border-radius:20px;padding:25px;margin-bottom:15px;border:2px solid #374151;position:relative}
.pricing-card.popular{border-color:var(--primary);box-shadow:0 0 20px rgba(59,130,246,0.3)}
.popular-badge{position:absolute;top:-12px;right:20px;background:var(--primary);color:white;padding:5px 15px;border-radius:20px;font-size:11px;font-weight:700}
.price{font-size:2rem;font-weight:700;color:var(--accent);margin:10px 0}
.pricing-features{list-style:none;margin:15px 0}
.pricing-features li{padding:8px 0;font-size:0.9rem}
.pricing-features li::before{content:'✓ ';color:var(--accent);font-weight:700}

/* CONTACT */
.contact-card{background:linear-gradient(135deg,#1f2937,#111827);padding:25px;border-radius:20px;text-align:center;border:1px solid #374151}

/* BOTTOM NAV */
.bottom-nav{position:fixed;bottom:0;left:0;right:0;background:#111827;display:flex;justify-content:space-around;padding:12px 0;border-top:1px solid #374151;z-index:100}
.nav-item{color:#9ca3af;text-decoration:none;font-size:11px;text-align:center}
.nav-item.active{color:var(--primary)}
.nav-icon{font-size:22px;display:block;margin-bottom:3px}
</style>
</head>
<body>

<!-- HEADER WITH LOGO -->
<header class="app-header">
    <img src=" Screenshot_20260717-224624 (1).png" width="20" height="100" alt="Clout TECH Logo" class="logo">
    <img src="Snapchat-913655823.jpg" alt="Gokah Israel" class="profile-pic">
    <h2>Gokah Israel Ewoenam</h2>
    <p>Web Developer</p>
    <div class="badge-row">
        <span class="badge">HTML</span>
        <span class="badge">CSS</span>
        <span class="badge">JS</span>
        <span class="badge">Python</span>
    </div>
    <p>📍 Afienya, Greater Accra, Ghana</p>
</header>

<!-- MAIN BUTTONS -->
<a href="https://wa.me/233557904956" class="btn btn-whatsapp">💬 WhatsApp: 0557904956</a>
<a href="#pricing" class="btn btn-primary">💰 View Pricing</a>

<div class="container">

    <!-- ABOUT -->
    <div class="section">
        <h2>👋 About Clout TECH</h2>
        <div class="card">
            <p>Clout TECH builds fast, modern websites for schools, businesses, and startups in Ghana.</p>
            <p style="margin-top:10px"><b style="color:var(--accent)">I'm very ready to work with you.</b></p>
        </div>
    </div>

    <!-- PRICING -->
    <div class="section" id="pricing">
        <h2>💰 Pricing Packages</h2>
        
        <div class="pricing-card">
            <h3>Basic Website</h3>
            <div class="price">GHS 800 <span>/one-time</span></div>
            <ul class="pricing-features">
                <li>5 Page Responsive Website</li>
                <li>Mobile Friendly Design</li>
                <li>Contact Form + WhatsApp Button</li>
                <li>7 Days Delivery</li>
            </ul>
            <a href="https://wa.me/233557904956?text=Hi%20Clout%20TECH%20I%20want%20Basic%20Website%20GHS%20800" class="btn btn-whatsapp">Order on WhatsApp</a>
        </div>

        <div class="pricing-card popular">
            <span class="popular-badge">MOST POPULAR</span>
            <h3>Business Pro</h3>
            <div class="price">GHS 1,500 <span>/one-time</span></div>
            <ul class="pricing-features">
                <li>10 Page Business Website</li>
                <li>Modern UI + Animations</li>
                <li>SEO + Google Setup</li>
                <li>14 Days Support</li>
            </ul>
            <a href="https://wa.me/233557904956?text=Hi%20Clout%20TECH%20I%20want%20Business%20Pro%20GHS%201500" class="btn btn-primary">Order on WhatsApp</a>
        </div>

        <div class="pricing-card">
            <h3>School Management System</h3>
            <div class="price">GHS 2,500 <span>/one-time</span></div>
            <ul class="pricing-features">
                <li>Student Records + Attendance</li>
                <li>Report Cards + CSV Export</li>
                <li>Admin Dashboard</li>
                <li>1 Month Free Support</li>
            </ul>
            <a href="https://wa.me/233557904956?text=Hi%20Clout%20TECH%20I%20want%20School%20System%20GHS%202500" class="btn btn-whatsapp">Order on WhatsApp</a>
        </div>
    </div>

    <!-- PROJECTS -->
    <div class="section" id="projects">
        <h2>🚀 My Projects</h2>
        <div class="project-card">
            <img src="Screenshot_20260717-213721.png" class="project-img" alt="CLOUT SMS">
            <div class="project-content">
                <h3>CLOUT SMS</h3>
                <p>School management system. Students, attendance, report cards.</p>
                <a href="https://israelclout.github.io/Tipsy.clout/" target="_blank" class="btn-small">Open App</a>
            </div>
        </div>
    </div>

    <!-- CONTACT -->
    <div class="section">
        <h2>📞 Contact</h2>
        <div class="contact-card">
            <p><b>Company:</b> Clout TECH</p>
            <p><b>Name:</b> Gokah Israel Ewoenam</p>
            <p><b>WhatsApp:</b> 0557904956</p>
            <a href="https://wa.me/233557904956" class="btn btn-whatsapp" style="margin-top:15px;width:100%">Chat Now</a>
        </div>
    </div>

</div>

<!-- BOTTOM NAV -->
<nav class="bottom-nav">
    <a href="#" class="nav-item active"><span class="nav-icon">🏠</span>Home</a>
    <a href="#pricing" class="nav-item"><span class="nav-icon">💰</span>Pricing</a>
    <a href="#projects" class="nav-item"><span class="nav-icon">📱</span>Projects</a>
    <a href="https://wa.me/233557904956" class="nav-item"><span class="nav-icon">💬</span>Contact</a>
</nav>

<footer>
    © 2026 Clout TECH. Built by Gokah Israel
</footer>

</body>
</html>
