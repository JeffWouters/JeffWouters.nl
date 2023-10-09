---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: JeffWouters
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Owner / CTO / Lead Consultant
          company: Methos
          company_url: 'https://www.methos.nl'
          company_logo: Methos
          location: The Netherlands
          date_start: '2015-11-01'
          date_end: ''
          description: |2-
            As the founder and technical lead of the company, in the end, I am responsible for everything, but I focus on the culture and technical direction.
            Regarding my preferred managemend style, there are a few phrases that guide me:

            1) Sometimes it's the little things that matter. Someone's father was rushed to the hospital, their car broke down, the came back from vacation or even when they just bought a house or it's their birthday.
            Send a cake/pie when someone has a birthday, send a post card when someone has a birthday or bought a house, or call them when they had unplanned work in the weekend and thank them for their work and ask them how they're doing. People tend to appreciate this, and it takes little effort to do it.

            2) Learn when to listen and when to respond. Sometimes people come to me with their problems or challenges. But not always they want me to provide a solution. Sometimes they just want to 
            Every now and then I catch myself listening to someone and before they finish what they're saying, I already have my answer ready and I'm impatiently waiting to give it to them. Sometimes that means that I didn't listen to the last bit of what they were saying.
            These days most people listen to what others tell them with the intention to reply. Lots of times this takes away from the actual listening to what they are saying.

            3) Learn to delegate. There are only so much hours in a day, and days in a week, etc. So in order to do more than you can accomplish just on your own, you'll need to delegate. Next to this, your employees/colleagues will probably value your trust and answer with their respect, or even loyalty.

            When it comes to fostering the culture of the company, here are the phrases that I try to always abide by:

            0) Anything can be discussed, even passionately, but always respectfully. Try to respect the opinions, views and points of others, or at least understand them. You don't have to agree with them, naturally. But a bit of understanding goes a long way.

            0) Know your limits, and learn those of others. When you know your limits, you know where to invest for growth but also when and what what to delegate.
            
            0) Think before you act. Don't make hasty decisions, and especially not led by emotions. Take your time, and don't ever let external factors make you decide when you're not ready to make a decision. If there's ever a customer or colleague that tries to force you to make a hasty decision, chances are you'll end up drawing the short straw.

        - title: Various employers
          company: Various companies
          company_url: ''
          location: California
          date_start: '2007-01-17'
          date_end: '2015-10-30'
          description: |2-
            Starting as a local support engineer, over a period of 8 years I grew into the role of Infrastructure Consultant. During that journey I had the pleasure of working with wonderful people and customers, where I would like to pick out three.
        - title: Servicedesk-/Local Support Engineer
          company: Icare Healthcare
          company_url: 'http://www.icare.nl'
          company_logo: Icare
          location: Meppel
          date_start: '2007-01-17'
          date_end: '2015-10-30'
          description: |2-
            In the project I had before, I was always cursing on the servicedesk for them not properly logging tickets. I only wanted to know 5 things: the 5 W's from Wouters: Who, what, where, when, why? I didn't understood why this was so difficult. Thanks to my time at this servicedesk, I learned just how difficult it can be... and I am very thankful for that.

        - title: Support Engineer
          company: RES Software Support
          company_url: 'http://www.res.nl'
          company_logo: RESSoftware
          location: California
          date_start: '2009-07-01'
          date_end: '2010-06-01'
          description: |2-
            This is where I learned two very valuable things, where the first was troubleshooting. Because RES' products were so intertwined in the Windows desktop and user experience, proper troubleshooting was a must.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Sep 2023
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 'https://learn.microsoft.com/en-us/users/jeffwouters/credentials/certification-o-/nouid.1541'
#          date_end: '2024-01-01'
          date_start: '2013-01-01'
          description: 'Microsoft Certified Trainer'
          organization: Microsoft MCT
          organization_url: https://www.microsoft.com
          title: MCT
          url: 'https://aka.ms/mctlounge'
        - certificate_url:
          date_end: '2023-03-01'
          date_start: '2013-06-01'
          description: 'Windows PowerShell / Cloud & Datacenter Management'
          organization: Microsoft MVP
          organization_url: https://www.microsoft.com
          title: Microsoft MVP
          url: 'https://mvp.microsoft.com/'
    design:
      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
      # Choose how many pages you would like to display (0 = all pages)
#      count: 3
      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
      # Choose how many pages you would like to offset by
#      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: asc
#    design:
      # Choose a layout view
#      view: compact
#      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: PowerShell
          tag: PowerShell
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: "Some pictures of me 'in action' ;-)"
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    id: talks
    content:
      title: Past & Future Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: It can be about something practical, fun, crazy, business or even all of the above ;-)
      text: |-
        Want to contact me? There are several ways, please choose the one(s) appropriate for you.
      # Contact (add or remove contact options as necessary)
      email: jeff@methos.nl
      phone: +31 6 81 24 48 11
      appointment_url: 'https://outlook.office365.com/owa/calendar/MethosBV@methos.nl/bookings/'
      address:
        city: Nieuwegein
        postcode: 3437 HG
        country: The Netherlands
        country_code: NL
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://x.com/jeffwouters'
        - icon: linkedin
          icon_pack: fab
          name: Connect with me
          link: 'https://zoom.com'
        - icon: message
          icon_pack: fas
          name: Teams me
          link: 'https://teams.microsoft.com/l/chat/0/0?users=jeff@methos.nl'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
