---
theme: slidev-theme-janis
layout: intro
---

# Making youtube videos with markdown

## Using slidev and some fancy tricks!

### Janis (janis.me, mail@janis.me)

<!--
Heyho!

Nice to have you here. Today we'll talk about how to make youtube videos with Markdown. I will give this approach a try so that I can make high quality tech videos, but faster. In the past, I always edited the videos manually, which looks better, but it's not very efficient for tech content.

So today, I want to show you how I made this exact video using web technology and some awesome tools!
-->

---
layout: intro
---

# You'll be looking at

## Slidev, Shiki, Markdown, Vue and Typescript

<!--
You will be looking at 
- slidev by anthony fu
- the shiki syntax highlighter
- some markdown
- some tiny vue components, and
- typescript.
-->

---
layout: introVideo
---

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
