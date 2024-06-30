# JavaScript-Styled TypeScript

This project demonstrates TypeScript with a JavaScript coding style, allowing for a more flexible typing approach while still leveraging TypeScript's benefits.

## Features

- TypeScript configuration that allows for JavaScript-like coding style
- Minimal setup for quick start
- GitHub Actions CI for automated builds

## Getting Started

### Prerequisites

- Node.js (latest LTS version recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/k-taro56/javascript-styled-typescript.git
   ```

2. Navigate to the project directory:
   ```
   cd javascript-styled-typescript
   ```

3. Install dependencies:
   ```
   npm install
   ```

### Usage

To build the project:

```
npm run build
```

This will compile the TypeScript files and output the result to the `dest` directory.

## Configuration

The project uses a custom TypeScript configuration to allow for a more JavaScript-like coding style. Key settings include:

- `"noImplicitAny": false`: Allows variables to be implicitly typed as `any`
- `"strict": true`: Enables all strict type-checking options, except where explicitly overridden

For more details, see the `tsconfig.json` file.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.
