# PerspectiveConfiguration

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Description

PerspectiveConfiguration is a powerful ChatGPT interface system that seamlessly integrates with Eloquence and Grace, two distinct assistant modes. This system offers a unique perspective on ChatGPT interactions, allowing users to choose between the two modes to tailor their experience.

## Features

- **Eloquence Mode**: Engage with ChatGPT in the eloquent and articulate style of the Eloquence Assistant.
- **Grace Mode**: Switch to Grace mode for a more graceful and refined conversation with ChatGPT.
- **Consistent Sessions**: Maintain consistent sessions with each assistant mode.
- **Structured Observation**: Capture and observe interactions in both Eloquence and Grace modes.
- **Simplified Coordination**: The Agent class efficiently coordinates interactions with the respective assistants.
- **Easy Integration**: Seamlessly incorporate PerspectiveConfiguration into your ChatGPT projects.

## Installation

To use PerspectiveConfiguration in your ChatGPT project, follow these steps:

1. Clone this repository.

## Usage

Here's how you can utilize PerspectiveConfiguration in your project:

1. Create an instance of the Agent class, providing your interaction string.
2. Specify the assistant mode (Eloquence or Grace) in the Agent constructor.
3. Access the structured observation data for in-depth analysis.

```csharp
// Example code snippet
Agent sol = new Agent("Your interaction string", false); // Choose Eloquence mode
sol.Initiate(); // Start the interaction
sol.Moon(); // Access structured observation data
