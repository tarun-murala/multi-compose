# multi-compose

This Docker Compose consists of
1. Jenkins (on port: 2100)
2. Jira (on port: 2200)
3. BitBucket (on port: 2300)
4. GitLab (on port: 2400)
5. GitLab Runner (Confifured with GitLab)

Use the following commands to spin up the container(s)

```
   docker-compose up -d
```

To Shutdown

```
   docker-compose down
```

To pick a specific docker file
```
   docker-compose -f docker-compose-jira-jenkins-bb.yml up -d
```
