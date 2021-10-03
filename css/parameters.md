Project Overview

Taking our new skills further, this project entails creating a basic travel destination website, leveraging HTML, CSS, and component thinking.

To submit this deliverable, ensure you push a last git commit using the message ‘final commit’ to your GitHub repository before the submission deadline. In addition, create a text document with a link to your GitHub repository and upload to Synapse before the submission deadline.

Pay attention to the details of the mockup, and the instructions below to successfully complete this project.
Tools & Resources

    Convert a creative mockup into a functional multi-page static site using HTML and CSS
    Download the assets & mockups here to get a better idea of how your project should appear
        Keep in mind that the mockups were created for a screen size of 1280px wide.

Functional Requirements

    The site must have 4 Pages:
        Home Page
        3 Destinations Pages (Iceland, Greece, Hawaii)
    The Home Page must have 4 Sections:
        Navigation Bar
            The Navigation Bar must have working links for each Page (Logo (should link to the Home page), Home, Iceland, Greece, Hawaii)
        Hero
        Recommendations
            3 Cards, one for each destination must be linked to the appropriate destination page (Iceland, Greece, Hawaii). Clicking anywhere on the card must go to the destination page.
        Footer
    The Destination Pages must have 3 Sections:
        Navigation Bar (Same as Home Page)
        3 Itinerary Cards for a 3 Day trip (Friday, Saturday, Sunday)
        Footer (Same as Home Page)

Visual Design Requirements

    All pages must match the mock ups as closely as possible, being mindful of image distortion and proportions.

    The site must use the assets provided.

    Each page must have an identical navbar with the following style:
        The Navigation Bar must be fixed to the top of the page
        The background color must be #FFFFFF
        The site logo/wordmark color must be #335576
        The currently active page must be underlined using the color #DB7A4E

    Each page must have an identical footer with the following style:
        The background color must be #FEFAF5
        The footer titles and text must be the color #335576
        The footer subtitles must be the color #DB7A4E

    The base font for the site must be Verdana.

    Home Page - Hero Section:
        The hero background color must be #FEFAF5
        The text content must be left aligned
        The slogan color must be #335576
        The ‘Get Started’ Button background color must be #DB7A4E

    Home Page - Recommendations Section:
        The recommendations title must have the color of #335576
        There will be 3 Cards, one for each destination (Iceland, Greece, Hawaii)
        The destination name must be in the bottom right corner of the card
        The border radius of the cards must be 5px
        The border of the cards must be 1px solid black with an opacity of 20%
        The box shadow of the cards must be:
            Horizontal Offset: 0px
            Vertical Offset: 4px
            Blur: 4px
            Color: Black, with an opacity of 20%

    Destination Pages:
        They must have a title with the destination name
        The provided image asset for the destination must take up the full width/height of the background for the page.
        They must have 3 Days of Itinerary activities including:
            A title for the day of the week
            4 Itinerary activities (e.g. Breakfast, Lunch, Dinner, Snorkeling)
            Activities must have a background of #FEFAF5

Implementation Requirements

    You must use semantic tags where appropriate (e.g. header, footer, navbar, etc)

    All CSS must be placed in a separate stylesheet and connected to the HTML through the link tag.

    File/Folder structure must be organized and follow the Travel Site Structure Diagram





    Navigation Bar: The menu items must be specified using an unordered list

    Recommendations Destination Cards: Must use the <a> tag around the cards in order to link to the appropriate page.

    Itinerary Cards: Must use an unordered list for the itinerary activities

    Reuse as much styling and code as possible (e.g. Destination Cards and Itinerary cards), and build your project around common component code that you can reuse if possible.

    Use the BEM methodology for all your class names.

    The layout of your site must use the Box Model, the CSS display property and CSS positioning including Flexbox. For this project, you should not use floats.

Diving Deeper

If you have completed the requirements above, you may go above and beyond to demonstrate skills you have been learning. However, any further features you add to the project must not conflict with the provided requirements.

Suggestions for Diving Deeper:

    Make your site responsive so that it looks good at any dimension.
    Add hover animations to links. For example, when hovering over menu items in the Navigation menu, add an underline to the hovered item. For your destination cards, change border color or add an semi-transparent overlay when hovered.
    Add a page for the “Get Started” button that has a simple form that allows a user to select a destination and provide their contact information and message that would be used to begin the booking process. The page should have the same look and feel as the rest of the site.
