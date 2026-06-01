# Full Project Context Prompt — Alargam Portfolio

I am working on a personal portfolio website for:

**Name:** Alargam Mohamed Osman  
**Displayed Name:** Alargam Osman  
**Role:** AI Software Engineer  
**Specialization:** Artificial Intelligence, Computer Vision, Robotics, Edge AI, Automation, and Real-Time Intelligent Systems  
**Email:** alargam.yagoub@gmail.com  
**GitHub:** https://github.com/alargam/  
**LinkedIn:** https://www.linkedin.com/in/alargam-osman/  

This file explains the full context of the portfolio project so any AI assistant or developer can understand what has already been built, what the goal is, and how to continue working on it correctly.

---

## 1. Project Overview

This is a personal portfolio website for Alargam Osman.

The goal of the website is to present Alargam as a strong AI Software Engineer with a focus on:

- Artificial Intelligence
- Computer Vision
- Robotics
- Edge AI
- Real-Time AI Systems
- Automation
- Embedded AI systems
- Model deployment
- Practical intelligent software solutions

The portfolio is based on the Frontend Mentor / TheCoderCoder single-page developer portfolio template:

Original GitHub template:
https://github.com/thecodercoder/fem-single-page-developer-portfolio

The project has been customized heavily to match Alargam's AI/Robotics identity instead of a frontend developer identity.

---

## 2. Current Project Structure

The local project folder is:

```bash
~/Portoflio/portfolio

Main files:

index.html
style.css
README.md
assets/
assets/images/

Important images inside assets/images/:

alargam-profile.jpg
alargam-profile-edited.jpg
AMR.png
Face_mask.png
xray-super-resolution.png
face-recognition-attendance.png
pattern-rings.svg
pattern-circle.svg
icon-invalid.svg
favicon-32x32.png

3. Website Type

This is a static website.

Technologies used:

HTML
CSS
JavaScript
GitHub Pages
FormSubmit for contact form email delivery

No React, no Node.js, no backend, and no database are used.

4. Deployment Target

The project is being deployed to GitHub Pages.

GitHub repository:

https://github.com/alargam/portfolio

Expected live website URL:

https://alargam.github.io/portfolio/

All asset paths must use relative paths like:

./assets/images/image-name.png

Do not use absolute paths like:

/assets/images/image-name.png

because the site will run under /portfolio/ on GitHub Pages.

5. Visual Style

The design should remain:

Dark / black background
Clean and modern
Minimal
Professional
AI / robotics / engineering focused
White text
Green accent underline
Sharp project thumbnails
Simple layout with strong spacing

Main accent color is defined in CSS as:

--accent: hsl(153, 71%, 59%);

This green accent is used for underline effects under:

Alargam Osman
About Me
Skills
Projects
Contact
Contact buttons / links
6. Hero Section

The hero section currently contains:

Hi, I'm
Alargam Osman
AI Software Engineer.
Contact me

Important design requirement:

The hero text should sit lower and feel balanced in the first screen.
It should not be too high.
It should visually balance with the profile image on the right.
The green underline must stay under the name only.
No long paragraph should be under the hero title, because the About Me section already explains the profile.

The hero image is:

./assets/images/alargam-profile-edited.jpg

There is also:

./assets/images/alargam-profile.jpg

The edited image is preferred for display.

7. About Me Section

The About Me section exists because the hero section should stay clean.

The current purpose of the About Me section is to explain Alargam's professional identity in a confident way.

Current About Me content should be close to this:

Software Engineer specializing in Artificial Intelligence, Computer Vision, Robotics, and Automation systems. I focus on building practical AI-powered software that transforms machine learning models into real applications, tools, and workflows that can be used in real-world environments.

My work combines software engineering with applied AI, including Python, OpenCV, PyTorch, TensorFlow, YOLO, ROS 2, Edge AI, model deployment, and system integration. I build end-to-end solutions such as computer vision pipelines, recognition systems, autonomous robotics platforms, medical image enhancement projects, and intelligent automation workflows.

I also build automation solutions using n8n, APIs, and AI services to create scalable workflows for business and technical use cases. My goal is to deliver reliable intelligent systems that bridge the gap between AI research, software products, and practical business value.

The tone should be:

Strong
Professional
Confident
Not weak
Not saying "I am open to anything" too much
Focused on value, building systems, real-world applications
8. Skills Section

The Skills section was expanded based on Alargam's CV.

Current skills should include:

Python
Computer Vision
Deep Learning
Edge AI
Robotics
Embedded Systems
C++
Model Deployment
Automation

Suggested descriptions:

Python — AI & Software Development
Computer Vision — OpenCV, YOLO & Image Processing
Deep Learning — PyTorch & TensorFlow
Edge AI — ONNX, TensorRT & Optimization
Robotics — ROS 2, SLAM & Navigation
Embedded Systems — ESP32, Raspberry Pi & micro-ROS
C++ — Embedded & Robotics Development
Model Deployment — Real-Time AI Applications
Automation — n8n, APIs & Workflow Engineering

Important visual requirement:

Skills text should not be too huge.
Skills title size should be smaller than the original template.
The section title Skills must have a green underline like other section headings.
The skills grid should feel balanced and not crowded.
9. Projects Section

The portfolio currently shows four main projects.

Project 1

Title:

Autonomous Mobile Robot

Tags:

Robotics
Navigation
Computer Vision

Image:

./assets/images/AMR.png

View Project link:

./projects/amr-robot.html

View Code link:

https://github.com/alargam/AMR_Robot

Project context:
This is an Autonomous Mobile Robot project involving ROS 2, SLAM, navigation, sensor fusion, LiDAR, camera data, Raspberry Pi, ESP32, micro-ROS, and real-time AI/robotics integration.

Project 2

Title:

Face Mask Detection System

Tags:

Computer Vision
Deep Learning
Deployment

Image:

./assets/images/Face_mask.png

View Project link:

./projects/face-mask-deployment.html

View Code link:

https://github.com/alargam/face_mask_deployment

Project context:
Face mask detection system using computer vision and deep learning. The project includes model training/inference and deployment-ready structure.

Project 3

Title:

Medical X-Ray Super Resolution

Tags:

Medical AI
Image Enhancement
Deep Learning

Image:

./assets/images/xray-super-resolution.png

View Project link:

./projects/super-resolution-medical-xray.html

View Code link:

https://github.com/alargam/Super_Resolution_Medical_X-Ray_Image

Project context:
Medical image super-resolution using deep learning / GAN-based techniques. The project visually compares low-resolution X-ray input with enhanced output after model processing.

Project 4

Title:

Face Recognition Attendance System

Tags:

Face Recognition
Attendance Automation
OpenCV

Image:

./assets/images/face-recognition-attendance.png

View Project link:

./projects/smart-face-recognition-attendance.html

View Code link:

https://github.com/alargam/Smart_Face_Recognition_Attendance_System

Project context:
Real-time face recognition attendance system using OpenCV, LBPH, webcam recognition pipeline, GUI, and automated attendance logging.

10. Project Images / Thumbnail Style

Project images should stay visually consistent:

Black background
Professional AI/robotics look
Minimal
No unnecessary clutter
Same image frame size
Same alignment
Not stretched
Not cropped badly

The CSS should keep all project thumbnails inside a consistent frame:

.projects__picture {
  width: 100%;
  aspect-ratio: 4 / 3;
  background-color: #000;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  margin-block-end: 20px;
}

.projects__image {
  width: 100%;
  height: 100%;
  object-fit: contain;
  background-color: #000;
}

This was done so all project images stay aligned and same visual height.

11. Contact Section

The Contact section should sound confident and client-focused.

Current preferred text:

Have an AI, computer vision, automation, or software project in mind? Send me a message and let's discuss how I can help design, build, or improve a practical intelligent system for your idea, product, or business.

The contact form sends to:

alargam.yagoub@gmail.com

It uses FormSubmit AJAX endpoint:

action="https://formsubmit.co/ajax/alargam.yagoub@gmail.com"

The form should not redirect to FormSubmit page after submit.

It should use JavaScript fetch to submit and keep the user on the portfolio page.

Important hidden inputs:

<input type="hidden" name="_subject" value="New message from portfolio website" />
<input type="hidden" name="_template" value="table" />
<input type="hidden" name="_captcha" value="false" />

The JavaScript should:

Prevent default form submission
Show "Sending..."
Disable button while sending
Send request using fetch
Show "Message sent successfully!" if okay
Show error message if something fails
Reset form after success
12. GitHub / Production Deployment

The project was cloned originally from:

https://github.com/thecodercoder/fem-single-page-developer-portfolio

Then the remote was changed to:

https://github.com/alargam/portfolio.git

Important Git commands used:

git remote -v
git remote set-url origin https://github.com/alargam/portfolio.git
git push -u origin main

There was a 403 error before because the remote still pointed to the original template repository.

Then GitHub CLI was used for login:

sudo apt install gh
gh auth login
gh auth setup-git
git push -u origin main

GitHub Pages should be enabled from:

Repository Settings > Pages > Deploy from a branch > main > /root > Save
13. Known Issues / Things to Preserve

Do not remove:

Green underline under Alargam Osman
Green underline under About Me
Green underline under Skills
Green underline under Projects
Green underline under Contact
Project image sizing consistency
FormSubmit AJAX behavior
GitHub and LinkedIn icons
Relative image paths starting with ./assets/images/

Do not re-add:

The long hero paragraph under the name
Too many random social icons
Twitter icon
Frontend Mentor icon
Original Adam Keyes content
Original frontend projects from the template
14. Important CSS Concepts Currently Used

Section heading underline:

.section-heading__text {
  display: inline-block;
  background-image: linear-gradient(
    to right,
    var(--accent) 75%,
    var(--accent) 75%
  );
  background-position: 0 1.08em;
  background-repeat: repeat-x;
  background-size: 8px 4px;
}

Hero name underline:

.hero__name {
  display: inline-block;
  white-space: nowrap;
  background-image: linear-gradient(
    to right,
    var(--accent) 75%,
    var(--accent) 75%
  );
  background-position: 0 1.08em;
  background-repeat: repeat-x;
  background-size: 8px 4px;
}

Hero text vertical position on desktop:

@media (min-width: 62.5em) {
  .hero__text {
    margin-block-start: 150px;
    margin-right: 0;
    flex: 1;
  }
}

Skill size reduction:

.skills__title {
  font-size: clamp(1.65rem, 3vw, 2.35rem);
  line-height: 1.15;
  margin-block-end: 4px;
}

.skills__description {
  font-size: 0.9rem;
  line-height: 1.4;
}
15. Preferred Website Sections Order

The final website order should be:

Header / Navigation
Hero
About Me
Skills
Projects
Contact
Footer
16. Main Objective for Any Future AI Assistant

If you are an AI assistant helping with this project, your goal is to preserve the current identity and design direction:

This is not a generic frontend developer portfolio.

It is a production-ready portfolio for an AI Software Engineer specializing in:

Real-Time AI Systems
Computer Vision
Robotics
Edge AI
Embedded AI
Automation
Model deployment

Any edits should make the website look more professional, more confident, and more aligned with AI/Robotics engineering.

Do not weaken the language.
Do not make the website look like a beginner portfolio.
Do not remove project links, images, or contact functionality.
Do not break GitHub Pages relative asset paths.

17. Quick Prompt for Future Use

Use this prompt if you want another AI assistant to continue the project:

I have a static HTML/CSS/JS personal portfolio website for Alargam Mohamed Osman, displayed as Alargam Osman, an AI Software Engineer specializing in Artificial Intelligence, Computer Vision, Robotics, Edge AI, Real-Time AI Systems, Embedded AI, and Automation. The website is based on the TheCoderCoder single-page developer portfolio template but has been customized heavily.

The project uses index.html, style.css, assets/images, GitHub Pages, and FormSubmit AJAX for the contact form. It is deployed to https://github.com/alargam/portfolio and should use relative paths like ./assets/images/... because it runs on GitHub Pages under /portfolio/.

The website sections are: Hero, About Me, Skills, Projects, Contact, Footer. The visual style is dark, minimal, professional, with white text and green accent underlines. Keep the green underline under Alargam Osman, About Me, Skills, Projects, and Contact.

Hero content:
Hi, I'm
Alargam Osman
AI Software Engineer.
Contact me

Do not add a long paragraph under the Hero because About Me handles the detailed explanation.

About Me should describe Alargam as a strong Software Engineer specializing in AI, Computer Vision, Robotics, Edge AI, Automation, model deployment, and real-world intelligent systems.

Skills should include Python, Computer Vision, Deep Learning, Edge AI, Robotics, Embedded Systems, C++, Model Deployment, and Automation.

Projects:
1. Autonomous Mobile Robot — image AMR.png — code https://github.com/alargam/AMR_Robot
2. Face Mask Detection System — image Face_mask.png — code https://github.com/alargam/face_mask_deployment
3. Medical X-Ray Super Resolution — image xray-super-resolution.png — code https://github.com/alargam/Super_Resolution_Medical_X-Ray_Image
4. Face Recognition Attendance System — image face-recognition-attendance.png — code https://github.com/alargam/Smart_Face_Recognition_Attendance_System

Contact form uses action https://formsubmit.co/ajax/alargam.yagoub@gmail.com and JavaScript fetch to submit without redirecting away from the page.

Please help improve or modify the project without breaking the layout, relative paths, project images, GitHub Pages deployment, or contact form behavior.

End of project context.