# Hotel Agent MCP Toolbox (Cloud SQL)

This project provides a toolbox agent designed to interface with Google Cloud SQL (Postgres) and related Google Cloud Platform (GCP) services, leveraging the Google ADK (Agent Development Kit) and AI Platform. The agent is intended to streamline data operations, automate workflows, and integrate advanced analytics or AI capabilities into SQL-powered environments.

## Features

- **Cloud SQL Integration:** Seamlessly interact with Google Cloud SQL (Postgres) datasets and tables.
- **AI Platform Extension:** Utilize AI Platform engines and agent capabilities for advanced analytics.
- **Cloud Storage Support:** Read from and write to Google Cloud Storage as part of your data workflows.
- **Extensible Toolbox:** Built on `toolbox-core` for modularity and reusability.

## Requirements

- Python 3.8+
- Google Cloud account with access to Cloud SQL, AI Platform, and Cloud Storage

Install dependencies:
```bash
pip install -r requirements.txt
```

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/rominirani/adk-projects.git
    cd adk-projects/7-bigquery-mcp-toolbox-agent
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. (Optional) Set up your Google Cloud credentials:
    ```bash
    export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/service-account-file.json"
    ```

## Usage

The agent is defined in `agent.py` and uses the MCP Toolbox to connect to a database.

1. Set up the MCP Toolbox as described in `instructions.txt`.
2. Run the agent (example):
```bash
python agent.py
```

## Configuration

- Ensure you have appropriate IAM roles for Cloud SQL, AI Platform, and Cloud Storage.
- Update any configuration files or environment variables as needed for your project.

## Contributing

Contributions are welcome! Please open issues or submit PRs for bug fixes, features, or enhancements.

## License

[MIT](../LICENSE) © 2025 rominirani

## Acknowledgements

- [Google ADK](https://github.com/google/adk)
- [Google Cloud Platform](https://cloud.google.com/)
- [toolbox-core](https://pypi.org/project/toolbox-core/)
