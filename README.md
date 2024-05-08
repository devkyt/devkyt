```yaml
apiVersion: human/v30
kind: Man
metadata:
  name: Kyrylo Tykhanskyi
  labels:
    position: DevOps Engineer
    location: Germany, Dessau 

spec:
  replicas: 1
  status: vs The World
  template:
    spec:
      container:
          image: devkyt:stable
      languages:
          primary: Python
          secondary: Go
      hobbies:
          - software 
          - architecture
          - jogging
          - videogames
      securityContext:
          runAsNonRoot: false
```
