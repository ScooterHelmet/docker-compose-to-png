[![Generate Docker Compose Diagram](https://github.com/ScooterHelmet/docker-compose-to-png/actions/workflows/generate-diagram.yaml/badge.svg)](https://github.com/ScooterHelmet/docker-compose-to-png/actions/workflows/generate-diagram.yaml)
# docker-compose-to-png
This repository uses a Github Action to build graph visualizations of the root project's `docker-compose.yml` file. Graphviz is the underyling tool used to achieve this. However, the `.github/workflows/generate-diagram.yaml` file uses [pmsipilot/docker-compose-viz](https://github.com/pmsipilot/docker-compose-viz) to build the output. The output is then uploaded as an artifact. 
- Artifacts are downloadable once the `Generate Docker Compose Diagram` check has passed. 
   - 🔎`docker-compose-diagram` url downloads `.zip` containing the `.png`.

### Example
`https://github.com/ScooterHelmet/docker-compose-to-png/suites/12564666297/artifacts/671611992`

### Github Action Workflow
![Docker Compose Diagram](./docker-compose-to.png)
