# Runner AI

Runner AI is an advanced, action-oriented Twitter bot designed to engage dynamically with topics related to speed, endurance, and the pursuit of goals. Utilizing cutting-edge GPT-4 Turbo, it generates and posts compelling content tailored to the Runner AI narrative—perfect for enthusiasts of momentum, progress, and high-energy pursuits.

Follow Runner AI Sample Usage on Twitter: [@RunnerAI](https://x.com/RunnerAI_SOL)

## Features

• Automatically analyzes trending topics and integrates dynamic charts to highlight momentum shifts.

• Posts content designed to energize followers, with visually engaging updates on "high runs" in performance or achievement.

• Highly configurable to post motivational quotes, training tips, or updates on trending topics related to running and self-improvement.

• Includes an optional performance tracker integration for enhanced engagement.

## Getting Started

To get started with Runner AI, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies using `npm` or `yarn`.
3. Set up your Twitter developer account and obtain API keys.
4. Configure the bot with your Twitter API keys and other credentials by creating a `.env` file and filling it with variables from `.env.example`.
5. Adjust the prompts in the `momentumPrompts` array to customize the bot’s content.
6. Launch the bot application to start posting high-energy, action-focused content!

### Modifying Prompts

To modify the prompts used by Runner AI, follow these steps:

1. Open the `momentum-prompts.constant.ts` file in the `src/constants` directory.
2. Locate the `momentumPrompts` array, which contains the prompts for various themes.
3. Each object in the `momentumPrompts` array represents a prompt for a specific theme.
4. Update the `prompt` property of each object to tailor the bot’s output.
5. Add new themes or remove existing ones to match your vision.
6. Save your changes and restart the bot application.

## Usage

Once configured and running, Runner AI will automatically post content based on its schedule. You can customize the frequency of posts by adjusting the Cron schedule in the `manage-tweet.service.ts` file.

## Contributing

If you'd like to contribute to Runner AI, feel free to submit pull requests with new features, bug fixes, or enhancements. Your input is invaluable and helps Runner AI evolve!

## License

This project is licensed under the MIT License.
