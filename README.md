# Grid_Structure
## Hosted Link: https://mayankkatheriya.github.io/Grid_Structure/
![image](https://github.com/Mayankkatheriya/Grid_Structure/assets/128832286/f42e0673-8825-4c04-8bc1-187f056329ec)
![image](https://github.com/Mayankkatheriya/Grid_Structure/assets/128832286/3a6f959b-b316-4df7-8cde-00bc7a41dca9)

HTML:

The HTML structure defines a basic webpage with the title "Grid Structure." It includes metadata and a stylesheet link for styling. The webpage content is contained within a "container" division.

Inside the "container" division, there's currently no content.

After the "container" division, there's a paragraph containing a URL: "https://www.podia.com/pricing." This URL appears to be unrelated to the content inside the "container" division and is placed directly in the body of the webpage.

Overall, the webpage structure seems minimal, with a focus on the "container" division which might potentially contain more content or elements in the actual implementation.

CSS:

Global Reset:

Targets all elements.\
Sets margin, padding, and box-sizing to create consistent spacing and sizing.\
Applies the 'Arial', 'Helvetica', sans-serif font family to all elements.

.container Class:

Sets background color to black.\
Adds a 1px solid white border.\
Sets width to 100%.\
Sets height to 36rem.\
Uses grid display for layout.\
Divides the grid into 16 columns with each column taking 6.25% of the container's width.\
Divides the grid into 6 rows, each with a fixed height of 6rem.

p Selector:

Targets all p elements.\
Sets font size to 16px.\
Uses 'Times New Roman', 'Times', serif font family for paragraphs.\
![image](https://github.com/Mayankkatheriya/Grid_Structure/assets/128832286/5beba00b-78ee-422b-882b-2f125816ad5b)
\
\
\
![image](https://github.com/Mayankkatheriya/Grid_Structure/assets/128832286/f4cd4192-df5c-433e-9105-93dd30d506f7)
![image](https://github.com/Mayankkatheriya/Grid_Structure/assets/128832286/7b43dd34-f7dd-4d46-a755-0a6eb1370fa0)
HTML:

"blank1": An empty division, likely used for spacing or layout purposes.\
"nav": This division contains a set of buttons and an image, forming a navigation menu.\
"Home" button\
"About" button\
Logo image\
"Menu" button\
"Contact" button\
"blank2": Another empty division, possibly used for spacing.\
"item1" to "item9": These divisions each contain an image, which appear to represent different items.\

CSS:

.container div:

Targets all <div> elements within the .container class.\
Sets background color to black and adds a small padding.

img:

Targets all <img> elements.\
Sets the height and width to 100%.\
Adds a 3px white solid border around the images.

div .nav:

Targets elements with the class .nav within <div> elements.\
Sets grid-column to span from the 4th column to the 4th column from the end.\
Sets background color to white.\
Adds margins and uses flex display for layout.\
Justifies content space-around and aligns items to the center.\
Adds a gap of 110px between items.

div .blank1 and div .blank2:

Targets elements with the classes .blank1 and .blank2 within <div> elements.\
Sets background color to white.\
Defines grid-columns for different sections and applies margins.

button:

Styles buttons with black background and white text.\
Sets width, padding, and border-radius for a rounded appearance.

div .nav img:

Targets <img> elements within .nav elements.\
Sets height to 95% and width to 85px.

.item1 to .item9:

Targets elements with classes .item1 through .item9.\
Defines grid-column and grid-row positions using span and specific column numbers.\
These classes are likely used to position different items within the grid layout.\
![image](https://github.com/Mayankkatheriya/Grid_Structure/assets/128832286/48ff3353-4b6b-4988-a1fb-f7dd1e3ce2bd)
