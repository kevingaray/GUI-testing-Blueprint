# GUI-testing-Blueprint
This repository serves as an addition to the organization's project originally hosted privately in a [GitHub repo](https://github.com/Dam24/GUI-testing). Here, you will find comprehensive information and resources that provide valuable context for the project.
## About
The GUI-testing Blueprint project was developed as part of the QA Automation Bootcamp. It focuses on performing comprehensive testing related to Blueprint, an internal application property of Jalasoft that allows users to create workflows business processes. This service provides a graphical interface that allows users to design workflows by connecting different steps and actions.  

<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/47c0ca8f-0fb6-43ed-9952-ae7c7550e2f9" width="500">  
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/2cf5e890-c9d7-4cb9-96f3-f2780e855377" width="500">  

To ensure efficient and agile testing practices, we used [Jira](https://www.atlassian.com/es/software/jira) to define the sprints and keep a track of the task  
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/a8ab9e25-bfe3-4997-bca4-abec61dca6f6" width="500">

To automate and streamline the testing process, we set [Jenkins](https://www.jenkins.io/) Jobs to run the test automatically every day at certain hour and with different resolutions.   
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/59f3b16c-d1a0-4f1c-8142-fc540f8efaf1" width="500">

### Scope
At the core of Blueprint lies its principal feature known as "Flows" that allows users to create a form and a flow  

<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/0562d9ed-85aa-44fd-a378-927ea995843a" width="350">

## Technologies
The project incorporates various technologies to support its development and testing processes. The following technologies are utilized:
| Technology            | Tool                                   |
|-----------------------|----------------------------------------|
| Language              | Python                                 |
| Core library          | Selenium                               |
| Test framework        | Robot                                  |
| Browsers              | Chrome  / Edge                         |
| Pipeline              | Jenkins                                |
| Scrum                 | Jira                                   |

## Testing Techniques
- Included
  - Acceptance testing
  - Functional testing
  - E2E testing
  - Boundary Testing
- Not included
  -  Non-functional testing (stress,load,performance)

## Conventions
- Python: When naming classes, PascalCase is used. For methods and variables, snake_case is employed
- Robot: snake_case for variables, and test titles with each first of all words letter capitalize , and should include tags

## Architecture: POM
![image](https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/3cb6624e-afe6-488a-b129-443e48f8d8da)

## Demo E2E
https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/81450a08-5463-4314-be81-5a827a0839ed


## Some Bugs Found
1. Hidden flow components when resolution changes
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/ff6b4fc4-79d1-485e-82c4-dd0349fd3b5b"  width="450">  
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/3965b57f-ad99-4f68-8f41-46c2f0ad0d1b"  width="450">  

2. "Create" button on "Create Flow" modal should be disabled until Flow name and code are verified  
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/494f4782-928a-4265-bedd-f2a04d713132" width="250">




## Robot Reports

### Chrome default resolution (full screen)
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/ba59114f-a945-4405-9813-50224bc7f435"  width="450">

### Chrome monitor 14 inches dimension
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/757505f4-2d03-4746-9054-3c474bc4408c"  width="450">

### Chrome Iphone 12 dimension
<img src="https://github.com/kevingaray/GUI-testing-Blueprint/assets/48739137/0fafb50d-f6b5-45f5-99ff-70cbb603c523"  width="450">



