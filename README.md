# MEDIFUL

MEDIFUL is a site with the intention to introduce people to mindfulness meditation. It is supposed to give people who have not yet tried meditating an overlook of what it is 
and a guide to their first session. It guides you either via a step by step guide or a video with the same intention. The site explains the benefits of meditation and why 
everyone should try it.

![Responsive Mockup](docs/site-showcase.jpg)

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](docs/navigation-bar.jpg)

- __First banner__

  - The first banner is simply there for visual stimulation and to grab the users attention.

![Home Banner](docs/first-banner.jpg)

- __Mindfulness section__

  -  This section explains what mindfulness is and briefly explains why it is useful.  It gives the user an overwiev of the rest of the sites content
   

![Mindfulness](docs/What-is-mindfulness.jpg)

- __Benefits__

  - The benefin section gives the user a list of benefits to be gained from meditation and has a paragraph talking about the benefits.
  - This section is meant to further incourage the user to practice meditation.

![Benefits](docs/benefits.jpg)

- __Practice banner__ 

  - This banner has the same purpuse as the banner on the home page. 
  - The banner is meant to capture the attention of the user and the colors on the image are meant to be calming.

![Practice banner](docs/practice-banner.jpg)

- __Guided meditation__

  - This section gives the user a step by step meditation guide to follow. 
  - It's a short and simple meditation session perfect for a beginner.

![Guided meditation](docs/guided-meditation.jpg)

- __Meditation video__

  - This section gives the user the oppertunity to watch a video guiding the user through their first session.
  - Giving the user this option is great if the user rather follows a audio-visual instruction. 

![Meditation video](docs/practice-video.jpg)

For some/all of your features, you may choose to reference the specific project files that implement them.

-__Contact page__

-This page gives the user the option to send me a question. After sending the question the user will be redirected to a new page thanking them for submitting it.

![Contact page](docs/contact-form.jpg)
![Thank you page](docs/thank-you-page.jpg)

### Features Left to Implement

- I want to make one last page, telling the user about an app called "Waking Up". This is a mindfulness app I really enjoy myself and i think its a great way for new mindfulness practitioners to progress in their mindfulness journey.
- I had to prioretize finishing the rest of my site before this and was left with no time to create this page.

## Testing 

I tested the navigation bar by clicking the different navigation opptions on every page to see if they directed me the right way. While doing this i also checked if my
"class="active"" which underlined the page I was currently viewing in the navigation section worked. This was also tested on my phone.

I tried viewing my site on different screen sizes, first by using the google chrome "inspect" tool. This was crucial to see how responsive my site was. 
When an element didnt behave as I wanted it to I played around with the code in the "inspect" tool until it worked as I wanted it to. This was a process i had to repeat many
times and on every page. When I felt happy with the site I tried visiting it on my phone to make sure there were no bugs. This also ensured that my "@media screen" property
worked.

I watched the video on my computer and on my phone and made sure all the controlls (such as the play- and fullscreen button) worked.

I tried filling out the form and submitting it. This tested if the user is able to input text in the different input element. It also tested if the submit button redirected me
to my submit.html page. This was problematic at first as the submit button either sent me to an error message page, or it cleard the form. By putting the submit button
outside of the form elemnt and wrapping it in an <a> element I got it to work.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleomatus.github.io%2Fmediful%2F)
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleomatus.github.io%2Fmediful%2Fcontact)
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleomatus.github.io%2Fmediful%2Fpractice)
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleomatus.github.io%2Fmediful%2Fsubmit)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fleomatus.github.io%2Fmediful%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

I have not found any unfixed bugs.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - Inide the Settings menu, scroll down to the Github pages header, click the link
  - Find the source header and click the branch button, select the main branch and press save. The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment and the link to your site will appear. 

  The live link can be found here -https://leomatus.github.io/mediful/

## Credits

### Content

    Content for the what is mindfulness and why is it usefull section was inspired by [Greatergood](https://greatergood.berkeley.edu/topic/mindfulness/definition) and [Mindful](https://www.mindful.org/what-is-mindfulness/)

    Insperation for the guided meditation text guide was taken from [Mindful](https://www.mindful.org/five-steps-to-mindfulness/)

    I had some problems displaying my content the way i wanted it to, I used to many floats which led to elemts ending up on top of each other. After a while it became too much to handle and I needed another way to display my content. After searching the web I found out about 
    "display: flex;" and "justify-content: ___;". I learned "display: flex;" from [css-tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) and "justify-content: ___; from [developer-mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)


###Media

    The image used as the home page banner was taken from [Actualized](https://www.actualized.org/forum/topic/7396-nutshell-in-depth-teachings-of-enlightenment/) 

    The image used for the practice page banner was taken from [HD Wallpapers](https://www.hdwallpapers.in/man_loneliness_alone_sadness_4k_hd_sad-wallpapers.html)

    The image used for the contact page was taken from [Calm Blog](https://blog.calm.com/blog/5-ways-to-improve-your-focus-and-productivity)

    The video used for the guided meditation was taken from [Youtube/Goodful](https://www.youtube.com/watch?v=U9YKY7fdwyg&t=1s)
