# @JRCharney

I am **Jason Charney** (@JRCharney).

## Current Programming Interests
- **HTML5**
- **CSS3**
- **HTML5 Canvas from scratch.** Not all the time but with those drawing that should be simple.
- **SVG from scratch.** Again, not all the time, but with those simple drawing.
- **JavaScript (especially functional programming).** All your `.filter()`, `.map()`, and `.reduce()` are belong to us!
- **Node.js** to make use of that JavaScript on the server side.
- **JSON** is fun to tinker with if you import it from a separate file.
- **Git** to keep my skills here sharp
- **[Leaflet](https://leafletjs.com/) and [OpenStreetMaps](https://www.openstreetmap.org/)** - I recently worked on a Bootcamp project that reignited my interest in it.
- **[OpenWeatherMap](https://openweathermap.org/) and [National Weather Service API](https://weather-gov.github.io/api/)** - Another project that fulfilled a long time dream uses OWM, but I want to transition the app to use the NWS API.
- **[Ruby](https://www.ruby-lang.org/).** Simple functional programming. A lot easier to pick up than [Haskell](https://www.haskell.org/). [This site](http://learnyouahaskell.com/) does help with learning Haskell, but have you downloaded a program that uses Haskell. It's Dependency Hell!
- **[Python](https://www.python.org/).** Trying to learn it. It's not hard. It's just trying to find time to do it. I bought a book on it right before I started the Wash U Bootcamp thinking I was going to spend my autumn (2022) finally learning how to use this.
- **Markdown with LaTeX and [Mermaid](https://mermaid-js.github.io/)**. Did you know you can add Math and Diagrams?  Check this out!

$$
\begin{aligned}
\text{For } u = f(x), v = g(x) \\
\frac{d}{dx}(u \pm v) &= \frac{du}{dx} \pm \frac{dv}{dx} && \text{Sum/Difference Rule} \\
\frac{d}{dx}(u \cdot v) &= \frac{du}{dx} \cdot v + u \cdot \frac{dv}{dx} && \text{Product Rule} \\
\frac{d}{dx}\left(\frac{u}{v}\right) &= \frac{\frac{du}{dx} \cdot v - u \cdot \frac{dv}{dx}}{v^2} && \text{Quotient Rule}, v \ne 0
\end{aligned}
$$

```mermaid
flowchart TD
intro([Start])
q1{{Gee Brain, what do you want to do tonight?}}
s1(The same thing we do every night, Pinky. Try to take over the world!)
s2(Nothing)
s3(Plot for world domination)
q2{{Did it work?}}
s4(Victory!)
s5(Failure)
s6(Come, Pinky. We must prepare for tomorrow night.)
q3{{What are we going to do tomorrow night, Brain?}}
s7(Resign to my failures)
s8(The same thing we do every night, Pinky. Try to take over the world!)
ending([Ending])

intro-->q1
q1-->s1
q1-->s2
s1-->s3
s3-->q2
q2-->s4
q2-->s5
s5-->s6
s6-->q3
q3-->s7
q3-->s8
s8-->q1
s2-->ending
s4-->ending
s7-->ending
```

Pretty cool, right?

## Things you should know about my programming style

### I rarely use CSS Frameworks (e.g. Bootstrap). 
It's easier just to make something up from scratch.  Seriously.

If you look at my more recent projects I've done with the Washington University of St. Louis Coding Bootcamp, you will notice that I use the same stylesheets.

In most cases, I just compartamentalize my CSS code based on major componets, establish a color scheme, reuse previous animations.

Styling the Bootstrap way defeats having a stylesheet in the first place, is like writing code in HTML4 (which was deprecated over 20 years ago), and frankly you should have your own library of styles anyway to define yourself as a web developer.

### I eschew installing every plugin.

There was a quote from *The Dilbert Future* by Scott Adams (before he became what he is now): 

> "In the future, technology will make us less productive."

And he was right. Some plugins in VS Code just WRECK code and also break the automatic text insertion. Do I want to use plugins that make sure I didn't forget to use colon, comma, or semicolon somewhere? Yes. Do I want it to turn my short one-liners into multi-line code? No.  Do I want it to insert a block of Bootstrap code I'll never use. ABSOUTELY NOT!  And I especially don't like it when I format my code a certain way that I know is functionally perficient only for the indenting to be undone by some plugin written by some screwball who peaked in high school.

The whole point: Don't install every plugin. There's a lot of stuff the Prettier folks got wrong.

* [Emmet](https://emmet.io/) is good for writing code.
* [JsDoc](https://jsdoc.app/) is good for documenting your JavaScript.
* [Jasmine](https://jasmine.github.io/) is good for Node Unit Testing.

### I prefer Linux.

Did you know I was turned down for a job once because I didn't own a Macbook?  I believe code should work on ANY operating system, but prefer to develop it on Linux.  You shouldn't have to take out a huge loan to buy a computer.  And you shouldn't be turned down for a job because you don't own an overpriced laptop.

Of course, the company seemed more like it was more interested in playing air hockey than it was writing code anyway. Their loss!

### I won't relocate the West Coast or North East
The reason: COST.

The problem isn't that I'm too stubborn to move, it's just that what makes more sense: Paying $3 for gas in St. Louis or $8 for gas in San Jose? You don't need to be an economist to figure that out.

### The Tech Industry is fine. It's BIG TECH that's screwed.
The New York Times recently published that Computer Science Majors were going to have a hard time finding a job.  I've had my BSCS since 2007, and the only thing I've found out that impeded me from getting a job in the tech industry is the LACK of a tech industry because of an emphasis on relying on Big Tech.

But here's the problem with that.

**The smartest people in the room are NOT the ones with all the money.**

> Caution, short rant ensues.

There's the saying "If you're so smart, why aren't you rich?"  The saying should be "If you're so rich, why aren't you smart?"

Mark Zuckerberg admitted in November 2022 that he screwed up going all in on his Metaverse nonsense.  Anyone who grew up and remember the VR Bubble of the 1990s could have told you that.

Elon Musk is going into some serious legal trouble since he bought Twitter from Jack Dorsey in late 2022.  Social medial is a mess right now, espeically after Elon fired all the people who needed to be there to keep Twitter going.

Netflix is suffering because when you threaten people who use it with a VPN or who share passwords with family and don't offer a way to migrate or separate accounts, folks are going to flock to other streaming services.  It sucks we have so many streaming services! Especially since the media companies in charge of them (Disney, Discovery-Warner Bros., Paramount) don't want to pay creators, are destroying content for tax write offs (espeically anything where a lot of animation and visual effects were involved), increase prices, insert ads, and then wonder where all your customers are.

Amazon, I know everything is going to streaming, but there's something inhertedly wrong when you need to find a used book store or video store that is still around to get physical copies of stuff because the digital copies are being destroyed by order of the massive conglomorate that promised that they wouldn't remove it. (I'm looking at you David Zaslav of Discovery-Warner Bros!)  So start making a list of all the classic movies you like, and get a copy or make sure there's a copy at your local library in their video section.

Para-social relationships with billionaires are unhealthy!  Elon Musk is NOT your friend.  Jeff Bezos doesn't own you anything.  The Cloud where all the streaming content is located is actually someone else's computer and that somone else doesn't want to pay to host it anymore because they'd rather keep the money for themselves.

So stick it to these mostly-baldheaded men, pirate everything! Or at very least, buy a physical copy.  No more lost media!

Once that is done, invite some friends over to watch stuff.  It's time we started getting together and watching movies again.

## Websites
- 🚧 [JRCharney.com](https://www.jrcharney.com/) 🚧 - It's been a while since I've updated this.
- [Dev.to/JRCharney](https://dev.to/jrcharney)
- [Codepen.io/JRCharney](https://codepen.io/jrcharney)
- 🚧 [JRCharney.github.io](https://jrcharney.github.io/) 🚧 - Under Construction
  - [Bootcamp Portfolio](https://jrcharney.github.io/bootcamp-portfolio/) - Eventually this will replace that.

## Education Background
- 2007: Maryville University, St. Louis, MO, Bachlors of Science in Computer Science
- 2020: LaunchCode Alumni, St. Louis, MO
- 2022-2023: Washington University of St. Louis, Coding Bootcamp, St. Louis, MO

## Contact
You can contact me here. I have a [LinkedIn](https://www.linkedin.com/in/jasoncharney/) profile, but that website sucks. It's such a crappy play.

