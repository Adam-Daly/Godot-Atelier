# Godot Atelier Website

Deployed version here: [Godot Atelier](https://github.com/Adam-Daly/Godot-Atelier/commits/main/)

![Website Preview](/assets/images/readme/website-preview.png)

## User Experience
The Godot Atelier website offers an intuitive and informative platform for individuals interested in learning game development using the Godot game engine. With its clean design and easy navigation, users can quickly access course information, learn about instructors, and sign up for courses.

## Target Audience
This website caters to aspiring game developers, whether beginners or experienced individuals looking to enhance their skills in 2D or 3D game development. It appeals to those seeking structured courses led by industry experts in a supportive online learning environment.

## User Stories
- As a novice game developer, I want to find comprehensive courses that cover both 2D and 3D game development so I can learn at my own pace.
- As a seasoned game developer, I seek expert guidance and real-world applications to improve my skills and stay updated with the latest trends.
- As an individual interested in game development, I want to connect with a supportive community and learn from experienced instructors to kickstart my career in the gaming industry.

# Design

1. A wireframe sketch was made to get an idea of the layout quickly.

    ![Wireframe](/assets/images/readme/wireframe-sketch.png)

2. [COOLORS](https://coolors.co/) was used to explore color themes for text and background colors.

    ![COOLOR](/assets/images/readme/color-themes.png)

3. [Looka](https://looka.com/) was used to explore logo ideas

   ![LOOKA](/assets/images/readme/logos.png)

4. [Figma](https://www.figma.com/) was used to nail down the design and layout of the website

   ![Figma](/assets/images/readme/figma.png)

## Features
1. **Informative Navigation**: Easy-to-use navigation allows users to explore different sections of the website, including courses, instructors, and sign-up forms.

    ![Navigation](/assets/images/readme/nav.png)

2. **Godot Features**: List of the main features that might draw someone to using Godot, such as the scripting languages and being open source.

    ![Godot Features](/assets/images/readme/godot-features.png)

3. **Course Details**: Detailed information about 2D and 3D game development courses, including structured email lessons, interactive exercises, and progressive learning paths.

    ![Course Details](/assets/images/readme/course-details.png)

4. **Instructor Profiles**: Profiles of experienced instructors, providing insights into their background and expertise in game development.

    ![Instructor Profiles](/assets/images/readme/instructors.png)

5. **Sign-Up Form**: A simple sign-up form where users can register for courses by providing their name, email, and preferred course type (2D, 3D, or both).

    ![Sign Up Form](/assets/images/readme/sign-up-form.png)

6. **Responsive Design**: The website is designed to be responsive, ensuring a seamless user experience across various devices and screen sizes.

    ![Responsive Design](/assets/images/readme/responsive.png)

## Future Feature Ideas
1. **Interactive Learning Tools**: Implement interactive learning tools such as quizzes and coding challenges to enhance user engagement and learning outcomes.
2. **Video Content**: Embed demos of recorded video content with instructors to provide additional support and clarification on course materials.
3. **Game Showcase**: Showcase games made by students or studios with the Godot game engine through the course.
4. **Advanced Courses**: Expand course offerings to include advanced topics such as game optimization, multiplayer game development, and virtual reality experiences.

# Technoloy Used

1. Github
2. Gitpod and VScode
3. Figma

# Languages Used

1. CSS
2. HTML

# Deployment

Deployed via github pages

![Deployment](/assets/images/readme/deploy.png)

1. Upload all files to a github repo.
2. Navigate to your settings page for the repo.
3. Click "Pages" and then "Deploy from a Branch" and choose the correct branch (usually main).

#  Testing

1. **Jigsaw CSS Validator**: Found one error with font optical sizing which I removed.

    ![Jigsaw](/assets/images/readme/jigsaw.png)

2. **W3C HTML Validator**: Identified a mistake with closing an ol list with the ul tag. There was also a duplicate ID which I changed to a class.

    ![W3C Validator](/assets/images/readme/w3c-validator.png)

3. **Lighthouse**: Using chrome dev tools, the lighthouse report was mostly positive except for performance. Large images were the culprit. 

    ![Lighthouse](/assets/images/readme/lighthouse.png)
    
# Bugs

1.  **Issue**: Large amounts of horizontal space when viewed on mobile with no obvious element causing it.

    **Fix**: using chrome dev tools, able to identify a form element had desktop width, fixed with media query. 

2.  **Issue**: When deploying, the css and images were not showing up.
    
    **Fix**: The urls do not need a / in front of them for relative urls, such as "/assets/images/image.png". "assets/images/image.png" is correct.

3.  **Issue**: Nav link does not go to the correct position when clicked.

    **Fix**: There were duplicate entries of the same ID. Changed one of them and link jumped to correct position.

# Credits

## Image Sources

### Logos
- Sega Logo: https://upload.wikimedia.org/wikipedia/commons/4/41/SEGA_logo.png
- Blizzard Logo: https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Blizzard_Entertainment_Logo.svg/1280px-Blizzard_Entertainment_Logo.svg.png
- Ubisoft Logo: https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/Ubisoft_logo.svg/2238px-Ubisoft_logo.svg.png
- Capcom Logo: https://upload.wikimedia.org/wikipedia/commons/2/2f/Capcom_logo.png
- Godot Atelier Logo Exploration: https://looka.com/

### Godot Features Images
- Innovative: https://godotengine.org/assets/home/features/innovative.webp
- Language Support: https://godotengine.org/assets/home/features/language.webp
- 2D Development: https://godotengine.org/assets/home/features/2d.webp
- 3D Development: https://godotengine.org/assets/home/features/3d.webp
- Cross-Platform: https://godotengine.org/assets/home/features/cross-platform.svg
- Open Source: https://godotengine.org/assets/home/features/oss.svg

### Instructor Portraits
- https://www.krea.ai/

### Banner Image
- https://raw.githubusercontent.com/godotengine/godot-design/master/screenshots/editor_tps_demo_1920x1080.jpg

## Font Sources
- Source Sans 3: https://fonts.google.com/specimen/Source+Sans+3

