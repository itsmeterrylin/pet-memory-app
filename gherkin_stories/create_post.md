Feature: Create a post

Scenario: Successfully creating a new post with a photo
   Given the user is on the Create Post screen
   When the user enters a valid post title
   And the user selects a photo
   And the user taps the "Submit" button
   Then the post should be saved with the title and photo
   And the post should appear in the list of all created posts
