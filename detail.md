# Developer Challenge: Vue.js Web Application with Docker

## Objective
We are looking for a Vue.js developer to create a web application that consists of three distinct screens. The application should be containerized using Docker and should be up and running on port 8080 when the `docker-compose up` command is executed.

## Requirements

### Screen 1: Text Manipulation Tool
- Create a text manipulation tool with the primary feature of swapping letters within words.
- The key functionality is the grouping of letters within the words. The size of these groups should be modifiable by the user.
- For example, if the group size is set to 2, the transformation would be as follows:
    - Input: "testing" -> Output: "ettsnig"
- Similarly, for a group size of 3:
    - Input: "testing" -> Output: "setnitg"

### Screen 2: Image Tool
- Implement an image tool that adjusts the brightness of a specific area within an uploaded image.
- Users should be able to specify the coordinates (x, y) and dimensions (width, height) of the area to be adjusted.
- For instance, adjusting the brightness of a 500x500 area starting from the coordinates (100, 100).

![example.png](https://i.ibb.co/mcPWNsb/example.png)

### Screen 3: Data Retrieval and Processing
- Fetch and process data from the specified endpoint: `https://pokeapi.co/api/v2/pokemon/`

## Submission Guidelines
- The web application must be fully functional within a Docker container.
- Provide clear documentation on how to set up and run the application.
- Ensure that all dependencies are properly managed through Docker.

Good luck with your innovative solution to this challenge!
