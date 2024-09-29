# Custom LinkedIn Banner Creator

This project allows you to create a personalized LinkedIn banner showcasing your GitHub contributions graph and professional information. Follow the steps below to customize the banner for your profile.

## My Banner

<img width="1438" alt="Screenshot 2024-09-28 at 10 07 02 PM" src="https://github.com/user-attachments/assets/6dba511b-471a-4da0-9073-51d676518741">

## Getting Started

1. Clone this repository or download the HTML and CSS files.
2. Open the project in your favorite code editor.

## Customization Steps

### 1. Update Personal Information

Open the `index.html` file and locate the `<div class="content">` section. Modify the following elements:

- Replace the title (`<h1>`) with your job title or professional headline.
- Update the paragraph (`<p>`) with your personal tagline or brief description.
- Change the email address to your contact email.

Example:

```html

  Full Stack Developer 👩‍💻
  Passionate about creating scalable web applications!
  
  Email: your.email@example.com

```

### 2. Add Your GitHub Contributions Graph

1. Go to your GitHub profile.
2. Right-click on your contributions graph and select "Save image as".
3. Save the image as "myContributions.png" in the same directory as your HTML file.
4. If you prefer a different file name, update the `src` attribute of the `<img>` tag in the HTML file:

```html

```

### 3. Customize Colors

Open the `styles.css` file to modify the color scheme:

- To change the background gradient, update the `background` property in the `.banner` class:

```css
.banner {
  background: linear-gradient(to right, #your-color-1, #your-color-2);
}
```

- To change text colors, update the `color` property in the `body, html` selector and the `.label p` selector.

### 4. Adjust Fonts

The banner uses the Poppins font by default. If you want to use a different font:

1. Replace the Google Fonts link in the `<head>` section of the HTML file with your chosen font.
2. Update the `font-family` property in the `body, html` selector in the CSS file.

### 5. Modify "Hire Me" Label

To change the "Hire Me" label, update the text in the `<div class="label">` section of the HTML file:

```html

  Your Custom Text

```

## Viewing Your Banner

Open the `index.html` file in a web browser to see your customized LinkedIn banner. You can take a screenshot of this page to use as your LinkedIn background image.

## Adding Your Banner to This README

After creating your custom banner:

1. Take a screenshot of your finished banner.
2. Save the screenshot in the project directory (e.g., as `banner-screenshot.png`).
3. Update the image link in this README file:

```md
![Custom LinkedIn Banner](path/to/your/banner-screenshot.png)
```

Replace `path/to/your/banner-screenshot.png` with the actual path to your screenshot file.

## Additional Customization

Feel free to further modify the HTML and CSS files to add more elements, change the layout, or adjust the styling to better fit your personal brand.

## License

This project is open source and available under the [MIT License](LICENSE).

Happy customizing!
