# Purrfect Cats: Your First Webpage
This is an already set up project folder to create your first webpage from start to finish on your own.
Follow the instructions to complete the assignment. You can use the webpage that we worked on in class as a guide but try to figure it out first without referencing it.


## Setting up
1. Open up index.html
2. Add a webpage title
> The Top 5 Purrfect Cats

3. Note that style.css is already linked and ready to go
4. Look in the images folder- note that there are already 5 images of varying sizes within there


## Adding a header
1. Add an `H1` tag with the name of the webpage
2. Add a `H4` tag with the following:
> The Internet exists to share pictures of cats with the masses. This webpage is no exception. Here is a list of 5 purrfect cats, in no particular order.


## The Cool Cat
1. Add an `H2` tag with the headline:
> The Cool Cat

2. Add a `P` tag with the following:
> The Cool Cat is one who doesn't care. He can often be found wearing aviator glasses, sporting a radical haircut, and hanging out in local coffeeshops. He only drinks craft beer.

3. Add an `img` tag that links to _coolcat.jpg_


## The Lazy Cat
1. Add an `H2` tag with the headline:
> The Lazy Cat

2. Add a `P` tag with the following:
> The Lazy Cat can be found sitting on porches all day long. She is always up for a long brunch and will bring the best snacks to parties. She also really needs a haircut.

3. Add an `img` tag that links to _lazycat.jpg_


## The Hairless Cat
1. Add an `H2` tag with the headline:
> The Hairless Cat

2. Add a `P` tag with the following:
> The Hairless Cat is the one who will always ask to borrow your sweater. She hates winter and would rather go to the dentist than live in a place where it snows all the time. Pro tip: scarves make the best gifts.

3. Add an `img` tag that links to _hairlesscat.jpg_


## The Sleeping Cat
1. Add an `H2` tag with the headline:
> The Sleeping Cat

2. Add a `P` tag with the following:
> The Sleeping Cat's ability to fall asleep literally anywhere will both impress and drive you nuts. While you fidget all night on a red eye from the west coast, he will get an amazing 8 hours sleep. Damn you, Sleeping Cat. Damn you.

3. Add an `img` tag that links to _sleepingcat.jpg_


## The Kitty Cat
1. Add an `H2` tag with the headline:
> The Kitty Cat

2. Add a `P` tag with the following:
> The Kitty Cat might be the most purrfect cat of all. Her real name is Rue but everyone calls her Kitty. She belongs to Lexi and loves to curl up in your lap and take a snooze. When left alone, she turns into a tiny terror.

3. Add an `img` tag that links to _kittycat.jpg_


## Attribution
One of the most important rules of the web is to cite appropriately and give credit where credit is due. So lets be kind and give attribution to the great people who provided these images.

1. Add a `br` tag after all of your content about cats to give it room

2. Add a `P` tag with the following:
> All photos were used with permission from the incredibly awesome site, Unsplash.

3. Add an `href` link and have it open in a new window
> https://unsplash.com/  


## Styling your page
In your style.css file, lets add the following styles to make our make look a little more fun:

1. Give the `body` attribute the following styles:
- Make the font `Trebuchet MS`
- Give it a color of `dimgray`
- Make the text centered
- Add 25% padding to the left and right

2. Style the `H1` as follows:
- Give it a color of `orangered`
- Make the font size 50px
- Make it all uppercase

3. Style the `H2` as follows:
- Give it a color of `teal`
- Make the font size 35px
- Make it all uppercase
- Add 30px of padding to only the top

4. Style the `H3` as follows:
- Make it all uppercase

5. Give the `img` the following styles
- Set the width to 100%  
- Set the height to auto

## Bonus Styling
If you have time, make page responsive (working on all devices) by adding something called a media query. For this example, the only thing we really need to change is to remove the body padding that we set at the beginning. So that when the page is viewed on a mobile phone, there wont be a ton of white space on the left and right side. Add the following code to the bottom of your stylesheet. You can read more about them here: https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries

 ```css
 @media(max-width:767px){
   body {
     padding: 0px;
   }
 }
```
