# AutoCon (AutoConverge)

AutoCon is an innovative project aimed at automating the software development process by leveraging a multi-agent system powered by AutoGen. Starting with a minimal codebase, AutoCon dynamically creates and manages agents to handle various aspects of software development, evolving in complexity as project demands grow. By emulating a real-world development team structure with distinct managerial hierarchies, AutoCon facilitates organized, efficient, and scalable project management.

## Features

- Dynamic agent creation and management.
- Multi-tiered managerial hierarchy.
- Modular project structure.
- Continuous Integration/Continuous Deployment (CI/CD) pipelines.
- Real-time monitoring and feedback loops.
- User-centric project management interface.
- Scalable to accommodate various project sizes and complexities.

## Directory Structure

```
AutoCon
├── autogen_config
│ ├── agent_definitions.py
│ ├── manager_definitions.py
│ └── system_config.py
|
├── src
│ ├── agents
│ │ ├── developer_agents.py
│ │ ├── manager_agents.py
│ │ ├── cicd_agent.py
│ │ └── …
│ ├── factories
│ │ └── agent_factory.py
│ ├── groups
│ │ └── conversation_groups.py
│ ├── user_interface
│ │ ├── static
│ │ ├── templates
│ │ └── app.py
│ └── …
|
├── tests
│ ├── test_agents.py
│ ├── test_factories.py
│ └── …
|
├── data
│ ├── project_definitions
│ ├── user_feedback
│ └── …
|
├── logs
│ ├── system_logs.txt
│ └── …
|
├── docs
│ ├── system_documentation.md
│ └── …
|
├── scripts
│ ├── initialization_script.py
│ └── …
│
└── main.py
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/AutoCon.git
cd AutoCon
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Run the initialization script:
```bash
python scripts/initialization_script.py
```
Start the main application:
```bash
python main.py
```

### Contributing:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes with meaningful commit messages.
- Create a pull request and describe the changes you’ve made.

### License

MIT License

### Contact

GitHub: @mattang-tde
Email: time@mattang.com
