![Logo](/assets/lhl-logo.png)

# Introduction

Hello and thank you for joining us for the Build Your First Website workshop.

My name is [Izzy Piyale-Sheard](http://twitter.com/izzydoesizzy), the Community Manager at Lighthouse Labs and workshop leader today.

Over the last few years, I've led a group of 30-40 software developers around the world for a year, organized meetups with different startups in countries all over the world, and started working as the Community Manager at Lighthouse Labs.


## The goal

You may have previously attempted to teach yourself how to code, or how to build website in different ways. The goal of today isn't to teach oyu everything from scratch, but rather to give you a few tools to be able to quickly and easily hack together a website as quickly as possible.

We'll be working with an HTML template, then learning how to modify it and adapt it to our liking by using Chrome Devtools, then throwing it up live so others can see it.

## Pair programming

You're encouraged to buddy up with one other person. That said, both of you should ideally do the setup work individually on your own laptops.

## The product

The finished page that we'll be building in just a few hours today will look and feel much like this.

![Edit](/assets/image1.png)
![Edit](/assets/image2.png)
![Edit](/assets/image3.png) 
![Edit](/assets/image4.png)

Let's get started with some [Setup](content/setup/README.md) or if you feel you can go faster here is a [Summary](SUMMARY.md) of all we'll cover.

# Setup

Since we only have a few hours to get you up to speed on being a Javascript Developer, you would benefit from completing these steps before you arrive to the Workshop.

Don't worry if you run into any issues.  Our mentors will be ready to help you get set up upon your arrival.

* You'll need [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html)
* If you don't have a text editor where you can code I recommend [Sublime Text](http://sublimetext.com)
* We'll share some code during the Workshop. Having an account on [GitHub](http://github.com) will speed things up.

# Step 1: Download the Template

First of all, please [download the resume template here](https://github.com/izzydoesizzy/resumetemplate).

![Edit](/assets/download.png)

# Step 2: Set up your workspace

### Step 2a: Open Sublime Text
### Step 2b: Click on File/Open then open the entire folder "resumetemplate-gh-pages"

![Edit](/assets/openfolder.png)

### Step 2c: Your Sublime Text should show the whole folder structure like this. 

![Edit](/assets/folderstructure.png)

### Step 2d: Open your website locally

Find your the website directory (folder) on your desktop again, right click on "index.html" and open with Chrome

![Edit](/assets/indexhtml.png)


## Congratulations! What you're seeing now in your browser is a local version of your website accessible on your computer!
![Edit](/assets/indexhtml.png)

![Edit](/assets/local.png)

# Step 3: Learning how to use Chrome Dev Tools

### Things To Try
* Right click on any part of the page and click inspect element
* Edit the contents of a website (any website) locally and play pranks on your friends

### Elements
These are HTML structural elements. What actually make up the architecture of your site. The text, the blocks the content, the photos.

### Styles
These are the parts of your website that are pretty. Colours, fonts, borders etc

# Step 4: Find, edit, then save in Sublime Text
After you've played around and figured out what you want to change, find those elements in the index.html file in Sublime Text, edit it, then save it for those changes to be permanent.


# Step 5: Font Awesome 
You might have been asking where these cool fonts come from? [Font Awesome](http://fontawesome.io/icons/). Whenever you see an icon, there's a good chance it's using FontAwesome or another icon font. In thise case I'll teach you how to use FontAwesome.

1. Right click and inspect one of the social media icons
2. You will see ```<i class="fa fa-twitter fa-3x"></i>```
3. On the [Font Awesome Icons Page](http://fontawesome.io/icons/), you'll see lots of other icon names. 
4. Try this change ```fa-twitter``` to ```fa-bitcoin```   
   
> So...  
> ```<i class="fa fa-twitter fa-3x"></i>```   
> should become   
>   ```<i class="fa fa-bitcoin fa-3x"></i>```

# Step 6: Links & Images

These should be pretty straightforward at this point. Right click, inspect element, find what you're looking for, change the link. Then go and change it in Sublime Text.

**Links**
> So if you want to change the link from my Twitter, to Google...  
> ```<a href="http://www.twitter.com/izzydoesizzy" target="_blank"><i class="fa fa-twitter fa-3x"></i></a>```   
> should become   
>   ```<a href=http://www.google.ca" target="_blank"><i class="fa fa-twitter fa-3x"></i></a>```

**Images**
> So if you want to change the circle image from my profile pic, to yours...  
> ```<img class="profilepic" src="https://pbs.twimg.com/profile_images/641063961144750081/IqosL0KD.jpg">```   
> should become   
>   ```<img class="profilepic" src="http://yournewurl.com/yournewphoto.png">```  
> OR drop a square image from into the /images directory.  
>   ```<img class="profilepic" src="images/yournewphoto.png">```  

![Edit](/assets/yournewphoto.png)


# Step 7: 

# Where can you find free templates?

* [HTML5UP](http://html5up.com)
* [TrendyTheme](https://trendytheme.net/items/category/html/)
* [StyleShout](https://www.styleshout.com/free-templates/)
* [TooPlate](http://www.tooplate.com/)
* [Templated](https://templated.co/)

These ones are fancy but cost money:
* [Themeforest](https://themeforest.net/category/site-templates/personal?sort=trending/?ref=ipiyale)
* [WrapBootstrap](https://wrapbootstrap.com/themes/landing-pages)


