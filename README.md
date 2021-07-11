# HackatoonButton
### *A website to randomly open interesting things across the internet. Submitted for the MLH Hackatoon 2021.*

# Instructions
Click on the website link: https://vishaaal.github.io/HackatoonButton/button.html

# How Is It Working?

One of the most common uses of a random engine is to create a random link out of a predetermined group of links. We specify in advance the URL's to be put in "black box", and have the random engine randomly draw one out to follow.

```js
function randomlink(){
    window.open(randomlinks[Math.floor(Math.random()*randomlinks.length)]);
}
```

### JavaScript Random Integers

`Math.random()` returns a random number between 0 (inclusive), and 1 (exclusive).

`Math.random()` always returns a number lower than 1.`

`Math.random()` used with `Math.floor()` multiplied with `randomlinks.length()` can be used to return random integers. 

Using those as indexes of the `randomlinks[]` can be used to point to that link stored in that index of the Array.

The `button` has an `onclick` event of `randomlink()` function, which when clicked by the user takes him/her to that link generated randomly.



# Why This Website?

Just have some fun while clicking through various websites and enjoy the unpredictability of a mere thing, as feeble as a button. 

After all a wise man once said:

> *The world is so unpredictable. Things happen suddenly, unexpectedly. We want to feel we are in control of our own existence. In some ways we are, in some ways we're not. We are ruled by the forces of chance and coincidence.* 
>
> ~**Paul Auster**

