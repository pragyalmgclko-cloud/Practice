# Practice
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Canvas | Empowering Creativity, Supporting Educators</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#fafafa;
    color:#222;
    line-height:1.7;
}

nav{
    position:fixed;
    top:0;
    width:100%;
    background:white;
    padding:15px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    box-shadow:0 2px 10px rgba(0,0,0,0.05);
    z-index:1000;
}

.logo{
    font-size:1.5rem;
    font-weight:700;
    color:#2f5d50;
}

nav ul{
    list-style:none;
    display:flex;
    gap:25px;
}

nav a{
    text-decoration:none;
    color:#444;
    font-weight:500;
    transition:0.3s;
}

nav a:hover{
    color:#2f5d50;
}

section{
    padding:100px 10%;
}

.hero{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    background:linear-gradient(rgba(255,255,255,0.9),rgba(255,255,255,0.9)),
    url('https://images.unsplash.com/photo-1513364776144-60967b0f800f?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
}

.hero h1{
    font-size:4rem;
    color:#2f5d50;
    margin-bottom:20px;
}

.hero p{
    max-width:800px;
    font-size:1.2rem;
    color:#555;
}

.btn{
    margin-top:30px;
    display:inline-block;
    padding:14px 32px;
    background:#2f5d50;
    color:white;
    text-decoration:none;
    border-radius:30px;
    transition:0.3s;
}

.btn:hover{
    transform:translateY(-3px);
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    font-size:2.4rem;
    color:#2f5d50;
}

.section-title p{
    color:#666;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:30px;
    border-radius:16px;
    box-shadow:0 10px 30px rgba(0,0,0,0.05);
}

.card h3{
    color:#2f5d50;
    margin-bottom:15px;
}

.impact{
    background:#f3f7f5;
}

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:25px;
    text-align:center;
}

.stat{
    background:white;
    padding:35px;
    border-radius:16px;
}

.stat h3{
    font-size:2.2rem;
    color:#2f5d50;
}

.timeline{
    display:grid;
    gap:20px;
}

.goal{
    background:white;
    padding:25px;
    border-left:5px solid #2f5d50;
    box-shadow:0 5px 15px rgba(0,0,0,0.05);
}

.contact{
    text-align:center;
}

footer{
    background:#2f5d50;
    color:white;
    text-align:center;
    padding:30px;
}

@media(max-width:768px){

.hero h1{
    font-size:2.5rem;
}

nav ul{
    gap:12px;
    font-size:0.9rem;
}
}
</style>
</head>

<body>

<nav>
    <div class="logo">Canvas</div>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#ecosystem">Ecosystem</a></li>
        <li><a href="#programs">Programs</a></li>
        <li><a href="#impact">Impact</a></li>
        <li><a href="#team">Team</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section class="hero">
    <h1>Canvas</h1>
    <p>
        Empowering creativity in students while creating meaningful income
        opportunities for talented art teachers through accessible online
        summer classes.
    </p>

    <a href="#about" class="btn">Explore Our Mission</a>
</section>

<section id="about">
    <div class="section-title">
        <h2>About Canvas</h2>
        <p>Where Creativity Meets Opportunity</p>
    </div>

    <p style="text-align:center; max-width:900px; margin:auto;">
        Canvas is a socially-driven educational initiative that connects
        students seeking creative growth with talented art educators who
        deserve better earning opportunities. Through online classes conducted
        via platforms such as Skype, we provide engaging artistic learning
        experiences while supporting low-income teachers.
    </p>
</section>

<section id="ecosystem">
    <div class="section-title">
        <h2>Business Ecosystem</h2>
        <p>A sustainable model benefiting everyone involved.</p>
    </div>

    <div class="cards">

        <div class="card">
            <h3>Students</h3>
            <p>
                Develop artistic skills, confidence, creativity,
                and portfolio-building experience.
            </p>
        </div>

        <div class="card">
            <h3>Teachers</h3>
            <p>
                Earn fair income, work remotely,
                and reach students across regions.
            </p>
        </div>

        <div class="card">
            <h3>Parents</h3>
            <p>
                Affordable and productive summer activities
                that encourage creativity and growth.
            </p>
        </div>

        <div class="card">
            <h3>Canvas Platform</h3>
            <p>
                Handles registrations, scheduling,
                quality assurance, and educator support.
            </p>
        </div>

    </div>
</section>

<section id="programs">
    <div class="section-title">
        <h2>Programs Offered</h2>
        <p>Age-appropriate creative learning pathways.</p>
    </div>

    <div class="cards">

        <div class="card">
            <h3>Beginner Art Explorers</h3>
            <p>
                Ages 6–9<br>
                Sketching, colouring, patterns, and nature drawing.
            </p>
        </div>

        <div class="card">
            <h3>Creative Artists</h3>
            <p>
                Ages 10–13<br>
                Watercolour techniques, perspective drawing,
                and creative projects.
            </p>
        </div>

        <div class="card">
            <h3>Young Professionals</h3>
            <p>
                Ages 14–18<br>
                Portrait drawing, acrylic painting,
                and portfolio development.
            </p>
        </div>

    </div>
</section>

<section id="impact" class="impact">
    <div class="section-title">
        <h2>Social Impact</h2>
        <p>Creating value beyond education.</p>
    </div>

    <div class="stats">

        <div class="stat">
            <h3>100+</h3>
            <p>Students Targeted</p>
        </div>

        <div class="stat">
            <h3>20+</h3>
            <p>Teachers Supported</p>
        </div>

        <div class="stat">
            <h3>10+</h3>
            <p>Summer Batches</p>
        </div>

        <div class="stat">
            <h3>3+</h3>
            <p>Scholarship Programs</p>
        </div>

    </div>
</section>

<section>
    <div class="section-title">
        <h2>Future Goals</h2>
        <p>Growing a nationwide creative learning community.</p>
    </div>

    <div class="timeline">

        <div class="goal">
            Expand teacher partnerships across India.
        </div>

        <div class="goal">
            Launch national online art competitions.
        </div>

        <div class="goal">
            Create digital student portfolios and exhibitions.
        </div>

        <div class="goal">
            Build a dedicated Canvas learning platform.
        </div>

    </div>
</section>

<section id="team">
    <div class="section-title">
        <h2>Leadership Team</h2>
        <p>Driving the vision forward.</p>
    </div>

    <div class="cards">

        <div class="card">
            <h3>Pragya</h3>
            <p>
                <strong>Co-Developer</strong><br><br>
                Responsible for strategic planning,
                student engagement, program design,
                and community outreach initiatives.
            </p>
        </div>

        <div class="card">
            <h3>Educator Network</h3>
            <p>
                A growing community of passionate teachers
                committed to nurturing creativity and supporting
                young artists.
            </p>
        </div>

    </div>
</section>

<section id="contact" class="contact">
    <div class="section-title">
        <h2>Contact Us</h2>
        <p>Join our mission.</p>
    </div>

    <p>
        Interested in enrolling, teaching, partnering,
        or volunteering?
    </p>

    <br>

    <p><strong>Email:</strong> hello@canvasarts.org</p>
    <p><strong>Mode:</strong> Online via Skype & Virtual Platforms</p>
</section>

<footer>
    <h3>Canvas</h3>
    <p>Empowering Creativity. Supporting Educators.</p>
    <br>
    <p>© 2026 Canvas Educational Initiative</p>
</footer>

</body>
</html>
