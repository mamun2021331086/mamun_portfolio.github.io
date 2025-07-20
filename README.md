# Personal Portfolio Website

A clean, modern, and responsive single-page portfolio website built with HTML and CSS. This project is designed to showcase my skills, projects, and professional background as a student of Computer Science and Engineering.

## ✨ Features

* **Hero Section:** A welcoming introduction with name, title, and social media links.
* **About Section:** A detailed biography including academic information and interests.
* **Skills Section:** Visually represents programming language proficiency with animated progress bars.
* **Projects Section:** Highlights key projects with descriptions, tech used, learning outcomes, and a link to the source code.
* **Smooth Scrolling:** A fixed navigation bar allows for smooth scrolling between different sections of the page.
* **Modern Design:** A dark-themed, visually appealing layout with custom fonts and glowing effects.

## 📸 Screenshot

![A screenshot of the portfolio website's hero section, showing a dark theme with blue accents, a profile picture, and introductory text.](https://i.imgur.com/8Qj8m7L.png)

## 🚀 Live Demo

You can view a live version of the portfolio here: \[**ADD YOUR LIVE DEMO LINK HERE**]

## 🛠️ Technologies Used

* **HTML5:** For the structure and content of the website.
* **CSS3:** For styling, layout, animations, and the overall design.
* **Google Fonts:** Utilizes the 'Oswald' and 'Poppins' font families for clean typography.
* **Font Awesome:** For scalable vector icons (social media logos).

## 📂 Project Structure

The project has a simple and easy-to-understand file structure.
Of course. Here is the complete README file in raw Markdown language. You can copy and paste this code directly into a file named `README.md` in your project's root directory.

# Personal Portfolio Website

A clean, modern, and responsive single-page portfolio website built with HTML and CSS. This project is designed to showcase my skills, projects, and professional background as a student of Computer Science and Engineering.

## ✨ Features

* **Hero Section:** A welcoming introduction with name, title, and social media links.
* **About Section:** A detailed biography including academic information and interests.
* **Skills Section:** Visually represents programming language proficiency with animated progress bars.
* **Projects Section:** Highlights key projects with descriptions, tech used, learning outcomes, and a link to the source code.
* **Smooth Scrolling:** A fixed navigation bar allows for smooth scrolling between different sections of the page.
* **Modern Design:** A dark-themed, visually appealing layout with custom fonts and glowing effects.

## 📸 Screenshot

![A screenshot of the portfolio website's hero section, showing a dark theme with blue accents, a profile picture, and introductory text.](https://i.imgur.com/8Qj8m7L.png)

## 🚀 Live Demo

You can view a live version of the portfolio here: \[**ADD YOUR LIVE DEMO LINK HERE**]

## 🛠️ Technologies Used

* **HTML5:** For the structure and content of the website.
* **CSS3:** For styling, layout, animations, and the overall design.
* **Google Fonts:** Utilizes the 'Oswald' and 'Poppins' font families for clean typography.
* **Font Awesome:** For scalable vector icons (social media logos).

## 📂 Project Structure

The project has a simple and easy-to-understand file structure.

```

portfolio-project/
├── index.html       \# The main HTML file
├── style.css        \# The stylesheet for all the styling
└── images/
└── mm.jpg       \# The profile picture (or any other images)

````

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You only need a modern web browser (like Chrome, Firefox, or Edge).

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repository-name
    ```
3.  **Open the website:**
    Simply open the `index.html` file in your web browser.

## ✏️ How to Customize

You can easily customize this portfolio to make it your own.

1.  **Update Personal Information:**
    * Open `index.html`.
    * Change the name, title, and bio in the hero section (`<div class="content">`).
    * Update the "About Me" section (`<section class="about-section">`) with your details.

2.  **Change the Profile Picture:**
    * Place your photo (e.g., `my-photo.jpg`) inside the project folder (or an `images` subfolder).
    * Open `style.css`.
    * Find the `.circle:nth-child(2)` rule.
    * Change the `background-image` URL to point to your new picture:
        ```css
        .circle:nth-child(2) {
            /* ... other styles */
            background-image: url(path/to/your/my-photo.jpg); 
        }
        ```

3.  **Update Skills:**
    * In `index.html`, navigate to the "My Programming Skills" section (`<section id="Skills">`).
    * For each skill, you can change the name (e.g., `<p>C</p>`) and adjust your proficiency by changing the `width` percentage in the inline style of the `.bar` div:
        ```html
        <div class="skill">
          <p>JavaScript</p>
          <div class="skill-bar">
            <div class="bar" style="width: 90%;"></div> 
          </div>
        </div>
        ```

4.  **Add/Update Projects:**
    * In `index.html`, find the "My Project" section (`<section id="project">`).
    * Modify the content inside each `<div class="project-card">` for your projects.
    * Update the `<h3>` for the title, the `<p>` tags for the description, and the `href` in the `<a>` tag to link to your project's code or live demo.

5.  **Update Social Media Links:**
    * In `index.html`, find the `<div class="icon">` section.
    * Change the `href` attribute in each `<a>` tag to your social media profile URLs. You can add or remove icons from [Font Awesome](https://fontawesome.com/).
        ```html
        <a href="[https://www.linkedin.com/in/your-profile](https://www.linkedin.com/in/your-profile)" target="_blank">
          <i class="fa-brands fa-linkedin-in"></i>
        </a>
        ```

## 📫 Contact

Created by **Abdullah Al Mamun** - feel free to get in touch!

* Facebook: [@abdullah.al.mamun](https://www.facebook.com/profile.php?id=61557841255693)
* GitHub: [@mamun2021331086](https://github.com/mamun2021331086)
* Add other contact methods here (e.g., LinkedIn, Email).

## 📜 License

This project is open source. You are free to use and modify it. If you use it, a link back to the original repository is appreciated but not required.
