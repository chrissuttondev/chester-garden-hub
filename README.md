# CHESTER GARDEN HUB
![chester-Garden-Hub-devices](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/63c2c643-e109-4155-b2ea-6b9177b46ebb)

Chester Garden Hub is a site that aims to inform people and encourage them to become involved with a community garden project based in Chester, UK. The site will be targeted toward people in the Chester area who have an interest in gardening, the environment, and their local community. It will be of value to the target demographic by providing them with information on the garden project, details on how they can get involved, and a contact form where they can submit an expression of interest.
# Table of Contents
1.<a href="#ux">UX</a>
<br><br>
2.<a href="#features">Features</a>
<br><br>
3.<a href="#bugs">Bugs</a>
<br><br>
5.<a href="#technologies-used">Technologies Used</a>
<br><br>
6.<a href="#credits">Credits</a>
<br><br>
7.<a href="#deployment">Deployment</a>
<br><br>
8.<a href="#contact">Contact</a>

# UX

### Visitor Goals
Target Audience 
- Gardening and food-growing enthusiasts
- Volunteers seeking opportunities
- Community-minded individuals

User Goals:
- Overview of Chester Community Garden Hub
- View project facilities' images
- Learn about involvement opportunities

Chester Garden Hub achieves these goals with:
- Impactful hero image and tagline on the homepage.
- Brief "About Us" section explaining the project's start.
- "Our Mission" section outlining project aspirations.
- "Our Garden" page showcasing garden features.
- "Get Involved" page with participation details and a contact form.

### Project Goals
- Provide information on the project's background, inception, and objectives.
- Recruit new members and volunteers.

### User Stories
- As a gardening enthusiast, I expect to see photographs of the garden and a comprehensive overview of the offerings available.
- As someone interested in volunteering at a community project, I expect to find a clear description of the available roles and how I can contribute.
- I would like to easily follow the project's updates and activities on social media platforms.

## Visual Design

### Wireframes
<img src="https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/aae26181-26c4-415b-bc6e-f6260767e953" alt="chester garden hub wireframe examples" width=50% height="auto">

### Fonts
- The Oswald font was used due to its attractive appearance, easy readability, and suitability for headings

### Icons
- The website utilizes icons from the Font Awesome icon library, specifically in the footer section. These icons serve as clickable links, directing users to the respective social media pages.

### Colors
Chester Garden Hub's design is minimalist, with garden images providing color and vibrancy. The color scheme includes green for nature and tranquility, pink for vibrancy and optimism, and dark gray for contrast and stability.

![coolors](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/4076e9af-29d0-4b22-a85d-a5764627b5d1)

# Features

### Header
 - The responsive header, present on every page of the site, includes a logo and site navigation menu. 
 - The menu provides links to the Home, Our Garden, and Get Involved pages, ensuring smooth and easy navigation between pages without relying on browser back buttons.

![header](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/a4e0fce0-d99d-4a81-a5eb-b9654c5726a8)

### Hero
- The hero section of the website features an eye-catching image and a punchy tagline.
- The primary objective is to convey to the user that this is a community project with 
  immense potential and that they can actively participate and get involved.

![hero](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/df7b9b02-b7ea-4340-ba69-c0b4042cd162)

### About Us
- "About Us" gives the project's background and origin.


![about](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/0c21a879-d366-413b-b909-a4b61d819599)

### Our Mission
- "Our Mission" details the project's goals and aspirations.


![mission](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/62d20f89-2792-478a-bf3d-a41c9ef707f5)

### Footer
- Includes social media links to Chester Garden Hub's accounts.
- Offers users the opportunity to follow the project on social media.


![footer](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/9148af9e-3a0f-4e82-9936-c46c743e4b0f)

### Our Garden
- Provides an overview and images of garden facilities.
- Explains the purposes and features of different garden parts.


![our garden 1](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/7382aaa8-dcb2-4da4-b232-97e36490f4cd)


![our garden 2](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/0264e150-2100-4c90-b5f1-63882c8c6154)

### Get Involved 
- Provides info on project membership and volunteer opportunities.
- Features a responsive contact form for expressing interest.
- Includes validation and asks for the user's name and email address.


![form](https://github.com/chrissuttondev/chester-garden-hub/assets/136370848/6da9655b-20c9-46e6-bbbd-2c298cf2be99)


### Additional Features
- Time Table of Events: Adding a timetable of events to inform users about upcoming meetings and activities.
- Participant Stories and Sound Bites: Including stories or short quotes from participants to provide insight into the potential impact of being involved in the project.
- Blog Section: Creating a blog section to post content on gardening tips, advice, and updates about Chester Garden Hub.

# Testing
## Validator Testing
- Html Code was passed through W3C official validator. No errors were returned.
- CSS Code was passed through the Jigsaw official validator. No errors were returned.

# Bugs
### Unfixed Bugs
- There are no unfixed bugs in the project.
### Fixed Issues / Challenges Faced 
The site was designed with a mobile-first approach, starting with a screen width of 320 pixels. CSS Flexbox was utilized to control element layout, with a vertical column structure for smaller screens and a combination of vertical and horizontal layouts for larger screens.

However, when applying a media query to change the flex-direction property from column to row for the header section, everything worked as expected. But in the about us and our mission sections, elements like headings, paragraphs, and images were not displaying as intended. They appeared on a single line and were squeezed together.

To address this issue, a solution was implemented by adding container divs within the original divs that utilized flex-direction: row. These new container divs only took effect for screen sizes of 768 pixels and above, while the original flexbox with flex-direction: column remained unchanged regardless of screen size. This approach helped achieve the desired horizontal layout when triggered by the media query, resolving the layout display problem.

# Technologies Used
### Languages
- HTML: Markup language for creating the website's structure.
- CSS: Styling language to design the website's appearance.

### Libraries
- Google Fonts: Used to access and apply font styles to the website.
- Font Awesome: Provides a library of icons for use in the project.

### Platforms
- GitHub: Utilized for version control, code storage, and site deployment.
- CodeAnywhere: Chosen as the development environment for the project.

### Additional Tools
- <a href="https://inkscape.org/">Inkscape:</a> Used for creating wireframes, and assisting in the website's design process.
- <a href="https://www.favicon-generator.org/">Favicon Generator:</a> Employed to generate the favicon for the website.
- <a href="https://coolors.co/"> Coolors:</a> Utilized to create the color scheme used in the project.
- <a href="https://techsini.com/multi-mockup/index.php">Mulit-Mock Up</a> to generate images of site on variuos devices.

# Credits

### Styling
- The styling for the logo section of the project was inspired by the <a href="https://code-institute-org.github.io/love-running-2.0/index.html"> Love Running website.</a>
   Oswald font and letter spacing were used to achieve the typography style.

### Code
- The form section of the website uses code from the W3Schools website: https://www.w3schools.com/howto/howto_css_contact_form.asp
- The code was modified and restyled to suit the specific needs and design of the project.

### Media
- Images used on the site were sourced from Unsplash and Pexels.
- Unsplash collection link: https://unsplash.com/collections/9165A2aJsPc/garden-hub
- Pexels collection link:  https://www.pexels.com/collections/garden-hub-exztcbl/

# Deployment

To deploy the site to GitHub Pages:

- Go to the repository's "Settings" tab.
- Scroll to the "Pages" section.
- Choose "Deploy from branch" in the "Source" dropdown.
- Select the "main" branch.
- Save and refresh the page.
- The site link displayed at the top.

Live link to the website https://chrissuttondev.github.io/chester-garden-hub

# Contact
 chrissutton1789@gmail.com 






  







  
