---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      I’m a developer, digital artist, consultant and a bunch of other
      impressive titles and buzz words.
    subtitle: >-
      This is my info—I’m sharing it all this with ya’ll to impress you with all
      the hard work I’ve done in the past few years. Once you’re impressed, you
      can continue to scroll down to see more details and credentials about me.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: Learn more
        altText: ''
        url: >-
          /<html dir="ltr" lang="en">  <head>    <meta charset="utf-8">   
          <title>New Tab</title>    <style>      body {        background:
          #FFFFFF;        margin: 0;      }      #backgroundImage {       
          border: none;        height: 100%;        pointer-events: none;       
          position: fixed;        top: 0;        visibility: hidden;       
          width: 100%;      }      [show-background-image] #backgroundImage
          {        visibility: visible;      }    </style>  </head>  <body>   
          <iframe id="backgroundImage" src=""></iframe>   
          <ntp-app></ntp-app>    <script type="module"
          src="new_tab_page.js"></script>    <link rel="stylesheet"
          href="chrome://resources/css/text_defaults_md.css">    <link
          rel="stylesheet" href="chrome://theme/colors.css?sets=ui,chrome">   
          <link rel="stylesheet" href="shared_vars.css">  </body></html>
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: RecentPostsSection
    subtitle: Posts
    actions:
      - type: Link
        label: See all posts
        altText: See all posts
        url: /blog
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    colors: colors-f
    variant: variant-d
    elementId: ''
    recentCount: 3
    showDate: true
    showAuthor: false
    showExcerpt: true
    showFeaturedImage: false
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: Your email
          width: 1/2
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
addTitleSuffix: true
socialImage: /images/contact.jpg
---
