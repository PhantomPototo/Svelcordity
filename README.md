# Svelcordity

Svelcordity is a template repository with a simple setup for integrating your Discord Activity with SvelteKit. This project utilizes a Unity WebGL build to display your Discord activity seamlessly. As an example, a roguelike game built with Unity is included in this template.

## Features

- Easy integration of Discord Activity with SvelteKit
- Unity WebGL build for interactive content
- Minimal setup and configuration required
- Includes a [sample roguelike game built with Unity](https://github.com/Chizaruu/Unity-RL-Tutorial)

## Prerequisites

- Unity Editor
- Node.js
- npm (Node Package Manager)
- GitHub Desktop (optional, but recommended for easier repository management)

## Getting Started

To get started with Svelcordity, follow these steps:

1. Click the "Use this template" button on the GitHub repository page to create a new repository based on this template.

2. Clone your newly created repository using GitHub Desktop or the command line:
   ```
   git clone https://github.com/yourusername/your-repo-name.git
   ```

3. Navigate to the project directory:
   ```
   cd your-repo-name
   ```

4. Install the dependencies:
   ```
   npm install
   ```

5. Create a `.env` file in the root directory of the project and add your Discord application's `CLIENT_ID` and `CLIENT_SECRET` for server-side authentication:
   ```
   CLIENT_ID=your_client_id
   CLIENT_SECRET=your_client_secret
   ```

## Setting Up Unity WebGL

1. Open your Unity project and select the **WebGL** platform.

2. Set the WebGL Template to **Minimal**:
   - Go to **Edit** -> **Project Settings** -> **Player** -> **Resolution and Presentation**
   - Click **Minimal** under **WebGL Template**.

3. Build your Unity project and locate the generated `Build` folder.

## Configuration

1. Open your project's `lib` folder and set up your configuration file (`config.ts`) with the necessary details.

2. Copy the Unity `Build` folder you generated earlier and paste it into this project's `static` folder.

## Usage

1. Run the development server to test the project:
   ```
   npm run dev
   ```

2. Open your browser and visit `https://localhost:5173` to see your Discord Activity in action.

3. When you're ready to deploy, build the project:
   ```
   npm run build
   ```

4. Deploy the built files to your preferred hosting platform (e.g., Vercel, AWS, Azure) if you want to share your Discord Activity with others (Discord Proxy).

5. Enjoy your Discord Activity powered by SvelteKit and Unity WebGL!

## Example: Roguelike Game

This template includes a sample roguelike game built with Unity to demonstrate how to integrate a Unity WebGL build with SvelteKit. The game files are in the `static/Build` folder.

Feel free to replace the example game with your Unity WebGL build to showcase your Discord Activity.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

In the words of Todd Howard, it just works.
