# Cyber Banner Project

This project features a full-screen banner with a masked background effect, perfect for a cyberpunk-themed website or event. The banner includes a large title with custom font styling, and the background image is dynamically masked using an animated GIF.

## Features
- Full-screen banner that covers the entire viewport.
- A custom font (`Hallowed Grounds`) for the title.
- A dynamic background image masked with an animated GIF to create a unique visual effect.
- Flexbox layout for easy centering of the content.

## Technologies Used
- **HTML**: The structure and content of the page.
- **CSS**: Styling, including flexbox for layout, background masking, and custom fonts.

## Setup

To get started with this project, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/SRCarlo/cyber-banner.git
    ```

2. **Navigate to the project folder**:

    ```bash
    cd cyber-banner
    ```

3. **Add the required files**:
   - **bg.jpg**: Your background image file.
   - **ink_lv2.gif**: The animated mask file for the background.
   - **Hallowed Grounds font**: Make sure the custom font is linked properly, either by including it in a `@font-face` rule or via a CDN link.

4. **Open `index.html` in your browser** to see the banner in action.

## Customization

- **Change the title**: Modify the text inside the `.title` class in `index.html`.
- **Adjust font**: If you want to use a different font, change the `font-family` property in the `.title` class in `style.css` and link the new font accordingly.
- **Background Image**: You can replace `bg.jpg` with your own image for a custom background.

## License

This project is open-source and available under the [MIT License](LICENSE).
