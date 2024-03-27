---
title: Yuna's blog post
published_at: 2024-03-27
snippet: About DMS1 assignment
disable_html_sanitization: true
allow_math: true
---

# Week 01 Session 01
![image 1](/s01w01/01.png)

![image 2](/s01w01/03.png)

![image 3](/s01w01/05.png)

![image 4](/s01w01/06.png)

![image 5](/s01w01/07.png)

![image 6](/s01w01/08.png)

In scavenger hunt, at first, we trying to find everything in the list order, but we quickly realized is impossible. So, the library as a place all the group members known, we started searching “a book containing Digital Media wisdom”. 

Then we found a book searching device and finds lots of book related to Digital Media wisdom.When we were walking out the library, we saw a vending machine in the corner. 

After this, we go downstairs and found the place for food, then we think we maybe can find “An explosive cup of coffee”, but all the coffee stores are closes so we took a photo with coffee machine. 

Then we read the list again, the last thing sounds so abstractive, and we don’t know where to go, but luckily, before the time out, we saw the roots, the gate and the chair and took these photos.



## Week 01 Session 02

**Editing Practice**[^1]

[30 sec footage](https://vimeo.com/927841223?share=copy)

[Pre-task](https://vimeo.com/921993721?share=copy)

[Class sound task](https://vimeo.com/927872572?share=copy)

About this task, I think is a good try but still have a lot of space to improve. 
First, I realised I’m too focused on the logic between the footages instead of describing something emotional. Second, about the editing technique, I think still need to try more and have more practice.
So in the following task, I will more focus on the meaning editing gave to the footage not the own storyline of the footages. 


Hyperlinks can be written like this: `[text](https://URL)`

You can find a markdown cheat-sheet [here](https://www.markdownguide.org/cheat-sheet/).

## Week 02 Session 01
**Storyboard**

![storyboard01](/s01w02/storyboard01.jpg)

![storyboard02](/s01w02/storyboard02.jpg)

![storyboard03](/s01w02/storyboard03.jpg)

![storyboard04](/s01w02/storyboard04.jpg)

To make the emotions behind the video has continuity, I will only use the state shot to do some match cut or quick cut to make the whole Video has a flow emotion.
In this project, the mean theme is “between” . In detail, this video will talk about the feeling between alive and death. There was a saying that when people fall in unconscious, they still have few second can hear the sound around and in the meantime they will recall all they’s lives. And this feeling is what the video will give to the audience.

At first, I will use seamless transitions between each footages, to blur the boundaries between different states of consciousness. This could involve fades, dissolves, or morphing effects to symbolize the fluidity between life and death.

Second, about the colour of footage, I will use cold tone to show the atmosphere of  detachment or otherworldliness.

Based on this I hope the audience can touch the feeling of unreal.

... which can be written inline, like this: $\{ x, y, z \} \in \N$

... or block, like this:

$$ x^2 + y^2 = z^2 $$

Visit [ $\KaTeX$ ](https://katex.org/docs/supported#fractions-and-binomials) for more information about writing maths.

## Week 02 Session 02

**Key moment**

![Key moment](/s02w02/key%20moment.jpg)

The key moment in the Video is the footage of  dragonfly. One symbolised falling into nothingness and another one means the mentally exist.

In the video I want to use the dragonfly as a symbol because in the dragonfly’s life cycle, involves a remarkable transformation from new-born to adult, symbolising the journey between different stages of existence. This transformation can mirror the theme of transitioning between life and death, highlighting the fluidity of existence.

For the visual design, The images of dragonflies will throughout the video as a visual clue, appearing in moments of  transformation. The sight of a dragonfly hovering between two worlds could serve as a  reminder of the connect between all things and the transient nature of existence.

**sound design**

*backgroung music chooseing*

There will be a main background music throughout the video.
To establish the mood and atmosphere of the memorise are passing by, the background music will be soft and ethereal. And it will start and fade out in a right time.

*Ambient Sounds*
 
About the ambient sounds, they will change with the sense, like at start to show a living’s life is vanishing, I will insert the sounds of heartbeat rhythms and the beeping of equipments. Meanwhile I will use L and J cut to transfer between the footage, for example, the audience may hear the heartbeat at first than see another sense about the dragonfly.

Via everything we mentioned above, the video will  evoke a sense of empty to lost as the feeling death bring us. And, the shots will be arranged to maintain a sense of flow and development, despite the protagonist's fragmented perception.

## Embedding video:

<iframe id="coding_train_video" src="https://www.youtube.com/embed/rI_y2GAlQFM?si=RDgjkpunxk1mQzMI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<script type="module">

    console.log (`hello world! 🚀`)

    const iframe  = document.getElementById (`coding_train_video`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16

</script>

## Embedding p5 sketches:

<iframe id="falling_falling" src="https://editor.p5js.org/capogreco/full/Fkg05m7aA"></iframe>

<script type="module">

    const iframe  = document.getElementById (`falling_falling`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16 + 42

</script>

## Canvas API

<canvas id="canvas_example"></canvas>

<script type="module">
    const cnv = document.getElementById (`canvas_example`)
    cnv.width = cnv.parentNode.scrollWidth
    cnv.height = cnv.width * 9 / 16

    const ctx = cnv.getContext (`2d`)
    const pos = {
        x: -100,
        y: cnv.height / 2 - 50
    }
    
    function draw_frame () {
        ctx.fillStyle = `turquoise`
        ctx.fillRect (0, 0, cnv.width, cnv.height)

        ctx.fillStyle = `hotpink`
        ctx.fillRect (pos.x, pos.y, 100, 100)

        pos.x += 2

        if (pos.x > cnv.width) {
            pos.x = -100
        }

        requestAnimationFrame (draw_frame)
    }

    draw_frame ()
</script>


