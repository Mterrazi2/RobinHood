<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Robin Hood | Gameplay Systems & Camera Design</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background-color: #0a0a0f;
    color: #e6e6e6;
    line-height: 1.7;
}

.container {
    max-width: 1000px;
    margin: auto;
    padding: 60px 20px;
}

a {
    color: #F5C542;
    text-decoration: none;
}

a:hover {
    color: white;
}

.back {
    margin-bottom: 40px;
    display: inline-block;
}

.hero h1 {
    font-size: 40px;
    margin-bottom: 10px;
}

.subtitle {
    color: #9aa0a6;
    margin-bottom: 20px;
}

.video-container {
    margin-top: 30px;
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
}

.video-container iframe {
    position: absolute;
    width: 100%;
    height: 100%;
}

section {
    margin-top: 60px;
}

h2 {
    border-left: 4px solid #F5C542;
    padding-left: 10px;
    margin-bottom: 20px;
}

ul {
    margin-left: 20px;
    margin-top: 10px;
}

.tech {
    margin-top: 20px;
}

.tech span {
    display: inline-block;
    background-color: #1f2230;
    padding: 6px 10px;
    margin: 5px 5px 0 0;
    border-radius: 4px;
    font-size: 13px;
}

.footer {
    margin-top: 100px;
    text-align: center;
    color: #777;
    font-size: 14px;
}
</style>
</head>

<body>

<div class="container">

<a class="back" href="https://mterrazi2.github.io/">← Back to Portfolio</a>

<div class="hero">
<h1>Robin Hood</h1>
<div class="subtitle">
3D Side-Scroller | Unreal Engine | Gameplay Systems
</div>

<p>
A 3D side-scrolling platformer built from scratch within a two-and-a-half-week sprint.
The project focused on implementing responsive character movement, dynamic camera systems,
and complete gameplay loop functionality without external tutorial reliance.
</p>

<div class="video-container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/JFtZ9s6NDZk?si=y14Z3--aaRqiber9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<div class="tech">
<span>Unreal Engine</span>
<span>Gameplay Systems</span>
<span>Character Movement</span>
<span>Camera Systems</span>
<span>Spatial Audio</span>
<span>Rapid Prototyping</span>
</div>
</div>

<section>
<h2>Project Overview</h2>
<p>
Robin Hood served as a rapid development challenge to test independent gameplay
engineering capability under time constraints. All core systems were implemented
without tutorial reference, emphasizing problem-solving and architectural clarity.
</p>

<p>
The primary objective was to build a complete, functional side-scrolling experience
including movement mechanics, camera logic, enemy interactions, and audio feedback.
</p>
</section>

<section>
<h2>Core Gameplay Systems Implemented</h2>
<ul>
<li>Custom character movement logic with responsive jump handling</li>
<li>Side-scrolling camera system with constrained axis control</li>
<li>Dynamic camera adjustment for environmental readability</li>
<li>Enemy interaction and collision systems</li>
<li>Spatial audio implementation for environmental feedback</li>
<li>Full gameplay loop structure (spawn → progression → completion)</li>
</ul>
</section>

<section>
<h2>Camera System Design</h2>
<p>
The camera system was engineered to maintain consistent player framing
while adapting to environmental verticality. Axis constraints ensured
side-scrolling clarity while preserving 3D depth.
</p>

<p>
Adjustments were made to prevent disorienting camera snapping,
prioritizing smooth interpolation and player readability.
</p>
</section>

<section>
<h2>Technical Challenges</h2>
<p>
Implementing clean side-scrolling behavior in a 3D space required
careful control of movement vectors and camera alignment.
Balancing responsiveness with physical consistency was a key focus.
</p>

<p>
Working under a strict time constraint required prioritizing modular
system design and efficient debugging workflows.
</p>
</section>

<section>
<h2>Future Improvements</h2>
<ul>
<li>Expanded enemy behavior variety</li>
<li>Advanced movement mechanics (wall jump, dash)</li>
<li>Combat system extension (ranged attacks)</li>
<li>Level progression and checkpoint systems</li>
</ul>
</section>

<div class="footer">
© 2026 Michael Terrazi
</div>

</div>

</body>
</html>
