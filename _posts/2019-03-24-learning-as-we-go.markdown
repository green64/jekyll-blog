---
layout: "post"
title: Learning As We Go
date: 2019-03-24
permalink: "/learning-as-we-go"
---

![image](https://www.samanthamccallfp18.com/assets/images/learning_as_we_go.jpg)

### My tribute-flexbox-new-blog experiment failed. And that's OK. 

My blog image probably seems like an odd image &mdash; what's with the cats, amirite? This 
post was actually inspired by the death of my cat Posie. I had her for 19 years, and although 
it was time for her to go, I'm still sad. Her sister Parker died in 2013. 

Since everything in my life right now seems to find its way back to dev learning, I thought my 
tribute blog would be a great opportunity to combine some code I've seen but not tried writing. 
My friend Patrick has been experimenting with CSS-based slideshows, animation, and parallax 
and created some really cool stuff. Then there's CSS Flexbox and CSS Grid. Switching blog formats has made me think more about layout methods other than Bootstrap and Materialize. Throw in a little brush up on media queries, and this page could double as a useful learning exercise and a tribute to my sweet kitties Parker and Posie. What could go wrong? 

In a word, time went wrong. As in, I don't have enough of it. My blog is great for minimally formatted markup text. And although I've found workarounds for some minor things, like opening links in a new page, I still haven't figured out the stylistic differences between creating a markup page and an HTML one in Jekyll. Like anything new in coding, it's going to require time to fully figure out the differences. And this week I wanted to spend my time on CSS Flexbox and Grid. 

### CSS epiphanies

Once I'd ditched the idea of a combo blog/tribute, I did learn a lot this week about using exclusive CSS for slideshows and layout. For starters, you can use the transition property or the animation property plus keyframes to create CSS slideshows. Since I was already enamored with Patrick's use of a zoom effect that's created by using hiding part of the image then slowly panning in, I followed his lead and used keyframes. 

I also learned a lot about using CSS Grid and CSS Flexbox. What you lose in the convenience of using a Bootstrap or Materialize CDN you make up for in greater control and more understanding of everything happening on the page &mdash; because you put it there. 

I even learned you can give grid areas names, which comes in really handy at media query time. For example if you named the elements in your grid like this: 

    grid {
  grid-template-areas:
    'avatar name'
    'bio    bio';
}
    

... then you wanted to rearrange them for a smaller mobile viewport, you could do this:


    grid {
  grid-template-areas:
    'avatar' 
    'name'
    'bio';
}
    
My page is responsive, but I didn't use this particular trick because I wasn't sure how to handle unequal columns percentage-wise. But [grid-template-areas](https://thoughtbot.com/blog/concise-media-queries-with-css-grid){:target="_blank"} are definitely something I want to learn more about. 

### To blog or not to blog 

Despite everything I learned about CSS slideshows, Grid, Flexbox, and a dash of HTML5 (I used details/summary tags to show/hide the poems about Parker and Posie) I wasn't going to blog about it since I couldn't put it all in my new blog packaging. But then I read an affirming tweet today that said when it comes to acquiring knowledge, there's no shame in not knowing, only in remaining ignorant because "We're all learning as we go." Indeed. 

As always, thanks for reading. If you want to see the results of my knowledge acquisition, it's the newest addition to my portfolio page called [Ode to Parker and Posie](https://www.samanthamccallfp18.com/portfolio.html){:target="_blank"}. If you're a cat lover, stick around for the whole slide show. Parker and Posie are gone, but their brothers Snickers and Doodle were pretty cute kittens. :) 