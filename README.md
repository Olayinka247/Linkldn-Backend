# Linkldn-Backend

# API #
    PROFILES:
    - GET https://yourapi.herokuapp.com/api/profile/

    Retrieves list of profiles

    - GET https://yourapi.herokuapp.com/api/profile/{userId}

    Retrieves the profile with userId = {userId}

    - POST https://yourapi.herokuapp.com/api/profile/

    Create the user profile with all his details

    - PUT https://yourapi.herokuapp.com/api/profile/

    Update current user profile details

    - POST https://yourapi.herokuapp.com/api/profile/{userId}/picture

    Replace user profile picture (name = profile)

    - GET https://yourapi.herokuapp.com/api/profile/{userId}/CV

    Generates and download a PDF with the CV of the user (details, picture, experiences)

 

 

    EXPERIENCE:
    - GET https://yourapi.herokuapp.com/api/profile/:userName/experiences

    Get user experiences

    - POST https://yourapi.herokuapp.com/api/profile/:userName/experiences

    Create an experience.

    - GET https://yourapi.herokuapp.com/api/profile/:userName/experiences/:expId

    Get a specific experience

    - PUT https://yourapi.herokuapp.com/api/profile/:userName/experiences/:expId

    Get a specific experience

    - DELETE https://yourapi.herokuapp.com/api/profile/:userName/experiences/:expId

    Get a specific experience

    - POST https://yourapi.herokuapp.com/api/profile/:userName/experiences/:expId/picture

    Change the experience picture

    - GET https://yourapi.herokuapp.com/api/profile/:userName/experiences/CSV

    Download the experiences as a CSV

 

 

    POSTS:
    - GET https://yourapi.herokuapp.com/api/posts/

    Retrieve posts

    - POST https://yourapi.herokuapp.com/api/posts/

    Creates a new post

    - GET https://yourapi.herokuapp.com/api/posts/{postId}

    Retrieves the specified post

    - PUT https://yourapi.herokuapp.com/api/posts/{postId}

    Edit a given post

    - DELETE https://yourapi.herokuapp.com/api/posts/{postId}

    Removes a post

    - POST https://yourapi.herokuapp.com/api/posts/{postId}

    Add an image to the post under the name of "post"
    
   Deployed -  https://linkdln-clone.herokuapp.com/posts

 
