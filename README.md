# SPL Token Launchpad

This project is a launchpad for SPL tokens built using TypeScript and Solana's Program Library (SPL). The application allows users to create and manage token sales on the Solana blockchain, integrating several essential functionalities for deploying tokens and managing minting events.

## Features
- **Token Creation**: Issue SPL tokens directly from the interface.
- **Token Sale Management**: Manage sales, set prices, and track token distribution.
- **Solana Integration**: Leverages Solana's SPL for token minting and management.
- **Responsive UI**: Built with Tailwind CSS for modern, responsive design.

## Prerequisites
- Node.js (v16+)
- Solana CLI installed
- Phantom wallet (for interacting with the Solana network)
- A Solana devnet or testnet account funded with SOL

## Installation

1. Clone the repository:
    \`\`\`bash
    git clone https://github.com/whistledev411/spl-token-launchpad.git
    cd spl-token-launchpad
    \`\`\`

2. Install the dependencies:
    \`\`\`bash
    npm install
    \`\`\`

3. Set up your environment variables:
    - Copy \`.env.example\` to \`.env\` and fill in the required values.

4. Compile the project:
    \`\`\`bash
    npm run build
    \`\`\`

## Usage

1. Start the local development server:
    \`\`\`bash
    npm run dev
    \`\`\`

2. Open your browser and navigate to \`http://localhost:3000/`.

3. Connect your Phantom wallet to interact with the Solana network.

## Project Structure

- \`src/\`: Contains the core application logic.
- \`public/\`: Static assets.
- \`tailwind.config.ts\`: Tailwind CSS configuration.
- \`tsconfig.json\`: TypeScript configuration file.

## Contributing
Feel free to fork the repository and submit pull requests. Any contributions are welcome.

## License
This project is licensed under the MIT License.
