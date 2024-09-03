# My UI Components

A collection of reusable UI components for React applications.

## Installation

To install the package, run the following command in your project directory:

```bash
npm install my-ui-components
```

## Usage

Here's a basic example of how to use the `Button` component:

```jsx
import React from "react";
import { Button } from "my-ui-components";

function App() {
  return (
    <div>
      <h1>Welcome to My App</h1>
      <Button variant="primary">Click me</Button>
    </div>
  );
}

export default App;
```

## Available Components

### Button

A customizable button component with different variants.

#### Props

| Prop      | Type                     | Default   | Description                                               |
| --------- | ------------------------ | --------- | --------------------------------------------------------- |
| variant   | "primary" \| "secondary" | "primary" | The variant of the button.                                |
| className | string                   | ""        | Additional class names to be added to the button element. |
| children  | React.ReactNode          | undefined | The content of the button.                                |

Plus all standard HTML button props.

#### Example

```jsx
<Button variant="secondary" onClick={() => console.log("Clicked!")}>
  Secondary Button
</Button>
```

## Customization

You can customize the styles of the components by overriding the default styles in your own CSS file.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Support

If you encounter any problems or have any questions, please open an issue in the GitHub repository.
