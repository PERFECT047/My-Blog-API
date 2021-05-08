# My-Blog-Web-App
Blogging Website with API in repo (My-Blog-Web-API). 

POST - To make a new post in the blogging website

GET - To get whole content for homepage

GET - indivisual content(or indivisual post)

**Working**

1. Communicates with JSON data base to update it's content and number of post in Homepage(Nodejs is used for API).
2. Homepage flexboxes with animations (CSS animation).
3. Each Indivisual posts are stored in DB so updation will be reflected (Communicationg with API).
4. To ceate new post have to upload Title, Content, also Image for cover (Multer for handling image).

**To Get It Working On Your System**
1. Make the api go live (by default it will be on port 3000)
2. Make sure the API content is unchanged if changed update address in app.js
3. In './api/models/Post.js' contains the Post class usend in API
4. Data.json is used for storing Data.
5. ./Uploads contains all image files to be used for(if changed make sure to rename properly or update in DB at post-image section)
6. example storgage form in Data.json 

{

    "id": "1581461442206",
    
    "title": "This is a New Blog Post",
    
    "content": "This is the content! ",
    
    "post_image": "uploads/post-image-1581461442199.jpg",
    
    "added_date": "1581461442206"
    
}


