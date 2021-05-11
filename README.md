**Table Of Content**
- [Info](#info)
- [Resit](#resit)
  - [Result](#result)
  - [Tip Top Improve](#tip-top-improve)
  - [Insight](#insight)
  - [Misc](#misc)
# Info

[cloned repo](https://www.github.com/cmda-minor-web/css-to-the-rescue-2021)

The core of this subject is to stress on CSS. We aren't allowed to use any JavaScript for interaction and have to find alternatives for those interactions.

The goals for this subject is as following:

- Experiment with CSS-techniques that are new for you.
- Know the full extent of CSS, that CSS is not just for styling.
- Understanding of the interaction techniques from CSS (and HTML). UX is humane within the chosen context(s).
- Progressive enhancement is elegantly applied. You can show how cascase, inheritance and specificity works.

There are two restrictions in this course:

1. Don't use `id="id"` or `class="class"`. The reason for this restriction is so we practice with the CSS selectors.
   - The caveat for this restriction is the `:target` selector which requires an ID.
   - If you don't see a way out without ID's or classes, follow the following steps:
     - Google it
     - Ask students
     - Ask teachers
     - Use class or ID.
1. Don't use JavaScript. If you plan to use interaction which isn't achievable by using CSS, scrap that interaction.

---

# Resit

[Before the resit (Week 1 to 4).](https://github.com/dewarian/css-to-the-rescue-2021/blob/master/V1-README.md)
## Result

Two distinctive variants of a menu. A light variant that would fit the restaurant or canteen of Apple Park. And a weird Dark variant that plays with animations and transitions.
![](https://cleanshot-cloud-fra.s3.eu-central-1.amazonaws.com/media/4504/HWtmTyEnGXkWHP5AuA8oIH2LUeJzMAHYpq0USwJA.gif?X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aDGV1LWNlbnRyYWwtMSJHMEUCIQCytekVHL%2B06yiJnscq8MGTGSkNEKW9az1pdcWEB9OzcAIgabq5o%2BSvqUgsE%2BZcCh0BLj0P%2BTZHiWe5IvfsoYoEyOQq4gEIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw5MTk1MTQ0OTE2NzQiDHtEGgVZwyjcSzKecCq2Aad7GdN0adbKRgjAK9uHqB8He4DKCsMTQvKPpT6ghIz2tO7qRNhK4zucMFMhYnynf45uFd2vKbgSEtahS97TPc5BqvSkLd4P2rqTCk2plDwgzs1fkSiqt%2Fy0VWo9xJzPZ04%2F7lg7l7zXfT2psKh%2B9SAh7dIRQ8tFOYfVPTE%2FR6Kazw3JWwMVG17XtoylxKexlE9PNdVoDWuQberlhWpUSxPn6IYGUIbJEcqKxtAgu3K1agvIhUGYMLi96oQGOuAB2MjwtF%2BepmmtTokx6DS5HPulrttUaot0QdlKdrfnxp8n4x4NMJNmaeenyGao6RqAgdADQqmB7DRocd5%2FikRbJcebtYAB8F%2BnXriUAwOt5Zovsre5%2FODz4gmdhbDEdE9ieVDwOe8d6Yt4gjPDwSrNqaK4m%2BvKwGhckMg8TOvYKSwC2uU5AYaHqw0d9Hs0%2F9yok4B4dlM70ow%2BIM0PiGOaJmkgdnlcPG4oRD91aumupQNUXyNC%2BkagmGFeJnepBMFxkUvLs5IlfO%2Btl1Fx7e0ksiPBzl%2FxroAcr4fBdwItk2c%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIA5MF2VVMNNGR2R4YN%2F20210511%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20210511T155048Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Signature=004dbd08d1f551e314b09c0eda912abe357ed74908d02fa596e6812e87e41e80)


## **🔎 Contexts**

The following media features have been used in this concept:
* `@media (prefers-color-scheme: dark | light) {}`
  To create two distinct variants of the menu.
* `@media (pointer: coarse) {}`
  To detect whether the user is viewing this concept on a touchscreen or not.

## **🚫 Restrictions**
* Responsive without mediaqueries.
  To create a website that is responsive on all screen sizes without the use of `@media screen (min-width: VALpx) {}`.
* Two colours.
  Creating a website that uses just two colours: hsl(18, 93%, 82%); and 


## **👏 Proud**
On what am I proud

Making the sections look like macOS windows, The part with header was especially tricky, because I didn't want to add extra elements to create it I had to think about adding it in another way. I saw a codepen about `repeating-radial-gradient` and thought of using it as a button, the button starts with black, goes to a colour, and ends in a transparent.

The transparent is there to remove the square of the gradient, making it look like its just a circle.

## **😥 Difficult**
What was difficult

Creating a heading with cartoon pop-up stylistic elements.

![image](https://user-images.githubusercontent.com/13199349/117880466-71e4c500-b2a8-11eb-911c-54d934d65c80.png)

To get a similar effect I had to use text-shadow MANY MANY MANY times to get close, but always ended up looking like a staircase. I also did not fully understand the positioning besides the basics (offset-x, offset-y).



```CSS
      text-shadow:
        -1px 0px var(--accent-400),
        -2px 1px var(--accent-400),
        -3px 1px var(--accent-400),
        -4px 2px var(--accent-400),
        -5px 3px var(--accent-400),
        0px 1px var(--accent-400),
        -1px 2px var(--accent-400),
        -1px 3px var(--accent-400),
        -2px 3px var(--accent-400),
        -2px 4px var(--accent-400);
```
![image](https://user-images.githubusercontent.com/13199349/117880990-fe8f8300-b2a8-11eb-8d89-a9a8113d7cde.png)


## **✨ Smooth**
What went well?

The accidental realisation that gridding the section in rows create this restaurant menu looking style. The demerit of this is that it only truly looks like a menu card if I add unsupported grid attributes.

## Insight
What did I realize with CSS?

Chaining CSS parameters, Never did I know that this was possible. See example with 
<p class="codepen" data-height="265" data-theme-id="dark" data-default-tab="result" data-user="dewarian" data-slug-hash="WNpQBbz" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="example text-shadow">
  <span>See the Pen <a href="https://codepen.io/dewarian/pen/WNpQBbz">
  example text-shadow</a> by Dewarian (<a href="https://codepen.io/dewarian">@dewarian</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

## Misc
What else do I want to do with CSS.

I would like to do more with animation and transition, creating abstract living shapes, without adding extra elements.

e.g. the following screenshot:
![image](https://user-images.githubusercontent.com/13199349/117882928-1d8f1480-b2ab-11eb-8e79-a5a83f1e3816.png)


Snapshot before altering the light mode version.
![image](https://user-images.githubusercontent.com/13199349/117823347-a8511e80-b26d-11eb-949a-1a5dd40d20bd.png)

https://cln.sh/vBMELQ