# Mirthy
A reusable set of styles and components meant to bring much mirth to the masses.

## Please god no
To my chagrin, I exist in a world where I regularly have to use CSS. It's not a bad tool, mind you. In fact, it has a lot of genuinely fantastic design decisions—like it being declarative. It's more a victim of the environment in which it exists, where developers are guaranteed to run into niche and infuriating problems. 

For instance, the behavior of the line-height property. It has no effect on an input element, but it somehow affects a button element just fine. Now, picture yourself trying to align a button and input to achieve the same height, without explicitly defining exact heights. As someone who (perhaps inadvisably) recoils at the thought of specifying pixel or rem values in CSS, I wish there was a solution that *just worked*. And that's just one example—the implementation of CSS standards are plagued with this sort of thing, like a victorian-era child, lungs filled with soot, coughing incessantly. And if you're enough of a fool to look into browser differences, be careful to avoid wanting to slam your skull against concrete.

In my estimation, the world of the browsers and the world of the designer are fundamentally at odds. The designer wants consistency, reliability, and perfection, and the browsers guarentee the designer will never attain them. Consistency gets pissed away the second you realize browsers just flagrantly decide to *mangle away* parts of your website. And, god forbid, you consider the mobile browsers. You might even get your site looking *perfect*—exactly how you wanted it—only to find that some specific device mangled it in a way you didn't think to check. Because, well, who in their right mind goes "Ah, yeah, I should check whether iOS Safari wants to shit in my mouth and fuck my mother by making every button look like a prolapsed anus"? No one! Not a single person. And yet we chug along. With our bandaids and our fixes and our structures and mental models, all in a vain attempt to patch a big Mickey Mouse bandaid on a flesh-wound sized problem. Alas!

## So what?
This repository fixes none of the aforementioned problems. Not a single one. I'm just using this space to complain. 

All this repository is a consistent set of styles and components for me to use across my projects. These aren't production-ready and likely never will be. These pages are alive—living documents—where I'll update and tinker with CSS and different stylings to allow for consistency across my differen creations.

I don't have enough experience with SemVer or the attention span to find out about it, but this project is version as follows: 

`MAJOR.MINOR.PATCH`

- Patch: for small fixes or adjustments that don't require changing the HTML of any corresponding web page. Everything should just work—while maybe looking a tad nicer than before
- Minor: something new that may or may not require changing the HTML of any coressponding web page. Maybe some new classes for a previously unstyled(or just indirectly styled) element.
- Major: the real shake-ups. This is the bullshit that I'll have to crawl an entire website after doing, making sure nothing is super-duper broken.

Welcome to v0.1.0. Most of this is a sloppily-thrown-together mess that you shouldn't bother trying to use. For the most part, a lot of this will be me really getting my hands dirty and learning CSS. That also means you're guarenteed to find absolutely zero best practices. If I have done something right, I promise you it was by accident. This code is known to the state to cause cancer birth defects or other reproductive harm. Have fun.

If you're reading this before there's any styles within the repo, that means I'm still refactoring [mirth.cc](https://mirth.cc) to fit the styles. Go check the site out if you want to know what things'll look like.
