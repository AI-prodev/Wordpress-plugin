## Requirement
Make a plugin that adds an "Awesome Posts" custom post type section to the WordPress dashboard.
The custom post type has 7 fields.
TITLE - Post Title
IMAGE - File Upload Button
TEXT-1 - Text Input Field
TEST-2 - Text Input Field
START - Date Picker
END - Date Picker
When the custom post is published, it save a post to the database like normal, and also saves the post contents to a .csv file in wp-content/awesome-posts.
There are 4 hidden fields that are saved with every awesome-post as well. (WEIGHT,HEIGHT,COLOR,MATERIAL) filled out with (10lbs.,7FT,Green,Canvas)
The .csv file to include the columns POST-ID, TITLE, IMAGE-URL, TEXT-1, TEXT-2, TEXT-3, START, END, WEIGHT, HEIGHT, COLOR MATERIAL