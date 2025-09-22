---
theme: slidev-theme-janis
layout: intro
---

<h1>
  <SlideIn v-click m-2>Making </SlideIn>
  <SlideIn v-click m-2 underline>awesome </SlideIn>
  
  <br />
  <SlideIn v-click m-2>presentations </SlideIn>

  <br />
  <SlideIn v-click m-2>with </SlideIn>
  <SlideIn v-click m-2 underline color="#72B7CF">Slidev</SlideIn>
</h1>

<SlideIn v-click>

## An intro to modern slideshows for developers - made with markdown

</SlideIn>

### Janis (janis.me, mail@janis.me)

<!--
Heyho!

Nice to have you here. Today we'll talk about how to make youtube videos with Markdown. I will give this approach a try so that I can make high quality tech videos, but faster. In the past, I always edited the videos manually, which looks better, but it's not very efficient for tech content.

So today, I want to show you how I made this exact video using web technology and some awesome tools!
-->

---
layout: intro
---

# We'll talk about

<v-clicks>

- What slidev is
- How to use it (in less than a minute)
- my ideal repository setup (don't be scared)
- Customizing themes, layouts.. everything

</v-clicks>

<!--
You will be looking at 
- slidev by anthony fu
- the shiki syntax highlighter
- some markdown
- some tiny vue components, and
- typescript.
-->

---
layout: center
---

<SlideIn>
  let's do this
</SlideIn>

---
layout: introVideo
transition: fade
---

---
transition: fade
layout: center
---

<SlideIn>
  A quick note
</SlideIn>

---
layout: two-cols-header
---

<h1 text-center>
This video is free, open source and interactive!
</h1>

::left::

<div text-center h-full flex flex-col justify-center>
  <SlideIn block v-click m-6>
    <fa7-solid:book text-4xl />
  </SlideIn>

  <SlideIn block v-click text-s m-1>
    janis.me/blog
  </SlideIn>
</div>

::right::

<div text-center h-full flex flex-col justify-center>
  <SlideIn block v-click m-6>
    <fa7-solid:code text-4xl />
  </SlideIn>

  <SlideIn block v-click text-s m-1>
    github.com/janis-me
  </SlideIn>
</div>

---

# Guess what

You're looking at it already. 😮

<v-click>
How this works:
</v-click>

<v-clicks>

- Slidev repo with custom theme and layouts
  - https://github.com/janis-me/slides
- Intro video embedded with a `<video>` tag
- Slideshow in markdown
- Screen-recorded with OBS

</v-clicks>

<v-click>
<br />
<br />
That's it!
</v-click>

<!--
And as you probably already guessed, everything you're looking at is built with these tools!

even the intro video was not cut in, but instead embedded as an HTML video element.
To make this work, I set up a small repo with some slides and a custom slidev theme/layout. For the intro, I just embedded the video and made it autoplay. 
And right now, I'm doing the voiceover and am recording the slideshow... as you can hear
-->

---
-->
---

# Some code

```ts
const x = 1;

export default function fraaiaia(test: number) {
  console.log('hey');
}
```
