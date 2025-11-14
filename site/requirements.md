You are an expert full stack engineer who are going to assist me to build a learning platform where users can do some functionalities

Resources
--------
    - Learning Tracks
        - Predefined Learning Tracks
            - Software Engineering
            - Embedded Software Engineer
            - Java Software Engineer
            - Python Software Engineer
            - Testing Engineer
            - DevOps Engineer
        - User defined Learning Tracks
        - Each Learning Track has
            - Title
            - Description
            - Image
            - Review Rating
            - Number of Reviews
            - Number of Learners
            - Number of Resources (Courses, Books, Projects, Articles)
            - Skills User will learn
            - Estimated Time to Complete
            - Enroll button
            - Three Levels (Beginner, Intermediate, Advanced)
            - A set of learning resources under each level
            - Review rating
            - Comments
            
    - Learning Resources
        - Courses
        - Books
        - Projects
        - Articles
        - Talks & Videos
        - Each Learning Resource has
            - Title
            - Description
            - Image
            - Review Rating
            - Number of Reviews
            - Number of Learners
            - Skills User will learn
            - Estimated Time to Complete
            - Enroll button
            - Three Levels (Beginner, Intermediate, Advanced) as the Learning Track
            - Review rating
            - Comments

Functionality
-------------
    - User can login
    - User can search for learning tracks or resources
        - Search Bar or Filter
            - Learning Track
            - Level
            - Skills
            - Learning Resource Type
                - Courses
                - Books
                - Projects
                - Articles
                - Talks & Videos
    - User can share learning tracks or resources
    - If user is logged in, they can
        - Get notification about
            - New Learning Track or Resource
            - Their own learning tracks or resources
                - Like
                - Comment
                - Share
        - Enroll in a learning track or resources
        - Create learning tracks or resources
        - Edit their own learning tracks or resources
        - Delete their own learning tracks or resources
        - Rate and comment on learning tracks or resources They enrolled in or created
    - When a user do CD (Create, Delete) on learning tracks or resources
        - The admin receives a notification mail
            - If the admin approves:
                - The resources are CD (Create, Delete) to the system.
            - If the admin rejects:
                - The request is declined.
        - The user receives a notification mail with approval/rejection message.


      