### Day25:
## VALIDATION!
x-Watch the video, then do the same thing for your Videogames app from Day24.
x-Validate input, return errors on the backend.
Catch them on the frontend and make your form user friendly!

Defien your own validation rules.
Some examples:
x- is your input type the type you expect it to be? ie: can i pass an array instead of a string as .req.body.name and pass your validation, breaking shit?
x- length checks
- bad word filters
*********ETH ADDRESS CHECKER
if (!ethers.utils.isAddress(enteredAddress)){}
*********************** #TODO put this on NFT viewer 

### Day24:
Combining express and Svelte (SERVER and CLIENT), as well as "cheating" with a database by using a file!

## HOMEWORK:
Create a frontend with Svelte and a backend with Express, like I do in my video, for a model of "Videogames", stored in a file "videogames.json". See my video for file structure!
Your form should have:
- Name
- Platform it's on
- Year of release
- Genre
- ESRB  rating
- Boolean value of whether it's good or not.

BONUS:
Add an IMAGE FILE UPLOADER to the Form, and save it in the backend as well! ( ask for help if you need )