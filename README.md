# Demo test for helm library chart - app repo
- update lib chart version in Chart.yaml
- update dependency  
`helm dependency update demochart/`
- check for validity  
`helm install mydemo demochart/ --debug --dry-run`