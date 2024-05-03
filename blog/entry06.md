# Entry 6
##### 5/6/24

## Context
In this section of my freedom project, I created the MVP for my website.  The MVP was a struggle but also felt very rewarding in the end.  I had implemented my skills of html, css, advanced css, bootstrap, and also the tool that i had learned which was A-Frame.  Over the course of this freedom project i learned a lot about not only how to make a website, but the creative possibilites that come with it.  While making my MVP, it opened my eyes to how some things can look on a webpage and inspired me to do some of those myself, so I did.  There was many challenges i had come across while creating it, but in the end i overcame them and found ways to pass them.

### Challenges
Some challenges that i had faced while designing my MVP was especially within CSS and positioning.  It took me forever to try and get my images in the right spot and get them aligned to where i want to be. 

![Screenshot 2024-05-02 210030](https://github.com/andrep8376/sep10-freedom-project/assets/146866615/f82833e8-77e4-4f3d-9bd0-538d603dd71e)

For example while making my timeline section of it, it was extremely hard to fit the images in the circle that was made up as a reference. (It wasn't that hard once i figured it out in the end).  I had searched through a ton of websites trying to find ways to resize these images in the right way, because some would fit and some wouldn't.  I then used my inspect tool and realized that all of the images on the website were under the same class.  I renamed the class of the timeline section, and went into the css and adjust the image size to be the exact size for each of them no matter what the image was to fit inside of the circle.

``` css
.img-fluid {
  max-width: 156px;
  height: 156px;
}
```

Another challenge that I had faced was as i was making my cards.  I had a hard time getting them in the right spot that i wanted and spent a lot of time trying to work on that.  Just like previously i was trying to browse examples of the same problem as me but none of them would help me.  Then as i was scrolling i remembered the previous lessons and also how the coding for cards have their width on them.  I used what i was previously taught and applied it to the code and it aligned them how i wanted them too and they looked the way that i wanted them to.  I also used the previous lessons to adjust the images of the cards to the desirable height and width so that they would fit in the row and look proper.

``` css
.card-img-top {
  width: 100%;
  height: 25vw;
  object-fit: cover;
  }
```








[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
