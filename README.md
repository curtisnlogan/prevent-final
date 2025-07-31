# prevent-website

A responsive educational website that helps users identify signs of radicalization and provides resources to report concerns about violent extremism.

## Purpose

This website was created to raise awareness about the UK's Prevent strategy and educate the public on recognizing early warning signs of radicalization. The goal is to help vulnerable individuals avoid being lured into violent extremism by providing clear information about what to look for and how to take action when concerns arise.

## User Value

This website educates visitors about radicalization warning signs through an interactive carousel showcasing five key indicators (glorifying violence, identity transformation, social isolation, dehumanizing language, and fixation on grievances) so that community members, educators, and family members can identify at-risk individuals and access official reporting channels to potentially prevent acts of terrorism.

## Deployment Procedure

The website can be deployed using any static hosting service since it consists of HTML, CSS, and Bootstrap components with no server-side processing required. Steps for deployment would include: uploading all files (index.html, css/styles.css, and assets/ folder) to a web hosting service, ensuring proper file structure is maintained, and configuring the domain to point to the index.html file as the root document.te

## Screenshots (with brief user value descriptions)

### Hero Section

The landing page features a clear call-to-action button linking to the official UK government terrorism reporting site, along with emergency contact information (999) prominently displayed. This immediate access to reporting mechanisms provides users with a direct path to take action on their concerns.

### What is Prevent Section

A visually organized breakdown of Prevent's three core functions using bullet points and contrasting colors. This section educates users about the strategy's approach to tackling terrorism ideology, early intervention, and rehabilitation, helping them understand the broader context of counter-extremism efforts.

### Signs of Radicalization Carousel

An interactive Bootstrap carousel displaying five key warning signs with background imagery and detailed descriptions. Each slide covers specific behaviors like glorifying violence, identity transformation, social isolation, dehumanizing language, and fixation on grievances, giving users concrete examples to recognize in their communities.

### Responsive Navigation

A mobile-first navigation system with special consideration for tablet users (exposed home link) and smartphone safe areas for device notches. This ensures accessibility across all devices while maintaining clean, professional presentation.

## AI & Outcomes

### AI’s Role in Creating/Resolving Key Bugs

bug → impact

-   suggested max-width in media queries instead of min-width → would not have activated responsive breakpoints properly

### Key Improvements From AI

improvement → impact

-   add safe area rule for notches etc. in css on nav bar → apple devices dominate some markets, so its important
    to account for their quirks
-   be aware of possible notches on smartphones → ensured adequate padding at top of nav bar
-   numerous how to wireframe tips → felt more at ease doing a form of design that I had never done before
-   noted my buttons were too small in my wireframe → easier to click on buttons with fingers on smartphones
-   be cautious of dense paragraphs unless necessary → introduction to prevent is more likely to be read when split into three bullet points
-   remove second repeated CTA → looks less pushy on a sensitive website related to prevent
-   remove fixed back to home button → i will have a sticky nav bar so it was redundant
-   expose one key nav link in tablet → easier for tablet users to return to the key hero section
-   reminder to use whitespace on either side in desktop → shouldn't be taking up the full width of screen like on a smartphone

### Overall Impact of AI on Efficiency

efficiency → impact

-   partially automating commits → easier but ai commit messages often require editing
-   summarizing large chunks of text for comprehension or content → saves time by removing non critical text but have to check that it hasn't omitted something key
