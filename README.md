<html>
<head>
<meta charset="utf-8">
<title>Mahatma Gandhi - Tribute page</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<main id="main">
<header>
<h1 id="title">Mahatma Gandhi</h1>
</header>
<p class="subtitle">A peaceful leader</p>
<figure id="img-div">
<a href="http://philogalichet.fr/wp-content/uploads/2019/01/Gandhi_Photo-Alamy.jpg" target="_blank">
<img class="lift-animation" id="image" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Mahatma-Gandhi%2C_studio%2C_1931.jpg/480px-Mahatma-Gandhi%2C_studio%2C_1931.jpg"
alt="A black-and-white photograph of Mahatma Gandhi wearing a stole."/></a>
<figcaption id="img-caption">Photograph of Mahatma Gandhi, London, 1931</figcaption>
</figure>
<section id="tribute-info">
<h2>A brief summary of Gandhi's journey</h2>
<h3>Early life</h3>
<p>
Mahatma Gandhi was born on October 2, 1869, in Porbandar, India, which was then part of the British Empire.
Although young Gandhi wanted to become a doctor, his father, who served as a chief minister in Porbandar, persuaded him to study law.
After 3 years of studies in London (where he became a vegetarian), Gandhi came back to India and tried to start his career as a lawyer.
</p>
<h3>South Africa</h3>
<p>
After struggling to find a job in India, he went to South Africa for a one-year contract to perform legal services. 
Gandhi was there confronted with discrimination against Indian immigrants by British authorities. 
At the end of his contract, Gandhi fought against a bill that would ban Indians from voting. 
Although he didn't stop the bill from passing, it initiated his fight for equality of human rights.
</p>
<h3>Return to India</h3>
<p>
In 1914, Gandhi sailed from South Africa to India, where he founded an ashram that was open to all castes.


</p>


</p>
<h3>India’s Independence</h3>
<p>
After a series of protests, India's independence was inevitable.
The Government of India Act (1935) surrendered significant amounts of power to Indians, and the Indian National Congress clamoured for more.
But after World War II Muslim League demanded that a separate state be created for India's Muslims, and to Gandhi's great distress, the Congress leaders agreed.
In August 1947, India was finally independent, not as a whole but divided into two countries, India and Pakistan. 
</p>
<h3>Assasination</h3>
<p>
Gandhi was assassinated by a Hindu nationalist, Nathuram Godse, in Delhi on January 30, 1948.
Godse stated that he killed Gandhi because of his complacency towards Muslims, holding him responsible for the frenzy of violence and suffering.
Gandhi's death was mourned nationwide, and over a million people joined the five-mile-long funeral procession that took over five hours. 
</p>
<h3>Legacy</h3>
<p>
Gandhi's commitment to nonviolence and his belief in simple living — making his clothes, eating a vegetarian diet — has been a beacon of hope for oppressed people around the world for decades to come after his death.
Gandhi's actions inspired future human rights movements around the globe, including those of civil rights leader Martin Luther King Jr. in the United States and Nelson Mandela in South Africa. 
</p>
</section>


<a href="https://wisdomquotes.com/gandhi-quotes/" target="_blank">
<blockquote class="lift-animation" cite="https://tanvi-gadhiya7.medium.com/in-a-gentle-way-you-can-shake-the-world-mahatma-gandhi-he-4de151cbba58">
<p>"In a gentle way, you can shake the world."</p>
<cite>- Mahatma Gandhi</cite></a>
</blockquote>
</main>
</body>
</html>
CSS code 
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP&family=Noto+Serif&family=Playfair+Display:ital@1&family=Roboto+Mono&family=Special+Elite&family=Zilla+Slab&display=swap');
html {
font-family: Noto Serif, serif;
font-size: 10px;
font-weight: 150;
color: black;
background: url(https://images.rawpixel.com/image_800/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIyLTA1L3B4NjUwODQ3LWltYWdlLWpvYjYzMC1hXzIuanBn.jpg);
}
body {
font-size: 1.6rem;
margin: 0 auto;
width: 70vw;
text-align: center;
}
@media (max-width: 768px) {
body {
width: 100vw;
}
}
@media (min-width: 1200px) {
body {
max-width: 700px;
}
}
a {
color: black;
text-decoration: none;
}
h1 {
font-family: Noto Sans JP, sans-serif;
font-size: 4rem;
color: black;
}
.subtitle {
font-family: Noto Sans JP, sans-serif;
font-size: 2rem;
color: black; 
}
h2 {
font-family: Noto Sans JP, sans-serif;
font-size: 2.8rem;
margin: 50px 0 25px 0;
text-align: center;
}
h3 {
font-family: Noto Sans JP, sans-serif;
font-size: 2rem;
font-weight: 600;
margin: 40px 0 5px 0;
color: black;
}
section {
text-align: left;
}
#image {
display: block;
max-width: 100%;
height: auto;
margin: 0 auto;
border-radius: 25px;
}
#img-caption {
font-family: Noto Sans JP, sans-serif;
margin-top: 20px;
}


blockquote {
font-family: Special Elite, sans-serif;
font-size: 2.25rem;
background-color: ghostwhite;
margin: 30px 3% 0 3%;
padding: 10px 0% 20px 0%;
max-width: 100%;
height: auto;
border-radius: 25px;
background: url(https://i.pinimg.com/originals/10/f9/44/10f944389ace361ae00a3fc6b7b16e9e.jpg)
}
cite {
font-family: Noto Sans JP, sans-serif;
font-size: 1.6rem;
}


.source-image {
width: 200px;
height: 100px;
border-radius: 15px;
background-color: white;
margin: 0 10px 50px 10px;
}
.lift-animation {
box-shadow: 0 1px 2px rgba(0, 0, 0, 0.322);
-webkit-transition: all 0.6s cubic-bezier(0.165, 0.84, 0.44, 1);
transition: all 0.6s cubic-bezier(0.165, 0.84, 0.44, 1);
margin-bottom: 30px;
}
.lift-animation::after {
content: "";
position: absolute;
z-index: -1;
top: 0;
left: 0;
width: 100%;
height: 100%;
box-shadow: 0 15px 15px rgba(0, 0, 0, 0.322); opacity: 0;
-webkit-transition: all 0.6s cubic-bezier(0.165, 0.84, 0.44, 1);
transition: all 0.6s cubic-bezier(0.165, 0.84, 0.44, 1);
}
.lift-animation:hover {
box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.377);
-webkit-transform: scale(1.03, 1.03);
transform: scale(1.03, 1.03);
}
.lift-animation:hover::after {
opacity: 1;
}
