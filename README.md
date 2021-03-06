All of us know the recent condition related to the COVID-19 outbreak. All our social platforms are flooded with various messages related to it. Some are good, some are fake, and some are pretty confusing and difficult to verify. In the midst of this information  spread, I receive a post from my collaborator Sayantari which was fascinating. We were particularly excited as we have a common interest in the study of epidemiological dynamics. We performed couple of oversimplified experiments to evaluate the present situation, and the effectiveness of the precautions that we are taking.
Consider there are initially two types of people present in any situation- sick person and healthy person. If a healthy person comes in contact with a sick person then with some finite probability, both of them turn into sick person. In case of highly infectios disease this probability is close to one. However, a sick person will recover eventually. Once recovered, that person may or may not get the infection again. In a framework where a recovered person may have infection again is more alarming, and recent studies are showing that COVID-19 might attack same person twice. So, we have different frameworks, like, susceptible-infected (SI) epidemic framework where infected person never recovers, susceptible-infected-recovered (SIR) epidemic framework  where infected person recovers, and never gets infected, or susceptible-infected-recovered-susceptible (SIRS) epidemic framework  where infected person recovers and then again may have the infection.

![](SI_SIR.gif)

Let us define our people! The blue ones and the red ones are the people who are healthy and sick respectively. After some time, we have some pink circles appearing in the left video indicating recovered people (The embedded media is a GIF file, so it runs in a loop). The people in our toy example are moving randomly, and when an infected person meets a healthy person he becomes sick. This models are widely used in epidemiology, and they correctly depict many disease spread like HIV. Here one must have a 'direct' contact with the infected person to acquire the infection. 
The life span of COVID-19 outside human body is yet debatable, but some studies show that it can be active quite long on different surfaces, and one does not require direct contact to be infected. This no longer allow us to use direct contamination models. We move to a model where a healthy person may become sick if he touches a surface which is infected by some sick person within a time span. We call this 'persistent contamination'as the virus remains active for longer period. 

![](small_particle_only.gif)

## Disclaimar
This post is to visualize the dynamics of epidemic spreads in a simple way. The real situation is much complex, and nowhere near to these simulations. So, you must constantly follow the government instructions and precaustions suggested by WHO. 

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/SaumikB/epidemiology_101/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SaumikB/epidemiology_101/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
