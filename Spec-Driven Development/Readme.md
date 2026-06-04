Reference: https://github.com/github/spec-kit

1. Install UV package manager
curl -LsSf https://astral.sh/uv/install.sh | sh
 
2. Install specify tool
uv tool install specify-cli --from git+ https://github.com/github/spec-kit.git@v0.8.12
 
3. Run setup
specify init . --integration copilot
 
Relaunch VS code, and check multiple folders under .github. Also in copilot chat window, where you select models, you can see new agents named speckit.*
Reference : GitHub - github/spec-kit: 💫 Toolkit to help you get started with Spec-Driven Development
 
/speckit.constitution analyse project and create the constitution
/speckit.specify        # Define what we want to build (requirements and user stories)
/speckit.clarify        # Clarify underspecified areas
/speckit.plan           # Create technical implementation plans with our chosen tech stack
/speckit.tasks          # Generate actionable task lists for implementation
/speckit.analyze        # Cross-artifact consistency & coverage analysis
/speckit.implement      # Execute all tasks to build the feature according to the plan
