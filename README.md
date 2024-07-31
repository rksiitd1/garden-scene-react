# Garden Scene React

A charming and responsive React component that renders a delightful garden scene using SVG and Tailwind CSS.

## Live Demo

Experience the garden scene in action: [View Live Demo](https://rksiitd1.github.io/garden-scene-react/)

## Features

- 🌳 Responsive SVG garden scene
- 🎨 Styled with Tailwind CSS for easy customization
- ⚛️ Built with React for efficient rendering
- 📱 Fully responsive design
- 🌞 Dynamic elements including sun, clouds, trees, and flowers

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/rksiitd1/garden-scene-react.git
   ```

2. Navigate to the project directory:
   ```
   cd garden-scene-react
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Usage

Import the `GardenScene` component into your React application:

```jsx
import GardenScene from './components/GardenScene';

function App() {
  return (
    <div className="App">
      <GardenScene />
    </div>
  );
}
```

## Customization

The garden scene can be easily customized by modifying the SVG elements in the `GardenScene.js` file. Tailwind CSS classes are used for styling, allowing you to change the colors, layout, and other visual aspects of the scene by modifying the class names.

## Deployment

This project is deployed on GitHub Pages. To deploy your own version:

1. Update the `homepage` field in `package.json`:
   ```json
   "homepage": "https://yourusername.github.io/garden-scene-react"
   ```

2. Run the deploy script:
   ```
   npm run deploy
   ```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

---

Happy gardening with React! 🌻🌿