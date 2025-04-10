# Wandelbots Robot Visualization

This example is using the [boilerplate](https://github.com/wandelbotsgmbh/wandelbots-js-boilerplate) for creating Wandelbots robot applications using [NextJS](https://nextjs.org/)

The example can be generated with the [CLI](https://portal.wandelbots.io/en/download).
```bash
$ nova app example get wandelbots-js-robot-visualization
```

<img width="100%" alt="Screenshot 2024-09-18 at 14 13 17" src="https://github.com/user-attachments/assets/2ae9e042-d3e4-4453-a9ee-48ce69e12786">

## Usage

**Note:** Please replace `<controller_id>` with the controller name you've selected and `<motion_group_id>` with the motion group ID in `src/templates/RobotVisualization/example.ws`

Example:
  - "0@abb" = get_controller("abb")[0]
  - "1@fanuc" = get_controller("fanuc")[1]

For more information about wandelscript you can have a look into [our docs](https://docs.dev.wandelbots.io/25.4/wandelscript/quickstart/).
