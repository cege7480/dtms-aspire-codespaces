# DTMS.Aspire Codespaces

This repository contains the GitHub Codespaces configuration for the DTMS.Aspire project, enabling easy development environment setup.

## About DTMS.Aspire

DTMS.Aspire is a .NET application leveraging Microsoft's Aspire framework for building distributed applications. This project is focused on transportation management system capabilities built with modern cloud-native technologies.

## GitHub Codespaces Setup

This repository is configured to work with GitHub Codespaces, providing a fully configured development environment in the cloud.

### Codespace Specifications

The devcontainer is configured with the following resources:
- **CPU:** 8+ cores
- **Memory:** 16GB+ RAM
- **Storage:** 32GB

### Development Environment Features

The Codespace includes:
- .NET 8 SDK
- Required VS Code extensions
- Automatic port forwarding for local development
- Automatic project restoration on startup

## Getting Started

### Launch a Codespace

1. Click the "Code" button on the repository
2. Select the "Codespaces" tab
3. Click "Create codespace on main"

### Development Workflow

Once your Codespace is ready:
1. The environment will automatically run `dotnet restore` to set up dependencies
2. You can build and run the application with standard .NET commands
3. Use the integrated terminal for command-line operations
4. Changes can be committed directly from the Codespace

## CI/CD Pipeline

The repository includes a GitHub Actions workflow that:
- Builds the project on every push and pull request to main
- Runs tests to ensure code quality
- Creates build artifacts for deployment

## Contributing

When contributing to this repository, please:
1. Create a feature branch from main
2. Make your changes
3. Submit a pull request with a clear description of the changes

## Useful Commands

```bash
# Build the project
dotnet build

# Run tests
dotnet test

# Run the application
dotnet run --project DTMS.Aspire.AppHost
```
