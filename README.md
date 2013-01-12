# Marked Themes

## about

Some CSS for the [Marked][] markdown processor.

[Marked]: http://markedapp.com

Includes the [scss][] I wrote as well as the css it compiles into, which marked uses.

[scss]: http://sass-lang.com

With the `config.rb` file and the way the folders are organized, you can just run `compass watch` and modify the scss files and the css files will be automatically updated.

## themes

### prose (aka the only one)

It's nice for writing fiction.

* paragraphs are indented like in books, where the first paragraph of a section is not indented. I wrote about why I like this [here](http://www.maxjacobson.net/2012-03-21-indenting-paragraphs-online).
* includes some google web fonts
* responsive
* cool horizontal rule w/ unicode symbols (v literary looking) which I wrote about [here](http://www.maxjacobson.net/2012-12-31-the-horizontal-rule)

[![Prose screenshot](http://d.pr/i/Iawe+ "Prose screenshot")](http://d.pr/i/Iawe)

Printing, or printing to PDF works nicely. I like these settings:

[![Print settings screenshot](http://d.pr/i/Kbox+ "Print settings screenshot")](http://d.pr/i/Kbox)

And I structure my documents like this:

    # Title

    By my name
    
    ## Chapter one

    The text of chapter one. Intra-chapter sections can be nicely demarcated with one of these:
    
    * * *
    
    Some more of chapter one.
    
    ## Chapter two

    I suppose you could use further sub headings like so
    
    ### morning

    As Gregor Samsa awoke one morning from uneasy dreams he found himself transformed in his bed into a gigantic insect. He was lying on his hard, as it were armor-plated, back and when he lifted his head a little he could see his dome-like brown belly divided into stiff arched segments on top of which the bed quilt could hardly keep in position and was about to slide off completely. His numerous legs, which were pitifully thin compared to the rest of his bulk, waved helplessly before his eyes.
    
    ### night

    I don't know I haven't read it, maybe he hits a club.

Ok I'm sleepy.
