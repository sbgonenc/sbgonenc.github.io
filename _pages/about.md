---
permalink: /
title: "Let's get acquainted! I am Berk!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
My name is S. Berk Gönenç
<span id="playAudioEmoji" style="cursor: pointer; text-decoration: underline;">
<span style="font-size: smaller; margin-left: 5px;">🔊</span>
</span>

<audio id="pronunciation">
<source src="/media/PTT-20240808-WA0001.opus" type="audio/mpeg">
Your browser does not support the audio element.
</audio>


<script>
  document.addEventListener("DOMContentLoaded", function() {
    var audio = document.getElementById("pronunciation");
    var emoji = document.getElementById("playAudioEmoji");

    emoji.addEventListener("click", function() {
      audio.play();
    });

    emoji.addEventListener("mouseover", function() {
      emoji.style.textDecoration = "none";
      emoji.style.transform = "scale(2.5)";
      emoji.style.transition = "transform 0.2s";
    });

    emoji.addEventListener("mouseout", function() {
      emoji.style.transform = "scale(1)";
      emoji.style.textDecoration = "underline";
    });  
});
</script>


I love:

&#128187;   programming and building stuff

&#128202;   analysing data to extract insights

&#129516;   thinking about biology problems

&#129518;   using AI models

&#128218;   learning new things

I am a **bioinformatician**, **computational biologist**, **Python developer** and an **AI enthusiast**!