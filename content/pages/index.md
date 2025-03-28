---
type: PageLayout
title: Home
colors: colors-e
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: damianruel's page
    subtitle: >-
      a musician, writer, artist and a bunch of other creative titles and buzz
      words.
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
          - pt-16
          - pb-4
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
    text: ''
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: ''
    text: >
      my goal is to share my thoughts and art and voice with the world. tysmsm
      for reading even this much into it, you can continue to scroll down to see
      more details and credentials about my creations !!!!!!!!
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-12
          - pb-6
        justifyContent: center
        borderWidth: 1
  - type: CtaSection
    title: Listen to my music!
    text: >
      hyperlink to Spotify, but you can find my music under "damianruel" on any
      music service u can imagine
    actions:
      - type: Button
        label: Spotify
        altText: pls
        url: >-
          https://open.spotify.com/track/0Lt7n7FZxKOgweu916V8gF?si=dbf3d58889e54f11
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Button
        label: Apple Music
        altText: ''
        url: 'https://music.apple.com/us/album/revision-iv/1757031953?i=1757031954'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: TestimonialsSection
    testimonials:
      - type: Testimonial
        quote: >
          Damian, known artistically as damianruel, is a Chicago-based
          multi-instrumentalist, composer, and otherwise artist whose work
          reflects partly his self-taught findings from exploring how notes work
          with his many curious ideas. He is his own producer and he plays the
          instruments in his song to ensure it ends up how he envisioned it.


          He keeps a genre-fluid approach to his projects, and likes to think he
          is unrestricted in musical expression. While his projects don't stick
          to one or three genres, he has a very similar vibe in the art he
          creates. He is very intentional with what he puts out, sometimes
          because he thinks it's funny to have an intro that's unrelated to the
          song, or if he thinks a note should be a quarter-tone sharp to bring
          out a certain feeling in the phrase.
        name: John Doe
        title: CEO at Parks
        image:
          type: ImageBlock
          url: /images/IMG_6333.jpg
          altText: John Doe
          caption: Caption of the image
          elementId: ''
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
    colors: colors-f
    variant: variant-c
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-0
          - pb-5
          - pl-6
          - pr-6
        justifyContent: center
        borderWidth: 1
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: ''
    text: >
      tbh i just wanted to see if i could do it. plus its a good hub to find all
      my projects
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-4
          - pb-1
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
    subtitle: why a website?
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-5
          - pb-0
          - pr-6
          - pl-6
        justifyContent: center
        borderWidth: 1
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
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
    subtitle: i have lots of thoughts i'd like to share
    title: My mind
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: got an idea to share? tell me more!!
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: hi
          label: fav greeting?
          hideLabel: true
          placeholder: fav greeting?
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
  - type: HeroSection
    title: >-
      I'm a developer, digital artist, consultant and a bunch of other
      impressive titles and buzz words.
    subtitle: >-
      This is my info—I'm sharing it all this with ya'll to impress you with all
      the hard work I've done in the past few years. Once you're impressed, you
      can continue to scroll down to see more details and credentials about me.
    actions:
      - type: Button
        label: Hire me
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-d
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
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
socialImage: /images/IMG_0074 - Copy.jpeg
metaTitle: home page ;p
metaDescription: read more about damianruel !!
---
