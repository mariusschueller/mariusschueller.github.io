---
title: "Pickleball Paddle"
excerpt: "Creating a Pickle Ball Paddle"
header:
  teaser: /assets/img/paddle1.jpg
gallery:
  - image_path: /assets/img/paddle2.jpg
  - image_path: /assets/img/paddle3.jpg
  - image_path: /assets/img/paddle4.jpg
   
---

<br>
<img src="/assets/img/paddle1.jpg" style="border-radius: 20px;">

<br>
# Overview
Pickleball is a racket sport that has been rapidly growing in popularity. The game is played with a hollow ball and a paddle. Pickleball paddles are made of plastic and are a fairly simple design. So, here is a pickleball paddle that can be used in the sport.

<br>
# Design
## Adhering to the Rule Book
There are many regulations for a pickleball paddle according to the <a href="https://usapickleball.org/docs/USA-Pickleball-Official-Rulebook-2024-v1.pdf">USA Pickleball Official Rulebook</a>. The three main specifications are material, surface, and size. The material used in paddles is open to anything deemed safe. This can be summarized into non-compressible, rigid material. For my design, PLA fits this criteria as a rigid material. The surface must be flat and consistent. This means that the paddle cannot contain holes or cracks. In addition, the surface cannot allow any excessive spin on the paddle. Using 3D printing methods, this can be achieved assuming no printing issues. For size, the combined length and width of the paddle cannot exceed 24 inches (60.96 cm). My paddle's maximum combined length and width is 47.3 cm. In addition, the length cannot exceed 17 inches (43.18 cm). My paddle's length is 27.3 cm. Therefore, my paddle follows all the rules set in the pickleball rulebook.

<br>

## Handle
For my grip, I used a multi-material grip. This allowed me to use both rigid and flexible components in my design to enhance its capabilities. The flexible components on the handle allow for a better grip on the material because the flexible material can conform slightly to a person’s hand when gripping. The flexible material is made out of TPU. The rigid component will provide structural support for the rest of the handle. The rigid material is made out of PLA. Using multiple materials works great in this situation because creating the handle entirely out of TPU would lead to a flimsy handle. In contrast, a PLA handle would be very rigid and more difficult to grip. The flexible and rigid components are joined together using 4 dovetail joints that run through the handle. These joints provide a secure connection between the two types of materials which stay securely joined when playing. The handle is designed to have three main divots for the fingers to grip onto. 

<br>
## Edge Guard
An edge guard was also added to the design. An edge guard protects the paddle when hitting something that could damage the pickleball paddle. As previously stated, surface imperfections can disqualify a paddle from use, which reveals the importance of the edge guard to the paddle. The edge guard created in this design is removable and can be interchanged with other similarly designed edge guards. The edge guard was made out of TPU with an infill of 30%. The guard simply slides onto the paddle through the handle. The flexible material can flex to fit around the rigid part of the paddle. The compression between the top of the edge guard and the bottom contract upon each other to keep the edge guard secured. To remove the edge guard, simply stretch to the top part of the edge guard to remove it from the paddle surface, and slide the edge guard back through the handle.

<br>
## Weight
Factoring in the initial weight estimations of the PLA material, it was clear that a heavy design would be the best implementation. The weight designations of pickleball paddles are less than 7.3 oz for lightweight, 8.3 oz for heavy, and in between for midweight. Typically, lightweight paddles, are designed for enhanced agility and control, albeit at the expense of power. Conversely, heavy paddles prioritize power, albeit at the cost of some maneuverability. Meanwhile, midweight paddles strive to strike a balance between power and control, catering to players who seek a harmonious blend of both attributes. Based on the printing weight given in Superslicer, my paddle weighs a total of 395.43 g. The playing surface weighs 323.76 g. The handle weighs 71.67 g. Consequently, the resultant weight (13.95 oz) exceeds the 8.3 oz threshold required for classification as a heavy paddle, aligning with the choice of maximizing power during gameplay.

<br>
## Mass Balance
According to this (ADD ANCHOR TAG) article, there are two types of mass balances: “head light” and “head heavy”. A head heavy paddle means that there will be a heavier swing weight which will result in “slower” play. It will make the paddle harder to move and change directions but will increase the power of the swing. Because the weight of my paddle is optimized for power, it was clear that a swing weight optimized for power would also be preferred. The article illustrates that a 5:8 ratio for the top of the paddle is needed for a "head heavy" paddle. This means that the top half of the paddle should make up about 62.5% of the total paddle’s weight. The process for aligning these weights was splitting up the top and bottom half of the paddle and seeing how changing the infill impacted the estimated weight distribution of the print. With 70% infill for my playing surface piece, the top half weighs 247.53 g, and with the total weight being 395.43 g, the top half of the racket is approximately 62.6% of the total racket's weight.

<br>

# Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ed01c68891f80f6b9?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<br>


{% include gallery caption="Pickleball Paddle Images" %}

