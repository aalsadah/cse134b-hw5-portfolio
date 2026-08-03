Website Netlify Link: [alis-portfolio-ucsd.netlify.app](https://ali-portfolio-ucsd.netlify.app/)

## Progressive Enhancement

For the Progressive Enhancement with JavaScript I went with the Form Validation and Error Reporting Feature. My baseline feature concerning the form was to validate the user input using native HTML and CSS controls which checked for required feilds left empty, and min/max inputs. The CSS invalid/valid-user psuedoclass modified the content of the input feilds and would add either a checkmark or an x. The JS script adds the feature which includes written outputs next to the feilds detailing the exact errors for why the user inputs are incorrect, and also allows the Narrator tool API to announce those error messages which improves the accessibility of the feature.

## Web Component

For the webcomponent I went with the dad joke api: [icanhazdadjoke.com](https://icanhazdadjoke.com/api)

I made the custom tag `<dad-joke>` for it, and the website had a simple to use api which did not require any keys and all I needed to do was fetch the endpoint url.

## SSG

For static site generation I decided to use 11ty, local setup and installation went smoothly. I downloaded it using npm and following the "Get Started" instructions on their website. however I found working with all the new files to be challenging and it was difficult to keep track of all the changes. I did not want to restart all site progress from scratch, I also noticed that SSG conversion cost some of the JavaScript features I implemented earlier. 

## Overall

I am very grateful for everything I learned in this course. Webdev truly has so much depth and complexity and it is clear to me that I was hearing alot of misconceptions that were reducing how much depth different topics in webdev contain. I feel like this course and these assignments have opened my eyes to what is possible to achieve and how important finding the best solutions is. This assignment especially has been challenging, but I also found it very valuable. 