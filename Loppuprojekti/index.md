## Oula Nikkinen web-tehtävä
### Jaon palikat/kappaleet sillee mukavasti että isompi aihe saa numeron ja sit jokainen tehtävä sarake pysäyttää merkillä #


# 1. Italics and Bold
 We'll start by learning two basic elements in text formatting: italics and bold. In these lessons, you'll notice some formatted red text; this text is actually written in Markdown! Regular Markdown doesn't look any different than regular text, but we're providing some highlighting to make it easier to see.

 To make a phrase italic in Markdown, you can surround words with an underscore (_ ). For example, _this_ word would become italic.

 For this next lesson, make the word "not" italic.
  Writing in Markdown is _not_ that hard!

 Awesome! Great job.

 Similarly, to make phrases bold in Markdown, you can surround words with two asterisks ( ** ). This will **really** get your point across.

 # In the box below, make the word "will" bold.
  I **will** complete these lessons!

 Good work!

 Of course, you can use _both italics and bold_ in the same line. You can also span them **across multiple words**.

 # In the box below, make the words "Of course" italic, and the words "a little moxie" bold.
  "_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"

 Fantastic!

 For the final exercise in this lesson, we're going to make some words bold and italic.

 In general, it doesn't matter which order you place the asterisks or underscores. 

 In the box below, make the words "This is unbelievable" both bold and italic. Place the asterisks **_on the outside_**, just to make it more legible.

 If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.

 Now you know how to make things bold and italic in Markdown!

# 2. Headers
 Let's take a look at another formatting convention: the header. Headers are frequently used on websites, magazine articles, and notices, to draw attention to a section. As their name implies, they act like titles or subtitles above sections.

 There are six types of headers, in decreasing sizes:

 #This is header one
 ##This is header two
 ###This is header three
 ####This is header four
 #####This is header five
 ######This is header six
 To make headers in Markdown, you preface the phrase with a hash mark (#). You place the same number of hash marks as the size of the header you want. For example, for a header one, you'd use one hash mark (# Header One), while for a header three, you'd use three (### Header Three).

 # For this next lesson, make each header the right size.
  #Header one
  ##Header two
  ###Header three
  ####Header four
  #####Header five
  ######Header six

 All right!

 It's up to you to decide when it's appropriate to use which header. In general, headers one and six should be used sparingly.

 You can also mix and match inline styles within headers, such as italicizing them. 
 
 # In the box below, make the first line a heading level four, and italicize the name of the book:
  #### Colombian Symbolism in _One Hundred Years of Solitude_
  Here's some words about the book _One Hundred Years..._.

 And that's all there is to making headers in Markdown.

# 3. Links
 We'll now learn how to make links to other web sites on the World Wide Web.

 There are two different link types in Markdown, but both of them render the exact same way. The first link style is called an inline link. To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parentheses ( ( ) ). For example, to create a hyperlink to www.github.com, with a link text that says, Visit GitHub!, you'd write this in Markdown: [Visit GitHub!](www.github.com).

 # In the box below, make a link to www.google.com, with link text that says "Search for it."
  [Search for it.](www.google.com)
 
 Nice work!

 You can add emphasis to link texts, if you like. 
 
 # In the box below, make the phrase "really, really" bold, and have the entire sentence link to www.dailykitten.com. You'll want to make sure that the bold phrasing occurs within the link text brackets.
  [You're **really, really** going to want to see this.](www.dailykitten.com)

 Fantastic!

 Although it might make for an awkward experience, you can make links within headings, too.

 # For this next tutorial, make the text a heading four, and turn the phrase "the BBC" into a link to www.bbc.com/news:
  #### The Latest News from [the BBC](www.bbc.com/news)

 That's all there is to writing inline links.

 The other link type is called a reference link. As the name implies, the link is actually a reference to another place in the document. Here's an example of what we mean:

     Here's [a link to something else][another place].
     Here's [yet another link][another-link].
     And now back to [the first link][another place].

     [another place]: www.github.com
     [another-link]: www.google.com
  
 The "references" above are the second set of brackets: [another place] and [another-link]. At the bottom of a Markdown document, these brackets are defined as proper links to outside websites. An advantage of the reference link style is that multiple links to the same place only need to be updated once. For example, if we decide to make all of the [another place] links go somewhere else, we only have to change the single reference link.

 Reference links don't appear in the rendered Markdown. You define them by providing the same tag name wrapped in brackets, followed by a colon, followed by the link.

 # In the box below, we've started writing out some reference links. You'll need to finish them up! Call the first reference tag "a fun place", and make it link to www.zombo.com; make the second link out to www.stumbleupon.com.
  
 Do you want to [see something fun][a fun place]: ?

 Well, do I have [the website for you][another fun place]: !

 [a fun place]: www.zombo.com
 [another fun place]: www.stumbleupon.com

 You now know how to make links in Markdown!

# 4. Images

 If you know how to create links in Markdown, you can create images, too. The syntax is nearly the same.

 Images also have two styles, just like links, and both of them render the exact same way. The difference between links and images is that images are prefaced with an exclamation point ( ! ).

 The first image style is called an inline image link. To create an inline image link, enter an exclamation point ( ! ), wrap the alt text in brackets ( [ ] ), and then wrap the link in parentheses ( ( ) ). (Alt text is a phrase or sentence that describes the image for the visually impaired.)

 For example, to create an inline image link to https://octodex.github.com/images/bannekat.png, with an alt text that says, Benjamin Bannekat, you'd write this in Markdown: ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png).

 # In the box below, turn the link to an image, and fill out the alt text brackets to say "A pretty tiger":
  ![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

 Wonderful!

 Although you don't need to add alt text, it will make your content accessible to your audience, including people who are visually impaired, use screen readers, or do not have high speed internet connections.

 For a reference image, you'll follow the same pattern as a reference link. You'll precede the Markdown with an exclamation point, then provide two brackets for the alt text, and then two more for the image tag, like this: ![The founding father][Father] At the bottom of your Markdown page, you'll define an image for the tag, like this: [Father]: http://octodex.github.com/images/founding-father.jpg.

 # In the box below, we've started placing some reference images; you'll need to complete them, just like the last lesson. Call the first reference tag "Black", and make it link to https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg; make the second image link out to http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png.

 [Black cat][Black]

 [Orange cat][Orange]

 [Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg

 [Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

 Ta da! You've learned all there is to adding images in Markdown!

# 5. Blockquotes
 If you need to call special attention to a quote from another source, or design a pull quote for a magazine article, then Markdown's blockquote syntax will be useful. A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader. For example:

 "The sin of doing nothing is the deadliest of all the seven sins. It has been said that for evil men to accomplish their purpose it is only necessary that good men should do nothing."

 To create a block quote, all you have to do is preface a line with the "greater than" caret (>). For example:

 > "In a few moments he was barefoot, his stockings folded in his pockets and his canvas shoes dangling by their knotted laces over his shoulders and, picking a pointed salt-eaten stick out of the jetsam among the rocks, he clambered down the slope of the breakwater."

 # In the box below, turn the book quotation into a blockquote:
 
  I read this interesting quote the other day:
 > "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

 Marvelous!

 You can also place a caret character on each line of the quote. This is particularly useful if your quote spans multiple paragraphs. For example:

 > His words seemed to have struck some deep chord in his own nature. Had he spoken of himself, of himself as he was or wished to be? Stephen watched his face for some moments in silence. A cold sadness was there. He had spoken of himself, of his own loneliness which he feared.
 >
 > —Of whom are you speaking? Stephen asked at length.
 >
 > Cranly did not answer.

 Notice that even blank lines must contain the caret character. This ensures that the entire blockquote is grouped together.

 # In the box below, Make the entire quotation a block quote by inserting a caret on each line.

  > Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...
  >
  > His father told him that story: his father looked at him through a glass: he had a hairy face.
  >
  > He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

 Tremendous!

 Block quotes can contain other Markdown elements, such as italics, images, or links.

 # In the box below, make the French text italic (not including the exclamation point). Also, turn the entire quote into a blockquote.
 > He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!

 Ta da! You've learned all there is to creating blockquotes in Markdown!

# 6. Lists
 This tutorial is all about creating lists in Markdown.

 There are two types of lists in the known universe: unordered and ordered. That's a fancy way of saying that there are lists with bullet points, and lists with numbers.

 To create an unordered list, you'll want to preface each item in the list with an asterisk ( * ). Each list item also gets its own line. For example, a grocery list in Markdown might look like this:

 * Milk
 * Eggs
 * Salmon
 * Butter
 This Markdown list would render into the following bullet points:

 Milk
 Eggs
 Salmon
 Butter
 In the box below, turn the words separated by a comma into a list.
  * Flour
  * Cheese
  * Tomatoes
 
 All right! That's how you write an unordered list. Now, let's talk about ordered ones.

 An ordered list is prefaced with numbers, instead of asterisks. Take a look at this recipe:

 Crack three eggs over a bowl
 Pour a gallon of milk into the bowl
 Rub the salmon vigorously with butter
 Drop the salmon into the egg-milk bowl
 To write that in Markdown, you'd do this:

 1. Crack three eggs over a bowl
 2. Pour a gallon of milk into the bowl
 3. Rub the salmon vigorously with butter
 4. Drop the salmon into the egg-milk bowl
 Easy, right? It's just like you'd expect a list to look.

 # In the box below, turn the rest of the recipe into an ordered list.
  1. Cut the cheese
  2. Slice the tomatoes
  3. Rub the tomatoes in flour

 Fantastic work!

 You can choose to add italics, bold, or links within lists, as you might expect. 
 
 # In the box below, turn the Latin names for the plants into italics.
  * Azalea (_Ericaceae Rhododendron_)
  * Chrysanthemum (_Anthemideae Chrysanthemum_)
  * Dahlia (_Coreopsideae Dahlia_)

 Magnificent!

 Occasionally, you might find the need to make a list with more depth, or, to nest one list within another. Have no fear, because the Markdown syntax is exactly the same. All you have to do is to remember to indent each asterisk one space more than the preceding item.

 For example, in the following list, we're going to add some sub-lists to each "main" list item, describing the people in detail:

 * Tintin
  * A reporter
  * Has poofy orange hair
  * Friends with the world's most awesome dog
 * Haddock
  * A sea captain
  * Has a fantastic beard
  * Loves whiskey
    * Possibly also scotch?
 When rendered, this list turns into the following grouping:

 Tintin
  A reporter
  Has poofy orange hair
  Friends with the world's most awesome dog
 Haddock
  A sea captain
  Has a fantastic beard
  Loves whiskey
   Possibly also scotch?
 # In the box below, turn the character's characteristics into sub-bullets. 
  * Calculus
    * A professor
    * Has no hair
    * Often wears green
  * Castafiore
    * An opera singer
    * Has white hair
    * Is possibly mentally unwell
 
 Stupendous! While you could continue to indent and add sub-lists indefinitely, it's usually a good idea to stop after three levels; otherwise, your text becomes a mess.

 There's one more trick to lists and indentation that we'll explore, and that deals with the case of paragraphs. Suppose you want to create a bullet list that requires some additional context (but not another list). For example, it might look like this:

 1. Crack three eggs over a bowl.

  Now, you're going to want to crack the eggs in such a way that you don't make a mess.

  If you do make a mess, use a towel to clean it up!

 2. Pour a gallon of milk into the bowl.

  Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

 3. Rub the salmon vigorously with butter.

  By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:

 > Up and down and all around, that's how butter on salmon goes.

 4. Drop the salmon into the egg-milk bowl.

 Here are some techniques on salmon-dropping:
  * Make sure no trout or children are present
  * Use both hands
  * Always have a towel nearby in case of messes

 To create this sort of text, your paragraph must start on a line all by itself underneath the bullet point, and it must be indented by at least one space. For example, the list above looks like this in Markdown:

 1. Crack three eggs over a bowl.

  Now, you're going to want to crack the eggs in such a way that you don't make a mess.

  If you _do_ make a mess, use a towel to clean it up!

 2. Pour a gallon of milk into the bowl.

  Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

 3. Rub the salmon vigorously with butter.

    By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:
    > Up and down and all around, that's how butter on salmon goes.
 4. Drop the salmon into the egg-milk bowl.

    Here are some techniques on salmon-dropping:

    * Make sure no trout or children are present
    * Use both hands
    * Always have a towel nearby in case of messes
   
 Notice that the first two items have a single space. This looks a bit odd, so you might want to indent properly to match the characters up (like items three and four). In these paragraphs, you can include all sorts of other Markdown elements, like blockquotes, or even other lists!

 # In the box below, convert the bullet points into their own paragraphs.
  1. Cut the cheese

    Make sure that the cheese is cut into little triangles.

  2. Slice the tomatoes

    Be careful when holding the knife.

    For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.

 You now know how to make lists in Markdown!

# 7. Paragraphs

 Markdown has several ways of formatting paragraphs.

 Let's take a few lines of poetry as an example. Suppose you want to write text that looks like this:

 Do I contradict myself?
 Very well then I contradict myself,
 (I am large, I contain multitudes.)

 Now, you might think that simply typing each verse onto its own line would be enough to solve the problem:

 Do I contradict myself?
 Very well then I contradict myself,
 (I am large, I contain multitudes.)
 Unfortunately, you'd be wrong! This Markdown would render simply as a single straight line: Do I contradict myself? Very well then I contradict myself, (I am large, I contain multitudes.).

 If you forcefully insert a new line, you end up breaking the togetherness:

 Do I contradict myself?

 Very well then I contradict myself,

 (I am large, I contain multitudes.)
 This is what's known as a hard break; what our poetry asks for is a soft break. You can accomplish this by inserting two spaces after each new line. This is not possible to see, since spaces are invisible, but it'd look something like this:

 Do I contradict myself?··
 Very well then I contradict myself,··
 (I am large, I contain multitudes.)
 Each dot ( · ) represents a space on the keyboard.

 Let's try this technique out. 
 
 # In the box below, insert the necessary number of spaces to make the poem render correctly:

  We pictured the meek mild creatures where  
  They dwelt in their strawy pen,  
  Nor did it occur to one of us there  
  To doubt they were kneeling then.

  Fantastic work!

 Aside from formatting poetry, one of the common uses for these soft breaks is in formatting paragraphs in lists. Recall in the previous lesson that we inserted a new line for multiple paragraphs within a list.

 # In the box below, instead of using hard breaks, tighten the sub-paragraphs with soft breaks:

  1. Crack three eggs over a bowl.  
   Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
   If you _do_ make a mess, use a towel to clean it up!

  2. Pour a gallon of milk into the bowl.  
   Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

 Et voila! You now know how to make soft breaks in Markdown!

 # Congratulations!
You’ve completed all the lessons!

