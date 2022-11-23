---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download my full resume from <a href="https://github.com/Rahpeima/required/files/10046110/CV-Uni.pdf" target="\_blank" style="color: #B509AC; text-decoration:none">here</a>.


<h1>Hello world</h1>
<p class="text">
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Perferendis
    veritatis animi aliquam laboriosam velit, esse, blanditiis aspernatur sint
    est magnam debitis delectus in fuga fugiat repellat dignissimos ipsum
    necessitatibus corrupti veniam reprehenderit,<span class="dots"> ...</span>
    <span class="moreText">
        assumenda sapiente expedita labore atque! Sint velit cumque minus
        pariatur quisquam, beatae ab quo impedit eaque soluta vel laboriosam
        itaque similique iste ex aut in nihil dolorem consequuntur possimus
        eligendi eos optio ipsam! Sint ullam voluptate obcaecati asperiores eos
        vero sed iusto magnam ad, vel repellat quidem? Omnis fugit accusantium,
        illo quos eos odio consectetur et nemo excepturi deleniti dolorum
        adipisci dolores delectus possimus libero, sed iusto dolorem? Lorem
        ipsum dolor sit amet consectetur adipisicing elit. Reiciendis neque
        distinctio modi dicta ut aperiam molestiae quos incidunt dolore iure
        officia! Blanditiis sint delectus quam quae nulla.</span
    >
</p>
<button class="read-more-btn">Read More</button>

<html>
<body>
body {
    font-family: "Montserrat";
    text-align: justify;
    max-width: 800px;
    margin: 0 auto;
    background-color: rgb(18, 23, 27);
    color: aliceblue;
}
.text {
    font-size: 24px;
}
.moreText {
    display: none;
}
.read-more-btn {
    padding: 15px 60px;
    background-color: rgb(149, 170, 197);
    color: rgb(53, 49, 49);
    border: none;
    outline: none;
    font-size: 20px;
    cursor: pointer;
}
.text.show-more .moreText {
    display: inline;
}
.text.show-more .dots {
    display: none;
}
</html>
</body>
<script>
const readMoreBtn = document.querySelector(".read-more-btn");
const text = document.querySelector(".text");
readMoreBtn.addEventListener("click", (e) => {
    text.classList.toggle("show-more");
    if (readMoreBtn.innerText === "Read More") {
        readMoreBtn.innerText = "Read Less";
    } else {
        readMoreBtn.innerText = "Read More";
    }
});
  </script>
