# Frontend Masters Course - Web Accessibility
## Web Accessibility by Jon Kuperman

You can find this course here at www.frontendmasters.com/courses/web-accessibility

- Course Notes

* Web Accessibility

### The Web is for Everyone
 - An  introduction  to  Accessibility

 Who should know about web accessibility?
 * Developers, Designers, Product Managers

 Moving target we want to identify and simplify the definition and technical target of it.

 Education on what is **Web Accessibility**??

 * Making your websites and applications able to be used by people with disabilities.

###  Agenda

* Types  of disabilities
* Assistive Technologies
* Keyboard Navigation
* Focus Control
* Working with Screen Readers
* Semantic HTML
* WAI-ARIA spec
* Accessibility in color and design

#### Types of Disabilities

  One problem is that accessibility terms themselves lend double meanings into a multitude of sub-fields in tech.

  * **Web performance** is a similar field when you are talking about potential users, making your web site accessable, taking into account of people in developing nations that are using slow connections or old devices.

  * **Internationaliztion** making your website useable for everyone, making sure that your strings are translated and can be read by people speaking a variety of languages.

  * **Design** Web Design, UI Design, Responsive Design, content hierarchy, Workflow. Closely related, coming from a place of empathy and  understanding our users and their needs.

Depending on who you ask, you may get slightly different definitions, which creates doubt of if Web Accesesibility encompass these specific domains.

* For this lesson we will focus in on people with disabilities and how to help them use the Web.


> More specifically, Web accessibilitiy means that people with disabilities can **perceive, understand, navigate, and interact** with the web and that they can **contribute to the Web**.

- *WAI-ARIA spec*

#### Let's talk numbers...

Doing your taxes: you know what you have to do, but instead of just being able to hit yes on a website you are given all of these forms to fill out a tax formand you're not sure on a certain step and you're lost. That negative frustration is the experience that is happening to your users who may have a disaibity and are useing your website.

Don't cause this frustration to your users!

#### Statistics

> One in six Americans (17%), 45 years of age or older, representing **16.5 million** middle-age and older adults, report *some form of visual imparment* even when wearing glasses or contact lenses.

So, as we're thinking about making designs and making websites for users with visual impairments.

> An estimateed 7.9 million  persons (age 6 and older) have difficulty  seeing words and letters in ordinary newspaper print

We have to make sure that our content is legdable.

> 1 in 5 people have a disability

These are potential users that want to give you their money!!

The Web, by it's very nature, is already accessible. You need to put in the work to make it accessable.

The first webpage was built in 1991 and it is fully accessible! You can get all the information if you put on a screen reader. It's fully responsive, and can be used on any  device.

**Why should we care about accessiblity?**
* We're making it inaccesible
* Human Rights - let's let everyone use our cool stuff!
* Legal Issue
* Reach a larger audience

#### WC3 Specifications

##### WebAIM Checklist


| Success Criteria| WebAIM's Recommendations                                                                                                                                                                                                        |
| ----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.1.1 Non-text  | * All images, form image buttons, and image map hot spots have appropriate, equivalent alt text.                                                                                                                                |
| content         | * Images that do  not convey content, are decorative, or contain content that is already conveyed in text are given null alt text (alt="") or implemented as CSS backgrounds. All linked images have descriptive alternate text.|
|(Level A)        | * Equivalent alternatives to complex images are provided in context or on a separate (linked and/or referenced via longdesc) page.                                                                                              |
|                 | * Form buttons have a descripted value.                                                                                                                                                                                         |
|                 | * Form inputs have associated text labels.                                                                                                                                                                                      |
|                 | * Embedded multimedia is identified via  accessible text.                                                                                                                                                                       |
|                 | * Frames are appropriately titled are appropriately titled.                                                                                                                                                                      |

[WebAIM.org](https://webaim.org/)

* Provides a lot of great resources on Web Accessability.
* Gone through the entire WC3 Spec and pulled out the important points for us as developers to follow.

### All Websites Should Be
* Perceivable
* Operable
* Understandable
* Robust - leans to contribution angle, don't want incredible experience for non-disability and then simple for disability. We want a comparable experience for both.

Today Developers use Div tags instead of semantic HTML and this takes away from the ability for screen readers to gain information from these components


## Types of Disability

Learning about the different types of disabilies will help a developer understand the needs of the users that will come to your website.

* Attention-Deficit/Hyperactivity Disorders

 :yellow_heart: Keeping your font size big

 :yellow_heart: Good spacing between topics

 :yellow_heart: Line length

* Blindness or Low Vision

 :blue_heart: Screen Readers

 :blue_heart: Color Contrast

* Brain Injuries

* Deaf / Hard-of-Hearing

 :orange_heart: closed captioning media

* Learning Disabilities

 :green_heart: Keyboard only

 :green_heart: Single switch

 :green_heart: Space between click targets

* Speech and Language Disabilities

* Modifications that are helpful for users with disabilities are **helpful to all users**. These modifications will bring positive feedback from all users. It's easy to understand, navigate, use the keyboard, etc. Black/White is not helpful.

## How to Browse the Web
* Screen Readers
* Head Wand / Mouth Sticks
* Keyboard Shortcuts
* Keyboard Only
* Single Switch
* Magnification

There are many diverse ways to use the web. We see many times that people with any motor disability that prefer to use the keyboard. This means that your website should be accessible **by keyboard only** (signing up, logging in, checkout out shopping cart, etc).
Bigger click targets and spacing around those targets help people who use headwands and mouth sticks.



