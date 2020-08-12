Inspiration

As a result of the recent events in 2020, including but not limited to the COVID-19 pandemic, Yemen humanitarian crisis, and the Black Lives Matter movement, we wanted to provide people with an option to educate themselves and support others across the nation and across the world. We help users find petitions to sign, organizations to support, and causes from all over the world to learn about and make it easy for them to take action.


What it does

ActiBridge is a website that will allow its users to bridge the gap between activism and ignorance and take action with movements they care about. Users can take a quiz that will personalize their results and show them various causes they can support, petitions they can side, and organizations to which they can donate. In addition, they can select their representative, and ActiBridge will automatically create and format an email for them to send.


How I built it

We built ActiBridge in Glitch using html, css, and javascript. Additionally, we used arcgis to create a map that allows users to find and set up local protests. The color scheme and layout was created in Adobe Color and draw.io. Our logo was created in Procreate and rendered with vectors in Paint Tool Sai. All photographs were found on online photo sharing platforms that offered free to share media, such as Wikimedia Commons and Flickr. The photographs were appropriately sized and given colored overlays in Pixlr. For our backend development, we integrated Firebase and Google Login to allow the user’s data to be stored-- data which would be meant to help make their experience more personalized on the “Match Up” and “Outreach” pages.


Challenges I ran into

The “Outreach” page allows the user to enter their ZIP code and matches them with their representative. One challenge that we ran into was creating an email template directly in their computer’s local mail application. Since the website uses an HTML form, the email had to be formatted using textareas. At first, we used a text element instead and were unable to add line breaks, and when using normal spaces the email would format with “+” between each word. We fixed this by changing the body element to a textarea and adding ASCII codes for spaces and line breaks.

While laying out the CSS of the entire website, we ran into several problems with consistent formatting, integrating photos into our color scheme, and ensuring the functionality of buttons and links. Although it was the first time many of our team members worked intensively with CSS, we were able to fix the various bugs by testing different solutions from sites such as StackOverflow and W3Schools. For integrating photos into our color scheme in particular, we were unable to fully solve the issue, as overlaying an unedited photo with a separate colored container never fully lined up the photo and the colored screen; unedited photos were also often too small for our website to host cohesively. We ended up editing the photos of protests outside of the CSS formatting. However, given more time we would continue to develop a more efficient solution that would allow developers to upload unedited photos and play with color overlays directly in the source code.

Glitch, the editor we hosted our project on, would often overload with requests, which made it difficult for our team to edit and test features on ActiBridge in real time. We addressed this by using local text editors to test our code and by playing with the Glitch editor settings to prevent automatic updates to our website.


Accomplishments that I'm proud of

We're proud of how the Outreach page came together. After about an hour of tinkering between GET and POST forms, text vs text/plain, and the textarea versus text, ew was able to figure out how the form works. The email was formatted correctly once the mail application opens, and we got to learn the difference between GET and POST.

We are also proud of the interactive elements in the navigation bar and the Black Lives Matters library page. The animations in the navigation bar and the hovering opacity features of the library page were new CSS features that most of us had never worked with before, and it was so cool to see that we could apply them successfully to website features of our choice.


What I learned

On the frontend side, we learned about CSS specificity and how to develop centralized stylesheets that determine style for all web pages. We learned how to create animations to make the website more interactive in CSS and Javascript. We learned to use structures such as grid containers to house multiple photos in cohesive and easily editable ways. On the backend side, we learned how HTML forms receive and process data that is entered, as well as how to set default, formatted values for parts of the form. We learned how these forms can be used to send emails from the user’s personal email. We learned how to integrate Google Login with our database and our frontend to make a user’s experience more familiar and personalized. Through research, we also learned that personalization is complex to implement, as it requires constant interactions between the front and back ends to make a user's experience unique. We were not able to fully implement the personalization factor, but through developing aspects that would lead to personalization, we learned a lot about how we might implement it in the future.


What's next for ActiBridge

We hope that in the future, we can continue to develop ActiBridge in ways that will make activism resources more accessible, interactive, and localized for aspiring social change makers. We hope that it can connect people from both local and global regions of the world. Also we would like to store user preferences in firebase to personalize their experience.


Built With

arc.gis, css, esri, firebase, html, javascript


Team Members

Anjali Kumar, Neha Konjeti, Helena Yang, Hannah Kim, Anthony Franco


Try it out

https://actibridge.glitch.me/


Devpost Submission

https://devpost.com/software/actibridge-cqrdtu
