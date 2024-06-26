# TidyHome Services

## The Tidy Home Cleaners website serves as a landing page for individuals and offices in Dublin City and its surrounding areas, offering professional cleaning services.

![image](./assets/images/worker.webp)


## Features

- **Navigation Bar**: 
  - The top of the page features a navigation bar with the home cleaning name, Tidy Home Cleaning, on the left, which links to the top of the page.
  - The right side of the navigation bar includes links to different sections of the page: About Us, Services, and Contact Us.
  - The navigation link has a hover border line of light gray color ('#ccc') for user indication.
  - The header has a white background and the text color is a shade of dark gray for better contrast.
  - The image explains that the site is for cleaning services.
  - This section provides the user with clear information about what the site is about.
  ![image](./assets/images/nav-bar.png)
  ![image](./assets/images/services-image.webp)

 

### About Us Page

#### Why Choose Us for Your Home Cleaning Needs



- The About Us section gives details about what Tidy Home Cleaners offer their members and includes headers and paragraphs outlining their services:
  - Satisfaction
  - Trained workers
  - Friendly
  - Stress-free

![image](./assets/images/aboutus-image.png)
  




 ### Services Section

- **Services section show the types of services they offer and includes headers and paragraphs explaining their services, outlining their services:**
  - **Satisfaction Guaranteed**
    - One-Off Deep Cleaning
    - End of Tenancy Cleaning
    - Upholstery Cleaning
    - Carpet Cleaning
    - After Builders Cleaning
    - Bathroom Steam Cleaning
    - Regular House Cleaning Services
    - Power Washing Driveways

    ![image](./assets/images/ourservices-image.png)

## Contact Information

- This section contains a form where the user can send a message. The form includes fields for the user's full name, email, and a text box where the user can describe the services they want.
- When the form is submitted, it will open in a new tab. The form's reply response is directed to Code Institute; this is just for project purposes as the company does not actually exist.
- The background image is a city center image showing offices, which are the company's target for cleaning services, and the water symbolizes cleanliness.

![image](./assets/images/contactus-image.png)

![image](./assets/images/contactform-image.png)



## Technologies Used

- HTML
- CSS

## Testing

- **Browser Compatibility**: Tested on Chrome, Microsoft Edge, Firefox, and Safari.
- **Responsiveness**: Confirmed the site looks good and functions on all standard screen sizes using devtools device toolbar.
- **Readability**: Ensured that the navigation, header, About Us, Services, and Contact text are all readable and easy to understand.
- **Form Functionality**: Verified that the form requires entries in every field, accepts only a valid email in the email field, and the submit button works.


## Validation Testing

- **HTML**: No errors were returned when passing through the official W3C validator.
- **CSS**: No errors were found when passing through the official Jigsaw validator.

## Validation Testing

- **HTML**: No errors were returned when passing through the official W3C validator.
- **CSS**: No errors were found when passing through the official Jigsaw validator.

## Accessibility

- I confirmed that the colors and fonts chosen are easy to read.
- The image performance is also good, as confirmed by running it through Lighthouse in DevTools.
![image](./assets/images/lighhouse-image.png)

# Getting Started

This section provides instructions on how to set up and run the project locally, as well as an overview of the deployment process.

## Setting Up Locally

To run this project locally:

- **Clone the repository**: Start by cloning the repository to your local machine using the following command:git clone https://github.com/desmond0147/tidyhome-services.git

- **Navigate to the project directory**: Change into the project directory: cd tidyhome-services

- **Open the project**: Open `index.html` in your web browser to view the site: open index.html

## Deployment Process

The project is deployed to GitHub Pages, which is a static site hosting service that takes files from a GitHub repository and serves them as a website.

Here are the steps followed to deploy the project:

- **Create a repository on GitHub**: A new repository named `tidyhome-services` was created on GitHub.

- **Link the repository to Gitpod**: The GitHub repository was linked to a Gitpod workspace for an integrated development environment that supports running the project directly in the browser.

- **Develop the project**: The project was developed within the Gitpod environment, making use of its features for writing, testing, and debugging the code.

- **Commit and push changes**: Changes were committed and pushed to the GitHub repository regularly using the following commands:
git add .
git commit -m "Commit message describing the changes"
git push

## Deploy to GitHub Pages

- From the source drop-down menu. select the Master Branch
- Once the master branch has been selected, the page provided the link to completed website. [tidyhome-services GitHub Pages](https://desmond0147.github.io/tidyhome-services/).

## Credits

- **Inspiration**: Love Running walkthrough project, Ai, google, YouTube Learn Web, mentor call sections.
- **Media**: Images were taken from Pexels. https://redketchup.io/image-resizer was use to resize image.

## Future Enhancements

Given more time, here are some additional features and improvements we would love to implement to enhance the TidyHome Services project:

1. **Interactive Features**:
   - **Contact Form**: Implement a user-friendly contact form to allow visitors to reach out directly from the website.
   - **Live Chat**: Add a live chat feature for real-time customer support and inquiries.

2. **Enhanced Content**:
   - **Blog Section**: Create a blog to share news, tips, and updates related to our services and industry trends.
   - **Testimonials**: Include a dedicated section for client testimonials to build trust and credibility with potential customers.

3. **Additional Pages**:
   - **About Us Page**: Add a comprehensive "About Us" page to share the story behind our project and team.
   - **Services Page**: Develop a detailed services page outlining the various offerings and specialties.

4. **Multimedia Content**:
   - **Gallery or Portfolio**: Showcase images or videos of our work to highlight successful projects and case studies.
   - **Tutorials and Case Studies**: Provide educational content or case studies demonstrating our expertise and successful outcomes.

5. **User Experience Enhancements**:
   - **Responsive Design**: Ensure the site is fully responsive and optimized for mobile devices to provide a seamless user experience across all platforms.
   - **Animations and Transitions**: Add subtle animations and transitions to enhance visual appeal and user interaction.

6. **SEO and Performance Improvements**:
   - **SEO Optimization**: Improve meta tags, alt texts, and content keywords to boost search engine rankings and visibility.
   - **Performance Optimization**: Optimize images, minify CSS/JS files, and implement lazy loading to improve site performance and load times.

7. **Analytics and Tracking**:
   - **Google Analytics**: Integrate Google Analytics to track visitor behavior, gather insights, and analyze site performance.
   - **Heatmaps**: Use tools like Hotjar or Crazy Egg to analyze user interactions and improve site usability.

## Contributing

We welcome contributions to improve our services and website. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

- Fixed an issue where the footer was floating after submitting the form. Resolved by setting the default styles to:

css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box; 
}